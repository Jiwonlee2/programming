# 객체지향 프로그래밍(OOP)

### 객체지향 프로그래밍 (OOP : Object Oriented Programming)
컴퓨터 프로그래밍 패러다임 중 하나로, 프로그래밍에서 필요한 데이터를 추상화시켜 상태와 행위를 가진 객체를 만들고 그 객체들 간의 유기적인 상호작용을 통해 로직을 구성하는 프로그래밍 방법이다.     

---

### 객체지향 프로그래밍의 장점과 단점

장점
* 코드 재사용이 용이 / 남이 만든 클래스를 가져와서 이용할 수 있고 상속을 통해 확장해서 사용할 수 있음.
* 유지보수가 쉬움 / 절차 지향 프로그래밍에서는 코드를 수정해야할 때 일일이 찾아 수정해야하는 반면, 객체 지향 프로그래밍에서는 수정해야 할 부분이 클래스 내부에 멤버 변수혹은 메서드로 있기 때문에 해당 부분만 수정하면 됨. 
* 대형 프로젝트에 적합 / 클래스단위로 모듈화시켜서 개발할 수 있으므로 대형 프로젝트처럼 여러명, 여러회사에서 개발이 필요할 시 업무 분담하기 쉽다.

단점
* 처리속도가 상대적으로 느림
* 객체가 많으면 용량이 커질 수 있음
* 설계시 많은 시간과 노력이 필요

---

### CLASS와 INSTANCE
* class : 어떤 문제를 해결하기 위한 데이터를 만들기기 위해 추상화를 거쳐 집단에 속하는 속성(attribute)과 행위(behavior)를 변수와 메서드로 정의한 것     
* instance : 클래스에서 정의한 것을 토대로 실제 메모리상에 할당된 것으로 실제 프로그램에서 사용되는 데이터
   
object는 class와 instance를 포함함.    
CLASS : 포유류 / INSTANCE : 사람, 곰, 고양이 등으로 생각할 수 있음.    
CLASS는 모듈처럼 일종의 grouping과 같은 역할을 함. 함수 뿐만 아니라 연관된 변수를 포함하기도 함.     
INSTANCE는 class를 복제하여 만들어진 것. 각각의 instance는 class와 같은 변수와 함수를 포함함.      
(함수의 내용은 같지만 변수에 담겨진 값이 다를 수 있음.)

---

### 객체 제작 - 클래스 만들기     
instance를 보통 객체라고 부름.     
객체지향 프로그램에서는 함수라는 말 대신 메소드, 행위 / 변수라는 말 대신 속성, 필드, 상태 사용      

### 객체지향 프로그래밍을 사용하는 이유
* 프로그램이 커지는 상황에서 필연적으로 발생하는 복잡성을 줄일 수 있음.
* instance의 소속을 알 수 있기에 연관성을 알 수 있음.

