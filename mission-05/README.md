<!-- sprite 이미지 --><br><br>

1. .favorite__list 안의 li 에 sprite 클래스를 준 뒤 <br>
    .sprite {<br>
      background: url(./images/rank.png) no-repeat;<br>
    }<br>
    배경이미지를 설정해둔다.<br>

2. 각 번호 마다 들어가는 이미지의 위치 값을 지정해준다.<br>
   .favorite__list li:nth-child(1) {<br>
    background-position: right 3px;<br>
  }<br>

      .favorite__list li:nth-child(2) {<br>
        background-position: right -33.666px;<br>
      }<br>


      .favorite__list li:nth-child(3) {<br>
        background-position: right -15.333px;<br>
      }<br>


      .favorite__list li:nth-child(4) {<br>
        background-position: right 3px;<br>
      }<br>

<p>*완성본*</p><br>
![image](https://github.com/seonyeongyoon/home-work/assets/66238849/b9b6dc5e-2010-4f2e-9bba-045cde7b3f85)
