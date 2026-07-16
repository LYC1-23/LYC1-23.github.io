<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>刘庾辰 - 个人简历</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', 'PingFang SC', Roboto, 'Helvetica Neue', sans-serif;
            background: #eef2f7;
            display: flex;
            justify-content: center;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.08);
            padding: 40px 50px;
        }

        /* ===== 顶部：头像 + 姓名 ===== */
        .header {
            display: flex;
            align-items: center;
            gap: 20px;
            padding-bottom: 18px;
            border-bottom: 3px solid #1a3a5c;
            margin-bottom: 20px;
            flex-wrap: wrap;
        }
        .avatar {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #1a3a5c;
            background: #eef2f7;
            flex-shrink: 0;
        }
        .name-title h1 {
            font-size: 28px;
            font-weight: 700;
            color: #1a2a3a;
        }
        .name-title .sub {
            font-size: 15px;
            color: #2d7aff;
            font-weight: 500;
        }
        .contact-short {
            margin-left: auto;
            font-size: 13px;
            color: #6b7a8a;
            text-align: right;
        }
        .contact-short a {
            color: #1a3a5c;
            text-decoration: none;
        }
        .contact-short a:hover {
            color: #2d7aff;
        }

        /* ===== 导航菜单 ===== */
        .nav {
            display: flex;
            gap: 8px;
            margin-bottom: 25px;
            flex-wrap: wrap;
            border-bottom: 2px solid #e8ecf2;
            padding-bottom: 12px;
        }
        .nav button {
            padding: 10px 28px;
            font-size: 15px;
            font-weight: 600;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            background: transparent;
            color: #6b7a8a;
            transition: all 0.25s;
            font-family: inherit;
        }
        .nav button:hover {
            background: #f0f4fb;
            color: #1a3a5c;
        }
        .nav button.active {
            background: #1a3a5c;
            color: white;
            box-shadow: 0 4px 12px rgba(26, 58, 92, 0.25);
        }

        /* ===== 内容区域 ===== */
        .content {
            min-height: 320px;
        }
        .page {
            display: none;
            animation: fadeIn 0.35s ease;
        }
        .page.active {
            display: block;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(12px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .page h2 {
            font-size: 20px;
            color: #1a3a5c;
            border-left: 4px solid #2d7aff;
            padding-left: 14px;
            margin-bottom: 16px;
        }

        /* 通用卡片样式 */
        .card-item {
            margin-bottom: 18px;
        }
        .card-item .head {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            font-weight: 600;
            color: #1a2a3a;
            font-size: 15px;
        }
        .card-item .head .title {
            color: #1a3a5c;
        }
        .card-item .head .date {
            color: #6b7a8a;
            font-weight: 400;
            font-size: 14px;
        }
        .card-item .detail {
            padding-left: 6px;
            margin-top: 4px;
        }
        .card-item .detail ul {
            list-style: none;
            padding-left: 0;
        }
        .card-item .detail ul li {
            padding: 3px 0 3px 20px;
            position: relative;
            font-size: 14.5px;
            color: #2d3a4a;
            line-height: 1.7;
        }
        .card-item .detail ul li::before {
            content: "•";
            color: #2d7aff;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        .card-item .sub-info {
            font-size: 14px;
            color: #3d4a5a;
            margin-top: 2px;
        }

        /* 兴趣爱好 - 标签样式 */
        .hobby-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 14px 24px;
            margin-top: 12px;
        }
        .hobby-tags .tag {
            background: #f0f4fb;
            padding: 8px 20px;
            border-radius: 30px;
            font-size: 15px;
            color: #1a3a5c;
            font-weight: 500;
        }
        .hobby-tags .tag span {
            margin-right: 6px;
        }

        /* 页脚 */
        .footer {
            margin-top: 30px;
            padding-top: 16px;
            border-top: 1px solid #e8ecf2;
            text-align: center;
            font-size: 13px;
            color: #8a94a6;
        }

        @media (max-width: 650px) {
            .container { padding: 25px 18px; }
            .header { flex-wrap: wrap; }
            .contact-short { text-align: left; margin-left: 0; width: 100%; }
            .nav button { padding: 8px 16px; font-size: 14px; flex: 1; min-width: 70px; text-align: center; }
            .avatar { width: 60px; height: 60px; }
        }
    </style>
</head>
<body>
<div class="container">

    <!-- ===== 顶部：头像 + 姓名 + 联系方式 ===== -->
    <div class="header">
        <img src="9329f7a4fde4311f83d3a02b21bce687.jpg" alt="刘庾辰" class="avatar" onerror="this.style.display='none'">
        <div class="name-title">
            <h1>刘庾辰</h1>
            <div class="sub">材料工程 · 纳米技术方向</div>
        </div>
        <div class="contact-short">
            📞 130-8152-4628<br>
            📧 <a href="mailto:113081524628@163.com">113081524628@163.com</a>
        </div>
    </div>

    <!-- ===== 导航菜单（4个选项） ===== -->
    <div class="nav">
        <button class="active" data-page="study">📖 学习经历</button>
        <button data-page="work">💼 工作经历</button>
        <button data-page="research">🔬 科研经历</button>
        <button data-page="hobby">🎯 兴趣爱好</button>
    </div>

    <!-- ===== 内容区域 ===== -->
    <div class="content">

        <!-- 页面1：学习经历 -->
        <div class="page active" id="study">
            <h2>学习经历</h2>
            <div class="card-item">
                <div class="head">
                    <span class="title">香港城市大学 · 材料工程及纳米技术 硕士</span>
                    <span class="date">2025.09 – 2027.06</span>
                </div>
                <div class="detail">
                    <ul>
                        <li>主修课程：材料表征仪器、材料的结构和变形、半导体的量子理论、材料科学的计算方法、能源应用纳米材料设计、薄膜技术和纳米晶涂层、材料热力学</li>
                    </ul>
                </div>
            </div>
            <div class="card-item">
                <div class="head">
                    <span class="title">燕山大学 · 高分子材料与工程 本科</span>
                    <span class="date">2021.09 – 2025.06</span>
                </div>
                <div class="detail">
                    <ul>
                        <li>主修课程：高分子化学、高分子物理、材料科学基础、高聚物合成工艺学、聚合物流变学、专业外语、功能高分子（双语）</li>
                        <li>辅修课程（微专业）：绿色化学工程、柔性可穿戴设备、储氢材料、清洁能源制备技术</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 页面2：工作经历 -->
        <div class="page" id="work">
            <h2>工作经历</h2>
            <div class="card-item">
                <div class="head">
                    <span class="title">心赛科技研发部 · 研发工程师</span>
                    <span class="date">2026.06 – 至今</span>
                </div>
                <div class="detail">
                    <ul>
                        <li>担任研发部实习工程师，熟悉ISO13485、GB42061及其他相关国家和行业标准</li>
                        <li>辅助项目组开展一次性心脏内超声成像导管中导管性能的优化，具有三类心脏介入导管的工作经验，熟悉项目策划、输入、输出、评审、验证、确认及转换全流程</li>
                    </ul>
                </div>
            </div>
            <div class="card-item">
                <div class="head">
                    <span class="title">日泰管业 · 轮值实习生</span>
                    <span class="date">2024.06 – 2024.07</span>
                </div>
                <div class="detail">
                    <ul>
                        <li>在质检、生产、包装和仓储车间进行轮岗</li>
                        <li>对管材生产全过程初步掌握，熟悉行业相关标准</li>
                    </ul>
                </div>
            </div>
            <div class="card-item">
                <div class="head">
                    <span class="title">亚稳材料全国重点实验室 · 科研助理</span>
                    <span class="date">2023.12 – 2024.06</span>
                </div>
                <div class="detail">
                    <ul>
                        <li>负责实验操作、新材料制备工艺研发和实验室保障工作</li>
                        <li>创新性探索出PVA凝胶的制备新工艺，为后续深入研究奠定关键基础</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 页面3：科研经历 -->
        <div class="page" id="research">
            <h2>科研经历</h2>
            <div class="card-item">
                <div class="head">
                    <span class="title">基于PVA/NaCl/甘油离子凝胶电解质的有机电化学晶体管</span>
                    <span class="date">2024.12 – 2025.06</span>
                </div>
                <div class="sub-info"><strong>承担工作：</strong>毕设项目，独立完成实验操作、样品表征、数据处理、论文撰写及答辩全流程</div>
                <div class="detail">
                    <ul>
                        <li>创新性地利用凝胶电解质提升OETC的使用稳定性，为其在生物传感领域的应用奠定基础</li>
                        <li>对科研全过程进行了系统性训练</li>
                    </ul>
                </div>
            </div>
            <div class="card-item">
                <div class="head">
                    <span class="title">高拉伸性硅钨酸增强的纳米复合水凝胶的制备及其性能研究</span>
                    <span class="date">2023.12 – 2024.12</span>
                </div>
                <div class="sub-info"><strong>承担工作：</strong>团队负责人 · 校级大学生创新创业项目</div>
                <div class="detail">
                    <ul>
                        <li>负责项目整体组建，协调组员分工配合，推动项目进展</li>
                        <li>利用硅钨酸增强水凝胶传感器性能，扩大其在生物医疗传感领域的应用</li>
                    </ul>
                </div>
            </div>
            <div class="card-item">
                <div class="head">
                    <span class="title">基于多孔PDMS摩擦纳米发电机的设计与应用</span>
                    <span class="date">2023.03 – 2023.12</span>
                </div>
                <div class="sub-info"><strong>承担工作：</strong>团队核心成员 · 省级大学生创新创业项目</div>
                <div class="detail">
                    <ul>
                        <li>负责数据整理、归纳及分析工作</li>
                        <li>利用摩擦发电原理制备传感器，提升了可穿戴传感器的使用性能及应用场景</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 页面4：兴趣爱好 -->
        <div class="page" id="hobby">
            <h2>兴趣爱好</h2>
            <div class="hobby-tags">
                <span class="tag">📚 阅读</span>
                <span class="tag">🏃 跑步</span>
                <span class="tag">🎵 音乐</span>
                <span class="tag">📷 摄影</span>
                <span class="tag">♟️ 围棋</span>
                <span class="tag">🧪 科学实验</span>
                <span class="tag">✈️ 旅行</span>
            </div>
            <div style="margin-top: 20px; color: #2d3a4a; line-height: 1.8; font-size: 14.5px;">
                <p>业余时间喜欢阅读科技类书籍和人物传记，保持每周3次健身房运动的习惯。对新兴科技充满好奇，持续关注材料科学和清洁能源领域的最新进展。</p>
            </div>
        </div>

    </div>

    <div class="footer">
        更新于 2026年7月 · 在线简历
    </div>

</div>

<!-- ===== JavaScript：切换页面 ===== -->
<script>
    const buttons = document.querySelectorAll('.nav button');
    const pages = {
        study: document.getElementById('study'),
        work: document.getElementById('work'),
        research: document.getElementById('research'),
        hobby: document.getElementById('hobby')
    };

    buttons.forEach(btn => {
        btn.addEventListener('click', function() {
            buttons.forEach(b => b.classList.remove('active'));
            this.classList.add('active');
            Object.values(pages).forEach(p => p.classList.remove('active'));
            const pageId = this.dataset.page;
            if (pages[pageId]) {
                pages[pageId].classList.add('active');
            }
        });
    });
</script>

</body>
</html>
