# 미션 - 자동차 경주 게임
우아한테크코스 프리코스 2주차 미션입니다.

## ⭐ 구현할 기능 목록 
- Car
    - 전진하기 기능
        - 0에서 9사이의 랜덤 값 중, 4이상이면 전진한다.
    - 이름을 리턴해주는 기능
    - 현재 position을 리턴해주는 기능
- Cars
    - 인자(String)를 기준으로 Car 객체들 생성
    - 매 회차 결과를 출력 하는 기능 
    - 경주 자동차리스트를 출력해주는 기능            
- RacingCarGame
    - 게임 시작 기능
    - 레이싱 자동차 초기화 기능
        - 경주할 자동차를 입력 받는다.
        - 경주할 자동차들의 유효성을 확인한다.
    - 시도할 회수 입력 받는 기능
    - 시도할 회수 출력 하는 기능
    - 시도할 회수 만큼 게임 게임 실행하는 기능
- CarValidator
    - 이름은 (,)로 구분하며, 입력 값에 대한 에러는 아래와 같다.
        - 입력 값이 없는 경우 : SpaceInputException
        - 구분 기호가 엾는 경우 : WithoutDelimiterException
        - 이름 입력이 유효하지 않는 에러 : InvalidNameException
        - 이름을 5글자 이상 입력 할 경우 : MaximumNameLengthException    
    
<br>

## 🔧 프로그래밍 요구 사항
- 자바 코드 컨벤션을 지키면서 프로그래밍한다.
  - 기본적으로 [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)을 원칙으로 한다.
  - 단, 들여쓰기는 '2 spaces'가 아닌 '4 spaces'로 한다.
  - 구현 순서, 공백도 포함한다.
- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용한다.
  - 예를 들어 while문 안에 if문이 있으면 들여쓰기는 2이다.
  - 힌트: indent(인덴트, 들여쓰기) depth를 줄이는 좋은 방법은 함수(또는 메소드)를 분리하면 된다.
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메소드)가 한 가지 일만 하도록 최대한 작게 만들어라.
- 프로그래밍 요구사항에서 별도로 변경 불가 안내가 없는 경우 파일 수정과 패키지 이동을 자유롭게 할 수 있다.
- 예외 상황 시 에러 문구를 출력해야 한다. 단, 에러 문구는 `[ERROR]` 로 시작해야 한다.
- 함수(또는 메소드)의 길이가 15라인을 넘어가지 않도록 구현한다.
  - 함수(또는 메소드)가 한 가지 일만 잘 하도록 구현한다.
- else 예약어를 쓰지 않는다.
  - 힌트: if 조건절에서 값을 return하는 방식으로 구현하면 else를 사용하지 않아도 된다.
  - else를 쓰지 말라고 하니 switch/case로 구현하는 경우가 있는데 switch/case도 허용하지 않는다.
- 이름을 통해 의도를 드러내라 ( 의도를 드러낼 수 있다면 축약하지 마라)
- 불필요한 공백 라인을 만들지 않는다.
- 반복을 피해라 ( 중복은 소프트웨어에서 모든 악의 근원이다.)
- 의미 없는 주석은 피해라
- 값을 하드코딩하지 마라.
- 의미 있는 commit 메세지를 사용해라