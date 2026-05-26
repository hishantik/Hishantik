<!--
  ═══════════════════════════════════════════════════════════════════
  █  HISHANTIK SARKAR — Developer Profile                           █
  █  Design: Premium Cyberpunk · Glassmorphism · Terminal Aesthetic  █
  ═══════════════════════════════════════════════════════════════════

  CUSTOMIZATION:
  Replace "Hishantik" with your GitHub username.
  Search "██ EDIT" to find all customizable sections.
  Color palette: #0f172a #111827 #1e293b #7c3aed #8b5cf6 #06b6d4 #ec4899 #22c55e
-->

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  SHARED SVG DEFINITIONS                                        ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- These are referenced by id throughout the document -->
<svg width="0" height="0" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad-purple-cyan" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#06b6d4"/>
    </linearGradient>
    <linearGradient id="grad-cyan-pink" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06b6d4"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
    <linearGradient id="grad-pink-purple" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ec4899"/>
      <stop offset="100%" stop-color="#7c3aed"/>
    </linearGradient>
    <linearGradient id="grad-full" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="20%" stop-color="#7c3aed"/>
      <stop offset="40%" stop-color="#06b6d4"/>
      <stop offset="60%" stop-color="#8b5cf6"/>
      <stop offset="80%" stop-color="#ec4899"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <linearGradient id="grad-fade-center" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="50%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#0f172a"/>
    </linearGradient>
    <filter id="glow-sm">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow-md">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <!-- Dot grid pattern -->
    <pattern id="dot-grid" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
      <circle cx="1" cy="1" r="0.5" fill="#1e293b"/>
    </pattern>
    <!-- Hex pattern -->
    <pattern id="hex-grid" x="0" y="0" width="28" height="49" patternUnits="userSpaceOnUse">
      <path d="M14 0 L28 8.5 L28 25.5 L14 34 L0 25.5 L0 8.5 Z" fill="none" stroke="#1e293b" stroke-width="0.5"/>
    </pattern>
  </defs>
</svg>

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  01 · HERO                                                    ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<!-- ██ EDIT: Replace "Hishantik" with your name ██ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,40:7c3aed,70:06b6d4,100:0f172a&height=180&section=header&text=Hishantik%20Sarkar&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Software%20Developer%20%C2%B7%20Open%20Source%20Enthusiast&descSize=15&descAlignY=58&descAlign=50&animation=scaleIn&font=Outfit" width="100%" alt=""/>

<br/>

<!-- Typing animation -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=400&size=17&pause=1200&color=06b6d4&center=true&vCenter=true&multiline=true&repeat=true&width=680&height=70&lines=%F0%9F%9A%80+Building+the+future%2C+one+commit+at+a+time;Open+Source+%C2%B7+Linux+%C2%B7+Web+Dev+%C2%B7+Cloud" alt=""/>

<br/><br/>

<!-- Avatar with SVG glow ring -->
<svg width="160" height="160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="avatar-clip"><circle cx="80" cy="80" r="62"/></clipPath>
    <linearGradient id="avatar-ring" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#7c3aed"/>
      <stop offset="50%" stop-color="#06b6d4"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>
  </defs>
  <!-- Glow -->
  <circle cx="80" cy="80" r="68" fill="none" stroke="#7c3aed" stroke-width="1" opacity="0.2" filter="url(#glow-md)"/>
  <!-- Ring -->
  <circle cx="80" cy="80" r="65" fill="none" stroke="url(#avatar-ring)" stroke-width="2.5"/>
  <!-- Inner dark -->
  <circle cx="80" cy="80" r="62" fill="#0f172a"/>
  <!-- Avatar image -->
  <image href="https://images.weserv.nl/?url=https://github.com/user-attachments/assets/8f184958-8242-483c-bcd6-61a60f396935?v=4&h=124&w=124&fit=cover&mask=circle&maxage=7d" x="18" y="18" width="124" height="124" clip-path="url(#avatar-clip)"/>
  <!-- Status dot -->
  <circle cx="130" cy="130" r="8" fill="#0f172a"/>
  <circle cx="130" cy="130" r="5.5" fill="#22c55e">
    <animate attributeName="opacity" values="1;0.5;1" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

<!-- Status line -->
<sub>
  <code>📍 India</code> · <code>🦉 Night Owl</code> · <code>☕ Coffee Powered</code> · <code>🟢 Available</code>
</sub>

<br/><br/>

<!-- Badges — minimal, three only -->
<img src="https://komarev.com/ghpvc/?username=Hishantik&label=views&color=7c3aed&style=flat&labelColor=111827" alt="views"/>
&nbsp;
<img src="https://img.shields.io/github/followers/Hishantik?label=followers&style=flat&color=06b6d4&logo=github&logoColor=white&labelColor=111827" alt="followers"/>
&nbsp;
<img src="https://img.shields.io/github/stars/Hishantik?label=stars&style=flat&color=ec4899&logo=github&logoColor=white&labelColor=111827" alt="stars"/>

<br/><br/>

<!-- Social row — flat style, minimal -->
<!-- ██ EDIT: Replace all href="#" with your URLs ██ -->
<a href="https://github.com/Hishantik"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://twitter.com/sarkar_234"><img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white" alt="X"/></a>
<a href="https://dev.to/sarkar_234"><img src="https://img.shields.io/badge/Dev.to-0A0A0A?style=flat&logo=dev.to&logoColor=white" alt="Dev.to"/></a>
<a href="https://linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/Dekustik"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
<a href="mailto:hishantik@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>

<br/>

<!-- Currently building — subtle indicator -->
<img src="https://img.shields.io/badge/%F0%9F%94%A7%20Currently%20building-Something%20awesome-22c55e?style=flat&labelColor=111827&color=22c55e" alt="building"/>

<br/>

<!-- SVG decorative arrow divider -->
<svg width="200" height="30" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="15" x2="85" y2="15" stroke="#1e293b" stroke-width="1"/>
  <polygon points="95,10 105,15 95,20" fill="#7c3aed" opacity="0.6"/>
  <polygon points="100,10 110,15 100,20" fill="#06b6d4" opacity="0.4"/>
  <line x1="115" y1="15" x2="200" y2="15" stroke="#1e293b" stroke-width="1"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  02 · ABOUT ME                                                ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=8b5cf6&center=true&vCenter=true&repeat=false&width=300&height=40&lines=About+Me" alt=""/>

<!-- Section number accent -->
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg">
  <rect width="40" height="2" rx="1" fill="url(#grad-purple-cyan)"/>
</svg>
</div>

<br/>

<!-- Two-column About Me — balanced layout -->
<table>
<tr>
<!-- Left: Code block -->
<td width="55%" valign="top">

```javascript
const developer = {
  name     : "Hishantik Sarkar",
  role     : "Software Developer",
  location : "India 🇮🇳",
  focus    : [
    "Backend & Systems",
    "Open Source Tooling",
    "Developer Experience",
    "Cloud Infrastructure"
  ],
  currently: {
    building : "Open-source tools & CLI utilities",
    learning : "Rust · System Design · Cloud Architecture",
    exploring: "AI/ML workflows · WebAssembly"
  },
  philosophy: "Write code that speaks for itself.",
  funFact   : "Night owl — best commits happen after midnight 🦉"
};
```

</td>

<!-- Spacer column -->
<td width="4%"></td>

<!-- Right: SVG Glassmorphism Card -->
<td width="41%" valign="top">

<!-- Card uses viewBox for responsive sizing -->
<svg viewBox="0 0 320 260" width="100%" xmlns="http://www.w3.org/2000/svg">
  <!-- Card background -->
  <rect x="1" y="1" width="318" height="258" rx="12" fill="#111827" fill-opacity="0.6" stroke="url(#grad-purple-cyan)" stroke-width="1" stroke-opacity="0.3"/>
  <!-- Dot pattern overlay -->
  <rect x="1" y="1" width="318" height="258" rx="12" fill="url(#dot-grid)" opacity="0.3"/>
  <!-- Glow accent top -->
  <rect x="20" y="0" width="80" height="2" rx="1" fill="#7c3aed" filter="url(#glow-sm)"/>

  <!-- Content -->
  <text x="24" y="36" font-family="system-ui" font-size="13" font-weight="600" fill="#e6edf3">🎯 Interests</text>
  <text x="24" y="60" font-family="monospace" font-size="11" fill="#8b949e">Linux · Open Source · Terminal Tools</text>
  <text x="24" y="78" font-family="monospace" font-size="11" fill="#8b949e">Web Dev · Cloud · DevOps</text>

  <line x1="24" y1="96" x2="296" y2="96" stroke="#1e293b" stroke-width="1"/>

  <text x="24" y="118" font-family="system-ui" font-size="13" font-weight="600" fill="#e6edf3">📖 Currently Reading</text>
  <text x="24" y="142" font-family="monospace" font-size="11" fill="#8b949e">Clean Architecture</text>
  <text x="24" y="160" font-family="monospace" font-size="11" fill="#8b949e">Designing Data-Intensive Apps</text>

  <line x1="24" y1="178" x2="296" y2="178" stroke="#1e293b" stroke-width="1"/>

  <text x="24" y="200" font-family="system-ui" font-size="13" font-weight="600" fill="#e6edf3">🎵 Vibes</text>
  <text x="24" y="224" font-family="monospace" font-size="11" fill="#8b949e">Lo-fi beats · Coding playlists</text>
  <text x="24" y="242" font-family="monospace" font-size="11" fill="#8b949e">Late night sessions</text>
</svg>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — About → Tech Stack                          ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="60" viewBox="0 0 1200 60" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 30 Q150 0 300 30 T600 30 T900 30 T1200 30 V60 H0 Z" fill="#111827" opacity="0.4"/>
  <path d="M0 35 Q150 10 300 35 T600 35 T900 35 T1200 35 V60 H0 Z" fill="#111827" opacity="0.2"/>
  <line x1="0" y1="30" x2="1200" y2="30" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  03 · TECH STACK                                              ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=7c3aed&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Tech+Stack" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-cyan-pink)"/></svg>
</div>

<br/>

<!-- Tech Stack — SVG framed skill icon grid -->
<!-- ██ EDIT: Replace skill slugs at skillicons.dev — https://skillicons.dev ██ -->
<div align="center">

<svg viewBox="0 0 660 280" width="660" xmlns="http://www.w3.org/2000/svg">
  <!-- Frame background -->
  <rect x="1" y="1" width="658" height="278" rx="12" fill="#0f172a" fill-opacity="0.5" stroke="#1e293b" stroke-width="1"/>
  <!-- Hex pattern overlay -->
  <rect x="1" y="1" width="658" height="278" rx="12" fill="url(#hex-grid)" opacity="0.3"/>
  <!-- Corner accents -->
  <path d="M1 20 L1 1 L20 1" fill="none" stroke="#7c3aed" stroke-width="2" opacity="0.6"/>
  <path d="M658 20 L659 1 L640 1" fill="none" stroke="#06b6d4" stroke-width="2" opacity="0.6"/>
  <path d="M1 260 L1 279 L20 279" fill="none" stroke="#06b6d4" stroke-width="2" opacity="0.6"/>
  <path d="M658 260 L659 279 L640 279" fill="none" stroke="#ec4899" stroke-width="2" opacity="0.6"/>

  <!-- Section labels -->
  <text x="20" y="28" font-family="monospace" font-size="10" fill="#8b949e" opacity="0.6">LANGUAGES</text>
  <text x="20" y="118" font-family="monospace" font-size="10" fill="#8b949e" opacity="0.6">FRONTEND & BACKEND</text>
  <text x="20" y="208" font-family="monospace" font-size="10" fill="#8b949e" opacity="0.6">DEVOPS & TOOLS</text>

  <!-- Separator lines -->
  <line x1="20" y1="100" x2="640" y2="100" stroke="#1e293b" stroke-width="0.5"/>
  <line x1="20" y1="190" x2="640" y2="190" stroke="#1e293b" stroke-width="0.5"/>

  <!-- Row 1: Languages (10 icons × 40px = 400px, centered) -->
  <image href="https://skillicons.dev/icons?i=c,cpp,java,python,js,ts,lua,bash,html,css&theme=dark&perline=10" x="80" y="34" width="500" height="58"/>

  <!-- Row 2: Frontend & Backend (8 icons × 40px = 320px, centered) -->
  <image href="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,tailwind,firebase,mongodb,postgres&theme=dark&perline=8" x="120" y="110" width="420" height="58"/>

  <!-- Row 3: DevOps & Tools (10 icons × 40px = 400px, centered) -->
  <image href="https://skillicons.dev/icons?i=docker,aws,git,github,linux,vim,neovim,vscode,figma,postman&theme=dark&perline=10" x="80" y="200" width="500" height="58"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Tech → System                               ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="50" viewBox="0 0 1200 50" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 25 Q300 50 600 25 T1200 25 V50 H0 Z" fill="#111827" opacity="0.3"/>
  <line x1="0" y1="25" x2="1200" y2="25" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
  <!-- Decorative dots -->
  <circle cx="200" cy="25" r="2" fill="#7c3aed" opacity="0.5"/>
  <circle cx="400" cy="25" r="2" fill="#06b6d4" opacity="0.5"/>
  <circle cx="600" cy="25" r="2" fill="#8b5cf6" opacity="0.5"/>
  <circle cx="800" cy="25" r="2" fill="#ec4899" opacity="0.5"/>
  <circle cx="1000" cy="25" r="2" fill="#7c3aed" opacity="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  04 · DEVELOPER CONTROL CENTER                                ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=06b6d4&center=true&vCenter=true&repeat=false&width=350&height=40&lines=System+Diagnostics" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-purple-cyan)"/></svg>
</div>

<br/>

<!-- ═══ Terminal Window — System Info + Animated Language Carousel ═══ -->
<!-- GitHub-safe: only uses <animate> on opacity. No clipPath, filter, or animateTransform. -->
<div align="center">

<!-- ██ EDIT: Replace system values with your actual setup ██ -->

<table>
<tr>
<!-- ═══ LEFT: System Info Terminal ═══ -->
<td valign="top">

<svg width="340" height="360" xmlns="http://www.w3.org/2000/svg">
  <!-- Window frame -->
  <rect x="0" y="0" width="340" height="360" rx="10" fill="#111827" stroke="#1e293b" stroke-width="1"/>
  <!-- Title bar -->
  <rect x="0" y="0" width="340" height="30" rx="10" fill="#1e293b"/>
  <rect x="0" y="18" width="340" height="12" fill="#1e293b"/>
  <circle cx="16" cy="15" r="4.5" fill="#f85149"/>
  <circle cx="30" cy="15" r="4.5" fill="#e3b341"/>
  <circle cx="44" cy="15" r="4.5" fill="#3fb950"/>
  <text x="170" y="19" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">system info</text>

  <!-- Static top border (no animation needed) -->
  <text x="14" y="50" font-family="monospace" font-size="11" fill="#7c3aed">╭──── system ───────────╮</text>

  <!-- Each line fades in sequentially -->
  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="0.2s" fill="freeze"/>
    <text x="14" y="70" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="70" font-family="monospace" font-size="10.5" fill="#06b6d4">OS      </text>
    <text x="82" y="70" font-family="monospace" font-size="10.5" fill="#e6edf3">Arch Linux / WSL</text>
    <text x="326" y="70" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="0.4s" fill="freeze"/>
    <text x="14" y="88" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="88" font-family="monospace" font-size="10.5" fill="#06b6d4">Shell   </text>
    <text x="82" y="88" font-family="monospace" font-size="10.5" fill="#e6edf3">zsh + oh-my-zsh</text>
    <text x="326" y="88" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="0.6s" fill="freeze"/>
    <text x="14" y="106" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="106" font-family="monospace" font-size="10.5" fill="#06b6d4">Editor  </text>
    <text x="82" y="106" font-family="monospace" font-size="10.5" fill="#e6edf3">Neovim / VS Code</text>
    <text x="326" y="106" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="0.8s" fill="freeze"/>
    <text x="14" y="124" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="124" font-family="monospace" font-size="10.5" fill="#06b6d4">Terminal</text>
    <text x="82" y="124" font-family="monospace" font-size="10.5" fill="#e6edf3">Alacritty / Kitty</text>
    <text x="326" y="124" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="1.0s" fill="freeze"/>
    <text x="14" y="142" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="142" font-family="monospace" font-size="10.5" fill="#06b6d4">WM/DE   </text>
    <text x="82" y="142" font-family="monospace" font-size="10.5" fill="#e6edf3">Hyprland / GNOME</text>
    <text x="326" y="142" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="1.2s" fill="freeze"/>
    <text x="14" y="160" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="160" font-family="monospace" font-size="10.5" fill="#06b6d4">Browser </text>
    <text x="82" y="160" font-family="monospace" font-size="10.5" fill="#e6edf3">Firefox / Brave</text>
    <text x="326" y="160" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="1.4s" fill="freeze"/>
    <text x="14" y="178" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="178" font-family="monospace" font-size="10.5" fill="#06b6d4">Theme   </text>
    <text x="82" y="178" font-family="monospace" font-size="10.5" fill="#e6edf3">Tokyo Night</text>
    <text x="326" y="178" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="1.6s" fill="freeze"/>
    <text x="14" y="196" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="196" font-family="monospace" font-size="10.5" fill="#06b6d4">Font    </text>
    <text x="82" y="196" font-family="monospace" font-size="10.5" fill="#e6edf3">JetBrains Mono NF</text>
    <text x="326" y="196" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="1.8s" fill="freeze"/>
    <text x="14" y="214" font-family="monospace" font-size="10.5" fill="#8b949e">│</text>
    <text x="26" y="214" font-family="monospace" font-size="10.5" fill="#06b6d4">Uptime  </text>
    <text x="82" y="214" font-family="monospace" font-size="10.5" fill="#e6edf3">coding...</text>
    <text x="326" y="214" font-family="monospace" font-size="10.5" fill="#8b949e" text-anchor="end">│</text>
  </g>

  <!-- Bottom border -->
  <text x="14" y="232" font-family="monospace" font-size="11" fill="#7c3aed">╰───────────────────────╯</text>

  <!-- Prompt + cursor -->
  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="2.0s" fill="freeze"/>
    <text x="14" y="252" font-family="monospace" font-size="10.5" fill="#22c55e">$</text>
    <text x="26" y="252" font-family="monospace" font-size="10.5" fill="#8b949e"> neofetch --short</text>
  </g>

  <!-- Blinking cursor -->
  <rect x="14" y="260" width="7" height="12" fill="#06b6d4" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>

  <!-- Runtime box -->
  <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.3s" begin="2.3s" fill="freeze"/>
    <text x="14" y="286" font-family="monospace" font-size="10" fill="#8b949e">╭── runtime ────────────╮</text>
    <text x="14" y="302" font-family="monospace" font-size="10" fill="#8b949e">│</text>
    <text x="26" y="302" font-family="monospace" font-size="10" fill="#06b6d4">node</text>
    <text x="56" y="302" font-family="monospace" font-size="10" fill="#e6edf3">v20+</text>
    <text x="92" y="302" font-family="monospace" font-size="10" fill="#06b6d4">python</text>
    <text x="140" y="302" font-family="monospace" font-size="10" fill="#e6edf3">3.11+</text>
    <text x="180" y="302" font-family="monospace" font-size="10" fill="#06b6d4">java</text>
    <text x="208" y="302" font-family="monospace" font-size="10" fill="#e6edf3">17+</text>
    <text x="326" y="302" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="end">│</text>
    <text x="14" y="318" font-family="monospace" font-size="10" fill="#8b949e">│</text>
    <text x="26" y="318" font-family="monospace" font-size="10" fill="#06b6d4">docker</text>
    <text x="72" y="318" font-family="monospace" font-size="10" fill="#e6edf3">24+</text>
    <text x="100" y="318" font-family="monospace" font-size="10" fill="#06b6d4">git</text>
    <text x="124" y="318" font-family="monospace" font-size="10" fill="#e6edf3">2.40+</text>
    <text x="326" y="318" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="end">│</text>
    <text x="14" y="334" font-family="monospace" font-size="10" fill="#8b949e">╰───────────────────────╯</text>
  </g>
</svg>

</td>

<td width="16"></td>

<!-- ═══ RIGHT: Animated Language Carousel ═══ -->
<td valign="top">

<!-- Each language block is its own SVG. They cycle visibility via staggered opacity animations. -->
<!-- dur=56s, 7 blocks × 8s each. keyTimes: in(0-5%) stay(5-75%) out(75-80%) gap(80-100%) -->

<svg width="360" height="360" xmlns="http://www.w3.org/2000/svg">
  <!-- Window frame -->
  <rect x="0" y="0" width="360" height="360" rx="10" fill="#111827" stroke="#1e293b" stroke-width="1"/>
  <!-- Title bar -->
  <rect x="0" y="0" width="360" height="30" rx="10" fill="#1e293b"/>
  <rect x="0" y="18" width="360" height="12" fill="#1e293b"/>
  <circle cx="16" cy="15" r="4.5" fill="#f85149"/>
  <circle cx="30" cy="15" r="4.5" fill="#e3b341"/>
  <circle cx="44" cy="15" r="4.5" fill="#3fb950"/>
  <text x="180" y="19" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">live code stream</text>

  <!-- ═══ BLOCK 1: Python ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.05;0.75;0.80" dur="56s" repeatCount="indefinite"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">#!/usr/bin/env python3</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">import</text>
    <text x="78" y="72" font-family="monospace" font-size="10.5" fill="#e6edf3"> asyncio</text>
    <text x="14" y="90" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="90" font-family="monospace" font-size="10.5" fill="#c678dd">from</text>
    <text x="66" y="90" font-family="monospace" font-size="10.5" fill="#e6edf3"> pathlib </text>
    <text x="118" y="90" font-family="monospace" font-size="10.5" fill="#c678dd">import</text>
    <text x="160" y="90" font-family="monospace" font-size="10.5" fill="#e6edf3"> Path</text>
    <text x="14" y="114" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="114" font-family="monospace" font-size="10.5" fill="#c678dd">async</text>
    <text x="68" y="114" font-family="monospace" font-size="10.5" fill="#c678dd"> def</text>
    <text x="90" y="114" font-family="monospace" font-size="10.5" fill="#61afef"> main</text>
    <text x="122" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">():</text>
    <text x="14" y="132" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="132" font-family="monospace" font-size="10.5" fill="#98c379">    print</text>
    <text x="86" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">(</text>
    <text x="92" y="132" font-family="monospace" font-size="10.5" fill="#98c379">"building..."</text>
    <text x="166" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">)</text>
    <text x="14" y="150" font-family="monospace" font-size="10.5" fill="#8b949e">5</text>
    <text x="36" y="150" font-family="monospace" font-size="10.5" fill="#98c379">    result </text>
    <text x="92" y="150" font-family="monospace" font-size="10.5" fill="#abb2bf">= </text>
    <text x="106" y="150" font-family="monospace" font-size="10.5" fill="#c678dd">await</text>
    <text x="140" y="150" font-family="monospace" font-size="10.5" fill="#e6edf3"> aio</text>
    <text x="162" y="150" font-family="monospace" font-size="10.5" fill="#abb2bf">.</text>
    <text x="168" y="150" font-family="monospace" font-size="10.5" fill="#61afef">gather</text>
    <text x="208" y="150" font-family="monospace" font-size="10.5" fill="#abb2bf">(</text>
    <text x="214" y="150" font-family="monospace" font-size="10.5" fill="#abb2bf">)</text>
    <!-- Blinking cursor -->
    <rect x="14" y="164" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <!-- Language label -->
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#e6943b" opacity="0.6">● python</text>
  </g>

  <!-- ═══ BLOCK 2: JavaScript ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.143;0.193;0.893;0.943" dur="56s" repeatCount="indefinite"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">// index.js</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">const</text>
    <text x="72" y="72" font-family="monospace" font-size="10.5" fill="#e06c75"> fetch</text>
    <text x="108" y="72" font-family="monospace" font-size="10.5" fill="#abb2bf"> = </text>
    <text x="124" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">require</text>
    <text x="168" y="72" font-family="monospace" font-size="10.5" fill="#98c379">(</text>
    <text x="174" y="72" font-family="monospace" font-size="10.5" fill="#98c379">'node-fetch'</text>
    <text x="246" y="72" font-family="monospace" font-size="10.5" fill="#98c379">)</text>
    <text x="252" y="72" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="96" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="96" font-family="monospace" font-size="10.5" fill="#c678dd">async</text>
    <text x="72" y="96" font-family="monospace" font-size="10.5" fill="#c678dd"> function</text>
    <text x="130" y="96" font-family="monospace" font-size="10.5" fill="#61afef"> getData</text>
    <text x="184" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">() {</text>
    <text x="14" y="114" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="114" font-family="monospace" font-size="10.5" fill="#c678dd">  const</text>
    <text x="78" y="114" font-family="monospace" font-size="10.5" fill="#e06c75"> res</text>
    <text x="102" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf"> = </text>
    <text x="118" y="114" font-family="monospace" font-size="10.5" fill="#c678dd">await</text>
    <text x="152" y="114" font-family="monospace" font-size="10.5" fill="#e06c75"> fetch</text>
    <text x="188" y="114" font-family="monospace" font-size="10.5" fill="#98c379">(</text>
    <text x="194" y="114" font-family="monospace" font-size="10.5" fill="#98c379">'/api/data'</text>
    <text x="256" y="114" font-family="monospace" font-size="10.5" fill="#98c379">)</text>
    <text x="262" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="132" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="132" font-family="monospace" font-size="10.5" fill="#c678dd">  return</text>
    <text x="80" y="132" font-family="monospace" font-size="10.5" fill="#e06c75"> res</text>
    <text x="104" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">.</text>
    <text x="110" y="132" font-family="monospace" font-size="10.5" fill="#61afef">json</text>
    <text x="136" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">();</text>
    <text x="14" y="150" font-family="monospace" font-size="10.5" fill="#8b949e">5</text>
    <text x="36" y="150" font-family="monospace" font-size="10.5" fill="#abb2bf">}</text>
    <rect x="14" y="164" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#e3b341" opacity="0.6">● javascript</text>
  </g>

  <!-- ═══ BLOCK 3: Rust ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.286;0.336;1.0;1.0" dur="56s" repeatCount="indefinite"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">// main.rs</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">use</text>
    <text x="58" y="72" font-family="monospace" font-size="10.5" fill="#e06c75"> std</text>
    <text x="82" y="72" font-family="monospace" font-size="10.5" fill="#abb2bf">::</text>
    <text x="94" y="72" font-family="monospace" font-size="10.5" fill="#e06c75">io</text>
    <text x="106" y="72" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="96" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="96" font-family="monospace" font-size="10.5" fill="#c678dd">fn</text>
    <text x="54" y="96" font-family="monospace" font-size="10.5" fill="#61afef"> main</text>
    <text x="92" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">() {</text>
    <text x="14" y="114" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="114" font-family="monospace" font-size="10.5" fill="#98c379">    println!</text>
    <text x="102" y="114" font-family="monospace" font-size="10.5" fill="#98c379">(</text>
    <text x="108" y="114" font-family="monospace" font-size="10.5" fill="#98c379">"fast & safe"</text>
    <text x="186" y="114" font-family="monospace" font-size="10.5" fill="#98c379">)</text>
    <text x="192" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="132" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">}</text>
    <rect x="14" y="146" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#f85149" opacity="0.6">● rust</text>
  </g>

  <!-- ═══ BLOCK 4: Go ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.143;0.193;0.893;0.943" dur="56s" repeatCount="indefinite" begin="8s"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">// main.go</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">package</text>
    <text x="86" y="72" font-family="monospace" font-size="10.5" fill="#e06c75"> main</text>
    <text x="14" y="96" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="96" font-family="monospace" font-size="10.5" fill="#c678dd">func</text>
    <text x="66" y="96" font-family="monospace" font-size="10.5" fill="#61afef"> main</text>
    <text x="104" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">() {</text>
    <text x="14" y="114" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="114" font-family="monospace" font-size="10.5" fill="#e06c75">    fmt</text>
    <text x="72" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">.</text>
    <text x="78" y="114" font-family="monospace" font-size="10.5" fill="#61afef">Println</text>
    <text x="128" y="114" font-family="monospace" font-size="10.5" fill="#98c379">("concurrent")</text>
    <text x="14" y="132" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">}</text>
    <rect x="14" y="146" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#06b6d4" opacity="0.6">● go</text>
  </g>

  <!-- ═══ BLOCK 5: TypeScript ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.143;0.193;0.893;0.943" dur="56s" repeatCount="indefinite" begin="16s"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">// config.ts</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">interface</text>
    <text x="98" y="72" font-family="monospace" font-size="10.5" fill="#e5c07b"> Config</text>
    <text x="144" y="72" font-family="monospace" font-size="10.5" fill="#abb2bf"> {</text>
    <text x="14" y="90" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="90" font-family="monospace" font-size="10.5" fill="#e06c75">  port</text>
    <text x="72" y="90" font-family="monospace" font-size="10.5" fill="#abb2bf">:</text>
    <text x="80" y="90" font-family="monospace" font-size="10.5" fill="#e5c07b"> number</text>
    <text x="126" y="90" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="108" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="108" font-family="monospace" font-size="10.5" fill="#e06c75">  debug</text>
    <text x="84" y="108" font-family="monospace" font-size="10.5" fill="#abb2bf">:</text>
    <text x="92" y="108" font-family="monospace" font-size="10.5" fill="#e5c07b"> boolean</text>
    <text x="144" y="108" font-family="monospace" font-size="10.5" fill="#abb2bf">;</text>
    <text x="14" y="126" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="126" font-family="monospace" font-size="10.5" fill="#abb2bf">}</text>
    <rect x="14" y="140" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#3178c6" opacity="0.6">● typescript</text>
  </g>

  <!-- ═══ BLOCK 6: C ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.143;0.193;0.893;0.943" dur="56s" repeatCount="indefinite" begin="24s"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">// main.c</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#c678dd">#include</text>
    <text x="92" y="72" font-family="monospace" font-size="10.5" fill="#98c379"> &lt;stdio.h&gt;</text>
    <text x="14" y="96" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="96" font-family="monospace" font-size="10.5" fill="#e5c07b">int</text>
    <text x="60" y="96" font-family="monospace" font-size="10.5" fill="#61afef"> main</text>
    <text x="96" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">(</text>
    <text x="102" y="96" font-family="monospace" font-size="10.5" fill="#e5c07b">int</text>
    <text x="126" y="96" font-family="monospace" font-size="10.5" fill="#e06c75"> argc</text>
    <text x="158" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">,</text>
    <text x="166" y="96" font-family="monospace" font-size="10.5" fill="#e5c07b"> char</text>
    <text x="196" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">**</text>
    <text x="210" y="96" font-family="monospace" font-size="10.5" fill="#e06c75"> argv</text>
    <text x="240" y="96" font-family="monospace" font-size="10.5" fill="#abb2bf">) {</text>
    <text x="14" y="114" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="114" font-family="monospace" font-size="10.5" fill="#e06c75">  printf</text>
    <text x="84" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">(</text>
    <text x="90" y="114" font-family="monospace" font-size="10.5" fill="#98c379">"systems level"</text>
    <text x="178" y="114" font-family="monospace" font-size="10.5" fill="#abb2bf">);</text>
    <text x="14" y="132" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="132" font-family="monospace" font-size="10.5" fill="#abb2bf">}</text>
    <rect x="14" y="146" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#a8b9cc" opacity="0.6">● c</text>
  </g>

  <!-- ═══ BLOCK 7: Bash ═══ -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1;1;0" keyTimes="0.143;0.193;0.893;0.943" dur="56s" repeatCount="indefinite" begin="32s"/>
    <text x="14" y="52" font-family="monospace" font-size="9" fill="#8b949e" opacity="0.5">$ terminal</text>
    <text x="14" y="72" font-family="monospace" font-size="10.5" fill="#8b949e">1</text>
    <text x="36" y="72" font-family="monospace" font-size="10.5" fill="#22c55e">$</text>
    <text x="50" y="72" font-family="monospace" font-size="10.5" fill="#e6edf3"> docker compose up -d</text>
    <text x="14" y="90" font-family="monospace" font-size="10.5" fill="#8b949e">2</text>
    <text x="36" y="90" font-family="monospace" font-size="10.5" fill="#22c55e">$</text>
    <text x="50" y="90" font-family="monospace" font-size="10.5" fill="#e6edf3"> git push origin main</text>
    <text x="14" y="108" font-family="monospace" font-size="10.5" fill="#8b949e">3</text>
    <text x="36" y="108" font-family="monospace" font-size="10.5" fill="#22c55e">$</text>
    <text x="50" y="108" font-family="monospace" font-size="10.5" fill="#e6edf3"> cargo build --release</text>
    <text x="14" y="126" font-family="monospace" font-size="10.5" fill="#8b949e">4</text>
    <text x="36" y="126" font-family="monospace" font-size="10.5" fill="#22c55e">$</text>
    <text x="50" y="126" font-family="monospace" font-size="10.5" fill="#e6edf3"> npm run deploy</text>
    <rect x="14" y="140" width="6" height="11" fill="#06b6d4" rx="1">
      <animate attributeName="opacity" values="1;0;1" dur="0.8s" repeatCount="indefinite"/>
    </rect>
    <text x="14" y="345" font-family="monospace" font-size="9" fill="#22c55e" opacity="0.6">● bash</text>
  </g>

</svg>

</td>
</tr>
</table>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — System → Analytics                          ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="50" viewBox="0 0 1200 50" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 20 C200 40 400 0 600 20 S1000 40 1200 20 V50 H0 Z" fill="#111827" opacity="0.3"/>
  <path d="M0 25 C200 45 400 5 600 25 S1000 45 1200 25 V50 H0 Z" fill="#111827" opacity="0.15"/>
  <line x1="0" y1="25" x2="1200" y2="25" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  05 · GITHUB ANALYTICS                                       ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=ec4899&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Analytics" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-cyan-pink)"/></svg>
</div>

<br/>

<!-- ██ EDIT: Change theme — tokyonight, dracula, radical, algolia, gruvbox, nightowl ██ -->
<div align="center">

<!-- SVG frame around stats cards -->
<svg width="95%" height="12" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="100%" height="1" fill="url(#grad-fade-center)" opacity="0.3"/>
  <!-- Corner dots -->
  <circle cx="0" cy="0" r="2" fill="#7c3aed" opacity="0.6"/>
  <circle cx="100%" cy="0" r="2" fill="#06b6d4" opacity="0.6"/>
</svg>

<!-- Stats + Streak -->
<a href="https://github.com/Hishantik">
  <img src="https://github-readme-stats.vercel.app/api?username=Hishantik&show_icons=true&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&icon_color=06b6d4&text_color=c9d1d9&ring_color=7c3aed&include_all_commits=true&count_private=true" width="49%" alt="stats"/>
</a>
<a href="https://github.com/Hishantik">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hishantik&theme=tokyonight&background=0d1117&hide_border=true&ring=7c3aed&fire=ec4899&currStreakLabel=7c3aed&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681" width="49%" alt="streak"/>
</a>

<!-- SVG separator between rows -->
<svg width="60%" height="20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="45%" y2="10" stroke="#1e293b" stroke-width="1"/>
  <circle cx="50%" cy="10" r="3" fill="none" stroke="url(#grad-purple-cyan)" stroke-width="1"/>
  <circle cx="50%" cy="10" r="1" fill="#7c3aed"/>
  <line x1="55%" y1="10" x2="100%" y2="10" stroke="#1e293b" stroke-width="1"/>
</svg>

<!-- Top Languages — donut -->
<a href="https://github.com/Hishantik">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hishantik&layout=donut&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&text_color=c9d1d9&langs_count=8" width="32%" alt="langs"/>
</a>

<!-- SVG separator -->
<svg width="40%" height="20" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="10" x2="100%" y2="10" stroke="#1e293b" stroke-width="0.5"/>
  <circle cx="20%" cy="10" r="1.5" fill="#7c3aed" opacity="0.4"/>
  <circle cx="40%" cy="10" r="1.5" fill="#06b6d4" opacity="0.4"/>
  <circle cx="60%" cy="10" r="1.5" fill="#8b5cf6" opacity="0.4"/>
  <circle cx="80%" cy="10" r="1.5" fill="#ec4899" opacity="0.4"/>
</svg>

<!-- Activity Graph -->
<a href="https://github.com/Hishantik">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Hishantik&bg_color=0d1117&color=06b6d4&line=7c3aed&point=ec4899&area=true&area_color=7c3aed&hide_border=true&custom_title=" width="95%" alt="activity"/>
</a>

<!-- SVG divider with glow -->
<svg width="70%" height="16" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="8" x2="100%" y2="8" stroke="#1e293b" stroke-width="0.5"/>
  <rect x="35%" y="6" width="30%" height="4" rx="2" fill="url(#grad-purple-cyan)" opacity="0.3" filter="url(#glow-sm)"/>
</svg>

<!-- Trophies -->
<a href="https://github.com/Hishantik">
  <img src="https://github-profile-trophy.vercel.app/?username=Hishantik&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=4" width="90%" alt="trophies"/>
</a>

<!-- SVG decorative element -->
<svg width="200" height="24" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="12" x2="70" y2="12" stroke="#1e293b" stroke-width="0.5"/>
  <polygon points="80,7 90,12 80,17" fill="#7c3aed" opacity="0.4"/>
  <circle cx="95" cy="12" r="2" fill="#06b6d4" opacity="0.6"/>
  <polygon points="100,7 110,12 100,17" fill="#ec4899" opacity="0.4" transform="scale(-1,1) translate(-200,0)"/>
  <line x1="130" y1="12" x2="200" y2="12" stroke="#1e293b" stroke-width="0.5"/>
</svg>

<!-- Contribution Snake -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hishantik/Hishantik/output/github-contribution-grid-snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/Hishantik/Hishantik/output/github-contribution-grid-snake-dark.svg" width="85%" alt="snake"/>
</picture>

<!-- Bottom frame -->
<svg width="95%" height="8" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="7" width="100%" height="1" fill="url(#grad-fade-center)" opacity="0.3"/>
  <circle cx="0" cy="7" r="2" fill="#06b6d4" opacity="0.6"/>
  <circle cx="100%" cy="7" r="2" fill="#ec4899" opacity="0.6"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Analytics → Projects                        ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="60" viewBox="0 0 1200 60" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 30 Q300 0 600 30 T1200 30 V60 H0 Z" fill="#111827" opacity="0.25"/>
  <path d="M0 35 Q300 10 600 35 T1200 35 V60 H0 Z" fill="#111827" opacity="0.12"/>
  <line x1="0" y1="30" x2="1200" y2="30" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
  <!-- Hex dots -->
  <circle cx="100" cy="30" r="1.5" fill="#7c3aed" opacity="0.5"/>
  <circle cx="300" cy="30" r="1.5" fill="#06b6d4" opacity="0.5"/>
  <circle cx="500" cy="30" r="1.5" fill="#8b5cf6" opacity="0.5"/>
  <circle cx="700" cy="30" r="1.5" fill="#ec4899" opacity="0.5"/>
  <circle cx="900" cy="30" r="1.5" fill="#22c55e" opacity="0.5"/>
  <circle cx="1100" cy="30" r="1.5" fill="#7c3aed" opacity="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  06 · FEATURED PROJECTS                                       ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=06b6d4&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Featured+Projects" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-purple-cyan)"/></svg>
</div>

<br/>

<!-- ██ EDIT: Replace REPO_NAME with your actual repo names ██ -->
<table>
<tr>
<td width="50%" align="center" valign="top">
<!-- SVG border frame -->
<svg width="100%" height="4" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="2" rx="1" fill="url(#grad-purple-cyan)" opacity="0.5"/>
</svg>
<a href="https://github.com/Hishantik/REPO_NAME">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&icon_color=06b6d4&text_color=c9d1d9"/>
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&icon_color=06b6d4&text_color=c9d1d9" alt=""/>
</picture>
</a>
</td>
<td width="50%" align="center" valign="top">
<svg width="100%" height="4" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="2" rx="1" fill="url(#grad-cyan-pink)" opacity="0.5"/>
</svg>
<a href="https://github.com/Hishantik/REPO_NAME">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=06b6d4&icon_color=7c3aed&text_color=c9d1d9"/>
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=06b6d4&icon_color=7c3aed&text_color=c9d1d9" alt=""/>
</picture>
</a>
</td>
</tr>
<tr><td colspan="2">
<!-- SVG row separator -->
<svg width="100%" height="16" xmlns="http://www.w3.org/2000/svg">
  <line x1="10%" y1="8" x2="90%" y2="8" stroke="#1e293b" stroke-width="0.5"/>
  <circle cx="50%" cy="8" r="2" fill="none" stroke="url(#grad-cyan-pink)" stroke-width="1"/>
</svg>
</td></tr>
<tr>
<td width="50%" align="center" valign="top">
<svg width="100%" height="4" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="2" rx="1" fill="url(#grad-pink-purple)" opacity="0.5"/>
</svg>
<a href="https://github.com/Hishantik/REPO_NAME">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=ec4899&icon_color=8b5cf6&text_color=c9d1d9"/>
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=ec4899&icon_color=8b5cf6&text_color=c9d1d9" alt=""/>
</picture>
</a>
</td>
<td width="50%" align="center" valign="top">
<svg width="100%" height="4" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="2" rx="1" fill="url(#grad-cyan-pink)" opacity="0.5"/>
</svg>
<a href="https://github.com/Hishantik/REPO_NAME">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=8b5cf6&icon_color=ec4899&text_color=c9d1d9"/>
<img src="https://github-readme-stats.vercel.app/api/pin/?username=Hishantik&repo=REPO_NAME&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=8b5cf6&icon_color=ec4899&text_color=c9d1d9" alt=""/>
</picture>
</a>
</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Projects → Presence                         ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="50" viewBox="0 0 1200 50" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 25 Q200 0 400 25 T800 25 T1200 25 V50 H0 Z" fill="#111827" opacity="0.3"/>
  <line x1="0" y1="25" x2="1200" y2="25" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  07 · LIVE CODING PRESENCE                                    ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=3fb950&center=true&vCenter=true&repeat=false&width=350&height=40&lines=Coding+%26+Presence" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-cyan-pink)"/></svg>
</div>

<br/>

<table>
<tr>
<td width="50%" align="center" valign="top">

<!-- SVG card frame for WakaTime -->
<svg width="100%" height="24" xmlns="http://www.w3.org/2000/svg">
  <rect x="5%" y="0" width="90%" height="2" rx="1" fill="url(#grad-purple-cyan)" opacity="0.4"/>
  <circle cx="5%" cy="1" r="2" fill="#7c3aed" opacity="0.5"/>
  <circle cx="95%" cy="1" r="2" fill="#06b6d4" opacity="0.5"/>
  <text x="50%" y="18" font-family="system-ui" font-size="12" fill="#8b949e" text-anchor="middle" font-weight="600">📊 WakaTime</text>
</svg>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=Dekustik&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&text_color=c9d1d9&layout=compact"/>
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Dekustik&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=7c3aed&text_color=c9d1d9&layout=compact" alt="wakatime"/>
</picture>
<br/><sub>🦉 Most productive in the evening</sub>

</td>
<td width="50%" align="center" valign="top">

<!-- SVG card frame for Spotify -->
<svg width="100%" height="24" xmlns="http://www.w3.org/2000/svg">
  <rect x="5%" y="0" width="90%" height="2" rx="1" fill="url(#grad-cyan-pink)" opacity="0.4"/>
  <circle cx="5%" cy="1" r="2" fill="#06b6d4" opacity="0.5"/>
  <circle cx="95%" cy="1" r="2" fill="#ec4899" opacity="0.5"/>
  <text x="50%" y="18" font-family="system-ui" font-size="12" fill="#8b949e" text-anchor="middle" font-weight="600">🎧 Now Playing</text>
</svg>

<a href="https://open.spotify.com/user/deku">
  <img src="https://dekutorem.vercel.app/api/spotify?background_color=0d1117&border_color=7c3aed" alt="spotify"/>
</a>
<br/><sub>🎵 What I'm listening to right now</sub>

</td>
</tr>
</table>

<br/>

<!-- WakaTime expanded -->
<details>
<summary><b>📈 Detailed Breakdown</b></summary>
<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/wakatime?username=Dekustik&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=06b6d4&text_color=c9d1d9&layout=full"/>
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Dekustik&theme=tokyonight&bg_color=0d1117&hide_border=true&title_color=06b6d4&text_color=c9d1d9&layout=full" width="95%" alt=""/>
</picture>
</div>

<br/>

```
╭──────────────────── activity patterns ────────────────────╮
│                                                           │
│  TIME OF DAY                   PRODUCTIVE DAYS            │
│  ────────────                  ───────────────            │
│  🌞 Morning    93  ████░░░░  14%   Mon  125  █████░░ 19% │
│  🌆 Daytime   166  ██████░░  25%   Tue   45  ██░░░░░  7% │
│  🌃 Evening   291  █████████ 44%   Wed  109  ████░░░ 16% │
│  🌙 Night     112  ████░░░░  17%   Thu   52  ██░░░░░  8% │
│                                Fri  109  ████░░░ 16% │
│  Timezone: Asia/Kolkata        Sat   97  ████░░░ 15% │
│                                Sun  125  █████░░ 19% │
│                                                           │
╰───────────────────────────────────────────────────────────╯
```

</details>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Presence → Blog                             ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="40" viewBox="0 0 1200 40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 20 Q150 0 300 20 T600 20 T900 20 T1200 20 V40 H0 Z" fill="#111827" opacity="0.2"/>
  <line x1="0" y1="20" x2="1200" y2="20" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  08 · BLOG POSTS                                              ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=8b5cf6&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Latest+Writing" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-pink-purple)"/></svg>
</div>

<br/>

<!-- ██ EDIT: Update blog posts ██ -->
<!-- BLOG-POST-LIST:START -->
<table>
<tr>
<td valign="top" width="3%"><code>01</code></td>
<td>
<a href="https://dev.to/hishantik/a-complete-guide-to-networking-on-linux-systems-for-file-and-data-sharing-126f"><b>A Complete Guide to Networking on Linux Systems</b></a><br/>
<sub>dev.to · <code>Linux</code> <code>Networking</code></sub>
</td>
</tr>
<tr><td colspan="2">
<svg width="100%" height="8" xmlns="http://www.w3.org/2000/svg">
  <line x1="3%" y1="4" x2="97%" y2="4" stroke="#1e293b" stroke-width="0.5"/>
</svg>
</td></tr>
<tr>
<td valign="top" width="3%"><code>02</code></td>
<td>
<a href="https://dev.to/hishantik/setting-up-termux-for-web-development-a-complete-guide-jal"><b>Setting Up Termux for Web Development</b></a><br/>
<sub>dev.to · <code>Termux</code> <code>Web Dev</code></sub>
</td>
</tr>
<tr><td colspan="2">
<svg width="100%" height="8" xmlns="http://www.w3.org/2000/svg">
  <line x1="3%" y1="4" x2="97%" y2="4" stroke="#1e293b" stroke-width="0.5"/>
</svg>
</td></tr>
<tr>
<td valign="top" width="3%"><code>03</code></td>
<td>
<a href="https://dev.to/hishantik/gaming-on-linux-using-wineproton-with-dxvk-a-complete-guide-2mh6"><b>The Complete Guide to Linux Gaming</b></a><br/>
<sub>dev.to · <code>Gaming</code> <code>Linux</code></sub>
</td>
</tr>
</table>
<!-- BLOG-POST-LIST:END -->

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Blog → Deep Dive                           ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="50" viewBox="0 0 1200 50" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 25 C300 5 600 45 900 25 S1200 5 1200 25 V50 H0 Z" fill="#111827" opacity="0.25"/>
  <line x1="0" y1="25" x2="1200" y2="25" stroke="url(#grad-fade-center)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  09 · EXPANDABLE SECTIONS                                     ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=7c3aed&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Deep+Dive" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-purple-cyan)"/></svg>
</div>

<br/>

<details>
<summary><b>🗂️ Dotfiles & Config</b></summary>
<br/>

<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Window frame -->
  <rect x="10%" y="0" width="80%" height="200" rx="10" fill="#111827" stroke="#1e293b" stroke-width="1"/>
  <!-- Title bar -->
  <rect x="10%" y="0" width="80%" height="28" rx="10" fill="#1e293b"/>
  <rect x="10%" y="18" width="80%" height="10" fill="#1e293b"/>
  <circle cx="calc(10% + 16)" cy="14" r="4" fill="#f85149"/>
  <circle cx="calc(10% + 30)" cy="14" r="4" fill="#e3b341"/>
  <circle cx="calc(10% + 44)" cy="14" r="4" fill="#3fb950"/>
  <text x="50%" y="18" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">dotfiles</text>

  <!-- Content -->
  <text x="12%" y="52" font-family="monospace" font-size="11" fill="#7c3aed">.zshrc</text>
  <text x="32%" y="52" font-family="monospace" font-size="11" fill="#8b949e">Zsh config + aliases</text>

  <text x="12%" y="74" font-family="monospace" font-size="11" fill="#7c3aed">.config/nvim</text>
  <text x="32%" y="74" font-family="monospace" font-size="11" fill="#8b949e">Neovim (LazyVim)</text>

  <text x="12%" y="96" font-family="monospace" font-size="11" fill="#7c3aed">.config/kitty</text>
  <text x="32%" y="96" font-family="monospace" font-size="11" fill="#8b949e">Kitty terminal</text>

  <text x="12%" y="118" font-family="monospace" font-size="11" fill="#7c3aed">.config/hypr</text>
  <text x="32%" y="118" font-family="monospace" font-size="11" fill="#8b949e">Hyprland WM</text>

  <text x="12%" y="140" font-family="monospace" font-size="11" fill="#7c3aed">.tmux.conf</text>
  <text x="32%" y="140" font-family="monospace" font-size="11" fill="#8b949e">Tmux config</text>

  <text x="12%" y="162" font-family="monospace" font-size="11" fill="#7c3aed">.gitconfig</text>
  <text x="32%" y="162" font-family="monospace" font-size="11" fill="#8b949e">Git aliases & settings</text>

  <!-- Cursor -->
  <rect x="12%" y="180" width="6" height="12" fill="#06b6d4" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite"/>
  </rect>
</svg>

<br/>
<!-- ██ EDIT: Link to your dotfiles repo ██ -->
<a href="https://github.com/Hishantik/dotfiles"><img src="https://img.shields.io/badge/View_Dotfiles-181717?style=flat&logo=github&logoColor=white" alt="dotfiles"/></a>

</details>

<br/>

<details>
<summary><b>🗺️ Learning Roadmap</b></summary>
<br/>

<!-- SVG Progress Tracker -->
<svg width="100%" height="260" xmlns="http://www.w3.org/2000/svg">
  <!-- Vertical line -->
  <line x1="30" y1="20" x2="30" y2="240" stroke="#1e293b" stroke-width="2"/>

  <!-- Completed items -->
  <circle cx="30" cy="20" r="6" fill="#22c55e"/>
  <path d="M27 20 L29 23 L34 17" fill="none" stroke="#0f172a" stroke-width="1.5"/>
  <text x="46" y="24" font-family="system-ui" font-size="12" fill="#e6edf3">JavaScript & TypeScript fundamentals</text>

  <circle cx="30" cy="50" r="6" fill="#22c55e"/>
  <path d="M27 50 L29 53 L34 47" fill="none" stroke="#0f172a" stroke-width="1.5"/>
  <text x="46" y="54" font-family="system-ui" font-size="12" fill="#e6edf3">React & Next.js</text>

  <circle cx="30" cy="80" r="6" fill="#22c55e"/>
  <path d="M27 80 L29 83 L34 77" fill="none" stroke="#0f172a" stroke-width="1.5"/>
  <text x="46" y="84" font-family="system-ui" font-size="12" fill="#e6edf3">Node.js & Express</text>

  <circle cx="30" cy="110" r="6" fill="#22c55e"/>
  <path d="M27 110 L29 113 L34 107" fill="none" stroke="#0f172a" stroke-width="1.5"/>
  <text x="46" y="114" font-family="system-ui" font-size="12" fill="#e6edf3">Docker & containerization</text>

  <circle cx="30" cy="140" r="6" fill="#22c55e"/>
  <path d="M27 140 L29 143 L34 137" fill="none" stroke="#0f172a" stroke-width="1.5"/>
  <text x="46" y="144" font-family="system-ui" font-size="12" fill="#e6edf3">Linux system administration</text>

  <!-- Pending items -->
  <circle cx="30" cy="170" r="6" fill="#1e293b" stroke="#7c3aed" stroke-width="1.5"/>
  <text x="46" y="174" font-family="system-ui" font-size="12" fill="#8b949e">Rust programming</text>

  <circle cx="30" cy="195" r="6" fill="#1e293b" stroke="#7c3aed" stroke-width="1.5"/>
  <text x="46" y="199" font-family="system-ui" font-size="12" fill="#8b949e">System design patterns</text>

  <circle cx="30" cy="220" r="6" fill="#1e293b" stroke="#7c3aed" stroke-width="1.5"/>
  <text x="46" y="224" font-family="system-ui" font-size="12" fill="#8b949e">Cloud architecture (AWS)</text>

  <circle cx="30" cy="245" r="6" fill="#1e293b" stroke="#7c3aed" stroke-width="1.5"/>
  <text x="46" y="249" font-family="system-ui" font-size="12" fill="#8b949e">WebAssembly & Kubernetes</text>
</svg>

</details>

<br/>

<details>
<summary><b>🏆 Open Source Contributions</b></summary>
<br/>

<!-- ██ EDIT: Add your open source contributions ██ -->
<sub>Contributions to various open-source projects in the Linux and web development ecosystem.</sub>

<br/><br/>

<a href="https://github.com/Hishantik"><img src="https://img.shields.io/badge/View_Contributions-181717?style=flat&logo=github&logoColor=white" alt="contributions"/></a>

</details>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  WAVE TRANSITION — Deep Dive → Connect                         ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<svg width="100%" height="60" viewBox="0 0 1200 60" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 30 Q300 0 600 30 T1200 30 V60 H0 Z" fill="#111827" opacity="0.3"/>
  <path d="M0 35 Q300 15 600 35 T1200 35 V60 H0 Z" fill="#111827" opacity="0.15"/>
  <line x1="0" y1="30" x2="1200" y2="30" stroke="url(#grad-full)" stroke-width="0.5"/>
</svg>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  10 · CONNECT & SUPPORT                                       ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Outfit&weight=600&size=24&pause=1000&color=ec4899&center=true&vCenter=true&repeat=false&width=300&height=40&lines=Let's+Connect" alt=""/>
<svg width="40" height="2" xmlns="http://www.w3.org/2000/svg"><rect width="40" height="2" rx="1" fill="url(#grad-cyan-pink)"/></svg>
</div>

<br/>

<!-- ██ EDIT: Replace all links with your actual URLs ██ -->
<div align="center">

<!-- SVG decorative frame -->
<svg width="500" height="10" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="5" x2="180" y2="5" stroke="#1e293b" stroke-width="0.5"/>
  <circle cx="190" cy="5" r="2" fill="#7c3aed" opacity="0.5"/>
  <circle cx="200" cy="5" r="2" fill="#06b6d4" opacity="0.5"/>
  <circle cx="210" cy="5" r="2" fill="#8b5cf6" opacity="0.5"/>
  <circle cx="220" cy="5" r="2" fill="#ec4899" opacity="0.5"/>
  <circle cx="230" cy="5" r="2" fill="#22c55e" opacity="0.5"/>
  <circle cx="240" cy="5" r="2" fill="#7c3aed" opacity="0.5"/>
  <circle cx="250" cy="5" r="2" fill="#06b6d4" opacity="0.5"/>
  <circle cx="260" cy="5" r="2" fill="#8b5cf6" opacity="0.5"/>
  <circle cx="270" cy="5" r="2" fill="#ec4899" opacity="0.5"/>
  <circle cx="280" cy="5" r="2" fill="#22c55e" opacity="0.5"/>
  <circle cx="290" cy="5" r="2" fill="#7c3aed" opacity="0.5"/>
  <circle cx="300" cy="5" r="2" fill="#06b6d4" opacity="0.5"/>
  <line x1="310" y1="5" x2="500" y2="5" stroke="#1e293b" stroke-width="0.5"/>
</svg>

<br/>

<!-- Primary -->
<a href="https://github.com/Hishantik"><img src="https://img.shields.io/badge/⭐_Star_Repos-181717?style=flat&logo=github&logoColor=white&labelColor=0f172a" alt=""/></a>
<a href="https://github.com/Hishantik?tab=followers"><img src="https://img.shields.io/badge/👥_Follow-7c3aed?style=flat&logo=github&logoColor=white&labelColor=0f172a" alt=""/></a>
<a href="https://twitter.com/sarkar_234"><img src="https://img.shields.io/badge/𝕏_Follow-000000?style=flat&logo=x&logoColor=white&labelColor=0f172a" alt=""/></a>

<br/>

<!-- Secondary -->
<a href="https://linkedin.com/in/"><img src="https://img.shields.io/badge/💼_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white&labelColor=0f172a" alt=""/></a>
<a href="mailto:hishantik@example.com"><img src="https://img.shields.io/badge/📧_Email-EA4335?style=flat&logo=gmail&logoColor=white&labelColor=0f172a" alt=""/></a>
<a href="https://dev.to/sarkar_234"><img src="https://img.shields.io/badge/📝_Blog-0A0A0A?style=flat&logo=dev.to&logoColor=white&labelColor=0f172a" alt=""/></a>

<br/>

<!-- Support -->
<a href="https://www.buymeacoffee.com/"><img src="https://img.shields.io/badge/☕_Buy_Me_A_Coffee-FFDD00?style=flat&logo=buymeacoffee&logoColor=black&labelColor=0f172a" alt=""/></a>
<a href="https://github.com/sponsors/Hishantik"><img src="https://img.shields.io/badge/💜_Sponsor-ec4899?style=flat&logo=github&logoColor=white&labelColor=0f172a" alt=""/></a>

<br/>

<!-- SVG decorative frame bottom -->
<svg width="500" height="10" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="5" x2="180" y2="5" stroke="#1e293b" stroke-width="0.5"/>
  <circle cx="250" cy="5" r="3" fill="none" stroke="url(#grad-purple-cyan)" stroke-width="1"/>
  <circle cx="250" cy="5" r="1" fill="#7c3aed"/>
  <line x1="310" y1="5" x2="500" y2="5" stroke="#1e293b" stroke-width="0.5"/>
</svg>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════ -->
<!-- ██  11 · FOOTER                                                  ██ -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<!-- SVG Wave Footer -->
<svg width="100%" height="80" viewBox="0 0 1200 80" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M0 40 Q200 0 400 40 T800 40 T1200 40 V80 H0 Z" fill="#111827" opacity="0.3"/>
  <path d="M0 45 Q200 10 400 45 T800 45 T1200 45 V80 H0 Z" fill="#111827" opacity="0.15"/>
  <path d="M0 50 Q200 20 400 50 T800 50 T1200 50 V80 H0 Z" fill="#111827" opacity="0.08"/>
  <line x1="0" y1="40" x2="1200" y2="40" stroke="url(#grad-full)" stroke-width="0.5"/>
</svg>

<div align="center">

<!-- Quote with SVG decoration -->
<svg width="400" height="60" xmlns="http://www.w3.org/2000/svg">
  <!-- Quote marks -->
  <text x="10" y="20" font-family="Georgia" font-size="28" fill="#7c3aed" opacity="0.4">"</text>
  <text x="370" y="50" font-family="Georgia" font-size="28" fill="#06b6d4" opacity="0.4">"</text>
  <!-- Quote text -->
  <text x="200" y="25" font-family="system-ui" font-size="14" font-weight="600" fill="#e6edf3" text-anchor="middle">Talk is cheap. Show me the code.</text>
  <text x="200" y="48" font-family="monospace" font-size="10" fill="#8b949e" text-anchor="middle">— Linus Torvalds</text>
</svg>

<br/>

<!-- Footer typing -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=400&size=13&pause=2000&color=6e7681&center=true&vCenter=true&multiline=true&repeat=true&width=500&height=50&lines=Thanks+for+visiting!;Let's+build+something+amazing+together+%F0%9F%9A%80" alt=""/>

<br/>

<sub>
Crafted with <code>❤️</code> by <b>Hishantik Sarkar</b> · <code>© 2026</code>
</sub>

<br/><br/>

<!-- Final gradient bar with glow -->
<svg width="90%" height="6" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="3" y="1.5" rx="1.5" fill="url(#grad-full)" opacity="0.8"/>
  <rect width="100%" height="6" y="0" rx="3" fill="url(#grad-full)" opacity="0.15" filter="url(#glow-md)"/>
</svg>

</div>

<!--
╔══════════════════════════════════════════════════════════════════╗
║                    CUSTOMIZATION GUIDE                           ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                 ║
║  Search "██ EDIT" to find all customizable sections.            ║
║                                                                 ║
║  1. Replace "Hishantik" with your GitHub username               ║
║  2. Update social links in Hero & Connect sections              ║
║  3. Replace REPO_NAME in Featured Projects                      ║
║  4. Update Dev Environment in System Diagnostics                ║
║  5. Update blog posts in Blog section                           ║
║  6. Update skill icons at skillicons.dev                        ║
║                                                                 ║
║  STATS THEMES: tokyonight · dracula · radical · algolia         ║
║                gruvbox · cobalt · nightowl · onedark            ║
║                                                                 ║
║  SERVICES USED:                                                 ║
║  • capsule-render (banners)                                     ║
║  • readme-typing-svg (typing animations)                        ║
║  • github-readme-stats (stats cards)                            ║
║  • github-readme-streak-stats (streak)                          ║
║  • github-profile-trophy (trophies)                             ║
║  • github-readme-activity-graph (activity)                      ║
║  • skillicons.dev (tech stack icons)                            ║
║  • komarev (visitor badge)                                      ║
║  • shields.io (badges)                                          ║
║  • dekutorem (spotify)                                          ║
║                                                                 ║
║  COLOR PALETTE:                                                 ║
║  Background:  #0f172a                                           ║
║  Card:        #111827                                           ║
║  Border:      #1e293b                                           ║
║  Purple:      #7c3aed                                           ║
║  Violet:      #8b5cf6                                           ║
║  Cyan:        #06b6d4                                           ║
║  Pink:        #ec4899                                           ║
║  Green:       #22c55e                                           ║
║                                                                 ║
║  GITHUB ACTIONS (recommended):                                  ║
║  • github-contribution-snake                                    ║
║  • waka-box                                                     ║
║  • blog-post-workflow                                           ║
║                                                                 ║
╚══════════════════════════════════════════════════════════════════╝
-->
