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
            justify-content: center;
            align-items: center;
            background-color: #d9d9d9;
        }
        .outer-box {
            width: 95%;
            height: 95%;
            background-color: #a9a9a9;
            border: 2px solid #000;
            box-sizing: border-box;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            position: relative;
            width: 90%;
            height: 90%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #b7b7b7;
            border: 2px solid #000;
            box-sizing: border-box;
        }
        .Rectangle-2 {
            width: 100%;
            height: 100%;
            background-color: #b7b7b7;
            border: 0.5px solid black;
            box-sizing: border-box;
            position: absolute;
            top: 0;
            left: 0;
        }
        .Rectangle-3 {
            width: 106px;
            height: 45px;
            background-color: #d9d9d9;
            border: 0.5px solid #aeaeae;
            box-sizing: border-box;
            margin: 10px;
        }
        .image-251 {
            width: 69.5px;
            height: 76.5px;
            background-color: rgb(255, 240, 50);
            margin-top: 20px;
        }
        .Vector {
            width: 90%;
            height: 60%;
            background-color: white;
            border: 0.5px solid black;
            box-sizing: border-box;
            position: absolute;
            bottom: 20%; /* 아래로 약간 내림 */
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .Vector .top-left-image {
            position: absolute;
            top: 20px;
            left: 20px;
            width: 150px; /* 원하는 크기로 설정 */
            height: auto;
        }
        .Vector .center-image {
            max-width: 25%;
            max-height: 25%;
            margin-top: 20px; /* 이미지를 아래로 내림 */
        }
        .text-box {
            font-family: 'LINESeedSansKR', sans-serif;
            font-size: 16px;
            color: black;
            margin-bottom: 10px; /* 텍스트와 이미지 사이의 간격 조정 */
        }
        .Frame-1000004919 {
            width: 250px; /* 버튼 크기 조정 */
            height: 50px; /* 버튼 크기 조정 */
            background-color: white;
            border-radius: 50px;
            border: 1.5px solid black;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 20px;
            cursor: pointer;
            position: relative;
            z-index: 10; /* 버튼이 다른 요소 위에 표시되도록 */
        }
        .Frame-1000004919 button {
            font-family: 'LINESeedSansKR-Bold', sans-serif;
            font-size: 16px; /* 글자 크기 조정 */
            color: black;
            background-color: white;
            border: none;
            cursor: pointer;
        }
        .Ellipse-2, .Ellipse-3 {
            display: none; /* 원 삭제 */
        }
        .additional-images-container {
            width: 90%;
            position: absolute;
            bottom: 5%; /* 흰색 네모 박스 아래에 위치 */
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #ffffff;
            border: 1px solid #000;
            box-sizing: border-box;
            padding: 10px;
            clip-path: polygon(0% 0%, 100% 0%, 120% 100%, -20% 100%); /* 사다리꼴 모양 */
        }
        .additional-images {
            display: flex;
            justify-content: space-around;
            width: 100%;
        }
        .additional-images img {
            width: 150px; /* 이미지 크기 조정 */
            height: auto;
        }
    </style>
</head>
<body>
    <div class="outer-box">
        <div class="container">
            <div class="Rectangle-2"></div>
            <div class="Rectangle-3"></div>
            <div class="Rectangle-3"></div>
            <div class="image-251"></div>
            <div class="Vector">
                <div class="text-box">
                    안녕, 나는 부덕이야~<br>
                    부스트캠프 미션 부스에 온 걸 환영해<br>
                    시작 버튼을 누르면 퀴즈를 풀어봐!
                </div>
                <img src="자산 1.png" alt="Central Image" class="center-image"> <!-- 중앙 이미지 -->
            </div>
            <div class="Frame-1000004919">
                <button onclick="window.location.href='sec.html'">시 - 작 - 하 - 기</button>
            </div>
            <div class="additional-images-container">
                <div class="additional-images">
                    <img src="레이어 1.png" alt="레이어 1.png"> <!-- 추가 이미지 1 링크 -->
                    <img src="레이어 1.png" alt="레이어 1.png"> <!-- 추가 이미지 2 링크 -->
                </div>
            </div>
        </div>
    </div>
</body>
</html>
