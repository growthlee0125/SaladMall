
![image](https://user-images.githubusercontent.com/92525310/148018553-00e7f23d-cad6-4a22-9183-b3d51fbc90f4.png)

# 샐러드 쇼핑몰 팀 프로젝트
1. 쇼핑몰 주소 - http://itwillbs9.cafe24.com/SaladMall/index
2. 디비 설계 - https://www.erdcloud.com/d/CSdHd4s6yZQC4GwdW

## 기획사항

1. 주제 : 커스터마이징 샐러드 쇼핑몰

2. 사용 언어 및 기술
- JavaSE - 1.8
- JSP
- JavaScript
- HTML
- CSS
- Jquery
- Ajax
- Spring Framework ver 4.3.8 RELEASE
- Tomcat ver 8.5
- MySQL Server ver 5.7

3. 협업도구 
- Git & GitHub & KakaoTalk
- Git : 소스코드 커밋
- GitHub Projects : 진행사항 정리
- GitHub Wiki : 회의록 정리, 공지사항, 디비 테이블, 레이아웃 및 스토리 보드 공유, 댓글 소통
- KakaoTalk : 익명 투표, 공지사항 전달, 일정 조율

## 구현 기간 및 팀원
- 2021.09.01 - 10.07
- 팀원 총 8명

## 구현 기능

1> 회원가입
- 회원가입 유효성 검사 (ajax(비동기 방식)으로 해볼것)
- 회원가입 시 이메일 인증 (SMTP)
- 회원가입 시 우편주소 api로 주소 불러오기
- 로그인
- 소셜로그인 정보 받아서 회원가입으로 연결하기
- 아이디/비밀번호 찾기 (이메일 인증)

2> 마이페이지
- 회원 정보 조회, 수정, 삭제
- 나의 등급, 쿠폰 조회하기
- 고객센터 문의하기
- 주문정보 조회, 수정, 삭제

3> 샐러드 커스텀 주문
- 커스터마이징(옵션선택) 선택 알고리즘 구현하기
- 나만의 레시피 등록하기
- 장바구니 등록하기
- 레시피 게시판
- 레시피 게시판 보여주기
- 조건에 맞는 레시피 검색하기
- 커스텀레시피 상세페이지
- 좋아요 기능(찜)
- 결제 배송주소 입력시 우편주소API(배송지입력)

4> 관리자 페이지
- 회원관리하기 : 전체 회원정보 조회, 수정, 삭제
- 주문관리하기 : 전체 주문정보 조회, 수정, 취소
- 인기 레시피 게시판 관리
- 주간 인기상품 등록하기
- 쿠폰 관리, 쿠폰 등록하기 (조건에 맞게 발급)
- 재료정보 등록, 수정, 삭제 

5> 고객센터 게시판
- 1대1 문의 카테고리 설정
- 문의글 작성, 수정, 삭제하기
