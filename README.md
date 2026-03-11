<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,12&height=3" width="100%"/>

<br/>

# Youngjun Hong

**`@HONGMOEJI`**

> *"기술은 사람에게 닿을 때 비로소 의미가 있다."*
>
> *복잡한 기술을 실제 사용자에게 닿는 제품으로 만드는 걸 좋아합니다.*

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:moejihong@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HONGMOEJI)

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,12&height=3" width="100%"/>

</div>

<br/>

## 🎓 About

**B.Sc. Computer Engineering** — Hansung University *(Big Data & Mobile Software)*

| 🏆 Awards | 👨‍💻 Activity |
|---|---|
| 🥇 교내 캡스톤 디자인 대회 수상 | 전공 튜터링 튜터 (24-1, 25-1, 25-2) |
| 🏆 제 9회 K-PaaS 활용 서비스 공모전 수상 | 교내 우수 장학생 (23-2, 24-2, 25-2) |

<br/>

## 🛠 Tech Stack

**Mobile**&nbsp;
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Swift](https://img.shields.io/badge/Swift-F54A2A?style=flat-square&logo=swift&logoColor=white)

**Backend**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Data & Search**&nbsp;
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Infra & AI**&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![LLM](https://img.shields.io/badge/On--Premises_LLM-412991?style=flat-square&logo=openai&logoColor=white)

<br/>

## 🚀 Projects

---

### 💊 MedEasy — 대화형 AI 복약 관리 앱

**TEAM MedEasy &nbsp;|&nbsp; 2025.02 – 2025.07 &nbsp;|&nbsp; [→ GitHub](https://github.com/team-medeasy/MedEasy)**

[![K-PaaS](https://img.shields.io/badge/🏆_K--PaaS_수상-darkgreen?style=flat-square)](https://github.com/team-medeasy/MedEasy)
[![Capstone](https://img.shields.io/badge/🥇_캡스톤_수상-blue?style=flat-square)](https://github.com/team-medeasy/MedEasy)

<img src="https://github.com/team-medeasy/MedEasy/raw/main/.github/profile/docs/cover.png" width="100%"/>

디지털 소외 계층(고령자)을 위한 **음성 대화형 AI 복약 관리 서비스**. 말 한 마디로 복약을 등록하고 관리합니다.

- 식약처 공공 의약품 데이터(허가정보·낱알식별·DUR) 수집·정제 파이프라인 및 7일 주기 스케줄러 구축
- 알약 이미지 OCR → 색상·형태·각인 추출 → Elasticsearch 벡터 유사도 검색 (**정확도 96.6%**)
- **MCP + LangGraph 기반 AI 에이전트** + STT/TTS + WebSocket 실시간 음성 대화 흐름 구현
- GitHub Actions Workflow 기반 **TestFlight 자동 배포** 파이프라인 구성

`JavaScript` `React Native` `Python` `FastAPI` `Firebase` `AWS S3` `Elasticsearch` `LangGraph` `MCP`

---

### ⚡ PLog — API 부하테스트 자동화 플랫폼

**TEAM PLog &nbsp;|&nbsp; 2025.07 – 2025.09 &nbsp;|&nbsp; [→ GitHub](https://github.com/team-Plog/plog)**

<img src="https://github.com/team-Plog/plog/raw/main/docs/cover.png" width="100%"/>

OpenAPI 스펙 → 시나리오 생성 → k6 부하 테스트 → **AI 분석 리포트**까지, 소규모 팀을 위한 완전 자동화 플랫폼.

- TPS·응답시간·에러율의 수치 비교를 통한 **병목 구간 자동 탐지** 및 분류 체계 구성
- **온프레미스 LLM**에 병목 데이터를 전달, 개선 가이드를 포함한 분석 보고서 자동 생성
- **SSE(Server-Sent Events)** 기반 k6 테스트 실행 중 메트릭 실시간 스트리밍
- SQLite 기반 분석 히스토리 저장·조회, InfluxDB 메트릭 저장 연계

`Python` `FastAPI` `SQLite` `InfluxDB` `k6` `Docker` `K3s` `LLM` `SSE`

---

### 📚 CHACK — 독서 습관 형성 앱

**TEAM CHACK &nbsp;|&nbsp; 2024.09 – 2024.12 &nbsp;|&nbsp; [→ GitHub](https://github.com/ChackTeam/Chack)**

<img src="https://github.com/ChackTeam/Chack/raw/develop/docs/SlideShow.gif" width="100%"/>

Flutter + Firebase Serverless 아키텍처 기반으로 설계한 **독서 기록·목표·통계 습관 형성 앱**.

- Cloud Scheduler 기반 주간 단위 외부 도서 API 데이터 자동 갱신 파이프라인 구성
- Naver 책 검색 / 도서관정보나루 / VWorld API 통합 서비스 레이어 설계 및 구현
- **앱 전반의 화면 구조 및 공통 위젯 컴포넌트** 설계 주도 (Cross-Platform 70%)
- Provider 기반 상태 관리, Firestore CRUD·외부 API 호출 오류 처리 서비스 레이어 전반 구현

`Dart` `Flutter` `Firebase` `Cloud Functions` `Serverless` `Location-Based Service`

---

### 📰 뉴스 감정 기반 이상 탐지

**TEAM 살려조 &nbsp;|&nbsp; 2025.03 – 2025.06 &nbsp;|&nbsp; [→ GitHub](https://github.com/HONGMOEJI/verbose-bdp-adventure)**

뉴스 데이터의 감정 변화를 분석해 **사회적 이상 징후를 탐지**하는 NLP 프로젝트.

- Selenium + BeautifulSoup 기반 뉴스 데이터 수집 자동화 파이프라인 구축
- KOTE 감정 레이블 데이터로 **BERT·ELECTRA 감정 분류 모델** 파인튜닝
- **Z-score + Isolation Forest** 기반 시계열 이상 탐지 구현 (탐지 정확도 70%)

`Python` `Selenium` `BeautifulSoup` `BERT` `ELECTRA` `Z-score` `Isolation Forest`

---

<br/>

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=HONGMOEJI&show_icons=true&hide_border=true&title_color=4f86c6&icon_color=4fb3f6&text_color=555&bg_color=fafafa&rank_icon=github"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HONGMOEJI&layout=compact&hide_border=true&title_color=4f86c6&text_color=555&bg_color=fafafa"/>
</div>

<br/>

<div align="center">
  <sub>📩 <a href="mailto:moejihong@gmail.com">moejihong@gmail.com</a></sub>
</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,12&height=3" width="100%"/>
</div>
