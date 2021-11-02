# 함수와 메소드

### 1. 함수(function) 

​	함수는 특정 작업을 수행하는 "코드 조각"이다.
​	범위가 전역이든 지역이든 "독립된 기능"을 수행하는 단위이다.
​	로직 처리 이후 사용자가 원하는 결과를 반환(return)한다.
​	**즉 함수는 독립적으로 존재한다.**

```java
//독립적으로 존재한다.
function plus(int a, int b) {
	retrun a+b;
}
```



### 2. 메소드(method)

​	메소드란 클래스, 구조체, 열거형에 포함되어 있는 **함수**이다. 다른말로 `클래스 함수`라고도 한다. 

```java
class Person { 
  //This is a method which acts only on Person type 
 	func personGreeting() { 
      greet(yourName: "Phil", category: .Person)
    }
```



### 정리

함수는 메소드를 포함하는 상위 개념이며, 함수 중 클래스 등에 종속된 것을 메소드라고 한다. 

