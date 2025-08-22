<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Marine Weather Dashboard</title>
  <style>
    body {
      font-family: Arial;
      margin: 0;
      padding: 0;
      background-color: #e0f7fa;
      color: #333;
    }
    header {
      background-color: #0077be;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    #windy {
      width: 100%;
      height: 500px;
      border: none;
    }
    .weather-box {
      background: #ffffff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 500px;
      margin: 20px auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>Marine Weather Dashboard</h1>
    <p>Live data from Open-Meteo and Windy.com</p>
  </header>

  <section class="weather-box">
    <h2>Marine Forecast (Open-Meteo)</h2>
    <p><strong>Location:</strong> <span id="location">Waiting for data...</span></p>
    <p><strong>Wave Height:</strong> <span id="wave_height">--</span> meters</p>
    <p><strong>Wind Speed:</strong> <span id="wind_speed">--</span> km/h</p>
  </section>

  <section>
    <h2>Windy.com Live Map</h2>
    <iframe id="windy" src="https://embed.windy.com/embed2.html?lat=20.0&lon=70.0&detailLat=20.0&detailLon=70.0&width=650&height=450&zoom=5&level=surface&overlay=wind&menu=true&message=true&marker=true&calendar=now&pressure=true&type=map&location=coordinates&detail=true&metricWind=km%2Fh&metricTemp=%C2%B0C&radarRange=-1" frameborder="0"></iframe>
  </section>

  <script>
    async function getMarineWeather() {
      const lat = 20.0;
      const lon = 70.0;
      const url = `https://marine-api.open-meteo.com/v1/marine?latitude=${lat}&longitude=${lon}&hourly=wave_height,wind_speed`;

      try {
        const response = await fetch(url);
        const data = await response.json();
        const wave = data.hourly.wave_height[0];
        const wind = data.hourly.wind_speed[0];

        document.getElementById("location").innerText = `Lat ${lat}, Lon ${lon}`;
        document.getElementById("wave_height").innerText = wave;
        document.getElementById("wind_speed").innerText = wind;
      } catch (err) {
        console.error("Failed to load weather:", err);
      }
    }

    getMarineWeather();
  </script>
</body>
</html>
