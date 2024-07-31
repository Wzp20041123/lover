<!DOCTYPE html>

<html lang="zh" >

<head>
    <meta charset="utf-8" />
    <title></title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        html, body {
            width: 100%;
            height: 100%;
        }

        body {
            background-color: pink;
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
        }

        .heart {
            width: 150px;
            height: 150px;
            background-color: red;
            position: relative;
            transform: rotate(45deg);
            animation: heartbit 1s alternate infinite;
            box-shadow: 0 0 400px red;
        }

            .heart::before {
                content: "";
                background-color: red;
                position: absolute;
                top: 0;
                left: -75px;
                width: 75px;
                height: 150px;
                border-radius: 100px 0 0 100px;
                box-shadow: 0 0 400px red;
            }

            .heart::after {
                content: "";
                background-color: red;
                position: absolute;
                top: -75px;
                left: 0px;
                width: 150px;
                height: 75px;
                border-radius: 100px 100px 0 0;
                box-shadow: 0 0 400px red;
            }

        @keyframes heartbit {
            0% {
                transform: rotate(45deg) scale(0.3);
            }

            100% {
                transform: rotate(45deg) scale(1.5);
            }
        }

        .text {
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
            position: relative;
            transform: rotate(315deg);
            display: flex;
            align-content: center;
            justify-content: center;
            text-align: center;
            font-size: 100px;
            color: lightpink;
        }
    </style>
</head>
<body>
    <div class="heart">
        <div class="text">
            ❀

        </div>
    </div>

</body>
</html>
