CRUD - Create, Update, Delete



Create



{ new : new.html 보여줌, create : 데이터베이스에 저장}



Get vs POST

Get : 데이터를 얻기 위한 요청, 데이터가 url에 보임

POST : 데이터를 생성하기 위한 요청, 데이터 url 안보임, Csrf 공격 방지



Update



{edit : edit.html 보여줌, update : 데이터베이스에 적용}

, 수정할 데이터의 id값을 받아야함 -> path converter를 이용해야한다.



Delete



따로 html을 만들 필요가 없다. Delete라는 함수에서 보내준 ID값을 삭제해주면 끝이난다.



---> 다시한번 강의 보면서 실습 진행해보기