## 테스트 구문 첫단어는 선택해주세요

실행
```
node server.js

//크롬 주소창에 입력

http://localhost:3000/

```

```
//create
TABLE table_name (column1 Numeric, column2 Numeric, column3 Numeric)

//insert
INTO table_name (column1, column2, column3) VALUES (1, 2, 3)

//delete
FROM table_name WHERE id = 3

//update
table_name SET column1 = 2 WHERE id = 1

//select
* FROM table_name
column1 FROM table_name WHERE id > 2

//drop
TABLE table_name
```

데이터베이스가 만들어지고 수정되고 삭제되는것이 눈에보이게 만들고 싶어서 html을 활용해 구현해봤습니다.
