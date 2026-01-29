# Playground_solver
surkitz님의 미궁 playground의 solver 모음집입니다.
모든 코드는 google colab에서 실행하시거나 로컬 환경에서 실행하실 수 있습니다. 

사용하기 쉽게 html 형태로 만드는 것은 수요가 있고 여유가 있으면 진행하겠습니다. 

## solver 별 사용법:
 ### Knight's Tour
 맨 위 code block에서 forbidden을 입력하고 밑에 코드 블럭 차례로 실행하시면 시작 ~ 끝까지 누르셔야 하는 칸 나옵니다.
 DFS algorithm 사용하였습니다.

 ### Lights Out
 맨 위 code block에서 on_grids에 켜져있는 전구 위치를 입력하고 다음 코드 블럭 실행하시면 Solution - click sequence에 눌러야 하는 칸의 위치가 출력됩니다.
 기본 전략은 위에서부터 차례차례 모든 행을 끄면서 내려오는 전략이고, 해당 전략을 사용하면 1행에 대한 선택 2^5 = 32가지에 의해서 최종 state가 결정되는 점을 이용해서 탐색하였습니다.
 횟수에는 충분히 여유가 있으니 전구 갯수를 최대한 줄여서 입력하시면 조금 편합니다.
