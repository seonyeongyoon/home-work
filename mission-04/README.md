1. .news class를 가진 section을 .news-title__area(제목 영역), .news__img(이미지 영역), news__content(본문 영역)으로 나눈다. <br/>
2. .news에 display: grid를 적용하고, 
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: auto;
    width: 380px;
    gap: 1.25rem;
  속성을 적용하여 사이 간격이 1.25rem이고 12컬럼으로 나눠진 형태의 그리드를 만든다. <br/>
3. 
  .news-title__area {
    grid-area: 1 / 1 / 2 / 13;
    ...
  }

  .news__img {
    grid-area: 2 / 1 / 4 / 6;
    ...
  }

  .news__content {
    grid-area: 2 / 6 / 4 / 13;
    ...
  }
  제목, 이미지, 본문 영역에 위와 같이 그리드를 적용하여 시안에 맞게 배치한다.
  
![화면 캡처 2023-06-12 223110](https://github.com/seonyeongyoon/home-work/assets/66238849/1410d324-b59c-44fc-a922-21b3fcbfa183) <br/>
![image](https://github.com/seonyeongyoon/home-work/assets/66238849/9127e98d-273a-4ddb-8323-2e1c28bd3c79)
