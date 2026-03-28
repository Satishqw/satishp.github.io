<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Satish P – AI/ML Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f9fc;
      color: #1a1a1a;
    }
    a { text-decoration: none; color: inherit; }

    header {
      background-color: #1e2a38;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    header p { font-size: 1.2rem; }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 2rem 1rem;
    }

    section {
      margin-bottom: 3rem;
    }

    h2.section-title {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 2rem;
      color: #0d47a1;
    }

    /* Skills Section */
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
    }
    .skill {
      width: 180px;
      text-align: center;
    }
    .skill-name { margin-bottom: 0.3rem; font-weight: bold; }
    .skill-bar {
      background: #e0e0e0;
      border-radius: 20px;
      overflow: hidden;
      height: 15px;
    }
    .skill-bar-inner {
      height: 100%;
      background: #0d47a1;
      width: 0;
      border-radius: 20px;
      transition: width 1.5s ease;
    }

    /* Artifacts Section */
    .artifacts {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
    }
    .artifact-card {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .artifact-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 20px rgba(0,0,0,0.15);
    }
    .artifact-card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
    .artifact-card h3 {
      margin-top: 0;
      color: #0d47a1;
    }
    .artifact-card ul {
      padding-left: 1.2rem;
      margin: 0.5rem 0 1rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #1e2a38;
      color: white;
    }

    /* Responsive */
    @media (max-width: 768px){
      header h1 { font-size: 2rem; }
      .skills { flex-direction: column; gap: 1rem; align-items: center; }
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <header>
    <h1>Satish P</h1>
    <p>Bridging Full-Stack Expertise with Cutting-Edge AI/ML Solutions</p>
  </header>

  <div class="container">
    <!-- Skills -->
    <section id="skills">
      <h2 class="section-title">Skills & Expertise</h2>
      <div class="skills">
        <div class="skill">
          <div class="skill-name">Python</div>
          <div class="skill-bar"><div class="skill-bar-inner" style="width:95%"></div></div>
        </div>
        <div class="skill">
          <div class="skill-name">Machine Learning</div>
          <div class="skill-bar"><div class="skill-bar-inner" style="width:90%"></div></div>
        </div>
        <div class="skill">
          <div class="skill-name">Data Analysis</div>
          <div class="skill-bar"><div class="skill-bar-inner" style="width:88%"></div></div>
        </div>
        <div class="skill">
          <div class="skill-name">AI Deployment</div>
          <div class="skill-bar"><div class="skill-bar-inner" style="width:85%"></div></div>
        </div>
      </div>
    </section>

    <!-- Artifacts -->
    <section id="artifacts">
      <h2 class="section-title">Portfolio Artifacts</h2>
      <div class="artifacts">
        <!-- Artifact 1 -->
        <div class="artifact-card">
          <h3>Artifact 1: Marketing Data Analysis Dashboard</h3>
          <img src="images/artifact1_dashboard.png" alt="Marketing Dashboard Screenshot">
          <ul>
            <li><strong>Objective:</strong> Analyze business data to identify trends and actionable insights.</li>
            <li><strong>Process:</strong> Imported datasets, cleaned data, calculated key metrics, visualized trends.</li>
            <li><strong>Tools:</strong> Excel, Google Sheets, Tableau</li>
            <li><strong>Value Proposition:</strong> Demonstrates ability to extract insights from business data for strategic decision-making.</li>
          </ul>
        </div>

        <!-- Artifact 2 -->
        <div class="artifact-card">
          <h3>Artifact 2: Fraud Detection Classifier</h3>
          <img src="images/artifact2_fraud.png" alt="Fraud Detection Visual">
          <ul>
            <li><strong>Objective:</strong> Detect rare fraudulent transactions in large datasets.</li>
            <li><strong>Process:</strong> Applied cost-sensitive learning, SMOTE, probability calibration, and time-based validation.</li>
            <li><strong>Tools:</strong> Python, Scikit-learn, XGBoost</li>
            <li><strong>Value Proposition:</strong> Highlights ability to build high-recall, cost-aware classification models for real-world data.</li>
          </ul>
        </div>

        <!-- Artifact 3 -->
        <div class="artifact-card">
          <h3>Artifact 3: AI Chatbot Interaction Coach</h3>
          <img src="images/artifact3_chatbot.png" alt="Chatbot Screenshot">
          <ul>
            <li><strong>Objective:</strong> Demonstrate applied reasoning in AI/ML scenario-based learning.</li>
            <li><strong>Process:</strong> Engaged with AI scenarios (missing data, imbalanced classes, high-dimensional streams), recorded reasoning and decisions.</li>
            <li><strong>Tools:</strong> Data Challenge Scenarios AI Coach, Brightspace</li>
            <li><strong>Value Proposition:</strong> Shows critical thinking, scenario-based decision-making, and applied ML understanding.</li>
          </ul>
        </div>

        <!-- Artifact 4 -->
        <div class="artifact-card">
          <h3>Artifact 4: Real-Time Sensor Anomaly Detection</h3>
          <img src="images/artifact4_pipeline.png" alt="Anomaly Detection Pipeline Diagram">
          <ul>
            <li><strong>Objective:</strong> Implement real-time anomaly detection on high-dimensional streaming sensor data.</li>
            <li><strong>Process:</strong> Preprocessed data, trained PCA/autoencoder, backfilled labels, layered alerts, shadow retraining for drift handling.</li>
            <li><strong>Tools:</strong> Python, TensorFlow/Keras, Scikit-learn, Flask, Docker</li>
            <li><strong>Value Proposition:</strong> Highlights ability to build real-time ML pipelines, handle sparse labels, and deploy safe anomaly detection systems.</li>
          </ul>
        </div>
      </div>
    </section>
  </div>

  <!-- Footer -->
  <footer>
    <p>© 2026 Satish P | <a href="https://github.com/Satishqw/satishAIML.github.io" target="_blank">GitHub Repository</a></p>
  </footer>

  <script>
    // Animate skill bars on scroll
    const skillBars = document.querySelectorAll('.skill-bar-inner');
    window.addEventListener('load', () => {
      skillBars.forEach(bar => {
        bar.style.width = bar.style.width;
      });
    });
  </script>
</body>
</html>
