<!-- README (HTML style) -->
<h1>My First Portfolio Website (HTML/CSS/JavaScript)</h1>

<p>
  This is my first portfolio website project. It includes smooth scrolling navigation,
  active link highlighting while scrolling, and a simple alert message when users click
  contact links.
</p>

<hr />

<h2>✨ Features</h2>
<ul>
  <li><b>Smooth Scrolling:</b> Clicking nav links scrolls smoothly to sections.</li>
  <li><b>Active Section Highlight:</b> The current section’s nav link becomes <code>active</code> while scrolling.</li>
  <li><b>Contact Click Alert:</b> Shows a friendly alert message when clicking contact links.</li>
</ul>

<hr />

<h2>📁 Project Structure (Example)</h2>
<pre>
portfolio-website/
├── index.html
├── style.css
└── script.js
</pre>

<hr />

<h2>🚀 How to Run</h2>
<ol>
  <li>Download or clone the project folder.</li>
  <li>Open <code>index.html</code> in your browser.</li>
</ol>

<hr />

<h2>🧠 JavaScript Explanation</h2>

<h3>1) Smooth Scrolling</h3>
<p>
  When you click a navigation link, the default jump is prevented and the page scrolls smoothly
  to the target section (with a small offset for the navbar height).
</p>

<h3>2) Active Link While Scrolling</h3>
<p>
  While you scroll, the script checks which section is currently in view and adds the
  <code>active</code> class to the matching navigation link.
</p>

<h3>3) Contact Alert Message</h3>
<p>
  When users click any link inside the contact area, an alert popup is shown to confirm interest.
</p>

<hr />

<h2>✅ Requirements</h2>
<ul>
  <li>A browser (Chrome, Edge, Firefox, etc.)</li>
  <li>Works with plain HTML/CSS/JavaScript (no frameworks needed)</li>
</ul>

<hr />

<h2>📝 Notes</h2>
<ul>
  <li>
    Make sure your navigation links match section IDs:
    <br />
    Example: <code>&lt;a href="#about"&gt;About&lt;/a&gt;</code> should match
    <code>&lt;section id="about"&gt;...&lt;/section&gt;</code>
  </li>
  <li>
    Ensure your CSS has an <code>.active</code> style for the highlighted nav link.
    Example: <code>.nav-links a.active { font-weight: bold; }</code>
  </li>
</ul>

<hr />

<h2>📌 Author</h2>
<p>
  <b>Your Name:</b> Samuel Zenebe<br />
  <b>Project:</b> First Portfolio Website
</p>
