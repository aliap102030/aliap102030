<!DOCTYPE html>
<html dir="rtl" lang="fa">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>علی عبدالله‌پور | توسعه‌دهنده فرانت‌اند</title>

  <!-- فونت وزیر از CDN -->
  <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v33.003/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Vazirmatn', sans-serif;
      background: #0D1117;
      color: #e6edf3;
      line-height: 1.8;
      padding: 40px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    h1, h2, h3 {
      font-weight: 700;
    }

    a {
      color: #58a6ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    .header {
      text-align: center;
      padding: 30px 0 20px;
      border-bottom: 1px solid #30363d;
      margin-bottom: 30px;
    }
    .header h1 {
      font-size: 2.8rem;
      background: linear-gradient(135deg, #58a6ff, #f0883e);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    .header p {
      color: #8b949e;
      font-size: 1.2rem;
      margin-top: 8px;
    }

    .section {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 25px 30px;
      margin-bottom: 25px;
      transition: all 0.3s ease;
    }
    .section:hover {
      border-color: #58a6ff;
    }
    .section h2 {
      color: #f0f6fc;
      font-size: 1.5rem;
      margin-bottom: 15px;
      border-right: 4px solid #58a6ff;
      padding-right: 15px;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      margin: 15px 0;
    }
    .badges img {
      height: 42px;
      border-radius: 6px;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 12px;
      margin-top: 10px;
    }
    .skills-grid li {
      list-style: none;
      background: #0D1117;
      padding: 12px 18px;
      border-radius: 8px;
      border: 1px solid #30363d;
      color: #c9d1d9;
      font-size: 0.95rem;
    }
    .skills-grid li:hover {
      border-color: #58a6ff;
      background: #161b22;
    }

    .project {
      background: #0D1117;
      padding: 20px 25px;
      border-radius: 10px;
      border: 1px solid #30363d;
      margin-bottom: 15px;
      transition: all 0.3s ease;
    }
    .project:hover {
      border-color: #58a6ff;
      transform: translateX(-5px);
    }
    .project h3 {
      color: #58a6ff;
      margin-bottom: 5px;
    }
    .project p {
      color: #8b949e;
      font-size: 0.95rem;
    }
    .project .tech {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 10px;
    }
    .project .tech span {
      background: #21262d;
      color: #c9d1d9;
      padding: 4px 14px;
      border-radius: 20px;
      font-size: 0.85rem;
      border: 1px solid #30363d;
    }
    .project .tech span:hover {
      background: #30363d;
      border-color: #58a6ff;
    }

    .stats {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .stats img {
      border-radius: 10px;
      max-width: 100%;
    }

    .social {
      display: flex;
      gap: 15px;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 10px;
    }
    .social a {
      display: inline-block;
      transition: transform 0.2s ease;
    }
    .social a:hover {
      transform: scale(1.05);
    }
    .social img {
      height: 45px;
    }

    .footer {
      text-align: center;
      padding-top: 30px;
      border-top: 1px solid #30363d;
      margin-top: 30px;
      color: #8b949e;
    }
    .footer .heart {
      color: #f0883e;
    }

    @media (max-width: 600px) {
      body {
        padding: 20px 15px;
      }
      .section {
        padding: 20px;
      }
      .header h1 {
        font-size: 2rem;
      }
      .skills-grid {
        grid-template-columns: 1fr;
      }
      .badges img {
        height: 35px;
      }
    }
  </style>
</head>
<body>

  <div class="header">
    <h1>علی عبدالله‌پور</h1>
    <p>توسعه‌دهنده فرانت‌اند | عاشق کد تمیز و تجربه کاربری عالی</p>
  </div>

  <div class="section">
    <h2>🛠️ تکنولوژی‌ها</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
      <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
    </div>
  </div>

  <div class="section">
    <h2>✨ مهارت‌های کلیدی</h2>
    <ul class="skills-grid">
      <li>✅ طراحی واکنش‌گرا با Tailwind</li>
      <li>✅ توسعه کامپوننت در React</li>
      <li>✅ مدیریت State (Redux - Context)</li>
      <li>✅ بهینه‌سازی عملکرد و Core Web Vitals</li>
      <li>✅ کار با Git و GitHub</li>
      <li>✅ آشنایی با Next.js</li>
    </ul>
  </div>

  <div class="section">
    <h2>📂 پروژه‌های شاخص</h2>

    <div class="project">
      <h3>🛒 فروشگاه اینترنتی</h3>
      <p>فروشگاه کامل با سیستم سبد خرید، پرداخت و پروفایل کاربری</p>
      <div class="tech">
        <span>React</span>
        <span>Next.js</span>
        <span>Tailwind</span>
        <span>Redux</span>
      </div>
    </div>

    <div class="project">
      <h3>📊 داشبورد مدیریت</h3>
      <p>داشبورد تحلیلی با نمودارهای تعاملی و فیلترهای پیشرفته</p>
      <div class="tech">
        <span>React</span>
        <span>Tailwind</span>
        <span>Recharts</span>
      </div>
    </div>

    <div class="project">
      <h3>🌐 وب‌سایت شخصی</h3>
      <p>نمونه کار با انیمیشن‌های جذاب و طراحی مدرن</p>
      <div class="tech">
        <span>Next.js</span>
        <span>Tailwind</span>
        <span>Framer Motion</span>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>📊 آمار گیت‌هاب</h2>
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api?username=aliii-ab&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117" alt="GitHub Stats" width="48%" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=aliii-ab&theme=dark&hide_border=true&background=0D1117" alt="GitHub Streak" width="48%" />
    </div>
    <br />
    <div style="text-align: center;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aliii-ab&layout=compact&theme=dark&hide_border=true&bg_color=0D1117" alt="Top Languages" width="40%" />
    </div>
  </div>

  <div class="section">
    <h2>📬 راه‌های ارتباطی</h2>
    <div class="social">
      <a href="https://linkedin.com/in/yourusername" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <a href="https://github.com/aliii-ab" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
      </a>
      <a href="mailto:youremail@gmail.com">
        <img src="https://img.shields.io/badge/ایمیل-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
      </a>
      <a href="https://t.me/yourusername" target="_blank">
        <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
      </a>
    </div>
  </div>

  <div class="footer">
    <p>
      <span class="heart">❤️</span> ساخته شده با عشق 
      <span class="heart">❤️</span>
    </p>
    <p style="font-size: 0.9rem; margin-top: 5px;">
      ⭐️ اگر از پروژه‌های من خوشت اومد، حتماً ستاره‌اش کن!
    </p>
    <p style="font-size: 0.8rem; margin-top: 8px; color: #606770;">
      علی عبدالله‌پور | ۲۰۲۶
    </p>
  </div>

</body>
</html>
