# 알고리즘 공부

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=alswns9288)](https://solved.ac/alswns9288/)



## 주의할 점

* input() 대신 sys.stdin.readline() 을 사용하자

    -> input() 으로는 시간초과가 날 수 있음.
* for 문으로 sum 등을 구할 때는 comprehension을 사용하자.

    -> 시간초과가 날 수 있음
    
    ex) sum(tree - mid for tree in trees if tree > mid)

* 분류가 애매한 것은 '구현'으로 작성함

___



## 푼 문제 리스트

| 인덱스 | 문제 | 일자 | 해결 알고리즘 | 사이트 | 비고 |
| ---- | ---- | -------- | ------ | ------ | ------ |
|1 |직사각형에서 탈출 (1085) |2022-02-13 |기하학 |백준 | |
|2 |덩치 (7568) |2022-02-13 |브루트포스 |백준 | |
|3 |영화감독 숌 (1436) |2022-02-13 |브루트포스 |백준 | |
|4 |제로 (10773) |2022-02-13 |스택 |백준 | |
|5 |통계학 (2108) |2022-02-13 |구현, 정렬 |백준 | |
|6 |균형잡힌 세상 (4949) |2022-02-13 |스택 |백준 | |
|7 |스택 수열 (1874) |2022-02-13 |스택 |백준 | |
|8 |나무 자르기 (2805) |2022-02-13 |이진탐색 |백준 | |
|9 |마인크래프트 (18111) |2022-02-14 |구현 |백준 |pypy3 |
|10 |피보나치 함수 (1003) |2022-02-14 |DP |백준 | |
|11 |유기농 배추 (1012) |2022-02-14 |BFS, DFS |백준 | |
|12 |경로 찾기 (11403) |2022-02-15 |플루이드 와샬 |백준 | |
|13 |잃어버린 괄호 (1541) |2022-02-15 |그리디 |백준 | |
|14 |최소 힙 (1927) |2022-02-15 |힙 |백준 | |
|15 |팩리토얼 0의 개수 (1676) |2022-02-16 |구현 |백준 | |
|16 |비밀번호 찾기 (17219) |2022-02-16 |자료구조 |백준 | |
|17 |적록색약 (10026) |2022-02-16 |BFS, DFS |백준 | |
|18 |토마토 (7569) |2022-02-17 |BFS |백준 |pypy3 |
|19 |Four Squares (17626) |2022-02-17 |DP |백준 |pypy3 |
|20 |DFS와 BFS (1260) |2022-02-17 |BFS, DFS |백준 | |
|21 |회의실 배정 (1931) |2022-02-18 |그리디 |백준 | |
|22 |듣보잡 (1764) |2022-02-18 |이진탐색 |백준 |해시로도 가능 (dict) |
|23 |집합 (11723) |2022-02-18 |구현 |백준 | |
|24 |나는야 포켓몬 마스터 이다솜 (1620) |2022-02-19 |해시 |백준 | |
|25 |Z (1074) |2022-02-19 |재귀 |백준 | |
|26 |최대 힙 (11279) |2022-02-19 |힙 |백준 | |
|27 |테트로미노 (14500) |2022-02-20 |구현 |백준 | |
|28 |1로 만들기 (1463) |2022-02-20 |DP |백준 | |
|29 |이중 우선순위 큐 (7662) |2022-02-20 |힙 |백준 | |
|30 |바이러스 (2606) |2022-02-20 |DFS, BFS |백준 | |
|31 |색종이 만들기 (2630) |2022-02-21 |재귀, 분할정복 |백준 | |
|32 |1, 2, 3 더하기 (9095) |2022-02-21 |DFS, 재귀 |백준 |문제 분류는 DP임 |
|33 |ATM (11399) |2022-02-21 |그리디 |백준 | |
|34 |2×n 타일링 (11726) |2022-02-22 |DP |백준 | |
|35 |연결 요소의 개수 (11724) |2022-02-22 |DFS, BFS |백준 | |
|36 |좌표 압축 (18870) |2022-02-22 |정렬 |백준 | |
|37 |절댓값 힙 (11286) |2022-02-22 |힙 |백준 | |
|38 |숨바꼭질 (1697) |2022-02-23 |BFS |백준 | |
|39 |공유기 설치 (2110) |2022-02-23 |이진탐색 |백준 | |
|40 |중량제한 (1939) |2022-02-23 |이진탐색, BFS |백준 |path와 weight를 인접행렬로 표현시 메모리 초과 |
|41 |미로 탐색 (2178) |2022-02-24 |BFS |백준 | |
|42 |플로이드 (11404) |2022-02-25 |플루이드 와샬 |백준 | |
|43 |구간 합 구하기 4 (11659) |2022-02-25 |구간 합 |백준 | |
|44 |크레인 인형뽑기 게임 |2022-02-26 |스택 |프로그래머스 | |
|45 |문자열 내 마음대로 정렬하기 |2022-02-27 |정렬 |프로그래머스 | |
|46 |시저 암호 |2022-02-27 |구현 |프로그래머스 | |
|47 |신규 아이디 추천 |2022-02-28 |구현 |프로그래머스 | |
|48 |모의고사 |2022-03-01 |완전탐색 |프로그래머스 | |
|49 |실패율 |2022-03-02 |구현 |프로그래머스 | |
|50 |숫자 문자열과 영단어 |2022-03-03 |구현 |프로그래머스 | |
|51 |키패드 누르기 |2022-03-04 |구현 |프로그래머스 | |
|52 |신고 결과 받기 |2022-03-05 |자료구조 |프로그래머스 | |
|53 |타겟 넘버 |2022-03-06 |DFS |프로그래머스 | |
|54 |큰 수 만들기 |2022-03-07 |그리디 |프로그래머스 | |
|55 |최댓값과 최솟값 |2022-03-08 |구현 |프로그래머스 | |
|56 |피보나치 수 |2022-03-09 |DP |프로그래머스 |재귀도 가능 |
|57 |괄호 변환 |2022-03-10 |재귀 |프로그래머스 | |
|58 |위장 |2022-03-11 |해쉬 |프로그래머스 | |
|59 |가장 큰 수 |2022-03-12 |정렬 |프로그래머스 | |
|60 |행렬의 곱셈 |2022-03-13 |수학, 구현 |프로그래머스 | |
|61 |네트워크 |2022-03-14 |BFS, DFS |프로그래머스 | |
|62 |가장 먼 노드 |2022-03-16 |BFS |프로그래머스 | |
|63 |카펫 |2022-03-17 |탐색 |프로그래머스 | |
|64 |문자열 압축 |2022-03-21 |압축, 문자열 |프로그래머스 | |
|65 |거리두기 확인하기 |2022-03-24 |BFS |프로그래머스 | |
|66 |기능개발 |2022-03-25 |큐 |프로그래머스 | |
|67 |오픈채팅방 |2022-03-26 |구현 |프로그래머스 | |
|68 |메뉴 리뉴얼 |2022-03-28 |DFS, 조합, 구현 |프로그래머스 | |
|69 |프린터 |2022-03-29 |데크 |프로그래머스 | |
|70 |주차 요금 계산 |2022-03-30 |구현 |프로그래머스 | |
|71 |N과 M (1) (15649) |2022-03-31 |DFS, 백트래킹 |백준 | |
|72 |N과 M (2) (15650) |2022-03-31 |DFS, 백트래킹 |백준 | |
|73 |N-Queen (9663) |2022-03-31 |DFS, 백트래킹 |백준 | |
|74 |다리를 지나는 트럭 |2022-04-01 |큐 |프로그래머스 | |
|75 |합 구하기 (11441) |2022-04-02 |구간합 |백준 | |
|76 |수식 최대화 |2022-04-03 |DFS, 구현 |프로그래머스 | |
|77 |소수 찾기 |2022-04-04 |DFS, 애라토스테네스의 체 |프로그래머스 | |
|78 |튜플 |2022-04-05 |정렬 |프로그래머스 | |
|79 |조이스틱 |2022-04-07 |그리디 |프로그래머스 |다른 사람 풀이 |
|80 |소트인사이드 (1427) |2022-04-08 |정렬 |백준 | |
|81 |N과 M (3) (15651) |2022-04-08 |DFS, 백트래킹 |백준 | |
|82 |동전0 (11047) |2022-04-09 |그리디 |백준 | |
|83 |IOIOI (5525) |2022-04-09 |구현 |백준 | |
|84 |하노이 탑 이동 순서 (11729) |2022-04-10 |재귀 |백준 | |
|85 |피보나치 수 5 (10870) |2022-04-10 |재귀 |백준 | |
|86 |팩토리얼 (10872) |2022-04-10 |재귀 |백준 | |
|87 |별 찍기 - 10 (2447) |2022-04-11 |재귀 |백준 | |
|88 |N과 M (4) (15652) |2022-04-12 |DFS, 백트래킹 |백준 | |
|89 |스도쿠 (2580) |2022-04-13 |DFS, 백트래킹 |백준 | |
|90 |쿼드트리 (1992) |2022-04-14 |재귀, 분할정복 |백준 | |
|91 |종이의 개수 (1780) |2022-04-14 |재귀, 분할정복 |백준 | |
|92 |곱셈 (1629) |2022-04-14 |재귀 |백준 | |
|93 |두 수의 합 (3273) |2022-04-14 |투포인터 |백준 | |
|94 |주유소 (13305) |2022-04-17 |그리디 |백준 | |
|95 |수 정렬하기 (2750) |2022-04-18 |정렬 |백준 | |
|96 |오큰수 (17298) |2022-04-18 |스택 |백준 | |
|97 |연산자 끼워넣기 (14888) |2022-04-18 |DFS |백준 | |
|98 |스타트와 링크 (14889) |2022-04-18 |DFS |백준 | |
|99 |큐2 (18258) |2022-04-19 |큐 |백준 | |
|100 |회전하는 큐 (1021) |2022-04-19 |큐 |백준 | |
|101 |AC (5430) |2022-04-20 |큐 |백준 | |
|102 |신나는 함수 실행 (9184) |2022-04-21 |DP |백준 | |
|103 |Palindrome Index |2022-04-21 |문자열, 투포인터 |HackerRank | |
|104 |가잔 긴 증가하는 부분 수열 (11053) |2022-04-22 |DP |백준 | |
|105 |K번째 수 (1300) |2022-04-23 |이분탐색 |백준 | |
|106 |물약 구매 (24954) |2022-04-24 |조합, 브루트포스 |백준 |pypy3 |
|107 |패션왕 신해빈 (9375) |2022-04-26 |해쉬, 셋 |백준 | |
|108 |연구소 (14502) |2022-04-27 |DFS, BFS |백준 |pypy3 |
|109 |연구소 (14502) |2022-04-28 |DFS, BFS |백준 |java 해결 |
|110 |나이트의 이동 (7562) |2022-04-29 |BFS |백준 | |
|111 |최댓값 구하기 |2022-04-30 | |프로그래머스 |SQL |
|112 |이름이 없는 동물의 아이디 |2022-04-30 | |프로그래머스 |SQL |
|113 |역순 정렬하기 |2022-04-30 | |프로그래머스 |SQL |
|114 |이름이 있는 동물의 아이디 |2022-04-30 | |프로그래머스 |SQL |
|115 |아픈 동물 찾기 |2022-04-30 | |프로그래머스 |SQL |
|116 |상위 n개 레코드 |2022-04-30 | |프로그래머스 |SQL |
|117 |고양이와 개는 몇 마리 있을까 |2022-04-30 | |프로그래머스 |SQL |
|118 |루시와 엘리 찾기 해결 |2022-04-30 | |프로그래머스 |SQL |
|119 |이름에 el이 들어가는 동물 찾기 |2022-04-30 | |프로그래머스 |SQL |
|120 |NULL 처리하기 |2022-04-30 | |프로그래머스 |SQL |
|121 |DATETIME에서 DATE 형 변환 |2022-04-30 | |프로그래머스 |SQL |
|122 |최솟값 구하기 |2022-04-30 | |프로그래머스 |SQL |
|123 |중성화 여부 파악하기 |2022-04-30 | |프로그래머스 |SQL |