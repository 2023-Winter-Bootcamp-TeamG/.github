# DoodleFilm
# Instruction
프레임에 맞춰 사진을 찍고 커스텀 서비스
</br>
[DoodleFilm medium]([https://medium.com/@wndudwns6824/6e2a73f0c838](https://medium.com/@wndudwns6824/2023-%EC%8B%A4%EB%A6%AC%EC%BD%98%EB%B0%B8%EB%A6%AC-%EA%B2%A8%EC%9A%B8-%EB%B6%80%ED%8A%B8%EC%BA%A0%ED%94%84-doodlefilm-6e2a73f0c838))
# DEMO
| 메인화면 & 회원가입 | 질문 생성 |
| :---: | :---: |
| ![main_signup](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/25394474-4278-4ded-9013-ce17bf0423b5)|![question](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/f90b2188-d48d-4f42-af51-ffc6e69d65a5)  | 
| **답변 & 캐릭터 생성** | **마이페이지 & 링크 복사** |
|![answer](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/07d3aece-18e7-4b4d-8edc-482a6f6e6498)| ![mypage](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/53093949-1718-4c6e-9dd0-5ae3050eb32d) |
| **상세 페이지**| **키워드 차트**|
|![detail](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/0f8c513f-18fc-427a-817f-50183f3b02a9)|![chart](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/cfcf7af9-b0b6-43d0-9523-f7ad0ebee511)|
|**중복 캐릭터 생성 & 이미지 다운로드**|
|![duplicate](https://github.com/2023-Summer-Bootcamp-Team-G/backend/assets/91904079/0b9191ed-1c9b-4b36-b2ed-c48a26ea760c)

# System Architecture
![teamg doodlefilm (6)](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/system.png)

# Tech Stack


| Frontend | Backend | DevOps | DB | Others |
| :---: | :---: | :---: | :---: | :---: |
|![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)<br> ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white)<br> ![Vite](https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)<br> ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=Tailwind%20CSS&logoColor=white)<br>![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white)<br>![zustand](https://img.shields.io/badge/zustand-ECD53F?style=for-the-badge&logo=zustand&logoColor=white)|![python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)<br> ![django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white)<br> ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white)<br> ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white)<br> ![gunicorn](https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)<br>|![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)<br> ![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white)<br> ![AMAZON_EC2](https://img.shields.io/badge/AMAZON_EC2-FF9900?style=for-the-badge&logo=AMAZONEC2&logoColor=white)<br>![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)<br> ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white)<br>![cAdvisor](https://img.shields.io/badge/cAdvisor%20CSS-FF4500?style=flat-square&logo=cAdvisor%20CSS&logoColor=white)|![MySql](https://img.shields.io/badge/MySql-4479A1?style=for-the-badge&logo=MySql&logoColor=white)<br> ![AMAZON_S3](https://img.shields.io/badge/AMAZON_S3-569A31?style=for-the-badge&logo=AMAZONS3&logoColor=white)<br> ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)<br> ![mongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white)<br>|![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)<br>![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)<br>![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)<br>


# Database
![ERD](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/ERD.png)<br>


# API
![api_1](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_1.png)<br> ![api_2](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_2.png)<br> ![api_3](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_3.png)<br>



## Detailed Info
**NAME** | **Description**
:---:|:---:
Nginx | 웹서버, 프록시 서버, https 연결 등을 담당합니다. | 
React | 질문 생성 및 답변, 캐릭터를 생성하여 보여주는 역할을 담당합니다. | 
Django | It's me의 서버로서 각종 요청을 처리하며 DB와 직접 소통합니다. | 
Gunicorn</br>Uvicorn | Gunicorn으로 Uvicorn 프로세스를 관리하며 요청을 비동기로 처리합니다. |
Mysql(RDS) | Database | 
RabbitMQ | 메세지 브로커로서 이미지 생성 처리 시간이 길기 때문에 사용합니다. | 
Celery | 이미지 생성과 같은 작업을 비동기 수행하기 위해 사용합니다. | 
Grafana | Prometheus로부터 받은 메트릭 데이터 등을 시각화하여 대시보드를 구성합니다. | 
Prometheus | Django의 메트릭 데이터를 수집하여 모니터링 합니다. | 
Filebeat | Nginx의 로그파일을 Filebeat로 수집합니다. | 
Logstash | Filebeat로 수집한 로그를 Logstash에 전달합니다. |
Elasticsearch | Logstash로부터 전달 받은 로그를 Elasticsearch에 저장합니다. | 
Kibana | Elasticsearch에 저장된 로그를 Kibana를 통해 분석 및 시각화합니다. | 

# Team Member


| Name | 황장현 | 김정우 | 김진우 | 이윤서 | 주영준 | 
| :---: | :---: | :---: | :---: | :---: | :---: | 
| Profile | ![황장현](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Janghyun.jpg)<br> | ![김정우](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Jeongwoo.jpg)<br> | ![김진우](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Jinwoo.jpg)<br> | ![이윤서](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Yunseo.jpg)<br> | ![주영준](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Yeongjun.jpg)<br> | 
| Role | Team Leader</br>Frontend| Backend<br>DevOps | Backend<br>DevOps | Backend<br>DevOps | Frontend |
| GitHub | [JH722](https://github.com/JH722) | [lockyous](https://github.com/lockyous) | [jinu0328](https://github.com/jinu0328) | [LeeYunseo04](https://github.com/LeeYunseo04) | [Ye0ngjun](https://github.com/Ye0ngjun) |
