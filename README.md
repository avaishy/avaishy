 <svg width="400" height="250" viewBox="0 0 400 250" xmlns="http://www.w3.org/2000/svg">
        {/* Background Gradient */}
        <defs>
         <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
           <stop offset="0%" style={{stopColor:" #0f2027", stopOpacity:1}} />
           <stop offset="50%" style={{stopColor: " #203a43", stopOpacity:1 }}/>
           <stop offset="100%" style={{stopColor:" #2c5364", stopOpacity:1}} />
         </linearGradient>

         <filter id="glow">
           <feGaussianBlur stdDeviation="3" rsult="blured" />
           <feMerge>
             <feMergeNode in="blurred" />
             <feMergeNode in="sourceGraphic" />
           </feMerge>
         </filter>
         </defs>
         <rect width="400" height="250" rx="20" fill="url(#bgGradient)" />
         <g filter="url(#glow)" fill=" #29b6f6" opacity="0.9">
         <rect x="80" y="140" width="20" height="60" />
         <rect x="120" y="100" width="20" height="100" />
         <rect x="160" y="120" width="20" height="80" />
         <rect x="200" y="80" width="20" height="120" />
         <rect x="240" y="60" width="20" height="140" />
        
         </g>
         <polyline
             point="80,170,120,160,140,200,90,240,70"
             stroke="ff9800"
             stokeWidth="4"
             fill="none"
             filter="url(#glow)"
             />
        
         
         </svg>
