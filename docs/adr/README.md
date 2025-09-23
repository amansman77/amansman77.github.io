# Architecture Decision Records (ADR)

이 디렉토리는 포트폴리오 프로젝트의 중요한 아키텍처 결정사항들을 기록합니다.

## ADR 목록

- [ADR-001: Jekyll 기반 정적 사이트 생성기 선택](0001-jekyll-static-site-generator.md)
- [ADR-002: Liquid 템플릿을 통한 동적 콘텐츠 구현](0002-liquid-dynamic-content.md)
- [ADR-003: SEO 최적화를 위한 메타데이터 구조 설계](0003-seo-metadata-structure.md)
- [ADR-004: 반응형 디자인을 위한 CSS Grid/Flexbox 활용](0004-responsive-design-css.md)
- [ADR-005: 프로젝트 케이스 스터디를 위한 Jekyll Collections 도입](0005-jekyll-collections-works.md)
- [ADR-006: 폼 제출을 위한 Formspree 대신 mailto 링크 선택](0006-mailto-instead-of-formspree.md)
- [ADR-007: 네비게이션 활성 상태 관리를 위한 Liquid 조건문 활용](0007-navigation-active-state.md)

## ADR 템플릿

새로운 ADR을 작성할 때는 다음 템플릿을 사용하세요:

```markdown
# ADR-XXX: [제목]

## 상태
[제안됨 | 승인됨 | 거부됨 | 대체됨]

## 컨텍스트
[문제 상황과 이 결정을 내리게 된 배경]

## 결정
[내린 결정]

## 결과
[이 결정의 결과, 긍정적/부정적 영향]

## 대안
[고려했던 다른 옵션들과 왜 선택하지 않았는지]
```
