# mysql client(gui)인 어플리케이션 - mysql workbench이용하기

- 설치해서 사용해봄.
- 이번시간은 workbench를 사용하는 방법이 중요한건 절대 하나도아니다.

- 저번시간에 mysql같은 database도 client와 server가있다고배웠따.

- workbench도 하나의 mysql client로 하나의 mysql server에 요청하여 접근할수있다는 것이다.

# 하나의 database server와 매우 많은 database client

- 세상엔 데이터베이스 서버가 하나는 절대아니다. 그래서 제목을 저렇게쓴건아님

- 하지만 하나의 서비스를 만들때 하나의 database server를 이용하는 database client는 굉장히 많다. 예를들면 웹브라우저가될수도 있고, 앱이될수도있고...

- 중요한건 하나의 database server를 중심으로 여러개의 database client가 존재해서 이용할수있다는것이다.
