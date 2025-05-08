# L-OBCUR-The-Scent-of-Mystery
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>L’OBCUR – The Scent of Mystery</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #0e0e0e;
      color: #f2f2f2;
    }

    header {
      background-color: #111;
      text-align: center;
      padding: 20px;
      border-bottom: 1px solid gold;
    }

    .logo {
      font-size: 36px;
      color: gold;
      margin: 0;
    }

    .slogan {
      font-style: italic;
      margin: 5px 0 15px;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav a {
      text-decoration: none;
      color: #f2f2f2;
      font-weight: bold;
    }

    nav a:hover {
      color: gold;
    }

    .hero {
      padding: 100px 20px;
      text-align: center;
      background: linear-gradient(to bottom, #1a1a1a, #0e0e0e);
    }

    .hero h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .btn {
      display: inline-block;
      padding: 10px 30px;
      background-color: gold;
      color: #0e0e0e;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 20px;
    }

    section.products, section.combo, section.promo, section.order-form {
      padding: 40px 20px;
      text-align: center;
    }

    h3 {
      color: gold;
      margin-bottom: 20px;
    }

    .product-list, .combo-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .product, .combo {
      background: #1a1a1a;
      padding: 20px;
      border: 1px solid gold;
      border-radius: 8px;
      width: 200px;
    }

    form input, form textarea, form button {
      display: block;
      width: 100%;
      max-width: 400px;
      margin: 10px auto;
      padding: 10px;
      border: none;
      border-radius: 5px;
    }

    form input, form textarea {
      background: #333;
      color: white;
    }

    form button {
      background-color: gold;
      color: #0e0e0e;
      font-weight: bold;
      cursor: pointer;
    }

    .promo-banner {
      background: gold;
      color: #0e0e0e;
      padding: 20px;
      font-weight: bold;
      border-radius: 8px;
      margin: 0 auto;
      max-width: 600px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      border-top: 1px solid gold;
    }
  </style>
</head>
<body>
  <header>
    <h1 class="logo">L’OBCUR</h1>
    <p class="slogan">The Scent of Mystery</p>
    <nav>
      <ul>
        <li><a href="#">Trang chủ</a></li>
        <li><a href="#products">Sản phẩm</a></li>
        <li><a href="#combo">Combo</a></li>
        <li><a href="#order">Đặt hàng</a></li>
        <li><a href="#promo">Khuyến mãi</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Khám phá thế giới mùi hương bí ẩn</h2>
    <p>Trải nghiệm tinh tế từ những note hương độc đáo</p>
    <a href="#products" class="btn">Xem sản phẩm</a>
  </section>

  <section id="products" class="products">
    <h3>Sản phẩm tầm trung</h3>
    <div class="product-list">
      <div class="product">Versace Dylan Blue</div>
      <div class="product">Mont Blanc Explorer</div>
      <div class="product">Maison Alhambra Amber</div>
    </div>
  </section>

  <section id="combo" class="combo">
    <h3>Combo theo nhóm mùi</h3>
    <div class="combo-list">
      <div class="combo">Combo Citrus Fresh</div>
      <div class="combo">Combo Woody & Warm</div>
      <div class="combo">Combo Floral Sensual</div>
    </div>
  </section>

  <section id="order" class="order-form">
    <h3>Đặt hàng ngay</h3>
    <form>
      <input type="text" placeholder="Họ tên">
      <input type="tel" placeholder="Số điện thoại">
      <textarea placeholder="Ghi chú sản phẩm (tên, số lượng)"></textarea>
      <button type="submit">Gửi đơn hàng</button>
    </form>
  </section>

  <section id="promo" class="promo">
    <div class="promo-banner">
      Tuần lễ Vàng - Giảm ngay 20% cho đơn từ 2 sản phẩm trở lên! ✨
    </div>
  </section>

  <footer>
    <p>&copy; 2025 L’OBCUR. All rights reserved.</p>
  </footer>
</body>
</html>
