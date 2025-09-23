# ADR-007: 네비게이션 활성 상태 관리를 위한 Liquid 조건문 활용

## 상태
승인됨

## 컨텍스트
사용자가 현재 어느 페이지에 있는지 명확하게 표시해야 합니다. 네비게이션에서 활성 상태를 시각적으로 구분할 수 있는 방법이 필요했습니다.

## 결정
Liquid 조건문을 사용하여 현재 페이지에 `active` 클래스를 동적으로 적용했습니다.

## 결과

### 긍정적 영향
- **사용자 경험**: 현재 위치 명확한 표시
- **접근성**: 시각적 피드백 제공
- **일관성**: 모든 페이지에서 동일한 동작
- **유지보수성**: 자동화된 상태 관리

### 부정적 영향
- **템플릿 복잡성**: Liquid 조건문 추가
- **성능**: 페이지별 조건문 처리

## 구현 세부사항

### 1. 네비게이션 템플릿 (_includes/navigation.html)
```html
<nav class="site-nav">
  <ul>
    <li><a href="{{ '/' | relative_url }}" 
           {% if page.url == '/' %}class="active"{% endif %}>홈</a></li>
    <li><a href="{{ '/services/' | relative_url }}" 
           {% if page.url == '/services/' %}class="active"{% endif %}>서비스</a></li>
    <li><a href="{{ '/work/' | relative_url }}" 
           {% if page.url == '/work/' %}class="active"{% endif %}>프로젝트</a></li>
    <li><a href="{{ '/about/' | relative_url }}" 
           {% if page.url == '/about/' %}class="active"{% endif %}>소개</a></li>
    <li><a href="{{ '/contact/' | relative_url }}" 
           {% if page.url == '/contact/' %}class="active"{% endif %}>연락처</a></li>
  </ul>
</nav>
```

### 2. CSS 스타일링 (assets/css/custom.css)
```css
.site-nav a.active {
  color: var(--primary-color);
  background: rgba(102, 126, 234, 0.15);
  font-weight: 600;
}

.site-nav a.active::after {
  content: '';
  position: absolute;
  bottom: -0.5rem;
  left: 50%;
  transform: translateX(-50%);
  width: 4px;
  height: 4px;
  background: var(--primary-color);
  border-radius: 50%;
}
```

### 3. 컬렉션 페이지 처리
```html
<!-- 프로젝트 페이지의 경우 -->
{% if page.url contains '/works/' %}class="active"{% endif %}
```

## 대안

### JavaScript 기반
- **장점**: 동적 처리 가능
- **단점**: SEO 불리, 초기 로딩 시 깜빡임

### 수동 클래스 추가
- **장점**: 단순함
- **단점**: 각 페이지마다 수동 설정 필요

### CSS :target 선택자
- **장점**: CSS만으로 구현
- **단점**: URL 해시 의존성

### 프레임워크 기반
- **장점**: 자동화된 상태 관리
- **단점**: Jekyll과 호환성 문제

## 확장 가능성

### 1. 다중 레벨 네비게이션
```html
<!-- 서브메뉴 활성 상태 -->
{% if page.url contains '/works/' %}class="active"{% endif %}
```

### 2. 브레드크럼
```html
<!-- 현재 경로 표시 -->
{% assign path_parts = page.url | split: '/' %}
{% for part in path_parts %}
  {% if part != '' %}
    <span>{{ part }}</span>
  {% endif %}
{% endfor %}
```

### 3. 모바일 네비게이션
```css
@media (max-width: 768px) {
  .site-nav a.active {
    background: var(--primary-color);
    color: white;
  }
}
```

## 접근성 고려사항

### 1. ARIA 속성
```html
<nav aria-label="메인 네비게이션">
  <a href="/" aria-current="page">홈</a>
</nav>
```

### 2. 키보드 네비게이션
```css
.site-nav a:focus {
  outline: 2px solid var(--primary-color);
  outline-offset: 2px;
}
```

### 3. 스크린 리더 지원
```html
<span class="sr-only">현재 페이지</span>
```
