<div align="center">

# 👋 안녕하세요, 개발자 최제현입니다.

저는 주어진 기능을 구현하는 데 그치지 않고,  
**문제가 발생하는 조건과 데이터 흐름을 파악하여 해결하는 개발자**를 목표로 하고 있습니다.

프로젝트를 진행할 때 기능의 동작 여부뿐 아니라  
사용자 권한, 데이터 상태, 예외 상황과 운영자의 처리 흐름까지 함께 고려하려고 노력합니다.

웨딩 플랫폼 **MerryView** 프로젝트에서는 결제·환불, 사용자 알림 및 관리자 기능을 담당했습니다.  
외부 결제 정보와 서버 데이터를 비교하고, 일부 사용된 패스의 환불을 제한하는 등  
서비스 운영 과정에서 발생할 수 있는 문제를 고민하며 기능을 구현했습니다.

오류가 발생하면 결과만 수정하기보다 원인을 확인하고,  
해결 과정과 주의 사항을 기록하며 꾸준히 성장하고 있습니다.
<br>

</div>

---

# 🙋 About Me

- ⚙️ Java·Spring Boot 기반 서버 기능 구현
- 🔗 MyBatis를 활용한 SQL 작성 및 데이터베이스 연동
- 🧩 결제·환불, 알림 및 관리자 운영 기능 구현
- 📝 오류 발생 조건과 해결 과정을 기록하는 습관
- 📚 정보처리기사 취득
- 🎓 AI 활용 풀스택 부트캠프 수료 예정

---

# 🛠 Tech Stack

## Backend

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

## Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

## Database

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)

## Deployment & Tools

![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MySQL Workbench](https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

# 📂 Projects

## 🎀 MerryView(팀 프로젝트)
> 실제 구매 영수증을 기반으로 웨딩 업체 리뷰와 결혼 정보를 공유하는 커뮤니티 플랫폼
<img src="./images/marryViewMain.JPG" width="1000" height="300">
 
### 담당 기능

- PortOne API를 활용한 패스 결제 및 결제 정보 검증
- 구매 수량과 잔여 수량을 기준으로 한 환불 조건 처리
- 댓글·좋아요·문의 답변 등에 따른 사용자 알림 기능
- 회원·신고·문의·상품·쿠폰·패스 관리자 기능
- 관리자 페이지의 일부 통계 데이터 조회 및 차트 구현

### 문제 해결 경험

- 일부 사용된 패스가 전체 환불되는 문제를 방지하기 위해 구매 수량과 잔여 수량을 비교했습니다.
- 결제 시 클라이언트 요청값 대신 PortOne 결제 내역과 서버 상품 정보를 비교·검증 하도록 구현했습니다

### GitHub

- [SpringProjectTeam3](https://github.com/limhyojin3/SpringProjectTeam3)

---

## 💻 Code.Snippet(개인 프로젝트)
> 개발 학습 내용과 오류 해결 경험을 코드와 함께 기록하고 공유하는 서비스
<img src="./images/Code.snippet_banner.png" width="1000">
 
### 담당 기능

- 회원·게시글·댓글·태그·좋아요·북마크·팔로우 DB 설계
- JWT 기반 회원 인증 및 로그인 상태 관리
- 게시글 CRUD와 코드 블록 등록
- 사용자 프로필과 활동 내역 관리

### 문제 해결 경험

- 고정 경로보다 동적 경로가 먼저 선언되어 발생한 API 라우팅 충돌을 해결했습니다.
- 기존 태그를 중복 저장하여 발생한 UNIQUE 제약조건 오류를 해결했습니다.

### GitHub

- [project_Code.Snippet](https://github.com/cjh-devv/project_Code.Snippet)

---

# 📜 Education & Certificate

### Education

- AI 활용 풀스택 부트캠프 수료 예정
- Java, Spring Boot, React, Flutter, Database 및 AWS 활용 교육

### Certificate

- 정보처리기사
- 전산회계 1급
- 전산세무 2급

---

# 📈 GitHub Stats

![GitHub stats](https://github-readme-stats.shion.dev/api?username=cjh-devv&show_icons=true&theme=dracula)

![Top Langs](https://github-readme-stats.shion.dev/api/top-langs/?username=cjh-devv&layout=compact&theme=dracula)

---

# 📫 Contact

- GitHub: [cjh-devv](https://github.com/cjh-devv)
- Email: cjh900318@gmail.com

---

<div align="center">

### 기능의 흐름과 문제의 원인을 이해하는 개발자로 성장하겠습니다.

</div>
