<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HOPOMOP – AI-Driven Machinery Part Segmentation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #3F6433; /* AIT Green */
      color: #fff;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin: 10px 0 0;
      font-size: 1.2em;
      color: #A1BE37; /* Lime Green accent */
    }
    .container {
      max-width: 1100px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
    }
    .section {
      margin-bottom: 50px;
    }
    .section h2 {
      font-size: 2em;
      margin-bottom: 10px;
      color: #3F6433;
      border-bottom: 3px solid #A1BE37;
      display: inline-block;
      padding-bottom: 5px;
    }
    .section p {
      font-size: 1.1em;
      margin: 10px 0;
    }
    .results, .authors {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }
    .result-card, .author-card {
      background: #f9f9f9;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      flex: 1 1 300px;
      max-width: 350px;
    }
    .result-card img, .author-card img {
      width: 100%;
      display: block;
    }
    .result-card .card-content, .author-card .card-content {
      padding: 15px;
    }
    .result-card h3, .author-card h3 {
      margin-top: 0;
      color: #3F6433;
    }
    .author-card a {
      color: #A1BE37;
      text-decoration: none;
      font-weight: bold;
    }
    .learn-more a {
      color: #3F6433;
      text-decoration: none;
      font-size: 1.2em;
      border-bottom: 2px solid #A1BE37;
      padding-bottom: 3px;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background: #f4f4f4;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>HOPOMOP</h1>
    <p>AI-Powered Machinery Part Segmentation</p>
  </header>
  <div class="container">
    <!-- About Section -->
    <div class="section" id="about">
      <h2>About HOPOMOP</h2>
      <p>
        HOPOMOP (Hundreds Of Points Over Millions Of Pixels) is an innovative AI system that segments machinery parts with minimal data. By combining cutting-edge foundation models and graph neural networks, it offers a transformative approach to visual analysis even in challenging, low-data scenarios.
      </p>
      <img src="images/logo.png" alt="HOPOMOP Logo" />
    </div>

    <!-- How It Works Section -->
    <div class="section" id="how-it-works">
      <h2>How It Works</h2>
      <p>
        Using a blend of synthetic data and domain randomization, HOPOMOP trains on images of complex machinery like truck-mounted loading cranes. This ensures the model adapts seamlessly from simulated environments to real-world applications.
      </p>
      <img src="images/domain_randomization.png" alt="Domain Randomization" />
    </div>

    <!-- Key Results Section -->
    <div class="section" id="results">
      <h2>Key Results</h2>
      <div class="results">
        <div class="result-card">
          <img src="images/few_shot_evaluation.png" alt="Few-Shot Evaluation" />
          <div class="card-content">
            <h3>Few-Shot Evaluation</h3>
            <p>
              High-accuracy segmentation achieved even with a few training samples.
            </p>
          </div>
        </div>
        <div class="result-card">
          <img src="images/sim_to_real.gif" alt="Simulation to Real Transfer" />
          <div class="card-content">
            <h3>Simulation to Real Transfer</h3>
            <p>
              Training on synthetic data transfers successfully to real-world scenarios.
            </p>
          </div>
        </div>
        <div class="result-card">
          <img src="images/davis1.gif" alt="Semi-Supervised Video Segmentation" />
          <div class="card-content">
            <h3>Semi-Supervised Video Segmentation</h3>
            <p>
              Robust segmentation even with minimal labelled frames in videos.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Meet the Authors Section -->
    <div class="section" id="authors">
      <h2>Meet the Authors</h2>
      <div class="authors">
        <div class="author-card">
          <div class="card-content">
            <h3>Michael Schwingshackl</h3>
            <p>📧 <a href="mailto:Michael.Schwingshackl@ait.ac.at">Michael.Schwingshackl@ait.ac.at</a></p>
            <p><a href="https://publications.ait.ac.at/de/persons/michael-schwingshackl" target="_blank">Research Profile</a></p>
            <p><a href="https://scholar.google.at/citations?user=fsvMYQYAAAAJ&hl" target="_blank">Google Scholar</a></p>
          </div>
        </div>
        <div class="author-card">
          <div class="card-content">
            <h3>Fabio Francisco Oberweger</h3>
            <p>📧 <a href="mailto:Fabio.Oberweger@ait.ac.at">Fabio.Oberweger@ait.ac.at</a></p>
            <p><a href="https://publications.ait.ac.at/de/persons/fabio.oberweger" target="_blank">Research Profile</a></p>
            <p><a href="https://scholar.google.at/citations?hl=de&user=njm6I3wAAAAJ" target="_blank">Google Scholar</a></p>
          </div>
        </div>
        <div class="author-card">
          <div class="card-content">
            <h3>Markus Murschitz</h3>
            <p>📧 <a href="mailto:Markus.Murschitz@ait.ac.at">Markus.Murschitz@ait.ac.at</a></p>
            <p><a href="https://publications.ait.ac.at/de/persons/markus.murschitz" target="_blank">Research Profile</a></p>
            <p><a href="https://scholar.google.at/citations?hl=de&user=S8yQbTQAAAAJ" target="_blank">Google Scholar</a></p>
          </div>
        </div>
      </div>
    </div>

    <!-- Learn More Section -->
    <div class="section learn-more" id="learn-more">
      <h2>Learn More</h2>
      <p>
        Read the full paper for an in-depth look at our approach: 
        <a href="https://arxiv.org/abs/2501.10080" target="_blank">📝 Link to Paper</a>
      </p>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 HOPOMOP | Powered by AIT Austrian Institute of Technology</p>
  </footer>
</body>
</html>
