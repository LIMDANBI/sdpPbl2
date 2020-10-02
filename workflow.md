# sdpPbl2

### team member

2019056462 임단비(dlaeksql08222@gmail.com)

2019036380 이다은(delee3064@gmail.com)

2018042797 이승현(leshleekor@hanyang.ac.kr)

2014040946 최여준(tmdcks94@hanyang.ac.kr)

2019042279 백승우(algus1645@hanyang.ac.kr)

2019044211 임승현(lsh0805@hanyang.ac.kr)


### 이전 시간에 제출했던 Git workflow에 대한 설명

> 1. master (Main)

Develop branch에서 통합된 기능들을 최종적으로 버전관리하고 릴리스까지 담당하는 브랜치.

릴리스를 담당하는 브랜치이므로 안정된 상태가 유지되어야 한다.

> 2. develop

master(main) 브렌치를 stable하게 유지하기 위해 master(main)에서 분기된 브랜치.

이하 추가 기능들은 이 브렌치에서 분기하여 개발하고 마찬가지로 이 브렌치로 merge한다.  

master(main) 브렌치로 merge하기 전에 추가된 기능들 간의 충돌을 관리하고 안정된 상태임을 검증한 뒤 master(main) 브렌치로 merge한다.

> 3. features

추가적인 기능을 구현하기 위해 develop branch에서 파생된  branch 이다.

각 팀마다 branch를 feature/f1, feature/f2, feature/f3 로 나누어 개발을 진행한다.

추가기능 구현이 완료되어 commit이 되었다면 develop branch 에 merge/rebase 한다.

> 4. topic

 기능 추가나 버그 수정과 같은 단위 작업을 위한 브랜치다. feature1, hotfix1와 같은 형태를 가지고 있다. 

일반적으로 여러 개의 작업을 동시에 진행할 때, 그 수만큼 브랜치를 생성한다.

develop/feature 브랜치로부터 만들며, 작업 완료시 develop/feature브랜치에 다시 병합한다.

> 결과화면
