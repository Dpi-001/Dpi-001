<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: black;
      overflow: hidden;
    }

    .falling-pattern {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: column;
      font-family: monospace;
      color: lime;
      font-size: 24px;
      white-space: nowrap;
      pointer-events: none;
    }

    .line {
      position: absolute;
      width: 100%;
      display: flex;
      justify-content: center;
      animation: fall 6s infinite linear;
    }

    .line:nth-child(1) {
      animation-delay: 0s;
    }

    .line:nth-child(2) {
      animation-delay: 1s;
    }

    .line:nth-child(3) {
      animation-delay: 2s;
    }

    .line:nth-child(4) {
      animation-delay: 3s;
    }

    .line:nth-child(5) {
      animation-delay: 4s;
    }

    .line:nth-child(6) {
      animation-delay: 5s;
    }

    @keyframes fall {
      0% {
        top: -100px;
      }
      100% {
        top: 100%;
      }
    }

    @keyframes drop {
      0% {
        opacity: 1;
      }
      50% {
        opacity: 0.5;
      }
      100% {
        opacity: 1;
      }
    }

    .line span {
      display: inline-block;
      animation: drop 3s linear infinite;
    }

    h1, h3 {
      color: white;
      text-align: center;
    }
  </style>
</head>
<body>
  <!-- Falling Binary Animation -->
  <div class="falling-pattern">
    <div class="line">
      <span>1 0 1 0 1 1 0 1 1 1</span>
      <span>1 1 0 1 0 1 1 1 0 1</span>
      <span>1 0 0 1 1 0 1 1 0 1</span>
    </div>
    <div class="line">
      <span>0 1 1 1 1 0 1 1 1 0</span>
      <span>1 0 0 1 0 1 0 1 1 0</span>
      <span>1 1 0 1 1 1 0 1 0 1</span>
    </div>
  </div>

  <!-- Profile Introduction -->
  <h1>Hi 👋, I'm Sudeep Lamichhane</h1>
  <h3>⚡ Cyberpunk Coder | Full-Stack Sorcerer | Debugging Ninja</h3>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=dpi-001&label=Profile%20views&color=green&style=flat" alt="dpi-001" />
  </p>

  <hr>

  <h3>🛠 **Tech Arsenal:**</h3>
  <pre>
  🔥 Programming: Laravel, JavaScript, Vue, React
  🛠 Frameworks: TailwindCSS, Node.js
  🖥 DevOps: Linux, Git
  </pre>

  <h3>🚀 **Currently Exploring:**</h3>
  <ul>
    <li>**Building the Future of E-Commerce:** `BarterLink` 🏪</li>
    <li>**Mastering the Art of Laravel & Vue.js** 🔥</li>
    <li>**Diving Deep into Secure Web Apps** 🔐</li>
  </ul>

  <h3>🤝 **Looking to Collaborate On:**</h3>
  <pre>
  🛒 Scalable E-Commerce Solutions
  📈 Data-Driven Web Applications
  🎨 Creative UI/UX Projects
  </pre>

  <h3>💬 **Ask Me About:**</h3>
  <pre>
  ⚡ JavaScript Tricks
  🚀 Performance Optimization
  </pre>

  <h3>📫 **How to Reach Me:**</h3>
  <pre>
  📩 Email: lsud_bca2079@lict.edu.np
  🌐 Portfolio: [Your Portfolio Link Here]
  📝 Blog: [Your Blog Link Here]
  </pre>

  <h3>⚡ **Fun Fact:**</h3>
  <pre>
  😆 I commit more to GitHub than I do to my New Year’s resolutions!
  🔧 My debugging process: 50% coding | 50% Googling errors.
  </pre>

  <hr>

  <!-- GitHub Stats -->
  <h3 align="center">📊 **GitHub Stats**</h3>
  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=dpi-001&theme=gruvbox&hide_border=true" alt="GitHub Streak" />
  </p>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=dpi-001&show_icons=true&theme=gruvbox&hide_border=true" alt="GitHub Stats" />
  </p>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dpi-001&show_icons=true&theme=gruvbox&layout=compact&hide_border=true" alt="Top Languages" />
  </p>

  <hr>

  <h3 align="center">🖥 **Tools & Tech Stack:**</h3>
  <p align="center">
    <img src="https://skillicons.dev/icons?i=html,css,js,laravel,vue,react,nodejs,tailwind,git,github,php,mysql,linux" />
  </p>

  <h3 align="center">🏆 **Achievements & Contributions:**</h3>
  <p align="center">
    <a href="https://github.com/ryo-ma/github-profile-trophy">
      <img src="https://github-profile-trophy.vercel.app/?username=dpi-001&theme=darkhub" alt="Trophies" />
    </a>
  </p>

  <hr>

  <h3 align="center">🔥 **Keep the Hustle Alive!**</h3>
  <pre align="center">
    "Code, Debug, Repeat. Sleep is for the weak."
  </pre>
</body>
</html>
