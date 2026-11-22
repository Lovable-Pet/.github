<div align="center">

<img src="https://raw.githubusercontent.com/Lovable-Pet/.github/main/profile/assets/hero.jpg" width="100%" alt="Lovable Pet: 공고 속 그 아이를, 우리 집에 실제 크기로">

<br>

**보호소 강아지를 입양 전에 우리 집에 띄워, 실제 크기로 함께 지내는 모습을 미리 체험해 보는 AR 서비스**

<br>

<a href="https://lovablepet.tech"><img src="https://img.shields.io/badge/서비스_바로가기-lovablepet.tech-ff7185?style=for-the-badge" alt="lovablepet.tech"></a>

</div>

<br>

## 🐾 왜 만들었나요

- 공고 사진만 봐서는 그 아이가 실제로 얼마나 큰지, 우리 집에 들어오면 어떤 모습일지 가늠하기 어려워요.
- Lovable Pet은 공공데이터포털의 유기동물 공고를 매주 모아 오고, **공고 사진으로 그 아이를 닮은 3D 강아지**를 만들어요.
- 만든 3D 강아지를 **AR로 우리 집 바닥에 실제 크기로** 놓아 보고, 말을 걸거나 묘기를 시켜 보며 먼저 만나 볼 수 있어요.

<br>

## 📱 서비스 화면

<img src="https://raw.githubusercontent.com/Lovable-Pet/.github/main/profile/assets/screen_flow.jpg" width="100%" alt="서비스 흐름: 둘러보기, 상세 정보, 실제 크기, 우리 집에 띄우기">

<img src="https://raw.githubusercontent.com/Lovable-Pet/.github/main/profile/assets/screen_find.jpg" width="100%" alt="찾기와 관심목록: 검색, 필터, 관심목록">

<img src="https://raw.githubusercontent.com/Lovable-Pet/.github/main/profile/assets/screen_ar.jpg" width="100%" alt="AR과 3D: AR 안내, 우리 집 바닥에, 화면 안 3D">

<br>

## 🏗️ 시스템 구조

<img src="https://raw.githubusercontent.com/Lovable-Pet/.github/main/profile/assets/architecture.png" width="100%" alt="LovablePet 시스템 아키텍처">

<br>

## 📦 레포지토리

| 레포지토리 | 하는 일 | 기술 |
| :-- | :-- | :-- |
| [**LovablePet-FE**](https://github.com/Lovable-Pet/LovablePet-FE) | 웹 앱 화면, AR 화면 | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![three.js](https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) ![model-viewer](https://img.shields.io/badge/model--viewer-4285F4?style=flat-square) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| [**LovablePet-BE**](https://github.com/Lovable-Pet/LovablePet-BE) | REST API, 공고 동기화, AR 생성 관리 | ![Java](https://img.shields.io/badge/Java_21-437291?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white) ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| [**LovablePet-AI-AR**](https://github.com/Lovable-Pet/LovablePet-AI-AR) | 공고 사진으로 3D 강아지 만들기 (GLB · USDZ) | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square) ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square) ![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white) |

<br>

## 👥 팀원과 역할

<table>
  <tr>
    <td align="center" width="33%"><a href="https://github.com/LeeJuYoung12"><img src="https://github.com/LeeJuYoung12.png" width="110" alt="이주영"><br><b>이주영</b></a><br><sub><b>팀장</b> · LeeJuYoung12</sub><br><sub>기획 · 인프라 · BE · AR 파이프라인 · 애니메이션</sub></td>
    <td align="center" width="33%"><a href="https://github.com/taetu"><img src="https://github.com/taetu.png" width="110" alt="김태우"><br><b>김태우</b></a><br><sub><b>팀원</b> · taetu</sub><br><sub>BE · AR 인터랙션 · 애니메이션</sub></td>
    <td align="center" width="33%"><a href="https://github.com/anjaein"><img src="https://github.com/anjaein.png" width="110" alt="안재인"><br><b>안재인</b></a><br><sub><b>팀원</b> · anjaein</sub><br><sub>FE · UI 디자인</sub></td>
  </tr>
</table>

| 팀원 | 맡은 일 |
| :-- | :-- |
| **이주영**<br><sub><b>팀장</b></sub><br><sub>LeeJuYoung12</sub> | **기획**: 서비스 기획<br>**인프라**: AWS EC2 · Docker Compose, Caddy HTTPS, GitHub Actions → GHCR 자동 배포와 스모크 테스트<br>**BE**: 프로젝트 초기 세팅, 공공데이터 유기동물 공고 동기화와 목록 · 상세 · 필터 API, AR 생성 관리 (파이프라인 연동, GLB · USDZ 제공), 관리자 권한<br>**AR 파이프라인**: 공고 사진 → 3D 강아지 생성 파이프라인 설계 · 개발 (배경 제거, 견종 템플릿 고르기, 털 무늬 · 색 판독, 템플릿에 털 입히기, 실제 크기 계산)<br>**애니메이션**: 강아지 3D 동작 애니메이션 제작 |
| **김태우**<br><sub><b>팀원</b></sub><br><sub>taetu</sub> | **BE**: 회원 · 로그인 (아이디 로그인, 카카오 로그인, JWT · 리프레시 토큰), 공통 응답 · 예외 처리, 찜 API<br>**AR 인터랙션 (FE)**: 바닥 인식과 놓기 (깊이 센서, 장애물 둘레 검사), 음성 명령 · 길게 눌러 짖기, 산책 모드, 고개 바라보기 · 몸 돌리기, 짖는 소리<br>**애니메이션**: 강아지 3D 동작 애니메이션 제작 |
| **안재인**<br><sub><b>팀원</b></sub><br><sub>anjaein</sub> | **디자인**: 와이어프레임, 디자인 시스템, 로고, 전체 화면 리디자인<br>**FE**: 프로젝트 초기 세팅 (Vite · React · Tailwind · Storybook), 둘러보기 · 검색 · 필터 · 상세 · 찜 · 로그인 · 마이 · 관리자 화면, API 연동과 토큰 재발급, MSW 목업, 첫 AR 화면 (model-viewer), CI · Vercel 배포 |
