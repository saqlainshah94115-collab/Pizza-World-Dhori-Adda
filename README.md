<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pizza World Dhori Adda</title>

  <style>
    body{
      margin:0;
      font-family: Arial, sans-serif;
      background:#111;
      color:#fff;
    }

    header{
      background:#e63946;
      padding:20px;
      text-align:center;
    }

    header h1{
      margin:0;
      font-size:32px;
    }

    .hero{
      text-align:center;
      padding:50px 20px;
      background: url('https://images.unsplash.com/photo-1601924582970-9238bcb495d5') center/cover;
    }

    .hero h2{
      font-size:40px;
      background:rgba(0,0,0,0.6);
      display:inline-block;
      padding:10px 20px;
      border-radius:10px;
    }

    .btn{
      display:inline-block;
      margin-top:20px;
      padding:12px 25px;
      background:#ffba08;
      color:#000;
      text-decoration:none;
      font-weight:bold;
      border-radius:8px;
    }

    .menu{
      padding:40px 20px;
      text-align:center;
    }

    .menu h2{
      font-size:28px;
      margin-bottom:20px;
    }

    .items{
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:20px;
    }

    .card{
      background:#222;
      padding:15px;
      width:200px;
      border-radius:10px;
    }

    .card img{
      width:100%;
      border-radius:10px;
    }

    .card h3{
      margin:10px 0 5px;
    }

    .price{
      color:#ffba08;
      font-weight:bold;
    }

    footer{
      background:#e63946;
      text-align:center;
      padding:20px;
      margin-top:30px;
    }
  </style>

</head>

<body>

<header>
  <h1>Pizza World Dhori Adda 🍕</h1>
</header>

<section class="hero">
  <h2>Hot & Fresh Pizza Delivered Fast</h2><br>
  <a class="btn" href="#menu">Order Now</a>
</section>

<section class="menu" id="menu">
  <h2>Our Menu</h2>

  <div class="items">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1601924928357-22b0a4a1c9c5">
      <h3>Chicken Pizza</h3>
      <p class="price">Rs 1200</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1594007654729-407eedc4be65">
      <h3>BBQ Pizza</h3>
      <p class="price">Rs 1300</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1548365328-9f547c4f4f5b">
      <h3>Zinger Burger</h3>
      <p class="price">Rs 450</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1606755962773-d324e9a13086">
      <h3>Loaded Fries</h3>
      <p class="price">Rs 350</p>
    </div>

  </div>
</section>

<footer>
  <p>📍 Dhori Adda | 📞 03XX-XXXXXXX</p>
  <p>Pizza World Dhori Adda © 2026</p>
</footer>

</body>
</html>
