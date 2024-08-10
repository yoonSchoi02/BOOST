<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        @import url('https://cdn.jsdelivr.net/gh/webfontworld/LINESeedKR/LINESeedSansKR.css');
        
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: #d9d9d9;
        }
        .outer-box {
            width: 95%;
            height: 70%;
            background-color: #a9a9a9;
            border: 2px solid #000;
            box-sizing: border-box;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        .Vector {
            width: 95%;
            height: 90%;
            background-color: white;
            border: 1px solid black;
            box-sizing: border-box;
            position: absolute;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            z-index: 1;
        }
        .Vector .top-left-image {
            position: absolute;
            top: 20px;
            left: 20px;
            width: 150px;
            height: auto;
        }
        .Vector .center-image {
            max-width: 30%;
            max-height: 30%;
            margin-top: 30px;
        }
        .text-box {
            font-family: 'LINESeedSansKR-Bold', sans-serif;
            font-size: 30px;
            color: black;
            margin-bottom: 10px;
        }
        .bottom_box {
            width: 95%;
            height: 20%;
            background-color: white;
            border: 2px solid black;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            z-index: 10;
        }
        .additional-images {
            display: flex;
            justify-content: space-around;
            width: 50%; /* 너비를 50%로 줄임 */
        }

        .additional-images img {
            width: 100px; /* 이미지 크기 줄임 */
            height: auto;
            margin-left: 150px; /* 이미지 위치를 오른쪽으로 조금 이동 */
            transition: transform 0.3s ease;
            cursor: pointer;
        }

        .additional-images img:hover {
            transform: translateX(10px); /* 호버 시 오른쪽으로 이동 */
        }
    </style>
</head>
<body>
    <div class="outer-box">
        <div class="Vector">
            <img src="boost logo.png" alt="Top Left Image" class="top-left-image"> <!-- 좌측 상단에 추가할 이미지 링크 -->
            <div class="text-box">
                안녕, 나는 부덕이야~<br>
                부스트캠프 미션 부스에 온 걸 환영해<br>
                시작 스틱을 눌러서 퀴즈를 풀어봐!
            </div>
            <img src="자산 1.png" alt="Central Image" class="center-image"> <!-- 중앙 이미지 -->
        </div>
    </div>

    <div class="bottom_box">
        <div class="additional-images">
            <a href="sec.html">
            <img src="레이어 1.png" alt="레이어 1.png"> <!-- 추가 이미지 2 링크 -->
        </div>
    </div>
</body>
</html>
