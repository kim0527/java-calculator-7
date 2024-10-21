# 🚀 우아한테크코스 프리코스 1주차: 문자열 덧셈 계산기

## 1️⃣ 기능 요구 사항
- 입력한 문자열에서 숫자를 추출하여 더하는 계산기를 구현합니다.
- 쉼표(`,`) 또는 콜론(`:`)을 구분자로 가지는 문자열을 전달하는 경우, 구분자를 기준으로 분리한 각 숫자의 합을 반환합니다.

  - 예시: 
    - `""` => 0 
    - `"1,2"` => 3 
    - `"1,2,3"` => 6 
    - `"1,2:3"` => 6

- 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있습니다. 커스텀 구분자는 문자열 앞부분의 `"//"`와 `"\n"` 사이에 위치하는 문자를 사용합니다.

  - 예시: 
    - `"//;\n1;2;3"` => 커스텀 구분자가 `;`이므로 결과 값은 6이 반환됩니다.


- 사용자가 잘못된 값을 입력할 경우 `IllegalArgumentException`을 발생시키며, 애플리케이션은 종료되어야 합니다.



## 2️⃣ 기능 구현 목록

### 1. 쉼표(`,`) 또는 콜론(`:`) 구분자
- [ ] 쉼표(`,`)에 따라 문자열 분리
- [ ] 콜론(`:`)에 따라 문자열 분리

### 2. 쉼표(`,`) 또는 콜론(`:`) 구분자 예외 상황 처리
- [ ] 입력이 올바르지 않을 경우 예외 처리

### 3. 커스텀 구분자
- [ ] 커스텀 구분자로 문자열 분리

### 4. 커스텀 구분자 예외 상황 처리
- [ ] 커스텀 구분자 입력이 잘못된 경우 예외 처리

### 5. 덧셈 연산자
- [ ] 분리된 숫자의 합 계산



## 3️⃣ 프로그래밍 요구 사항

- [x] JDK 21 버전에서 실행 가능해야 합니다.
- [ ] 프로그램 실행의 시작점은 `Application`의 `main()`입니다.
- [ ] `build.gradle` 파일은 변경할 수 없으며, 제공된 라이브러리 이외의 외부 라이브러리는 사용하지 않습니다.
- [ ] 프로그램 종료 시 `System.exit()`를 호출하지 않습니다.
- [ ] 프로그래밍 요구 사항에서 달리 명시하지 않는 한, 파일, 패키지 등의 이름을 변경하거나 이동하지 않습니다.
- [x] 자바 코드 컨벤션을 준수하며, 기본적으로 Java Style Guide를 원칙으로 합니다.
- [ ] `camp.nextstep.edu.missionutils`에서 제공하는 `Console` API를 사용하여 구현해야 합니다.
    - 사용자가 입력하는 값은 `camp.nextstep.edu.missionutils.Console`의 `readLine()`을 활용합니다.
