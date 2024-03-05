# 프로젝트 소개

> 사용자가 게시판에 자유롭게 글을 작성하고, 다른 사용자의 게시글에 댓글을 달 수 있는 게시판입니다.\
> 로그인 하지 않아도 작성된 글을 읽을 수 있지만, 게시글과 댓글을 쓰기 위해서는 로그인을 해야 합니다.\
> 사용자는 자신이 작성한 글만 관리(삭제, 수정)할 수 있으며, 타인이 작성한 글은 관리할 수 없습니다.
> 
> Html 5.0, SpringBoot, Spring JPA를 사용해 기본적인 웹페이지를 구현하고,\
> Get, Post 를 통해 데이터를 DB에 저장하고 불러와 출력하도록 했습니다.


> ### 개발 기간 및 인원
> 23.12.15 ~ 24.01.29 (2주) \
> 풀스택 1명

<br/>

# 기술 스택
![html](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![java](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

# 주요 기능

### 회원가입 및 로그인 기능
- 사용자는 ID, 비밀번호, email을 정보를 통해 가입할 수 있으며, 중복된 email 주소는 사용할 수 없다.
- ID 및 PW가 일치하지 않으면 오류화면 대신 오류 메세지를 띄운다.
- 로그인 되면 로그인 버튼이 로그아웃으로 바뀌며, 로그아웃 버튼을 통해 로그아웃을 할 수 있다.


### 게시판 글 관리
- 게시글을 작성하면 DB에 사용자 정보, 게시글 제목과 내용, 작성일자가 저장된다.
- 작성된 게시글에는 사용자 정보(글쓴이)가 표시된다.
- 로그인한 사용자와 글쓴이가 동일한 경우 [수정] 및 [삭제] 버튼이 노출된다.
- 로그인 하지 않으면 게시글 작성 및 댓글 작성이 불가하다.

<br/>

# 추가 구현하고 싶은 기능

### 관리자 기능 차별화
- Admin 계정은 모든 User가 작성한 내용을 관리(수정, 삭제) 할 수 있어야 한다. 

- ### 게시글 내용 공유하기
- 작성된 게시글의 내용을 소셜미디어로 공유할 수 있어야 한다.
- 게시글을 공유하면 게시글의 제목, 요약된 내용, 작성자를 확인할 수 있으며 링크를 통해 해당 게시물을 확인할 수 있어야 한다. 

- ### 조회 수 표시
- 게시글이 얼마나 조회 되었는지 조회수를 확인 할 수 있어야 한다.

