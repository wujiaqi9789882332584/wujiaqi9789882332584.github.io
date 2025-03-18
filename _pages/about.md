<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人简介 - 吴佳琦</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        /* 导航栏样式 */
        nav {
            background: #2c3e50;
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
        }

        .nav-links {
            display: flex;
            justify-content: center;
            list-style: none;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin: 0 2rem;
            padding: 0.5rem;
        }

        /* 内容区块 */
        section {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* 个人信息头部 */
        .profile-header {
            display: flex;
            align-items: center;
            margin-top: 4rem;
        }
        
        .profile-photo {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-right: 3rem;
            border: 3px solid #2c3e50;
        }

        /* 基本信息样式 */
        .basic-info p {
            margin: 0.5rem 0;
            font-size: 1.1rem;
        }

        /* 时间轴样式（用于生平） */
        .timeline {
            border-left: 3px solid #2c3e50;
            padding-left: 2rem;
            margin: 2rem 0;
        }

        .timeline-item {
            margin: 1.5rem 0;
            position: relative;
        }

        .timeline-item::before {
            content: "";
            position: absolute;
            left: -2.65rem;
            top: 0.3rem;
            width: 15px;
            height: 15px;
            background: #e74c3c;
            border-radius: 50%;
        }

        /* 联系方式样式 */
        .contact-info {
            background: #f8f9fa;
            padding: 2rem;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav>
        <ul class="nav-links">
            <li><a href="#profile">基本信息</a></li>
            <li><a href="#biography">个人生平</a></li>
            <li><a href="#skills">个人能力</a></li>
            <li><a href="#honors">个人荣誉</a></li>
            <li><a href="#contact">联系方式</a></li>
        </ul>
    </nav>

    <!-- 基本信息 -->
    <section id="profile">
        <div class="profile-header">
            <img src="wujiaqi.jpg" alt="吴佳琦" class="profile-photo">
            <div class="basic-info">
                <h1>吴佳琦</h1>
                <p>出生日期：2006年2月17日</p>
                <p>所属大学：华中科技大学 船舶与海洋工程系 轮机工程专业</p>
            </div>
        </div>
    </section>

    <!-- 个人生平 -->
    <section id="biography">
        <h2>个人生平</h2>
        <div class="timeline">
            <div class="timeline-item">
                <h3>2021-2024</h3>
                <p>于武汉市第三中学学习</p>
            </div>
            <div class="timeline-item">
                <h3>2024-至今</h3>
                <p>于华中科技大学学习本科课程</p>
    </section>

    <!-- 个人能力 -->
    <section id="skills">
        <h2>个人能力</h2>
        <ul>
            <li>熟悉c++编程语言</li>
            <li>具有良好的数学素养</li>
            <li>具有优秀的学习能力</li>
        </ul>
    </section>

    <!-- 个人荣誉 -->
    <section id="honors">
        <h2>个人荣誉</h2>
        <ul>
            <li>2013年 优秀团员</li>
            <li>2024年 优秀毕业生称号</li>
        </ul>
    </section>

    <!-- 联系方式 -->
    <section id="contact">
        <h2>联系方式</h2>
        <div class="contact-info">
            <p>电话：+86 15102751301</p>
            <p>邮箱：15102752301@163.com</p>
        </div>
    </section>

</body>
</html>
