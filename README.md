# 미션 - 숫자 야구 게임

## ⚾ 구현할 클래스의 역할과 기능 목록

### 플레이어 (Player)
게임 진행에 필요한 값을 제공
- 게임 진행 시 세 자리 숫자를 입력
- 게임 종료 시 추가 진행 여부를 입력

### 상대방 (Computer)
게임 시작, 종료 제어를 담당
- 어플리케이션 실행 시 게임 시작
- 점수에 따른 힌트 출력
- 플레이어가 정답을 맞추면 게임 종료 여부 확인
- 사용자의 선택에 따라 게임을 다시 시작, 또는 종료
- 입력이 유효하지 않을 때 예외 발생시켜 종료 

### 야구게임 (BaseballGame)
정답 설정과 점수 채점
- 게임 시작 시 세 자리 정답 숫자 설정
- 볼/스트라이크/낫싱 여부 판단

### 입력 유효성 검사 (InputValidator)
플레이어의 입력값 검사
- 게임 진행 중 잘못된 값이 주어졌는지 검사 
- 게임 종료 후 잘못된 값이 주어졌는지 검사


<br>

## 📝 License

This project is [MIT](https://github.com/woowacourse/java-baseball-precourse/blob/master/LICENSE) licensed.
