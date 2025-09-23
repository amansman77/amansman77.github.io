# ADR-004: 반응형 디자인을 위한 CSS Grid/Flexbox 활용

## 상태
승인됨

## 컨텍스트
포트폴리오가 다양한 디바이스에서 일관된 사용자 경험을 제공해야 합니다. 모바일, 태블릿, 데스크톱에서 최적화된 레이아웃이 필요했습니다.

## 결정
CSS Grid와 Flexbox를 조합하여 반응형 디자인을 구현했습니다.

## 결과

### 긍정적 영향
- **반응형 레이아웃**: 모든 디바이스에서 최적화된 표시
- **유연한 그리드**: 콘텐츠에 따른 자동 조정
- **성능**: CSS만으로 구현하여 JavaScript 의존성 없음
- **유지보수성**: 명확한 CSS 구조

### 부정적 영향
- **브라우저 호환성**: 구형 브라우저 지원 제한
- **복잡성**: CSS 구조 복잡도 증가

## 구현 세부사항

### 1. CSS Grid (메인 레이아웃)
```css
.hero-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  align-items: center;
}

@media (max-width: 768px) {
  .hero-grid {
    grid-template-columns: 1fr;
  }
}
```

### 2. Flexbox (컴포넌트 레이아웃)
```css
.card-container {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.card {
  flex: 1 1 300px;
  min-width: 0;
}
```

### 3. 반응형 브레이크포인트
```css
/* 모바일 */
@media (max-width: 768px) { }

/* 태블릿 */
@media (min-width: 769px) and (max-width: 1024px) { }

/* 데스크톱 */
@media (min-width: 1025px) { }
```

## 대안

### CSS Framework (Bootstrap, Tailwind)
- **장점**: 빠른 개발, 일관된 디자인
- **단점**: 커스터마이징 제한, 번들 크기

### JavaScript 기반 반응형
- **장점**: 동적 조정 가능
- **단점**: 성능 오버헤드, SEO 불리

### 별도 모바일 사이트
- **장점**: 최적화된 모바일 경험
- **단점**: 유지보수 부담, 중복 코드

## 디자인 시스템

### 1. 그리드 시스템
- **12컬럼 그리드**: 유연한 레이아웃
- **간격 시스템**: 0.5rem, 1rem, 2rem, 4rem
- **브레이크포인트**: 768px, 1024px

### 2. 컴포넌트 레이아웃
- **카드**: Flexbox 기반 유연한 크기
- **네비게이션**: 모바일에서 햄버거 메뉴
- **히어로**: Grid 기반 2컬럼 레이아웃

### 3. 타이포그래피
- **반응형 폰트**: clamp() 함수 활용
- **라인 높이**: 가독성 최적화
- **여백**: 일관된 간격 시스템
