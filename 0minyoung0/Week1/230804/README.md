# [level 2] 3 x n 타일링 - 12902 

[문제 링크](https://school.programmers.co.kr/learn/courses/30/lessons/12902?language=java) 

### 성능 요약

메모리: 52.2 MB, 시간: 16.24 ms

### 구분

코딩테스트 연습 > 연습문제

### 채점결과

Empty

### 문제 설명

<p>가로 길이가 2이고 세로의 길이가 1인 직사각형 모양의 타일이 있습니다. 이 직사각형 타일을 이용하여 세로의 길이가 3이고 가로의 길이가 n인 바닥을 가득 채우려고 합니다. 타일을 채울 때는 다음과 같이 2가지 방법이 있습니다</p>

<ul>
<li>타일을 가로로 배치 하는 경우</li>
<li>타일을 세로로 배치 하는 경우</li>
</ul>

<p>예를들어서 n이 8인 직사각형은 다음과 같이 채울 수 있습니다.</p>

<p><img src="https://i.imgur.com/zBW7peI.png" title="" alt="Imgur"></p>

<p>직사각형의 가로의 길이 n이 매개변수로 주어질 때, 이 직사각형을 채우는 방법의 수를 return 하는 solution 함수를 완성해주세요.</p>

<h5>제한사항</h5>

<ul>
<li>가로의 길이 n은 5,000이하의 자연수 입니다.</li>
<li>경우의 수가 많아 질 수 있으므로, 경우의 수를 1,000,000,007으로 나눈 나머지를 return해주세요.</li>
</ul>

<h5>입출력 예</h5>
<table class="table">
        <thead><tr>
<th>n</th>
<th>result</th>
</tr>
</thead>
        <tbody><tr>
<td>4</td>
<td>11</td>
</tr>
</tbody>
      </table>
<h5>입출력 예 설명</h5>

<p>입출력 예 #1<br>
다음과 같이 11가지 방법이 있다.<br>
<img src="https://i.imgur.com/nnoT9kL.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/QTZFrTH.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/YE1JfJn.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/QhYvRTr.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/NKgKTIR.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/3uobFxe.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/sEK9oor.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/u6dpiep.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/re3C19N.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/GerdAJB.png" title="" alt="Imgur"><br>
<img src="https://i.imgur.com/ITcbWj0.png" title="" alt="Imgur"></p>


> 출처: 프로그래머스 코딩 테스트 연습, https://programmers.co.kr/learn/challenges