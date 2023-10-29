# 미션 - 자동차 경주

- 간단 소개 : n대의 자동차가 주어진 횟수동안 전진 또는 멈추는 경주를 통해 우승자를 가린다.

<br>

## 🎯 개발 요구 사항
- 개발 환경 : JDK17
- IDE : Eclipse
- 형상관리 툴 : GitHub

<br>

## 🚗 기능 요구 사항

### 기본기능

- 사용자는 각 자동차에 5자 이하의 이름을 부여할 수 있다.
- 자동차 이름은 슆표(,)를 기준으로 구분한다.
- 사용자는 몇 번을 이동할 것인지 입력할 수 있다.
- 한바퀴 진행될 때마다 자동차 이름과 전진한 횟수를 출력한다.
- 자동차가 전진하는 조건은 0에서 9사이에서 무작위 값을 정한 후, 결괏값이 4 이상일 경우이다.
- 경주 게임을 완료 한 후 누가 우승했는지 알려준다.
- 우승자는 여러 명일 수 있으며, 쉼표(,)를 이용하여 구분한다.
- 잘못된 값을 입력할 경우 프로그램을 종료한다.


### 입력

- 서로 다른 자동차 이름(쉼표로 구분)

```
pobi,woni,jun
```

- 자동차의 이동 횟수

```
5
```

### 출력

- 1. 각 차수별 실행 결과

```
pobi : --
woni : ----
jun : ---
```


- 2-1. 단독 우승자 안내 문구

```
최종 우승자 : pobi
```

- 2-2. 공동 우승자 안내 문구

```
최종 우승자 : pobi, jun
```
