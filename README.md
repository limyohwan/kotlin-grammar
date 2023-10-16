# kotlin-grammar

## 인프런 강의
- Kotlin 문법 총 정리 - 1시간
- https://www.inflearn.com/course/%EC%BD%94%ED%8B%80%EB%A6%B0-%EB%AC%B8%EB%B2%95%EC%B4%9D%EC%A0%95%EB%A6%AC-1%EC%8B%9C%EA%B0%84#reviews

## kotlin in action
- 코틀린은 간결하고 실용적이며 자바 코드와의 상호운용성을 중시
- 코틀린은 현재 자바가 사용되고 있는 모든 용도에 적합하면서도 더 간결하고 생산적이며 안전한 대체 언어를 제공하는 것임

## 코틀린 특징
- 정적 타입 지정 언어
  - 코틀린 컴파일러가 자동으로 변수 타입을 유추하므로 타입 선언을 생략해도됨 -> 타입 추론
  - 장점
    - 성능 = 실행 시점에 어떤 메소드를 호출할지 알아내는 과정이 필요 없으므로 호출이 더 빠름
    - 신뢰성 = 컴파일러로 정확성을 검증하기 때문에 신뢰성 상승
    - 유지 보수성 = 객체가 어떤 타입에 속하는지 쉽게 알기 때문에 다루기 쉬움
    - 도구 지원 = 더 안전하게 리팩터링하고 툴은 더 정확한 코드 완성 기능을 제공함
- 함수형 프로그래밍
  - 일급 시민인 함수 = 함수를 일반 값처럼 다룰 수 있음
  - 불변성 = 일단 만들어지면 내부 상태가 변하지 않는 불변 객체를 사용함
  - 부수 효과 없음 = 입력이 같으면 항상 같은 출력, 다른 객체의 상태를 변경하지 않으며 외부나 바깥 환경과 상호작용하지 않는 순수 함수를 사용
  - 람다식을 이용한 간결한 코드
  - 다중 쓰레드를 사용해도 안전함 = 불변 데이터를 사용하기 때문에 복잡한 동기화를 적용하지 않아도됨
  - 테스트하기 쉬움

## 코틀린 응용
- 자바 코드와 상호운용 가능
- 코틀린 빌버 패턴을 활용하여 간결한 구문을 사용하여 객체로 이뤄진 그래프를 쉽게 구축하면서도 코틀린이 제공하는 완전한 추상화와 코드 재활용을 지속적으로 누릴 수 있음
- 실용성, 간결성(코드를 읽기 쉬움, 의도를 파악하기 쉬움), 안전성(NullPointerException을 없애기 위해 노력함, JVM 사용으로 메모리 안정성, 버퍼 오버플로 방지), 상호운용성
- kotlinc를 이용하여 .kt(코틀린파일)을 컴파일하고 java 명령으로 컴파일된 코드를 실행함 