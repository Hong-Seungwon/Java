# Java

#### [2022_06_21](p2022_06_21)

  - 변수(Variable)

#### [2022_06_22](p2022_06_22)

  - 명시적 형변환(ExplicitConversion) / 묵시적 형변환(ImplicitConversion)

  - 연산자(Operator)

  - 조건문(if)

#### [2022_06_23](p2022_06_23)

  - 조건문(if, switch)

  - 반복문(for, while, do~while)

#### [2022_06_24](p2022_06_24)

  - for문 응용(팩토리얼, 구구단 가로로)

  - 제어문(break, continue)

  - 메소드(Method)

  - 배열(Array)

#### [2022_06_27](p2022_06_27)

  - 배열(Array)

  - String 클래스

  - 사용자 정의 클래스

#### [2022_06_28](p2022_06_28)

  - 배열 응용

  - 필드 사용
  
`
(클래스 필드 선언, 외부 클래스에서 필드값 읽기/변경, 필드 자동 초기화, 필드값 출력)
`

#### [2022_06_29](p2022_06_29)

  - 로또 

  - 필드 초기화
  
  `
  (생성자 필드 초기화, 객체 생성 후 필드값 출력)
  `

  - 생성자 오버로딩(Overloading)

  - 정적 필드, 정적 메소드

#### [2022_06_30](p2022_06_30)
  
   - 싱글톤(Singleton)
    
   - Final 
   
    1. Final이 멤버변수에 사용될 경우
    -> 상수 (값을 수정할 수 없다)

    2. Final이 메소드에 사용될 경우
    -> 메소드 오버라이딩을 허용하지 않는다는 의미

    3. Final이 클래스에 사용될 경우
    -> 상속을 허용하지 않는다는 의미
    
   - Final 필드
   
   `
   (최종적인 값을 갖고 있는 필드 = 값을 변경할 수 없는 필드) 
   `

   - 패키지(Package)
   
   `
   (Package와 Import, 같은 패키지/다른 패키지에 들어있는 클래스
   `
   
   [a/b](a/b) / [Calling.class](Calling.class), [hello](hello) / [UsePackageHelloWorld.class](UsePackageHelloWorld.class)
   
   
   - 날짜, 시간 관련 클래스
   
   `
   (java.util.Date, java.sql.Timestamp, java.util.Calendar)
   `
   
#### [2022_07_01](p2022_07_01)

  - 문자열 관련 클래스 
  
  `
  (String, StringBuffer, StringTokenizer)
  `
  
  - 문자열 관련 메소드
  
  `
   (length(), replace(), indexOf(), substring(), toLowerCase(), toUpperCase(), trim(), split())
  `
  
  - 값 비교(.equals())
  
#### [2022_07_04](p2022_07_04)
  
  - 주민번호 유효성 검사
  
  - Wrapper 클래스
  
  `
  (기본 자료형 <--> 참조형) 
  `
  
  - 자동 박싱 / 언박싱
  
  - 문자열 변환(valueOf())
  
  - Frame
  
  - 상속(Inheritance)
    
#### [2022_07_05](p2022_07_05)

  - 반지름이 5인 원주, 원의 넓이, 구의 겉넓이, 구의 부피 구하기(DecimalFormat 클래스 이용)
  
  - 상속(Inheritance)
    
    - 접근 제어자
    
     [packTest/packOne](packTest/packOne) / [SuperSubA.class](SuperSubA.class) / [SubOne.class](SubOne.class)
        
    - 상속(Inheritance)에서의 생성자
  
      1. 생성자는 기본적으로 상속이 되지 않는다

      2. 자식클래스를 이용해서 객체를 생성할때 자식클래스의 생성자(기본생성자,매개변수 있는 생성자 모두 가능)가 호출되면, 부모클래스의 기본생성자가 자동으로 호출된다.

      3. 매개변수가 있는 생성자가 있는 경우에는 더이상 컴파일러가 기본 생성자를 자동으로 생성해 주지 않는다.

      4. 부모 클래스의 매개변수가 있는 생성자를 자식 클래스에서 호출 할때는 super()를 이용해서 호출할 수 있다.
         단, super()는 자식 클래스의 생성자 안에서만 사용 가능함.
  
  - 메소드 오버라이딩(Method Overriding)
  
  - super. : 부모 클래스에 있는 은닉된 멤버변수와  메소드를 호출할 때 사용 
  
  - super() : 부모 클래스의 매개변수를 가진 생성자를 호출할 때 사용
  
#### [2022_07_06](p2022_07_06)

  - 평년, 윤년 구분하기
  
  - 추상(Abstract) 클래스
  
  - 인터페이스(Interface)
  
  - 레퍼런스(Reference) 형변환
  
  `
  (업 캐스팅(자동 형변환), 다운 캐스팅(강제 형변환))
  `
  
#### [2022_07_07](p2022_07_07)

  - 평년, 윤년 구분하기(GregorianCalendar 클래스 이용)
  
  - 레퍼런스(Reference) 형변환
  
  - Set 인터페이스
  
  `
  (상속받는 클래스 : HashSet, TreeSet)
  `
  
  - List 인터페이스
  
  `
  (상속받는 클래스 : ArrayList)
  `
  
  - List 응용 게시판 만들기
  
  - Vector 클래스
  
#### [2022_07_08](p2022_07_08)
  
  - Vector 클래스
  
  - Map 인터페이스
  
  `
  (상속받는 클래스 : HashMap, HashTable)
  ` 
  
  - 큐(Queue) : FIFO(First Input First Output)구조
  
  - 스택(Stack) : LIFO(Last Input First Output)구조
  
 
