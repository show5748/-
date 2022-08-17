
#   📃 Spring 입문 주차 개인 과제


📌 "스프링 부트로 로그인 기능이 없는 나만의 항해 블로그 백엔드 서버 만들기"

📌 학습내용
1. RDMBS, SQL, JPA  
2. 기본 CRUD API 구현 
3. Controller, Repository, Server 
4. AWS EC2, RDS

📌 Requirement:
<aside>
✅ 서비스 완성

</aside>

### **요구사항**

1. 아래의 요구사항을 기반으로 Use Case 그려보기
    - 손으로 그려도 됩니다.
    - cf. [https://narup.tistory.com/70](https://narup.tistory.com/70)
2. 전체 게시글 목록 조회 API
    - 제목, 작성자명, 작성 날짜를 조회하기
    - 작성 날짜 기준으로 내림차순 정렬하기
3. 게시글 작성 API
    - 제목, 작성자명, 비밀번호, 작성 내용을 입력하기
4. 게시글 조회 API
    - 제목, 작성자명, 작성 날짜, 작성 내용을 조회하기 
    (검색 기능이 아닙니다. 간단한 게시글 조회만 구현해주세요.)
5. ~~게시글 비밀번호 확인 API~~
    - ~~비밀번호를 입력 받아 해당 게시글의 비밀번호와 일치여부 판단하기~~
6. 게시글 수정 API
    - 제목, 작성자명, 비밀번호, 작성 내용을 수정되게 하기
7. 게시글 삭제 API
    - 글이 삭제되게 하기

<aside>
✅ AWS 배포

</aside>

1. RDS 연결
    - MySQL을 이용하기
2. EC2 배포
    - Ubuntu EC2 를 구매한 뒤, 8080 포트와 80번 포트를 연결하여 포트 번호 없이도 서비스에 접속 가능하게 하기

📌 API 명세서

![image](https://user-images.githubusercontent.com/35902293/184717656-9114821e-84d1-4a1a-973a-54a3627ae8ea.png)



📌 use case


![image](https://user-images.githubusercontent.com/35902293/185252432-96d6c158-6b76-4613-9886-40db10916776.png)
