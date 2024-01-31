<div align=center>

![a](https://github.com/2023WB-TeamB/Backend/assets/154852834/dc9f71a6-d196-4cae-adda-a4fccdf23b69)<br>

**깃허브 연동을 통해 기술 블로그, README 등의 문서화 작업을 효율적으로 도와주는 서비스입니다.**


</div>
<br/><br/><br/><br/>

## 📝 Table of Contents

- [Medium](#-medium)
- [Demo](#-demo)<br>
- [System Architechture](#-system-architechture)<br>
- [Tech stack](#-tech-stack)<br>
- [ERD](#-erd)<br>
- [API](#-api)<br>
- [Monitoring](#-monitoring)<br>
- [How to Start](#-how-to-start)<br>
- [File Directory](#-file-directory)<br>
- [Member](#-member)<br>

<br/><br/><br/>

## 📒 Medium

🔗 https://medium.com/@woal9844/siliconvalley-winter-bootcamp-gitodoc-korean-e35907b4b030<br>

<br/><br/><br/>

## 📹 Demo



<br/><br/><br/>

## 💻 System Architechture

<img width="996" alt="archi" src="https://github.com/2023WB-TeamB/Backend/assets/154852834/4627241f-6215-4fdb-9584-3efac0b9eab2">

<br/><br/><br/>

## 💡 Tech stack

<br>
<div align =center>

|      분야      |                                                                                                                                                                                                                                                                                                                                                                  사용 기술                                                                                                                                                                                                                                                                                                                                                                   |
| :------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  **Fronted**   |                                           <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">                                             |
|  **Backend**   |                                  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white"> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/cloud sql-2496ED?style=for-the-badge&logo=&logoColor=white">                                  |
|   **DevOps**   |                                                                                            <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/github actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/compute engine-2496ED?style=for-the-badge&logo=&logoColor=white">                                                                                           |
| **Monitoring** |                                                                                                                                                                                                                                                           <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white">                                                                                                                                                                                                                                                             |
|    **etc**     | <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/chat gpt-009639?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white"> <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> |

</div>
<br/><br/><br/>

## 💾 ERD

<img width="1213" alt="ERD" src="https://github.com/2023WB-TeamB/Backend/assets/154852834/41023269-d808-4f21-8e0c-abe3c8e81a47">

<br/><br/><br/>

## 📚 API

### swagger

<div markdown="1">
  
<img width="738" alt="api" src="https://github.com/2023WB-TeamB/Backend/assets/154852834/3a2926bd-985b-4e41-af7e-78c49d0dc897">
  
</div>
<br/><br/><br/>

## 📈 Monitoring

### Grafana & Prometheus

![grafana](https://github.com/2023WB-TeamB/Backend/assets/154852834/7fee2bfb-909c-463d-bc0c-077f25850685)

<br/><br/><br/>

## 🚀 How to Start

<br/>

#### 1. clone the repository(docker-GCP)<br>
```
git clone https://github.com/2023WB-TeamB/Docker-GCP.git
```

<br/>

#### 2. Set environment file<br>
Path : Docker-GCP/backend/.env<br>
    
```
SECRET_KEY=''

DATABASE_ENGINE=
DATABASE_NAME=''
DATABASE_USER=''
DATABASE_PASSWORD=''
DATABASE_HOST=
DATABASE_PORT=
DATABASE_OPTIONS=init_command=''

GPT_SECRET_KEY=''

ENG_TITLE_ASSISTANT_ID=''
KOR_TITLE_ASSISTANT_ID=''

ENG_OUTLINE_ASSISTANT_ID=''
KOR_OUTLINE_ASSISTANT_ID=''

ENG_CODE_ASSISTANT_ID=''
KOR_CODE_ASSISTANT_ID=''

ENG_TECH_STACK_ASSISTANT_ID=''
KOR_TECH_STACK_ASSISTANT_ID=''

ENG_MAIN_FUNCTION_ASSISTANT_ID=''
KOR_MAIN_FUNCTION_ASSISTANT_ID=''

ENG_CORE_ALGORITHM_ASSISTANT_ID=''
KOR_CORE_ALGORITHM_ASSISTANT_ID=''


FRAMEWORK_ASSISTANT_ID=''

GITHUB_TOKEN=''

RABBITMQ_DEFAULT_USER=
RABBITMQ_DEFAULT_PASS=
RABBITMQ_BROKER=''

AWS_ACCESS_KEY_ID=''
AWS_SECRET_ACCESS_KEY=''
```
<br/>
</div>

#### 3. Set ceritificate.pem , priviate.key<br/>
Path : Docker-GCP/nginx/ceritificate.pem<br>
    
```
a
```

<br>
</div>

Path : Docker-GCP/nginx/priviate.key<br>

```
a
```

<br/>

#### 4. run<br>

```
docker-compose -f docker-compose.prod.yml up --build
```

<br/><br/><br/>

## 📁 File Directory

<details>
<summary> #### Click </summary>
<pre>
<code>
  📦Docker-GCP
   ┣ 📂.github
   ┃ ┗ 📂workflows
   ┃   ┗ 📜docker-image.yml
   ┣ 📂backend
   ┃ ┣ 📂.github
   ┃ ┃ ┣ 📂ISSUE_TEMPLATE
   ┃ ┃ ┗ 📂workflows
   ┃ ┃   ┗ 📜django_deploy.yml
   ┃ ┣ 📂badge
   ┃ ┃ ┣ 📜__init__.py
   ┃ ┃ ┣ 📜admin.py
   ┃ ┃ ┣ 📜apps.py
   ┃ ┃ ┣ 📜models.py
   ┃ ┃ ┣ 📜tech_stack_images.py
   ┃ ┃ ┣ 📜tests.py
   ┃ ┃ ┣ 📜urls.py
   ┃ ┃ ┗ 📜views.py
   ┃ ┣ 📂docs
   ┃ ┃ ┣ 📜__init__.py
   ┃ ┃ ┣ 📜admin.py
   ┃ ┃ ┣ 📜AiTask.py
   ┃ ┃ ┣ 📜apps.py
   ┃ ┃ ┣ 📜github.py
   ┃ ┃ ┣ 📜models.py
   ┃ ┃ ┣ 📜serializers.py
   ┃ ┃ ┣ 📜tests.py
   ┃ ┃ ┣ 📜urls.py
   ┃ ┃ ┗ 📜views.py
   ┃ ┣ 📂gtd
   ┃ ┃ ┣ 📜__init__.py
   ┃ ┃ ┣ 📜asgi.py
   ┃ ┃ ┣ 📜celery.py
   ┃ ┃ ┣ 📜settings.py
   ┃ ┃ ┣ 📜urls.py
   ┃ ┃ ┗ 📜wisgi.py  
   ┃ ┣ 📂templates
   ┃ ┃ ┗ 📂tag
   ┃ ┃   ┣ 📜card1.html
   ┃ ┃   ┣ 📜terminal1.html
   ┃ ┃   ┗ 📜terminal2.html
   ┃ ┗ 📂users
   ┃ ┃ ┣ 📜__init__.py
   ┃ ┃ ┣ 📜admin.py
   ┃ ┃ ┣ 📜apps.py
   ┃ ┃ ┣ 📜models.py
   ┃ ┃ ┣ 📜serializers.py
   ┃ ┃ ┣ 📜tests.py
   ┃ ┃ ┣ 📜urls.py
   ┃ ┃ ┣ 📜utils.py 
   ┃ ┃ ┗ 📜views.py
   ┃ ┣ 📜.gitignore
   ┃ ┣ 🐳docker-compose.dev.yml
   ┃ ┣ 🐳Dockerfile
   ┃ ┣ 📜manage.py
   ┃ ┣ 📜prometheus.yml
   ┃ ┣ 📜README.md
   ┃ ┗ 📜requirements.txt
   ┣ 📂frontend
   ┃ ┣ 📂.github
   ┃ ┃ ┗ 📂ISSUE_TEMPLATE
   ┃ ┣ 📂public
   ┃ ┃ ┗ 📜gtd.svg
   ┃ ┣ 📂src
   ┃ ┃ ┣ 📂assets
   ┃ ┃ ┃ ┣ 📂fonts
   ┃ ┃ ┃ ┗ 📂images
   ┃ ┃ ┃   ┣ 📂MainPage
   ┃ ┃ ┃   ┣ 📂mydocs
   ┃ ┃ ┃   ┗ 📂Viewer
   ┃ ┃ ┃     ┗ 📂Badge
   ┃ ┃ ┣ 📂components
   ┃ ┃ ┃ ┣ 📂MainPage
   ┃ ┃ ┃ ┣ 📂mydocs
   ┃ ┃ ┃ ┃ ┣ 📂lower  
   ┃ ┃ ┃ ┃ ┗ 📂upper 
   ┃ ┃ ┃ ┣ 📂ViewEdit
   ┃ ┃ ┃ ┣ 📜BadgeGuide.tsx
   ┃ ┃ ┃ ┣ 📜CloseBtn.tsx
   ┃ ┃ ┃ ┣ 📜GradientBtn.tsx
   ┃ ┃ ┃ ┣ 📜Header.tsx
   ┃ ┃ ┃ ┣ 📜ModalStore.tsx
   ┃ ┃ ┃ ┣ 📜Register.tsx
   ┃ ┃ ┃ ┣ 📜SearchItem.tsx
   ┃ ┃ ┃ ┣ 📜SearchList.tsx
   ┃ ┃ ┃ ┣ 📜Signin.tsx
   ┃ ┃ ┃ ┣ 📜useDebounce.tsx
   ┃ ┃ ┃ ┗ 📜useOutsideClick.tsx
   ┃ ┃ ┣ 📂pages
   ┃ ┃ ┃ ┣ 📜MainPage.tsx  
   ┃ ┃ ┃ ┣ 📜MyDocsPage.tsx  
   ┃ ┃ ┃ ┣ 📜SharedDocPage.tsx  
   ┃ ┃ ┃ ┗ 📜ViewerPage.tsx  
   ┃ ┃ ┣ 📂store
   ┃ ┃ ┃ ┗ 📜store.ts 
   ┃ ┃ ┣ 📜App.css
   ┃ ┃ ┣ 📜App.tsx
   ┃ ┃ ┣ 📜GlobalStyle.tsx
   ┃ ┃ ┣ 📜index.css
   ┃ ┃ ┣ 📜main.tsx
   ┃ ┃ ┗ 📜vite-env.d.ts
   ┃ ┣ 📜.eslintrc.cjs
   ┃ ┣ 📜.gitnore
   ┃ ┣ 📜.prettierrc
   ┃ ┣ 🐳docker-compose.dev.yml
   ┃ ┣ 🐳Dockerfile
   ┃ ┣ 📜Dockerfile.prod
   ┃ ┣ 📜index.html
   ┃ ┣ 📜package.json
   ┃ ┣ 📜README.md
   ┃ ┣ 📜tsconfig.json
   ┃ ┣ 📜tsconfig.node.json
   ┃ ┣ 📜vite.config.ts
   ┃ ┣ 📜yarn.lock
   ┣ 📂nginx
   ┃ ┣ 🐳Dockerfile
   ┃ ┗ 📜nginx.conf
   ┣ 📂prometheus
   ┃ ┗ 📜prometheus.yml
   ┣ 📜.gitmodules
   ┣ 🐳docker-compose.prod.yml
   ┗ 📜README.md

</code>
</pre>
</details>
<br/><br/><br/>

## 😃 Member

| Name    |                   <center>김선재</center>                   |                    <center>고재훈</center>                    |                   <center>김광현</center>                   |                 <center>나희수</center>                 |                     <center>오채영</center>                     |                 <center>김동현</center>                 |                 <center>장태희</center>                 | <center>홍선아</center>    |
| :------ | :---------------------------------------------------------: | :-----------------------------------------------------------: | :---------------------------------------------------------: | :-----------------------------------------------------: | :-------------------------------------------------------------: | :-----------------------------------------------------: | :-----------------------------------------------------: | -------------------------- |
| Profile | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/bc72312e-ea35-4485-bb3e-c21370424fdc" >  | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/43d7c0b7-68d6-43d6-b0da-aa9967687b81" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/e904fe90-ba63-4e2b-91c8-b0a7f69c15b4" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/7a613d01-462d-41ae-9be1-2c1cb1c70681" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/9ff6bf0a-e0e8-4a1a-9a79-a7f62bf06f6b" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/0eacb7bf-714b-474c-b215-a7d78344df81" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/2383d1fa-734a-41c3-a513-e56f45fe6bdb" >   | <img src="https://github.com/2023WB-TeamB/Backend/assets/154852834/a5117cde-e88f-49dd-8327-90b46177b46e" >  |
| role    |                 <center> Team Leader<br> Backend<br> DevOps</center>                  |                  <center> Frontend </center>                  |                 <center> Frontend </center>                 |               <center> Frontend </center>               |                   <center> Frontend </center>                    |  <center> Backend </center>   |          <center>Backend<br> DevOps</center>           | <center>Backend</center> |
| GitHub  | <center>[@sunjae98](https://github.com/sunjae98)</center> | <center>[@hoon99](https://github.com/hoon99)</center> | <center>[@Haron1248](https://github.com/Haron1248)</center> | <center>[@naGGuri](https://github.com/naGGuri)</center> | <center>[@ocy5007](https://github.com/ocy5007)</center> | <center>[@ddhhy](https://github.com/ddhhy)</center> | <center>[@TaeHee00](https://github.com/TaeHee00)</center> | <center>[@HongSeonah](https://github.com/HongSeonah)</center>

</div>

