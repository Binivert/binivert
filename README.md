<style>
:root {
  --bg: #010b1f;
  --panel: #041737;
  --cyan: #00e5ff;
  --cyan-soft: #7fe9ff;
}
body, .cyber-wrapper {
  background: var(--bg);
  color: var(--cyan);
  font-family: "IBM Plex Mono", "Space Grotesk", "Orbitron", monospace;
}
.cyber-wrapper {
  padding: 1.5rem;
  background: var(--bg);
}
a {
  color: var(--cyan);
  text-decoration: none;
}
.grid {
  display: grid;
  gap: 1.25rem;
}
.header-grid {
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  align-items: center;
}
.identity-grid {
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
}
.skills-grid {
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
}
.widgets-grid {
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1rem;
}
.contact-grid {
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
}
.panel {
  background: radial-gradient(circle at top, rgba(0,229,255,0.08), transparent 55%), var(--panel);
  border: 1px solid rgba(0,229,255,0.25);
  border-radius: 0.85rem;
  padding: 1.25rem;
  box-shadow: 0 0 18px rgba(0,229,255,0.12);
}
.placeholder {
  border: 1px dashed rgba(0,229,255,0.45);
  border-radius: 0.85rem;
  padding: 2rem;
  text-align: center;
  font-size: 0.85rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--cyan-soft);
}
.placeholder.tall {
  min-height: 220px;
}
.glitch {
  position: relative;
  font-size: clamp(2.4rem, 6vw, 4.6rem);
  font-weight: 700;
  letter-spacing: 0.3em;
  text-transform: uppercase;
  color: var(--cyan);
}
.glitch::before,
.glitch::after {
  content: attr(data-text);
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  clip-path: inset(0 0 0 0);
  animation: glitchShift 2.8s infinite;
}
.glitch::before {
  color: rgba(0,229,255,0.65);
  transform: translate(2px, -2px);
  animation-duration: 3.2s;
}
.glitch::after {
  color: rgba(0,229,255,0.35);
  transform: translate(-2px, 2px);
  animation-duration: 2.7s;
}
@keyframes glitchShift {
  0% { clip-path: inset(0 0 85% 0); }
  20% { clip-path: inset(15% 0 40% 0); }
  40% { clip-path: inset(60% 0 5% 0); }
  60% { clip-path: inset(20% 0 25% 0); }
  80% { clip-path: inset(40% 0 15% 0); }
  100% { clip-path: inset(0 0 85% 0); }
}
.signature {
  font-size: 1rem;
  letter-spacing: 0.5em;
  margin-top: 0.5rem;
  color: var(--cyan-soft);
}
.type-line {
  border-right: 2px solid var(--cyan);
  white-space: nowrap;
  overflow: hidden;
  width: fit-content;
  font-size: 1rem;
  letter-spacing: 0.25em;
  margin-top: 1rem;
  animation: typing 5s steps(40) infinite alternate, caret 0.7s step-end infinite;
}
@keyframes typing {
  0% { width: 0; }
  50% { width: 100%; }
  100% { width: 0; }
}
@keyframes caret {
  from, to { border-color: transparent; }
  50% { border-color: var(--cyan); }
}
.badge {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.25rem 0.65rem;
  margin: 0.2rem;
  font-size: 0.75rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  border: 1px solid rgba(0,229,255,0.6);
  border-radius: 999px;
  background: rgba(4,27,58,0.9);
  color: var(--cyan);
}
.divider {
  height: 2px;
  margin: 2rem 0;
  background: linear-gradient(90deg, transparent, var(--cyan), transparent);
  position: relative;
  overflow: hidden;
}
.divider::after {
  content: "";
  position: absolute;
  top: -4px;
  left: -10%;
  width: 20%;
  height: 10px;
  background: rgba(0,229,255,0.6);
  animation: scan 3s linear infinite;
}
@keyframes scan {
  0% { left: -20%; }
  100% { left: 120%; }
}
.widget-card {
  background: rgba(4,23,55,0.85);
  border: 1px solid rgba(0,229,255,0.25);
  border-radius: 0.85rem;
  padding: 0.6rem;
  text-align: center;
}
.widget-card img {
  width: 100%;
  border-radius: 0.5rem;
  border: 1px solid rgba(0,229,255,0.15);
}
.contact-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.65rem 1rem;
  border-radius: 999px;
  border: 1px solid rgba(0,229,255,0.4);
  background: rgba(4,23,55,0.75);
  letter-spacing: 0.15em;
}
</style>

<div class="cyber-wrapper">

<div class="grid header-grid panel">
  <div>
    <div class="glitch" data-text="BINIYAM BONGER">BINIYAM BONGER</div>
    <div class="signature">BINI&nbsp;V_X</div>
    <div class="type-line">AI ∷ DEEP LEARNING ∷ COMPUTER VISION</div>
    <p style="margin-top:1rem; letter-spacing:0.2em; color:var(--cyan-soft);">Hyper-modular perception systems, self-evolving vision stacks.</p>
  </div>
  <div class="placeholder tall">[ PLACEHOLDER ∷ FUTURE NEON VISUAL ]</div>
</div>

<div class="divider"></div>

<div class="grid identity-grid">
  <div class="panel">
    <h3 style="margin-top:0; letter-spacing:0.25em;">IDENTITY ∷ FOCUS</h3>
    <p style="letter-spacing:0.18em;">Exploring Artificial Intelligence and Visual Intelligence.</p>
    <div>
      <span class="badge">AI</span>
      <span class="badge">DEEP LEARNING</span>
      <span class="badge">COMPUTER VISION</span>
      <span class="badge">EDGE CV</span>
      <span class="badge">MLOPS</span>
    </div>
  </div>
  <div class="panel">
    <h3 style="margin-top:0; letter-spacing:0.25em;">STATUS MATRIX</h3>
    <div class="badge">Binivert // GitHub</div>
    <div class="badge">MODE: BLUEPRINT</div>
    <div class="badge">SIGNAL BANDWIDTH: ULTRA-CYAN</div>
    <div class="badge">LOCALE: REMOTE GRID</div>
  </div>
</div>

<div class="divider"></div>

<div class="panel">
  <h3 style="margin-top:0; letter-spacing:0.25em;">SKILL MESH</h3>
  <div class="grid skills-grid">
    <span class="badge">PYTHON</span>
    <span class="badge">OPENCV</span>
    <span class="badge">TENSORFLOW</span>
    <span class="badge">PYTORCH</span>
    <span class="badge">PANDAS</span>
    <span class="badge">MEDIAPIPE</span>
    <span class="badge">GITHUB</span>
    <span class="badge">LINUX</span>
  </div>
</div>

<div class="divider"></div>

<div class="panel">
  <h3 style="margin-top:0; letter-spacing:0.25em;">GITHUB DIAGNOSTICS GRID</h3>
  <div class="grid widgets-grid">
    <div class="widget-card">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=binivert&show_icons=true&bg_color=010b1f&title_color=00e5ff&text_color=7fe9ff&icon_color=00e5ff&hide_border=true" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/binivert">
        <img alt="Streak Stats" src="https://streak-stats.demolab.com?user=binivert&background=010b1f&ring=00e5ff&fire=00e5ff&currStreakLabel=00e5ff&sideNums=00e5ff&sideLabels=00e5ff&currStreakNum=00e5ff&dates=7fe9ff&hide_border=true" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=binivert&layout=compact&bg_color=010b1f&title_color=00e5ff&text_color=7fe9ff&hide_border=true&langs_count=8" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/ryo-ma/github-profile-trophy">
        <img alt="GitHub Trophies" src="https://github-profile-trophy.vercel.app/?username=binivert&theme=nord&no-frame=true&no-bg=true&column=4&margin-w=8&margin-h=8" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/Ashutosh00710/github-readme-activity-graph">
        <img alt="Contribution Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=binivert&bg_color=010b1f&color=00e5ff&line=00e5ff&point=00e5ff&area=true&hide_border=true" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/Ashutosh00710/github-readme-activity-graph">
        <img alt="Code Frequency" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=binivert&theme=github_dark" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/yoshi389111/github-profile-3d-contrib">
        <img alt="3D Contribution Graph Night" src="https://raw.githubusercontent.com/binivert/binivert/output/profile-night-rainbow.svg" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/binivert/binivert">
        <img alt="Snake Animation" src="https://github.com/binivert/binivert/blob/output/github-contribution-grid-snake.svg" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Repo Summary" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=binivert&theme=github_dark" />
      </a>
    </div>
    <div class="widget-card">
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Code Commit Stats" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=binivert&theme=github_dark" />
      </a>
    </div>
  </div>
</div>

<div class="panel" style="margin-top:1.5rem;">
  <h3 style="margin-top:0; letter-spacing:0.25em;">REPO SIGNAL BADGES</h3>
  <div class="badge">
    <a href="https://github.com/binivert/binivert">
      ![Repo Size](https://img.shields.io/github/repo-size/binivert/binivert?style=flat-square&color=00e5ff&labelColor=041737&label=BINIVERT%20SIZE)
    </a>
  </div>
  <div class="badge">
    <a href="https://github.com/binivert/binivert">
      ![Last Commit](https://img.shields.io/github/last-commit/binivert/binivert?style=flat-square&color=00e5ff&labelColor=041737&label=LAST%20COMMIT)
    </a>
  </div>
  <div class="badge">
    <a href="https://github.com/binivert/binivert">
      ![Repo Stars](https://img.shields.io/github/stars/binivert/binivert?style=flat-square&color=00e5ff&labelColor=041737&label=STARS)
    </a>
  </div>
</div>

<div class="divider"></div>

<div class="panel">
  <h3 style="margin-top:0; letter-spacing:0.25em;">VISUAL PLACEHOLDERS</h3>
  <div class="grid identity-grid">
    <div class="placeholder">[ INSERT CYBERPUNK AVATAR ]</div>
    <div class="placeholder">[ INSERT DATASTREAM GIF ]</div>
  </div>
</div>

<div class="divider"></div>

<div class="panel contact-grid">
  <div>
    <h3 style="margin-top:0; letter-spacing:0.25em;">CONTACT CHANNELS</h3>
    <a class="contact-link" href="https://instagram.com/binivert" target="_blank">INSTAGRAM // @BINIVERT</a>
    <div style="margin-top:1rem;">
      <div class="contact-link">[ PLACEHOLDER ∷ EMAIL LINK ]</div>
      <div class="contact-link">[ PLACEHOLDER ∷ PORTFOLIO LINK ]</div>
    </div>
  </div>
  <div>
    <h3 style="margin-top:0; letter-spacing:0.25em;">SIGNAL STATUS</h3>
    <p style="letter-spacing:0.2em;">Open for AI vision collaborations, research spikes, stealth prototypes.</p>
    <p style="letter-spacing:0.18em;">Ping → <code style="background:rgba(0,229,255,0.08); padding:0.15rem 0.4rem; border-radius:0.5rem;">binivert</code></p>
  </div>
</div>

</div>
