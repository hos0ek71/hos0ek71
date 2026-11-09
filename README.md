# 주호석

<a href="mailto:kmb5037@naver.com"><img src="https://img.shields.io/badge/Email-kmb5037%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white" alt="Email" /></a>
<a href="https://juhoseok.github.io/jekyll-theme-velog/"><img src="https://img.shields.io/badge/Tech%20Blog-juhoseok.github.io-222222?style=flat-square&logo=githubpages&logoColor=white" alt="Tech Blog" /></a>
<a href="https://github.com/JUHOSEOK"><img src="https://img.shields.io/badge/Jungle%20Account-JUHOSEOK-181717?style=flat-square&logo=github&logoColor=white" alt="JUHOSEOK" /></a>

## 🔎 핵심 역량

- **기능·권한 검증** — 관리자 화면 지표 정합성 수정, 로그인·일반 사용자·관리자별 접근 허용/차단 테스트
- **API·DB 연동** — 외부 대중교통 API 응답 처리, PostgreSQL 모델·Alembic 마이그레이션
- **실행 환경·CI** — Docker Compose·AWS·Nginx 환경, GitHub Actions 빌드·테스트 및 OpenAPI 검증
- **인증·실시간 흐름** — WebSocket 연결 URL의 JWT를 Redis 1회용 티켓 방식으로 개선, REST 저장·실시간 갱신·재연결 흐름 확인

## 🛠 Tech Stack

| 분야 | 기술 |
| :-- | :-- |
| **Backend** | <img src="https://skillicons.dev/icons?i=java,spring,py,fastapi" height="34" alt="Java, Spring Boot, Python, FastAPI" /><br /><sub>Java · Spring Boot · Spring Security · JPA · MyBatis · Python · FastAPI</sub> |
| **Database** | <img src="https://skillicons.dev/icons?i=postgres,redis" height="34" alt="PostgreSQL, Redis" /><br /><sub>PostgreSQL · Oracle · Redis · SQLAlchemy · Alembic</sub> |
| **Infra / CI** | <img src="https://skillicons.dev/icons?i=docker,aws,nginx,githubactions" height="34" alt="Docker, AWS, Nginx, GitHub Actions" /><br /><sub>Docker · Docker Compose · AWS · Nginx · GitHub Actions</sub> |
| **Test / 검증** | <sub>Pytest · HTTP E2E 테스트 · OpenAPI 명세·검증</sub> |
| **Web / App** | <img src="https://skillicons.dev/icons?i=react,ts,js,html,css,cs" height="34" alt="React, TypeScript, JavaScript, HTML, CSS, C#" /><br /><sub>React · TypeScript · JavaScript · HTML/CSS · C#</sub> |
| **AI / Data** | <sub>Spring AI · pgvector</sub> |
| **Collaboration** | <img src="https://skillicons.dev/icons?i=git,github,notion,figma" height="34" alt="Git, GitHub, Notion, Figma" /> |

## 📂 Projects

| 프로젝트 | 기간 | 담당 | 주요 기술 |
| :-- | :-- | :-- | :-- |
| [**다짜조**](https://github.com/hos0ek71/dazzajo-portfolio)<br /><sub>AI PC 견적 추천·검증 및 AS 지원 플랫폼</sub> | 2026.06 ~ 2026.07<br /><sub>크래프톤 정글 · 5인 팀</sub> | 공통 인프라·CI, 관리자 화면·권한 테스트, 실시간 상담 인증 | Java 21 · Spring Boot · PostgreSQL · Redis · AWS |
| [**DailyMotion**](https://github.com/Dev-SangWoo/DailyMotion)<br /><sub>스마트 출퇴근 경로 최적화 앱</sub> | 2025.09 ~ 2025.12<br /><sub>한국지능정보사회진흥원 공모전 · 팀</sub> | 백엔드 경로 최적화 모듈·API·DB | Python · FastAPI · PostgreSQL · Alembic · Pytest |
| [**커스텀 의류 제작 매칭 서비스**](https://github.com/hos0ek71/letsgit)<br /><sub>부천대학교 졸업 프로젝트</sub> | 2024.12 ~ 2025.07<br /><sub>팀</sub> | React 기반 프론트 모듈 | React · JavaScript · Spring Boot · Oracle |
| [**카페 키오스크**](https://github.com/hos0ek71/cafeproject)<br /><sub>C# 융합 프로젝트</sub> | 2024.09 ~ 2024.12 | 메뉴·주문·결제 UI, DB 설계·트랜잭션 | C# · Oracle |

<details open>
<summary><b>다짜조 — AI PC 견적 추천·검증 및 AS 지원 플랫폼</b></summary>
<br />

예산과 용도에 맞는 조립 PC 견적을 추천하고, 부품 호환성 확인부터 견적 변경과 AS 상담까지 이어 주는 서비스입니다.

- **공통 실행 환경·CI** — Docker Compose·AWS·Nginx 기반 실행 환경을 다루고, GitHub Actions 빌드·테스트와 OpenAPI 검증을 구성
- **AWS 배포 자동화** — Green 환경 배포, ECR 이미지 다이제스트 기반 릴리스, 인스턴스 상태 확인·롤백 경로 구성
- **관리자 화면·권한 검증** — 관리자 지표 정합성 수정, 로그인·일반 사용자·관리자별 접근 허용/차단 테스트
- **실시간 상담 인증** — WebSocket 연결 URL에 JWT가 노출되는 구조를 REST로 발급한 Redis 1회용 티켓 인증으로 개선하고, REST 저장·실시간 갱신·재연결 흐름을 정리
- **부품 관계 그래프 UI** — 부품 관계와 호환 후보, 조합 검증 상태(PASS·WARN·FAIL)를 그래프로 확인하는 화면
- **협업** — PR 리뷰·버그 수정, 변경 후 서비스를 직접 사용해 동작 확인

`Java 21` `Spring Boot` `React` `TypeScript` `PostgreSQL` `Redis` `Docker Compose` `AWS` `Nginx` `GitHub Actions`

🔗 [포트폴리오 저장소](https://github.com/hos0ek71/dazzajo-portfolio) · [팀 원본 저장소](https://github.com/jungle-final-project/prototype)

</details>

<details>
<summary><b>DailyMotion — 스마트 출퇴근 경로 최적화 앱</b></summary>
<br />

목표 도착 시각을 기준으로 출퇴근 경로와 출발 시점을 안내하고, 예상 도착 시간과 지연을 감지하는 모바일 서비스입니다.

- **외부 API 연동** — ODSAY 경로 검색, 버스·지하철 도착 정보를 연동해 경로·혼잡도 응답 처리
- **DB 모델·마이그레이션** — 출퇴근 설정과 최적화 이력을 저장하는 PostgreSQL 모델을 SQLAlchemy·Alembic으로 구현
- **테스트·명세** — Pytest·HTTP E2E 테스트로 API 동작을 확인하고 OpenAPI 명세 정리

`Python` `FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL` `Pytest` `OpenAPI`

🔗 [팀 저장소](https://github.com/Dev-SangWoo/DailyMotion)

</details>

<details>
<summary><b>온라인 커스텀 의류 제작 매칭 서비스 — 졸업 프로젝트</b></summary>
<br />

의뢰인과 디자이너를 연결해 맞춤 의류 제작을 의뢰·관리하는 웹 서비스입니다.

- **담당** — 팀 내 React 기반 프론트 모듈
- **의뢰인 화면** — 옷 제작 템플릿 디자인, 디자이너 검색, 대화방, 의뢰 게시판, 마이페이지
- **디자이너 화면** — 계약 관리, 제작 관리, 포트폴리오 관리
- 사용자 역할에 따라 화면을 나누어 구성하고, 졸업작품으로 발표

`React` `JavaScript` `HTML/CSS` `Java` `Spring Boot` `Oracle`

🔗 [저장소](https://github.com/hos0ek71/letsgit)

</details>

<details>
<summary><b>카페 키오스크 — C# 융합 프로젝트</b></summary>
<br />

- 카페 메뉴, 주문·결제 UI 구성
- Oracle 데이터베이스 설계와 트랜잭션 처리

`C#` `Oracle` `Visual Studio` `Windows`

🔗 [저장소](https://github.com/hos0ek71/cafeproject)

</details>

## 🎓 Education & Activities

| 기간 | 내용 |
| :-- | :-- |
| 2026.03 ~ 2026.07 | **SW-AI랩(크래프톤 정글) 12기 수료** · K-디지털 트레이닝 |
| 2025.09 ~ 2025.12 | **민관협력 지원 플랫폼 활용 디지털 사회혁신 서비스 개발 공모전** · 한국지능정보사회진흥원 — DailyMotion, 교통혁신 부문 우수상 |
| 2021.03 ~ 2026.02 | **부천대학교 컴퓨터소프트웨어과 졸업** |

## 📌 More

- [AI 지식 게시판](https://github.com/hos0ek71/notice_board) — Spring Boot·PostgreSQL·pgvector 기반 게시판에 Spring AI RAG 유사 글 검색과 Q&A를 결합한 개인 과제
- [코드트리 코딩테스트](https://github.com/hos0ek71/code-tree-repository) — 알고리즘 문제 풀이 기록
- 크래프톤 정글 과정의 추가 학습 기록은 [JUHOSEOK](https://github.com/JUHOSEOK) 계정에 있습니다.
