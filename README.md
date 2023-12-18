## PORTFOLIO
***
### 목차
***
![대문](https://github.com/kkameoo/bikeproject/assets/116774845/734fb4b7-f1c4-4fa4-9e8d-ee5d9a27c50b)
- [포트폴리오 개요](https://github.com/kkameoo/bikeproject#포트폴리오-개요)
- [기술 및 도구](https://github.com/kkameoo/bikeproject#기술-및-도구)
- [백엔드 사용 기술](https://github.com/kkameoo/bikeproject#백엔드-사용-기술)          
- [기능 구현](https://github.com/kkameoo/bikeproject#기능-구현)
- [참고 자료](https://github.com/kkameoo/bikeproject#참고-자료)
- [시현 영상](https://github.com/kkameoo/bikeproject#시현-영상)    
### 포트폴리오 개요
***

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

## 구글 로그인 기능

## 로그인 기능

## 게시물 작성 기능
          
## 마이페이지 + qr코드

## 조회수별로 정렬 기능

## 채팅 기능
     
## 카카오 api를 이용한 거래할 장소 지정 기능

 
### 참고 자료
***
구글 api    
   
카카오 맵 api    
https://apis.map.kakao.com/    

### 시현 영상
***
링크 : 


# LibraryProject
### 12.04 오류
- IllegalStateException: Cannot call sendRedirect() after the response has been committed
- getRedirectStrategy().sendRedirect() 함수 호출 시 발생하는 오류
- 원인 - 페이지가 2번 호출되서 발생하는 오류
- 해결방법 - 페이지가 1번만 호출되게 컨트롤러 부분을 고침
