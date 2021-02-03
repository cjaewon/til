# 28일간의 플루터

## 1일차
1. 다른 프로그래밍 언어 바이너리와는 다르게 `/Users/jaewon/flutter` 처럼 특정 폴더에 설치되지 않고 다운로드 한 위치로부터 PATH 을 설정하게 된다. 나는 `/Users/jaewon/flutter`로 설정하였다. (flutter 폴더 안에 .git 파일이 포함되어 있어야 했다. 업데이트를 위한 것 같다) 

2. Dart 관련
    - 코드들은 다 main 함수를 가지고 있다.
    - `var` 키워드를 이용해서 변수를 선언할 수 있다. 상수는 `const` 키워드를 이용한다. 기본적으로 Dart는 타입이 있는 정적언어다. 하지만 타입 추론 기능이 있어서 타입을 명시하지 않아도 된다.
      - 타입을 명시하는 경우에는 `[int, String ..] 변수명` 으로 명시 할 수 있다.
    - if, while, for 문법은 자바스크립트와 동일하다.
    - 함수의 경우 C언어와 비슷하게 사용 할 수 있다. 물론 자바스크립트에서의 화살표 함수도 가능하다.