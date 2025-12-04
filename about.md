---
layout: page
title: "소개"
permalink: /about/
description: "만 {{ 'now' | date: '%Y' | minus: 2012 }}년차 백엔드 개발자 황호성의 소개 및 경력"
---

<div class="about-hero">
  <div class="container">
    <h1>안녕하세요, 황호성입니다</h1>
    <p>만 {{ 'now' | date: '%Y' | minus: 2012 }}년차 백엔드 개발자이자 Tech Lead로서, 기획부터 운영까지 전 주기 개발 경험을 보유하고 있습니다.</p>
  </div>
</div>

<div class="about-content">
  <div class="container">
    <div class="intro-section">
      <p><strong>{{ 'now' | date: '%Y' | minus: 2012 }}년 {{ 'now' | date: '%m' | minus: 2 }}개월</strong>의 개발 경험을 보유한 백엔드 개발자이자 <strong>Tech Lead</strong>로서, 기획부터 운영까지 전 주기 개발 경험을 보유하고 있습니다.</p>
      <p>실시간 대규모 트래픽 대응과 MSA 전환, GPT 기반 AI 도입 등 실전 중심의 기술 적용에 강점이 있으며, TDD·DDD 기반 리팩토링과 코드리뷰 문화 확산 등 개발 조직의 성장에도 기여해왔습니다.</p>
    </div>

    <div class="core-competencies">
      <h2>🎯 핵심 역량</h2>
      
      <div class="competencies-grid">
        <div class="competency-card">
          <div class="competency-icon">👥</div>
          <h3>개발 조직 성장</h3>
          <ul>
            <li><strong>TDD 도입</strong>: 테스트 커버리지 0% → 27% 확보</li>
            <li><strong>코드리뷰 문화</strong>: 비신뢰기반 개발문화를 신뢰기반으로 개선</li>
            <li><strong>팀 리딩</strong>: 파트원들의 업무 만족도 및 개발능력 향상</li>
          </ul>
        </div>
        
        <div class="competency-card">
          <div class="competency-icon">🚀</div>
          <h3>대규모 서비스 운영</h3>
          <ul>
            <li><strong>500만 회원 데이터 처리</strong> 경험</li>
            <li><strong>200만 회원 대상 Push 발송</strong> (6시간 소요)</li>
            <li><strong>150만명의 휴면 해제와 신규 가입 처리</strong> (일주일간)</li>
          </ul>
        </div>
        
        <div class="competency-card">
          <div class="competency-icon">⚡</div>
          <h3>기술 혁신</h3>
          <ul>
            <li><strong>Java → NodeJS 전환</strong> 프로젝트 리드</li>
            <li><strong>Multi Cloud 전환</strong>: AWS RDS를 Multi Cloud 기반 MariaDB Cluster로 전환</li>
            <li><strong>AI 도입</strong>: ChatGPT & Azure Document AI를 활용한 Document AI PoC 완료</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="career-section">
      <h2>💼 주요 경력</h2>
      
      <div class="career-timeline">
        <div class="career-item current">
          <div class="career-header">
            <h3>하이파킹 (2024.11 ~ 현재)</h3>
            <span class="position">책임연구원</span>
            <span class="company-info">주차장 운영사업 중심의 모빌리티 HUB 기업 (매출액: 1727억, 종업원수: 928명)</span>
          </div>
          <div class="career-content">
            <ul>
              <li><strong>Java → NodeJS 전환</strong>: 기존 Java 기반 서비스를 NodeJS로 전환 중</li>
              <li><strong>Multi Cloud 전환</strong>: AWS RDS(MariaDB)를 Multi Cloud 기반 MariaDB Cluster로 전환</li>
              <li><strong>모니터링 시스템</strong>: MariaDB 및 Java 서비스의 Connection Pool 모니터링 툴 제공</li>
              <li><strong>주차 도메인 기능</strong>: 정기권, 할인, 주차 통제 외부 연동 개발</li>
            </ul>
          </div>
        </div>

        <div class="career-item">
          <div class="career-header">
            <h3>트레드링스 (2023.04 ~ 2024.10)</h3>
            <span class="position">개발팀 매니저</span>
            <span class="company-info">수출입 물류 플랫폼 기업 (누적 투자금: 90억, 종업원수: 49명)</span>
          </div>
          <div class="career-content">
            <div class="career-subsection">
              <h4>개발팀 짐고 프로덕트 팀장 (2023.12 ~ 2024.10)</h4>
              <ul>
                <li><strong>서비스 모델 피봇</strong>: 견적중심에서 선적중심으로 2달간 3명의 개발자와 함께 전환</li>
                <li><strong>Global 서비스</strong>: 선적 노트 프로젝트 (2명), 정기 결제 프로젝트 (6명) Tech Advisor 역할</li>
                <li><strong>Document AI PoC</strong>: ChatGPT & Azure Document AI를 활용한 선적 문서 정보 추출 (정확도 90%+, 비용 $9/이미지)</li>
                <li><strong>ChatGPT 활용</strong>: 물도도(물류 도메인 도우미), HSCode 도우미 사내 서비스 제공</li>
                <li><strong>개발 프로세스</strong>: Git-flow에서 Github-flow로 전환하여 릴리즈 주기 개선</li>
              </ul>
            </div>
            <div class="career-subsection">
              <h4>개발팀 짐고 프로덕트 개발자 (2023.04 ~ 2023.11)</h4>
              <ul>
                <li><strong>TDD 도입</strong>: 테스트 커버리지 0% → 27% 확보</li>
                <li><strong>OOP & DDD 리팩토링</strong>: 파편화된 개념을 응집하도록 리팩토링</li>
                <li><strong>조직 성장</strong>: 코드리뷰 문화 활성화, 사내 함께 읽기 모임 주도</li>
                <li><strong>성과</strong>: 비신뢰기반 개발문화를 신뢰기반으로 개선</li>
              </ul>
            </div>
          </div>
        </div>
        <!-- 나머지 경력들은 간소화하여 표시 -->
        <div class="career-item">
          <div class="career-header">
            <h3>FXGear (2021.09 ~ 2023.03)</h3>
            <span class="position">백엔드 파트 리더</span>
            <span class="company-info">AR, VR, 디지털 휴먼 서비스 제공 XR 기업 (매출: 42억, 종업원수: 80명)</span>
          </div>
          <div class="career-content">
            <ul>
              <li><strong>대국민 서비스</strong>: 싸이월드 재출시 프로젝트 참여</li>
              <li><strong>대규모 트래픽</strong>: 오픈시 일주일동안 150만명의 휴면 해제와 신규 가입 처리</li>
              <li><strong>회원 관리</strong>: 500만명 회원의 정보 관리</li>
              <li><strong>서비스 운영</strong>: Push 발송, Email 발송, 결제 및 도토리 서비스 운영</li>
            </ul>
          </div>
        </div>
        
        <div class="career-item">
          <div class="career-header">
            <h3>AI 플랫폼 개발 (2019.06 ~ 2021.08)</h3>
            <span class="position">AI 서비스플랫폼팀 책임</span>
            <span class="company-info">엔키스, 지어소프트, 엠아이큐브솔루션</span>
          </div>
          <div class="career-content">
            <ul>
              <li><strong>DataLake 플랫폼</strong>: Springboot + VueJS 관리 서비스, Python 데이터 처리 파이프라인</li>
              <li><strong>AI O&M 플랫폼</strong>: Triton Inference 서버, Tensorflow/PyTorch 모델 통합 검증</li>
              <li><strong>Edge AI 플랫폼</strong>: 라즈베리파이 K3S 클러스터, NVIDIA Jetson NANO 활용</li>
              <li><strong>MLOps 플랫폼</strong>: Kubernetes CPU/GPU 클러스터, Gitlab CI/CD, Prometheus & Grafana</li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="tech-stack-section">
      <h2>🛠️ 기술 스택</h2>
      
      <div class="tech-stack">
        <div class="tech-category">
          <h3>Backend Development</h3>
          <div class="tech-items">
            <span class="tech-item">Java</span>
            <span class="tech-item">Spring Boot</span>
            <span class="tech-item">JPA</span>
            <span class="tech-item">QueryDSL</span>
            <span class="tech-item">Python</span>
            <span class="tech-item">Django</span>
            <span class="tech-item">NodeJS</span>
          </div>
        </div>
        
        <div class="tech-category">
          <h3>Architecture & Cloud</h3>
          <div class="tech-items">
            <span class="tech-item">MSA</span>
            <span class="tech-item">Event Driven Architecture</span>
            <span class="tech-item">DDD</span>
            <span class="tech-item">AWS</span>
            <span class="tech-item">Kubernetes</span>
            <span class="tech-item">Docker</span>
          </div>
        </div>
        
        <div class="tech-category">
          <h3>Database & Middleware</h3>
          <div class="tech-items">
            <span class="tech-item">PostgreSQL</span>
            <span class="tech-item">MariaDB</span>
            <span class="tech-item">Oracle</span>
            <span class="tech-item">MongoDB</span>
            <span class="tech-item">Redis</span>
            <span class="tech-item">ElasticSearch</span>
            <span class="tech-item">Kafka</span>
          </div>
        </div>
        
        <div class="tech-category">
          <h3>AI & ML</h3>
          <div class="tech-items">
            <span class="tech-item">Triton</span>
            <span class="tech-item">Torch</span>
            <span class="tech-item">ChatGPT</span>
            <span class="tech-item">Azure Document AI</span>
            <span class="tech-item">MLOps</span>
          </div>
        </div>
        
        <div class="tech-category">
          <h3>DevOps & Monitoring</h3>
          <div class="tech-items">
            <span class="tech-item">Gitlab</span>
            <span class="tech-item">Jenkins</span>
            <span class="tech-item">Prometheus</span>
            <span class="tech-item">Grafana</span>
            <span class="tech-item">Zabbix</span>
            <span class="tech-item">ELK Stack</span>
          </div>
        </div>
      </div>
    </div>

    <div class="education-section">
      <h2>📚 교육 및 자격</h2>
      
      <div class="education-grid">
        <div class="education-card">
          <h3>학력</h3>
          <ul>
            <li><strong>금오공과대학교</strong> 컴퓨터공학과 졸업 (4.05/4.5)</li>
            <li><strong>원곡고등학교</strong> 이공계 졸업</li>
          </ul>
        </div>
        
        <div class="education-card">
          <h3>자격증</h3>
          <ul>
            <li><strong>정보처리기사</strong> (2011.06)</li>
            <li><strong>OCP</strong> (2011.02)</li>
          </ul>
        </div>
        
        <div class="education-card">
          <h3>병역</h3>
          <ul>
            <li><strong>해군 현역 병장</strong> 만기제대 (2006.05 ~ 2008.06)</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="values-section">
      <h2>🌟 핵심 가치</h2>
      
      <div class="values-grid">
        <div class="value-card">
          <div class="value-icon">🤝</div>
          <h3>협업과 소통</h3>
          <p><strong>사람</strong>, <strong>관계</strong>, <strong>협업</strong>, <strong>효율</strong>에 관심이 많아 자연스럽게 supporter 역할을 합니다. 팀원들이 만족할 수 있는 업무 환경을 함께 만드는 것을 중요하게 생각하며, 코드리뷰 문화 확산 및 지속적인 학습 환경 조성에 기여합니다.</p>
        </div>
        
        <div class="value-card">
          <div class="value-icon">📈</div>
          <h3>지속적인 성장</h3>
          <p>slow starter로서 꾸준한 학습과 성장을 추구합니다. 새로운 기술과 방법론에 대한 열린 마음을 가지고 있으며, TDD, DDD 등 최신 개발 방법론 도입 및 팀 확산에 앞장섭니다.</p>
        </div>
        
        <div class="value-card">
          <div class="value-icon">💎</div>
          <h3>가치 창출</h3>
          <p>단순한 개발을 넘어서 비즈니스 가치를 창출하는 것을 목표로 합니다. 사용자와 고객에게 실질적인 도움이 되는 서비스를 만드는 것을 추구하며, 대규모 트래픽 처리 및 안정적인 서비스 운영 경험을 바탕으로 합니다.</p>
        </div>
      </div>
    </div>

    <div class="contact-section">
      <h2>📞 연락처</h2>
      <p>새로운 프로젝트나 협업 기회가 있으시다면 언제든 연락주세요!</p>
      
      <div class="contact-info">
        <div class="contact-item">
          <strong>이메일</strong>: amansman77@gmail.com
        </div>
        <div class="contact-item">
          <strong>GitHub</strong>: <a href="https://github.com/amansman77" target="_blank">github.com/amansman77</a>
        </div>
        <div class="contact-item">
          <strong>LinkedIn</strong>: <a href="https://www.linkedin.com/in/hosung-hwang-916046184" target="_blank">linkedin.com/in/hosung-hwang-916046184</a>
        </div>
        <div class="contact-item">
          <strong>블로그</strong>: <a href="https://yeti.tistory.com/" target="_blank">yeti.tistory.com</a>
        </div>
        <div class="contact-item">
          <strong>입사가능시기</strong>: 확정 후 4주 이내
        </div>
      </div>
    </div>

    <div class="cta-section">
      <h2>함께 가치있는 서비스를 만들어가요!</h2>
      <a href="/contact/" class="btn btn-primary btn-large">프로젝트 의뢰하기</a>
    </div>
  </div>
</div>

<style>
.about-hero {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 80px 0;
  text-align: center;
}

.about-hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.about-hero p {
  font-size: 1.25rem;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto;
}

.about-content {
  padding: 80px 0;
}

.intro-section {
  text-align: center;
  margin-bottom: 4rem;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.intro-section p {
  font-size: 1.1rem;
  line-height: 1.8;
  color: #666;
  margin-bottom: 1rem;
}

.core-competencies {
  margin: 4rem 0;
}

.core-competencies h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.competencies-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.competency-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
}

.competency-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.competency-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.competency-card h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.competency-card ul {
  margin: 0;
  padding-left: 1.5rem;
  text-align: left;
}

.competency-card li {
  margin-bottom: 0.5rem;
  line-height: 1.6;
  color: #666;
}

.career-section {
  margin: 4rem 0;
}

.career-section h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.career-timeline {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

.career-item {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.career-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.career-item.current {
  border-left: 4px solid #667eea;
}

.career-header {
  background: #f8f9fa;
  padding: 1.5rem;
  border-bottom: 1px solid #e9ecef;
}

.career-header h3 {
  margin: 0 0 0.5rem 0;
  color: #333;
  font-size: 1.3rem;
}

.position {
  display: inline-block;
  background: #667eea;
  color: white;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 500;
  margin-bottom: 0.5rem;
}

.company-info {
  display: block;
  color: #666;
  font-size: 0.9rem;
  margin-top: 0.5rem;
}

.career-content {
  padding: 1.5rem;
}

.career-subsection {
  margin-bottom: 1.5rem;
}

.career-subsection:last-child {
  margin-bottom: 0;
}

.career-subsection h4 {
  color: #333;
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.career-content ul {
  margin: 0;
  padding-left: 1.5rem;
}

.career-content li {
  margin-bottom: 0.5rem;
  line-height: 1.6;
  color: #666;
}

.tech-stack-section {
  margin: 4rem 0;
}

.tech-stack-section h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.tech-stack {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.tech-category {
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 12px;
  text-align: center;
}

.tech-category h3 {
  color: #333;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

.tech-items {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  justify-content: center;
}

.tech-item {
  background: #667eea;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.3s ease;
}

.tech-item:hover {
  background: #764ba2;
  transform: translateY(-2px);
}

.education-section {
  margin: 4rem 0;
}

.education-section h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.education-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.education-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.education-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.education-card h3 {
  color: #333;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.education-card ul {
  margin: 0;
  padding-left: 1.5rem;
}

.education-card li {
  margin-bottom: 0.5rem;
  line-height: 1.6;
  color: #666;
}

.values-section {
  margin: 4rem 0;
}

.values-section h2 {
  text-align: center;
  margin-bottom: 3rem;
  font-size: 2.5rem;
  color: #333;
}

.values-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.value-card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
}

.value-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
}

.value-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.value-card h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.value-card p {
  color: #666;
  line-height: 1.6;
  margin: 0;
}

.contact-section {
  margin: 4rem 0;
  text-align: center;
}

.contact-section h2 {
  margin-bottom: 1rem;
  font-size: 2.5rem;
  color: #333;
}

.contact-section p {
  font-size: 1.1rem;
  color: #666;
  margin-bottom: 2rem;
}

.contact-info {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1rem;
  max-width: 800px;
  margin: 0 auto;
}

.contact-item {
  padding: 1rem;
  background: #f8f9fa;
  border-radius: 8px;
  text-align: left;
}

.contact-item a {
  color: #667eea;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}

.cta-section {
  text-align: center;
  padding: 60px 40px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-radius: 12px;
  margin: 4rem 0;
}

.cta-section h2 {
  font-size: 2.5rem;
  margin-bottom: 2rem;
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
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
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
  .about-hero {
    padding: 60px 0;
  }
  
  .about-hero h1 {
    font-size: 2rem;
  }
  
  .about-content {
    padding: 60px 0;
  }
  
  .container {
    padding: 0 20px !important;
  }
  
  .post-title,
  .post-header,
  .post-content {
    padding-left: 0;
    padding-right: 0;
  }
  
  .competencies-grid,
  .values-grid {
    grid-template-columns: 1fr;
  }
  
  .education-grid {
    grid-template-columns: 1fr;
  }
  
  .contact-info {
    grid-template-columns: 1fr;
  }
  
  .tech-stack {
    grid-template-columns: 1fr;
  }
}
</style>