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

  <!-- Balance Base -->
  <polygon points="190,200,210,200,200,230" fill="rgba(255,255,255,0.8)"/>

  <!-- Balance Beam -->
  <polygon points="80,170,320,170,200,200,80,170" fill="rgba(255,255,255,0.7)"/>

  <!-- Left Cube -->
  <polygon points="90,120,130,100,170,120,130,140" fill="rgba(255,255,255,0.9)"/>
  <polygon points="130,100,130,140,170,120,170,80" fill="rgba(255,255,255,0.8)"/>
  <polygon points="90,120,130,140,130,100,90,80" fill="rgba(255,255,255,0.6)"/>

  <!-- Right-Bottom Cube -->
  <polygon points="230,140,270,120,310,140,270,160" fill="rgba(255,255,255,0.9)"/>
  <polygon points="270,120,270,160,310,140,310,100" fill="rgba(255,255,255,0.8)"/>
  <polygon points="230,140,270,160,270,120,230,100" fill="rgba(255,255,255,0.6)"/>

  <!-- Right-Middle Cube -->
  <polygon points="230,100,270,80,310,100,270,120" fill="rgba(255,255,255,0.9)"/>
  <polygon points="270,80,270,120,310,100,310,60" fill="rgba(255,255,255,0.8)"/>
  <polygon points="230,100,270,120,270,80,230,60" fill="rgba(255,255,255,0.6)"/>

  <!-- Right-Top Cube -->
  <polygon points="230,60,270,40,310,60,270,80" fill="rgba(255,255,255,0.9)"/>
  <polygon points="270,40,270,80,310,60,310,20" fill="rgba(255,255,255,0.8)"/>
  <polygon points="230,60,270,80,270,40,230,20" fill="rgba(255,255,255,0.6)"/>

</svg>
