# 2016_Summer_CSharp

* 개요 
  * CS(CSharp)에 대해 공부하는 스터디입니다.

* 진행 예정 내용 
 * 다소 중요하다고 생각된 내용은 **보라색 볼드(굵게)** 처리하였습니다.
  * ~~중요한 게 중요하지 않은 것보다 많게 보이는 건 착각입니다.~~
  * ~~사실 딱히 강조처리 하는게 의미가 없을수도..~~

 * #1. 닷넷 프레임워크 살펴보기 
  * **(5월 11일에 완료)**
  * **닷넷 응용 프로그램의 기본 구조**
  * **CLR과 IL/MSIL(CIL)**
  * 닷넷 호환 언어
  * CTS와 CLS
  * 메타데이터, 닷넷 응용 프로그램 속의 메타데이터
  * **어셈블리, 모듈**
  * CLI와 CTS, CLI와 닷넷 프레임워크
  * 닷넷 프레임워크 구성 요소
  * 기존 윈도우 프로그램과 닷넷 응용 프로그램의 대응 관계
  * 모노(Mono) 프레임워크
  * C#과 닷넷 프레임워크
  * Naming Convention

 * #2. C#의 타입과 문장(Statement), 배열 
  * **(5월 11일에 완료)**
  * **자료형과 기본 자료형**
  * **C#에서의 정수 타입, 실수 타입, 문자 타입. 상수**
  * C#에서의 변수 초기화
  * C#에서의 Escape Sequence
  * 형변환
  * 예약어와 식별자
  * **값 형식과 참조 형식**
  * **배열, 다차원 배열, 가변 배열**
  * **논리 연산자, 관계 연산자, 조건 연산자**
  * **C#의 조건문과 반복문, 점프문**

 * #3. 클래스와 객체지향 Part.#1 
  * **(5월 25일에 완료)**
  * **클래스와 인스턴스**
  * **new 연산자**
  * **데이터 멤버와 메서드 정의**
  * **생성자와 소멸자, 기본 생성자**
  * GC와 소멸자
  * **정적 데이터 멤버와 정적 메서드**
  * **정적 생성자(Static Constructor)**
  * 네임스페이스와 클래스, using을 통한 네임스페이스 선언
  * C#에서의 FQDN
  * **C#에서의 접근 제한자**
  * **접근자 메서드와 설정자 메서드, 그리고 속성(Property)**
  * 문맥 예약어
  * 가변 객체와 불변 객체
  * **클래스 내 데이터 멤버로써의 상수**
  * **readonly 데이터 변수**
  * **메서드 오버로딩**
  * **연산자 오버로딩**
  * 중첩 클래스

 * #4. 클래스와 객체지향 Part.#2 
  * **(5월 25일 ~ 6월 1일에 걸쳐 완료)**
  * **C#에서의 클래스 상속**
  * 봉인된 클래스(Sealed class)
  * **클래스 상속 관계에서의 형변환**
  * **as 연산자와 is 연산자**
  * **enum 클래스 타입**
  * enum과 Flag 특성
  * **this 예약어와 base 예약어**
  * **인덱서 구문**
  * **virtual 예약어와 가상 함수**
  * **메서드 오버라이딩과 new 예약어를 통한 메서드 정의**
  * **클래스 간의 형변환**
  * **추상 메서드와 추상 클래스**

 * #5. 클래스와 객체지향 Part.#3 
  * **(6월 1일에 완료)**
  * **델리게이트(delegate)의 정의**
  * **델리게이트의 특성, C#과 1급 함수**
  * System.MulticastDelegate
  * **델리게이트 인스턴스와 산술 연산자**
  * **콜백 메서드**
  * **인터페이스, 추상 클래스와 인터페이스**
  * **인터페이스의 구현**
  * **구조체(Struct), 구조체와 클래스**
  * **깊은 복사와 얕은 복사, PBV(CBV)와 PBR(CBR)**
  * **ref와 out 예약어를 통한 PBR**

 * #5.5. 자투리 객체지향
  * **(6월 21일에 완료)**
  * ~~분량과 순서 조절로 인해 남은 것~~
  * 강력한 결합과 느슨한 결합
  * System.Object와 System.ValueType
  * 배열과 System.Array
  * **열거자와 IEnumerator, IEnumerable**
  * **이벤트**


 * #6. 마무리하는 C# 1.0 Part.1 
  * **(6월 21일에 완료)**
  * **C#의 전처리기 지시문**
  * **변수의 유효범위**
  * **특성(Attribute) 클래스**
  * **특성(Attribute)과 속성(Property)**
  * **특성(Attribute)와 리플렉션(Reflection)**
  * **System.AttributeUsage**
  * **System.AttributeTargets, 특성에서의 대상 명시**
  * **어셈블리 정보 수정**
  * 시프트 연산자
  * 연산자 간의 우선순위
  * **오버플로(Overflow), 언더플로(Underflow)**
  * checked 예약어와 unchecked 예약어
  * **가변 인자, params 예약어**
  * 플랫폼 호출(Platform Invocation)
  * extern 예약어와 비관리 코드
  * unsafe 예약어와 포인터, 포인터 연산
  * fixed 예약어와 참조 형식 인스턴스에 대한 포인터 연산
  * stackalloc 예약어

 * #7. 마무리하는 C# 1.0 Part.2 
  * **(6월 28일에 완료)**
  * **예외(Exception)**
  * System.Exception
  * **try/catch를 통한 예외 처리기**
  * **finally 블록**
  * **throw 예약어**
  * Swallowing Exception 피하기
  * 스택과 Stack Overflow
  * 관리 힙과 GC
  * **박싱(Boxing)과 언박싱(Unboxing)**
  * 가비지 수집
  * 루트 참조(Root reference)
  * 대용량 객체 힙(LOH, Large Object Heap)
  * **IDisposable 인터페이스와 using 블록**
  * 소멸자와 비관리 메모리
  * 다시 보는 GC와 소멸자, 종료 큐

 * #8. Visual Studio와 C# 
  * **(6월 28일에 완료)**
  * 프로젝트 파일 설정(csproj)
  * 솔루션 파일 설정(sln)
  * csc에서의 다중 소스 컴파일, 라이브러리 생성과 참조
  * Visual Studio에서의 라이브러리 생성
  * **CLR과 app.config**
  * **supportedRuntime 태그**
  * **config 파일과 닷넷 응용 프로그램 실행 과정**
  * **appSettings 태그**
  * **System.ObsoleteAttribute**
  * **디버그 빌드와 릴리즈 빌드**
  * 각 빌드에서의 전처리 상수 정의, Conditional 특성
  * System.Diagnotics.Debug, System.Diagnotics.Trace
  * 플랫폼 설정을 통한 응용 프로그램 빌드
  * **어셈블리 이름과 DLL 지옥**
  * **PKI와 강력한 이름의 어셈블리(서명된 어셈블리)**
  * **전용 어셈블리와 XCopy 배포**
  * **GAC와 전역 어셈블리**

 * #9. BCL Part.1
  * **닷넷 BCL 속의 컬렉션**
  * BCL을 통한 시간 처리
  * BCL 속 유용한 문자열 메서드
  * Encoding
  * Regex
  * **직렬화(Serailization)와 역직렬화(Deserialization)**
  * **Stream과 MemoryStream**
  * **StreamReader/StreamWriter와 BinaryReader/BinaryWriter**
  * BinaryFormatter를 이용한 직렬화
  * XmlSerializer를 이용한 직렬화
  * DataContractJsonSerializer를 이용한 직렬화
  * BigInteger와 IntPtr, Tuple

 * #10. C# 2.0으로 올라서기
  * **제네릭, 제네릭 메서드와 제네릭 클래스**
  * **제네릭과 박싱/언박싱**
  * **제네릭 형식 매개변수와 where 예약어**
  * BCL의 컬렉션 속 제네릭
  * **?? 연산자**
  * **제네릭과 default 예약어**
  * **열거와 yield return/yield break**
  * **값 형식과 Nullable<T> 구조체**
  * **익명 메서드와 델리게이트**
  * **정적 클래스**
  * 부분 클래스

 * #11. C# 3.0으로 올라서기
  * **타입 추론(Type Inference), var 예약어**
  * **자동 구현 속성(Auto-Implemented Property)**
  * 객체 초기화, 컬렉션 초기화
  * 익명 타입
  * 부분 메서드
  * **확장 메서드(Extension Method)**
  * **람다 식(Lambda Expression)**
  * 람다 지원 델리게이트, Action, Func, Predicate
  * **Enumerable 정적 클래스와 람다 식, 컬렉션**
  * 식 트리로 사용되는 람다 식
  * **LINQ(Language-integrated Query)**
  * **LINQ와 from-in, where, group-by**
  * **지연 연산(Lazy Evaluation)**

 * 아래는 보류 중인 작성 목록입니다.
 * #12. BCL Part.2
 * #13. C# 4.0으로 올라서기
 * #14. BCL Part.3
 * #15. C# 5.0으로 올라서기
 * #16. C# 6.0으로 올라서기
 * #17. BCL Part.4

 

| 참가자
|--------
|[신형철](https://github.com/nerumin), 
[이승현](https://github.com/leesnhyun), 
[홍성현](https://github.com/tjdgus3537), 
[강민승](https://github.com/minseungkang), 
박인서, 김상렬, 유성현, 성훈
