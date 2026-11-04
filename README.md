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

<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>COCOON VIETNAM - Mỹ phẩm thuần chay</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f8f8f1;
    color: #333;
}

header {
    background: #244b35;
    color: white;
    padding: 25px;
    text-align: center;
}

.logo {
    font-size: 38px;
    font-weight: bold;
    letter-spacing: 5px;
}

header p {
    margin-top: 8px;
}

nav {
    background: #fff;
    padding: 18px;
    text-align: center;
    position: sticky;
    top: 0;
}

nav a {
    text-decoration: none;
    color: #31583c;
    margin: 15px;
    font-weight: bold;
}

.banner {
    background: #dce8d5;
    text-align: center;
    padding: 90px 20px;
}

.banner h1 {
    font-size: 42px;
    color: #244b35;
}

.banner p {
    margin: 20px;
    font-size: 18px;
}

button {
    background: #315d3e;
    color: white;
    border: none;
    padding: 13px 25px;
    border-radius: 5px;
    cursor: pointer;
}

section {
    padding: 50px 25px;
    text-align: center;
}

h2 {
    color: #31583c;
    margin-bottom: 25px;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    max-width: 1100px;
    margin: auto;
}

.product {
    background: white;
    padding: 18px;
    border-radius: 12px;
    box-shadow: 0 3px 10px #ddd;
}

.product img {
    width: 100%;
    height: 210px;
    object-fit: cover;
    border-radius: 8px;
}

.product h3 {
    color: #31583c;
    margin: 15px 0;
}

.price {
    color: #a45d35;
    font-weight: bold;
    margin: 12px;
}

.about {
    background: #e8eddf;
    line-height: 1.8;
}

footer {
    background: #244b35;
    color: white;
    text-align: center;
    padding: 30px;
    line-height: 2;
}
</style>
</head>

<body>

<header>
    <div class="logo">COCOON</div>
    <p>Mỹ phẩm thuần chay Việt Nam</p>
</header>

<nav>
    <a href="#home">Trang chủ</a>
    <a href="#about">Giới thiệu</a>
    <a href="#products">Sản phẩm</a>
    <a href="#contact">Liên hệ</a>
</nav>

<div class="banner" id="home">
    <h1>COCOON VIETNAM</h1>
    <p>Thiên nhiên Việt Nam - Vẻ đẹp thuần chay</p>
    <button onclick="location.href='#products'">
        KHÁM PHÁ NGAY
    </button>
</div>

<section id="about" class="about">
    <h2>VỀ THƯƠNG HIỆU COCOON</h2>
    <p>
    Cocoon là thương hiệu mỹ phẩm thuần chay của Việt Nam,
    lấy cảm hứng từ nguyên liệu thiên nhiên Việt Nam.
    Các sản phẩm hướng đến chăm sóc da và tóc,
    đồng thời đề cao vẻ đẹp bền vững.
    </p>
</section>

<section id="products">
    <h2>SẢN PHẨM NỔI BẬT</h2>

    <div class="products">

        <div class="product">
            <img src="https://placehold.co/300x250?text=Cocoon+Coffee" alt="Tẩy da chết cà phê">
            <h3>Tẩy da chết cà phê Đắk Lắk</h3>
            <p class="price">Giá tham khảo: 165.000đ</p>
            <button onclick="addCart('Tẩy da chết cà phê Đắk Lắk')">
            Thêm vào giỏ
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x250?text=Cocoon+Cleanser" alt="Sữa rửa mặt bí đao">
            <h3>Sữa rửa mặt bí đao</h3>
            <p class="price">Giá tham khảo: 195.000đ</p>
            <button onclick="addCart('Sữa rửa mặt bí đao')">
            Thêm vào giỏ
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x250?text=Cocoon+Rose" alt="Nước dưỡng hoa hồng">
            <h3>Nước dưỡng hoa hồng</h3>
            <p class="price">Giá tham khảo: 175.000đ</p>
            <button onclick="addCart('Nước dưỡng hoa hồng')">
            Thêm vào giỏ
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x250?text=Cocoon+Hair" alt="Dầu gội bưởi">
            <h3>Dầu gội bưởi</h3>
            <p class="price">Giá tham khảo: 195.000đ</p>
            <button onclick="addCart('Dầu gội bưởi')">
            Thêm vào giỏ
            </button>
        </div>

    </div>
</section>

<section>
    <h2>GIÁ TRỊ CỦA COCOON</h2>
    <p>Thuần chay - Thiên nhiên - Bền vững</p>
    <p>Ưu tiên nguyên liệu có nguồn gốc từ Việt Nam.</p>
</section>

<section>
    <h2>GIỎ HÀNG</h2>
    <p id="cart">Bạn chưa chọn sản phẩm nào.</p>
</section>

<section id="contact">
    <h2>LIÊN HỆ</h2>
    <p>Website: cocoonvietnam.com</p>
    <p>Email: support@cocoonvietnam.com</p>
</section>

<footer>
    <h2 style="color:white">COCOON VIETNAM</h2>
    <p>Mỹ phẩm thuần chay Việt Nam</p>
    <p>© 2026 COCOON. All Rights Reserved.</p>
</footer>

<script>
let cart = [];

function addCart(product) {
    cart.push(product);
    document.getElementById("cart").innerHTML =
    "Bạn đã chọn " + cart.length + " sản phẩm:<br>" +
    cart.join("<br>");
    alert("Đã thêm sản phẩm vào giỏ hàng!");
}
</script>

</body>
</html>
