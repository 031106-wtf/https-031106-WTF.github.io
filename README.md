<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>关于我 - 个人介绍</title>
    <style>
        /* 全局样式：简洁统一 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Inter", "Arial", sans-serif;
        }
        body {
            background-color: #fafafa;
            color: #333;
            line-height: 1.6;
        }

        /* 头部区域：突出个人形象 */
        .header {
            background: linear-gradient(135deg, #4267b2, #3498db);
            color: white;
            text-align: center;
            padding: 4rem 2rem;
        }
        .avatar {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            border: 4px solid white;
            margin-bottom: 1.5rem;
            object-fit: cover; /* 保持图片比例 */
        }
        .header h1 {
            font-size: 2.2rem;
            margin-bottom: 0.5rem;
        }
        .header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        /* 主体内容：分块展示信息 */
        .container {
            max-width: 800px;
            margin: 3rem auto;
            padding: 0 2rem;
        }
        .section {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .section h2 {
            color: #4267b2;
            font-size: 1.5rem;
            margin-bottom: 1.2rem;
            border-left: 4px solid #4267b2;
            padding-left: 0.8rem;
        }
        .info-list {
            list-style: none;
        }
        .info-list li {
            margin-bottom: 1rem;
            font-size: 1rem;
        }
        .info-list li span {
            font-weight: 600;
            color: #4267b2;
        }

        /* 底部区域：简洁版权 */
        .footer {
            text-align: center;
            padding: 2rem;
            color: #666;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <!-- 头部： 姓名 + 身份 -->
    <div class="header">
                <h1>（王霆锋）</h1>
        <p>（智能制造专业学生 ）</p >
    </div>

    <!-- 主体：核心信息 -->
    <div class="container">
        <!-- 个人简介 -->
        <div class="section">
            <h2>个人简介</h2>
            <p>（热爱机电的智能制造专业学生，喜欢通过实践探索Web开发，平时喜欢运动和阅读，擅长快速学习新技能，希望未来能在前端领域持续成长。）</p >
        </div>

        <!-- 基本信息 -->
        <div class="section">
            <h2>基本信息</h2>
            <ul class="info-list">
                <li><span>生日：</span>（2003年11月）</li>
                <li><span>学历：</span>（华侨大学 智能制造工程专业 本科在读）</li>
                <li><span>邮箱：</span>（407623711@qq.com）</li>
                <li><span>所在地：</span>（福建省厦门市）</li>
                <li><span>兴趣：</span>（Web开发、摄影、跑步、看书）</li>
            </ul>
        </div>

        <!-- 技能/优势 -->
        <div class="section">
            <h2>技能与优势</h2>
            <ul class="info-list">
                <li><span>技术能力：</span>（掌握HTML5语义化标签、CSS Flex/Grid布局，了解JavaScript基础语法，会使用Figma简单设计）</li>
                <li><span>软技能：</span>（注重细节、团队沟通能力强、遇到问题会主动查资料解决、时间管理有条理）</li>
                <li><span>其他：</span>（英语CET-4）</li>
            </ul>
        </div>
    </div>

    <!-- 底部：版权信息 -->
    <div class="footer">
        <p>© 2025 （王霆锋）的个人介绍页 | 设计与开发：自己</p >
    </div>
</body>
</html>
