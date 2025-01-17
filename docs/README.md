# 프리코스 2주차 : 자동차 경주 게임 🚗

---

## 기능 목록

### 입력

1. 자동차 이름 입력 받기
   - 문장 출력 : "경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)"
   - 자동차 이름을 입력 받는다.
   - ', '를 기준으로 쪼개어서 List에 담는다.
   - 앞뒤 공백을 제거한 후 반환한다.

2. 시도할 횟수 입력 받기
   - 문장 출력 : "시도할 회수는 몇회인가요?"
   - 숫자(문자열) 입력 받는다.
     - 정수가 아니면 예외를 반환한다.
   - 정수로 변환 후, TryCount(시도 횟수) 인스턴스 생성 후 반환한다.

### 출력

1. 시도 횟수만큼 실행 결과를 출력한다.
2. 최종 우승자 이름들을 출력한다.


### 자동차

- 이름을 가진다.
- 위치(전진 횟수)를 가진다.
  - 초기값은 0이다.
- 유효성 검사
  - 전체 자동차
    - 개수: 2~10대 내여야 한다.
    - 중복된 이름은 허용하지 않는다.
- 전진 조건(위치 이동 조건)
  - 0~9 범위의 랜덤값이 4이상인 경우 이다.
- 가장 큰 위치 이동한 차들을 조회할 수 있어야 한다.

### 시도 횟수

- 유효성 검사
    - 1~15회 이내의 범위여야 한다. 
- 시도 횟수는 변경이 불가하다.

### 위치

- 초기값은 0이다.
- 위치는 증가만 할 수 있다.
- 다른 위치와 비교할 수 있다.

### 이름

- 유효성 검사 :
  1. 영어 소문자만 허용
  2. 공백 비허용
  3. 길이: 1~5자 내
