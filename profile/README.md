# DoodleFilm
# Instruction
프레임에 맞춰 사진을 찍고 커스텀 서비스
</br>
[DoodleFilm](https://medium.com/@wndudwns6824/6e2a73f0c838)
# DEMO
| 메인화면 & 회원가입 | 질문 생성 |
| :---: | :---: |
| |  | 
| **답변 & 캐릭터 생성** | **마이페이지 & 링크 복사** |
|||
| **상세 페이지**| **키워드 차트**|
|||
|**중복 캐릭터 생성 & 이미지 다운로드**|
||

# System Architecture
![teamg doodlefilm (6)](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/system.png)

# Tech Stack


| Frontend | Backend | DevOps | DB | Others |
| :---: | :---: | :---: | :---: | :---: |
|![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)<br> ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white)<br> ![Vite](https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)<br> ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=Tailwind%20CSS&logoColor=white)<br>![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white)<br>![zustand](https://img.shields.io/badge/zustand-ECD53F?style=for-the-badge&logo=zustand&logoColor=white)|![python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)<br> ![django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white)<br> ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white)<br> ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white)<br> ![gunicorn](https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)<br>|![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)<br> ![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=NGINX&logoColor=white)<br> ![AMAZON_EC2](https://img.shields.io/badge/AMAZON_EC2-FF9900?style=for-the-badge&logo=AMAZONEC2&logoColor=white)<br>![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)<br> ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white)<br>![cAdvisor](https://img.shields.io/badge/cAdvisor-FF4500?style=flat-square&logo=cAdvisor%20CSS&logoColor=white)|![MySql](https://img.shields.io/badge/MySql-4479A1?style=for-the-badge&logo=MySql&logoColor=white)<br> ![AMAZON_S3](https://img.shields.io/badge/AMAZON_S3-569A31?style=for-the-badge&logo=AMAZONS3&logoColor=white)<br> ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white)<br> ![mongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white)<br>|![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)<br>![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)<br>![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)<br>


# Database
![ERD](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/ERD.png)<br>


# API
![api_1](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_1.png)<br> ![api_2](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_2.png)<br> ![api_3](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/api_3.png)<br>



## Detailed Info
**NAME** | **Description**
:---:|:---:
| REACT | 사용자 인터페이스를 구축하는데 사용함으로써 사용자가 쉽고 직관적으로 사진 편집 기능을 이용할 수 있는 동적인 웹사이트를 제공합니다. |
| DJANGO | 개발이 빠르고 유지보수가 간편하며 보안 강화에 도움이 됩니다. |
| RABBITMQ | 백그라운드 작업을 비동기적으로 처리하여 서버의 부하를 줄이고 사용자 요청에 빠르게 응답할 수 있게 합니다. |
| CELERY | 사진 처리, AI 스티커 생성과 같이 시간 소요가 큰 작업을 백그라운드에서 처리하여 프론트엔드의 성능 저하 없이 복잡한 작업을 수행할 수 있게 합니다. |
| GUNICORN | Django 애플리케이션의 효율적인 배포를 도와 웹 서비스의 안정성과 응답성을 향상시킵니다. |
| DOCKER | 서비스의 여러 컴포넌트를 독립적으로 관리하고 배포할 수 있게 해주어 개발, 테스팅, 프로덕션 환경 간 일관성을 보장합니다. |
| NGINX | 웹 서버로서 고성능 정적 컨텐츠 제공하여 사용자에게 빠른 페이지 로딩 시간과 안정적인 서비스 경험을 제공합니다. |
| AMAZON EC2 | 사용량에 따라 서버 리소스를 유연하게 조정할 수 있어 트래픽이 많은 시간에도 안정적인 서비스를 제공합니다. |
| PROMETHEUS | 시스템과 애플리케이션의 여러 메트릭을 수집하고 저장합니다. 이 데이터는 시스템의 상태를 감시하고 문제가 발생했을 때 경고를 발생시키는데 도움이 됩니다. |
| GRAFANA | Cadvisor와 Prometheus에서 수집된 데이터를 시각적으로 표현합니다. 대시보드를 통해 사용자가 시스템의 성능 지표를 쉽게 확인하고 분석할 수 있게 합니다. |
| cAdvisor | 컨테이너화된 환경에서 애플리케이션의 리소스 사용량을 모니터링합니다. 이는 시스템의 성능을 실시간으로 파악하고 리소스 관리를 최적화하는데 도움이 됩니다. |
| MYSQL | 사용자 정보, 사진 메타데이터 등의 구조화된 데이터를 관리하는데 사용됩니다. |
| AMAZON S3 | 대용량 사진 데이터 저장에 이상적인 아키텍처로 사용자가 업로드한 사진 및 생성된 인생네컷 사진을 안정하게 저장하고 즉시 접근이 가능합니다. |
| REDIS | 세션 관리와 캐싱에 사용되어 웹사이트의 응답 시간을 단축시킵니다. 이는 사용자가 웹사이트를 빠르고 원활하게 탐색할 수 있게 합니다. |
| MongoDB | 비구조화된 데이터 또는 빠르게 변하는 데이터를 효과적으로 처리합니다. |

# Team Member


| Name | 황장현 | 김정우 | 김진우 | 이윤서 | 주영준 | 
| :---: | :---: | :---: | :---: | :---: | :---: | 
| Profile | ![황장현](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Janghyun.jpg)<br> | ![김정우](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Jeongwoo.jpg)<br> | ![김진우](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Jinwoo.jpg)<br> | ![이윤서](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Yunseo.jpg)<br> | ![주영준](https://github.com/2023-Winter-Bootcamp-TeamG/.github/blob/main/assets/Yeongjun.jpg)<br> | 
| Role | Team Leader</br>Frontend| Backend<br>DevOps | Backend<br>DevOps | Backend<br>DevOps | Frontend |
| GitHub | [JH722](https://github.com/JH722) | [lockyous](https://github.com/lockyous) | [jinu0328](https://github.com/jinu0328) | [LeeYunseo04](https://github.com/LeeYunseo04) | [Ye0ngjun](https://github.com/Ye0ngjun) |
