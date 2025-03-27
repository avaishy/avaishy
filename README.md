<svg width="400" height="250" viewBox="0 0 400 250" xmlns="http://www.w3.org/2000/svg">

    {/* Background Gradient */}
    <defs>
         <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
           <stop offset="0%" style={{stopColor:" #1e3c72", stopOpacity:1}} />
           <stop offset="100%" style={{stopColor: "rgb(42, 74, 129)", stopOpacity:1 }}/>
         </linearGradient>

         <filter id="glow">
           {/* <feGaussianBlur stdDeviation="3" rsult="blured" /> */}
           <feMerge>
             <feMergeNode in="blurred" />
             <feMergeNode in="sourceGraphic" />
           </feMerge>
         </filter>
         </defs>
         <rect width="400" height="250" rx="20" fill="url(#bgGradient)" />
    
    <rect x="10" y="50" width="80" height="30" fill=" #ffffff" stroke="#000" stroke-width="2"/>
    

    <polygon points="10,50 30,40 40,50 60,40 70,50 90,40 90,50" fill="#ffffff" stroke="#000" stroke-width="2"/>
    
    <rect x="70" y="25" width="10" height="25" fill="#ffffff" stroke="#000" stroke-width="2"/>
    

    <circle cx="75" cy="20" r="5" fill="#ffffff"/>
    <circle cx="72" cy="15" r="4" fill="#ffffff"/>
    <circle cx="70" cy="10" r="3" fill="#ffffff"/>
    
    <rect x="15" y="60" width="10" height="10" fill="#1e3c72" stroke="#000" stroke-width="2"/>
    <rect x="35" y="60" width="10" height="10" fill="#1e3c72" stroke="#000" stroke-width="2"/>
    <rect x="55" y="60" width="10" height="10" fill="#1e3c72" stroke="#000" stroke-width="2"/>
    <rect x="75" y="60" width="10" height="10" fill="#1e3c72" stroke="#000" stroke-width="2"/>
  </svg>

  ------------------------
   <svg width="400" height="250" viewBox="0 0 400 250" xmlns="http://www.w3.org/2000/svg">
        {/* Background Gradient */}
        <defs>
         <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
           <stop offset="0%" style={{stopColor:" #1e3c72", stopOpacity:1}} />
           <stop offset="100%" style={{stopColor: "rgb(42, 74, 129)", stopOpacity:1 }}/>
         </linearGradient>

         <filter id="glow">
           {/* <feGaussianBlur stdDeviation="3" rsult="blured" /> */}
           <feMerge>
             <feMergeNode in="blurred" />
             <feMergeNode in="sourceGraphic" />
           </feMerge>
         </filter>
         </defs>
         <rect width="400" height="250" rx="20" fill="url(#bgGradient)" />

         
          {/* MicroPhone Icon */}
          <g filter="url(#glow)" fill=" #fff" opacity="0.9">
         <circle cx="200" cy="100" r="35" />
         <rect x="185" y="130" width="30" height="60" rx="10" />
         <line x1="200" y1="190"  x2="200" y2="220" stroke=" #fff" strokeWidth="6" strokeLinecap="round" />
         </g>
         </svg>
