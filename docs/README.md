구현 기능 목록

1. 프로그래밍 요구사항의 라이브러리를 사용하여 상대방(컴퓨터)의 수를 생성한다.
   조건 : 1 ~ 9 까지 서로 다른 수로 이루어진 3 자리 수를 생성

2. 유저의 입력 값을 (1)에서 생성 한 3 자리 수와 비교하고 결과에 맞는 출력 생성
   예) 상대방(컴퓨터)의 수가 425일 때
      	- 123을 제시한 경우 : 1스트라이크
      	- 456을 제시한 경우 : 1볼 1스트라이크
      	- 789를 제시한 경우 : 낫싱
        - 425를 제시한 경우 : 3개의 숫자를 모두 맞히셨습니다! 게임 종료
                             게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요.

3. (2)에서 게임 종료 후 사용자의 입력 값에 따라 애플리케이션을 다시 시작하거나 종료

4. (2)에서 사용자가 잘못된 값을 입력한 경우 IllegalArgumentException을 발생시켜 애플리케이션을 종료
