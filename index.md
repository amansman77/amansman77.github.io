---
layout: home
title: "황호성 - 백엔드 개발자 & Tech Lead"
description: "만 {{ 'now' | date: '%Y' | minus: 2012 }}년차 백엔드 개발자 황호성입니다. Spring Boot, MSA, DevOps, AI 전문가로 안정적이고 확장 가능한 백엔드 시스템을 구축합니다."
---

<div class="hero-section">
  <div class="hero-content">
    <h1 class="hero-title">안정적이고 확장 가능한 백엔드 시스템을 구축하세요</h1>
    <p class="hero-subtitle">만 {{ 'now' | date: '%Y' | minus: 2012 }}년차 백엔드 개발자 황호성과 함께 귀사의 비즈니스 성장을 위한 최적의 솔루션을 만들어보세요.</p>
    <div class="hero-cta">
      <a href="/contact/" class="btn btn-primary btn-large">프로젝트 의뢰하기</a>
      <a href="/services/" class="btn btn-secondary btn-large">서비스 보기</a>
    </div>
  </div>
</div>

<div class="value-proposition">
  <div class="container">
    <h2>왜 황호성과 함께해야 할까요?</h2>
    <div class="value-grid">
      <div class="value-item">
        <div class="value-icon">🚀</div>
        <h3>{{ 'now' | date: '%Y' | minus: 2012 }}년의 실전 경험</h3>
        <p>기획부터 운영까지 전 주기 개발 경험을 보유한 개발자로, 실시간 대규모 트래픽 대응과 MSA 전환 등 실전 중심의 기술 적용에 강점이 있습니다.</p>
      </div>
      <div class="value-item">
        <div class="value-icon">⚡</div>
        <h3>검증된 기술 스택</h3>
        <p>Spring Boot, Java, Node.js, Python을 활용한 고성능 API 개발과 AWS, Kubernetes 기반의 확장 가능한 인프라 구축 경험을 보유하고 있습니다.</p>
      </div>
      <div class="value-item">
        <div class="value-icon">🎯</div>
        <h3>AI/ML 전문성</h3>
        <p>Triton/Torch Inference Server 운영 경험과 GPT 기반 AI 도입 경험을 바탕으로 AI 모델 서빙 환경을 안정적으로 구축할 수 있습니다.</p>
      </div>
      <div class="value-item">
        <div class="value-icon">👥</div>
        <h3>팀 리딩 경험</h3>
        <p>TDD·DDD 기반 리팩토링과 코드리뷰 문화 확산 등 개발 조직의 성장에도 기여해왔으며, 기술을 통한 사용자 경험 개선과 팀워크 중심의 협업을 중요 가치로 삼고 있습니다.</p>
      </div>
    </div>
  </div>
</div>

<div class="services-preview">
  <div class="container">
    <h2>주요 서비스</h2>
    <div class="services-grid">
      <div class="service-card">
        <h3>백엔드 시스템 구축</h3>
        <p>MSA 기반의 유연하고 확장 가능한 시스템 설계 및 Spring Boot/Java/Node.js를 활용한 고성능 API 개발</p>
        <ul>
          <li>시스템 아키텍처 설계</li>
          <li>API 개발 및 최적화</li>
          <li>데이터베이스 모델링</li>
          <li>성능 튜닝</li>
        </ul>
      </div>
      <div class="service-card">
        <h3>AI/ML 서비스 개발</h3>
        <p>AI 모델 서빙 아키텍처 설계 및 추론 API 개발, 데이터 전처리 파이프라인 구축</p>
        <ul>
          <li>AI 모델 서빙 환경 구축</li>
          <li>추론 API 개발</li>
          <li>데이터 파이프라인 구축</li>
          <li>Document AI PoC</li>
        </ul>
      </div>
      <div class="service-card">
        <h3>DevOps & Tech Lead</h3>
        <p>CI/CD 파이프라인 구축, 컨테이너 오케스트레이션, 모니터링 시스템 도입 및 개발팀 리딩</p>
        <ul>
          <li>CI/CD 파이프라인 구축</li>
          <li>Kubernetes/Docker 환경</li>
          <li>모니터링 시스템 설정</li>
          <li>개발팀 멘토링</li>
        </ul>
      </div>
    </div>
    <div class="services-cta">
      <a href="/services/" class="btn btn-outline">모든 서비스 보기</a>
    </div>
  </div>
</div>

<div class="recent-work">
  <div class="container">
    <h2>최근 프로젝트</h2>
    <div class="work-grid">
      {% assign sorted_works = site.works | sort: "date" | reverse %}
      {% for work in sorted_works limit:3 %}
        <div class="work-item">
          <h3><a href="{{ work.url }}">{{ work.title }}</a></h3>
          <p class="work-date">{{ work.date | date: "%Y년 %m월" }}</p>
          <p>{{ work.description | truncate: 150 }}</p>
          <a href="{{ work.url }}" class="read-more">자세히 보기 →</a>
        </div>
      {% endfor %}
    </div>
    <div class="work-cta">
      <a href="/work/" class="btn btn-outline">모든 프로젝트 보기</a>
    </div>
  </div>
</div>

<div class="cta-section">
  <div class="container">
    <h2>프로젝트를 시작할 준비가 되셨나요?</h2>
    <p>더 자세한 서비스 정보와 프로젝트 사례를 확인해보세요.</p>
    <div class="cta-buttons">
      <a href="/services/" class="btn btn-primary btn-large">서비스 보기</a>
      <a href="/about/" class="btn btn-secondary btn-large">더 알아보기</a>
    </div>
  </div>
</div>

<style>
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 80px 0;
  text-align: center;
}

.hero-content {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 20px;
}

.hero-title {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
  line-height: 1.2;
}

.hero-subtitle {
  font-size: 1.25rem;
  margin-bottom: 2rem;
  opacity: 0.9;
  line-height: 1.6;
}

.hero-cta {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.value-proposition {
  padding: 80px 0;
  background: #f8f9fa;
}

.value-proposition h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.value-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  max-width: 1200px;
  margin: 0 auto;
}

.value-item {
  text-align: center;
  padding: 2rem;
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.value-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.value-item h3 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #333;
}

.value-item p {
  color: #666;
  line-height: 1.6;
}

.services-preview {
  padding: 80px 0;
}

.services-preview h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.service-card {
  padding: 2rem;
  border: 1px solid #e9ecef;
  border-radius: 12px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.service-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
}

.service-card h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.service-card p {
  color: #666;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.service-card ul {
  list-style: none;
  padding: 0;
}

.service-card li {
  padding: 0.5rem 0;
  color: #666;
  position: relative;
  padding-left: 1.5rem;
}

.service-card li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #28a745;
  font-weight: bold;
}

.services-cta {
  text-align: center;
}

.recent-work {
  padding: 80px 0;
  background: #f8f9fa;
}

.recent-work h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.work-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.work-item {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.work-item h3 {
  margin-bottom: 0.5rem;
}

.work-item h3 a {
  color: #333;
  text-decoration: none;
}

.work-item h3 a:hover {
  color: #667eea;
}

.work-date {
  color: #666;
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

.work-item p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.read-more {
  color: #667eea;
  text-decoration: none;
  font-weight: 500;
}

.read-more:hover {
  text-decoration: underline;
}

.work-cta {
  text-align: center;
}

.cta-section {
  padding: 80px 0;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-align: center;
}

.cta-section h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.cta-section p {
  font-size: 1.25rem;
  margin-bottom: 2rem;
  opacity: 0.9;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 12px 24px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

.btn-primary {
  background: #667eea;
  color: white;
  border-color: #667eea;
}

.btn-primary:hover {
  background: #5a6fd8;
  border-color: #5a6fd8;
  transform: translateY(-2px);
}

.btn-secondary {
  background: transparent;
  color: white;
  border-color: white;
}

.btn-secondary:hover {
  background: white;
  color: #667eea;
  transform: translateY(-2px);
}

.btn-outline {
  background: transparent;
  color: #667eea;
  border-color: #667eea;
}

.btn-outline:hover {
  background: #667eea;
  color: white;
  transform: translateY(-2px);
}

.btn-large {
  padding: 16px 32px;
  font-size: 1.1rem;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

@media (max-width: 768px) {
  .hero-section {
    padding: 60px 0;
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    margin-left: 0 !important;
    margin-right: 0 !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    box-sizing: border-box;
  }
  
  .hero-content {
    width: 100% !important;
    max-width: 100% !important;
    padding: 0 20px !important;
    margin: 0 auto !important;
  }
  
  .hero-title {
    font-size: 2rem;
  }
  
  .hero-subtitle {
    font-size: 1.1rem;
  }
  
  .hero-cta, .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .value-grid, .services-grid, .work-grid {
    grid-template-columns: 1fr;
  }
  
  .container {
    width: 100% !important;
    max-width: 100% !important;
    padding: 0 20px !important;
    margin: 0 auto !important;
  }
}
</style>
