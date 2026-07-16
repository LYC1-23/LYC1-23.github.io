<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>刘庚辰 - 个人简历</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', 'PingFang SC', Roboto, sans-serif;
            background: #f4f7fa;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 30px;
        }
        .card {
            background: white;
            max-width: 700px;
            width: 100%;
            padding: 45px 50px;
            border-radius: 24px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.08);
            transition: all 0.2s;
        }
        h1 {
            font-size: 32px;
            font-weight: 700;
            color: #1a1a2e;
            margin-bottom: 6px;
        }
        .subhead {
            font-size: 18px;
            color: #555;
            margin-bottom: 20px;
            border-bottom: 2px solid #eef2f7;
            padding-bottom: 18px;
        }
        .section {
            margin-top: 22px;
        }
        .section h2 {
            font-size: 18px;
            font-weight: 600;
            color: #16213e;
            letter-spacing: 0.3px;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        .section h2::before {
            content: "◆";
            color: #2d7aff;
            font-size: 14px;
        }
        .section p, .section li {
            color: #2d3a4a;
            line-height: 1.7;
            font-size: 15.5px;
        }
        .section ul {
            list-style: none;
            padding-left: 4px;
        }
        .section ul li {
            padding: 4px 0;
        }
        .section ul li::before {
            content: "•";
            color: #2d7aff;
            font-weight: bold;
            margin-right: 10px;
        }
        .contact-links {
            display: flex;
            flex-wrap: wrap;
            gap: 16px 28px;
            margin-top: 6px;
        }
        .contact-links a {
            color: #1a1a2e;
            text-decoration: none;
            font-size: 15px;
            border-bottom: 1.5px solid transparent;
            transition: 0.2s;
        }
        .contact-links a:hover {
            border-bottom-color: #2d7aff;
            color: #2d7aff;
        }
        .footer-note {
            margin-top: 28px;
            font-size: 14px;
            color: #8a94a6;
            border-top: 1px solid #eef2f7;
            padding-top: 18px;
            text-align: center;
        }
        @media (max-width: 500px) {
            .card { padding: 30px 20px; }
            h1 { font-size: 26px; }
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>刘庾辰</h1>
        <div class="subhead">GitHub 个人主页 · 正在学习前端开发</div>

        <div class="section">
            <h2>关于我</h2>
            <p>你好！我是刘庾辰，目前正在探索 Web 开发的世界。这个页面是我用 HTML + CSS 在 GitHub Pages 上搭建的个人简历站点，未来会持续更新我的学习成果和项目作品。</p>
        </div>

        <div class="section">
            <h2>技术方向</h2>
            <ul>
                <li>HTML / CSS（正在巩固）</li>
                <li>JavaScript（学习入门中）</li>
                <li>Git & GitHub（日常协作工具）</li>
            </ul>
        </div>

        <div class="section">
            <h2>联系方式</h2>
            <div class="contact-links">
                <a href="mailto:liugengchen@example.com">📧 liugengchen@example.com</a>
                <a href="https://github.com/LYC1-23" target="_blank">🐙 GitHub</a>
            </div>
        </div>

        <div class="footer-note">
            🌱 持续学习 · 保持好奇
        </div>
    </div>
</body>
</html>
