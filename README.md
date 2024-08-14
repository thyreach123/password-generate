<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>
<body>
    <div class="container">
        <h1><span>Password Generator</span></h1>
        <div class="display">
            <input type="text" id="password" placeholder="password">
            <img src="images/copy.png" onclick="copyPassword()">
        </div>
        <button onclick="createPassword()"><img src="images/generate.png">Generate Password</button>

        <div id="copyStatus" class="copyStatus">Copied to Clipboard</div>
    </div>
    
</body>
<script type="text/javascript" src="function.js"></script>
</html>
