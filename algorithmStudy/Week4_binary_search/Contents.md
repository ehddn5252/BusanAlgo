### 목차
[0. 색종이 만들기](#promblem-0)
[1. 수 찾기](#promblem-1)
[2. 듣보잡](#promblem-2)
[3. 공유기 설치](#promblem-3)
[4. 가장 긴 증가하는 부분 수열2](#promblem-4)
#

### [다시 목차로](#목차)

### promblem0

### [2630 색종이 만들기](https://www.acmicpc.net/problem/2630)


시간 제한 | 메모리 제한 |	제출 | 정답| 맞은 사람 | 정답 비율
------|------|------|------|------|------
1 초 | 128 MB | 7698 | 5320 | 4455 | 71.612%


문제
<br>
    아래 <그림 1>과 같이 여러개의 정사각형칸들로 이루어진 정사각형 모양의 종이가 주어져 있고, 각 정사각형들은 하얀색으로 칠해져 있거나 파란색으로 칠해져 있다. 주어진 종이를 일정한 규칙에 따라 잘라서 다양한 크기를 가진 정사각형 모양의 하얀색 또는 파란색 색종이를 만들려고 한다.



전체 종이의 크기가 N×N(N=2k, k는 1 이상 7 이하의 자연수) 이라면 종이를 자르는 규칙은 다음과 같다.

전체 종이가 모두 같은 색으로 칠해져 있지 않으면 가로와 세로로 중간 부분을 잘라서 <그림 2>의 I, II, III, IV와 같이 똑같은 크기의 네 개의 N/2 × N/2색종이로 나눈다. 나누어진 종이 I, II, III, IV 각각에 대해서도 앞에서와 마찬가지로 모두 같은 색으로 칠해져 있지 않으면 같은 방법으로 똑같은 크기의 네 개의 색종이로 나눈다. 이와 같은 과정을 잘라진 종이가 모두 하얀색 또는 모두 파란색으로 칠해져 있거나, 하나의 정사각형 칸이 되어 더 이상 자를 수 없을 때까지 반복한다.

위와 같은 규칙에 따라 잘랐을 때 <그림 3>은 <그림 1>의 종이를 처음 나눈 후의 상태를, <그림 4>는 두 번째 나눈 후의 상태를, <그림 5>는 최종적으로 만들어진 다양한 크기의 9장의 하얀색 색종이와 7장의 파란색 색종이를 보여주고 있다.



입력으로 주어진 종이의 한 변의 길이 N과 각 정사각형칸의 색(하얀색 또는 파란색)이 주어질 때 잘라진 하얀색 색종이와 파란색 색종이의 개수를 구하는 프로그램을 작성하시오.

입력
<br>
첫째 줄에는 전체 종이의 한 변의 길이 N이 주어져 있다. N은 2, 4, 8, 16, 32, 64, 128 중 하나이다. 색종이의 각 가로줄의 정사각형칸들의 색이 윗줄부터 차례로 둘째 줄부터 마지막 줄까지 주어진다. 하얀색으로 칠해진 칸은 0, 파란색으로 칠해진 칸은 1로 주어지며, 각 숫자 사이에는 빈칸이 하나씩 있다.

출력 
<br>
첫째 줄에는 잘라진 햐얀색 색종이의 개수를 출력하고, 둘째 줄에는 파란색 색종이의 개수를 출력한다.
<br>
  <h3>예시입력</h3>

```Python
8
1 1 0 0 0 0 1 1
1 1 0 0 0 0 1 1
0 0 0 0 1 1 0 0
0 0 0 0 1 1 0 0
1 0 0 0 1 1 1 1
0 1 0 0 1 1 1 1
0 0 1 1 1 1 1 1
0 0 1 1 1 1 1 1
```
<h3>예시출력</h3>

```python
9
7
```
### [다시 목차로](#목차)

### promblem1

### [1920 수 찾기](https://www.acmicpc.net/problem/1920)


시간 제한 | 메모리 제한 |	제출 | 정답| 맞은 사람 | 정답 비율
------|------|------|------|------|------
2 초 | 128 MB | 66662 | 20003 | 13062 | 29.696%


문제
<br>

N개의 정수 A[1], A[2], …, A[N]이 주어져 있을 때, 이 안에 X라는 정수가 존재하는지 알아내는 프로그램을 작성하시오.

입력
첫째 줄에 자연수 N(1≤N≤100,000)이 주어진다. 다음 줄에는 N개의 정수 A[1], A[2], …, A[N]이 주어진다. 다음 줄에는 M(1≤M≤100,000)이 주어진다. 다음 줄에는 M개의 수들이 주어지는데, 이 수들이 A안에 존재하는지 알아내면 된다. 모든 정수의 범위는 -231 보다 크거나 같고 231보다 작다.

출력
M개의 줄에 답을 출력한다. 존재하면 1을, 존재하지 않으면 0을 출력한다.
<br>


<br>
  <h3>예시입력</h3>

```Python
5
4 1 5 2 3
5
1 3 7 9 5
```
<h3>예시출력</h3>

```python
1
1
0
0
1
```



### [다시 목차로](#목차)
### promblem 2
### [1764 듣보잡](https://www.acmicpc.net/problem/1764)

시간 제한 | 메모리 제한 |	제출 | 정답| 맞은 사람 | 정답 비율
------|------|------|------|------|------
2 초 | 256 MB	| 21622 | 8617 | 6092 | 39.202%
<br>

문제
<br>
김진영이 듣도 못한 사람의 명단과, 보도 못한 사람의 명단이 주어질 때, 듣도 보도 못한 사람의 명단을 구하는 프로그램을 작성하시오.

입력
<br>
첫째 줄에 듣도 못한 사람의 수 N, 보도 못한 사람의 수 M이 주어진다. 이어서 둘째 줄부터 N개의 줄에 걸쳐 듣도 못한 사람의 이름과, N+2째 줄부터 보도 못한 사람의 이름이 순서대로 주어진다. 이름은 띄어쓰기 없이 영어 소문자로만 이루어지며, 그 길이는 20 이하이다. N, M은 500,000 이하의 자연수이다.

출력
<br>
듣보잡의 수와 그 명단을 사전순으로 출력한다.
예시입력
```Python
3 4
ohhenrie
charlie
baesangwook
obama
baesangwook
ohhenrie
clinton
```

예시출력
```Python
2
baesangwook
ohhenrie
```

### [다시 목차로](#목차)
### promblem 3
### [2110 공유기](https://www.acmicpc.net/problem/2110)

시간 제한 | 메모리 제한 |	제출 | 정답| 맞은 사람 | 정답 비율
------|------|------|------|------|------
2 초 | 128 MB | 13652 | 6055 | 4486 | 45.930%

<br>
문제
<br>
도현이의 집 N개가 수직선 위에 있다. 각각의 집의 좌표는 x1, ..., xN이고, 집 여러개가 같은 좌표를 가지는 일은 없다.

도현이는 언제 어디서나 와이파이를 즐기기 위해서 집에 공유기 C개를 설치하려고 한다. 최대한 많은 곳에서 와이파이를 사용하려고 하기 때문에, 한 집에는 공유기를 하나만 설치할 수 있고, 가장 인접한 두 공유기 사이의 거리를 가능한 크게 하여 설치하려고 한다.

C개의 공유기를 N개의 집에 적당히 설치해서, 가장 인접한 두 공유기 사이의 거리를 최대로 하는 프로그램을 작성하시오.

입력
<br>
첫째 줄에 집의 개수 N (2 ≤ N ≤ 200,000)과 공유기의 개수 C (2 ≤ C ≤ N)이 하나 이상의 빈 칸을 사이에 두고 주어진다. 둘째 줄부터 N개의 줄에는 집의 좌표를 나타내는 xi (1 ≤ xi ≤ 1,000,000,000)가 한 줄에 하나씩 주어진다.

출력
<br>
첫째 줄에 가장 인접한 두 공유기 사이의 최대 거리를 출력한다.

예시입력
```Python
5 3
1
2
8
4
9
```

예시출력
```Python
3
```

### [다시 목차로](#목차)
### promblem 4
### [12015 가장 긴 증가하는 부분 수열2](https://www.acmicpc.net/problem/12015)

시간 제한 | 메모리 제한 |	제출 | 정답| 맞은 사람 | 정답 비율
------|------|------|------|------|------
1 초 | 512 MB | 10693 | 4690 | 3242 | 46.117%
<br>
문제
<br>

수열 A가 주어졌을 때, 가장 긴 증가하는 부분 수열을 구하는 프로그램을 작성하시오.

예를 들어, 수열 A = {10, 20, 10, 30, 20, 50} 인 경우에 가장 긴 증가하는 부분 수열은 A = {10, 20, 10, 30, 20, 50} 이고, 길이는 4이다.

입력
<br>
첫째 줄에 수열 A의 크기 N (1 ≤ N ≤ 1,000,000)이 주어진다.

둘째 줄에는 수열 A를 이루고 있는 Ai가 주어진다. (1 ≤ Ai ≤ 1,000,000)

출력
<br>
첫째 줄에 수열 A의 가장 긴 증가하는 부분 수열의 길이를 출력한다.

예시입력
```Python
6
10 20 10 30 20 50
```

예시출력
```Python
4
```
