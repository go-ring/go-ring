<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Hello!&desc=I%20am%20GaEun&fontAlignY=40&color=0:feac5e50:c779d0,100:4bc0c8&fontColor=f7f5f5&textBg=282829" alt="Header" />
</div>

<br>

<div align="center">
  안녕하세요! 끊임없는 문제 해결과 안정적인 아키텍처를 고민하는 <b>백엔드 개발자 이가은</b>입니다. <br>
  새로운 기술을 탐구하고, 기록으로 남기며 함께 성장하는 것을 즐깁니다.
</div>

<br>

<div align="center">
  <a href="https://go-ring.github.io/portfolio/">
    <img src="white_turtle.png" height="28" align="center" />
    <img src="https://img.shields.io/badge/Portfolio-282829?style=for-the-badge" align="center" />
  </a>
  &nbsp;&nbsp;
  <a href="https://velog.io/@goring"><img src="https://img.shields.io/badge/Velog-20CE94?style=for-the-badge&logo=velog&logoColor=white" align="center" /></a>
  &nbsp;&nbsp;
  <a href="mailto:dlrkdms001@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" align="center" /></a>
</div>

<br>

## 🎓 Education

- **삼성 청년 SW·AI 아카데미 (SSAFY)** (2025.07 ~ 2026.06)
  - 14기 교육생 | 삼성전자 | 알고리즘 및 웹 개발 심화 과정
- **CIA Academy** (2024.07 ~ 2024.09)
  - 어학연수 | 글로벌 커뮤니케이션 능력 향상 및 문화 교류
- **한남대학교 시스템 소프트웨어 공학 연구실** (2022.10 ~ 2024.01)
  - 학부 연구생 | 논문 작성 및 최신 기술 동향 연구

---

## 🛠 Tech Stack

### 🚀 Backend
<p>
  <img src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/-Spring-6DB33F?style=flat-square&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/-Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/-QueryDSL-4479A1?style=flat-square">
  <img src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
</p>

### 🗄️ Database
<p>
  <img src="https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/-ElasticSearch-005571?style=flat-square&logo=elasticsearch&logoColor=white">
</p>

### ☁️ Infra & Tools
<p>
  <img src="https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/-GitLab_CI/CD-FC6D26?style=flat-square&logo=gitlab&logoColor=white">
  <img src="https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white">
  <br><br>
  <img src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white">
</p>

---

## 💻 Projects

### 🐶 [BAEKGU (백구)](#)
**AI 기반 맞춤형 채용/구직 플랫폼 (2026.01 ~ 2026.02)**  
> 기술 경험과 재무/뉴스 데이터를 교차 분석하여 공고 매칭 및 증거 중심(Evidence-based) 자소서 작성을 돕는 올인원 솔루션.
- **역할**: Backend & JiraOps (`Java`, `Spring Boot`, `Redis`, `QueryDSL`)
- **성과**:
  - 보안 로직 DB → Redis 전환으로 응답속도 120ms → 5ms, CPU 사용률 80% 감소.
  - 채팅방 목록 조회 속도 30배 개선 (QueryDSL 최적화).
  - STOMP 레이어로 인증 시점을 분리하여 채팅 지연시간 10ms 미만 단축. 

### 📝 [Algogo (알고고)](#)
**스터디 관리 및 지능형 코드 리뷰 플랫폼 (2025.10 ~ 2025.11)**
> 알고리즘 문제 제출 시스템과 G-Eval AI 코드 분석 엔진을 결합한 스터디 자동화 플랫폼.
- **역할**: Backend & CI/CD (`Spring Boot`, `MySQL`, `Docker`, `GitLab CI/CD`)
- **성과**:
  - Blue-Green 배포 안정화를 통한 트래픽 유실 0건 달성.
  - 레이어 캐싱 및 Multi-stage 빌드로 CI/CD 배포 파이프라인 66% 단축 (12분 → 4분).
  - 커스텀 `@Async` 스레드 풀 분리로 AI 응답 지연의 시스템 전파 방지.

### 💊 [DDOYA (또야)](#)
**AI 비전 스캐닝 맞춤형 영양제 및 복약 관리 솔루션 (2026.02 ~ 2026.03)**  
> 스마트폰 카메라로 알약과 성분표를 인식하여 맞춤형 분석 리포트와 복약 캘린더를 제공하는 앱.
- **역할**: Backend & Infra (`Spring Boot`, `MySQL`, `FastAPI`, `Jenkins`)
- **성과**:
  - 스마트 복약 인증 및 성분 분석 API 파이프라인 구축.
  - FCM 기반 푸시 알림 연동 및 FastAPI와의 데이터 통신 인터페이스 최적화.

### 🎨 [ColorFinder (컬러파인더)](#)
**데이터 기반 퍼스널 컬러 진단 및 의류 추천 이커머스**  
> 안면 색상 데이터를 유클리디안 거리 알고리즘으로 분석하여 퍼스널 컬러를 분류하고 기온에 맞는 의류를 추천.
- **역할**: Server 개발 (`Spring`, `Flask`, `MySQL`, `Python`)
- **성과**:
  - 기상청 실시간 API 응답을 메모리(Local Cache) 처리하여 성능 부하 통제.
  - 맞춤형 의류 카테고리 필터링 알고리즘 및 결제 비즈니스 로직 연동.

---

## 📊 GitHub Stats & Career

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=go-ring&show_icons=true&theme=transparent&hide_border=true&title_color=c779d0&icon_color=4bc0c8&text_color=ffffff&bg_color=282829" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=go-ring&layout=compact&theme=transparent&hide_border=true&title_color=c779d0&text_color=ffffff&bg_color=282829" height="150" alt="Top Languages" />
</div>

<div align="center">
  <br>
  <a href="https://solved.ac/goring/">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=goring" alt="Solved.ac Profile" />
  </a>
</div>

<br>

<div align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgo-ring&count_bg=%23282829&title_bg=%23282829&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false" alt="Hits"/>
</div>
