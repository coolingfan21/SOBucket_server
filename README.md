# SOBucket-server

### **1. About**

---

버킷리스트 공유 및 연결, 크롤링 정보 제공

### 2**. Team Rule**

---

1. Merge 타이밍 - 팀 코드리뷰 후
2. Commit 메세지
 - 좋은 commit 메세지(https://blog.ull.im/engineering/2019/03/10/logs-on-git.html) 사용
 - 깃이모지(https://gitmoji.carloscuesta.me/) 사용
3. ES Lint + Prettier 통일 : 내용을 추후 정할 것 (airbnb)
4. 페어 프로그래밍 - 코드 리뷰 한시간 전에 (default) / slack요청(emergency)
5. Merge후에는 local에 있는 해당 branch는 삭제
6. Standup meeting 시간 : 토이 제출 후 10분 휴식 후(매일10:10~10:30)

### 3**. Stack**

---

Project 에서는 최소 2일 최대 4일의 기간 동안 Software Requirements(SR) 를 진행하게 됩니다. 
SR 동안에 Project 에 사용할 Stack을 확정하여야 합니다. 확정된 Stack을 아래에 정리해 주시기 바랍니다.

[Project Stack](https://www.notion.so/a2841e3948b74f529eeed0a394da073b)

### 4**. Members Role**

---

아래의 테이블에는 각 팀원의 Role를 업데이트 해주시기 바랍니다. 

[Members](https://www.notion.so/3fe89baa2d6a44dcb31bedcecf11bc2a)

### 5**. Project Step**

---

프로젝트는 Bare Minimum / Advanced / Nightmare 로 구성됩니다.

### 🐻BareMinimum

---

Home page

피드 렌더링(database)

좋아요 버튼

퍼가요~ 버튼 (bucket list 추가)

Login/Logout 버튼

회원가입 버튼

피드 상세 페이지

내용

좋아요 버튼

퍼가요~ 버튼

리뷰 컴포넌트 추가

Login page

Login 기능 (JWT Token)

Signup page

회원가입 기능

Mypage

렌더링 페이지(자기피드)

Bucket list 구현

Create

리스트 제목

내용

이미지 추가

Update

완료 state 변경

Read

Delete

Private page

개인정보 수정

탈퇴

### 🐯Advanced

---

피드 상세 페이지

댓글 추가 기능

피드 검색

제목 기반 결과 반환

알람

리스트에 완료 예상 일정 추가

피드 상세 페이지

Crawling 

연결된 기능 : 렌더링 데이터 / 키워드(signup) 선택

버킷리스트 상세페이지 댓글 구현

댓글추가시 실시간 알람(slack API사용?)

### 🦇Nightmare

---

친구/즐겨찾기 구현

연결된 기능 : 버킷 리스트 작성 시 공개 범위 설정

Admin page(Chunk big)

권한설정

대쉬보드

체크인

사용자 특화 vs 권한설정 ? —> 사용자 특화로.

### 6. API 문서

---

[Server API 문서](https://www.notion.so/745af9867f6740078e613d7d54f85420)

### 7. Datebase Schema

---

  

![2%20HaliBoliSky%20SO%20Bucket/database_schima().png](2%20HaliBoliSky%20SO%20Bucket/database_schima().png)

bucketlist - user 관계 그림으로 (작성한 목업을 중심으로)

(NM)((x) - 렌더링만)크롤링정보()

(NM)친구정보

### 8. Standup Meeting Log

---

아래의 테이블을 이용해서 매일 진행되는 Standup Meeting 을 기록합니다. 

기록을 하는 이유는 합의된 내용을 팔로우업 하기 위함 입니다. 
기록자는 반드시 팀장이어야할 필요는 없습니다. 진행은 팀장님이 해주시되, 기록자는 지목해 주시기 바랍니다. 

[Standup Meeting Log](https://www.notion.so/7e75c102527a457a8099024cece35389)

### 9**. Task**

---

스탠드업 미팅에서는 아래의 테이블을 사용하여 진행합니다.

**참고문서 -** [프로젝트 Stand up Meeting 안내문서](https://www.notion.so/codestates/Stand-up-Meeting-0fcccff1667a4a6f92bf879f3e928873)

[Sprint 1(화~금)](https://www.notion.so/1120a59466e1408ebaa652c687807974)

[Sprint 2(월~화)](https://www.notion.so/3511a930c82d4055ba3ad21977e4736e)

[Sprint 3(수~목)](https://www.notion.so/831dd0dbb79d4e87ad1dc66902112f1a)

### 10**. Sprint 회고**

---

아래의 테이블에서 팀장님 주도하에 프로젝트 Sprint 회고가 이루어 집니다.

**참고문서** - [프로젝트 Sprint 회고 안내문서](https://www.notion.so/codestates/Sprint-3671fc16580346b29155541c2d18d616)

****1. Sprint 별로 작성해 주시기 바랍니다. 
2. Sprint는 '4' 이상으로 생성 가능합니다.

[Sprint 회고 테이블](https://www.notion.so/5f7b2243be3b42759d98282e324b0fdf)

### 10**. Reference**

---

### **11. Results**

---

프로젝트를 완성하고 결과물을 소개하는 페이지 입니다. 
프로젝트 소개에 필요한 슬라이드, 자료 등을 등록해 주시기 바랍니다. 

[프로젝트 Repository](https://www.notion.so/347d1483f1d34b2a9f0a208f21342aac)

[프로젝트 발료자료](https://www.notion.so/52b6492da4d648449c8d47ee9f4180d5)
