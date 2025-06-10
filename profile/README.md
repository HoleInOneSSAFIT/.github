## 프로젝트 개요

- **프로젝트명**: SSAFIT  
- **프로젝트 기간**: 2025.05.14 ~ 2025.05.28  
- **목표**:  
  운동을 시작하고 싶지만 막막함 때문에 망설이는 사용자에게 **맞춤 운동 루틴을 추천**하고,  
  **루틴 공유 및 커뮤니티 활동을 통해 지속 가능한 운동 습관**을 형성하도록 돕는 것  
- **타겟**:  
  - 운동을 처음 시작하는 초보자  
  - 매번 똑같은 루틴에 지루함을 느끼는 사용자  
  - 다른 사람의 운동 루틴을 참고하거나 공유하며 동기부여를 받고 싶은 사용자  
<br>

## 프로젝트 소개

운동을 처음 시작하는 사람들은 정보의 홍수 속에서 루틴을 선택하기 어렵고, 지속적으로 동기를 유지하는 것도 쉽지 않습니다.  
SSAFIT은 이러한 문제를 해결하기 위해 다음과 같은 기능을 제공합니다:
- 알고리즘 기반 운동 영상 자동 추천  
- 커뮤니티 내에서 루틴 공유 및 피드백 기능  
- 다양한 사용자의 루틴을 참고할 수 있는 소셜 피드 구성  

이를 통해 사용자는 자연스럽게 운동 루틴을 시작하고, 꾸준히 운동 습관을 만들어갈 수 있는 발판을 마련할 수 있습니다.  
<br>

## 팀원 소개

<div align="center">

| <img src="https://img.shields.io/badge/Project_Leader-FF5733" /> | <img src="https://img.shields.io/badge/Team_Member-%2300264B" /> |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|      <img src="https://avatars.githubusercontent.com/u/195052290?v=4" width="120px;" alt="김윤정" />      |      <img src="https://avatars.githubusercontent.com/u/180911275?v=4" width="120px;" alt="이현지" />      |
|           [김윤정](https://github.com/yoonjeongKm)           |           [이현지](https://github.com/hyunjilee1132)           |
|  팀장 - 운동 루틴 생성 및 커뮤니티 기능 담당  |  팀원 - 유저 관리 및 커뮤니티 댓글 기능 담당  |

</div>
<br>

## 개발환경 및 개발도구
### Frontend<br/>
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

### Backend<br/>
![SpringBoot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)
![Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

### DataBase<br/>
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![mybatis](https://img.shields.io/badge/mybatis-555555.svg?&style=for-the-badge&logo=mybatis&logoColor=white)

### Infra<br/>
![Amazon S3](https://img.shields.io/badge/Amazon_S3-232F3E?style=for-the-badge&logo=Amazon_S3&logoColor=white)

### build<br/>
![Maven](https://img.shields.io/badge/apachemaven-%23757575?style=for-the-badge&logo=apachemaven&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### 협업<br/>
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
<br>

## ERD
![Image](https://github.com/user-attachments/assets/8df9f3ed-101d-4019-ac9c-2c746dd7f9f9)
| 테이블명        | 설명                 |
|-----------------|----------------------|
| user            | 회원 정보            |
| routine         | 운동 루틴            |
| routine_video   | 운동 루틴과 운동 영상 매핑 |
| youtube_video   | 유튜브 영상 메타데이터 |
| uploaded_video  | 직접 업로드한 영상 정보 |
| post            | 운동 루틴 공유 게시글 |
| post_file       | 게시글 첨부 파일      |
| comment         | 게시글 댓글 및 대댓글  |
| post_like       | 게시글 좋아요         |
<br>

## 프로젝트 실행 가이드
### holeinone-server 실행

- `holeinone-server/src/main/resources` 경로에 `application.properties` 파일을 생성합니다.
- 다음과 같은 설정 항목들을 환경에 맞게 작성해야 합니다:
  - 데이터베이스(MySQL) 연결 정보
  - 유튜브 API 키
  - JWT 비밀 키
  - AWS S3 관련 설정
- 초기 데이터베이스 스키마는 `holeinone-server/src/main/resources/ssafit.sql` 파일을 참고해 구성합니다.

### holeinone-front 실행

- `holeinone-front` 디렉토리에서 다음 명령어를 실행해 개발 서버를 시작합니다:

```bash
cd holeinone-front
npm install
npm run dev
