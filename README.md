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
|31 |색종이 만들기 (2630) |2022-02-21 |재귀 |백준 | |
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