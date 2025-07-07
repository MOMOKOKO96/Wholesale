# <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MOMO KOKO | Wholesale Fashion</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0; padding: 0;
      background: #fefefe;
      color: #333;
    }
    header {
      background-color: #ff6f61;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 4px;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 8px;
      font-weight: 600;
    }
    nav {
      background: #333;
      text-align: center;
      padding: 12px 0;
    }
    nav a {
      color: white;
      margin: 0 18px;
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ff6f61;
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      color: #ff6f61;
      margin-bottom: 25px;
      font-weight: 700;
      font-size: 2rem;
      border-bottom: 3px solid #ff6f61;
      display: inline-block;
      padding-bottom: 6px;
    }
    .product-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 24px;
      justify-content: center;
    }
    .product {
      border: 1px solid #ddd;
      border-radius: 6px;
      width: 220px;
      padding: 15px;
      text-align: center;
      background: white;
      box-shadow: 0 2px 8px rgb(0 0 0 / 0.1);
      transition: transform 0.3s ease;
    }
    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgb(0 0 0 / 0.2);
    }
    .product img {
      width: 100%;
      height: auto;
      border-radius: 4px;
      margin-bottom: 12px;
    }
    .product h3 {
      margin: 10px 0 6px;
      font-size: 1.2rem;
      color: #333;
    }
    .product p {
      color: #666;
      font-size: 1rem;
    }
    #howtoorder p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 14px;
    }
    #contact p {
      font-size: 1.1rem;
      margin: 8px 0;
    }
    footer {
      background: #ff6f61;
      color: white;
      text-align: center;
      padding: 22px 20px;
      margin-top: 50px;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      .product-grid {
        flex-direction: column;
        align-items: center;
      }
      .product {
        width: 90%;
      }
      header h1 {
        font-size: 2.2rem;
      }
      h2 {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>MOMO KOKO</h1>
  <p>Wholesale Fashion from Thailand to Myanmar</p>
</header>

<nav>
  <a href="#products">Products</a>
  <a href="#howtoorder">How to Order</a>
  <a href="#contact">Contact</a>
</nav>

<section id="products">
  <h2>Featured Products</h2>
  <div class="product-grid">
    <div class="product">
      <img src="https://via.placeholder.com/220x270?text=Floral+Blouse" alt="Floral Blouse" />
      <h3>Floral Blouse</h3>
      <p>Price: 3,800 MMK <br/><small>(Min order: 5 pcs)</small></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/220x270?text=Summer+Dress" alt="Summer Dress" />
      <h3>Summer Dress</h3>
      <p>Price: 6,500 MMK <br/><small>(Min order: 3 pcs)</small></p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/220x270?text=Basic+T-Shirt" alt="Basic T-Shirt" />
      <h3>Basic T-Shirt</h3>
      <p>Price: 2,500 MMK <br/><small>(Min order: 10 pcs)</small></p>
    </div>
  </div>
</section>

<section id="howtoorder">
  <h2>How to Order</h2>
  <p>1. Browse our products and select your favorites.</p>
  <p>2. Send your order list via Viber or Telegram.</p>
  <p>3. We confirm availability and send you the invoice.</p>
  <p>4. Make payment via KBZPay, WavePay, or bank transfer.</p>
  <p>5. Receive delivery via express courier or pick up in Yangon.</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>📞 Phone: 09-123456789</p>
  <p>📱 Viber/Telegram: @momokoko</p>
  <p>📧 Email: contact@momokoko.com</p>
  <p>📍 Location: Yangon, Myanmar</p>
</section>

<footer>
  &copy; 2025 MOMO KOKO. All rights reserved.
</footer>

</body>
</html>
