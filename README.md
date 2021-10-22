# Inscapee 알고리즘 스터디

## 진행방식

- 매주 수요일 오후 3시 ~ (조율 가능)
- 불참 또는 과제 미제출시 차주 스터디 모임까지 스터디원에게 커피 한잔씩 제공
  - 팀원들이 인정하는 사유가 있으면 통과
- 문제출처 : [Baekjoon](https://www.acmicpc.net/)
- 문제 개수 : 주당 3개
- 제출 방법
  - 해당 주차 디렉토리에 본인 이름 디렉토리 생성
  - 코드 작성 후 PR
- 과제 확인
  - 모임 때 PR 리뷰
- 과제 선정
  - 스터디 종료전 알고리즘 주제 선정 및 백준에서 등급별(60% 초과, 40% ~ 60%, 40% 미만) 문제 선택
- 스터디 진행(2시간)
  - 문제 풀기(난이도 중) : 1시간
  - 문제 리뷰 : 1시간(문제를 해결 한 사람 발언건 우선)

### 백준 node.js 입력 받는 방법
```javascript
const input = require('fs').readFileSync('/dev/stdin').toString();
```

## 커리큘럼

| 주차  | 내용                                   | 과제                                                                                                                                           |
| :---: | :------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 1주차 | Big-O 표기법                           |                                                                                                                                                |
| 2주차 | 구현(Implementation)                   | [10808](https://www.acmicpc.net/problem/10808), [16236](https://www.acmicpc.net/problem/16236), [11332](https://www.acmicpc.net/problem/11332) |
| 3주차 | 탐색(배열 탐색, 문자열 탐색, 완전탐색) | [2665](https://www.acmicpc.net/problem/2665), [14500](https://www.acmicpc.net/problem/14500), [15684](https://www.acmicpc.net/problem/15684)   |
| 4주차 | DFS, BFS                               | [3187](https://www.acmicpc.net/problem/3187), [1260](https://www.acmicpc.net/problem/1260), [1987](https://www.acmicpc.net/problem/1987)       |
| 5주차 | DFS, BFS                               | [16948](https://www.acmicpc.net/problem/16948), [20058](https://www.acmicpc.net/problem/20058), [15971](https://www.acmicpc.net/problem/15971) |
| 6주차 | DP                                     | [10870](https://www.acmicpc.net/problem/10870), [2631](https://www.acmicpc.net/problem/2631), [9656](https://www.acmicpc.net/problem/9656)     |
| 7주차 | Priority Queue, Binary Search          |                [1927](https://www.acmicpc.net/problem/1927), [11279](https://www.acmicpc.net/problem/11279), [1261](https://www.acmicpc.net/problem/1261)                                                                                                                                |
| 8주차 | ...                                    |                                                                                                                                                |

## 공부할 내용

- 시뮬레이션
- 탐색
  - 배열 탐색
  - 문자열 탐색
  - 완전 탐색
  - DFS(깊이 우선 탐색)
  - BFS(너비 우선 탐색)
- 정렬
  - 선택 정렬
  - 버블 정렬
  - 삽입 정렬
- 자료구조
  - 단순구조
    - 정수
    - 실수
    - 문자
    - 문자열
  - 선형구조
    - 순차 리스트
    - 연결 리스트
      - 단순 연결 리스트
      - 이중 연결 리스트
      - 원형 연결 리스트
    - 스택
    - 큐
      - 우선순위큐
    - 덱
  - 비선형구조
    - 트리
      - 일반 트리
      - 이진 트리
    - 그래프
      - 방향 그래프
      - 무방향 그래프
  - 파일구조
    - 순차 파일
    - 색인 파일
    - 직접 파일

## 주차별 주제 디렉토리 생성 방법

```
yarn subject {yymmdd_subject}
```
