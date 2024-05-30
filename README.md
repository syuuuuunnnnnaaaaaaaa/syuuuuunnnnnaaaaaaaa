Top 명령어
-실시간으로 CPU 사용률을 체크해주는 도구
-시스템의 상태를 전반적으로 가장 빠르게 파악 가능(CPU,Memory,Process)
-리눅스를 사용하는 서버의 성능이나 현재 돌아가고 있는 상황을 볼때 사용
-리눅스에서 top 명령어를 치고 들어가면 됨
-옵션 없이 입력하면 interver간격(3초)으로 화면 갱신
-순간의 정보를 확인하려면 '-b' 옵션 추가
 '-n':top실행 주기 설정 (반복 횟수)

Ps 명령어
-Process State의 약자로 현재 실행 중인 프로세스와 상태를 출력하는 명령어
-사용자와 관련된 프로세스만 출력
-ps명령어 출력 항목(ex3개)
1.PID:프로세스의 식별 번호
2.%CPU:cpu사용 비율의 추정치
3.PRI:실제 실행 우선순위
-명령어 옵션
1.-A:모든 프로세스를 출력
2.-a:세션 리더를 제외하고 터미넣에 종속되지 않은 모든 프로세스 출력
3.-f:출력을 풀 포맷으로 표기

jobs 명령어
-옵션이나 인자 없이 주로 사용. 단 ,실행중인 작업이 없다면 아무것도 출력되지 않음
-명령어 옵션
1.-i:프로세스 id와 함꼐 잡 목록을 출력.
2.-p:잡의 프로세스 id만 출력.
3.-s:중지된 잡만 출력.

kill 명령어
-동작하고 있는 프로세스에 간단한 메시지를 보내는 명령어.
-기본적으로 보내는 메시지는 종료 메시지임
-kill은 종료와 무고나한 메시지 보낼 떄도 사용
-내부적으로 kill()이란 시스템 콜을 사용하여 구분
-신호가 지정되지 않은 경우 기본값은 -15(-term)
