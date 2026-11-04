<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NOTPAS - My pham cham soc da</title>
<style>
* {box-sizing:border-box}
body {
  margin:0;
  font-family:Arial,sans-serif;
  background:#fff8fa;
  color:#49363d;
}
header {
  background:#f3dce5;
  padding:22px 8%;
  display:flex;
  justify-content:space-between;
  align-items:center;
}
.logo {font-size:30px;font-weight:bold;color:#a64f70}
nav a {
  margin-left:22px;
  text-decoration:none;
  color:#49363d;
}
.hero {
  text-align:center;
  padding:90px 20px;
  background:#f8e9ee;
}
.hero h1 {font-size:45px;color:#a64f70}
.hero p {font-size:18px}
button {
  background:#a64f70;color:white;
  border:0;padding:13px 25px;
  border-radius:25px;cursor:pointer;
}
.products {
  padding:45px 8%;
  text-align:center;
}
.list {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(210px,1fr));
  gap:25px;
}
.product {
  background:white;padding:20px;
  border-radius:15px;
  box-shadow:0 3px 12px #eadce1;
}
.product img {
  width:100%;height:190px;
  object-fit:cover;border-radius:12px;
}
.price {color:#b34c73;font-weight:bold}
footer {
  background:#f3dce5;
  text-align:center;padding:25px;
}
</style>
</head>
<body>

<header>
  <div class="logo">NOTPAS</div>
  <nav>
    <a href="#">Trang chu</a>
    <a href="#products">San pham</a>
    <a href="#about">Gioi thieu</a>
    <a href="#contact">Lien he</a>
  </nav>
</header>

<section class="hero">
  <h1>NOTPAS BEAUTY</h1>
  <p>Cham soc lan da, toa sang ve dep tu nhien.</p>
  <button onclick="location.href='#products'">
    Kham pha ngay
  </button>
</section>

<section class="products" id="products">
  <h2>SẢN PHẨM NỔI BẬT</h2>
  <div class="list">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1608248543803-ba4f8c70ae0b?w=500" alt="Mỹ phẩm dưỡng da">
      <h3>Kem dưỡng da</h3>
      <p>Dưỡng ẩm và chăm sóc da mỗi ngày.</p>
      <p class="price">199.000đ</p>
      <button onclick="alert('Bạn đã chọn Kem dưỡng da!')">Mua ngay</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1601049541289-9b1b7bbbfe19?w=500" alt="Serum">
      <h3>Serum dưỡng da</h3>
      <p>Chăm sóc và nuôi dưỡng làn da.</p>
      <p class="price">249.000đ</p>
      <button onclick="alert('Bạn đã chọn Serum!')">Mua ngay</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1556229010-6c3f2c9ca5f8?w=500" alt="Sữa rửa mặt">
      <h3>Sữa rửa mặt</h3>
      <p>Làm sạch da nhẹ nhàng.</p>
      <p class="price">129.000đ</p>
      <button onclick="alert('Bạn đã chọn Sữa rửa mặt!')">Mua ngay</button>
    </div>
  </div>
</section>

<section id="about" class="products">
  <h2>VỀ NOTPAS</h2>
  <p>NOTPAS mang đến những sản phẩm làm đẹp,
  giúp bạn tự tin chăm sóc và yêu thương bản thân.</p>
</section>

<footer id="contact">
  <h3>NOTPAS BEAUTY</h3>
  <p>Website mỹ phẩm và chăm sóc sắc đẹp</p>
  <p>Liên hệ: notpasbeauty@gmail.com</p>
  <p>© 2026 NOTPAS. All rights reserved.</p>
</footer>

</body>
</html>
