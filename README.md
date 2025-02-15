# Valentine-surprise
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day ❤️</title>
    <style>
        body {
            text-align: center;
            background-color: #ffdde1;
            font-family: Arial, sans-serif;
        }
        .container {
            margin-top: 100px;
        }
        .hidden {
            display: none;
        }
        .btn {
            background-color: #ff4d6d;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            cursor: pointer;
        }
        .message {
            margin-top: 20px;
            font-size: 20px;
            color: #d6336c;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Valentine's Day, My Love! ❤️</h1>
        <p>Click the button below for a surprise!</p>
        <button class="btn" onclick="showMessage()">Click Me</button>
        <div id="messageContainer" class="hidden">
            <p class="message">You are the most amazing person in my life, and I am so lucky to have you. Happy Valentine's Day! 💖</p>
            <p class="message">Wishing you endless love, joy, and happiness today and always! 💕</p>
        </div>
    </div>
    
    <script>
        function showMessage() {
            document.getElementById('messageContainer').classList.remove('hidden');
        }
    </script>
</body>
</html>
