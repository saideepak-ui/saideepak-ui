<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sai Deepak's GitHub Profile</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #f4f4f9, #e8f0fe);
      margin: 0;
      padding: 0;
      color: #333;
    }
    .header {
      display: flex;
      align-items: center;
      padding: 40px;
      background: linear-gradient(to right, #1e1e2f, #2c3e50);
      color: white;
      position: relative;
    }
    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      margin-right: 30px;
      transition: transform 0.3s ease;
    }
    .profile-img:hover {
      transform: scale(1.1);
    }
    .header-content {
      flex: 1;
    }
    .linkedin-link {
      position: absolute;
      top: 20px;
      right: 20px;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
    }
    .linkedin-link img {
      width: 30px;
      vertical-align: middle;
      margin-right: 8px;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    .section {
      margin-bottom: 60px;
    }
    h2 {
      color: #1e1e2f;
      border-bottom: 3px solid #0078d4;
      padding-bottom: 10px;
    }
    .cert, .project {
      background: linear-gradient(to right, #ffffff, #f0f9ff);
      border-radius: 12px;
      padding: 25px;
      margin: 20px 0;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      display: flex;
      align-items: center;
    }
    .cert:hover, .project:hover {
      transform: scale(1.02);
      box-shadow: 0 6px 16px rgba(0,0,0,0.15);
    }
    .cert img, .project img {
      width: 60px;
      height: 60px;
      margin-right: 20px;
    }
    .cert-content, .project-content {
      flex: 1;
    }
    .cert h3, .project h3 {
      margin-top: 0;
      color: #333;
    }
    .cert a, .project a {
      text-decoration: none;
      color: #0078d4;
    }
    .cert a:hover, .project a:hover {
      text-decoration: underline;
    }
    footer {
      background: #1e1e2f;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <div class="header">
    <a href="https://www.linkedin.com/in/sai-deepak-munja-528759320/" class="linkedin-link" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">LinkedIn Profile</a>
    <img src="https://drive.google.com/uc?export=view&id=1hz7AQwc-v5aXa8s6HZ_7g4-i-DhNeUIw" alt="Profile Picture" class="profile-img" />
    <div class="header-content">
      <h1>Hi 👋, I'm Sai Deepak</h1>
      <p><strong>B.Tech (CSE - Data Science), Geethanjali College of Engineering and Technology, 2025 Graduate</strong><br>
      Passionate about Data Analysis | Python | Machine Learning | Excel | Power BI | Statistics<br>
      I love exploring data-driven solutions, building interactive dashboards, and uncovering actionable insights.<br>
      📫 Email: <strong>saideepakmunja@gmail.com</strong></p>
    </div>
  </div>

  <div class="container">
    <div class="section">
      <h2>Certifications</h2>
      <!-- Certification Cards (your previous code here) -->
    </div>

    <div class="section">
      <h2>Internship</h2>
      <div class="cert">
        <img src="https://img.icons8.com/fluency/48/000000/artificial-intelligence.png" alt="AI Internship">
        <div class="cert-content">
          <h3>AI/ML Intern at Cantilever Labs</h3>
          <p>Designed and developed a Fake News Detection model using TF-IDF vectorization and Passive Aggressive Classifier. Achieved 90%+ accuracy on benchmark datasets.</p>
          <p><strong>Skills:</strong> Python, Pandas, Machine Learning, Scikit-learn</p>
          <a href="https://github.com/saideepak-ui/Fake-news-with-python">Project Link</a>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>Projects</h2>
      <!-- Project Cards (your previous code here) -->
    </div>
  </div>

  <footer>
    &copy; 2025 Sai Deepak. All rights reserved.
  </footer>
</body>
</html>
