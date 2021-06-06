Model 실습

![image-20210603014715740](C:\Users\ih506\AppData\Roaming\Typora\typora-user-images\image-20210603014715740.png)



필드 옵션

blank : validation 시에 empty 허용하는지

null : null 값 허용하는지

db_index : 인덱스 필드인지

default : 디폴드 값이나 함수를 지정해줌

unique : 현재 테이블 내 유일한 값인지 



makemigration : 앱 내의 migration 폴더를 만들어서 models.py의 변경사항 저장

migrate : Migration 폴더를 실행시켜 데이터베이스에 적용



Django는 admin 패널을 적용