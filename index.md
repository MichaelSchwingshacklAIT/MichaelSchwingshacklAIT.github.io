<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOPOMOP - Few-Shot Machinery Part Segmentation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .section {
            margin-bottom: 40px;
        }
        .authors {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .author {
            background: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
            width: 250px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>HOPOMOP - Few-Shot Machinery Part Segmentation</h1>
    </header>
    <div class="container">
        <div class="section">
            <h2>Understanding HOPOMOP</h2>
            <p>HOPOMOP is an AI-powered system that segments machinery parts using few-shot learning. It combines foundation models and graph neural networks to accurately identify components, even with minimal data.</p>
            <img src="images/logo.png" alt="HOPOMOP Logo">
        </div>
        <div class="section">
            <h2>How It Works</h2>
            <p>Using domain-randomized synthetic data, HOPOMOP trains models to recognize truck-mounted loading cranes and other machinery parts. The AI seamlessly transfers this knowledge to real-world applications.</p>
            <img src="images/domain_randomization.png" alt="Domain Randomization">
        </div>
        <div class="section">
            <h2>Key Results</h2>
            <p>From few-shot segmentation to real-world adaptation, HOPOMOP achieves high accuracy across different machinery parts and environments.</p>
            <img src="images/sim_to_real.gif" alt="Simulation to Real Transfer">
        </div>
        <div class="section">
            <h2>Meet the Authors</h2>
            <div class="authors">
                <div class="author">
                    <h3>Michael Schwingshackl</h3>
                    <a href="https://publications.ait.ac.at/de/persons/michael-schwingshackl">🔗 Research Profile</a>
                </div>
                <div class="author">
                    <h3>Fabio Francisco Oberweger</h3>
                    <a href="https://publications.ait.ac.at/de/persons/fabio.oberweger">🔗 Research Profile</a>
                </div>
                <div class="author">
                    <h3>Markus Murschitz</h3>
                    <a href="https://publications.ait.ac.at/de/persons/markus.murschitz">🔗 Research Profile</a>
                </div>
            </div>
        </div>
        <div class="section">
            <h2>Learn More</h2>
            <p>Read the full paper: <a href="https://arxiv.org/abs/2501.10080">📝 Link to Paper</a></p>
        </div>
    </div>
</body>
</html>
