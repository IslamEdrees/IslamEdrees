## 📡 LIVE VOIP TRAFFIC

<p align="center">

<svg width="700" height="220" viewBox="0 0 700 220" xmlns="http://www.w3.org/2000/svg">

  <!-- Nodes -->
  <rect x="20" y="80" width="120" height="50" rx="10" fill="#0f0"/>
  <text x="40" y="110" fill="black">SIP TRUNK</text>

  <rect x="180" y="80" width="120" height="50" rx="10" fill="#0f0"/>
  <text x="200" y="110" fill="black">SBC</text>

  <rect x="340" y="80" width="120" height="50" rx="10" fill="#0f0"/>
  <text x="350" y="110" fill="black">KAMAILIO</text>

  <rect x="500" y="80" width="120" height="50" rx="10" fill="#0f0"/>
  <text x="510" y="110" fill="black">ASTERISK</text>

  <!-- Lines -->
  <line x1="140" y1="105" x2="180" y2="105" stroke="#0f0" stroke-width="2"/>
  <line x1="300" y1="105" x2="340" y2="105" stroke="#0f0" stroke-width="2"/>
  <line x1="460" y1="105" x2="500" y2="105" stroke="#0f0" stroke-width="2"/>

  <!-- Moving Packet -->
  <circle r="6" fill="red">
    <animateMotion dur="3s" repeatCount="indefinite">
      <mpath href="#path"/>
    </animateMotion>
  </circle>

  <path id="path" d="M 80 105 L 560 105" fill="none"/>

</svg>

</p>
