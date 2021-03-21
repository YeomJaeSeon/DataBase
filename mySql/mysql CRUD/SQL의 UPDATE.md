# SQL의 세번쨰 update하기

- 데이터를 업데이트하는건 Create(INSERT), Read(SELECT)에비해선 하나도 안중요함 그래도 한번해보자.

`UPDATE table이름 SET 바꿀내용 where`로 바꾸면됨

- UPDATE에서 중요한건 `WHERE id = 1`이러한 문장을 놓치지않는게 중요하다. 이러한 synctax를 놓치면 테이블의 1억개의 모든데이터가 모두 업데이트되버려서 개발망하고 짤림.
