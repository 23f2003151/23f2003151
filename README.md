<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="160" viewBox="0 0 1000 160">
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#ff00cc"/>
      <stop offset="50%" stop-color="#00ffff"/>
      <stop offset="100%" stop-color="#ffcc00"/>
    </linearGradient>
  </defs>

  <rect width="100%" height="100%" rx="20" fill="#8e44ad"/>

  <!-- Main text -->
  <text x="50%" y="55%" text-anchor="middle" dominant-baseline="middle"
        font-size="56" font-family="Arial, Helvetica, sans-serif"
        fill="url(#grad)">
    Hey, I'm Anuj!
    <animate attributeName="x"
             values="50%;49.6%;50%"
             dur="0.12s"
             repeatCount="indefinite"/>
  </text>

  <!-- Cyan glitch -->
  <text x="50%" y="55%" text-anchor="middle" dominant-baseline="middle"
        font-size="56" font-family="Arial, Helvetica, sans-serif"
        fill="#00ffff" opacity="0.4">
    Hey, I'm Anuj!
    <animateTransform attributeName="transform"
                      type="translate"
                      values="0 0;-3 -2;0 0"
                      dur="0.15s"
                      repeatCount="indefinite"/>
  </text>

  <!-- Red glitch -->
  <text x="50%" y="55%" text-anchor="middle" dominant-baseline="middle"
        font-size="56" font-family="Arial, Helvetica, sans-serif"
        fill="#ff0044" opacity="0.4">
    Hey, I'm Anuj!
    <animateTransform attributeName="transform"
                      type="translate"
                      values="0 0;3 2;0 0"
                      dur="0.15s"
                      repeatCount="indefinite"/>
  </text>
</svg>
