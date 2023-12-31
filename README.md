<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Website</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background: linear-gradient(45deg, #4A148C, #880E4F, #B71C1C, #FF6F00);
            background-size: 400% 400%;
            animation: gradientAnimation 15s ease infinite;
        }

        @keyframes gradientAnimation {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }

        .welcome-box {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-family: 'Arial', sans-serif;
            color: #333;
        }

        p {
            font-family: 'Arial', sans-serif;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="welcome-box">
        <h1>Welcome to My Website</h1>
        <p>Thank you for visiting! Feel free to explore and discover.</p>
    </div>

</body>
</html>

