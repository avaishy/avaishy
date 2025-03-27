<svg width="400" height="250" viewBox="0 0 400 250" xmlns="http://www.w3.org/2000/svg">
  
  <!-- Background Gradient -->
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1e3c72"/>
      <stop offset="100%" stop-color="rgb(42, 74, 129)"/>
    </linearGradient>

    <!-- Glow effect -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="blurred"/>
      <feMerge>
        <feMergeNode in="blurred"/>
        <feMergeNode in="sourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="400" height="250" rx="20" fill="url(#bgGradient)"/>

  <!-- Factory Icon -->
  <g filter="url(#glow)" fill="#fff" opacity="0.9">
    
    <!-- Factory Base -->
    <rect x="90" y="130" width="140" height="50" rx="5"/>
    
    <!-- Roof (Zigzag) -->
    <polygon points="90,130 120,110 130,130 150,110 160,130 180,110 210,130"/>

    <!-- Chimney -->
    <rect x="175" y="90" width="20" height="40" rx="3"/>

    <!-- Smoke (Three circles) -->
    <circle cx="185" cy="78" r="8"/>
    <circle cx="180" cy="65" r="6"/>
    <circle cx="176" cy="55" r="5"/>

    <!-- Factory Windows -->
    <rect x="100" y="140" width="20" height="20" rx="3"/>
    <rect x="130" y="140" width="20" height="20" rx="3"/>
    <rect x="160" y="140" width="20" height="20" rx="3"/>
    <rect x="190" y="140" width="20" height="20" rx="3"/>
    
    <!-- Side Pipes (Industrial Look) -->
    <rect x="230" y="135" width="10" height="30" rx="3"/>
    <rect x="250" y="125" width="10" height="40" rx="3"/>
  </g>

</svg>
