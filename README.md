# math-study-notes-2022
We love to work with people
<!DOCTYPE html>
<html>
<head>
    <title>My Math Class Portfolio</title>
    <style>
        body, html { margin: 0; padding: 0; height: 100%; overflow: hidden; font-family: sans-serif; background: #111; color: white; }
        .navbar { display: flex; background: #222; padding: 10px; gap: 10px; justify-content: center; }
        .nav-btn { background: #444; color: white; border: none; padding: 8px 16px; cursor: pointer; border-radius: 4px; font-weight: bold; }
        .nav-btn:hover { background: #666; }
        .container { height: calc(100% - 50px); width: 100%; }
        iframe { width: 100%; height: 100%; border: none; }
    </style>
</head>
<body>

    <div class="navbar">
        <button class="nav-btn" onclick="switchServer('https://cloudmoonapp.com')">Server 1 (CloudMoon)</button>
        <button class="nav-btn" onclick="switchServer('https://easyfun.gg')">Server 2 (EasyFun)</button>
        <button class="nav-btn" onclick="switchServer('https://croxyproxy.com')">Server 3 (Proxy Backup)</button>
    </div>

    <div class="container">
        <iframe id="game-frame" src="https://cloudmoonapp.com"></iframe>
    </div>

    <script>
        function switchServer(url) {
            document.getElementById('game-frame').src = url;
        }
    </script>

</body>
</html>
