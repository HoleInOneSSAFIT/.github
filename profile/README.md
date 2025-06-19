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
|  팀장 - 운동 루틴 생성 및 커뮤니티 게시글 기능 담당  |  팀원 - 유저 관리 및 커뮤니티 댓글 기능 담당  |

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
## [초기화면]
1. **운동 루틴 게시글 부위별 조회**
   - 커뮤니티에 작성된 운동 루틴 게시글을 **운동 부위별로 필터링**하여 조회할 수 있습니다.
   - 예: 전신, 상체, 하체, 복부, 스트레칭 등
![01-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/59d07b07-91c2-4ed0-9bf4-ad3913125afb)

2. **운동 루틴 만들기 버튼**
   - 초기화면에 위치한 **[운동 루틴 만들기]** 버튼 클릭 시, 사용자의 **로그인 상태를 확인**합니다.
   - **비로그인 상태일 경우** 로그인 화면으로 자동 이동하여 사용자 인증을 유도합니다.
![메인2](https://github.com/user-attachments/assets/c5f4eb11-d0df-4bdc-a271-a2da28a03f30)

3. **유튜브에서 영상 찾아보기**
   - 초기화면의 **[유튜브에서 영상 찾아보기]** 버튼 클릭 시, **유튜브 홈으로 이동**합니다.
   - 사용자가 직접 원하는 운동 영상을 검색하고 확인할 수 있습니다.
![메인3](https://github.com/user-attachments/assets/5b66fa26-6d8d-4419-b9a7-adcaea3f84dd)

## [운동 루틴]
### 1. 운동 영상 추천받기
- **추천 방식**: 인기 기반 / 랜덤 기반
- 사용자가 선택한 **운동 부위**, **운동 시간**, **추천 방식**에 따라 유튜브에 업로드된 운동 영상을 추천받습니다.
- 추천된 영상과 함께 해당 **유튜브 영상의 정보** (제목, 채널명, 썸네일, 영상 길이 등)가 함께 표시됩니다.
- 마음에 들지 않는 경우 **다시 추천받기**를 통해 다른 영상을 받을 수 있습니다.
- 마음에 드는 경우 **운동 후 쉬는 시간**을 입력한 후 임시 루틴에 추가할 수 있습니다.
![운동-영상-추천](https://github.com/user-attachments/assets/e7c4fcff-f6b4-474b-96bc-5e4bb2c93195)

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

### 7. 운동 루틴 삭제하기
- 사용자가 직접 생성한 **운동 루틴을 삭제**할 수 있습니다.
![운동-루틴-삭제하기-Trim](https://github.com/user-attachments/assets/0d6adc6f-4390-4b9f-b12b-8a3c6c5dbdb0)

## [커뮤니티 게시글]
### 1. 커뮤니티 게시글 작성
- **[루틴 공유하기]** 버튼을 클릭하여 운동 루틴을 커뮤니티에 공유할 수 있습니다.
- 게시글 작성 항목:
  - 제목
  - 내용
  - (선택) 파일 첨부
  - (선택) 썸네일 이미지
- 공유할 루틴은 **우측 미리보기 영역**에서 확인할 수 있습니다.
- 게시글을 등록하면 **게시글 상세 페이지**로 이동합니다.
![운동 루틴 공유하기](https://github.com/user-attachments/assets/ca590c59-683a-4506-8c69-a5b938bd9de1)

### 2. 커뮤니티 게시글 수정 및 삭제
- 커뮤니티에 작성된 게시글은 언제든지 수정이 가능합니다.
  - 제목, 내용, 첨부 파일, 썸네일 이미지 수정 가능
- 게시글 삭제 시 해당 게시글과 함께 **공유된 운동 루틴도 함께 삭제**됩니다.
![게시글-수정-삭제-_1_ (1)](https://github.com/user-attachments/assets/67b780e7-2568-4640-913a-9fa8626764ee)

### 3. 게시글 상세 페이지
- 공유된 운동 루틴의 **운동 영상 정보를 재생**할 수 있습니다.
- 각 운동 영상이 끝난 후, 사용자가 설정한 **쉬는 시간이 팝업 타이머**로 표시됩니다.
  - 타이머는 중단 가능하며, 종료 후 **다음 영상이 자동 재생**됩니다.
- 영상 목록 중 원하는 영상 선택 시 바로 해당 영상으로 이동할 수 있습니다.
- 하단에 **댓글 조회 및 작성**이 가능하며, **우측 상단에는 작성자 정보**가 표시됩니다.
- **좋아요 기능** 제공: 사용자당 한 번만 클릭 가능
![게시글 기능들](https://github.com/user-attachments/assets/374b10a3-7969-4661-b2b1-97efa0e6b12e)

### 4. 커뮤니티 게시글 최신순 / 인기순 정렬
- 커뮤니티 전체 게시글을 **최신순** 또는 **인기순**으로 정렬하여 조회할 수 있습니다.
![커뮤니티 최신순 인기순](https://github.com/user-attachments/assets/bf7dbf5d-cf95-4795-a997-a78823591e50)

### 5. 커뮤니티 운동 부위별 조회
- 게시글을 운동 부위 기준으로 필터링하여 조회할 수 있습니다.
  - 예: 전신, 상체, 하체, 복부 등
![커뮤니티 운동 부위별 분류](https://github.com/user-attachments/assets/26a69cdc-43d0-4f3e-9eb1-73ba1cddc5b2)

### 6. TOP ROUTINE 조회
- 전체 게시글 중에서 **조회수, 댓글 수, 좋아요 수**에 따라 점수를 차등 부여하여 **상위 4개의 루틴**을 선정해 보여줍니다.
![커뮤니티 탑루틴](https://github.com/user-attachments/assets/f6efed43-4b83-4945-853f-b5d52f1b046d)

<br>

## API 명세서
### AdminController
| HTTP Method | API | Description | Request Body/Params | Response Body | Authorization |
| --- | --- | --- | --- | --- | --- |
| GET | /api/admin/users | 모든 회원 조회 | Header:<br>Authorization: Bearer &lt;accessToken&gt; | List&lt;User&gt;<br>(회원 목록) | O (ROLE_ADMIN) |
| GET | /api/admin/users/{username} | 특정 회원 조회 | Path Variable:<br>username<br>Header:<br>Authorization: Bearer &lt;accessToken&gt; | User<br>(특정 회원 정보) | O (ROLE_ADMIN) |
| DELETE | /api/admin/users/{username} | 특정 회원 탈퇴 | Path Variable:<br>username<br>Header:<br>Authorization: Bearer &lt;accessToken&gt; | "회원이 정상적으로 탈퇴 되었습니다.” | O (ROLE_ADMIN) |

### AuthController
| HTTP Method | API | Description | Request Body/Params | Response Body | Authorization |
| --- | --- | --- | --- | --- | --- |
| GET | /api/auth/check-username | 아이디 중복 확인 | username | Boolean | X |
| GET | /api/auth/check-nickname | 닉네임 중복 확인 | nickname | Boolean | X |
| GET | /api/auth/postlist | 사용자가 작성한 게시글 목록 | Header:<br>Authorization: Bearer &lt;accessToken&gt; | List&lt;Post&gt;<br>(게시글 정보 목록) | O (ROLE_USER) |
| GET | /api/auth/commentlist | 사용자가 작성한 댓글 목록 | Header:<br>Authorization: Bearer &lt;accessToken&gt; | List&lt;CommentResponse&gt;<br>(댓글 목록) | O (ROLE_USER) |
| GET | /api/auth/info | 사용자 정보 | Header:<br>Authorization: Bearer &lt;accessToken&gt; | User<br>(회원 상세 정보) | O (ROLE_USER) |
| POST | /api/auth/register | 회원가입 | Form: UserJoinRequest,<br>Multipart: profileImage | “회원가입 성공” | X |
| POST | /api/auth/login | 로그인 | JSON:<br>{ “username”: “”,<br>“password”: “”} | { “accessToken”: “”},<br>refreshToken(cookie) | X |
| POST | /api/auth/logout | 로그아웃 | Cookie: refreshToken | "로그아웃 되었습니다” | O (ROLE_USER),<br>refreshToken 필요 |
| POST | /api/auth/refresh | 토큰 만료시 재발급 | Cookie: refreshToken | Header:<br>Authorization: Bearer &lt;accessToken&gt; | O (ROLE_USER),<br>refreshToken 필요 |
| PUT | /api/auth/update | 정보수정 | Form: User<br>Header:<br>Authorization: Bearer &lt;accessToken&gt; | "수정이 완료되었습니다.” | O (ROLE_USER) |
| DELETE | /api/auth/delete | 회원탈퇴 | Header:<br>Authorization: Bearer &lt;accessToken&gt; | "계정이 성공적으로 탈퇴 처리 되었습니다.” | O (ROLE_USER) |

### CommentController
| HTTP Method | API | Description | Request Body/Params | Response Body | Authorization |
| --- | --- | --- | --- | --- | --- |
| GET | /api/posts/{postId}/comments | 특정 게시글에 대한 댓글 목록 조회 | PathVariable: postId<br>(댓글을 조회할 게시글의 ID) | List&lt;CommentResponse&gt;<br>(댓글 목록) | X |
| POST | /api/posts/{postId}/comments/write | 댓글 작성 | Header:<br>Authorization: Bearer &lt;accessToken&gt;<br>PathVariable: postId<br>RequestBody: CommentRequest (댓글 내용) | "댓글 등록이 완료되었습니다.” | O (ROLE_USER, ROLE_ADMIN) |
| PUT | /api/posts/{postId}/comments/{commentId} | 댓글 수정 | Header:<br>Authorization: Bearer &lt;accessToken&gt;<br>PathVariable: postId, commentId<br>RequestBody: CommentRequest | "댓글이 성공적으로 수정되었습니다.” | O (ROLE_USER, ROLE_ADMIN) |
| DELETE | /api/posts/{postId}/comments/{commentId} | 댓글 삭제 | Header:<br>Authorization: Bearer &lt;accessToken&gt;<br>PathVariable: postId, commentId | 대댓글이 있는 경우:<br>”(soft-delete) ‘(삭제된 댓글 입니다.)’ 삭제”<br>대댓글이 없는 경우:<br>”(soft-delete) UI상에 안보이게 삭제” | O (ROLE_USER, ROLE_ADMIN) |

### VIDEO_RECOMMEND
| 요구사항ID         | 구분             | 요구사항 이름          | 요구사항 설명                                                             | API                                                   |
|--------------------|------------------|-------------------------|---------------------------------------------------------------------------|--------------------------------------------------------|
| VIDEO_RECOMMEND_01 | VIDEO_RECOMMEND  | 유튜브 영상 검색        | 선택 조건(운동 부위, 영상 길이 등)에 따라 유튜브 API에 요청              | [GET] /api/video/search                                   |
| VIDEO_RECOMMEND_02 | VIDEO_RECOMMEND  | 인기 영상 추천          | 조회수가 높은 영상 중 랜덤 선택                                           | [GET] /api/video/search                                   |
| VIDEO_RECOMMEND_03 | VIDEO_RECOMMEND  | 랜덤 영상 추천          | 조건에 맞는 영상 중 무작위 선택                                           | [GET] /api/video/search                                   |
| VIDEO_RECOMMEND_04 | VIDEO_RECOMMEND  | 영상 다시 추천          | 추천받은 영상 스킵하고 다음 영상 추천                                     | [GET] /api/video/reSearch                                |
| VIDEO_RECOMMEND_05 | VIDEO_RECOMMEND  | 랜덤 영상 선택          | 랜덤 영상 중 하나를 선택해 임시 루틴에 추가                               | [POST] /api/video/youtubeSelect                          |
| VIDEO_RECOMMEND_06 | VIDEO_RECOMMEND  | 임시 루틴 조회          | 임시 등록한 운동 루틴을 순서대로 조회                                     | [GET] /api/video/routineSelect/{sequence}                |
| VIDEO_RECOMMEND_07 | VIDEO_RECOMMEND  | 임시 루틴 삭제          | 임시 루틴 영상 중 하나 삭제                                               | [GET] /api/video/routineDelete/{sequence}                |
| VIDEO_RECOMMEND_08 | VIDEO_RECOMMEND  | 임시 루틴 전체 초기화   | 임시 루틴 전체 초기화                                                     | [GET] /api/video/tempRoutineReset                        |
| VIDEO_RECOMMEND_09 | VIDEO_RECOMMEND  | 임시 루틴 저장          | 선택한 영상(업로드/랜덤 유튜브/URL 입력) 등록                             | [POST] /api/video/insertVideoRoutine                     |
| VIDEO_RECOMMEND_10 | VIDEO_RECOMMEND  | 루틴 등록               | 루틴 생성(루틴명, 설명, 영상 목록, 쉬는 시간 등 입력)                     | [POST] /api/video/insertVideoRoutine                     |
| VIDEO_RECOMMEND_11 | VIDEO_RECOMMEND  | 루틴 삭제               | 운동 루틴 삭제                                                             | [DELETE] /api/video/routineIdDelete/{routineId}          |
| VIDEO_RECOMMEND_12 | VIDEO_RECOMMEND  | 영상 업로드             | 사용자가 직접 찍은 영상 업로드 (S3 저장 + 영상 정보 입력)                 | [POST] /api/video/myUpload                               |
| VIDEO_RECOMMEND_13 | VIDEO_RECOMMEND  | 유튜브 URL 입력         | URL로 입력한 유튜브 영상 정보 불러오고, 운동 부위 및 쉬는 시간 입력       | [POST] /api/video/directYoutubeUrl                       |

### COMMUNITY_POST
| 요구사항ID         | 구분             | 요구사항 이름           | 요구사항 설명                                                                 | API                                                       |
|--------------------|------------------|--------------------------|-------------------------------------------------------------------------------|------------------------------------------------------------|
| COMMUNITY_POST_01  | COMMUNITY_POST   | 게시글 등록              | 게시글 정보 저장 (게시글 + 영상-게시글 매핑 정보 분리 저장)                 | [POST] /api/post/insert                                     |
| COMMUNITY_POST_02  | COMMUNITY_POST   | 게시글 수정              | 제목, 설명, 영상 리스트, 태그 정보 수정                                       | [PUT] /api/post/update/{postId}                             |
| COMMUNITY_POST_03  | COMMUNITY_POST   | 게시글 삭제              | 게시글 및 연관 매핑 정보 삭제. 영상이 고아 상태면 영상도 삭제                | [DELETE] /api/post/{postId}                                 |
| COMMUNITY_POST_04  | COMMUNITY_POST   | 게시글 전체 조회         | 커뮤니티 전체 게시글 리스트 조회                                             | [GET] /api/post/all                                         |
| COMMUNITY_POST_05  | COMMUNITY_POST   | 게시글 상세 조회         | 게시글 상세 정보 조회 (제목, 설명, 영상 목록, 태그, 작성자, 날짜 등)         | [GET] /api/post/{postId}                                    |
| COMMUNITY_POST_06  | COMMUNITY_POST   | 게시글 파일 정보 조회    | 썸네일, 첨부파일 정보 조회                                                    | [GET] /api/post/{postId}/files                              |
| COMMUNITY_POST_07  | VIDEO_RECOMMEND  | 루틴 조회                | 루틴-영상 매핑 정보 조회                                                     | [GET] /api/post/routine/{routineId}/info                    |
| COMMUNITY_POST_08  | VIDEO_RECOMMEND  | 특정 루틴 정보 조회      | 루틴과 연결된 영상 정보 조회                                                 | [GET] /api/post/routine/{routineId}                         |
| COMMUNITY_POST_09  | VIDEO_RECOMMEND  | 게시글 작성 유저 조회    | 게시글 작성자 정보 조회                                                       | [GET] /api/post/user/{postId}                               |
| COMMUNITY_POST_10  | COMMUNITY_POST   | 최신 게시글 조회         | 최신 게시글 1개 조회                                                          | [GET] /api/post/latest                                      |
| COMMUNITY_POST_11  | COMMUNITY_POST   | 인기 게시글 조회         | 좋아요 수 기준 인기 게시글 1개 조회                                           | [GET] /api/post/popular                                     |
| COMMUNITY_POST_12  | COMMUNITY_POST   | 운동 부위별 게시글 조회  | 운동 부위별 필터 게시글 조회 (전체 포함)                                     | [GET] /api/post/part                                        |
| COMMUNITY_POST_13  | COMMUNITY_POST   | 게시글 작성 페이지       | 추천받은 영상 기반 게시글 작성 폼 제공. 제목, 설명, 업로드 지원              | [GET] /api/post/{postId}                                    |
| COMMUNITY_POST_14  | COMMUNITY_POST   | 게시글 좋아요            | 게시글 좋아요 및 좋아요 수 조회                                              | [POST] /api/post/{postId}/like <br> GET /api/post/{postId}/like |
| COMMUNITY_POST_15  | COMMUNITY_POST   | 상세 페이지 조회수 증가   | 상세 조회 시 조회수 증가 처리                                                 | [POST] /api/post/{postId}/increase-view                     |
| COMMUNITY_POST_16  | COMMUNITY_POST   | 댓글 수 조회              | 게시글에 달린 댓글 수 조회                                                    | [GET] /api/post/{postId}/commentCount                       |

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
```
<br>

## 프로젝트 후기
### 🍥김윤정
처음 프로젝트의 주제가 "운동"으로 정해졌을 때, 평소에 운동을 하지 않던 저로서는 어떤 기능을 추가하면 좋을지 많은 고민을 했습니다. 하지만 잘 알지 못하는 부분에 억지로 접근하기보다는, 저 같은 사람들이 사용하기 좋은 운동 사이트가 무엇일까 고민하게 되었습니다.
많은 고민 끝에, 초심자를 위해 운동 루틴을 공유할 수 있는 사이트를 만드는 것이 좋겠다고 판단했습니다. 사이트의 특성상 이미지와 영상을 저장하는 기능이 많았기 때문에 AWS S3를 활용하기로 했고, 이는 결과적으로 좋은 선택이었다고 생각합니다.
백엔드와 프론트엔드를 동시에 진행해야 했기 때문에 일정이 다소 타이트하게 느껴지기도 했지만, 기획했던 기능들은 대부분 구현할 수 있어서 다행이라고 생각합니다.
완벽한 결과라고는 할 수 없지만, 좋은 팀원을 만나 갈등 없이 서로의 의견을 주고받으며 프로젝트를 완성할 수 있었던 것은 정말 소중한 경험이었습니다. 이번 프로젝트를 통해 기획부터 구현, 협업까지 많은 부분을 배우고 성장할 수 있었습니다.
함께 고생해준 팀원에게 고맙다고 말하고 싶습니다!
### 🍥이현지
**Keep**

이번 프로젝트에서 회원 관리와 댓글 기능을 담당했습니다. 

인증 방식은 기존의 세션 기반 인증이 아닌 JWT를 채택했습니다. JWT는 무상태(stateless) 구조를 기반으로 서버 확장성과 성능 측면에서 유리하며, 토큰 자체에 사용자 정보와 권한 정보를 포함할 수 있어 서버 간 인증 처리에 있어 효율적이라고 판단했습니다.

Spring Security도 함께 적용하여 인증 및 인가 흐름을 체계적으로 구성했습니다. 필터 체인을 통해 JWT를 검증하고, 어노테이션 기반의 권한 제어를 활용함으로써 보안 로직을 프레임워크 기반에서 안정적으로 구현할 수 있었습니다. 결과적으로 개발 기간 내에 높은 수준의 보안 구조를 갖춘 회원 관리 기능을 완성할 수 있었습니다.

RefreshToken은 DB에 저장하는 방식으로 설계했습니다. 이를 통해 토큰 탈취 등의 보안 사고 발생 시 관리자가 직접 토큰을 만료 처리할 수 있고, 로그아웃 시 해당 토큰을 삭제하여 명확한 세션 종료가 가능하도록 했습니다. 또한 이후에는 요청 로그를 기록·분석하는 방식으로 이상 행위를 탐지하거나 사용자 활동을 추적하는 기능으로 확장할 수 있는 여지를 고려했습니다.

프로필 이미지는 Amazon S3에 저장하고, DB에는 해당 이미지의 URL만을 저장하는 방식으로 구현했습니다. 이로써 서버 및 DB의 스토리지 부담을 줄이고, 이미지 저장에 대한 확장성과 관리 효율성을 확보했습니다.

또한 Jira를 활용하여 업무를 분배하고, 데일리 스크럼을 통해 팀 내 업무 진행 상황을 지속적으로 공유했습니다. 이 과정을 통해 기획, 일정 관리, 커뮤니케이션 측면에서도 체계적인 협업 경험을 쌓을 수 있었습니다.

**Problem**

이번 프로젝트에서는 자체 ID/PW 기반의 로그인 방식만을 제공했기 때문에, 사용자 편의성과 접근성 측면에서 아쉬움이 있었습니다. OAuth와 같은 다양한 인증 방식을 제공하지 못해 사용자 진입 장벽을 낮추는데에 한계가 있었습니다. 

또한 프로필 수정 화면의 UX가 부족하여, 사용자 입장에서 이미지 변경이나 정보 수정 과정이 직관적이지 못했습니다. UI 흐름 및 피드백 구조의 개선이 필요한 상황이었습니다.

댓글 기능은 로그인한 사용자만 작성할 수 있도록 제한하고, 본인 댓글에 대해서만 수정 및 삭제할 수 있도록 구현하였으나, 관리자 권한을 활용한 댓글 관리 기능은 포함하지 못했습니다. 커뮤니티 운영 관점에서 필수적인 기능을 구현하지 못한 점이 아쉬웠습니다.
그리고 대댓글 기능 또한 구현하지 못했습니다. 댓글 간의 상호작용 흐름을 구성하지 못한 점에서 커뮤니케이션 구조의 완성도가 부족했습니다.

**Try**

기존의 ID/PW 기반의 로그인 방식에 추가적으로 OAuth 2.0 기반의 로그인 기능을 도입할 것입니다. 구글, 네이버, 카카오 등 다양한 외부 인증 수단을 연동함으로써 사용자 접근성을 높이고, JWT 기반 인증과의 통합을 통해 보안성과 확장성도 함께 확보할 것입니다.

프로필 수정 기능은 사용자 친화적인 방식으로 개선할 것입니다. 이미지 미리보기, 변경 확인 피드백, 직관적인 레이아웃 등을 도입하여 수정 과정을 보다 명확하고 편리하게 구성할 것입니다.

댓글 기능에는 관리자 권한을 추가할 것입니다. 관리자 계정이 댓글을 블라인드 처리하거나 삭제 이력을 확인할 수 있도록 하여, 커뮤니티 품질을 유지하고 악성 게시물에 대응할 수 있도록 구현할 것입니다.

마지막으로 대댓글 기능을 구현할 것입니다. 댓글(0)에 대한 대댓글(1)까지만 허용하는 구조로 깊이를 제한하고, @태그를 통해 부모 댓글을 명확히 지정하는 방식으로 단순하고 명료한 구조를 유지할 것입니다. 또한 soft delete 방식을 적용하여 삭제된 댓글의 무결성을 유지하고, 데이터 일관성도 함께 확보할 수 있도록 설계할 것입니다.
