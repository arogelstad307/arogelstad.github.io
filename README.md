<DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Scuba Diving Locations</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      margin: 0;
      padding: 0;
    }

    header {
      text-align: center;
      background-color: #20b2aa;
      color: white;
      padding: 20px 0;
    }

    .container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 40px;
    }

    .image-link {
      position: relative;
      width: 200px;
      height: 200px;
      border-radius: 10px;
      overflow: hidden;
    }

    .image-link img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.3s ease;
    }

    .image-link img:hover {
      transform: scale(1.05);
    }

    .image-link a {
      display: block;
      width: 100%;
      height: 100%;
      text-decoration: none;
    }

    figure {
      text-align: center;
    }
    figcaption {
      margin-top: 10px;
      font-size: 14px;
      color: #555;
    }

    .description {
      font-size: 12px;
      color: #666;
      margin-top: 5px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #20b2aa;
      color: white;
      position: fixed;
      width: 100%;
      bottom: 0;
    }

  </style>
</head>
<body>
  <header>
    <h1>Popular Scuba Diving Locations</h1>
    <p>Explore the underwater world at these famous diving spots!</p>
  </header>

  <div class="container">
    <figure class="image-link">
      <a href="location1.html">
        <img src="scuba1.jpg" alt="Great Barrier Reef">
      </a>
      <figcaption>Great Barrier Reef</figcaption>
      <p class="description">Discover the vibrant coral reefs and marine life of Australia.</p>
    </figure>
    <figure class="image-link">
      <a href="location2.html">
        <img src="scuba2.jpg" alt="Blue Hole, Belize">
      </a>
      <figcaption>Blue Hole, Belize</figcaption>
      <p class="description">Dive into the mysterious depths of this iconic underwater sinkhole.</p>
    </figure>
    <figure class="image-link">
      <a href="location3.html">
        <img src="scuba3.jpg" alt="Galapagos Islands">
      </a>
      <figcaption>Galapagos Islands</figcaption>
      <p class="description">Swim alongside unique species in this UNESCO World Heritage site.</p>
    </figure>
    <figure class="image-link">
      <a href="location4.html">
        <img src="scuba4.jpg" alt="Palau, Micronesia">
      </a>
      <figcaption>Palau, Micronesia</figcaption>
      <p class="description">Experience breathtaking underwater caves and diverse marine ecosystems.</p>
    </figure>
  </div>

  <footer>
    <p>&copy; 2025 Scuba Diving Adventures. All rights reserved.</p>
  </footer>
</body>
</html>
