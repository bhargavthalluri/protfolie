# protfolie  
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>A4 Portfolio</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background: #ccc;
    }

    .page {
      width: 210mm;
      height: 297mm;
      margin: auto;
      background: white;
      box-shadow: 0 0 5px rgba(0,0,0,0.5);
      box-sizing: border-box;
      padding: 20mm;
      font-family: Arial, sans-serif;
      color: #000;
    }

    h1, h2, h3 {
      margin: 0;
    }

    .header {
      text-align: center;
      border-bottom: 2px solid #000;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    .section {
      margin-bottom: 15px;
    }

    .section h2 {
      border-bottom: 1px solid #aaa;
      padding-bottom: 4px;
      margin-bottom: 10px;
    }

    ul {
      margin: 0;
      padding-left: 20px;
    }

    .project {
      margin-bottom: 8px;
    }

    /* Scale the page to fit the screen */
    @media screen {
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      .page {
        transform: scale(0.7);
        transform-origin: top center;
      }
    }

    /* Print setup */
    @media print {
      body {
        background: none;
      }
      .page {
        box-shadow: none;
        transform: none;
        margin: 0;
      }
    }
  </style>
</head>
<body>

  <div class="page">
    <div class="header">
      <h1>SHIVA BHARGAV</h1>
      <p>Email: bhargavthalluri57@gmail.com | Phone: +91 8179568216</p>
      <p>LinkedIn: linkedin.com/in/Bhargav | GitHub: github.com/Shiva bhrgav</p>
    </div>

    <div class="section">
      <h2>Objective</h2>
      <p>To secure a responsible career opportunity to fully utilize my training and skills, while making a significant contribution to the company.</p>
    </div>

    <div class="section">
      <h2>Education</h2>
      <p><strong>B.Tech in artificial intelligence and machine learning</strong><br>anurag University</p>
    </div>

    <div class="section">
      <h2>Technical Skills</h2>
      <ul>
        <li>Languages: HTML, CSS, JavaScript, Python,c++,java</li>
        <li>Tools: Git, VS Code</li>
        <li>Frameworks: React (Basics), Node.js (Basics)</li>
      </ul>
    </div>

    <div class="section">
      <h2>Projects</h2>
      <div class="project">
        <strong>Portfolio Website</strong><br>
        A simple portfolio website built using HTML and CSS.
      </div>
      <div class="project">
        <strong>Task Manager</strong><br>
        A to-do list app with JavaScript functionality for task tracking.
      </div>
    </div>

    <div class="section">
      <h2>Certifications</h2>
      <ul>
        <li>Front-End Development – Coursera</li>
        <li>Python Programming – edX</li>
      </ul>
    </div>

    <div class="section">
      <h2>Languages Known</h2>
      <ul>
        <li>English</li>
        <li>Hindi</li>
      </ul>
    </div>
  </div>

</body>
</html>
