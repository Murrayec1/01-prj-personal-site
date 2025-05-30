<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Emerald Carolynn - Personal Website</title>
  <link rel="stylesheet" href="style.css"> <!-- Link to the CSS file -->
  <style>
    /* Import a more professional gothic font from Google Fonts */
    @import url('https://fonts.googleapis.com/css2?family=IM+Fell+English:ital,wght@0,400;1,400&display=swap');

    /* Set a dark purple background and a professional gothic font */
    body {
      background-color: #2b1837; /* Deep purple for a gothic vibe */
      color: #e6e6fa; /* Light lavender text for contrast */
      font-family: 'IM Fell English', serif; /* Professional gothic font */
      margin: 0;
      padding: 0;
    }

    /* Navigation bar styles */
    nav {
      background-color: #3d2247;
      border-bottom: 2px solid #7c3a7e;
      text-align: center;
      padding: 10px 0;
      margin-bottom: 10px;
    }
    nav a {
      color: #ffb6c1;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1.1em;
      font-family: 'IM Fell English', serif;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #e6e6fa;
      text-shadow: 0 0 5px #ffb6c1;
    }

    /* Style the header with a spooky color and center the text */
    header {
      background-color: #3d2247;
      color: #ffb6c1;
      text-align: center;
      padding: 20px 0;
      border-bottom: 2px solid #7c3a7e;
      font-family: 'IM Fell English', serif;
    }

    /* Style the profile image with a simple border and shadow */
    section img {
      display: block;
      margin: 15px auto;
      border: 3px solid #7c3a7e;
      border-radius: 50%;
      box-shadow: 0 0 10px #7c3a7e;
    }

    /* Add a semi-transparent background to sections */
    section {
      background-color: rgba(44, 19, 56, 0.9);
      margin: 25px auto;
      padding: 20px;
      max-width: 400px;
      border: 2px solid #7c3a7e;
      border-radius: 15px;
      font-family: 'IM Fell English', serif;
    }

    /* Make section headings stand out */
    h2 {
      color: #ffb6c1;
      text-shadow: 2px 2px 8px #7c3a7e;
      font-family: 'IM Fell English', serif;
    }

    /* Style the lists */
    ul {
      list-style-type: square;
      padding-left: 25px;
    }

    li {
      margin-bottom: 8px;
      font-size: 1.1em;
    }

    /* Footer with a gothic touch */
    footer {
      text-align: center;
      padding: 15px 0;
      background-color: #3d2247;
      color: #e6e6fa;
      border-top: 2px solid #7c3a7e;
      margin-top: 30px;
      font-family: 'IM Fell English', serif;
    }
  </style>
</head>
<body>
  <!-- Navigation Bar -->
  <!-- This is a simple navigation bar for beginners -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#favorites">Favorites</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Website Header (Hero Section) -->
  <header id="home">
    <!-- Main heading for your site -->
    <h1>Emerald Carolynn</h1>
    <!-- Catchy subtitle for your hero section -->
    <p style="font-size:1.3em; margin-top:10px;">
      Web Alchemist &amp; Creative Coder
    </p>
    <!-- Fun, magical tagline for beginners -->
    <p style="font-style:italic; color:#ffb6c1; margin-top:5px;">
      Brewing up enchanting websites with a dash of code and a sprinkle of magic!
    </p>
  </header>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <img src="profile.jpg" alt="Emerald Carolynn" width="200">
    <!-- Friendly, quirky, and spooky beginner bio -->
    <p>
      Hi there! I'm Emerald Carolynn, your friendly neighborhood Web Alchemist. I'm just starting my magical journey in web development, brewing up beginner projects with a dash of spooky style and a sprinkle of quirky code. If you like cauldrons full of creativity, glowing buttons, and a little bit of web wizardry, you’re in the right place. Let’s cast some code spells together!
    </p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>My Skills</h2>
    <!-- Fun and quirky list of skills for beginners, each with a simple icon -->
    <ul>
      <li>
        <!-- html icon -->
        <span style="font-size:1.3em; margin-right:8px;">🔮</span>
        html (I can conjure up web pages!)
      </li>
      <li>
        <!-- css icon -->
        <span style="font-size:1.3em; margin-right:8px;">🧙‍♀️</span>
        css (I style with a sprinkle of magic!)
      </li>
      <li>
        <!-- JavaScript icon -->
        <span style="font-size:1.3em; margin-right:8px;">✨</span>
        JavaScript (I make things move—abracadabra!)
      </li>
      <li>
        <!-- Creative Writing icon (using a book emoji for better support) -->
        <span style="font-size:1.3em; margin-right:8px;">📖</span>
        Creative Writing (I cast spells with words!)
      </li>
      <li>
        <!-- Coding with AI icon -->
        <span style="font-size:1.3em; margin-right:8px;">🤖</span>
        Coding with AI (Cause robots are cool! Right?!)
      </li>
      <li>
        <!-- Beginner in Coding icon -->
        <span style="font-size:1.3em; margin-right:8px;">🧪</span>
        Beginner in Coding (Every web alchemist starts somewhere!)
      </li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li>
        <!-- Crystal Ball icon for personal website -->
        <span style="font-size:1.3em; margin-right:8px;">🔮</span>
        <strong>Personal Website</strong> - This website you are viewing now!
      </li>
      <li>
        <!-- Potion icon for To-Do List App -->
        <span style="font-size:1.3em; margin-right:8px;">🧪</span>
        <strong>To-Do List App</strong> - A simple app to keep track of tasks.
      </li>
      <li>
        <!-- Spell Book icon for Portfolio Website -->
        <span style="font-size:1.3em; margin-right:8px;">📜</span>
        <strong>Portfolio Website</strong> - A collection of my favorite work.
      </li>
    </ul>
  </section>

  <!-- Favorite Sites Section -->
  <section id="favorites">
    <h2>My Favorite Sites</h2>
    <!-- This is a simple list of your favorite websites with links and fantasy icons -->
    <ul>
      <li>
        <!-- Magic Book icon for W3Schools -->
        <span style="font-size:1.3em; margin-right:8px;">📚</span>
        <a href="https://www.w3schools.com/" target="_blank" style="color:#ffb6c1;">
          W3Schools (Great for learning web basics!)
        </a>
      </li>
      <li>
        <!-- Scroll icon for MDN Web Docs -->
        <span style="font-size:1.3em; margin-right:8px;">📜</span>
        <a href="https://developer.mozilla.org/" target="_blank" style="color:#ffb6c1;">
          MDN Web Docs (Awesome coding reference)
        </a>
      </li>
      <li>
        <!-- Crystal Ball icon for CodePen -->
        <span style="font-size:1.3em; margin-right:8px;">🔮</span>
        <a href="https://codepen.io/" target="_blank" style="color:#ffb6c1;">
          CodePen (Try out your code and see it live!)
        </a>
      </li>
      <li>
        <!-- Potion icon for Coolors -->
        <span style="font-size:1.3em; margin-right:8px;">🧪</span>
        <a href="https://coolors.co/" target="_blank" style="color:#ffb6c1;">
          Coolors (Fun color palette generator)
        </a>
      </li>
      <li>
        <!-- LinkedIn with a link icon -->
        <span style="font-size:1.3em; margin-right:8px;">🔗</span>
        <a href="https://www.linkedin.com/in/emerald-murray-799a68368/" target="_blank" style="color:#ffb6c1;">
          My LinkedIn (Connect with me!)
        </a>
      </li>
    </ul>
  </section>

  <!-- Contact Section moved to the bottom -->
  <section id="contact">
    <h2>Contact</h2>
    <p>You can reach me at: <a href="mailto:murrayec1@appstate.edu" style="color:#ffb6c1;">murrayec1@appstate.edu</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>Thanks for stopping by!</p>
  </footer>
</body>
</html>
