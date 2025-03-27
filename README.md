<svg width="400" height="250" viewBox="0 0 400 250" xmlns="http://www.w3.org/2000/svg">
  
  <!-- Background Gradient -->
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e3c72" stop-opacity="1"/>
      <stop offset="100%" stop-color="rgb(42, 74, 129)" stop-opacity="1"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blurred"/>
      <feMerge>
        <feMergeNode in="blurred"/>
        <feMergeNode in="sourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="400" height="250" rx="20" fill="url(#bgGradient)"/>

  <!-- Factory Outline -->
  <g filter="url(#glow)" fill="#fff" opacity="0.9">
    <!-- Factory Building -->
    <rect x="100" y="120" width="120" height="60" rx="5"/>
    
    <!-- Zigzag Roof -->
    <polygon points="100,120 130,100 140,120 160,100 170,120 190,100 220,120" />

    <!-- Chimney -->
    <rect x="190" y="80" width="15" height="40" rx="3"/>

    <!-- Smoke -->
    <circle cx="197" cy="70" r="8"/>
    <circle cx="193" cy="58" r="6"/>
    <circle cx="190" cy="48" r="5"/>

    <!-- Windows -->
    <rect x="110" y="135" width="20" height="20" rx="3"/>
    <rect x="140" y="135" width="20" height="20" rx="3"/>
    <rect x="170" y="135" width="20" height="20" rx="3"/>
    <rect x="200" y="135" width="20" height="20" rx="3"/>
  </g>
</svg>
