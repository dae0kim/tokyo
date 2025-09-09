# \# 20250909

# tokyo



\# 과제

=============

1\. 프로그래밍 언어와 자바

&nbsp;	- 프로그래밍 언어 : 사람의 언어와 기계어의 다리 역할

&nbsp;	- 고급언어

&nbsp;		- 컴퓨터와 대화할 수 있는 언어 중 사람이 이해하기 쉬운 언어

&nbsp;		- 고급언어로 작성된 파일을 소스파일이라고 함	 

&nbsp;			  - Ex) Java, C, C++, Python 등

&nbsp;	- JAVA의 특징

&nbsp;		- 모든 운영체제에서 실행 가능

&nbsp;		- 객체지향 프로그래밍(OOP : Object Oriented Programming)

&nbsp;			   - 메모리 자동 정리

&nbsp;		- 풍부한 무료 라이브러리

2\. JDK

* &nbsp;자바 프로그램 실행을 위해 JDK(Java Development Kit) 설치 필요
* JDK에는 Oracle JDK와 Open JDK 두 종류가 있음
* 안정적인 사용을 위해 LTS 버전 설치 권장



3\. 환경변수

* JDK 설치 후 프로그램들이 이를 사용할 수 있도록 JAVA\_HOME 환경변수를 설정 및 Path 환경변수 수정 필요



4\. 바이트코드 파일과 자바 가상머신

* 자바로 작성한 소스파일(.java)을 컴파일하여 확장자명이 .class인 바이트코드 파일을 생성
* 이후 자바 가상 머신(JVM : Java Virtual Machine)을 구동하여 바이트코드 파일을 완전한 기계어로 번역 및 실행
* 이때 JVM은 운영체제별로 이해하는 기계어로 번역해야하기 때문에, 각 운영체제별 설치하는 JDK가 다름



5\. 소스 작성 및 실행

* new -> project -> java project 생성
* 좌측 Project Explore에서 생성된 프로젝트의 src 폴더 확인
* src 폴더 하위에 package 생성
* 생성된 package 하위에 소스코드를 작성할 class 파일 생성 (class명은 반드시 대문자로 작성)
* 생성된 class 파일의 main 함수에 테스트 코드 System.out.print("Hello world"); 작성 후 상단의 run 아이콘 클릭
* 하단의 console에 원하는 출력값이 나오는지 확인

&nbsp;	



