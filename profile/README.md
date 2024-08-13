#  👋 시니어 스마트 도우미앱 Beeper

<img width="700" height="700" alt="스크린샷 2024-08-14 오전 1 05 35" src="https://github.com/user-attachments/assets/366abf88-85c9-40e7-9454-3ba24f6f3fca">


# Team    

Last Dance
 
Test ID : 12
Test PW : 12

<br>

# Beeper
어떻게 하는지 모르시겠다고요? 무엇이든 물어보세요!
모르는 것이 있으면 무엇이든 저희 학생들이 알려드립니다!

## 프로젝트 소개

- Beeper는 시니어분들을 위해 언제 어디서나 궁금증을 해결할 수 있도록 도움을 주는 도우미 앱 입니다.
- 모르는 것이 있다면 음성 인식 버튼 하나로 질문을 할 수 있습니다.
- AI로 요약된 내용은 도우미들의 키워드에 맞춰서 알림이 전달됩니다.
- 도우미 분들은 화상채팅을 통해 시니어 분들의 궁금증을 해결해드리고 마일리지를 적립하게 됩니다.

<br>

## 팀원 소개

<div align="center">

| **문지혜** | **이기정** | **이주현** | **정은혁** |
| :------: |  :------: | :------: | :------: |
| [<img src="https://avatars2.githubusercontent.com/u/67064571?v=4?s=100" height=150 width=150 alt="Back-End"/> <br/> @Jihye Moon](https://github.com/Dev-JihyeMoon) | [<img width=150 height=150 alt="스크린샷 2024-08-13 오후 5 55 32" src="https://github.com/user-attachments/assets/e175d555-a463-47e7-8edb-be2c4c991e12" alt="AI / Front-End"/> <br/> @이기정](https://github.com/a8534751) | [<img src="https://avatars.githubusercontent.com/u/127174197?s=400&v=4" height=150 width=150 alt="Back-End"/> <br/> @ImitationProgramer](https://github.com/ImitationProgramer) | [<img src="https://avatars.githubusercontent.com/u/69712631?v=4" height=150 width=150 alt="Front-End"/> <br/> @EunHyeokJung](https://github.com/EunHyeokJung) |

</div>

<br>

## 1. 개발 환경
- Front-End : Flutter<br>
- Back-End : Spring Boot, JPA, API 개발<br>
- AI : FastAPI, LangChain<br>
- 버전 및 이슈 관리 : Github, Github Issues, Github Project, Git-flow<br>
- 협업 툴 : Notion<br>
- Infra : GCP, Git, Docker, Jenkins<br>
- 디자인 : Figma<br>

<br>

## 기술 스택

### FE ###
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/java-02569B?style=flat-square&logo=flutter&logoColor=white"/>


### BE ###
<img src="https://img.shields.io/badge/spring%20boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/spring%20data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<br>
### AI ###
<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white"> <img src="https://img.shields.io/badge/Langchain-teal">
### Infra ###
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonAWS&logoColor=white"> <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
&nbsp;
### 🔨  Tools 🔨 
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=PyCharm&logoColor=white"/>

<br>


## 2. 채택한 개발 기술
<br>

## Flutter
 Flutter는 위젯기반 프론트 프레임워크로서 강력한 생산성을 제공합니다. 다양하게 컨포넌트를 구현하여 개발할 수 있는 만큼 효율적으로 개발할 수 있을 것이라 생각하였습니다. 또한 flutter.dev에 있는 다양한 종류의 라이브러리는 컴퓨터 비전이나 AI등 다양한 기능들을 구현해놓아 웹,앱밖에 공부하지 않은 개발자들도 충분히 사용할 수 있어 채택하였습니다.

## JPA
  -  JPA는 데이터베이스 벤더에 종속되지 않기 때문에 다양한 데이터베이스로 쉽게 전환할 수 있는 유연성을 제공합니다. 캐시 메커니즘을 통한 성능 최적화가 가능하며, 복잡한 쿼리를 쉽게 작성할 수 있는 JPQL (Java Persistence Query Language)을 지원합니다. 따라서, JPA는 데이터 접근 계층을 단순화하고, 개발 시간을 단축시키며, 코드의 가독성과 유지보수성을 높이기 위해 사용했습니다.
  -  Repository 접근을 이미 만들진 메소드를 통해 가능하다는 점에서도 선택을 하게 되었습니다.
  
## LangChain
  - 랭체인은 벡터DB 특유의 벡터기반 검색방식이 특정 문자열이나 키워드를 서칭,추출에 특화되어있어 사용했습니다. 특히 conversation함수의 자문자답방식은 기존의 프롬프트와는 달리 모든 프롬프트가 랭체인내 저장되어있는 데이터에 근거하기에
    여러곳에서 근거를 끌어와 일관성을 해치는 기존의 멀티 턴 방식의 프롬프트와의 차별성을 가져 점점 태그들을 하나하나 지워가며 적정 태그를 찾는 태깅방식에 적합하다고 판단하여 사용했습니다.

## 3. 브랜치 전략
- Git-flow 전략을 기반으로 main, develop 브랜치와 feature, release, hotfix 보조 브랜치를 운용했습니다.
  - main 브랜치는 배포 단계에서만 사용하는 브랜치
  - develop 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치(merge)
  - feature 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 삭제
  - release 브랜치는 develop에서 master로 merge하기 전에 품질 검사를 진행하는 브랜치
  - hotfix 브랜치는 출시 버전에서 발생한 버그를 수정하는 브랜치
  
<br>

## 4. 역할 분담
<br>

😎문지혜
  - Back-End Develop
  - 

🫅🏼이기정(팀장)
  - UI 
  - AI
    - LangChain을 사용한 키워드 최적화 기능 구현
    - Speak to Text,LLM을 이용한 녹음본의 요약정리(Whisper, Cloverspeech, gpt-4o)
    - AI API개발

🥔이주현
  - Back-End Develop
    - firebase 기반 개발 진행
    - webRTC 사용을 위한 웹 소캣 개발 진행
    - ERD 개발 진행
  - README 등 소개 파일 및 발표 피피티 준비
  
🦝정은혁
  - UI
  - 

<br>

## ✨️️주요 기능
1. 간편한 질문 방법
2. 재빠른 답변 시간
3. 질문자와 답변자 모두 만족하는 상부상조 시스템

## 🖥️ 서비스 화면
### 로그인 화면

### 음성 인식 화면

### 화상 채팅 화면

### 대시보드(도우미)

### 대시보드(시니어)


## ERD

<img width="826" alt="스크린샷 2024-08-13 오후 11 03 08" src="https://github.com/user-attachments/assets/77e3f658-6d34-406d-8172-2c59a2e26671">

<br>

## 폴더 구조

<details>
  <summary>Front</summary>
</details>
<details>
  <summary>Back</summary>
</details>
