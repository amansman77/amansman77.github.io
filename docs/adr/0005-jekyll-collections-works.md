# ADR-005: 프로젝트 케이스 스터디를 위한 Jekyll Collections 도입

## 상태
승인됨

## 컨텍스트
포트폴리오에서 프로젝트 케이스 스터디를 체계적으로 관리해야 합니다. 각 프로젝트별로 상세한 정보를 제공하고, 새로운 프로젝트를 쉽게 추가할 수 있는 구조가 필요했습니다.

## 결정
Jekyll Collections를 사용하여 `_works` 컬렉션을 생성했습니다.

## 결과

### 긍정적 영향
- **구조화된 관리**: 프로젝트별 독립적인 파일
- **자동 생성**: URL과 메타데이터 자동 처리
- **확장성**: 새로운 프로젝트 쉽게 추가
- **일관성**: 통일된 프로젝트 구조

### 부정적 영향
- **파일 구조 복잡성**: 컬렉션 디렉토리 관리
- **학습 곡선**: Jekyll Collections 개념 이해 필요

## 구현 세부사항

### 1. 컬렉션 설정 (_config.yml)
```yaml
collections:
  works:
    output: true
    permalink: /:collection/:name/
    sort_by: date
    sort_order: reverse
```

### 2. 프로젝트 파일 구조
```
_works/
├── hiparking-migration.md
├── tradlinx-ai-pivot.md
├── fxgear-cyworld.md
└── ai-platform-development.md
```

### 3. 프로젝트 파일 템플릿
```markdown
---
layout: default
title: "프로젝트명"
date: 2024-01-01
category: "백엔드"
tech_stack: ["Spring Boot", "MSA"]
---

## 문제 상황
...

## 해결 방안
...

## 결과
...

## 역할 및 인사이트
...
```

## 대안

### 단일 파일 관리
- **장점**: 단순함
- **단점**: 파일 크기 증가, 관리 어려움

### 외부 CMS
- **장점**: 전문적 관리
- **단점**: 의존성, 비용

### 정적 파일
- **장점**: 단순함
- **단점**: 메타데이터 관리 어려움

## 프로젝트 구조

### 1. 메타데이터
- **title**: 프로젝트명
- **date**: 완료일
- **category**: 분야 (백엔드, DevOps, AI)
- **tech_stack**: 사용 기술

### 2. 콘텐츠 구조
- **문제 상황**: 해결해야 할 문제
- **해결 방안**: 기술적 접근
- **결과**: 비즈니스 임팩트
- **역할 및 인사이트**: 개인적 기여와 학습

### 3. 자동 생성 기능
- **URL**: `/works/project-name/`
- **네비게이션**: 자동 메뉴 생성
- **검색**: 프로젝트별 검색 가능
