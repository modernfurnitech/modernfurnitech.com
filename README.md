<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Modern Furnitech Solutions</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <style>
    body{
      margin:0;
      font-family:Arial, Helvetica, sans-serif;
      background:#0f0f0f;
      color:#fff;
    }

    header{
      background:#000;
      padding:20px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    header span{color:#caa24d;}

    .hero{
      padding:80px 40px;
      text-align:center;
      background:linear-gradient(to right,#000,#1a1a1a);
    }

    .hero h2{font-size:40px;}
    .hero p{color:#ccc;}

    .btn{
      display:inline-block;
      margin-top:20px;
      padding:12px 30px;
      background:#caa24d;
      color:#000;
      text-decoration:none;
      font-weight:bold;
      border-radius:4px;
    }

    section{
      padding:60px 40px;
      max-width:1200px;
      margin:auto;
    }

    h3{text-align:center;font-size:32px;margin-bottom:40px;}

    .services,.why{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }

    .card{
      background:#1a1a1a;
      padding:25px;
      border-radius:8px;
      text-align:center;
    }

    .card h4{color:#caa24d;}

    /* PRODUCT SECTION */
    .product-box{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:40px;
    }

    .product-gallery{
      display:grid;
      grid-template-columns:repeat(2,1fr);
      gap:15px;
    }

    .product-gallery img{
      width:100%;
      border-radius:8px;
    }

    .price{
      font-size:28px;
      color:#caa24d;
      margin-bottom:15px;
    }

    .product-details ul{
      list-style:none;
      padding:0;
      font-size:18px;
    }

    .product-details li{margin-bottom:10px;}

    .note{
      color:#ccc;
      margin-top:15px;
    }

    footer{
      background:#000;
      padding:30px;
      text-align:center;
      color:#aaa;
    }

    .whatsapp-float{
      position:fixed;
      bottom:20px;
      right:20px;
      background:#25D366;
      color:#fff;
      border-radius:50px;
      padding:12px 18px;
      text-decoration:none;
      font-weight:bold;
      z-index:999;
    }

    @media(max-width:768px){
      .product-box{grid-template-columns:1fr;}
    }
  </style>
</head>

<body>

<header>
  <h1>Modern <span>Furnitech</span> Solutions</h1>
  <div>📞 9234736961</div>
</header>

<div class="hero">
  <h2>Premium Furniture Manufacturer</h2>
  <p>Customized Modern Sofa • Beds • Tables • Mattress & Cushions</p>
  <p><b>Manufacturing | Wholesale | Retail</b></p>
  <a href="tel:9234736961" class="btn">Call Now</a>
</div>

<section>
  <h3>Our Services</h3>
  <div class="services">
    <div class="card"><h4>Customized Modern Sofa</h4></div>
    <div class="card"><h4>Customized Modern Bed</h4></div>
    <div class="card"><h4>Tables</h4></div>
    <div class="card"><h4>Mattress & Cushions</h4></div>
    <div class="card"><h4>Sofa Repairing</h4></div>
    <div class="card"><h4>Bed Repairing</h4></div>
    <div class="card"><h4>Bed Installation</h4></div>
  </div>
</section>

<!-- SOFA PRODUCT SECTION -->
<section>
  <h3>Our Products</h3>

  <div class="product-box">
    <div class="product-gallery">
      <img src="sofa1.jpg">
      <img src="sofa2.jpg">
      <img src="sofa3.jpg">
      <img src="sofa4.jpg">
    </div>

    <div class="product-details">
      <h4 class="price">₹ 33,333 /-</h4>

      <ul>
        <li><b>Fabric:</b> Velvet (Mousa)</li>
        <li><b>Frame Material:</b> Liptus Wood + Plywood</li>
        <li><b>Seating Capacity:</b> 8 Seater</li>
        <li><b>Foam:</b> Harmony HR Foam</li>
        <li><b>Delivery:</b> Free of Cost</li>
      </ul>

      <p class="note">
        <b>Note:</b> You can customize size and design.  
        Choose any colour or fabric material.
      </p>

      <a href="https://wa.me/919234736961?text=I%20want%20to%20order%208%20Seater%20Luxury%20Sofa" 
         class="btn" target="_blank">
        Order on WhatsApp
      </a>
    </div>
  </div>
</section>

<section>
  <h3>Why Choose Us</h3>
  <div class="why">
    <div class="card">Premium Quality Materials</div>
    <div class="card">Modern & Custom Designs</div>
    <div class="card">Affordable Pricing</div>
    <div class="card">Trusted by Customers</div>
  </div>
</section>

<footer>
  📍 Gopalganj <br>
  📞 9234736961 <br><br>
  © 2026 Modern Furnitech Solutions
</footer>

<a href="https://wa.me/919234736961" class="whatsapp-float" target="_blank">
  <i class="fa fa-whatsapp"></i> Order via WhatsApp
</a>

</body>
</html>
