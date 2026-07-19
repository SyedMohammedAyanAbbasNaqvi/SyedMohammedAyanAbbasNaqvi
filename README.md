<svg width="1536" height="960" viewBox="0 0 1536 960" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" font-family="'Courier New', 'JetBrains Mono', monospace">

  <defs>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <linearGradient id="lineFade" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#00F0FF" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#00F0FF" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="chipFade" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0F1730"/>
      <stop offset="100%" stop-color="#0A0E27"/>
    </linearGradient>

    <clipPath id="imgClip">
      <rect x="632" y="80" width="880" height="500" rx="14"/>
    </clipPath>
  </defs>

  <!-- BACKGROUND -->
  <rect x="0" y="0" width="1536" height="960" fill="#05070F"/>

  <!-- HEADER -->
  <text x="40" y="52" fill="#00F0FF" font-size="26" font-weight="700" filter="url(#glow)">&lt;/&gt;</text>
  <text x="80" y="52" fill="#F1F5FF" font-size="26" font-weight="700" letter-spacing="2">ABOUT ME</text>
  <rect x="330" y="40" width="1166" height="2" fill="url(#lineFade)"/>

  <!-- LEFT IDENTITY CARD -->
  <rect x="24" y="80" width="580" height="500" rx="14" fill="#080B1A" stroke="#00F0FF" stroke-width="1.5" filter="url(#glow)"/>

  <!-- field rows: icon, label, value -->
  <g font-size="17" fill="#DCE6F5">
    <text x="52" y="126" font-size="18">👤</text>
    <text x="88" y="126" fill="#7FDBFF">Name</text>
    <text x="200" y="126">: Ayan Abbas</text>

    <text x="52" y="160" font-size="18">📍</text>
    <text x="88" y="160" fill="#7FDBFF">Location</text>
    <text x="200" y="160">: Lucknow, India</text>

    <text x="52" y="194" font-size="18">💼</text>
    <text x="88" y="194" fill="#7FDBFF">Role</text>
    <text x="200" y="194">: Full Stack Developer</text>

    <text x="52" y="228" font-size="18">🔷</text>
    <text x="88" y="228" fill="#7FDBFF">Focus</text>
    <text x="200" y="228">:</text>
    <text x="220" y="228" fill="#9FB3D1">▹ Interactive Web Experiences</text>
    <text x="220" y="252" fill="#9FB3D1">▹ Frontend Engineering</text>
    <text x="220" y="276" fill="#9FB3D1">▹ 3D Interfaces</text>
    <text x="220" y="300" fill="#9FB3D1">▹ Cybersecurity</text>
    <text x="220" y="324" fill="#9FB3D1">▹ Artificial Intelligence</text>

    <text x="52" y="368" font-size="18">🚀</text>
    <text x="88" y="368" fill="#7FDBFF">Currently Building :</text>
    <text x="220" y="392" fill="#9FB3D1">▹ Client Projects</text>
    <text x="220" y="416" fill="#9FB3D1">▹ Interactive Portfolio</text>
    <text x="220" y="440" fill="#9FB3D1">▹ AI Automation Tools</text>

    <text x="52" y="484" font-size="18">📖</text>
    <text x="88" y="484" fill="#7FDBFF">Currently Learning :</text>
    <text x="220" y="508" fill="#9FB3D1">▹ Next.js</text>
    <text x="220" y="532" fill="#9FB3D1">▹ Spring Boot</text>
    <text x="220" y="556" fill="#9FB3D1">▹ Threat Intelligence</text>
  </g>

  <!-- vertical connector dots on far left -->
  <line x1="30" y1="100" x2="30" y2="560" stroke="#123" stroke-width="2" stroke-dasharray="2,6"/>

  <!-- RIGHT IMAGE CARD -->
  <rect x="628" y="76" width="888" height="508" rx="14" fill="#080B1A" stroke="#00F0FF" stroke-width="1.5" filter="url(#glow)"/>
  <image href="assets/watched-bg.png" x="632" y="80" width="880" height="500" preserveAspectRatio="xMidYMid slice" clip-path="url(#imgClip)"/>
  <!-- subtle darken overlay so text stays legible -->
  <rect x="632" y="80" width="880" height="500" fill="#000000" opacity="0.12" clip-path="url(#imgClip)"/>

  <!-- STAT CARDS -->
  <g>
    <!-- card template positions -->
    <rect x="24" y="604" width="365" height="90" rx="10" fill="#080B1A" stroke="#123B4A" stroke-width="1.5"/>
    <rect x="410" y="604" width="365" height="90" rx="10" fill="#080B1A" stroke="#123B4A" stroke-width="1.5"/>
    <rect x="796" y="604" width="365" height="90" rx="10" fill="#080B1A" stroke="#123B4A" stroke-width="1.5"/>
    <rect x="1182" y="604" width="330" height="90" rx="10" fill="#080B1A" stroke="#123B4A" stroke-width="1.5"/>

    <text x="52" y="640" font-size="22">👁️</text>
    <text x="90" y="638" fill="#9FB3D1" font-size="14" letter-spacing="1">PROFILE VIEWS</text>
    <text x="90" y="668" fill="#F1F5FF" font-size="26" font-weight="700">8.2K+</text>

    <text x="438" y="640" font-size="22">👥</text>
    <text x="476" y="638" fill="#9FB3D1" font-size="14" letter-spacing="1">FOLLOWERS</text>
    <text x="476" y="668" fill="#F1F5FF" font-size="26" font-weight="700">1.2K+</text>

    <text x="824" y="640" font-size="22" fill="#FFD84D">★</text>
    <text x="862" y="638" fill="#9FB3D1" font-size="14" letter-spacing="1">TOTAL STARS</text>
    <text x="862" y="668" fill="#F1F5FF" font-size="26" font-weight="700">250+</text>

    <text x="1210" y="640" font-size="22">📈</text>
    <text x="1248" y="638" fill="#9FB3D1" font-size="14" letter-spacing="1">TOTAL COMMITS</text>
    <text x="1248" y="668" fill="#F1F5FF" font-size="26" font-weight="700">2.1K+</text>
  </g>

  <!-- TECH STACK HEADER -->
  <text x="40" y="740" fill="#00F0FF" font-size="22" font-weight="700" filter="url(#glow)">&lt;/&gt;</text>
  <text x="78" y="740" fill="#F1F5FF" font-size="22" font-weight="700" letter-spacing="2">TECH STACK</text>
  <rect x="290" y="728" width="1206" height="2" fill="url(#lineFade)"/>

  <!-- TECH CHIPS ROW (16 chips) -->
  <g font-size="12" fill="#DCE6F5" text-anchor="middle">
    <!-- generated grid: 16 chips, 88px pitch starting x=40 -->
    <!-- chip 1: React -->
    <g transform="translate(40,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="24" fill="#61DAFB" text-anchor="middle">⚛</text>
      <text x="40" y="66" text-anchor="middle">React</text>
    </g>
    <!-- chip 2: Next.js -->
    <g transform="translate(128,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#FFFFFF" text-anchor="middle">▲</text>
      <text x="40" y="66" text-anchor="middle">Next.js</text>
    </g>
    <!-- chip 3: JavaScript -->
    <g transform="translate(216,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="18" fill="#F0DB4F" text-anchor="middle" font-weight="700">JS</text>
      <text x="40" y="66" text-anchor="middle">JavaScript</text>
    </g>
    <!-- chip 4: TypeScript -->
    <g transform="translate(304,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="18" fill="#3178C6" text-anchor="middle" font-weight="700">TS</text>
      <text x="40" y="66" text-anchor="middle">TypeScript</text>
    </g>
    <!-- chip 5: Node.js -->
    <g transform="translate(392,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#68A063" text-anchor="middle">⬡</text>
      <text x="40" y="66" text-anchor="middle">Node.js</text>
    </g>
    <!-- chip 6: Express -->
    <g transform="translate(480,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="18" fill="#FFFFFF" text-anchor="middle" font-weight="700">Ex</text>
      <text x="40" y="66" text-anchor="middle">Express</text>
    </g>
    <!-- chip 7: MongoDB -->
    <g transform="translate(568,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#4DB33D" text-anchor="middle">🍃</text>
      <text x="40" y="66" text-anchor="middle">MongoDB</text>
    </g>
    <!-- chip 8: Java -->
    <g transform="translate(656,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#E76F00" text-anchor="middle">☕</text>
      <text x="40" y="66" text-anchor="middle">Java</text>
    </g>
    <!-- chip 9: Spring Boot -->
    <g transform="translate(744,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#6DB33F" text-anchor="middle">🌱</text>
      <text x="40" y="66" text-anchor="middle">Spring</text>
    </g>
    <!-- chip 10: Python -->
    <g transform="translate(832,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="22" fill="#4B8BBE" text-anchor="middle">🐍</text>
      <text x="40" y="66" text-anchor="middle">Python</text>
    </g>
    <!-- chip 11: Tailwind -->
    <g transform="translate(920,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#38BDF8" text-anchor="middle">〜</text>
      <text x="40" y="66" text-anchor="middle">Tailwind</text>
    </g>
    <!-- chip 12: Three.js -->
    <g transform="translate(1008,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#FFFFFF" text-anchor="middle">△</text>
      <text x="40" y="66" text-anchor="middle">Three.js</text>
    </g>
    <!-- chip 13: Git -->
    <g transform="translate(1096,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#F05033" text-anchor="middle">⎇</text>
      <text x="40" y="66" text-anchor="middle">Git</text>
    </g>
    <!-- chip 14: GitHub -->
    <g transform="translate(1184,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#FFFFFF" text-anchor="middle">🐙</text>
      <text x="40" y="66" text-anchor="middle">GitHub</text>
    </g>
    <!-- chip 15: VS Code -->
    <g transform="translate(1272,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#007ACC" text-anchor="middle">🧰</text>
      <text x="40" y="66" text-anchor="middle">VS Code</text>
    </g>
    <!-- chip 16: Linux -->
    <g transform="translate(1360,764)">
      <rect width="80" height="80" rx="10" fill="url(#chipFade)" stroke="#1B2A4A"/>
      <text x="40" y="40" font-size="20" fill="#FCC624" text-anchor="middle">🐧</text>
      <text x="40" y="66" text-anchor="middle">Linux</text>
    </g>
  </g>

  <!-- QUOTE BAR -->
  <rect x="24" y="880" width="1488" height="60" rx="10" fill="#080B1A" stroke="#1B2A4A" stroke-width="1.5"/>
  <text x="60" y="917" fill="#00F0FF" font-size="26" font-weight="700">&#8220;</text>
  <text x="768" y="917" fill="#DCE6F5" font-size="16" text-anchor="middle" font-style="italic">I don't just build websites. I build experiences that people remember.</text>
  <text x="1476" y="917" fill="#00F0FF" font-size="26" font-weight="700" text-anchor="end">&#8221;</text>

</svg>
