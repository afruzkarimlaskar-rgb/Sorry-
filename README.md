<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry, My Love</title>
    <style>
        body {
            background-color: lightpink;
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding: 50px;
            margin: 0;
            overflow: hidden;
        }
        h1 {
            color: #ff69b4;
            font-size: 3em;
            animation: bounce 2s infinite;
        }
        p {
            font-size: 1.5em;
            color: #333;
            margin: 20px 0;
        }
        .heart {
            font-size: 100px;
            animation: float 3s ease-in-out infinite;
            display: inline-block;
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-30px); }
            60% { transform: translateY(-15px); }
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Sorry, My Love!</h1>
        <p>I'm truly sorry for whatever I did. You mean the world to me, and I love you more than anything. Please forgive me?</p>
        <div class="heart">❤️</div>
    </div>
</body>
</html>
