<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>動物世界真奇妙</title>
    <style>
      .container {
        width: 92%;      /*佔全網頁的水平92%*/
        padding: 4px;   /*box與contanier的距離*/
        background: rgb(197, 197, 227);
        margin: 100px auto; /*跟上面的距離.左右自動調整*/
        display: flex;    /*將box由垂直變成水平*/
        justify-self: center;   /*box置中水平對齊方式*/
      }
      .box {
        width: 210px;
        height: 300px;
        background: #e892eb;
        margin: 6px 8px;/*box與box之間距離*/
        text-align:center;
      }
      .box:hover{
        transform: scale(1.2);/*選到的box放大1.2*/
        background: #96b3db;/*選到box放大後顏色*/
        box-shadow: 3px 3px 3px #ff800a55;/*選到box設陰影*/
        z-index: 2; /*設定元素的堆疊順序-在container之上*/
      }
      img{
        margin: 5px;/*圖片與box的邊距*/
        box-shadow: 2px 2px 10px #4a06f6f3;/*設圖片的陰影*/
        height: 260px;
        width: 200px;
        border-radius: 10px 10px 10px 10px;
      }
      body{
        background-image: url(media/background.jpg);
      }
      h1{
        font-size: 300%;
        text-align: center;
      }
      .effect{
            animation: blink 2s infinite; 
            color: #4d0adc;
            font-size: 3em;
            
        }
        @keyframes blink{
            0%{opacity: 0;}
            50%{opacity: 1;}
            100%{opacity: 0;}
        }
    </style>
  </head>

  <body>
    <h1 class="effect">動物世界真奇妙</h1>
    <div class="container">
      <div class="box"><a href="world-animal-day.html"><img src="media/index-world-animal-day.jpg" alt="" ></a>
        世界動物日</div>
      <div class="box"><a href="Animal-Encyclopedia.html"><img src="media/index-Animal-Encyclopedia.jpg" alt=""></a>動物圖鑑</div>
      <div class="box"><a href="funny-videos.html"><img src="media/index-funny-video.jpg" alt=""></a>有趣的影片</div>
      <div class="box"><a href="animal-map.html"><img src="media/index-animal-map.jpg" alt=""></a>動物地圖</div>
      <div class="box"><a href="Questionnaire.html"><img src="media/index-Questionnaire.png" alt=""></a>問卷</div>
     
    </div>
  </body>
</html>
