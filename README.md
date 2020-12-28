# ConventionCollector_Spring

### 프로젝트 개요

##### 코딩시 사용하는 변수명 & 컨밴션을 통일하고 더 좋은 방법을 공유하기 위해 만듬
1. 기본적으로 자바와 파이썬에 대한 코딩 컨벤션 공유
2. 여러 상황에 따라 사용하는 컨벤션 작성 및 공유
3. 검색 알고리즘을 사용해서 원하는 변수를 찾음 ex) 전송 + 이미지 검색 => sendImg, postImg ....
4. 많이 채택될 수록 맨위에 나오게 작성
5. 클래스, 메소드, 변수 ... 각 상황에 따라 값을 찾음

### 프로잭트 구성
1. 데이터베이스 -> Mysql 사용

### SETTING

1. eclipse Spring MVC Project 생성 (STS 플러그인 설치 후)
2. project -> properties -> facets -> java(1.8), runtimes( tomcat 8.5) 설정
3. src/main/resources 폴더의 log4j.xml 제외하고 삭제
4. src/main/webapp/WEB-INF 밑의 spring, views 폴더 삭제
5. web.xml -> <web-app> 루트엘리먼트 제외 삭제
6. pom.xml -> spring version => 5.1.5 setting



