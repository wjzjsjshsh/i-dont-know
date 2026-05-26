<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bre Mn Sheremn</title>
    <style>
        /* Reset and center everything on the screen */
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
            background-color: #000000; /* Black background */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
        }

        /* Container for the text and heart */
        .card {
            background-color: #ffffff; /* White card background */
            padding: 40px 60px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: scale(1.05);
        }

        /* Styling the text */
        .text {
            color: #000000; /* Black text */
            font-size: 2.5rem;
            font-weight: 700;
            letter-spacing: 1px;
            margin-bottom: 20px;
        }

        /* Styling the black heart */
        .heart {
            font-size: 3rem;
            color: #000000; /* Black heart */
            display: inline-block;
            animation: pulse 1.5s infinite;
        }

        /* Smooth pulsing animation for the heart */
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
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
        <div class="text">bre mn sheremn</div>
        <div class="heart">&#x2665;</div>
    </div>

</body>
</html>

