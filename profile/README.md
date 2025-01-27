<h4 align="center">📜 2024 Techeer Winter BootCamp K team 📜</h1>
<h1 align="center">🕵️ AILIBI 🕵️</h1>
<div align="center"> 
<h3><b> AI-based detective simulation game </b></h3><br>
<img width="1503" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/main.png" alt="대표 이미지">
<h3><b>AI+ALIBI(현재 부재 증명)= AILIBI</b></h3>

<br>

</div>
<br><br>


# 📖 Table of contents
* [Introduction](#-introduction)
* [Demo](#-demo)
* [API](#-api)
* [System Architecture](#-system-architecture)
* [ERD](#-erd)
* [Tech Stack](#-tech-stack)
* [Monitoring](#-monitoring)
* [Directory Structure](#-directory-structure)
* [How to start](#-how-to-start)
* [Team Members](#-team-members)

<br>

# 📣 Introduction
### URL
> 🗝️ [AILIBI](https://AILIBI.link) 

### Medium
> 🔎 [AILIBI Medium](https://medium.com) &nbsp;

<br>

- **AI + ALIBl(형사 사건이 발생한 시간에 용의자가 그 범죄 현장에 있지 않았다는 증명)=AILIBI**
- **AI 기반 탐정 시뮬레이션**
- **1인용 두뇌게임**
- **사용자가 사건 종류,장소,시간을 입력하면 AI(GPT-4)가 시나리오,용의자,증거를 생성**
- **사용자는 시나리오의 탐정이 되어 용의자를 심문하고 증거를 탐색**
- **진범은 찾아내면 승리**

<br>

# 🕺🏻 Demo
### 로그인 페이지 및 시작 페이지
> AILIBI 게임에 대한 간략한 설명을 담고 있습니다.
<img align="center" width="1000" alt="Onboarding" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/main.png">
<img align="center" width="1000" alt="Onboarding" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/login.png">


### 메인 페이지
> 현재까지 진행했던 히스토리 페이지 및 새로운 시나리오를 생성하는 시나리오 페이지로 이동이 가능합니다
<br>
<img align="center" width="1000" alt="Login & Sign up" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/mainPage.png">

<br>

### 시나리오 생성 페이지
> 플레이어가 탐정 스토리의 주요 배경과 사건을 설정하는 페이지입니다..<br>
> 사건의 종류,시간,장소 등을 선택할 수 있습니다.
<br>
<img align="center" width="1000" alt="Login & Sign up" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/make.png">

<br>

### 히스토리 페이지
> 플레이어가 이전에 해결했던 사건들을 확인할 수 있는 기록 페이지입니다.<br>
> 사건별 결과와 세부 정보를 조회할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/history.png">

<br>

### 로딩 페이지 및 미니게임
> 게임이 로드되는 동안 플레이어가 즐길 수 있는 간단한 미니게임이 포함된 페이지입니다.<br>
> 대기 시간을 줄이고 몰입감을 높이는 역할을 합니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/loading.png">
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/minigame.png">
<br>

### 플레이 페이지
> 플레이어가 사건을 해결하며 진행하는 메인 게임 화면입니다.<br>
> 증거를 조하고, 용의자를 심문하며 사건의 진실을 추적합니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/play.png">

<br>
  
### 용의자 및 증거 페이지
> 주요 용의자들의 프로필, 알리바이, 행동 기록 등을 확인할 수 있는 페이지입니다.<br>
> 발견된 증거를 정리하고 분석하여 사건 해결에 활용합니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/">

<br>

### 용의자 채팅 페이지
> AI 기반으로 용의자와 실시간으로 대화하며 단서를 수집하는 페이지입니다.<br>
> TTS로 생성된 꿀보이스로 자유로운 대화가 가능합니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/">

<br>

### 추리 노트 팝업
> 플레이어가 정리한 사건의 단서, 용의자 관계도, 메모 등을 빠르게 볼 수 있는 팝업입니다.<br>
>추리를 위한 모든 정보를 한눈에 확인할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/">

<br>

### 결과 페이지
> 사건이 해결된 이후의 페이지로, 사건의 전개와 해결 과정을 요약합니다.<br>
> 플레이어의 선택에 따라 달라지는 결과 페이지와 크레딧 화면을 볼 수 있습니다
<br>
<img align="center" width="1000" alt="" src="https://raw.githubusercontent.com/ksm0520/practice/main/images/">




<br>

# 📗 API
<img width="1503" src="https://github.com/user-attachments/assets/bf878657-839e-4c39-9e44-7aa49bfe750e" alt="API 이미지">



<br><br>

# 🛠 ️System Architecture <a name="-system-architecture"></a>
<div align="center">
  <img align="center" width="1000" src="https://github.com/user-attachments/assets/f4ef9980-faf7-4c55-9d48-fd0d3c1901de">
</div>
<br><br>

# 🔑 ERD
<div align="center">
  <img width="1000" src="https://github.com/user-attachments/assets/202ea22b-0dca-4d18-b7e4-b53515745f75">
</div>
<br><br>

# 💻 Tech Stack

<div align="center">
  <table>
    <tr>
      <th>Field</th>
      <th>Technology of Use</th>
    </tr>
    <tr>
      <td><b>Frontend</b></td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
        <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">
        <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
        <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
        <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
        <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">
        <img src="https://img.shields.io/badge/Styled--Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white">
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white">
        <img src="https://img.shields.io/badge/DJANGO_REST_Framework-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709">
        <img src="https://img.shields.io/badge/Django--Channels-34A853?style=for-the-badge&logo=django&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Database</b></td>
      <td>
        <img src="https://img.shields.io/badge/AmazonS3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white">
        <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
        <img src="https://img.shields.io/badge/AmazonRDS-527FFF?style=for-the-badge&logo=amazon-rds&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/OpenAI-74aa9c?style=for-the-badge&logo=openai&logoColor=white">
        <img src="https://img.shields.io/badge/DALL·E-1192e8?style=for-the-badge&logo=openai&logoColor=white">
      </td>
      </td>
    </tr>
    <tr>
      <td><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white">
        <img src="https://img.shields.io/badge/AmazonEC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=black">
        <img src="https://img.shields.io/badge/GitHubActions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
        <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
        <img src="https://img.shields.io/badge/cAdvisor-0078D7?style=for-the-badge&logo=google&logoColor=white">
        <img src="https://img.shields.io/badge/NodeExporter-00695C?style=for-the-badge&logo=google&logoColor=white">
        <img src="https://img.shields.io/badge/GrafanaLoki-005571?style=for-the-badge&logo=grafana&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>ETC</b></td>
      <td>
        <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img src="https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
      </td>
    </tr>
  </table>
</div>
<br><br>

# 📊 Monitoring
<div align="center">
  <h3 align="left">Prometheus & Grafana</h3>
  <table>
        <tr>
            <th colspan="2">Django</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/07339efc-48c9-4b9d-b6a1-ea19910eb1db" alt="Django"></td>
            <td><img src="https://github.com/user-attachments/assets/e4099e6f-7463-4b95-af36-f1690b917073" alt="Django2"></td>
        </tr>
        <tr>
            <th colspan="2">Celery</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/074048e6-4ece-43f9-9800-2f2d523f2930" alt="Celery"></td>
            <td><img src="https://github.com/user-attachments/assets/8d67960d-b60e-4a37-9597-7eabeed8c6fb" alt="Celery2"></td>
        </tr>
        <tr>
            <th colspan="2">cAdvisor</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/5c995407-38a8-4949-8807-c6678e15adea" alt="cAdvisor"></td>
            <td><img src="https://github.com/user-attachments/assets/8ec92d68-418e-4d97-a288-88bf7b0e4bac" alt="cAdvisor2"></td>
        </tr>
        <tr>
            <th colspan="2">Node_Exporter</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/ecd13865-d1f4-4f34-af30-2d91b081b7b8"></td>
            <td><img src="https://github.com/user-attachments/assets/cff8c04a-700c-45ad-ad84-017d343d2e3d" alt="Node Exporter2"></td>
        </tr>
        <tr>
            <th colspan="2">RabbitMQ</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/e41beaed-0e21-4f7d-82b0-e86a8a6b9f37"></td>
            <td><img src="https://github.com/user-attachments/assets/1dd07d64-3548-476f-a68a-7b5e613b49cc" alt="Node Exporter2"></td>
        </tr>
        <tr>
          <th>Nginx_Exporter</th>
          <th>Redis</th>
        </tr>
        <tr>
          <td><img src="https://github.com/user-attachments/assets/ef00a11f-e77a-40a2-ad32-b19d67b65e2a"></td>
          <td><img src="https://github.com/user-attachments/assets/67a6e2fb-fa01-4172-9a86-a0b17a847379"></td>
        </tr>
    </table>
  <br>
</div>
<br>
  
  <h3 align="left">Cloud Flare</h3>
<table>
  <tr>
      <th colspan="2">Frontend</th>
  </tr>
  <tr>
      <td><img src="https://github.com/user-attachments/assets/77b5c76c-1567-4e63-b5db-4335749167cb"></td>
      <td><img src="https://github.com/user-attachments/assets/e9429a44-14d5-4711-9124-0a9a83c5abc9" alt="Node Exporter2"></td>
  </tr>
</table>

<br>


# 🔧 Logging
<div align="center">
  <h3 align="left">Loki</h3>
  <table>
        <tr>
            <th colspan="2">Nginx</th>
        </tr>
        <tr>
            <td><img src="https://github.com/user-attachments/assets/fa352ece-f6f7-4862-ba17-22ed53a2378b" alt="Django"></td>
            <td><img src="https://github.com/user-attachments/assets/e9749025-fd86-4203-aee0-30713e96ad5f" alt="Django2"></td>
        </tr>
    </table>
</div>
<br>

# 📂 Directory Structure

<details>
  <summary>AILIBI-Backend</summary>
<pre>
<code>
🗂️AILIBI-Backend
┣ 📂.github
┃ ┣ 📂ISSUE_TEMPLATE
┃ ┗ 📂workflows
┣ 📂Backend
┃ ┣ 📃__init__.py
┃ ┣ 📃asgi.py
┃ ┣ 📃celery.py
┃ ┣ 📃settings.py
┃ ┣ 📃urls.py
┃ ┗ 📃wsgi.py
┣ 📂alertmanager
┃ ┗ 📃alertmanager.yml
┣ 📂chat
┃ ┣ 📂migrations
┃ ┣ 📂templates
┃ ┣ 📃Serializers.py
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃consumers.py
┃ ┣ 📃models.py
┃ ┣ 📃routing.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂evidence
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂grafana/data
┃ ┣ 📂alerting/1
┃ ┗ 📃grafana.db
┣ 📂health
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂llm
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂prometheus
┃ ┣ 📃alert-rules.yml
┃ ┗ 📃prometheus.yml
┣ 📂promtail
┃ ┗ 📃config.yaml
┣ 📂scenario
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃scenario_urls.py
┃ ┣ 📃serializers.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂staticfiles
┃ ┣ 📂admin
┃ ┣ 📂drf-yasg
┃ ┗ 📂rest_framework
┣ 📂stt
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂suspect
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃suspect_urls.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂tts
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃apps.py
┃ ┣ 📃tasks.py
┃ ┣ 📃urls.py
┃ ┗ 📃views.py
┣ 📂user
┃ ┣ 📂migrations
┃ ┣ 📃__init__.py
┃ ┣ 📃admin.py
┃ ┣ 📃apps.py
┃ ┣ 📃models.py
┃ ┣ 📃serializers.py
┃ ┣ 📃tests.py
┃ ┣ 📃urls.py
┃ ┣ 📃users_urls.py
┃ ┗ 📃views.py
┣ 📃.gitattributes
┣ 📃.gitignore
┣ 📃Dockerfile
┣ 📃README.md
┣ 📃README.md
┣ 📃docker-compose-blue.yml
┣ 📃docker-compose-common.yml
┣ 📃docker-compose-green.yml
┣ 📃grafana.ini
┣ 📃manage.py
┣ 📃nginx.conf
┣ 📃requirements.txt
┗ 📃start_celery_flower.sh
</code>
</pre>
</details>
<details>
    <summary>AILIBI-Frontend</summary>
<pre>
<code>
🗂️AILIBI-Frontend
┣ 📂.github
┃ ┣ 📂ISSUE_TEMPLATE
┃ ┗ 📂workflows
┣ 📂public
┃ ┣ 📂fonts
┃ ┣ 📂images
┃ ┣ 📂mp4
┃ ┣ 📂sounds
┃ ┣ 📃logo.png
┃ ┗ 📃vite.svg
┣ 📂src
┃ ┣ 📂assets
┃ ┃ ┗ 📃react.svg
┃ ┣ 📂components
┃ ┃ ┣ 📃EndingPage.css
┃ ┃ ┣ 📃LogInPage.css
┃ ┃ ┣ 📃SignupBox.css
┃ ┃ ┗ 📃VideoPage.css
┃ ┣ 📂hooks
┃ ┃ ┣ 📃UserContext.tsx
┃ ┃ ┗ 📃axiosInstance.ts
┃ ┣ 📂mocks
┃ ┃ ┗ 📃webSocketService.ts
┃ ┣ 📂pages
┃ ┃ ┣ 📃ChattingPage.tsx
┃ ┃ ┣ 📃ChoosePage.tsx
┃ ┃ ┣ 📃EndingPage.tsx
┃ ┃ ┣ 📃EvidencePage.tsx
┃ ┃ ┣ 📃GamePage1.tsx
┃ ┃ ┣ 📃HistoryNote.tsx
┃ ┃ ┣ 📃HistoryPopUp.tsx
┃ ┃ ┣ 📃InitChatPage.tsx
┃ ┃ ┣ 📃LeftPage.tsx
┃ ┃ ┣ 📃LoadingScenarioPage.tsx
┃ ┃ ┣ 📃LogInPage.tsx
┃ ┃ ┣ 📃LoginBox.tsx
┃ ┃ ┣ 📃MainAudioContext.tsx
┃ ┃ ┣ 📃MainPage.tsx
┃ ┃ ┣ 📃MakeScenarioPage.tsx
┃ ┃ ┣ 📃NotePage.tsx
┃ ┃ ┣ 📃PlayAudioContext.tsx
┃ ┃ ┣ 📃PlayHistoryPage.tsx
┃ ┃ ┣ 📃PlayPage.tsx
┃ ┃ ┣ 📃ResultLoadingPage.tsx
┃ ┃ ┣ 📃RightPage.tsx
┃ ┃ ┣ 📃SignupBox.tsx
┃ ┃ ┣ 📃SudokuGame.tsx
┃ ┃ ┣ 📃SuspectPage.tsx
┃ ┃ ┣ 📃TTSService.tsx
┃ ┃ ┗ 📃vite-env.d.ts
┃ ┣ 📂services
┃ ┃ ┗ 📃vite-env.d.ts
┃ ┣ 📃App.css
┃ ┣ 📃App.tsx
┃ ┣ 📃index.css
┃ ┣ 📃main.tsx
┃ ┗ 📃vite-env.d.ts
┣ 📃.gitignore
┣ 📃Dockerfile
┣ 📃README.md
┣ 📃docker-compose.yml
┣ 📃eslint.config.js
┣ 📃index.html
┣ 📃package-lock.json
┣ 📃package.json
┣ 📃postcss.config.cjs
┣ 📃tailwind.config.js
┣ 📃tsconfig.app.json
┣ 📃tsconfig.json
┣ 📃tsconfig.node.json
┗ 📃vite.config.ts
</code>
</pre>
</details>
<br>

# 🧐 How To Start

### Backend 
```
git clone --recursive https://github.com/2024-Winter-Bootcamp-team-K/AILIBI-Backend.git
```
### env setting in the Backend folder
* Backend/.env
```
DB_ENGINE=
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=

OPENAI_API_KEY=

NAVER_CLIENT_ID=
NAVER_CLIENT_SECRET=

ELEVENLABS_API_KEY=
ELEVENLABS_MODEL_ID=
TASK_1_VOICE_ID=
TASK_2_VOICE_ID=
TASK_3_VOICE_ID=
```
### Run Docker
```
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml down

docker-compose -f docker-compose-common.yml -f docker-compose-green.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml down
```
### Frontend
```
git clone --recursive https://github.com/2024-Winter-Bootcamp-team-K/AILIBI-Frontend.git
```
### Install
```
npm run dev
```
<br>

# 👨‍👩‍👧‍👦 Team Members
<table width="1000">
<thead>
</thead>
<tbody>

<tr>
<th>Name</th>
<td width="100" align="center">박근채</td>
<td width="100" align="center">여상윤</td>
<td width="100" align="center">박수용</td>
<td width="100" align="center">김승민</td>
<td width="100" align="center">이수연</td>
<td width="100" align="center">박명남</td>
</tr>

<tr>
<th>Profile</th>
<td width="100" align="center">
<a href="https://github.com/pgc0419">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Grassyeochi">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/parksooyong03">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/ksm0520">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/URsuyeon">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/myungnam1">
<img src="https://github.com/user-attachments/assets/0d75e2eb-cc92-4fc2-814d-768bd86f992b" width="60" height="60">
</a>
</td>
</tr>

<tr>
<th>Role</th>
<td width="190" align="center">
Leader<br>
Full Stack<br>
DevOps<br>
Design<br>
</td>
<td width="190" align="center">
Backend<br>
DevOps<br>
</td>
<td width="190" align="center">
Backend<br>
DevOps<br>
</td>
<td width="190" align="center">
Frontend<br>
Design<br>
</td>
<td width="190" align="center">
Frontend<br>
Design<br>
</td>
<td width="190" align="center">
Frontend<br>
Design<br>
</td>

<tr>
<th>GitHub</th>
<td width="100" align="center">
<a href="https://github.com/pgc0419">
<img src="http://img.shields.io/badge/pgc0419-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/Grassyeochi">
<img src="http://img.shields.io/badge/Grassyeochi-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/parksooyong03">
<img src="http://img.shields.io/badge/parksooyong03-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/ksm0520">
<img src="http://img.shields.io/badge/ksm0520-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/URsuyeon">
<img src="http://img.shields.io/badge/URsuyeon-green?style=social&logo=github"/>
</a>
</td>
<td width="100" align="center">
<a href="https://github.com/myungnam1">
<img src="http://img.shields.io/badge/myungnam1-green?style=social&logo=github"/>
</a>
</td>
</tr>
</tbody>
</table>
<br>
