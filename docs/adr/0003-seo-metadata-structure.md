# ADR-003: SEO 최적화를 위한 메타데이터 구조 설계

## 상태
승인됨

## 컨텍스트
포트폴리오의 검색엔진 최적화를 위해 구조화된 메타데이터가 필요합니다. 개인 브랜딩, 기술 커뮤니티 노출, 포트폴리오 검증을 위한 SEO 전략이 필요했습니다.

## 결정
다층적 SEO 메타데이터 구조를 설계했습니다.

## 결과

### 긍정적 영향
- **검색 노출**: 개인명, 기술 스택으로 검색 시 노출
- **소셜 공유**: Open Graph, Twitter Cards로 풍부한 미리보기
- **구조화된 데이터**: 검색엔진이 콘텐츠 이해 향상
- **사이트맵**: 자동 생성으로 크롤링 최적화

### 부정적 영향
- **복잡성**: 메타데이터 관리 부담
- **중복**: 여러 곳에서 동일한 정보 관리

## 구현 세부사항

### 1. 기본 메타데이터 (_config.yml)
```yaml
seo:
  type: "Person"
  name: "황호성"
  description: "만 {{ 'now' | date: '%Y' | minus: 2012 }}년차 백엔드 개발자"
```

### 2. Open Graph 메타데이터
```html
<meta property="og:title" content="황호성 - 백엔드 개발자 & Tech Lead">
<meta property="og:description" content="만 13년차 백엔드 개발자">
<meta property="og:type" content="profile">
```

### 3. 구조화된 데이터 (JSON-LD)
```json
{
  "@type": "Person",
  "name": "황호성",
  "jobTitle": "백엔드 개발자",
  "description": "만 13년차 백엔드 개발자"
}
```

### 4. 사이트맵 자동 생성
```yaml
plugins:
  - jekyll-sitemap
```

## 대안

### 수동 메타데이터 관리
- **장점**: 단순함
- **단점**: 일관성 부족, 유지보수 어려움

### 외부 SEO 도구
- **장점**: 전문적 관리
- **단점**: 비용, 의존성

## SEO 전략

### 1. 개인 브랜딩
- "황호성" 검색 시 전문성 어필
- LinkedIn, GitHub 연동

### 2. 기술 커뮤니티
- "Spring Boot 전문가", "MSA 전문가" 검색 노출
- 기술 블로그 연동

### 3. 포트폴리오 검증
- 이력서 링크 클릭 시 전문성 확인
- 신뢰도 구축
