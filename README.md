# javascript-racingcar-precourse

# javascript-calculator-precourse

# 자동차 경주

# 기능 목록 작성

- 경주할 자동차 이름 입력 받기
- 시도할 횟수 입력 받기
- 랜덤값을 반환하는 기능
- 자동차가 랜덤값을 받아 랜덤값이 4이상일 경우 전진하는 기능
- 우승자를 뽑는 기능(여러명일 수 있다)
- 결과를 출력하는 기능

# 개발 중 체크리스트

## 프로그래밍 체크리스트

### 필수

- Node.js 20.17.0 버전에서 실행 가능해야 한다.
- 프로그램 실행의 시작점은 App.js의 run()이다.
- package.json 파일은 변경할 수 없으며, 제공된 라이브러리와 스타일 라이브러리 이외의 외부 라이브러리는 사용하지 않는다.
- 프로그램 종료 시 process.exit()를 호출하지 않는다.
- 프로그래밍 요구 사항에서 달리 명시하지 않는 한 파일, 패키지 등의 이름을 바꾸거나 이동하지 않는다.
- 자바스크립트 코드 컨벤션을 지키면서 프로그래밍한다.
- 기본적으로 JavaScript Style Guide를 원칙으로 한다.
- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메서드)의 길이가 10라인을 넘어가지 않도록 구현한다.

---

### 이후 요구사항

- Jest를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인한다.

- else를 지양한다.

- 함수(또는 메서드)가 한 가지 일만 잘 하도록 구현한다.

- 입출력을 담당하는 클래스를 별도로 구현한다.

---

### 개인적인 목표

캡슐화를 깨지 말고 객체지향적으로 프로그래밍하자. getter와 setter 사용을 지양한다.

## 테스트 케이스

- 시도할 횟수에 음수가 입력됐을 경우 [ERROR]
- 시도할 횟수가 소수일 경우 [ERROR]
- 이름에 공백이 포함되어 있을 경우 trim()으로 공백 제거
- 이름이 5자를 초과할 경우 [ERROR]
