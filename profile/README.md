#  👋 시니어 스마트 도우미앱 Beeper




# Beeper
어떻게 하는지 모르시겠다고요? 무엇이든 물어보세요!
모르는 것이 있으면 무엇이든 저희 학생들이 알려드립니다!

## 프로젝트 소개

- Beeper는 시니어분들을 위해 언제 어디서나 궁금증을 해결할 수 있도록 도움을 주는 도우미 앱 입니다.
- 모르는 것이 있다면 음성 인식 버튼 하나로 질문을 할 수 있습니다.
- AI로 요약된 내용은 도우미들의 키워드에 맞춰서 알림이 전달됩니다.
- 도우미 분들은 화상채팅을 통해 시니어 분들의 궁금증을 해결해드리고 마일리지를 적립하게 됩니다.

<br>

# Team    

Last Dance
 

<br>

## 팀원 소개

<div align="center">

| **문지혜** | **이기정** | **이주현** | **정은혁** |
| :------: |  :------: | :------: | :------: |
| [<img src="https://avatars2.githubusercontent.com/u/67064571?v=4?s=100" height=150 width=150 alt="Back-End"/> <br/> @Jihye Moon](https://github.com/Dev-JihyeMoon) | [<img width=150 height=150 alt="스크린샷 2024-08-13 오후 5 55 32" src="https://github.com/user-attachments/assets/e175d555-a463-47e7-8edb-be2c4c991e12" alt="AI / Front-End"/> <br/> @이기정](https://github.com/a8534751) | [<img src="https://avatars.githubusercontent.com/u/127174197?s=400&v=4" height=150 width=150 alt="Back-End"/> <br/> @ImitationProgramer](https://github.com/ImitationProgramer) | [<img src="https://avatars.githubusercontent.com/u/69712631?v=4" height=150 width=150 alt="Front-End"/> <br/> @EunHyeokJung](https://github.com/EunHyeokJung) |

</div>

<br>

## 역할 분담
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
  
🧐정은혁
  - 기획 & Front-end developer
  - 어르신도 사용하기 편한 UI/UX 만들기!
  - webRTC 화상통화 개발
  - Flutter로 전체 페이지 제작
  - Build with AI! 🤖
  - 발표자!

<br>

## 1. 개발 환경
- Front-End : Flutter<br>
- Back-End : Spring Boot, JPA, API 개발<br>
- AI : FastAPI, LangChain<br>
- 버전 및 이슈 관리 : Github, Github Issues, Github Project, Git-flow<br>
- 협업 툴 : Notion<br>
- Infra : GCP, Git, Docker, Jenkins<br>
- 디자인 : Figma<br>
- Build with AI! Claude 3.5 sonnet, ChatGPT 4.0o

<br>

## 기술 스택

### FE ###
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>


### BE ###
<img src="https://img.shields.io/badge/spring%20boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/spring%20data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<br>
### AI ###
<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white"> <img src="https://img.shields.io/badge/Langchain-teal?style=for-the-badge">
### Infra ###
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonAWS&logoColor=white"> <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white"> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
&nbsp;
### 🔨  Tools 🔨 
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white"/> <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white"/>

<br>


## 2. 채택한 개발 기술
<br>

## Flutter

 - 첫째, Flutter는 위젯 기반 프레임워크로서 강력한 생산성을 제공합니다. 이를 통해 개발자는 재사용 가능한 컴포넌트를 쉽게 만들고 유지보수할 수 있습니다. 위젯 시스템은 직관적이고 일관성이 있어, 한 번 배워두면 다양한 UI 요소를 빠르게 구현할 수 있습니다.

 - 둘째, Flutter는 단일 코드베이스로 iOS와 Android 두 플랫폼에서 네이티브 수준의 성능을 제공하는 앱을 개발할 수 있습니다. 이는 개발 시간과 비용을 크게 절감해주며, 동시에 두 플랫폼에서 일관된 사용자 경험을 제공할 수 있게 합니다.

 - 셋째, Flutter는 다양한 라이브러리와 패키지를 통해 컴퓨터 비전, AI 등의 복잡한 기능도 쉽게 구현할 수 있습니다. 예를 들어, flutter.dev에 있는 라이브러리들은 이미지 인식, 자연어 처리 등 고급 기능을 지원해주기 때문에, 웹과 앱만을 공부한 개발자들도 충분히 활용할 수 있습니다. 이는 개발자의 학습 곡선을 완화시키고, 프로젝트의 기술적 범위를 확장하는 데 도움을 줍니다.

 - 넷째, Flutter의 Hot Reload 기능은 개발 생산성을 극대화합니다. 코드 변경 사항을 즉시 반영하여 UI를 실시간으로 확인할 수 있기 때문에, 개발 속도가 빨라지고 디버깅이 용이해집니다.

 - 다섯째, Flutter 커뮤니티는 매우 활발하며, 방대한 양의 문서와 예제 코드가 제공되어 있어 개발 중에 직면하는 문제를 빠르게 해결할 수 있습니다. 이는 개발자의 작업 효율성을 높이고, 프로젝트의 안정성을 보장하는 데 큰 도움이 됩니다.


## JPA
 - 첫째, JPA는 객체 관계 매핑(ORM)을 통해 데이터베이스와의 상호 작용을 단순화합니다. 이를 통해 개발자는 데이터베이스의 테이블을 직접 다루지 않고, 객체를 통해 데이터를 조작할 수 있습니다. 이는 코드의 가독성을 높이고, 유지보수를 쉽게 합니다.

 - 둘째, JPA는 데이터베이스 독립성을 제공합니다. 즉, 특정 데이터베이스에 종속되지 않고, 다양한 데이터베이스 시스템(MySQL, PostgreSQL, Oracle 등)에서 사용할 수 있습니다. 이는 데이터베이스 변경 시에도 애플리케이션 코드의 수정이 최소화되도록 합니다.

 - 셋째, JPA는 강력한 쿼리 언어인 JPQL(Java Persistence Query Language)을 제공합니다. JPQL은 객체지향적인 문법을 사용하여 복잡한 쿼리를 작성할 수 있게 해주며, SQL에 비해 더 간결하고 이해하기 쉽습니다. 이를 통해 개발자는 효율적으로 데이터 검색 및 조작을 수행할 수 있습니다.

 - 넷째, JPA는 트랜잭션 관리를 자동으로 처리해줍니다. 이를 통해 데이터 일관성을 유지하고, 여러 데이터 조작 작업을 하나의 논리적 단위로 묶어 원자성을 보장할 수 있습니다. 이는 데이터 무결성을 보호하는 데 중요한 역할을 합니다.

 - 다섯째, JPA는 강력한 캐싱 메커니즘을 제공합니다. 이는 반복적인 데이터베이스 접근을 줄여 애플리케이션 성능을 향상시키고, 응답 속도를 빠르게 합니다. 1차 캐시와 2차 캐시를 통해 효율적인 데이터 관리를 할 수 있습니다.

 - 여섯째, JPA는 대규모 커뮤니티와 광범위한 문서화가 되어 있어, 개발 중 발생하는 문제를 해결하는 데 큰 도움이 됩니다. 다양한 예제 코드와 가이드가 제공되어 있어, 학습과 적용이 용이합니다.

  
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

## ✨️️주요 기능
1. 간편한 질문 방법
2. 재빠른 답변 시간
3. 질문자와 답변자 모두 만족하는 상부상조 시스템

## 🖥️ 서비스 화면
### 로그인 화면
![KakaoTalk_Video_2024-08-14-05-15-52](https://github.com/user-attachments/assets/7b6e93a4-a6fb-4fb1-afac-447f44ee5aac)

### 음성 인식 화면
![KakaoTalk_Video_2024-08-14-05-15-52-2](https://github.com/user-attachments/assets/86a4d962-4368-4e62-9ea8-4b29d7172656)

### 화상 채팅 화면
![KakaoTalk_Video_2024-08-14-05-44-05](https://github.com/user-attachments/assets/1f82ee30-7c62-4b67-9171-5dbef4954074)

### 대시보드(도우미)
![KakaoTalk_Video_2024-08-14-05-15-52-5](https://github.com/user-attachments/assets/c600194d-a62c-497d-a51c-40ab4ccc7fae)


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
