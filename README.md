# ⚾ 미션: 숫자 야구 게임

## 구현 기능 목록 

### 입력
- [x] "숫자를 입력해주세요 : " 출력
- [x] 콘솔 사용자 입력
  - [ ] 입력값을 모델에 저장(List)
- [x] 게임 추가 진행 여부 입력
- [ ] [예외] 사용자 입력값 검증 (IllegalArgumentException)

### 출력
- [x] 결과값 출력 (볼, 스트라이크, 낫싱)
  - [x] 결과 메시지 생성 
- [x] 정답을 맞췄을 시 "3개의 숫자를 모두 맞히셨습니다! 게임 종료" 출력
- [x] 게임을 계속 진행할 것인지에 대한 여부 출력

### 컴퓨터 난수 생성 
- [x] 중복없는 3자리 난수 생성
  - [x] 생성한 난수를 모델에 저장(Set)

### 정답 판별 알고리즘
- [x] 숫자만 맞춘 경우 `n볼`
- [x] 숫자와 자리를 모두 맞춘 경우 `n스트라이크`
- [x] 숫자와 자리 하나도 맞추지 못한 경우 `낫싱`
- [x] 숫자와 자리 모두 맞춘 경우 ➡ 게임 세트 종료

### 게임 진행
- [x] 게임이 끝난 후, 추가 게임 진행 여부 확인  
- [x] 게임 상태 정보 초기화 

## 실행 로직

1. 프로그램 실행
2. 3자리 난수 생성 (중복 x)
3. 사용자 입력
   1. 입력값 유효성 검증
4. 심판이 볼, 스트라이크 확인
5. 볼, 스트라이크 출력
6. 게임 종료 조건 확인
7. 프로그램 종료 여부 선택
8. (종료를 선택했다면) 프로그램 종료

## 클래스 다이어그램(추가 예정)

## 피드백 