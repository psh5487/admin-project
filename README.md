# admin-project
Admin 프로그램의 RestAPI 개발하기

## Stack
- Spring Boot
- MySQL
- JPA
- Lombok


## ERD
<img width="500" alt="관계도" src="https://user-images.githubusercontent.com/26567880/92546478-97d74700-f28d-11ea-90e8-ffd360177988.png">
<img width="500" alt="ERD" src="https://user-images.githubusercontent.com/26567880/92546239-0ec01000-f28d-11ea-9c1a-6f22b56741c6.png">

## API
### Host
http://localhost:8080

|Method|URI|Description|
|------|---|-----------|
|GET   |/api/user/{id}|(User) 회원 정보 조회|
|POST  |/api/user     |(User) 회원 정보 생성|
|PUT   |/api/user     |(User) 회원 정보 업데이트|
|DELETE|/api/user/{id}|(User) 회원 정보 삭제|
|GET   |/api/item/{id}|(Item) 상품 정보 조회|
|POST  |/api/item     |(Item) 상품 정보 생성|
|PUT   |/api/item     |(Item) 상품 정보 업데이트|
|DELETE|/api/item/{id}|(Item) 상품 정보 삭제|
|GET   |/api/orderGroup/{id}|(OrderGroup) 주문 조회|
|POST  |/api/orderGroup     |(OrderGroup) 주문 생성|
|PUT   |/api/orderGroup     |(orderGroup) 주문 정보 업데이트|
|DELETE|/api/orderGroup/{id}|(orderGroup) 주문 정보 삭제|

## Refactoring
- Enum 형태의 값 관리
- @EnableJpaAuditing 로 중복요소 제거
- Optional 로 Null 처리
- Controller, Service 추상화하기

