# 지금까지 한 데이터베이스 (MYSQL)구조를 복습해보자.

- mysql서버에 들어간다는건 `database server`에 들어가는것이다.
- `database server`에는 여러개의 `database (= schema)`가 있다.
- `databse (=schema)`에는 연관된 테이블들이 존재한다.(테이블은 표이다.)

즉 table들이 모여서 database(schema), database들이 모여서 database server(mysql)을 이루고있다.

# database만들고 use database로 데이터베이스 사용설정하고 table을 create했다. 이젠 테이블에 데이터를 INSERT해보자.

- row(record = 행)은 데이터 하나를 의미한다했고 이 데이터 하나를 테이블에 입력하자.
- `INSERT INTO topic (title, description, created, author, profile) VALUES('MongoDB', 'MongoDB is ...', NOW(), 'charlie zeplin', 'soccer player');`
- 이런식으로 입력하면됨.
- 잘입력되었는지 화인하려면 `SELECT * FROM topic`을통해서 해당 테이블의 데이터를 확인할수있음.

# 지금까지 뭐 데이터베이스 만들고, 데이터베이스 drop으로 삭제하고. 테이블 생성(create)하고 .. 이런거 했찌만 이런거 거의안씀. 가장중요한건 테이블에 데이터를 주입하는 INSERT와 테이블의 데이터를 조회하는 SELECT가 가장중요하다.
