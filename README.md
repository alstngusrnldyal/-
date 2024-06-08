<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>서현퀸 과 수현퀸의동짓팥죽먹브레드</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 20px;
        }
        p {
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>안녕하세용!</h1>
    </header>
    <div class="container">
        <h2>팥쥭죽죽팥</h2>
        <p>안녕하세요! 이 곳은 나의 설빙입니당. 빙수를 만들어봐요!</p>
        <p>다양한 떡토핑과 젤리를 사용하여 나만의 멋진 빙수를 만들어보세요!</p>
    </div>
</body>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <script>
        function updateTime() {
            var now = new Date();
            var hours = now.getHours();
            var minutes = now.getMinutes();
            var seconds = now.getSeconds();
            document.getElementById('time').textContent = hours + ':' + minutes + ':' + seconds;
        }
        setInterval(updateTime, 1000);
    </script>
</head>
<body>
    현재야~~(임솔)의 시간: <span id="time"></span>
</body>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>로고 애니메이션</title>
    <style>
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .logo {
            width: 20px;
            height: 30px;
            background-color: #ffcc00;
            animation: rotate 2s linear infinite;
        }
    </style>
</head>
<body>
    <div class="logo"></div>
</body>
어때요? 신기하죠?
더잇음
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>하트 로고 애니메이션</title>
    <style>
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .heart {
            width: 50px;
            height: 50px;
            background-color: #ff6b6b;
            position: relative;
            animation: rotate 2s linear infinite;
        }
        .heart::before,
        .heart::after {
            content: "";
            position: absolute;
            top: 0;
            width: 100px;
            height: 140px;
            background-color: #ff6b6b;
            border-radius: 100px 100px 0 0;
        }
        .heart::before {
            left: 50px;
            transform: rotate(-45deg);
            transform-origin: 0 100%;
        }
        .heart::after {
            left: 0;
            transform: rotate(45deg);
            transform-origin: 100% 100%;
        }
    </style>
</head>
<body>
    <div class="heart"></div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>하트 로고 애니메이션</title>
    <style>
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        .heart {
            width: 150px;
            height: 150px;
            background-color: #ff6b6b;
            position: relative;
            animation: rotate 2s linear infinite;
        }
        .heart::before,
        .heart::after {
            content: "";
            position: absolute;
            top: 0;
            width: 100px;
            height: 140px;
            background-color: #ff6b6b;
            border-radius: 100px 100px 0 0;
        }
        .heart::before {
            left: 50px;
            transform: rotate(-45deg);
            transform-origin: 0 100%;
        }
        .heart::after {
            left: 0;
            transform: rotate(45deg);
            transform-origin: 100% 100%;
        }
    </style>
</head>
<body>
    <div class="heart"></div>
</body>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>귀여운 햄스터 사진</title>
    <style>
        .hamster-img {
            width: 300px;
            height: auto;
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <img src="https://i.imgur.com/zUdwW.jpg" alt="귀여운 햄스터" class="hamster-img">
</body>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>귀여운 토끼 로고</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        .rabbit-logo {
            width: 150px;
            height: 150px;
            background-color: #ffc0cb;
            border-radius: 50%;
            position: relative;
        }

        .rabbit-ear {
            position: absolute;
            top: 20%;
            width: 50px;
            height: 80px;
            background-color: #ffc0cb;
            border-radius: 50%;
            transform: rotate(-45deg);
        }

        .rabbit-ear.left {
            left: 15%;
        }

        .rabbit-ear.right {
            right: 15%;
            transform: rotate(45deg);
        }

        .rabbit-face {
            position: absolute;
            top: 40%;
            left: 25%;
            width: 50%;
            height: 50%;
            background-color: white;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <div class="rabbit-logo">
        <div class="rabbit-ear left"></div>
        <div class="rabbit-ear right"></div>
        <div class="rabbit-face"></div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>귀여운 토끼 로고</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        .rabbit-logo {
            width: 150px;
            height: 150px;
            background-color: #ffc0cb;
            border-radius: 50%;
            position: relative;
        }

        .rabbit-ear {
            position: absolute;
            top: 20%;
            width: 50px;
            height: 80px;
            background-color: #ffc0cb;
            border-radius: 50%;
            transform: rotate(-45deg);
        }

        .rabbit-ear.left {
            left: 15%;
        }

        .rabbit-ear.right {
            right: 15%;
            transform: rotate(45deg);
        }

        .rabbit-face {
            position: absolute;
            top: 40%;
            left: 25%;
            width: 50%;
            height: 50%;
            background-color: white;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <div class="rabbit-logo">
        <div class="rabbit-ear left"></div>
        <div class="rabbit-ear right"></div>
        <div class="rabbit-face"></div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>귀여운 토끼 로고</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

        .rabbit-logo {
            width: 150px;
            height: 150px;
            background-color: #ffc0cb;
            border-radius: 50%;
            position: relative;
        }

        .rabbit-ear {
            position: absolute;
            top: 20%;
            width: 50px;
            height: 80px;
            background-color: #ffc0cb;
            border-radius: 50%;
            transform: rotate(-45deg);
        }

        .rabbit-ear.left {
            left: 15%;
        }

        .rabbit-ear.right {
            right: 15%;
            transform: rotate(45deg);
        }

        .rabbit-face {
            position: absolute;
            top: 40%;
            left: 25%;
            width: 50%;
            height: 50%;
            background-color: white;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <div class="rabbit-logo">
        <div class="rabbit-ear left"></div>
        <div class="rabbit-ear right"></div>
        <div class="rabbit-face"></div>
    </div>
</body>
</html>


