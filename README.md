# OSS 8 project

# C를 이용한 2048 game 구현
2048 game : 매 턴마다 4x4 사이즈의 박스에 2, 4 중 랜덤한 숫자가 빈 공간 중 하나의 위치에 들어감
플레이어는 십자가를 이용하여 상하좌우 중 한 방향으로 블록들을 밀어넣음
미는 방향으로 같은 두 숫자가 있다면, 하나의 블록으로 합쳐짐

화살표로 조작함

# 추가적인 구현 - 대각선 이동
조작법 ↖ : Q / ↗ : E / ↙ : Z / ↘ : C

구현을 했지만 게임 난이도가 너무 쉬워지는 이유로 논의 후에 횟수를 5회로 제한하기로 하였음

# 랭킹 구현
점수 순으로 정렬하여 원한다면 랭킹에 이름과 점수를 등록할 수 있도록 함
