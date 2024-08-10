<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .Rectangle-3 {
            width: 1280px;
            height: 600px;
            flex-grow: 0;
            padding: 32px 421px 83px 40px;
            border: solid 1px #000;
            background-color: #fff;
            box-sizing: border-box;
            margin-top: 50px; /* 페이지 상단에서 약간 아래로 위치 */
        }
        .Rectangle-14 {
            width: 1440px;
            height: 250px;
            margin: 50px 0 0; /* 페이지 상단과 간격 추가 */
            background-image: linear-gradient(to right, #1e1e1e, #dadada);
        }
        .content {
            font-size: 18px;
            color: #333;
        }
        .date {
            text-align: right;
            font-size: 14px;
            color: #555;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <div class="Rectangle-3">
        <div class="date">8/10(토)</div>
        <div class="content">
            <!-- 여기에 원하는 텍스트나 콘텐츠를 추가하세요 -->
            여기에 텍스트를 입력하세요.
        </div>
    </div>

    <div class="Rectangle-14">
        <!-- 이 영역에 추가적인 콘텐츠를 넣을 수 있습니다 -->
    </div>

</body>
</html>
