## 📡 LIVE VOIP DASHBOARD (REAL-TIME FLOW)

<p align="center">

<svg width="820" height="260" viewBox="0 0 820 260" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->
  <rect width="100%" height="100%" fill="#000000"/>

  <!-- SIP PATH (Green) -->
  <path id="sipPath" d="M 100 90 L 700 90" stroke="#00FF00" stroke-width="2" fill="none"/>

  <!-- RTP PATH (Blue) -->
  <path id="rtpPath" d="M 100 170 L 700 170" stroke="#00AEEF" stroke-width="2" fill="none"/>

  <!-- FAILOVER PATH (Red dashed) -->
  <path id="failPath" d="M 350 90 L 350 170" stroke="#FF0000" stroke-width="2" stroke-dasharray="6,4" fill="none"/>

  <!-- NODES -->
  <!-- SIP TRUNK -->
  <rect x="40" y="60" width="120" height="40" rx="8" fill="#00FF00"/>
  <text x="55" y="85" fill="#000">SIP TRUNK</text>

  <!-- SBC -->
  <rect x="200" y="60" width="120" height="40" rx="8" fill="#00FF00"/>
  <text x="235" y="85" fill="#000">SBC</text>

  <!-- KAMAILIO -->
  <rect x="360" y="60" width="120" height="40" rx="8" fill="#00FF00"/>
  <text x="370" y="85" fill="#000">KAMAILIO</text>

  <!-- ASTERISK -->
  <rect x="520" y="60" width="120" height="40" rx="8" fill="#00FF00"/>
  <text x="530" y="85" fill="#000">ASTERISK</text>

  <!-- AGENT -->
  <rect x="680" y="60" width="120" height="40" rx="8" fill="#00FF00"/>
  <text x="705" y="85" fill="#000">AGENT</text>

  <!-- RTP LABELS -->
  <text x="60" y="190" fill="#00AEEF">RTP STREAM</text>

  <!-- SIP PACKET -->
  <circle r="5" fill="#00FF00">
    <animateMotion dur="3s" repeatCount="indefinite">
      <mpath href="#sipPath"/>
    </animateMotion>
  </circle>

  <!-- RTP PACKET -->
  <circle r="5" fill="#00AEEF">
    <animateMotion dur="2s" repeatCount="indefinite">
      <mpath href="#rtpPath"/>
    </animateMotion>
  </circle>

  <!-- FAILOVER PACKET -->
  <circle r="5" fill="#FF0000">
    <animateMotion dur="4s" repeatCount="indefinite">
      <mpath href="#failPath"/>
    </animateMotion>
  </circle>

</svg>

</p>
