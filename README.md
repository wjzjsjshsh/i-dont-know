<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #0d0d13;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
        }

        .container {
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
        }

        .heart {
            position: relative;
            width: 100px;
            height: 90px;
            background-color: #ff2a5f;
            transform: rotate(-45deg);
            animation: beat 1.2s infinite ease-in-out;
            box-shadow: 0 0 40px #ff2a5f, 0 0 80px #ff2a5f;
        }

        .heart::before,
        .heart::after {
            content: "";
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: #ff2a5f;
            border-radius: 50%;
        }

        .heart::before {
            top: -50px;
            left: 0;
        }

        .heart::after {
            top: 0;
            left: 50px;
        }

        .text {
            font-size: 3rem;
            font-weight: 800;
            color: #ffffff;
            text-transform: uppercase;
            letter-spacing: 4px;
            text-shadow: 0 0 10px #ff2a5f, 0 0 20px #ff2a5f, 0 0 40px #ff2a5f;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes beat {
            0% {
                transform: scale(1) rotate(-45deg);
            }
            30% {
                transform: scale(1.25) rotate(-45deg);
            }
            60% {
                transform: scale(1) rotate(-45deg);
            }
            80% {
                transform: scale(1.15) rotate(-45deg);
            }
            100% {
                transform: scale(1) rotate(-45deg);
            }
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="heart"></div>
        <div class="text">I Love You</div>
    </div>

</body>
</html>
