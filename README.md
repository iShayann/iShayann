 /* Ice theme for GitHub READMEs by Jason Long */


/* color scheme */

:root {
  --ice-cyan: #00bfff;
  --ice-blue: #87ceeb;
  --ice-orange: #ffa500;
  --ice-yellow: #ffff00;
  --ice-green: #00ff00;
  --ice-purple: #9370db;
  --ice-pink: #ffc0cb;
}

/* typography */

body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: var(--ice-blue);
  font-weight: bold;
}

a {
  color: var(--ice-cyan);
}

a:hover {
  color: var(--ice-purple);
}

/* layout */

.boxed-group {
  border: 1px solid var(--ice-blue);
  border-radius: 3px;
  margin-bottom: 16px;
}

.boxed-group > h3 {
  background-color: var(--ice-blue);
  border-radius: 3px 3px 0 0;
  color: #fff;
  padding: 8px 12px;
}

.boxed-group > ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.boxed-group > ul > li {
  border-top: 1px solid var(--ice-blue);
  padding: 8px 12px;
}

.boxed-group > ul > li:first-of-type {
  border-top: 0;
  padding-top: 12px;
}

/* custom styles */

.ice-cyan {
  color: var(--ice-cyan);
}

.ice-blue {
  color: var(--ice-blue);
}

.ice-orange {
  color: var(--ice-orange);
}

.ice-yellow {
  color: var(--ice-yellow);
}

.ice-green {
  color: var(--ice-green);
}

.ice-purple {
  color: var(--ice-purple);
}

.ice-pink {
  color: var(--ice-pink);
}
