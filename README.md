# 장민수 개인프로젝트
 조작키 : W,A,S,D 이동, 마우스 방향으로 바라보고 왼클릭 시 공격합니다. 쉬프트키를 눌러 이동속도를 늘려 빠르게 이동할수있지만
 스테미너가 존재하여 항상 달릴 수는 없습니다. 적에게 총 5대를 맞게 되면 사망하게 됩니다.
 맵에는 랜덤한 위치에 동전이 생성됩니다. 해당 동전은 개당 10점으로 총 100점을 먹게되면 되는 게임입니다.
 적으로 고블린이 맵에 랜덤스폰되며 최대 3마리까지 소환됩니다.
 동전과 고블린은 최대 개수에 도달하면 더 생성되지 않으며 사라진 오브젝트들은 다시 재활용 됩니다
 적은 A* 알고리즘을 기반으로 이동되며 Wall레이어로 설정된 장애물을 회피하여 플레이어의 위치로 이동하게됩니다. 플레이어가 A* 알고리즘
 인식 범위 밖에 있다면 인식범위내에 플레이어와 가장 가까운 좌표를 목표로 이동하여 점점 다가옵니다. 목표지점에 도달하면 다시 A* 알고리즘을 시작하는 방식으로 플레이어를 추격합니다.