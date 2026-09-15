# 💼 포트폴리오 (Portfolio)

## ✉️ Contact & Links
* **Email:** beautiyj@naver.com
* **GitHub:** [github.com/beautiyj](https://github.com/beautiyj)
* **Youtube:** [Channel](https://youtube.com/channel/UCytaNKIpHrPVVYnA3D1469Q?si=E2B3tnPvIstcqNYF)
* **Naver Blog:** [Blog](https://blog.naver.com/beautiyj)
* **Instagram:** [Instagram](https://www.instagram.com/beautiyj)
* **X(Twitter):** [X](https://twitter.com/char_ming_xoxo?t=v48kbu3QYkA33QK-GLUYCg&s=09)

## 🛠️ Skill Set

* **Frontend**
  + **Framework / Library:** React (Vite, React Router, Tailwind CSS), Android Compose (Kotlin, Camera2 API)
  + **Language:** JavaScript, HTML, CSS, JSX, Kotlin

* **Backend**
  + **Framework:** Spring Boot (Spring Data JPA, QueryDSL, Spring Security), Django
  + **Language & Tool:** Java, Python, Gradle

* **AI & Vector / Vision**
  + **AI Framework:** Spring AI (Ollama 기반 LLM / RAG 연동), Gemini & OpenAI API
  + **Computer Vision & DL:** OpenCV, MediaPipe (제스처 인식), PyTorch *(기초)*, TensorFlow / Keras *(기초)*
  + **Database & Vector Engine:** PostgreSQL (pgvector 코사인 유사도), MySQL, SQLite, Oracle

* **Infrastructure & DevTools**
  + **DevOps:** Docker, Docker Compose, GitHub Actions (CI), Linux, WSL2
  + **Tools:** Git, GitHub, Notion, Jira, Figma, IntelliJ, PyCharm, DataGrip, DBeaver, VS Code, Postman, Swagger

## 🐾 Education & Background
* **중앙정보처리학원 이대캠퍼스** 2026.03 ~ 2026.09
  + 클라우드 기반 프론트엔드&백엔드 자바(JAVA) 풀스택 개발자 취업 캠프 9기
  + 자바 및 스프링 부트 기반 백엔드 개발, 리액트 활용 프론트엔드 개발, 데이터베이스 연동 경험
  + Docker 및 AWS를 활용한 인프라 구축과 웹 사이트 배포 학습, Spring AI 기반 LLM 및 클라우드 데브옵스 학습
  + Java, Spring Boot, Spring AI, HTML, CSS, JavaScript, React, Oracle, MySQL, PostgreSQL, Docker, AWS EC2

* **청년취업사관학교(용산캠퍼스/서울경제진흥원)** 2025.06.30 ~ 2025.12.10
  + 비트컴퓨터 AIoT 앱/서비스 개발자 양성 취업캠프 4기
  + 장고 기반 웹사이트 개발, 안드로이드 컴포즈 기반 앱 개발, 머신러닝과 딥러닝 학습, AWS 활용 배포
  + Python, Kotlin, GitHub, Django, Android Compose, PyTorch, TensorFlow, OpenCV, MediaPipe, RAG 활용 LLM

<br><br>

---

## 🏆 팀 프로젝트 (Team Projects)

### [팀 프로젝트] 대학생 취창업 통합 관리 플랫폼 <폴라리스>
* **기간:** 2026.07 – 2026.09 (팀 프로젝트 · 4인)
#### 1. 개발 인원과 포지션
	+ 총 4명 (풀스택 엔지니어 & 인프라 담당 - AI 잡매칭 파이프라인 및 백엔드/인프라 총괄)
#### 2. 개발 환경
	+ 언어 : Java 17, JavaScript, HTML / CSS
	+ OS : Cross-Platform / Linux (Docker)
#### 3. 사용기술 및 툴
	+ Spring Boot 4.0.7, Spring Security, Spring Data JPA, Querydsl, React, PostgreSQL 16 (pgvector), Docker, Docker Compose, GitHub Actions, Figma
#### 4. 설명
	+ PostgreSQL pgvector 기반 코사인 유사도 연산을 도입하여 런타임 AI 부하 없이 밀리초 단위 고속 AI 잡매칭 파이프라인 구축
	+ 원자적 트랜잭션 및 Unique 제약을 적용해 지원 현황 및 스크랩 동시성 충돌 방지 및 데이터 정합성 확보
	+ [GitHub 레포지토리 바로가기] (https://github.com/Wiza-Project) *(llm 작업 후 fork 브랜치 링크로 변경 예정)*

---

### [팀 프로젝트] 여행-커뮤니티 통합 플랫폼 〈갈래말래〉
* **기간:** 2026.06 – 2026.08 (팀 프로젝트 · 6인)
#### 1. 개발 인원과 포지션
	+ 총 6명 (풀스택 엔지니어 — 데이터 파이프라인 & 공통 컴포넌트)
#### 2. 개발 환경
	+ 언어 : Java, JSP, HTML / CSS
	+ OS : Cross-Platform / Linux
#### 3. 사용기술 및 툴
	+ Spring Boot, Spring Data JPA, Spring Security, WebClient, MySQL, Resilience4j, `@Scheduled`, Docker, Figma
#### 4. 설명
	+ WebClient, `@Scheduled`, Queue 구조를 결합한 스마트 큐 셀렉팅 기반 공공데이터 자동 수집·적재 파이프라인 설계
	+ Resilience4j + Jitter 지수 백오프를 적용하여 외부 공공데이터 API 호출 한도 초과(Rate Limit) 및 스레드 병목 방어
	+ [GitHub 레포지토리 바로가기] (https://github.com/beautiyj/travel-community)

---

### [팀 프로젝트] AIoT를 활용한 개인 복약/건강 관리 통합 시스템 〈MyRhythm〉
* **기간:** 2025.10.13 – 2025.12.09 (새싹캠퍼스 용산 종합프로젝트)
#### 1. 개발 인원과 포지션
	+ 팀 프로젝트 (Android · Backend · IoT 통합 아키텍처 설계 및 연동)
#### 2. 개발 환경
	+ 언어 : Kotlin, Python, C++ (ESP32 Firmware)
	+ OS : Android / Linux / IoT Embedded
#### 3. 사용기술 및 툴
	+ Android (Jetpack Compose, Clean Architecture, Multi-module), Backend (Django, JWT, RAG, REST API), IoT (ESP32, BLE, Wi-Fi), Docker
#### 4. 설명
	+ 복약 관리와 건강 모니터링을 목표로 Android 앱, Backend 서버, IoT 디바이스가 유기적으로 연동되는 통합 아키텍처 시스템 구축
	+ 디바이스는 이벤트 생성 및 물리적 알림만 담당하고, 판단 및 상태 결정(TAKEN / MISSED / WRONG)은 서버가 단일 진실의 원천(Single Source of Truth)으로서 총괄하도록 설계
	+ BLE 및 QR 기반 디바이스 등록 플로우 구축, 네트워크 불안정 및 시간 오차 등 실제 환경을 고려한 서버 중심 판정 로직 구현
	+ [GitHub 레포지토리 바로가기] [(https://github.com/beautiyj/MyRhythm_Project.git)]

---

### [팀 프로젝트] 실시간 경매를 접목한 중고 거래 쇼핑몰 웹 서비스
* **기간:** 2025.08.11 – 2025.08.13 (새싹캠퍼스 미니프로젝트 · 4인)
#### 1. 개발 인원과 포지션
	+ 총 4명 (팀원: 김윤석, 김윤정, 김형준, 송윤석) / 풀스택 및 웹 서비스 구현
#### 2. 개발 환경
	+ 언어 : Python, HTML / CSS, JavaScript
	+ OS : Cross-Platform / Web
#### 3. 사용기술 및 툴
	+ Django, Database, Git / GitHub, 협업 툴
#### 4. 설명
	+ 1명의 판매자가 다양한 상품을 등록하고 여러 고객이 구매할 수 있는 중고 거래 쇼핑몰 웹 서비스 구축
	+ 일반 구매 방식 외에 낙찰 이벤트(실시간 경매 방식)를 도입하여 유저 참여 흥미도 및 서비스 몰입도 제고
	+ [유튜브 시연 영상 바로가기] (https://youtube.com/channel/UCytaNKIpHrPVVYnA3D1469Q?si=E2B3tnPvIstcqNYF)
	+ [GitHub 레포지토리 바로가기] [(https://github.com/beautiyj/mini_project.git)]

<br><br>

---

## 🚀 개인 프로젝트 (Mini Projects)

### [개인 프로젝트] AI 기반 GitHub 프로젝트 자동화 플래너
* **기간:** 2026.03 – 진행 중 (개인 프로젝트)
#### 1. 개발 인원과 포지션
	+ 총 1명 (풀스택 / 백엔드 중심 아키텍처 설계 & 구현)
#### 2. 개발 환경
	+ 언어 : Python, HTML / CSS
	+ OS : Cross-Platform
#### 3. 사용기술 및 툴
	+ Django, SQLite, MySQL, GitHub REST API, GitHub OAuth, Gemini & OpenAI API, Docker, VSCode
#### 4. 설명
	+ 사용자 프로젝트 계획 입력 시 LLM 기반 마일스톤 자동 생성 파이프라인 및 JSON 응답 예외 처리 구조화
	+ 게스트 세션 플랜 데이터를 GitHub OAuth 로그인 계정으로 병합 동기화하는 사용자 연동 로직 구현
	+ [GitHub 레포지토리 바로가기] [(https://github.com/beautiyj/HandPoseAi.git)]

---

### [개인 프로젝트] 실시간 손동작 인식 3D 포즈 앱 〈HandPoseAi〉
* **기간:** 2026.02 – 진행 중 (개인 프로젝트)
#### 1. 개발 인원과 포지션
	+ 총 1명 (컴퓨터 비전 AI 파이프라인 엔지니어링 & Android 앱 개발)
#### 2. 개발 환경
	+ 언어 : Python, Kotlin
	+ OS : Cross-Platform (Android / PC)
#### 3. 사용기술 및 툴
	+ OpenCV, MediaPipe Hands, PyTorch, NumPy, Android Compose, Camera2 API, Android Studio, VSCode
#### 4. 설명
	+ 영상 스트림 속에서 손의 21포인트 관절 랜드마크를 실시간 검출하고 기하학적 각도 기반 제스처 분류 알고리즘 구축
	+ 관심 영역(ROI) 설정 및 경량화 전처리 파이프라인 도입을 통한 모바일 환경 실시간 FPS 성능 최적화
	+ [GitHub 레포지토리 바로가기] [(https://github.com/beautiyj/github-ai-planner.git)]

---
