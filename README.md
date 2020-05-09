

num키와 / 키는 매크로 토글키(1~3), *는 매크로 비활성

숫자부분은 토글될때마다 기능이 바뀌며 매크로를 종료시 일반 넘버패드숫자로 작동합니다.

+ 키는 창 최대화,원상복구를 토글합니다. ( 1번 매크로 토글시만, 비활성시엔 그냥 +버튼으로 작동 )

ActiveingKey("PotPlayer64","{left}")   (여기서 PotPlayer64는 class 기준)

팟플레이어64를 활성화시키고 키보드 왼쪽 화살표를 누른 후 이전에 쓰던 창을 다시 활성화 시킵니다.

OpenWindowActive("Notion.exe","C:\Users\Administrator\AppData\Local\Programs\Notion\Notion.exe") 

notion.exe 프로그램을 활성화,최소화합니다, 켜져있지 않을시 실행시킵니다.

WindowKeyPress("whale.exe","!{left}") 

whale.exe 프로그램이 활성화 되어있다면 alt + 화살표왼쪽키를 누릅니다.

vk06A & vk0DD:: ; 매크로 토글 거꾸로 

vk06F & vk0BB:: ; 매크로 토글

vk06F & vk068:: ; 매크로 종료

원하시는 키로 매핑하시면 됩니다
