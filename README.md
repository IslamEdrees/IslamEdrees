## 📡 LIVE VOIP DASHBOARD

<p align="center">

<svg width="800" height="220"
     xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink">

  <!-- Background -->
  <rect width="100%" height="100%" fill="#000"/>

  <!-- PATH -->
  <path id="sipPath" d="M 100 110 L 700 110"
        stroke="#00FF00" stroke-width="2" fill="none"/>

  <!-- NODES -->
  <text x="90" y="90" fill="#00FF00">SIP</text>
  <text x="250" y="90" fill="#00FF00">SBC</text>
  <text x="400" y="90" fill="#00FF00">KAM</text>
  <text x="550" y="90" fill="#00FF00">AST</text>
  <text x="700" y="90" fill="#00FF00">AGENT</text>

  <!-- MOVING DOT -->
  <circle r="6" fill="#00FF00">
    <animateMotion dur="3s" repeatCount="indefinite">
      <mpath xlink:href="#sipPath"/>
    </animateMotion>
  </circle>

</svg>

</p>
