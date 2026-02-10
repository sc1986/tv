<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>正在加载...</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }
        .container {
            text-align: center;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
        }
        h1 {
            margin-bottom: 20px;
            font-size: 24px;
        }
        .loading {
            width: 50px;
            height: 50px;
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-top-color: white;
            border-radius: 50%;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        .manual-link {
            margin-top: 20px;
            padding: 10px 20px;
            background: white;
            color: #764ba2;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            transition: transform 0.2s;
        }
        .manual-link:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>正在跳转到目标页面...</h1>
        <div class="loading"></div>
        <br><br>
        <a href="https://bc.188766.xyz/?url=https://live.iill.top" class="manual-link">如果没有自动跳转，请点击这里</a>
    </div>

    <script>
        // 立即跳转
        window.location.href = 'https://bc.188766.xyz/?url=https://live.iill.top';
    </script>
</body>
</html>
