## 코틀린에서 변수를 다루는 방법

* 모든 변수는 var / val을 붙여 주어야 한다.
    *  var : 변경 가능하다 / val : 변경 불가능하다 (read-only)
* 타입을 명시적으로 작성하지 않아도, 타입이 추론된다.
* Primitive Type과 Reference Type을 구분하지 않아도 된다.
    * 내부적으로 연산할때는 primitiveType을 쓰는등 처리를 해준다
* Null이 들어갈 수 있는 변수는 타입 뒤에 ? 를 붙여주어야 한다.
    * 아예 다른 타입으로 간주된다.
* 객체를 인스턴스화 할 때 new를 붙이지 않아야 한다.
