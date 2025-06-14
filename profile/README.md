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

## 페이지 별 기능
## [운동 루틴]
### 1. 운동 영상 추천받기
- **추천 방식**: 인기 기반 / 랜덤 기반
- 사용자가 선택한 **운동 부위**, **운동 시간**, **추천 방식**에 따라 유튜브에 업로드된 운동 영상을 추천받습니다.
- 추천된 영상과 함께 해당 **유튜브 영상의 정보** (제목, 채널명, 썸네일, 영상 길이 등)가 함께 표시됩니다.
- 마음에 들지 않는 경우 **다시 추천받기**를 통해 다른 영상을 받을 수 있습니다.
- 마음에 드는 경우 **운동 후 쉬는 시간**을 입력한 후 임시 루틴에 추가할 수 있습니다.
![운동-영상-추천하기](https://github.com/user-attachments/assets/187ad280-e0ea-4122-b9d2-0454b372caa6)

### 2. 나의 영상 업로드하기
- 사용자가 직접 촬영한 운동 영상을 업로드할 수 있습니다.
- 입력 항목:
  - 영상 제목
  - 운동 부위
  - 운동 시간
  - 운동 후 쉬는 시간
  - 영상 파일
- 모든 정보를 올바르게 입력하면 해당 영상이 **루틴에 추가**됩니다.
![나의-영상-업로드하기](https://github.com/user-attachments/assets/9c13363a-d6dd-465f-8a8d-f2da48987e31)

### 3. 유튜브 영상 직접 등록하기
- 사용자가 원하는 유튜브 영상의 **URL을 직접 입력**하여 등록할 수 있습니다.
- 등록 시 유튜브 영상의 **정보** (제목, 채널명, 썸네일, 영상 길이 등)를 함께 확인할 수 있습니다.
- **운동 부위**와 **운동 후 쉬는 시간**을 입력하면 해당 영상이 루틴에 담깁니다.
![운동 영상 업로드하기](https://github.com/user-attachments/assets/73f8c5c5-b820-4e31-8fc6-1e9f10e2b21f)

### 4. 임시 루틴에서 영상 삭제
- 임시로 담아둔 루틴 영상 목록 중에서 **특정 영상 한 개를 삭제**할 수 있습니다.
![루틴 영상 삭제](https://github.com/user-attachments/assets/41481271-5492-4419-bbcc-a4b2c41c57c7)

### 5. 임시 루틴 초기화
- 임시로 담아둔 **모든 영상 목록을 한 번에 초기화**하여 삭제할 수 있습니다.
![임시 루틴 초기화](https://github.com/user-attachments/assets/c019f74d-905a-49c3-973d-051adfd80493)

### 6. 운동 루틴 완성하기
- 임시 루틴에 담긴 영상 리스트를 바탕으로 **운동 루틴을 생성**합니다.
- **루틴 제목**과 **루틴 설명**을 입력한 뒤 저장하면, 해당 루틴에 포함된 영상 정보와 함께 **루틴 상세 페이지**로 이동합니다.
![운동 루틴 완성하기](https://github.com/user-attachments/assets/c350f326-5a24-4892-94fb-4be60991b4ca)

### 7. 운동 루틴 공유하기
- **루틴 공유하기** 버튼을 클릭하여 루틴을 커뮤니티에 공유할 수 있습니다.
- 게시글 작성 항목:
  - 제목
  - 내용
  - (선택) 파일 첨부
  - (선택) 썸네일 이미지
- 공유할 루틴은 **우측 미리보기 영역**에서 확인할 수 있습니다.
- 게시글을 등록하면 **게시글 상세 페이지**로 이동합니다.
![운동 루틴 공유하기](https://github.com/user-attachments/assets/ca590c59-683a-4506-8c69-a5b938bd9de1)

### 8. 운동 루틴 삭제하기
- 사용자가 직접 생성한 **운동 루틴을 삭제**할 수 있습니다.

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
