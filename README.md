<!--
Modern, 100% GitHub-compatible dark-themed README.
- Uses your GitHub profile picture as the header.
- Two main cards (Creative & Tech Stack) are larger and on top.
- Three smaller cards (About, Education, Connect) are below, perfectly aligned.
- Responsive breakpoints: Cards stack vertically on small screens for perfect alignment.
- All boxes use gray #262626, strong box-shadow, and Poppins font.
- No white space or padding; background is #222020.
-->

<div align="center" style="background:#222020; padding:0; margin:0; width:100vw;">

<img src="https://github.com/ThePhatLee.png" alt="ThePhatLee avatar" width="150" style="margin-bottom: 18px; background:#262626; border-radius:50%; box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5);" />

<div style="font-family:'Poppins','Segoe UI',Arial,sans-serif; font-size:2.25em; font-weight:900; letter-spacing:2px; color:#d9d9d9; margin-top:10px;">
  <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f393.svg" width="40" style="vertical-align:middle"/> Hi, I'm ThePhatLee
</div>
<div style="color:#a6a6a6;font-family:'Poppins','Segoe UI',Arial,sans-serif; font-weight:500; margin-bottom:10px; font-size:1.18em;">
  Freelancer Web Developer | Three.js/WebGL Creative Engineer <br>
  Student · Software Development / Engineering
</div>

</div>

---

<!-- RESPONSIVE GRID USING FLEXBOX AND WRAP FOR GITHUB COMPATIBILITY -->
<!-- All cards use the same color, shadow, and border radius. Large cards on top, smaller on bottom, always aligned. -->
<div align="center" style="background:#222020; width:100vw; padding:0; margin:0;">
<!-- Flexbox parent for responsiveness (GitHub doesn't support media queries, but flex-wrap is respected) -->
<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:24px 24px;background:#222020;max-width:100vw;padding:0 0 24px 0;">

  <!-- LEFT LARGE CARD: Creative Coding -->
  <div style="flex:1 1 340px; min-width:290px; max-width:420px; background:#262626; border-radius:15px; border:2px solid #595959; box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5); margin:8px; padding:32px 22px 32px 22px; font-family:'Poppins','Segoe UI',Arial,sans-serif; display:flex; flex-direction:column; justify-content:center;">
    <div style="display:flex;align-items:center;gap:12px;">
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f47e.svg" width="30"/>
      <span style="font-size:1.35em;font-weight:700;letter-spacing:0.5px;color:#d9d9d9;">Creative Coding & 3D Art</span>
    </div>
    <div style="margin-top:14px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original-wordmark.svg" width="33"/>
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f3a8.svg" width="27"/>
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f5bc.svg" width="27"/>
    </div>
    <ul style="margin:20px 0 0 0;padding-left:20px;text-align:left;color:#a6a6a6;font-size:1.05em;">
      <li>Three.js / WebGL interactive & creative experiences</li>
      <li>3D rendering, generative art, creative coding</li>
      <li>Visual effects, UI/UX, immersive web</li>
      <li>Photography & digital art lover</li>
    </ul>
  </div>

  <!-- RIGHT LARGE CARD: Tech Stack -->
  <div style="flex:1 1 340px; min-width:290px; max-width:420px; background:#262626; border-radius:15px; border:2px solid #595959; box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5); margin:8px; padding:32px 22px 32px 22px; font-family:'Poppins','Segoe UI',Arial,sans-serif; display:flex; flex-direction:column; justify-content:center;">
    <div style="display:flex;align-items:center;gap:12px;">
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4bb.svg" width="30"/>
      <span style="font-size:1.35em;font-weight:700;letter-spacing:0.5px;color:#d9d9d9;">Tech Stack & Workflow</span>
    </div>
    <div style="margin-top:14px">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fedora/fedora-original.svg" width="24"/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="24"/>
    </div>
    <ul style="margin:20px 0 0 0;padding-left:20px;text-align:left;color:#a6a6a6;font-size:1.05em;">
      <li>HTML, CSS/SCSS, JavaScript, React, C++, Python</li>
      <li>Three.js, WebGL, React</li>
      <li>Containerized Dev (Podman/Docker), CI/CD, QA</li>
      <li>Fedora (Silverblue/Kinoite), Linux-first, open source</li>
    </ul>
  </div>
</div>

<!-- BREAKPOINT for perfect alignment: force next row on narrow screens by using 100% width invisible block -->
<div style="flex-basis:100%;height:0;"></div>

<!-- Smaller cards in a new flex row, always aligned under the big cards. -->
<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:18px 18px;background:#222020;max-width:100vw;padding:0 0 24px 0;">

  <!-- About Card -->
  <div style="flex:1 1 210px;min-width:165px;max-width:260px;background:#262626;border:2px solid #595959;border-radius:15px;box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5);margin:8px;padding:18px 12px;font-family:'Poppins','Segoe UI',Arial,sans-serif;">
    <div style="display:flex;align-items:center;gap:8px;">
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/2728.svg" width="22"/>
      <span style="font-weight:700;color:#d9d9d9;">About Me</span>
    </div>
    <ul style="margin:13px 0 0 0;padding-left:16px;text-align:left;color:#a6a6a6;font-size:1em;">
      <li>🐧 Fedora & immutable systems</li>
      <li>🔎 Open source, QA, beta testing</li>
      <li>🛡️ Learning ethical hacking, cyber security</li>
      <li>🤝 Always open to creative collabs!</li>
    </ul>
  </div>

  <!-- Education Card -->
  <div style="flex:1 1 210px;min-width:165px;max-width:260px;background:#262626;border:2px solid #595959;border-radius:15px;box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5);margin:8px;padding:18px 12px;font-family:'Poppins','Segoe UI',Arial,sans-serif;">
    <div style="display:flex;align-items:center;gap:8px;">
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f393.svg" width="22"/>
      <span style="font-weight:700;color:#d9d9d9;">Education</span>
    </div>
    <ul style="margin:13px 0 0 0;padding-left:16px;text-align:left;color:#a6a6a6;font-size:1em;">
      <li>🎓 Focus: Software Dev / Engineering</li>
      <li>🕸️ Web, creative, and 3D dev</li>
      <li>🔒 Cybersecurity & IT support</li>
    </ul>
  </div>

  <!-- Connect Card -->
  <div style="flex:1 1 210px;min-width:165px;max-width:260px;background:#262626;border:2px solid #595959;border-radius:15px;box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5);margin:8px;padding:18px 12px;font-family:'Poppins','Segoe UI',Arial,sans-serif;">
    <div style="display:flex;align-items:center;gap:8px;">
      <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f4e8.svg" width="22"/>
      <span style="font-weight:700;color:#d9d9d9;">Find Me</span>
    </div>
    <div style="margin:9px 0 0 0;">
      <a href="https://github.com/ThePhatLee" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="25" style="margin-right:5px;"/>
      </a>
      <a href="https://gitlab.com/ThePhatLe" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gitlab/gitlab-original.svg" width="25" style="margin-right:5px;"/>
      </a>
      <a href="https://discussion.fedoraproject.org/u/thephatlee/summary" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/1507452?s=48&v=4" width="25" style="margin-right:5px;"/>
      </a>
      <a href="https://matrix.to/#/@thephatle:matrix.com" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Matrix.org_Logo.svg" width="25"/>
      </a>
    </div>
    <div style="font-size:0.93em;color:#a6a6a6;margin-top:8px">
      🚫 No social networks – open source & decentralized only!
    </div>
  </div>
</div>
</div>

---

<blockquote align="center" style="font-style:italic; color:#d9d9d9; font-family:'Poppins','JetBrains Mono','Fira Code',monospace; background:#262626; border-radius:10px; padding:12px 18px; border:2px solid #595959; box-shadow:10px 15px 50px 5px rgba(0,0,0,0.5);">
  “Pixels, code, and creativity.<br>
    I build web worlds that move, render, and inspire.<br>
    Let’s push boundaries together.”
</blockquote>

<!--
Tips:
- The header uses your GitHub profile picture.
- Two large cards on top, three smaller below, all aligned. Flex-wrap ensures they stack cleanly on mobile.
- All cards: #262626, border radius 15px, border #595959, strong box-shadow.
- No white backgrounds/padding. Font: Poppins (if installed).
-->
