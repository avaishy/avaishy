<svg width="800" height="500" viewBox="0 0 800 500" xmlns="http://www.w3.org/2000/svg">
    <!-- Sky Background -->
    <defs>
        <linearGradient id="skyGradient" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#87CEEB"/> <!-- Light Blue -->
            <stop offset="100%" stop-color="#B0E0E6"/> <!-- Pale Turquoise -->
        </linearGradient>
    </defs>
    <rect width="100%" height="100%" fill="url(#skyGradient)"/>

    <!-- Sun -->
    <circle cx="120" cy="80" r="40" fill="#FFD700"/>

    <!-- Clouds -->
    <g fill="#FFFFFF">
        <ellipse cx="200" cy="90" rx="50" ry="30"/>
        <ellipse cx="250" cy="80" rx="40" ry="25"/>
        <ellipse cx="230" cy="100" rx="45" ry="25"/>
    </g>

    <!-- Ground -->
    <rect x="0" y="400" width="800" height="100" fill="#4CAF50"/>

    <!-- Cooling Towers -->
    <polygon points="150,350 180,250 210,350" fill="#8D8D8D" stroke="#5A5A5A" stroke-width="3"/>
    <polygon points="220,350 250,230 280,350" fill="#8D8D8D" stroke="#5A5A5A" stroke-width="3"/>

    <!-- Factory Building -->
    <rect x="300" y="280" width="220" height="120" fill="#3F51B5" stroke="#2C3E50" stroke-width="3"/>
    <rect x="310" y="290" width="50" height="60" fill="#FFC107"/>
    <rect x="370" y="290" width="50" height="60" fill="#FFC107"/>
    <rect x="430" y="290" width="50" height="60" fill="#FFC107"/>

    <!-- Chimneys -->
    <rect x="320" y="180" width="30" height="100" fill="#795548"/>
    <rect x="380" y="150" width="30" height="130" fill="#795548"/>
    <rect x="440" y="170" width="30" height="110" fill="#795548"/>

    <!-- Smoke -->
    <g fill="#BDBDBD">
        <circle cx="335" cy="160" r="20"/>
        <circle cx="390" cy="120" r="25"/>
        <circle cx="450" cy="130" r="22"/>
    </g>

    <!-- Pipelines -->
    <rect x="200" y="350" width="100" height="20" fill="#9E9E9E"/>
    <rect x="300" y="350" width="20" height="50" fill="#9E9E9E"/>
    <rect x="500" y="350" width="100" height="20" fill="#9E9E9E"/>

    <!-- Electric Towers -->
    <polygon points="600,350 640,250 680,350" fill="#8D8D8D" stroke="#5A5A5A" stroke-width="3"/>
    <polygon points="700,350 740,230 780,350" fill="#8D8D8D" stroke="#5A5A5A" stroke-width="3"/>
    
</svg>
