<svg width="100%" height="140" viewBox="0 0 900 140" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad">
      <stop offset="0%" stop-color="#ff00cc"/>
      <stop offset="50%" stop-color="#00ffff"/>
      <stop offset="100%" stop-color="#ffcc00"/>
    </linearGradient>

  </defs>

  <rect width="100%" height="100%" rx="18" fill="#8e44ad"/>

  <text
    x="50%"
    y="55%"
    text-anchor="middle"
    dominant-baseline="middle"
    font-size="48"
    font-family="Arial, Helvetica, sans-serif"
    fill="url(#grad)"
    filter="url(#glitch)"
  >
    Hey, I'm Anuj!
    <animate
      attributeName="x"
      from="50%"
      to="49.5%"
      dur="0.08s"
      repeatCount="indefinite"
    />
  </text>
</svg>

javascript
import DataScientist from 'AnujYadav';

class Bio extends DataScientist {
  name = 'Anuj Yadav';
  pronouns = 'He/Him';
  interests = ['Data Science', 'Machine Learning', 'Business Analytics'];
  location = 'India';
}

class Skills extends DataScientist {
  languages = ['Python', 'Java', 'C++', 'JavaScript'];
  databases = ['MySQL', 'MongoDB'];
  tools = ['Pandas', 'NumPy', 'Scikit-learn', 'Power BI', 'Tableau'];
}

