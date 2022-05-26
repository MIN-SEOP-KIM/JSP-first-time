## :speech_balloon:JSP란?
Java Sever Pages 약자로, 동적 웹페이지를 만들때 사용된다. JSP는 html환경에서 실행된다.
![image](https://user-images.githubusercontent.com/93521131/170396782-1a2d2a56-77e6-4996-9f9a-2802e71320d2.png)

동적 웹페이지를 만들어 주는 jsp태그 이다.

## :speech_balloon:태그 사용법 ( 전역변수와 지역변수)

![image](https://user-images.githubusercontent.com/93521131/170396999-1b72a3d7-c564-4308-9146-a632452b0d75.png)

보기와 같이 <%! %> 는 전역변수를 설정하는 태그이고, <% %>는 지역 변수를 선언하는 태그이다. 
증가 연산자를 붙여, 실행했을때,   
결과는 다음과 같이 나온다.

![image](https://user-images.githubusercontent.com/93521131/170399386-6b62d664-23f1-494c-b81a-6d7b493e67fa.png)

이런식으로 나오는데 , 다시 재시작을 누르면 

![image](https://user-images.githubusercontent.com/93521131/170399437-4b938050-999a-4b62-b98c-1b4e1c4842a9.png)

전역변수의 숫자가 점점커지는 것을 볼 수있다. 따라서 다음과 같은 정의를 내릴 수 있다.
 - 전역변수는 숫자가 초기화가 되지 않는다.
 - 지역변수는 매번 실행할때 마다 초기화 되므로, 숫자가 바뀌지 않는다.

## :speech_balloon:전역변수 조건문

![image](https://user-images.githubusercontent.com/93521131/170399766-6630abd2-368a-4356-a9cc-eb518ffa9ff5.png)

if문은 스크립 트릿이라고 하는 <% %>에 선언하여 사용한다.

### :computer:실행화면 

![image](https://user-images.githubusercontent.com/93521131/170399953-4c4c42ea-8b8b-46b6-a343-a0ad5946708e.png)

## :speech_balloon:배열 

![image](https://user-images.githubusercontent.com/93521131/170400255-b33d083a-d0f8-40f5-8291-10dcff2670a7.png)

기존 자바에서 선언하는 방식인 자료형 변수명[] = {}; 으로 선언하는데 jsp도 동일하게 선언하면 된다.

![image](https://user-images.githubusercontent.com/93521131/170400574-d498aa6b-55ce-4c39-ab24-0c41395f0a43.png)

보기의 코드는 out.print(); 를 사용하지 않고, 웹페이지에 직접 출력하는 방식의 태그이다.

### :computer:실행화면

![image](https://user-images.githubusercontent.com/93521131/170400654-923a4a11-8694-4162-8a8c-5dfb1a2ed5bf.png)

## :speech_balloon:2차원 배열과 for문

기존방식의 코드로 배열을 출력하려면 , 가독성이 떨어지고,코드의 길이가 길어지므로, for문을 사용하여 더욱 간단하게 만들 수 있다.

![image](https://user-images.githubusercontent.com/93521131/170400935-e7790b0a-7010-4d60-ac4e-f689ad49a075.png)

2차원 기존 자바 문법과 같이 자료형 변수명[][] = {{}.{}}; 식으로 선언 하면 된다.

중첩 for문을 사용하여,  이차원 배열에 있는 값을 출력해 준다.

### :computer:실행화면

![image](https://user-images.githubusercontent.com/93521131/170401193-c9364b6c-69c5-4f85-936d-61227d1971e7.png)

## :speech_balloon:클래스와 메소드

![image](https://user-images.githubusercontent.com/93521131/170401469-9b7f0a95-0c5f-4471-b1e9-d34aeeadcb99.png)

 보기의 코드는 Class를 선언한 것인데, 클래스는 변수와 메소드를 정의 하는 일종의 틀로써, 간단히 설명하면 설계도의 개념과 비슷하다고 할 수 있다.
 Class 내부에 있는 함수를 메소드라 하며 , 실제 동작을 담당한다.
 
 ![image](https://user-images.githubusercontent.com/93521131/170401981-5d14f4a3-5385-4e7a-a860-cefbb8e1ba34.png)

전체적인 코드이다.

![image](https://user-images.githubusercontent.com/93521131/170402033-dc26a61b-02be-4798-925f-2d87fd58ec56.png)

 보기 코드는 클래스를 사용하기 위해 인터런스를 선언한것이다. 인터런스는 클래스를 사용하기 위한 복제품과 같은 개념이라 할 수 있다.
 
 ### :computer:실행화면
 
 ![image](https://user-images.githubusercontent.com/93521131/170402145-159a0095-06de-4f89-89d4-838e5a75e15b.png)

## :speech_balloon:예제

![image](https://user-images.githubusercontent.com/93521131/170402248-be3541b6-6b65-4dc7-b825-0250c4a2e2cb.png)

 문자열로 사용자의 아이디와 비밀번호를 만들고, 조건문인 if문을 사용하여 조건이 맞을 경우 "OK"라는 문자를 아닐 경우 "ㅠㅠ"라는 문자를 출력하는 간단한 프로그램이다.
 
 ### :computer:실행화면
 
 ![image](https://user-images.githubusercontent.com/93521131/170402420-dc983746-9340-4d25-a922-572a93eaf29e.png)


## :laughing:마치며..

java를 기반으로 한 언어 이기 때문에, 배우기에 나름 쉬웠던거 같다. 나중에 산업기사 준비할때, 깃허브에 정리한 자료가 도움이 될거 같다는 생각이 든다.




