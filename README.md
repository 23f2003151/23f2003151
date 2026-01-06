<svg width="100%" height="160" viewBox="0 0 1000 160" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#ff00cc"/>
      <stop offset="50%" stop-color="#00ffff"/>
      <stop offset="100%" stop-color="#ffcc00"/>
    </linearGradient>

    <filter id="glitch">
      <feOffset dx="2" dy="0" result="off1"/>
      <feOffset dx="-2" dy="0" result="off2"/>
      <feBlend in="off1" in2="off2" mode="screen"/>
    </filter>
  </defs>

  <rect width="100%" height="100%" rx="18" fill="#8e44ad"/>

  <!-- Main text -->
  <text
    x="50%"
    y="55%"
    text-anchor="middle"
    dominant-baseline="middle"
    font-size="56"
    font-family="Arial, Helvetica, sans-serif"
    fill="url(#grad)"
    filter="url(#glitch)"
  >
    Hey, I'm Anuj!
    <animate
      attributeName="x"
      from="50%"
      to="49.6%"
      dur="0.08s"
      repeatCount="indefinite"
    />
  </text>

  <!-- Cyan glitch layer -->
  <text
    x="50%"
    y="55%"
    text-anchor="middle"
    dominant-baseline="middle"
    font-size="56"
    font-family="Arial, Helvetica,
