<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You</title>
    <style>
        /* Reset and center everything on the screen */
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ffe6e6, #ffb3ba);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
        }

        /* Container for the content */
        .card {
            text-align: center;
            background: rgba(255, 255, 255, 0.85);
            padding: 40px 60px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        /* The text styling */
        h1 {
            color: #ff4d6d;
            font-size: 3rem;
            margin: 0 0 20px 0;
            letter-spacing: 2px;
        }

        /* Animated Heart */
        .heart {
            color: #ff0a54;
            font-size: 5rem;
            animation: pulse 1.2s infinite;
            display: inline-block;
        }

        /* Heart beating animation */
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            30% {
                transform: scale(1.2);
            }
            60% {
                transform: scale(1);
            }
            80% {
                transform: scale(1.15);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="heart">❤️</div>
        <h1>I Love You</h1>
    </div>

</body>
</html>

