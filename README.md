<svg width="560" height="80" xmlns="http://www.w3.org/2000/svg">
  <style>
    .text {
      font-family: 'Georgia', serif;
      font-size: 42px;
      font-weight: 300;
      fill: #1a1714;
      letter-spacing: 0.3em;
    }
    .sub {
      font-family: 'Courier New', monospace;
      font-size: 13px;
      fill: #9a9087;
      letter-spacing: 0.15em;
    }
    .cursor {
      fill: #c9a99a;
      animation: blink 1s step-end infinite;
    }
    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }
 
    .char { opacity: 0; }
    .c1  { animation: appear 0.1s 0.3s forwards; }
    .c2  { animation: appear 0.1s 0.5s forwards; }
    .c3  { animation: appear 0.1s 0.7s forwards; }
    .c4  { animation: appear 0.1s 0.9s forwards; }
    .c5  { animation: appear 0.1s 1.1s forwards; }
 
    .sub-text { opacity: 0; animation: fadein 0.8s 1.8s forwards; }
 
    @keyframes appear { to { opacity: 1; } }
    @keyframes fadein { to { opacity: 1; } }
  </style>
 
  <rect width="560" height="80" fill="#f9f6f1" rx="8"/>
 
  <text y="52" x="28">
    <tspan class="text char c1">k</tspan><tspan class="text char c2">y</tspan><tspan class="text char c3">o</tspan><tspan class="text char c4">m</tspan><tspan class="text char c5">i</tspan>
    <tspan class="cursor" font-size="38" dy="2"> |</tspan>
  </text>
 
  <text x="30" y="72" class="sub sub-text">pure beauty, found in simple things.</text>
</svg>
 
