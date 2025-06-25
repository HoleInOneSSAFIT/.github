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

### PostController
| HTTP Method | API | Description | Request Body/Params | Response Body | Authorization |
|-------------|-----|-------------|----------------------|----------------|----------------|
| POST | /api/post/insert | 게시글 등록 | Form: PostDetailInfo<br>Header: Authorization: Bearer &lt;accessToken&gt; | { "postId": Long } | O (ROLE_USER) |
| GET | /api/post/{postId} | 게시글 상세 조회 | Path: postId | Post | X |
| GET | /api/post/{postId}/files | 게시글 첨부파일 조회 | Path: postId | List&lt;PostFile&gt; | X |
| GET | /api/post/routine/{routineId}/info | 루틴 정보(제목, 내용 등) 조회 | Path: routineId | Routine | X |
| GET | /api/post/routine/{routineId} | 루틴 영상 리스트 조회 | Path: routineId | List&lt;VideoRoutineSessionData&gt; | X |
| GET | /api/post/user/{postId} | 게시글 작성자 정보 조회 | Path: postId | User | X |
| DELETE | /api/post/{postId} | 게시글 삭제 | Path: postId | "게시글 삭제 성공" | O (ROLE_USER) |
| GET | /api/post/all | 전체 게시글 목록 조회 | 없음 | List&lt;Post&gt; | X |
| GET | /api/post/latest | 게시글 최신순 조회 | 없음 | List&lt;Post&gt; | X |
| GET | /api/post/popular | 게시글 인기순 조회<br>(조회수 1점, 좋아요 3점, 댓글수 5점 기준) | 없음 | List&lt;Post&gt; | X |
| GET | /api/post/part | 특정 운동 부위 게시글 검색 | Query: part | List&lt;Post&gt; | X |
| PUT | /api/post/update/{postId} | 게시글 수정 | Path: postId<br>Form: PostDetailInfo<br>Optional: files(List&lt;MultipartFile&gt;), filesToDelete(List&lt;Long&gt;)<br>Header: Authorization: Bearer &lt;accessToken&gt; | "게시글 수정 완료" | O (ROLE_USER) |
| GET | /api/post/me | 현재 접속한 유저 ID 반환 | Header: Authorization: Bearer &lt;accessToken&gt; | Long (userId) | O (ROLE_USER) |
| POST | /api/post/{postId}/like | 게시글 좋아요/취소 토글 | Path: postId<br>Header: Authorization: Bearer &lt;accessToken&gt; | LikeResponse | O (ROLE_USER) |
| GET | /api/post/{postId}/like | 게시글 좋아요 수 및 상태 조회 | Path: postId<br>Header: Authorization: Bearer &lt;accessToken&gt; | LikeResponse | O (ROLE_USER) |
| POST | /api/post/{postId}/increase-view | 게시글 조회수 증가 | Path: postId | int (증가된 조회수) | X |
| GET | /api/post/{postId}/commentCount | 게시글의 댓글 수 조회 | Path: postId | int (댓글 수) | X |

### VideoController
| HTTP Method | API | Description | Request Body/Params | Response Body | Authorization |
|-------------|-----|-------------|----------------------|----------------|----------------|
| GET | /api/video/search | 조건에 맞는 유튜브 영상 검색 및 추천 | Query: part, duration (optional), recommend (optional)<br>Header: Authorization: Bearer &lt;accessToken&gt;<br>Session: videoRoutineData | YoutubeVideo (랜덤 1개) | O (ROLE_USER) |
| GET | /api/video/reSearch | 특정 유튜브 영상 제외하고 다시 추천 | Query: youtubeVideoId<br>Session: videoRoutineData | YoutubeVideo (랜덤 1개) | X |
| GET | /api/video/youtubeSelect | 루틴에 유튜브 영상 추가 | Query: youtubeVideoId, sequence, restSecondsAfter<br>Session: videoRoutineData → videoRoutineResult로 이동 | YoutubeVideo | X |
| GET | /api/video/routineSelect/{sequence} | 루틴에서 특정 순서의 영상 조회 | Path: sequence<br>Session: videoRoutineResult | YoutubeVideo or UploadedVideo | X |
| GET | /api/video/routineDelete/{sequence} | 루틴에서 특정 순서의 영상 삭제 | Path: sequence<br>Session: videoRoutineResult | VideoRoutineSessionData | X |
| GET | /api/video/tempRoutineReset | 세션에 저장된 임시 루틴 초기화 | 없음<br>Session: videoRoutineResult 제거 | "임시 루틴과 내부 리스트가 초기화되었습니다." | X |
| POST | /api/video/insertVideoRoutine | 세션의 영상 리스트를 이용해 루틴 생성 및 저장 | Form: routineTitle, routineContent<br>Header: Authorization: Bearer &lt;accessToken&gt;<br>Session: videoRoutineResult | { routineId, message, routineVideos } | O (ROLE_USER) |
| DELETE | /api/video/routineIdDelete/{routineId} | 루틴 삭제 | Path: routineId | "삭제 성공: {result}" | O (ROLE_USER) |
| POST | /api/video/myUpload | 유저가 직접 촬영한 영상 업로드 | Multipart: file<br>Params: title, part, durationSeconds, sequence, restSecondsAfter<br>Header: Authorization: Bearer &lt;accessToken&gt;<br>Session: videoRoutineResult | UploadedVideo | O (ROLE_USER) |
| POST | /api/video/directYoutubeUrl | 유튜브 URL 직접 입력하여 영상 추가 | Params: url, part, sequence, restSecondsAfter<br>Header: Authorization: Bearer &lt;accessToken&gt;<br>Session: videoRoutineResult | YoutubeVideo | O (ROLE_USER) |

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
Keep

이번 프로젝트에서 운동 루틴 추천 및 커뮤니티 게시글 기능을 담당했습니다.

운동을 자주 하지 않던 제 입장에서는 사용자 중심의 시각으로 기능을 기획하는 데 많은 고민을 하게 되었습니다. 특히, 운동을 막 시작하려는 사람들에게 필요한 기능이 무엇일지를 고려해 ‘영상 추천’, ‘루틴 구성’, ‘루틴 공유’라는 세 가지 핵심 기능을 중심으로 설계했습니다.

운동 영상 추천 기능은 유튜브 API를 활용하여 사용자의 선택에 따라 부위, 시간, 추천 방식(인기 기반, 랜덤 기반)으로 영상을 필터링할 수 있도록 구현했습니다. 이후 추천받은 영상을 기반으로 루틴을 구성하고, 이를 커뮤니티에 공유할 수 있도록 했습니다. 루틴에 등록되는 영상들은 임시로 담고, 삭제·초기화·확정 등 다양한 흐름을 지원하도록 세션 기반으로 설계한 점이 실제 사용자 시나리오에 잘 맞았다고 생각합니다.

또한 게시글 작성 시 루틴 미리보기를 지원하고, 루틴 상세 페이지에서 자동 재생 및 쉬는 시간 타이머를 구현하여 사용자 경험을 강화했습니다. 기능 구현 외에도 AWS S3를 활용한 파일 저장, 영상/루틴/게시글 간의 연계 흐름 구현 등 다양한 기술을 실제로 적용해보며 좋은 실습 경험을 할 수 있었습니다.

Problem

추천 알고리즘이 기본적인 랜덤/인기 기반으로만 제공되어, 사용자 맞춤형 추천이라는 부분에서는 다소 아쉬움이 있었습니다. 사용자의 운동 성향이나 과거 루틴 등을 고려한 개인화 로직이 없었기 때문에, 추천의 정밀도가 높다고 보긴 어려웠습니다.

루틴 구성 UI에서 영상 추가/삭제 등의 흐름이 직관적이지 않은 부분도 있었습니다. 특히 업로드 영상과 유튜브 영상을 함께 다루는 구조에서 사용자 혼란이 발생할 수 있었고, 이 부분을 명확히 구분하거나 UX적으로 보완할 필요가 있다고 느꼈습니다.

또한 게시글 공유 이후, 루틴의 수정이나 삭제가 곧 게시글과 연결된 데이터 전체에 영향을 주기 때문에, 이 관계 설정 및 관리가 초심자에겐 다소 복잡하게 느껴질 수 있었습니다. 향후 게시글과 루틴 간 연계 구조를 유연하게 관리할 수 있는 기능이 필요하다고 생각했습니다.

Try

향후에는 사용자 맞춤형 추천 알고리즘을 도입하고자 합니다. 예를 들어 사용자의 운동 빈도, 선호 운동 부위, 영상 시청 기록 등을 기반으로 추천 영상을 필터링하거나 가중치를 반영하여 보다 개인화된 루틴을 제안할 수 있도록 개선할 예정입니다.

루틴 구성 UI는 드래그앤드롭 방식이나 루틴 타임라인 시각화와 같은 방식을 통해 사용자가 루틴을 더 직관적으로 구성할 수 있도록 개선할 계획입니다. 특히 업로드 영상과 유튜브 영상의 구분을 더 명확히 하여 UX 혼란을 줄일 수 있도록 구조를 정비할 것입니다.

또한 게시글-루틴 간의 연계 구조를 개선하여, 루틴 수정이 게시글에 바로 반영되지 않도록 버전 관리 또는 복사 공유 구조를 도입할 계획입니다. 이를 통해 데이터 무결성을 유지하면서도 사용자의 편의성을 확보할 수 있도록 설계할 것입니다.

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
