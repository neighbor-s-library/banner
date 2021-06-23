# 도서 공유 플렛폼 Hello Book

## 개요
집에 있지만 다 읽고 더 이상 읽지 않는 책을 플랫폼에 올려 각 유저들이 실제로 만나서 도서를 공유하는 서비스입니다. 즉, 당근마켓과 비슷하게 사용자들이 자신이 위치한 곳 근처에서 서로가 가진 서적을 확인하고 원하는 책을 찾아서 상호간 도서를 서로 대여할 수 있는 서비스입니다.



기존 당근마켓에서 올라오는 중고물품들이 책으로 바뀌고 중고 매매 보다는 대여에 초점을 맞췄습니다. 또한 같은 성향의 책을 공유함으로써 커뮤니티도 활성화 될 수 있을꺼 같습니다.
대상고객은 둘로 나눠서 소유하고 있는 도서를 대여 해주는 자와 소유하고 있지 않는 도서를 대여 받는 자가 있습니다.



~~비즈니스 모델은  등록자와 대여자 사이에서 발생 할 수 있는 미 반납, 혹은 연체가 발생 했을 때의 문제를 중간에서 중계를 함으로써 중계 수수료를 수익으로 만들 예정 입니다.~~
<hr/>

### 프로젝트 기획안
![기획안](https://user-images.githubusercontent.com/72908656/122868522-04778a00-d366-11eb-9e68-f63eee4363b4.png)
![기획안](https://user-images.githubusercontent.com/72908656/122868418-e27e0780-d365-11eb-8629-b8c5cac8ea91.png)
<hr/>

### 데이터베이스 스키마
![un](https://user-images.githubusercontent.com/72908656/122869665-8e742280-d367-11eb-9837-d097e149eb92.png)
<hr/>

### 서비스 구조도
![구조도](https://user-images.githubusercontent.com/72908656/122866630-3cc99900-d363-11eb-8b2d-be85bc077a82.png)
<hr/>

### 개발 환경
- Javascript
- Java 11
- Spring
- AWS(EC2, RDS)
- Apache Tomcat
- Cloudinary
- Docker
<hr/>

### 프로토타입 demo
[Hello Book](http://13.125.105.120)
<hr/>

### Frontend
[Github 링크](https://github.com/neighbor-s-library/front-end)

### Backend API 목록
[Githu 링크](https://github.com/neighbor-s-library/back-end)


- GET /products/{id}
- GET /users
- POST /users
- POST /join/ 
