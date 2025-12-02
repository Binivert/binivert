<!-- 
╔══════════════════════════════════════════════════════════════════════════════╗
║  CYBERPUNK GITHUB PROFILE README - Biniyam Bonger                            ║
║  Color Palette:                                                               ║
║    --bg: #061028 (deep navy)                                                  ║
║    --neon-cyan: #00E5FF                                                       ║
║    --blue: #0077FF                                                            ║
║    --accent: #9B59FF (sparingly)                                              ║
║    --glass: rgba(255,255,255,0.03)                                            ║
╚══════════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════════
     ANIMATED GLITCH NAME BANNER
     ═══════════════════════════════════════════════════════════════════════════ -->

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="glitch" x="-20%" y="-20%" width="140%" height="140%">
      <feTurbulence type="fractalNoise" baseFrequency="0.02" numOctaves="3" result="noise" seed="1">
        <animate attributeName="seed" values="1;10;1" dur="0.5s" repeatCount="indefinite"/>
      </feTurbulence>
      <feDisplacementMap in="SourceGraphic" in2="noise" scale="8" xChannelSelector="R" yChannelSelector="G">
        <animate attributeName="scale" values="0;8;0;5;0" dur="3s" repeatCount="indefinite"/>
      </feDisplacementMap>
    </filter>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="neonGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00E5FF">
        <animate attributeName="stop-color" values="#00E5FF;#0077FF;#9B59FF;#00E5FF" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#0077FF"/>
      <stop offset="100%" style="stop-color:#00E5FF">
        <animate attributeName="stop-color" values="#00E5FF;#9B59FF;#0077FF;#00E5FF" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="scanline" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:rgba(0,229,255,0)">
        <animate attributeName="offset" values="0;1;0" dur="2s" repeatCount="indefinite"/>
      </stop>
      <stop offset="5%" style="stop-color:rgba(0,229,255,0.3)">
        <animate attributeName="offset" values="0.05;1.05;0.05" dur="2s" repeatCount="indefinite"/>
      </stop>
      <stop offset="10%" style="stop-color:rgba(0,229,255,0)">
        <animate attributeName="offset" values="0.1;1.1;0.1" dur="2s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  
  <style>
    @keyframes flicker {
      0%, 100% { opacity: 1; }
      92% { opacity: 1; }
      93% { opacity: 0.8; }
      94% { opacity: 1; }
      96% { opacity: 0.9; }
      97% { opacity: 1; }
    }
    @keyframes rgbShift {
      0%, 100% { transform: translate(0, 0); }
      25% { transform: translate(-2px, 0); }
      50% { transform: translate(2px, 0); }
      75% { transform: translate(-1px, 1px); }
    }
    .main-text { 
      font-family: 'Courier New', monospace; 
      font-size: 56px; 
      font-weight: bold;
      fill: url(#neonGrad);
      filter: url(#glow);
      animation: flicker 5s infinite;
    }
    .glitch-r {
      font-family: 'Courier New', monospace;
      font-size: 56px;
      font-weight: bold;
      fill: #ff0040;
      opacity: 0.7;
      animation: rgbShift 0.3s infinite;
    }
    .glitch-b {
      font-family: 'Courier New', monospace;
      font-size: 56px;
      font-weight: bold;
      fill: #00E5FF;
      opacity: 0.7;
      animation: rgbShift 0.3s infinite reverse;
    }
    .subtitle {
      font-family: 'Courier New', monospace;
      font-size: 18px;
      fill: #9bdcff;
      opacity: 0.9;
    }
    .scanline-overlay {
      fill: url(#scanline);
      mix-blend-mode: overlay;
    }
  </style>
  
  <rect width="800" height="200" fill="#061028"/>
  
  <!-- Scanline effect -->
  <rect class="scanline-overlay" width="800" height="200"/>
  
  <!-- Glitch layers -->
  <text x="400" y="90" text-anchor="middle" class="glitch-r" filter="url(#glitch)">Biniyam Bonger</text>
  <text x="400" y="90" text-anchor="middle" class="glitch-b" filter="url(#glitch)">Biniyam Bonger</text>
  
  <!-- Main text -->
  <text x="400" y="90" text-anchor="middle" class="main-text">Biniyam Bonger</text>
  
  <!-- Subtitle -->
  <text x="400" y="130" text-anchor="middle" class="subtitle">AI • Computer Vision • Deep Learning Explorer</text>
  
  <!-- Decorative lines -->
  <line x1="150" y1="155" x2="300" y2="155" stroke="#00E5FF" stroke-width="1" opacity="0.5">
    <animate attributeName="x2" values="300;320;300" dur="2s" repeatCount="indefinite"/>
  </line>
  <line x1="500" y1="155" x2="650" y2="155" stroke="#00E5FF" stroke-width="1" opacity="0.5">
    <animate attributeName="x1" values="500;480;500" dur="2s" repeatCount="indefinite"/>
  </line>
</svg>

<!-- Fallback text for renderers that don't support SVG animation -->
<!--
# Biniyam Bonger
### AI • Computer Vision • Deep Learning Explorer
-->

<!-- Micro-badges -->
<br/>

![Open to Collaboration](https://img.shields.io/badge/Open%20to-Collaboration-00E5FF?style=for-the-badge&labelColor=061028)
![Computer Vision](https://img.shields.io/badge/Computer-Vision-9B59FF?style=for-the-badge&labelColor=061028)

<br/>

<!-- Hero blurb -->
<em>Building the machines that teach computers to see — realtime vision, models & systems.</em>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ANIMATED NEON DIVIDER
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="30" viewBox="0 0 1200 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="dividerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#061028"/>
      <stop offset="20%" style="stop-color:#00E5FF">
        <animate attributeName="offset" values="0.2;0.4;0.2" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#9B59FF"/>
      <stop offset="80%" style="stop-color:#00E5FF">
        <animate attributeName="offset" values="0.8;0.6;0.8" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#061028"/>
    </linearGradient>
    <filter id="dividerGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <path d="M0,15 Q300,5 600,15 T1200,15" stroke="url(#dividerGrad)" stroke-width="2" fill="none" filter="url(#dividerGlow)">
    <animate attributeName="d" 
             values="M0,15 Q300,5 600,15 T1200,15;M0,15 Q300,25 600,15 T1200,15;M0,15 Q300,5 600,15 T1200,15" 
             dur="4s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════════
     MAIN CONTENT GRID
     ═══════════════════════════════════════════════════════════════════════════ -->

<table width="100%">
<tr>
<td width="70%" valign="top">

<!-- LEFT COLUMN: Tech Stack & Projects -->

## <img src="https://img.shields.io/badge/▸-00E5FF?style=flat-square&labelColor=061028" height="20"/> Tech Stack

<!-- Glitch header decoration (inline) -->
<sup>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</sup>

<div align="center">

<!-- Programming Languages -->
<table>
<tr>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
<br><sub><b>Python</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript" />
<br><sub><b>JavaScript</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=cpp" width="48" height="48" alt="C++" />
<br><sub><b>C++</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js" />
<br><sub><b>Node.js</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=html" width="48" height="48" alt="HTML" />
<br><sub><b>HTML</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=css" width="48" height="48" alt="CSS" />
<br><sub><b>CSS</b></sub>
</td>
</tr>
</table>

<!-- Databases -->
<table>
<tr>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="MySQL" />
<br><sub><b>MySQL</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB" />
<br><sub><b>MongoDB</b></sub>
</td>
</tr>
</table>

<!-- Vision & ML -->
<table>
<tr>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=opencv" width="48" height="48" alt="OpenCV" />
<br><sub><b>OpenCV</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=pytorch" width="48" height="48" alt="PyTorch" />
<br><sub><b>PyTorch</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=tensorflow" width="48" height="48" alt="TensorFlow" />
<br><sub><b>TensorFlow</b></sub>
</td>
<td align="center" width="96">
<img src="https://img.shields.io/badge/MediaPipe-00E5FF?style=flat-square&logo=google&logoColor=white" height="48" alt="MediaPipe" />
<br><sub><b>MediaPipe</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=matlab" width="48" height="48" alt="MATLAB" />
<br><sub><b>MATLAB</b></sub>
</td>
<td align="center" width="96">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" height="48" alt="Pandas" />
<br><sub><b>Pandas</b></sub>
</td>
</tr>
</table>

<!-- Web & Tools -->
<table>
<tr>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" />
<br><sub><b>React</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
<br><sub><b>Git</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
<br><sub><b>Docker</b></sub>
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=githubactions" width="48" height="48" alt="GitHub Actions" />
<br><sub><b>Actions</b></sub>
</td>
</tr>
</table>

</div>

<br/>

## <img src="https://img.shields.io/badge/▸-9B59FF?style=flat-square&labelColor=061028" height="20"/> Featured Projects

<sup>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</sup>

<!-- Project Card 1: sl-interpreter -->
<a href="https://github.com/Binivert/sl-interpreter">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Binivert&repo=sl-interpreter&theme=dark&hide_border=true&bg_color=061028&title_color=00E5FF&icon_color=9B59FF&text_color=9bdcff" alt="sl-interpreter" />
</a>

> 🤟 **Sign Language Interpreter** — Real-time gesture recognition & translation system

![Python](https://img.shields.io/badge/Python-00E5FF?style=flat-square&labelColor=061028)
![OpenCV](https://img.shields.io/badge/OpenCV-9B59FF?style=flat-square&labelColor=061028)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0077FF?style=flat-square&labelColor=061028)

---

<!-- Project Card 2: security-system -->
<a href="https://github.com/Binivert/security-system">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Binivert&repo=security-system&theme=dark&hide_border=true&bg_color=061028&title_color=00E5FF&icon_color=9B59FF&text_color=9bdcff" alt="security-system" />
</a>

> 🔐 **Security System** — Intelligent surveillance with motion detection & alerts

![Python](https://img.shields.io/badge/Python-00E5FF?style=flat-square&labelColor=061028)
![Computer Vision](https://img.shields.io/badge/CV-9B59FF?style=flat-square&labelColor=061028)
![Deep Learning](https://img.shields.io/badge/DL-0077FF?style=flat-square&labelColor=061028)

---

<!-- Project Card 3: VisionArc -->
<a href="https://github.com/Binivert/VisionArc">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Binivert&repo=VisionArc&theme=dark&hide_border=true&bg_color=061028&title_color=00E5FF&icon_color=9B59FF&text_color=9bdcff" alt="VisionArc" />
</a>

> 👁️ **VisionArc** — Computer vision framework for rapid prototyping & deployment

![Python](https://img.shields.io/badge/Python-00E5FF?style=flat-square&labelColor=061028)
![PyTorch](https://img.shields.io/badge/PyTorch-9B59FF?style=flat-square&labelColor=061028)
![CUDA](https://img.shields.io/badge/CUDA-0077FF?style=flat-square&labelColor=061028)

</td>
<td width="30%" valign="top">

<!-- RIGHT COLUMN: Social Links -->

<div align="center">

<!-- Animated Social Card -->
<svg width="220" height="320" viewBox="0 0 220 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="cardGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="cardBorder" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF">
        <animate attributeName="stop-color" values="#00E5FF;#9B59FF;#00E5FF" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#9B59FF">
        <animate attributeName="stop-color" values="#9B59FF;#00E5FF;#9B59FF" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  
  <style>
    @keyframes pulse {
      0%, 100% { opacity: 0.8; }
      50% { opacity: 1; }
    }
    .card-bg { fill: #061028; }
    .card-border { stroke: url(#cardBorder); stroke-width: 2; fill: none; }
    .card-title { font-family: 'Courier New', monospace; font-size: 14px; fill: #00E5FF; font-weight: bold; }
    .social-text { font-family: 'Courier New', monospace; font-size: 11px; fill: #9bdcff; }
    .icon-glow { animation: pulse 2s infinite; }
  </style>
  
  <rect x="5" y="5" width="210" height="310" rx="10" class="card-bg"/>
  <rect x="5" y="5" width="210" height="310" rx="10" class="card-border" filter="url(#cardGlow)"/>
  
  <text x="110" y="35" text-anchor="middle" class="card-title">⚡ CONNECT</text>
  <line x1="30" y1="50" x2="190" y2="50" stroke="#00E5FF" stroke-width="1" opacity="0.5"/>
  
  <!-- LinkedIn -->
  <g class="icon-glow" transform="translate(30, 70)">
    <rect width="24" height="24" rx="4" fill="#0077B5"/>
    <text x="12" y="17" text-anchor="middle" fill="white" font-size="14" font-weight="bold">in</text>
  </g>
  <text x="65" y="87" class="social-text">LinkedIn</text>
  
  <!-- Discord -->
  <g class="icon-glow" transform="translate(30, 115)">
    <rect width="24" height="24" rx="4" fill="#5865F2"/>
    <text x="12" y="17" text-anchor="middle" fill="white" font-size="10">DC</text>
  </g>
  <text x="65" y="132" class="social-text">binitrion</text>
  
  <!-- Email -->
  <g class="icon-glow" transform="translate(30, 160)">
    <rect width="24" height="24" rx="4" fill="#EA4335"/>
    <text x="12" y="17" text-anchor="middle" fill="white" font-size="10">@</text>
  </g>
  <text x="65" y="177" class="social-text">bintrion@gmail</text>
  
  <!-- Instagram -->
  <g class="icon-glow" transform="translate(30, 205)">
    <rect width="24" height="24" rx="4" fill="#E4405F"/>
    <text x="12" y="17" text-anchor="middle" fill="white" font-size="10">IG</text>
  </g>
  <text x="65" y="222" class="social-text">@bini_v</text>
  
  <!-- LeetCode -->
  <g class="icon-glow" transform="translate(30, 250)">
    <rect width="24" height="24" rx="4" fill="#FFA116"/>
    <text x="12" y="17" text-anchor="middle" fill="black" font-size="10" font-weight="bold">LC</text>
  </g>
  <text x="65" y="267" class="social-text">binivert</text>
  
</svg>

<br/>

<!-- Clickable social links -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](REPLACE_WITH_LINKEDIN_URL)
<!-- ⚠️ REPLACE_ME: Replace REPLACE_WITH_LINKEDIN_URL with your LinkedIn profile URL -->
<!-- Example: https://www.linkedin.com/in/biniyam-bonger/ -->

[![Discord](https://img.shields.io/badge/Discord-binitrion-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/binitrion)

[![Email](https://img.shields.io/badge/Email-bintrion%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bintrion@gmail.com)

[![Instagram](https://img.shields.io/badge/Instagram-bini__v-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/bini_v/)

[![LeetCode](https://img.shields.io/badge/LeetCode-binivert-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/binivert/)

</div>

<br/>

<!-- Current Focus Card -->
<div align="center">

## ⚡ Current Focus

</div>

```
┌─────────────────────────┐
│ ◉ Real-time vision      │
│   pipelines             │
│                         │
│ ◉ PyTorch/CUDA          │
│   optimizations         │
│                         │
│ ◉ Edge device           │
│   deployment            │
│                         │
│ ◉ MediaPipe custom      │
│   detection systems     │
└─────────────────────────┘
```

</td>
</tr>
</table>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ANIMATED DIVIDER 2
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="100%" height="30" viewBox="0 0 1200 30" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="dividerGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#061028"/>
      <stop offset="30%" style="stop-color:#9B59FF">
        <animate attributeName="offset" values="0.3;0.5;0.3" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#00E5FF"/>
      <stop offset="70%" style="stop-color:#9B59FF">
        <animate attributeName="offset" values="0.7;0.5;0.7" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#061028"/>
    </linearGradient>
  </defs>
  <rect x="0" y="14" width="1200" height="2" fill="url(#dividerGrad2)"/>
  <circle cx="600" cy="15" r="4" fill="#00E5FF">
    <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#00E5FF;#9B59FF;#00E5FF" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════════
     GITHUB STATS SECTION
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

## <img src="https://img.shields.io/badge/▸-00E5FF?style=flat-square&labelColor=061028" height="20"/> GitHub Analytics

<sup>━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━</sup>

<br/>

<!-- Stats Cards Row -->
<table>
<tr>
<td>

<!-- GitHub Stats Card -->
<img src="https://github-readme-stats.vercel.app/api?username=Binivert&show_icons=true&hide_border=true&bg_color=061028&title_color=00E5FF&icon_color=9B59FF&text_color=9bdcff&ring_color=00E5FF&include_all_commits=true&count_private=true" alt="GitHub Stats" />

</td>
<td>

<!-- Top Languages Card -->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Binivert&layout=compact&hide_border=true&bg_color=061028&title_color=00E5FF&text_color=9bdcff&langs_count=8" alt="Top Languages" />

</td>
</tr>
</table>

<br/>

<!-- Streak Stats -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Binivert&hide_border=true&background=061028&stroke=00E5FF&ring=00E5FF&fire=9B59FF&currStreakNum=9bdcff&sideNums=9bdcff&currStreakLabel=00E5FF&sideLabels=00E5FF&dates=9bdcff" alt="GitHub Streak" />

<br/><br/>

<!-- GitHub Trophies -->
<img src="https://github-profile-trophy.vercel.app/?username=Binivert&theme=darkhub&no-frame=true&no-bg=true&column=7&margin-w=15&margin-h=15" alt="GitHub Trophies" />

<br/><br/>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Binivert&bg_color=061028&color=9bdcff&line=00E5FF&point=9B59FF&area=true&area_color=00E5FF&hide_border=true" alt="Contribution Graph" />

<br/><br/>

<!-- Contribution Snake -->
<!-- ⚠️ This requires GitHub Actions setup - see SETUP section below -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Binivert/Binivert/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Binivert/Binivert/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Binivert/Binivert/output/github-contribution-grid-snake-dark.svg" />
</picture>
<!-- Fallback: If snake doesn't load, the contribution graph above serves as alternative -->

<br/><br/>

<!-- Additional Stats Badges -->
<img src="https://komarev.com/ghpvc/?username=Binivert&style=for-the-badge&color=00E5FF&label=PROFILE+VIEWS" alt="Profile Views" style="display:none" />
<!-- Note: Visitor counter disabled as per request -->

<!-- Language Stats Donut -->
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Binivert&layout=donut&hide_border=true&bg_color=061028&title_color=00E5FF&text_color=9bdcff" alt="Languages Donut" />

<br/><br/>

<!-- Detailed Stats -->
<table>
<tr>
<td>

![Commits](https://img.shields.io/badge/Total%20Commits-Loading-00E5FF?style=for-the-badge&labelColor=061028&logo=git&logoColor=white)

</td>
<td>

![PRs](https://img.shields.io/badge/Pull%20Requests-Loading-9B59FF?style=for-the-badge&labelColor=061028&logo=github&logoColor=white)

</td>
<td>

![Issues](https://img.shields.io/badge/Issues-Loading-0077FF?style=for-the-badge&labelColor=061028&logo=github&logoColor=white)

</td>
</tr>
</table>

<!-- Summary Card -->
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Binivert&theme=github_dark" alt="Profile Summary" />

<br/>

<!-- Productive Time & Commits per Language -->
<table>
<tr>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Binivert&theme=github_dark&utcOffset=0" alt="Productive Time" />
</td>
<td>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Binivert&theme=github_dark" alt="Repos per Language" />
</td>
</tr>
</table>

<br/>

<!-- Additional Shields.io Badges -->

![GitHub followers](https://img.shields.io/github/followers/Binivert?style=for-the-badge&labelColor=061028&color=00E5FF&logo=github)
![GitHub User's stars](https://img.shields.io/github/stars/Binivert?style=for-the-badge&labelColor=061028&color=9B59FF&logo=github)

<br/>

<!-- Language Badges -->
![Python](https://img.shields.io/badge/Python-Expert-00E5FF?style=for-the-badge&labelColor=061028&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Proficient-9B59FF?style=for-the-badge&labelColor=061028&logo=javascript&logoColor=white)
![C++](https://img.shields.io/badge/C++-Intermediate-0077FF?style=for-the-badge&labelColor=061028&logo=cplusplus&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Specialist-00E5FF?style=for-the-badge&labelColor=061028&logo=opencv&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Practitioner-9B59FF?style=for-the-badge&labelColor=061028&logo=pytorch&logoColor=white)

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     FOOTER
     ═══════════════════════════════════════════════════════════════════════════ -->

<br/>

<div align="center">
<svg width="100%" height="50" viewBox="0 0 1200 50" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#061028"/>
      <stop offset="50%" style="stop-color:#00E5FF"/>
      <stop offset="100%" style="stop-color:#061028"/>
    </linearGradient>
  </defs>
  <rect x="0" y="24" width="1200" height="2" fill="url(#footerGrad)"/>
</svg>

<br/>

<sub>⚡ Last Updated: 2024 • Built with passion for Computer Vision & AI ⚡</sub>

<br/>

<sub>💡 <em>"The best way to predict the future is to build it."</em></sub>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     SETUP INSTRUCTIONS
     ═══════════════════════════════════════════════════════════════════════════ -->

<details>
<summary><h2>📋 SETUP INSTRUCTIONS (Click to expand)</h2></summary>

### 🚀 Quick Start Checklist

- [ ] Create a repository named exactly `Binivert` (same as your username)
- [ ] Copy this entire README.md content into that repository
- [ ] Replace all placeholders (see below)
- [ ] Set up GitHub Actions for the snake animation
- [ ] Pin your featured repositories
- [ ] Upload any custom assets

---

### 1️⃣ Create Your Profile Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `Binivert` (MUST match your username exactly)
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"
6. Replace the default README with this content

---

### 2️⃣ Replace Placeholders

#### LinkedIn URL
Find this line in the README:
```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](REPLACE_WITH_LINKEDIN_URL)
```

Replace `REPLACE_WITH_LINKEDIN_URL` with your actual LinkedIn profile URL:
```markdown
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/your-linkedin-username/)
```

#### Other Social Links (Already configured)
- Discord: `binitrion` ✓
- Email: `bintrion@gmail.com` ✓
- Instagram: `https://www.instagram.com/bini_v/` ✓
- LeetCode: `https://leetcode.com/binivert/` ✓

---

### 3️⃣ Set Up GitHub Actions for Snake Animation

The contribution snake requires a GitHub Action to generate the SVG.

#### Step 3.1: Create the workflow file

1. In your `Binivert` repository, create folder: `.github/workflows/`
2. Create file: `.github/workflows/snake.yml`
3. Paste this content:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *" # Runs daily at midnight UTC
  workflow_dispatch: # Allows manual trigger
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: Binivert
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

#### Step 3.2: Enable Actions

1. Go to your repository → **Settings** → **Actions** → **General**
2. Under "Workflow permissions", select **"Read and write permissions"**
3. Click **Save**

#### Step 3.3: Run the workflow

1. Go to **Actions** tab
2. Click "Generate Snake" workflow
3. Click "Run workflow" → "Run workflow"
4. Wait for it to complete (creates `output` branch with snake SVGs)

---

### 4️⃣ Pin Your Featured Repositories

1. Go to your GitHub profile: `github.com/Binivert`
2. Click "Customize your pins"
3. Select these repositories:
   - `sl-interpreter`
   - `security-system`
   - `VisionArc`
4. Click "Save pins"

---

### 5️⃣ Personal Access Token (Optional - For Private Repo Stats)

If you want to include private repository statistics:

#### Step 5.1: Create a Personal Access Token

1. Go to [GitHub Settings → Developer Settings → Personal Access Tokens → Tokens (classic)](https://github.com/settings/tokens)
2. Click "Generate new token (classic)"
3. Name: `README_STATS`
4. Select scopes:
   - `repo` (Full control of private repositories)
   - `read:user` (Read user profile data)
5. Click "Generate token"
6. **Copy the token immediately** (you won't see it again)

#### Step 5.2: Add Token as Repository Secret

1. Go to your `Binivert` repository → **Settings** → **Secrets and variables** → **Actions**
2. Click "New repository secret"
3. Name: `GH_TOKEN`
4. Value: Paste your token
5. Click "Add secret"

⚠️ **SECURITY WARNING**: Never paste tokens directly in your README. Always use GitHub Secrets.

---

### 6️⃣ Custom Assets (Optional)

If you want to use custom GIF banners instead of SVG:

1. Create an `assets/` folder in your repository
2. Upload your GIF (e.g., `banner.gif`)
3. Replace the SVG banner with:
```markdown
![Banner](https://raw.githubusercontent.com/Binivert/Binivert/main/assets/banner.gif)
```

**Recommended GIF specs:**
- Width: 800px
- Height: 200px
- File size: < 5MB (compress with [ezgif.com](https://ezgif.com/optimize))

---

### 7️⃣ Widget Customization Reference

#### GitHub Readme Stats
```
https://github-readme-stats.vercel.app/api?username=Binivert&show_icons=true&hide_border=true&bg_color=061028&title_color=00E5FF&icon_color=9B59FF&text_color=9bdcff
```

**Parameters:**
- `bg_color`: Background color (hex without #)
- `title_color`: Title text color
- `icon_color`: Icon color
- `text_color`: Body text color
- `hide_border`: Remove border (true/false)
- `show_icons`: Show icons (true/false)
- `count_private`: Include private repos (true/false)

#### Streak Stats
```
https://github-readme-streak-stats.herokuapp.com/?user=Binivert&hide_border=true&background=061028&stroke=00E5FF&ring=00E5FF&fire=9B59FF&currStreakNum=9bdcff
```

#### Activity Graph
```
https://github-readme-activity-graph.vercel.app/graph?username=Binivert&bg_color=061028&color=9bdcff&line=00E5FF&point=9B59FF&area=true&hide_border=true
```

---

### 8️⃣ Troubleshooting

| Issue | Solution |
|-------|----------|
| Snake not showing | Run the GitHub Action manually; check `output` branch exists |
| Stats cards blank | Verify username is correct; widgets may have rate limits |
| SVG not animating | Some browsers/renderers block SVG animations; this is normal |
| Images broken | Check URLs are correct; ensure repository is public |
| Widgets slow to load | Third-party services may have delays; this is normal |

---

### 9️⃣ Maintenance Checklist

**Monthly:**
- [ ] Update "Last Updated" date in footer
- [ ] Check all widget URLs still work
- [ ] Compress any new GIFs added

**Quarterly:**
- [ ] Review and update tech stack if skills changed
- [ ] Update featured projects if new repos created
- [ ] Check third-party services (vercel apps) are still available

**Fallbacks:**
If any widget service goes down, these are reliable alternatives:
- Stats: `https://github-readme-stats.vercel.app/` (multiple mirrors available)
- Badges: `https://shields.io/` (very stable)
- Icons: `https://skillicons.dev/` or `https://simpleicons.org/`

---

### 🔒 Security Notes

1. **Never** commit tokens or secrets to your README
2. Use GitHub Secrets for any sensitive data
3. Review Actions permissions periodically
4. The `GITHUB_TOKEN` used in Actions is automatically provided and scoped

---

### 📄 License

This README design is shared under **CC-BY-NC-SA 4.0**.

You may:
- Share and adapt the design
- Must give attribution
- Non-commercial use only
- Share adaptations under same license

Feel free to change this license for your own profile.

---

### 🎨 Color Palette Quick Reference

```
--bg:        #061028  (Deep Navy)
--neon-cyan: #00E5FF  (Primary Accent)
--blue:      #0077FF  (Secondary)
--accent:    #9B59FF  (Purple Highlight)
--text:      #9bdcff  (Light Cyan Text)
--glass:     rgba(255,255,255,0.03)
```

To change the theme, find-and-replace these hex values throughout the README.

</details>

---

<div align="center">
<sub>⚡ Crafted with 💜 and lots of ☕ ⚡</sub>
</div>
