<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vikash Kumar | Software Developer</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #0d1117;
      --card: #161b22;
      --primary: #5E81AC;
      --secondary: #88C0D0;
      --text: #d8dee9;
      --muted: #9aa4b2;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }

    header {
      text-align: center;
      margin-bottom: 60px;
    }

    header h1 {
      font-size: 3rem;
      color: var(--secondary);
    }

    header p {
      margin-top: 10px;
      color: var(--muted);
      font-size: 1.1rem;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      font-size: 1.8rem;
      color: var(--primary);
      margin-bottom: 20px;
      border-left: 4px solid var(--primary);
      padding-left: 12px;
    }

    .card {
      background: var(--card);
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 0 1px rgba(255,255,255,0.04);
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }

    ul {
      list-style: none;
    }

    ul li::before {
      content: "▹";
      color: var(--secondary);
      margin-right: 8px;
    }

    .competencies {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .tag {
      background: rgba(94,129,172,0.15);
      color: var(--secondary);
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      margin-top: 60px;
      color: var(--muted);
      font-size: 0.9rem;
    }

    footer span {
      color: var(--secondary);
    }
  </style>
</head>
<body>

  <div class="container">

    <!-- HEADER -->
    <header>
      <h1>Vikash Kumar</h1>
      <p>Software Developer | CSE (AIML)</p>
    </header>

    <!-- SUMMARY -->
    <section>
      <h2>Professional Summary</h2>
      <div class="card">
        <p>
          Computer Science Engineering student specializing in <strong>Artificial Intelligence & Machine Learning</strong>,
          with strong skills in <strong>Full Stack Web Development</strong> and
          <strong>Data Structures & Algorithms</strong>.
        </p>
        <br/>
        <p>
          Experienced in building responsive web applications and RESTful APIs.
          Possesses a solid <strong>conceptual understanding of AI/ML</strong> including
          data preprocessing, supervised learning, and model workflows.
        </p>
        <br/>
        <p>
          Currently strengthening problem-solving skills and preparing to learn
          <strong>Cloud Computing and scalable system design</strong>.
        </p>
      </div>
    </section>

    <!-- EDUCATION -->
    <section>
      <h2>Education</h2>
      <div class="card">
        <strong>B.Tech – Computer Science & Engineering (AIML)</strong><br/>
        Expected Graduation: 2027<br/><br/>
        <span>Relevant Coursework:</span>
        Data Structures & Algorithms, OOP, DBMS, OS, Computer Networks, AI & ML
      </div>
    </section>

    <!-- SKILLS -->
    <section>
      <h2>Technical Skills</h2>
      <div class="skills-grid">

        <div class="card">
          <strong>Programming</strong>
          <ul>
            <li>Java, JavaScript, Python</li>
            <li>C, C++</li>
          </ul>
        </div>

        <div class="card">
          <strong>Full Stack Development</strong>
          <ul>
            <li>React.js, HTML, CSS, Tailwind</li>
            <li>Node.js, Express.js</li>
            <li>REST APIs, JWT</li>
          </ul>
        </div>

        <div class="card">
          <strong>Databases</strong>
          <ul>
            <li>MongoDB</li>
            <li>MySQL, PostgreSQL</li>
          </ul>
        </div>

        <div class="card">
          <strong>AI / ML (Foundational)</strong>
          <ul>
            <li>Python for ML</li>
            <li>Supervised Learning</li>
            <li>Scikit-learn, Basic TensorFlow</li>
          </ul>
        </div>

      </div>
    </section>

    <!-- CORE COMPETENCIES -->
    <section>
      <h2>Core Competencies</h2>
      <div class="card competencies">
        <div class="tag">Full Stack Development</div>
        <div class="tag">Data Structures & Algorithms</div>
        <div class="tag">Problem Solving</div>
        <div class="tag">REST API Development</div>
        <div class="tag">Object-Oriented Programming</div>
        <div class="tag">AI/ML Fundamentals</div>
        <div class="tag">Git & GitHub</div>
      </div>
    </section>

    <!-- CURRENT FOCUS -->
    <section>
      <h2>Currently Focused On</h2>
      <div class="card">
        <ul>
          <li>Building full-stack web applications</li>
          <li>Daily DSA practice (LeetCode, GFG)</li>
          <li>Strengthening AI/ML fundamentals</li>
          <li>Preparing for Cloud & system design</li>
        </ul>
      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      <p>“Talk is cheap. Show me the code.” — <span>Linus Torvalds</span></p>
    </footer>

  </div>

</body>
</html>
