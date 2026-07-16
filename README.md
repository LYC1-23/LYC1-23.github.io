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
            padding: 50px 55px;
        }
        /* 头部 */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            border-bottom: 3px solid #1a3a5c;
            padding-bottom: 20px;
            margin-bottom: 25px;
        }
        .name-title h1 {
            font-size: 34px;
            font-weight: 700;
            color: #1a2a3a;
            letter-spacing: 2px;
        }
        .name-title .sub {
            font-size: 16px;
            color: #2d7aff;
            font-weight: 500;
            margin-top: 4px;
        }
        .contact-info {
            text-align: right;
            font-size: 14px;
            color: #2d3a4a;
            line-height: 1.8;
        }
        .contact-info a {
            color: #1a3a5c;
            text-decoration: none;
        }
        .contact-info a:hover {
            color: #2d7aff;
            text-decoration: underline;
        }
        /* 通用 */
        .section {
            margin-top: 22px;
        }
        .section h2 {
            font-size: 18px;
            font-weight: 700;
            color: #1a3a5c;
            border-left: 4px solid #2d7aff;
            padding-left: 12px;
            margin-bottom: 12px;
        }
        .section p, .section li {
            color: #2d3a4a;
            line-height: 1.8;
            font-size: 14.5px;
        }
        .section ul {
            list-style: none;
            padding-left: 0;
        }
        .section ul li {
            padding: 3px 0 3px 20px;
            position: relative;
        }
        .section ul li::before {
            content: "•";
            color: #2d7aff;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        /* 教育经历 */
        .edu-item, .exp-item, .project-item {
            margin-bottom: 16px;
        }
        .edu-item .head, .exp-item .head, .project-item .head {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            font-weight: 600;
            color: #1a2a3a;
            font-size: 15px;
        }
        .edu-item .head .school, .exp-item .head .company, .project-item .head .proj {
            color: #1a3a5c;
        }
        .edu-item .head .date, .exp-item .head .date, .project-item .head .date {
            color: #6b7a8a;
            font-weight: 400;
            font-size: 14px;
        }
        .edu-item .detail, .exp-item .detail, .project-item .detail {
            padding-left: 0;
            margin-top: 4px;
        }
        .edu-item .detail ul, .exp-item .detail ul, .project-item .detail ul {
            padding-left: 0;
        }
        .exp-item .detail ul li, .project-item .detail ul li {
            padding: 2px 0 2px 20px;
            font-size: 14px;
        }
        .exp-item .sub-info {
            font-size: 14px;
            color: #3d4a5a;
            margin-top: 2px;
        }
        .project-item .sub-info {
            font-size: 14px;
            color: #3d4a5a;
            margin-top: 2px;
        }
        /* 技能标签 */
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 12px 30px;
            margin-top: 6px;
        }
        .skills-grid .skill-item {
            font-size: 14.5px;
            color: #2d3a4a;
        }
        .skills-grid .skill-item strong {
            color: #1a3a5c;
            font-weight: 600;
        }
        /* 个人总结 */
        .summary p {
            font-size: 14.5px;
            line-height: 1.9;
            color: #2d3a4a;
        }
        /* 底部 */
        .footer {
            margin-top: 30px;
            padding-top: 18px;
            border-top: 1px solid #e8ecf2;
            text-align: center;
            font-size: 13px;
            color: #8a94a6;
        }
        @media (max-width: 650px) {
            .container { padding: 30px 20px; }
            .header { flex-direction: column; }
            .contact-info { text-align: left; margin-top: 10px; }
            .edu-item .head, .exp-item .head, .project-item .head {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
<div class="container">

    <!-- 头部信息 -->
    <div class="header">
        <div class="name-title">
            <h1>刘庾辰</h1>
            <div class="sub">材料工程 · 纳米技术方向</div>
        </div>
        <div class="contact-info">
            📞 130-8152-4628<br>
            📧 <a href="mailto:113081524628@163.com">l13081524628@163.com</a><br>
            🐙 <a href="https://github.com/LYC1-23" target="_blank">github.com/LYC1-23</a>
        </div>
    </div>

    <!-- 教育经历 -->
    <div class="section">
        <h2>教育经历</h2>
        <div class="edu-item">
            <div class="head">
                <span class="school">香港城市大学（东莞） · 材料工程及纳米技术 硕士</span>
                <span class="date">2025.09 – 2027.06</span>
            </div>
            <div class="detail">
                <ul>
                    <li>主修课程：材料表征仪器、材料的结构和变形、半导体的量子理论、材料科学的计算方法、能源应用纳米材料设计、薄膜技术和纳米晶涂层、材料热力学</li>
                </ul>
            </div>
        </div>
        <div class="edu-item">
            <div class="head">
                <span class="school">燕山大学 · 高分子材料与工程 本科</span>
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

    <!-- 实习工作经历 -->
    <div class="section">
        <h2>实习工作经历</h2>
        <div class="exp-item">
            <div class="head">
                <span class="company">心赛科技研发部 · 研发工程师</span>
                <span class="date">2026.06 – 至今</span>
            </div>
            <div class="detail">
                <ul>
                    <li>担任研发部实习工程师，熟悉ISO13485、GB42061及其他相关国家和行业标准</li>
                    <li>辅助项目组开展一次性心脏内超声成像导管中导管性能的优化，具有三类心脏介入导管的工作经验，熟悉项目策划、输入、输出、评审、验证、确认及转换全流程</li>
                </ul>
            </div>
        </div>
        <div class="exp-item">
            <div class="head">
                <span class="company">日泰管业 · 轮值实习生</span>
                <span class="date">2024.06 – 2024.07</span>
            </div>
            <div class="detail">
                <ul>
                    <li>在质检、生产、包装和仓储车间进行轮岗</li>
                    <li>对管材生产全过程初步掌握，熟悉行业相关标准</li>
                </ul>
            </div>
        </div>
        <div class="exp-item">
            <div class="head">
                <span class="company">亚稳材料全国重点实验室 · 科研助理</span>
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

    <!-- 项目经历 -->
    <div class="section">
        <h2>项目经历</h2>
        <div class="project-item">
            <div class="head">
                <span class="proj">《基于PVA/NaCl/甘油离子凝胶电解质的有机电化学晶体管》</span>
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
        <div class="project-item">
            <div class="head">
                <span class="proj">《高拉伸性硅钨酸增强的纳米复合水凝胶的制备及其性能研究》</span>
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
        <div class="project-item">
            <div class="head">
                <span class="proj">《基于多孔PDMS摩擦纳米发电机的设计与应用》</span>
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

    <!-- 专业技能 -->
    <div class="section">
        <h2>专业技能</h2>
        <div class="skills-grid">
            <span class="skill-item"><strong>英语水平：</strong>大学英语六级（CET-6），较好的听说读写能力</span>
            <span class="skill-item"><strong>计算机：</strong>熟练运用科研分析软件与办公软件</span>
            <span class="skill-item"><strong>奖学金：</strong>大一至大四全年校级奖学金</span>
        </div>
    </div>

    <!-- 个人总结 -->
    <div class="section summary">
        <h2>个人总结</h2>
        <p>本科及研究生阶段成绩位于前列，较为全面且扎实掌握专业相关知识，对于材料学科具有热情和终身学习的动力。掌握实验室基本技能，可通过短期学习快速掌握新技能。团结同事、乐于助人、有耐心，具有较好的人际交往能力；性格沉稳，执行力强，能进行有效沟通。</p>
    </div>

    <div class="footer">
        更新于 2026年7月 · 在线简历
    </div>

</div>
</body>
</html>
