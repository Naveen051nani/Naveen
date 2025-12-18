# Naveen
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Telugu Biography Archive</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: #111;
      color: white;
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.5rem;
      letter-spacing: 1px;
    }
    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-size: 0.95rem;
    }
    .hero {
      background: #fff;
      padding: 3rem 2rem;
      text-align: center;
    }
    .hero h2 {
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }
    .hero p {
      color: #555;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 6px 16px rgba(0,0,0,0.08);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-4px);
    }
    .card img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }
    .card-content {
      padding: 1rem;
    }
    .card-content h3 {
      margin: 0.3rem 0;
      font-size: 1.1rem;
    }
    .card-content p {
      font-size: 0.9rem;
      color: #555;
    }
    footer {
      background: #111;
      color: #aaa;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
      font-size: 0.85rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Telugu Biography</h1>
  <nav>
    <a href="#">People</a>
    <a href="#">Categories</a>
    <a href="#">About</a>
  </nav>
</header>

<section class="hero">
  <h2>Inspiring Telugu Lives</h2>
  <p>Stories of actors, leaders, scientists, freedom fighters, and unsung heroes</p>
</section>

<div class="container">
  <div class="grid">

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="NTR">
      <div class="card-content">
        <h3>N. T. Rama Rao</h3>
        <p>Legendary actor and former Chief Minister of Andhra Pradesh.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="Savithri">
      <div class="card-content">
        <h3>Savithri</h3>
        <p>Iconic Telugu actress known for powerful performances.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400x300" alt="CNR Rao">
      <div class="card-content">
        <h3>C. R. Rao</h3>
        <p>Renowned statistician of Indian origin.</p>
      </div>
    </div>

  </div>
</div>

<footer>
  © 2025 Telugu Biography Project • Inspired by Biography.com
</footer>

</body>
</html>
