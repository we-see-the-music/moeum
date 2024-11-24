# 🥁 모두의 음악: 모음
### 청각 장애인을 위한 음악 및 가사 시각화 웹 서비스
![모두의 음악 홍보용 대표 이미지](./promo.png)

<br/>

## 프로젝트 소개
- **진행 기간:** 2024.10.14 ~ 2024.11.18 (5주)
- **팀 구성:** 프론트엔드 3인, 백엔드 3인 (총 6인)

<br/>

## 모음의 기술
#### 🎨 Frontend
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/react router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white"> <img src="https://img.shields.io/badge/matter.js-4B5562?style=for-the-badge&logo=matter.js&logoColor=white"> <img src="https://img.shields.io/badge/zustand-413C36?style=for-the-badge&logoColor=white">

#### 🔨 Backend
<img src="https://img.shields.io/badge/spring boot-6db33f?style=for-the-badge&logo=spring boot&logoColor=white"> <img src="https://img.shields.io/badge/spring security-6db33f?style=for-the-badge&logo=spring security&logoColor=white"> <img src="https://img.shields.io/badge/redis-ff4438?style=for-the-badge&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/rabbitmq-ff6600?style=for-the-badge&logo=rabbitmq&logoColor=white"> <img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white"> <img src="https://img.shields.io/badge/mongodb-47a248?style=for-the-badge&logo=mongodb&logoColor=white">

#### 📊 Data Analysis & AI
<img src="https://img.shields.io/badge/python-3776ab?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/hugging face-ffd21e?style=for-the-badge&logo=hugging face&logoColor=black"> <img src="https://img.shields.io/badge/librosa-7902A2?style=for-the-badge"> <img src="https://img.shields.io/badge/tensorflow-ff6f00?style=for-the-badge&logo=tensorflow&logoColor=white"> <img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white">

#### 🗃 CI/CD & Server
<img src="https://img.shields.io/badge/jenkins-d24939?style=for-the-badge&logo=jenkins&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ed?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/amazon ec2-ff9900?style=for-the-badge&logo=amazon ec2&logoColor=white"> <img src="https://img.shields.io/badge/amazon s3-569a31?style=for-the-badge&logo=amazon s3&logoColor=white">

#### 💻 Utility
<img src="https://img.shields.io/badge/gitlab-fc6d26?style=for-the-badge&logo=gitlab&logoColor=white"> <img src="https://img.shields.io/badge/jira-0052cc?style=for-the-badge&logo=jira&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/mattermost-0058cc?style=for-the-badge&logo=mattermost&logoColor=white">

<br/>

## 담당 분야
#### 백엔드
- Music 서비스 내부 API 구현
  - 앨범 정보 및 좋아요 CRUD
  - 아티스트 정보 및 좋아요 CRUD
  - 음악 업로드 및 시각화 데이터 요청
- Recommendation 서비스 내부 API 중 재생 기록 관련 기능 구현
- Spring Boot 백엔드 서버와 FastAPI 백엔드 서버를 연결
  - 관리자가 음악을 업로드하면 시각화 데이터를 생성하는 파이프라인 구축
#### 데이터 분석 및 AI
- librosa, spotipy 패키지를 이용한 음악 분석
- OpenAI 음성 분석 AI 모델을 이용한 마디별 대표음 분석
