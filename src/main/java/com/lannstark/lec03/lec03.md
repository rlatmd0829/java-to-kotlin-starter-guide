## 코틀린에서 Type을 다루는 방법

- 코틀린의 변수는 초기값을 보고 타입을 추론하며, 기본 타입들 간의 변환은 명시적으로 이루어진다.
- 코틀린에서는 is, !is, as, as? 를 이용해 타입을 확인하고 캐스팅한다.
  - Is : 객체가 특정 타입인지 확인 하는 연산
  - As : 객체를 명시적으로 특정 타입으로 캐스팅하는 연산
- 코틀린의 Any는 Java의 Object와 같은 최상위 타입이다.
- 코틀린의 Unit은 Java의 void와 동일하다.
- 코틀린에 있는 Nothing은 정상적으로 끝나지 않는 함수의 반환을 의미한다.
- 문자열을 가공할때 ${변수}와 ””” ””” 를 사용하면 깔끔한 코딩이 가능하다.
- 문자열에서 문자를 가져올때의 Java의 배열처럼 [ ]를 사용한다
