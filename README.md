# java-ladder
2022 마스터즈 백엔드 사다리 게임 프로젝트

<br>

## 사다리 게임 1단계 - 기본 기능 구현

### 기능 요구 사항

---

- 간단한 사다리 게임을 구현한다.
- n명의 사람과 m개의 사다리 개수를 입력할 수 있어야 한다.
- 사다리의 라인은 랜덤 값에 따라 있거나 없을 수도 있다.
- 사다리가 있으면 ``-``를 표시하고, 없으면 ``" "(공백문자)``를 표시한다. 양 옆에는 ``|``로 세로를 표시한다.
- 사다리 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.

<br>

### 프로그래밍 요구 사항

---

- **메서드 크기가 최대 10라인을 넘지 않도록 구현한다.**
- 메서드가 한 가지 일만 하도록 최대한 작게 만든다.
- 2차원 배열을 학습하고 이를 이용해서 문제를 해결한다.

<br>

### 예상 결과 및 동작 예시

---

- 요구 사항에 따라 3명의 사람을 위한 높이 5의 사다리를 만들 경우, 프로그램 실행 결과는 다음과 같다.

````
참여할 사람은 몇 명인가요?
3
최대 사다리 높이는 몇 개인가요?
5

|-| |
| |-|
|-|-|
| |-|
|-| |
````

<br>

### 접근

---

- [X] 랜덤 수를 이용하여 사다리 가로 놓기 구현


## 구현 사항 정리
