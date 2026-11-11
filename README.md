<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&text=Hana%20Roh&animation=fadeIn&fontColor=faf0ff&fontSize=60" />

---

## 🛠 Tech Stack

### Backend & Language
* **Language:**
  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
  ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
  ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
* **Framework / Library:**
  ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
  ![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
  ![NodeJS](https://img.shields.io/badge/node.js-%236DA55F.svg?style=for-the-badge&logo=node.js&logoColor=white)
  ![NestJS](https://img.shields.io/badge/Nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
  ![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
  * JPA, MyBatis

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
* **주요 역할:** 백엔드 API 개발, AWS 인프라 운영, 운영툴(Admin Hub) 풀스택 개발
* **기술 스택:** Node.js(NestJS/Express), .NET(Platform), TypeScript, Python, MySQL, Flyway, React, shadcn/ui, AWS(ECS, ECR, Lambda, S3, CloudFront, CloudWatch, Firehose, Glue, Athena, SSM), Docker, GitHub Actions, Postman, Swagger
* **주요 성과 및 업무:**
  * **챔피언십 이벤트 백엔드 구축:** Flyway DB 스키마 관리, API 9종 설계·개발 후 Docker 컨테이너로 ECS 배포, AWS Lambda 시즌 승점 자동 계산 구현
  * **쿼리 성능 최적화:** N+1 문제 발생 쿼리(2,000여 건)를 Bulk Upsert 및 인덱스 최적화로 2건으로 재설계하여 부하 약 92\~94% 감소, 처리 속도 12\~16배 개선
  * **디자인 패턴 적용:** 플랫폼별 분기 로직을 GoF Template Method 패턴으로 리팩토링하여 OCP 만족, 신규 플랫폼은 자식 클래스 1개 추가만으로 확장
  * **리더보드·시즌 자동화:** Steam Web API 연동(리더보드 생성·조회·등록), Meta와 넘버링·보상 로직 정합성 점검, NestJS Cron으로 월간 시즌 갱신·리더보드 생성·백업 자동화
  * **스케줄러 장애 대응:** Meta 서버 오류로 스케줄러가 실패하는 상황에 대비해 수동 실행 API 3종(리더보드 생성/시즌 갱신/이전 시즌 백업) 개발·배포, Postman Collection으로 팀 공유
  * **리더보드 데이터 보정:** Pico/Pico China 누락 리더보드 총 456개(228개×2)를 Python 스크립트로 명령어 한 줄, 약 1분에 생성
  * **ECS 전환 및 배포 자동화:** Dev/Beta/Live를 ECS로 전환, Docker 빌드 → ECR 자동 태깅·푸시 스크립트 작성, 롤링 무중단 배포 구성
  * **Beta 환경 리소스 문제 해결:** t4g.small 메모리 부족으로 롤링 배포가 실패하는 문제를 Auto Scaling Group으로 서비스 중단 없이 인스턴스·Task 사양을 교체해 해결, Dev는 사양을 낮춰 비용 절감
  * **운영툴(Admin Hub) 전면 개편:** 동작하지 않던 뉴스보드·공지·쿠폰·이벤트·유저 메시지 정상화, DB 직접 수정 없이 권한자가 데이터를 관리하도록 개선해 QA 시간 단축, 관리 환경을 live → dev·beta까지 확장, shadcn/ui 컴포넌트로 UI 통일
  * **RBAC 권한 체계 재설계:** 모든 계정이 CUD 가능하던 구조를 Viewer(Read)/Editor(CUD)/Admin(계정 관리)으로 분리, 프로젝트별(RVRF/Sticky Planet) 메뉴·권한 분기 및 기존 데이터 이관 SQL 작성
  * **운영 편의 기능:** ALL SAVE(전 플랫폼·환경 일괄 적용), 빌드 없는 UI TEXT 수정, QA용 유저 데이터 초기화 버튼, 비밀번호 상시 변경, Hero Fish/Shark·Shark Frenzy 설정 관리 페이지
  * **Schemaless 이벤트 스탯 설계:** 고정 키 + JSON 컬럼(`event_shark_configs`) 구조로 기획 변경 시 서버 배포 없이 운영툴에서 즉시 반영(리드타임 2시간 → 즉시), 스탯 반환 API와 Swagger 명세서를 클라이언트 팀에 공유
  * **데이터 조회·대시보드:** 구매 로그 조회 API·화면, CSV 다운로드(UTF-8 BOM), 기간·재화·아이템 유형별 시각화 대시보드 개발, 인덱스 추가로 조회 시간 단축
  * **Steam 매출 대시보드:** Steam 재무 API를 매일 수집해 DB에 적재, 수동 확인(약 5분) 대비 약 20초로 단축(약 15배), 원본은 gzip + Intelligent-Tiering으로 S3 백업해 용량 약 91.7% 절감(1.1MB → 93.3KB)
  * **이벤트 API 개발:** 멕시코 DLC 알레브리헤 이벤트 활성 여부 API, Winter Shark Frenzy API, 크리스마스 이벤트(DLC_SeasonEvent) API 개발
  * **보안 개선:** Git에 포함되던 서버 `.env`를 SSM Parameter Store로 이전, ECS 태스크 정의에 직접 주입, AWS CLI로 로컬 `.env` 자동 생성 스크립트 작성
  * **장애 분석 및 로그 비용 절감:** EC2 디스크 풀 장애 원인 분석, 불필요 로그 축소 및 보존 기간 후 삭제 도입, 로그를 Firehose → S3(약 1.4배 저렴) → 2주 후 Glacier Instant Retrieval(약 6.6배 저렴) → 6개월 후 자동 삭제
  * **DB 용량 관리:** 구매 로그 Parquet+Snappy 압축 S3 아카이빙 및 Athena 파티션 조회, 이후 프로시저+이벤트 기반 DB 파티셔닝으로 전환, 미션 진행도 테이블 월별 파티션 및 12개월 초과 데이터 자동 삭제, MySQL 8.0 → 8.4 Blue/Green 무중단 업그레이드
  * **데이터 보호 및 CS:** S3 Versioning 적용(이전 버전 7일 후 삭제, 최신 2개 보존), RDS 스냅샷 → S3 → Glue → Athena 조회 체계로 유저 CS 데이터 확인
  * **프론트 배포 자동화:** Hub 프론트의 S3·CloudFront 배포(백업 → 업로드 → 캐시 무효화)를 `npm run deploy` 한 번으로 자동화

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

---

[skuring-repo]: https://github.com/orgs/team-skhuring/repositories
[dive-repo]: https://github.com/hana4979/project-dive-musicstreaming.git
[getsetgo-repo]: https://github.com/Team-Travelmate-himedia/Project_Team_Travelmate.git

