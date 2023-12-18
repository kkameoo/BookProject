## PORTFOLIO
***
### 목차
***
- [포트폴리오 개요](https://github.com/kkameoo/Bookproject#포트폴리오-개요)
- [기술 및 도구](https://github.com/kkameoo/Bookproject#기술-및-도구)
- [백엔드 사용 기술](https://github.com/kkameoo/Bookproject#백엔드-사용-기술)          
- [기능 구현](https://github.com/kkameoo/Bookproject#기능-구현)
- [참고 자료](https://github.com/kkameoo/Bookproject#참고-자료)
- [시현 영상](https://github.com/kkameoo/Bookproject#시현-영상)    
### 포트폴리오 개요
***
![대문](https://github.com/kkameoo/bikeproject/assets/116774845/734fb4b7-f1c4-4fa4-9e8d-ee5d9a27c50b)
분류: 팀 프로젝트  
제작 기간: 2023.09.01 ~ 2023.12.15  
주요 기능: 로그인, 구글 로그인, 회원가입, 게시판, 위치 지정, 채팅, 게시물 정렬, qr코드, 마이페이지      

### 기술 및 도구
***
프론트엔드 - Html, CSS, javascript            
백엔드 - SpringBoot    
데이터베이스 - Mysql    
서버 구동 - SpringBoot         
형상 관리 - Github       
개발 도구 - Vscode, Intellij    

### 백엔드 사용 기술
***
- thymleaf 
- springTest
- webSocket
- lombok
- jpa
- springSecurity
- JsonWebToken
- Oauth2

### 기능 구현
***
## 회원가입
![회원가입](https://github.com/kkameoo/bikeproject/assets/116774845/0ab06dc5-f78b-40c9-985a-7d3e4bbc73ee)
## 구글 로그인 기능
![구글로그인](https://github.com/kkameoo/bikeproject/assets/116774845/70dfe1c8-ecd8-48ad-ba33-761e0003f9a4)
## 로그인 기능
![로그인](https://github.com/kkameoo/bikeproject/assets/116774845/577a825a-23e0-4e5a-ae8a-dc1877b43ed3)
## 게시물 작성 기능
![게시물 작성](https://github.com/kkameoo/bikeproject/assets/116774845/8aea87a6-76ab-42e3-9284-4c64692a0121)
## 마이페이지 + qr코드
![마이페이지+qr코드](https://github.com/kkameoo/bikeproject/assets/116774845/02fbc6e4-2cc9-4afe-9a4a-70bad2e0b2c8)
## 조회수별로 정렬 기능
![조회수별로 정렬](https://github.com/kkameoo/bikeproject/assets/116774845/473a644c-65f7-4437-a7dc-908f90f83bef)
## 채팅 기능
![채팅](https://github.com/kkameoo/bikeproject/assets/116774845/3aca5e66-ea67-45f9-bd1e-72efddcaa4b7)
## 거래할 장소 지정 기능
![지도](https://github.com/kkameoo/bikeproject/assets/116774845/922267d3-d710-4e6f-9dba-40a890fcc4b1)
 
### 참고 자료
***
구글 api   
https://cloud.google.com/?hl=ko  
카카오 api      
https://apis.map.kakao.com/  

### 시현 영상
***
링크 : 



### 12.04 오류 내역
- IllegalStateException: Cannot call sendRedirect() after the response has been committed
- getRedirectStrategy().sendRedirect() 함수 호출 시 발생하는 오류
- 원인 - 페이지가 2번 호출되서 발생하는 오류
- 해결방법 - 페이지가 1번만 호출되게 컨트롤러 부분을 고침
