# 👋 Kim Soyeon

<p align="center">
  <a href="https://www.instagram.com/soyuuuuuni/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white"/></a>
  <a href="mailto:thdus1770@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

I am a **Backend-focused Fullstack Developer** passionate about designing scalable systems, building end-to-end web applications, and creating real-world impactful services with AI and distributed technologies.

I enjoy bridging **backend architecture ↔ frontend experience**, and I specialize in **Spring Boot, Java, MySQL, Redis, Kafka, Vue.js, FastAPI**, and distributed system design.

---

# 🎓 Education & Experience

**B.S. in Computer Information & Communication Engineering, Chonnam National University**  
*Mar 2023 — Feb 2025*

**Samsung SW·AI Academy For Youth 13th (Java Track)**  
*Jan 2025 — Nov 2025*

**IT Intern, Construction Workers Mutual Aid Association (CWMA)**  
*Nov 2025 — Apr 2026*

---

# 🚀 Projects 

## 📌 Speakle — 팝송 기반 영어 학습 & 추천 웹 서비스  
**2025.09 ~ 2025.10 | 팀 프로젝트(6인)**

Qwen 임베딩되어 있는 가사 데이터, weaviate를 이용해 AI 기반으로 가사를 분석하고, 학습자 수준별로 단어·표현·문장 학습을 지원하며  
개인 맞춤형 팝송 추천까지 제공하는 영어 학습 플랫폼입니다.

- **기술 스택:** FastAPI, Python, Weaviate(Vector DB), PostgreSQL, Vue.js, Spotify API, LLM, Docker  
- **담당 역할:** 전체 시스템 설계, 빅데이터 추천 시스템 개발(weaviate, EDA, 데이터 전처리), 백엔드/AI 파이프라인 개발, 벡터 검색 시스템 구축, UI/UX 설계  
- **성과:**  
  - Spotify API + LLM 기반 팝송 추천 알고리즘 구현  
  - Weaviate 벡터 DB 기반 가사 임베딩·유사도 검색 구조 설계  
  - 가사 학습 모듈(단어·표현·문장 난이도 태깅) 개발  
  - 장문의 가사를 여러 단계로 Chunking → Embedding → 학습 카드 자동 생성  
  - Docker Compose로 전체 스택 컨테이너라이징
  - SSAFY 빅데이터 추천 프로젝트 최우수상(1등) 수상
- **특징:** 실전 수준의 ML 파이프라인, 추천 시스템, 벡터 검색 기반 서비스 아키텍처를 직접 구축한 AI + 웹서비스 프로젝트

---

## 📌 ZIPZIP — 부동산 통합 웹 플랫폼  
**2025.04 ~ 2025.05 | 팀 프로젝트(2인)**

실거래가·등기·커뮤니티·상권 데이터를 통합하여 부동산 사기 예방 및 매물 탐색을 지원하는 웹 서비스입니다.

- **기술 스택:** Spring Boot, Java, MySQL, Redis, Vue.js, Spring AI, JWT  
- **담당 역할:** 백엔드 개발, 전체 UI/UX 설계, Vue.js 프론트엔드 구현  
- **성과:**  
  - 공공데이터 기반 실거래·등기·상권 데이터를 연결하는 백엔드 아키텍처 설계  
  - Spring AI 기반 뉴스 요약, Redis 기반 챗봇 기능 개발  
  - JWT 회원 인증, 마이페이지, 지역 위험도 분석 기능 구현  
  - GitHub 브랜치 전략·PR 리뷰 기반 협업 경험 축적
- **영상:** https://youtu.be/6d4JpQGmMJ0?si=A_MskkXpHkZPP1uJ

---

## 📌 참견도치 — 실시간 AI 갈등 중재 서비스  
**2025.07 ~ 2025.08 | 팀 프로젝트(6인)**

WebRTC·Kafka·Redis·LLM을 결합하여 실시간 갈등 중재와 대화 분석을 제공하는 서비스입니다.

- **기술 스택:** Spring Boot, Java, MySQL, Kafka, Redis, SSE, WebRTC, Vue.js, JWT  
- **담당 역할:** Kafka 이벤트 설계, Redis SSE, WebRTC, 백엔드 개발, UI/UX 설계, PM  
- **성과:**  
  - WebRTC 기반 실시간 화상 스트리밍 및 대화 분석 파이프라인 구축  
  - Kafka 기반 실시간 이벤트 처리 구조 설계  
  - Redis SSE를 적용하여 안정적인 실시간 데이터 전송 구현  
  - LLM 기반 대화 요약·감정 분석 리포트 생성 기능 설계  
  - 스프린트 관리·PR 리뷰·브랜치 전략 등 PM 역할 수행
  - SSAFY 웹서비스 프로젝트 우수상(2등) 수상
- **문서:** https://www.notion.so/AI-2510b21b2383808a8c44f46de4a68507?pvs=21

---

## 📌 Joying — 렌탈·에스크로 기반 실거래 플랫폼  
**2025 | 팀 프로젝트(6인)**

대여 요청부터 결제, 배송, 반납, 정산까지 전체 실거래 흐름을 구현한 렌탈 서비스 플랫폼입니다.

- **기술 스택:** Spring Boot, JPA, MySQL, Redis, EC2, Jenkins, Docker, Vue.js, JWT, MongoDB, Elastic Search  
- **담당 역할:** 시스템 아키텍처 설계, 백엔드 API, 결제·에스크로 구조 설계&개발, 도메인 모델링  
- **성과:**  
  - Toss Payments 기반 결제·에스크로 연동  
  - Redis 기반 세션/캐시·상태 저장 구조 설계  
  - 비관적 lock, outbox pattern, circuit breaker 등 안정적인 트랜잭션 처리 고려한 결제 시스템   
  - 실거래 프로세스 기반 엔티티 설계 및 전체 대여·반납 프로세스 개발
  - SSAFY 자율(최종) 프로젝트 우수상(3등) 수상

---

## 📌 SOLSOL DX — 장학금 지급·신청 프로세스 자동화 플랫폼  
**2025.08 | 팀 프로젝트(4인)**

장학금 지급, 신청, 검증, 관리 절차를 자동화한 웹 기반 DX 시스템입니다.
신한은행 해커톤 본선 진출 프로젝트입니다.

- **기술 스택:** Spring Boot, Java, MySQL, Python, FastAPI, Vue.js  
- **담당 역할:** API 설계, 신청·심사·승인 단계 도메인 분석, 관리자, 마이박스 기능 개발  
- **성과:**  
  - 장학금 처리 프로세스 자동화로 수작업 감소 및 업무 효율 개선  
  - 신청–검증–승인–지급 파이프라인 설계  
  - 실제 기관 업무를 모티브로 한 DX 시스템 구축 경험 확보(신한은행 헤이영 캠퍼스 앱과 연동)  

---

## 📌 다회용기 리워드 플랫폼 — 친환경 소비 장려 서비스  
**2023.09 ~ 2024.06 | 3인 캡스톤 디자인**

다회용기 사용을 장려하기 위해 포인트 적립·리워드 지급 구조로 설계된 친환경 플랫폼입니다.

- **기술 스택:** React, Python, Django, Figma  
- **담당 역할:** 전체 UI/UX 설계, React 프론트 개발, 백엔드 일부 기여  
- **성과:**  
  - 사용자 경험 중심 UI/UX 디자인 및 반응형 구현  
  - 팀 협업 기반 GitHub 버전 관리 및 API 명세 설계  
  - 졸업 논문 산출물 제작  

---

## 📌 SEC-FTP — RSA·AES 기반 보안 파일 전송 시스템  
**2024.11 ~ 2024.12 | 팀 프로젝트(3인)**

RSA 공개키 교환과 AES 대칭키 암호화를 활용한 보안 파일 전송 프로토콜 구현 프로젝트입니다.

- **기술 스택:** C, OpenSSL, TCP Socket, Ubuntu  
- **담당 역할:** 서버 인증·대칭키 교환 로직·암호화 명령 송수신 구현  
- **성과:**  
  - 실제 보안 프로토콜 구조를 이해하고 직접 설계  
  - 인증 로직 설계 및 예외 처리 구현  
  - OpenSSL 기반 암호화 통신 실습 경험 확보  
- **문서:** https://www.notion.so/SEC-FTP-20b0...

---

## 📌 TimeSaver — 대학생 시간표 추천 서비스  
**2023.03 ~ 2023.06 | 팀 프로젝트(5인)**

공강·희망 과목 조건을 기반으로 시간표를 추천하는 웹 서비스입니다.

- **기술 스택:** C, HTML/CSS, React, Flask  
- **담당 역할:** UI/UX 설계 및 프론트엔드 구현  
- **성과:** 기획–디자인–개발 전 과정을 경험하며 협업 역량 강화  
- **링크:** https://github.com/soyuuuuuni/timesaver

---

# 🛠 Tech Stack

### **Backend**
Java • Spring Boot • Spring MVC • Spring AI  
Python • FastAPI

### **Database / Storage**
MySQL • PostgreSQL • Redis • Weaviate (Vector DB)

### **Architecture / Infra**
Kafka • Docker • Linux • JWT • REST API • WebRTC • SSE

### **Frontend**
Vue.js • HTML/CSS • JavaScript

### **DevOps / Tools**
Git • GitHub • Figma • OpenVidu

---

# 📊 GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=soyuuuuuni&show_icons=true&theme=dark"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=soyuuuuuni&layout=compact&theme=dark"/>
</p>

![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/soyuuuuuni&title=visit)

---

# 📫 Contact

📧 Email — **thdus1770@gmail.com**  
📸 Instagram — **@soyuuuuuni**

