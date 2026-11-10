![header](https://capsule-render.vercel.app/api?type=venom&color=timeAuto&height=700h&fontSize=60&text=Hana%20Roh)

---

## 🛠 Tech Stack

### Backend & Language
* **Language:**
  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
  ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
* **Framework / Library:**
  ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
  ![Spring Data JPA](<img src="https://img.shields.io/badge/JPA-004D40?style=for-the-badge"/>)
  ![MyBatis](<img src="https://img.shields.io/badge/MyBatis-1F1F1F?style=flat"/>)
  ![NodeJS](https://img.shields.io/badge/node.js-%236DA55F.svg?style=for-the-badge&logo=node.js&logoColor=white)
  ![NestJS](https://img.shields.io/badge/Nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
  ![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white) 

### Database & DevOps
* **Database:**
  ![MySQL](	https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
  ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white)
* **Cloud & Infrastructure:**
  ![AWS](	https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
  ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
* **Tools:**
  ![Git](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
  ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
  ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
  ![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)
  ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
  ![Unity](	https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
  * IntelliJ IDEA, VS Code, Eclipse, Postman, Swagger

---

## 🚀 Projects

### 1. Real VR Fishing (실무 프로젝트)
* **작업 기간:** 2025.09.01 ~ 2026.05.31 (9개월, (주)디유지피닉스)
* **주요 역할:** 백엔드 API 개발 및 AWS 인프라 운영
* **주요 성과 및 업무:**
  * **챔피언십 이벤트 백엔드 구축:** Flyway DB 스키마 관리, API 9종 개발, AWS Lambda 시즌 승점 자동 계산 구현
  * **쿼리 성능 최적화:** N+1 문제 발생 쿼리(2,000여 건)를 Bulk Upsert 및 인덱스 최적화로 재설계하여 처리 속도 12~16배 개선 (260초 → 10~15초, 부하 92~94% 감소)
  * **디자인 패턴 적용:** 플랫폼별 분기 로직을 GoF Template Method 패턴으로 리팩토링하여 OCP(개방-폐쇄 원칙) 만족
  * **자동화 및 운영툴 개편:** 관리자 웹페이지(Admin Hub) 전면 개편(RBAC 권한 체계 재설계), Steam 매출 데이터 수동 확인(5분) 대비 자동화 대시보드로 15배 단축 (약 20초)
  * **비용 절감 및 인프라 운영:** CloudWatch 로그를 Firehose → S3 → Glacier로 이관하여 보관 비용 약 70% 절감, Parquet+Snappy 압축을 통한 S3 아카이빙 및 Athena 파티션 조회 구조 구축

### 2. [Skhuring][skuring-repo]
* **작업 기간:** 2025.03.10 ~ 2025.06.16 (팀 프로젝트, 2인)
* **주요 역할:** Spring Security 기반 보안 설정, 소셜 로그인, 챗봇 API 연동, CI/CD 구축
* **주요 성과:**
  * Spring Security 및 JWT를 활용한 인증/인가 처리 및 카카오 OAuth2 소셜 로그인 구현
  * 네이버 클라우드 Clova Studio (HyperCLOVA X 모델) API를 연동한 질의응답 챗봇 기능 구현
  * GitHub Actions를 활용한 AWS EC2 자동 배포(CI/CD) 파이프라인 구축

### 3. [Dive][dive-repo]
* **작업 기간:** 2025.02.07 ~ 2025.03.03 (팀 프로젝트, 5인, 팀장)
* **주요 역할:** 토스페이먼츠 API 연동 결제 시스템, 선물 기능, 팀장(일정 관리 및 ERD 설계 주도)
* **주요 성과:**
  * 토스페이먼츠 API를 연동하여 멤버십 및 MP3 결제/선물(중복 보유 조건 검증) 시스템 구현
  * GitHub Organizations 및 Notion/Google 스프레드시트를 활용한 협업 프로세스 및 API 명세 표준화 리딩

### 4. [GetSetGo!][getsetgo-repo]
* **작업 기간:** 2024.12.02 ~ 2024.12.20 (팀 프로젝트, 4인, 팀장)
* **주요 역할:** 일정 관리 기능 구현, 일정 중복 방지 로직, 전체 시스템 구조 설계
* **주요 성과:**
  * AJAX 기반 실시간 검색, Date Range Picker를 활용한 5일 연속 일정 생성 및 10자리 문자열 코드 공유 기능 구현
  * 일정 중복 방지 로직을 적용하여 사용자 일정 충돌 최소화

---

## 📜 Certifications & Education
* **정보처리기사 필기 합격** (실기 응시 예정) (2025.09)
* **SQL개발자(SQLD)** 취득 (2025.06)
* **자바 풀스택 개발자 양성과정 수료** (하이미디어아카데미) (2024.09 ~ 2025.03)

---

## 📬 Contact
* **Email:** hana4979@gmail.com
* **GitHub:** [@hana4979](https://github.com/hana4979)

--

[skuring-repo]: [https://github.com/orgs/team-skhuring/repositories]
[dive-repo]: [https://github.com/hana4979/project-dive-musicstreaming.git]
[getsetgo-repo]: [https://github.com/Team-Travelmate-himedia/Project_Team_Travelmate.git]

