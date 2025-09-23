# ADR-001: Jekyll 기반 정적 사이트 생성기 선택

## 상태
승인됨

## 컨텍스트
포트폴리오 사이트를 구축하기 위해 정적 사이트 생성기를 선택해야 했습니다. GitHub Pages와의 호환성, SEO 최적화, 유지보수성, 그리고 개발자 친화적인 환경이 필요했습니다.

## 결정
Jekyll을 정적 사이트 생성기로 선택했습니다.

## 결과

### 긍정적 영향
- **GitHub Pages 네이티브 지원**: 별도 빌드 설정 없이 자동 배포
- **Liquid 템플릿**: 동적 콘텐츠 생성 가능 (경력 계산 등)
- **SEO 플러그인**: jekyll-seo-tag, jekyll-sitemap 등 풍부한 생태계
- **Markdown 지원**: 콘텐츠 작성의 편의성
- **컬렉션 기능**: 프로젝트 케이스 스터디 관리

### 부정적 영향
- **Ruby 의존성**: 로컬 개발 환경 설정 복잡성
- **빌드 시간**: 대용량 사이트에서 느린 빌드 속도
- **플러그인 제한**: GitHub Pages에서 지원하지 않는 플러그인 사용 불가

## 대안

### Next.js
- **장점**: React 기반, SSR/SSG 지원, 성능 최적화
- **단점**: GitHub Pages와의 호환성 문제, 복잡한 배포 설정

### Hugo
- **장점**: 빠른 빌드 속도, Go 기반
- **단점**: GitHub Pages와의 제한적 호환성, 학습 곡선

### Gatsby
- **장점**: GraphQL, 플러그인 생태계
- **단점**: 복잡한 설정, GitHub Pages와의 호환성 문제

## 구현 세부사항

```yaml
# _config.yml
plugins:
  - jekyll-sitemap
  - jekyll-seo-tag

collections:
  works:
    output: true
    permalink: /:collection/:name/
```
