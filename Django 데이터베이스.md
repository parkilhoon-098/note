Django 데이터베이스



Wordcount

1. {우리의 클라이언트가 서버에 워드카운트 페이지를 홈 URL을 통해 요청} 
2. 렌더링 {클라이언트 요청에 대한 서버의 응답}
3. {클라이언트 이용자가 데이터를 적고 submit을 누르면 내용을 result url + data 요청을 보내게 된다.}
4. {result url을 보낸 데이터를 views.py에서 세주는 로직을 통해 workdcount data로 응답을 해준다.}



Django는 ORM을 지원

ORM(Object Relation Mapping)

-> 데이터베이스에 명령을 내리지않아도 파이썬에 객체지향적인 방법으로 데이터베이스에 데이터를 생성, 삭제, 수정등을 할 수 있다. 



class란? 정보를 저장하는 형식의 틀



table을 이용해 class로 나타내는 법

class Blog : id =숫자, 제목 = 문자, 본문 = 문자, 생성날짜 = 날짜, 글쓴이 =문자

models.py