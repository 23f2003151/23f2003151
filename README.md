<svg width="100%" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#ff00cc"/>
      <stop offset="50%" stop-color="#3333ff"/>
      <stop offset="100%" stop-color="#00ffcc"/>
    </linearGradient>

    <filter id="glitch">
      <feColorMatrix
        type="matrix"
        values="
        1 0 0 0 0
        0 1 0 0 0
        0 0 1 0 0
        0 0 0 1 0"/>
      <feOffset dx="2" dy="0" result="off1"/>
      <feOffset dx="-2" dy="0" result="off2"/>
    </filter>
  </defs>

  <rect width="100%" height="100%" rx="15" fill="#8e44ad"/>

  <text x="50%" y="65%"
        dominant-baseline="middle"
        text-anchor="middle"
        font-size="48"
        font-family="Arial, Helvetica, sans-serif"
        fill="url(#grad)"
        filter="url(#glitch)">
    Hey, I'm Anuj!
    <animate attributeName="x" from="50%" to="49%" dur="0.08s" repeatCount="indefinite"/>
  </text>
</svg>

import DataScientist from 'AnujYadav';

class Bio extends DataScientist {
  name       = 'Anuj Yadav';
  pronouns   = 'He/Him';
  interests  = [
    'Data Science',
    'Machine Learning',
    'Business Analytics',
    'Open Source'
  ];
  location   = 'India';
}

class Skills extends DataScientist {
  languages        = ['Python', 'Java', 'C++', 'JavaScript'];
  databases        = ['MySQL', 'MongoDB'];
  data_science     = ['Pandas', 'NumPy', 'Scikit-learn'];
  visualization    = ['Power BI', 'Tableau'];
  web_development  = ['HTML', 'CSS', 'React', 'Node.js'];
}
