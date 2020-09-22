# 단축키 정리
```c
<ctrl> + <`>
```
터미널 열기
-------
```c
<ctrl> + <s>
```
저장
-------
```c
 블럭잡고 <alt> + <shift> + <아래방향>
```
복사와 붙여넣기 한번에
-------
```c
파일만들고 <!> + <shift>
```
기본적인 틀 생성
-------
```c
<shift> + <alt> + <f>
```
줄정리
-------
```c
 내용작성 <ctrl> + </> 
```
주석이 된다
---------
```c
 <shift> + <delete>
```
한줄지움
----------
# vscode 수정후에는 반드시
```c
git add
git commit -m ''
git push
```
***제발***
# 웹 응용 프로그래밍 2주차 수업 정리
## 앵커(anchor) 태그 
```c
<a href="#content1">이름</a> 
<h1 id="content1">이름</h1>
```
누르면 페이지 내 그 부분으로 이동
```c
<a href="./페이지경로">페이지이름</a>
```
누르면 그 페이지로 이동
## 목록(list) 태그 
```c
<ul>
  <li>아이템 1</li>
  <li>아이템 2</li>
  <li>아이템 3</li>
</ul>
```
*아이템 1   
*아이템 2   
*아이템 3   
```c
<ol>
  <li>아이템 1</li>
  <li>아이템 2</li>
  <li>아이템 3</li>
</ol>
```
1.아이템 1   
2.아이템 2   
3.아이템 3   
## 표(table) 관련 태그
```c
            <table border="1">
        <caption>HTML 태그</caption>
        <thead>
            <tr>
                <th>종류</th>>
                <th>상표</th>>
                <th>메뉴</th>>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>피자</th>
                <td>피자알볼로</td>
                <td>핫치킨골드</td>
            </tr>
            <tr>
                <th rowspan="3">치킨</th>
                <td>비비큐</td>
                <td>황금올리브 닭다리</sup></td>
            </tr>
            <tr>
                <td>푸라닭</td>
                <td>블랙알리오</td>
            </tr>
            <tr>
                <td>비에이치씨</td>
                <td>뿌링클 닭다리</td>
            </tr>
 </table>           
```
종류|상표|메뉴
---|---|---|
피자|피자알볼로|핫치킨골드
치킨|비비큐|황금올리브 닭다리
치킨|푸라닭|블랙알리오|
치킨|비에이치씨|뿌링클 닭다리
(실제로는 치킨 칸이 하나로 병합되어 있다.)
## 공간 분할(space) 태그
```c
<div></div>
```
## 시맨틱(semantic) 구조 태그
```c
<div><a href="./">홈으로 이동</a></div>
``` 
## 이미지 태그
```c
<img src="./images/이미지이름.jpg" alt="1st image" height="200">
```
## 오디오 태그
```c
<audio src="./sounds/외디오이름.wav" controls></audio>
  
          or
  
  <audio controls loop>
    <source src="./sounds/오디오 이름.wav" type="audio/wav">
  </audio>
```
## 비디오 태그
```c
<video controls height="300">
    <source src="./videos/비디오이름.mp4" type="video/mp4">
  </video>
```
 ## Youtube 비디오 넣기
 ```c
 <iframe width="560" height="315"
          src="영상소스코드"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen></iframe>
 ```
