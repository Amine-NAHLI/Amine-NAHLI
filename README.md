<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1280 380" width="1280" height="380">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712"/>
      <stop offset="40%" stop-color="#0c0a1f"/>
      <stop offset="100%" stop-color="#1a0a2e"/>
    </linearGradient>
    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06b6d4"/>
      <stop offset="50%" stop-color="#6366f1"/>
      <stop offset="100%" stop-color="#a855f7"/>
    </linearGradient>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#6366f1" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#6366f1" stop-opacity="0"/>
    </radialGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#6366f1" stroke-width="0.4" opacity="0.25"/>
    </pattern>
    <pattern id="dots" width="20" height="20" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="0.8" fill="#06b6d4" opacity="0.3"/>
    </pattern>
    <filter id="glow-text" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background layers -->
  <rect width="1280" height="380" fill="url(#bg)"/>
  <rect width="1280" height="380" fill="url(#grid)"/>
  <rect width="1280" height="380" fill="url(#dots)"/>

  <!-- Glow orbs -->
  <circle cx="200" cy="120" r="280" fill="url(#glow)"/>
  <circle cx="1080" cy="280" r="320" fill="url(#glow)" opacity="0.6"/>

  <!-- Top status bar -->
  <line x1="0" y1="42" x2="1280" y2="42" stroke="#6366f1" stroke-width="1" opacity="0.4"/>
  <text x="40" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#06b6d4" letter-spacing="2">● SYSTEM ONLINE</text>
  <text x="200" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="2">SESSION: amine.nahli</text>
  <text x="420" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="2">NODE: fes-mar-01</text>
  <text x="600" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="2">UPTIME: 1247d</text>
  <text x="780" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#22c55e" letter-spacing="2">▲ STATUS: AVAILABLE</text>
  <text x="1010" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="2">SEC LVL: ████░ 85%</text>
  <text x="1200" y="28" font-family="JetBrains Mono, monospace" font-size="11" fill="#06b6d4" letter-spacing="2">v3.0</text>

  <!-- Bottom status bar -->
  <line x1="0" y1="338" x2="1280" y2="338" stroke="#6366f1" stroke-width="1" opacity="0.4"/>
  <text x="40" y="358" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="3">[ SECURITY ENGINEER ]</text>
  <text x="280" y="358" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="3">[ FULL-STACK BUILDER ]</text>
  <text x="540" y="358" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="3">[ AI / VISION ENGINEER ]</text>
  <text x="820" y="358" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="3">[ UPF FÈS · 3RD YEAR ]</text>
  <text x="1080" y="358" font-family="JetBrains Mono, monospace" font-size="11" fill="#94a3b8" letter-spacing="3">[ MOROCCO · 2026 ]</text>

  <!-- Decorative corner brackets -->
  <g stroke="#06b6d4" stroke-width="2" fill="none" opacity="0.7">
    <path d="M 30 70 L 30 100 L 60 100"/>
    <path d="M 1250 70 L 1250 100 L 1220 100"/>
    <path d="M 30 310 L 30 280 L 60 280"/>
    <path d="M 1250 310 L 1250 280 L 1220 280"/>
  </g>

  <!-- Main name -->
  <text x="640" y="180" text-anchor="middle" font-family="JetBrains Mono, monospace" font-weight="800" font-size="92" fill="url(#accent)" letter-spacing="6" filter="url(#glow-text)">AMINE NAHLI</text>

  <!-- Subtitle line -->
  <line x1="380" y1="210" x2="900" y2="210" stroke="url(#accent)" stroke-width="1" opacity="0.6"/>

  <!-- Subtitle -->
  <text x="640" y="245" text-anchor="middle" font-family="JetBrains Mono, monospace" font-weight="500" font-size="18" fill="#e2e8f0" letter-spacing="4">I BREAK THINGS TO UNDERSTAND THEM</text>
  <text x="640" y="275" text-anchor="middle" font-family="JetBrains Mono, monospace" font-weight="500" font-size="18" fill="#06b6d4" letter-spacing="4">THEN I BUILD BETTER ONES</text>

  <!-- Decorative side text -->
  <text x="50" y="195" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0x01</text>
  <text x="50" y="210" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0x02</text>
  <text x="50" y="225" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0x03</text>
  <text x="1210" y="195" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0xAA</text>
  <text x="1210" y="210" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0xBB</text>
  <text x="1210" y="225" font-family="JetBrains Mono, monospace" font-size="10" fill="#6366f1" opacity="0.6" letter-spacing="2">0xCC</text>
</svg>
