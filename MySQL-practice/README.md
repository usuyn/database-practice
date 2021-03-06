# Start study MySQL 2021.10.08

### Practice of MySQL_1 - 2021.10.08
- 어떠한 이유로 데이터베이스 기술이 생겨났는지, 앞으로 배울 MySQL이 어떤 DBMS인지에 대해 배웠습니다.

***

### Practice of MySQL_2 - 2021.10.08
- 스프레드시트와 DB로 데이터를 제어할 때의 차이점과 MySQL을 사용해서 DB에 저장되어 있는 데이터를 웹페이지에 공유할 수 있다는 것을 배웠습니다.

***

### Practice of MySQL_3 - 2021.10.09
- 실습환경을 구축했습니다. MySQL을 설치하고 cmd를 사용해 MySQL을 실행했습니다.

***

### Practice of MySQL_4 - 2021.10.10
- 표(table), 데이터베이스(db, schema), 데이터베이스 서버로 이루어진 구조에 대해 배웠습니다.

***

### Practice of MySQL_5 - 2021.10.10
- DB가 보안 측면에서 가지는 장점과 권한 부여 기능에 대해 배웠습니다.  
- 명령 프롬프트를 이용해 MySQL 서버에 접속하는 방법을 배웠습니다.

***

### Practice of MySQL_6 - 2021.10.11
- 명령을 사용해 DB를 생성, 삭제, 출력, 실행하는 방법을 배웠습니다.

***

### Practice of MySQL_7 - 2021.10.12
- SQL이 어떤 언어인지에 대해 배웠습니다.  
- DB를 구성하며 row와 column으로 나누어지는 표의 기본 구조에 대해 배웠습니다.

***

### Practice of MySQL_8 - 2021.10.13
- table 생성 방법을 배웠습니다.  
- column을 설정할 때 필요한 MySQL의 여러 데이터 타입과 제약 조건을 설정하는 방법을 배웠습니다.

![image](https://user-images.githubusercontent.com/68963707/137009061-f67f8fa5-e310-43c9-a612-63bedcc8e23a.png)

<img src="https://user-images.githubusercontent.com/68963707/137009616-123560ad-5c2c-4c99-9487-490b92760efb.png" width="500" height="auto">

***

### Practice of MySQL_9 - 2021.10.13
- DB에서 가장 중요한 기능인 Create, Read에 대해 간략한 설명을 들었습니다.

***

### Practice of MySQL_10 - 2021.10.14
- INSERT 명령을 통한 데이터 삽입 방법을 배웠습니다.  
- 데이터가 삽입된 table을 보여주는 SELECT * FROM 명령을 배웠습니다.

<img src="https://user-images.githubusercontent.com/68963707/137512713-2aa6b650-702a-4257-9147-481027f43223.png" width="700" height="auto">

***

### Practice of MySQL_11 - 2021.10.15
- table에 삽입된 데이터를 조회하는 SELECT 문법에 대해 배웠습니다.  
- 특정 column만 조회하는 경우, 특정 데이터 가진 row만 조회하는 경우, 정렬, 보이는 row의 개수 제한 등 여러가지 조건에 따른 SELECT문을 배웠습니다.

<img src="https://user-images.githubusercontent.com/68963707/137513215-953e9339-3bfd-418a-b3e4-cdb50a20743e.png" width="400" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/137513354-390a2226-ff84-4088-8473-3680c6d1714e.png" width="600" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/137513451-1181b8bb-2cd4-4ff1-ae3d-3151c899e407.png" width="700" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/137513541-5bdefdaa-2833-41d8-8ecd-41db85ef7def.png" width="700" height="auto">

***

### Practice of MySQL_12 - 2021.10.16
- table에 삽입된 데이터를 수정하는 UPDATE에 대해 배웠습니다.

<img src="https://user-images.githubusercontent.com/68963707/137591685-11025f26-1657-4f58-8a3c-91f5699ccfd8.png" width="700" height="auto">

***

### Practice of MySQL_13 - 2021.10.16
- table에 삽입된 데이터를 삭제하는 DELETE에 대해 배웠습니다.

<img src="https://user-images.githubusercontent.com/68963707/137591936-93a9b721-1c25-46ce-a1d2-fd0f8a3d5ac2.png" width="700" height="auto">

***

### Practice of MySQL_14 - 2021.10.17
- 지금까지 배운 내용을 정리했습니다.  
- 앞으로 배울 관계형 DB의 의미와 필요성에 대해 간략히 정리했습니다.

***

### Practice of MySQL_15 - 2021.10.18
- topic tabled의 author, profile 데이터에서 발생하는 중복의 문제점에 대해 다뤘습니다.  
- 중복의 문제점을 해결하기 위해 topic, author table을 각각 분리, 생성하고 얻는 장점과 단점을 비교했습니다.  
- 데이터를 별도의 table로 보관, 중복을 발생시키지 않으면서 하나의 table로 합쳐진 결과를 보고 싶을 때 사용하는 JOIN의 개념에 대해 배웠습니다.

***

### Practice of MySQL_16 - 2021.10.20
- 기존 topic table을 topic_backup table로 변경했습니다.  
- author, topic table을 새로 생성해 topic_backup table의 데이터를 분리했습니다.

<img src="https://user-images.githubusercontent.com/68963707/138127991-305b0e56-6018-4eec-aad3-8a2e5f5856a6.png" width="500" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/138128036-fd69d2c1-d3ca-433d-85ee-24d97e3b83f2.png" width="300" height="auto">

***

### Practice of MySQL_17 - 2021.10.21
- topic, author table을 하나의 table로 합치기 위해 JOIN을 사용했습니다.  
- topic의 author_id의 값과 같은 값을 가지고 있는 author table의 행을 가져와서 topic table과 함께 합쳐 출력했습니다.  
- 별칭을 지정하는 AS를 사용했습니다.

<img src="https://user-images.githubusercontent.com/68963707/138308806-1439626e-ae3b-434b-8c19-b2e4fdb1edee.png" width="800" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/138314862-412f10d6-d1b4-4b85-bf34-f3182db228b5.png" width="600" height="auto">

<img src="https://user-images.githubusercontent.com/68963707/138314987-233af3fd-e66d-4a29-81e8-66efc4591e0c.png" width="700" height="auto">

***

### Practice of MySQL_18 - 2021.10.23
- 인터넷과 DB의 관계에 대해 배웠습니다.  
- DB 클라이언트와 DB 서버를 구분하고 어떤 차이가 있는지 역할은 무엇인지 배웠습니다.

***

### Practice of MySQL_19 - 2021.10.24
- MySQL client에는 어떤 것들이 있는지 알아봤습니다.  
- CLI 기반 MySQL Monitor와 GUI 기반 MySQL Workbench의 차이점과 각 장점, 단점에 대해 배웠습니다.

***

### Practice of MySQL_20 - 2021.10.25
- MySQL Workbench를 설치하고 사용하는 방법을 배웠습니다.
- MySQL Monitor에서 명령어를 사용해 수행했던 작업을 MySQL Workbench에서 수행했습니다.

![image](https://user-images.githubusercontent.com/68963707/139281880-7c2d7659-dd3b-4622-8720-c24a3bd49440.png)

![image](https://user-images.githubusercontent.com/68963707/139282495-d0e0ccdb-55a3-410d-a43d-91a6893b6fb4.png)

![image](https://user-images.githubusercontent.com/68963707/139282629-1c6e1afe-4468-494f-a748-bc599ea018ec.png)

***

-완료-
