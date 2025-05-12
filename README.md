<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sumra Zaman - Portfolio</title>
  
  <!-- AOS Library for scroll animations -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f8fc;
      margin: 0;
      padding: 0;
      color: #333;
      transition: background 0.3s, color 0.3s;
    }

    body.dark-mode {
      background: #121212;
      color: #ddd;
    }

    header {
      background-color: #4a90e2;
      color: white;
      text-align: center;
      padding: 2rem 0;
      position: relative;
    }

    header .profile-image {
      position: absolute;
      top: 50%;
      right: 20px;
      transform: translateY(-50%);
      width: 200px; /* Adjust size as needed */
      height: 130px; /* Adjust size as needed */
      border-radius: 50%;
      border: 2px solid white;
    }

    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 2rem;
      background: white;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
    }

    body.dark-mode main {
      background: #1e1e1e;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      color: #4a90e2;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
      margin-top: 2rem;
    }

    body.dark-mode footer {
      background-color: #1a1a1a;
      color: #aaa;
    }

    a {
      color: #4a90e2;
      text-decoration: none;
    }

    .skills {
      margin: 2rem 0;
    }

    .skill-bar {
      width: 100%;
      background-color: #e0e0e0;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    .skill-progress {
      height: 25px;
      border-radius: 10px;
      text-align: center;
      line-height: 25px;
      color: white;
      font-weight: bold;
    }

    .skill-name {
      margin-bottom: 5px;
    }

    #toggle-theme {
      float: right;
      background: #4a90e2;
      color: white;
      border: none;
      padding: 8px 12px;
      margin-bottom: 10px;
      border-radius: 5px;
      cursor: pointer;
    }

    input, textarea {
      width: 100%;
      padding: 8px;
      margin-top: 5px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    button[type="submit"] {
      background-color: #4a90e2;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    canvas {
      display: block;
      margin: 20px auto;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sumra Zaman</h1>
    <p>Computer Science Student | Data Analysis Enthusiast</p>
    <img src="C:\Users\Admin\Desktop\aaa.png" alt="Sumra Zaman" class="profile-image">
  </header>

  <main>
    <button id="toggle-theme">Toggle Dark Mode</button>

    <section data-aos="fade-up">
      <h2>About Me</h2>
      <p>
        My name is Sumra Zaman, and I am currently pursuing a Bachelor of Science degree in Computer Science 
        with a focus on Data Analysis at COMSATS University, Wah Campus. I am a passionate and hardworking student 
        who enjoys learning and facing new academic challenges.
      </p>
    </section>

    <section data-aos="fade-up">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill-name">Python</div>
        <div class="skill-bar">
          <div class="skill-progress" style="width: 90%; background-color: #4a90e2;">90%</div>
        </div>
        
        <div class="skill-name">Data Analysis</div>
        <div class="skill-bar">
          <div class="skill-progress" style="width: 85%; background-color: #7ed321;">85%</div>
        </div>
        
        <div class="skill-name">SQL</div>
        <div class="skill-bar">
          <div class="skill-progress" style="width: 80%; background-color: #f5a623;">80%</div>
        </div>
        
        <div class="skill-name">Machine Learning</div>
        <div class="skill-bar">
          <div class="skill-progress" style="width: 75%; background-color: #d0021b;">75%</div>
        </div>
      </div>

      <!-- Smaller Pie Chart -->
      <canvas id="skillChart" width="350" height="350"></canvas>
    </section>

    <section data-aos="fade-up">
      <h2>Interests & Hobbies</h2>
      <p>
        In my free time, I enjoy reading, writing, and exploring new technologies. I have a strong interest in 
        data exploration and love uncovering patterns and insights from complex datasets.
      </p>
    </section>

    <section data-aos="fade-up">
      <h2>My Goal</h2>
      <p>
        My goal is to build a successful career in the field of data science, where I can apply my knowledge to 
        solve real-world problems and make a positive impact on society.
      </p>
    </section>

    <section data-aos="fade-up">
      <h2>Projects</h2>
      <div>
        <h3>Online Shopping System</h3>
        <p>Developed a web-based system for managing online orders, customer profiles, and inventory using PHP and MySQL.</p>

        <h3>YouTube & Kids Data Analysis</h3>
        <p>Performed exploratory data analysis on how YouTube content affects children using Python libraries like pandas, matplotlib, and seaborn.</p>
      </div>
    </section>

    <section data-aos="fade-up">
      <h2>Testimonials</h2>
      <blockquote style="background:#f0f8ff; padding:1rem; border-left:4px solid #4a90e2; margin: 1rem 0;">
        <p>"Sumra is incredibly dedicated and has a natural talent for uncovering insights from data. A joy to work with!"</p>
        <footer>– Dr. Ayesha Khan, Data Science Professor</footer>
      </blockquote>

      <blockquote style="background:#f0f8ff; padding:1rem; border-left:4px solid #4a90e2;">
        <p>"Her project on YouTube analytics was not only thorough but also delivered with clarity and confidence."</p>
        <footer>– Mian Muhammad Talha, COMSATS</footer>
      </blockquote>
    </section>

    <section data-aos="fade-up">
      <h2>Send Me a Message</h2>
      <form action="https://formspree.io/f/yourformID" method="POST">
        <label for="name">Name:</label>
        <input type="text" name="name" id="name" required>

        <label for="email">Email:</label>
        <input type="email" name="email" id="email" required>

        <label for="message">Message:</label>
        <textarea name="message" id="message" rows="5" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>

    <section data-aos="fade-up">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:samrizaman7890@gmail.com">samrizaman7890@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/sumra-zaman" target="_blank">linkedin.com/in/sumra-zaman</a></p>
    </section>
  </main>

  <footer>
    <p>© 2025 Sumra Zaman. All rights reserved.</p>
  </footer>

  <!-- JS Libraries -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();

    // Dark mode toggle
    document.getElementById('toggle-theme').addEventListener('click', () => {
      document.body.classList.toggle('dark-mode');
    });

    // Pie chart
    const ctx = document.getElementById('skillChart').getContext('2d');
    new Chart(ctx, {
      type: 'pie',
      data: {
        labels: ['Python', 'Data Analysis', 'SQL', 'Machine Learning'],
        datasets: [{
          data: [90, 85, 80, 75],
          backgroundColor: ['#4a90e2', '#7ed321', '#f5a623', '#d0021b']
        }]
      },
      options: {
        responsive: false
      }
    });
  </script>
</body>
</html>
