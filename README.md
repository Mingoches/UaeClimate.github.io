<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UAE Climate Awareness</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #f5f7fa;
    color: #333;
}

/* NAVBAR */
nav {
    background: #0a2540;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
}
nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: 500;
}

/* HERO */
.hero {
    background: linear-gradient(to right, #0077b6, #00b4d8);
    color: white;
    padding: 80px 20px;
    text-align: center;
}
.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}
.hero p {
    font-size: 18px;
}

/* SECTION */
.container {
    max-width: 1000px;
    margin: auto;
    padding: 40px 20px;
}

.section-title {
    text-align: center;
    margin-bottom: 30px;
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    transition: 0.3s;
}
.card:hover {
    transform: translateY(-5px);
}

/* FOOTER */
footer {
    background: #0a2540;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}
</style>

</head>
<body>

<!-- NAVBAR -->
<nav>
    <div><strong>UAE Atmosphere Project</strong></div>
    <div>
        <a href="#about">About</a>
        <a href="#weather">Weather</a>
        <a href="#climate">Climate</a>
        <a href="#solutions">Solutions</a>
    </div>
</nav>

<!-- HERO -->
<section class="hero">
    <h1>Forecasting Our Future Atmosphere</h1>
    <p>Understanding Weather, Climate, and Climate Change in the UAE</p>
</section>

<!-- ABOUT -->
<section id="about" class="container">
    <h2 class="section-title">🌍 About the Atmosphere</h2>
    <p style="text-align:center;">
        The atmosphere protects life on Earth, regulates temperature, and drives weather systems.
    </p>
</section>

<!-- WEATHER -->
<section id="weather" class="container">
    <h2 class="section-title">🌦️ UAE Weather Conditions</h2>
    <div class="cards">
        <div class="card">
            <h3>🔥 Extreme Heat</h3>
            <p>Temperatures can exceed 50°C during summer.</p>
        </div>
        <div class="card">
            <h3>🌫️ Humidity</h3>
            <p>High humidity in coastal areas due to the Arabian Gulf.</p>
        </div>
        <div class="card">
            <h3>🌪️ Dust Storms</h3>
            <p>Shamal winds cause reduced visibility and air quality.</p>
        </div>
        <div class="card">
            <h3>🌁 Fog</h3>
            <p>Common in winter mornings due to moisture and cooling.</p>
        </div>
    </div>
</section>

<!-- CLIMATE -->
<section id="climate" class="container">
    <h2 class="section-title">📊 Climate Change in UAE</h2>
    <p style="text-align:center;">
        Scientific data shows rising temperatures and more frequent heatwaves in the UAE.
        This confirms long-term climate change trends affecting the region.
    </p>
</section>

<!-- SOLUTIONS -->
<section id="solutions" class="container">
    <h2 class="section-title">💡 Solutions & Adaptation</h2>
    <div class="cards">
        <div class="card">
            <h3>⚠️ Heat Alerts</h3>
            <p>Warning systems to protect students and communities.</p>
        </div>
        <div class="card">
            <h3>🌳 Urban Greening</h3>
            <p>Planting trees to reduce temperatures naturally.</p>
        </div>
        <div class="card">
            <h3>🏠 Cool Buildings</h3>
            <p>Reflective materials to reduce indoor heat.</p>
        </div>
        <div class="card">
            <h3>🚰 Hydration Stations</h3>
            <p>Ensuring water access during extreme heat events.</p>
        </div>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <p>Grade 12 Science Project | UAE Climate Awareness</p>
</footer>

</body>
</html>
