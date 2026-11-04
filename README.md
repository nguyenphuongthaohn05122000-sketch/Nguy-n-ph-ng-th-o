
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NOTPAS COSMETICS</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    background: #fff8fa;
    color: #444;
}
header {
    background: #f5b8ce;
    padding: 22px;
    text-align: center;
}
.logo {
    font-size: 32px;
    font-weight: bold;
    color: white;
}
nav {
    background: white;
    padding: 18px;
    text-align: center;
}
nav a {
    text-decoration: none;
    color: #c45d85;
    margin: 15px;
    font-weight: bold;
}
.banner {
    background: #fce0e9;
    text-align: center;
    padding: 65px 20px;
}
.banner h1 {
    color: #c04c7a;
    font-size: 38px;
}
.banner p {
    margin: 15px;
}
button {
    background: #d96d98;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 20px;
    cursor: pointer;
}
section {
    padding: 35px 20px;
    text-align: center;
}
.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    max-width: 1100px;
    margin: auto;
}
.product {
    background: white;
    padding: 18px;
    border-radius: 12px;
    box-shadow: 0 2px 8px #ead5dd;
}
.product img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
}
.product h3 {
    margin: 12px;
    color: #bd527b;
}
.price {
    color: #e14e83;
    font-weight: bold;
    margin: 10px;
}
footer {
    background: #d96d98;
    color: white;
    text-align: center;
    padding: 25px;
}
</style>
</head>

<body>

<header>
    <div class="logo">NOTPAS COSMETICS</div>
    <p>Vẻ đẹp tự nhiên - Tự tin tỏa sáng</p>
</header>

<nav>
    <a href="#">Trang chủ</a>
    <a href="#about">Giới thiệu</a>
    <a href="#products">Sản phẩm</a>
    <a href="#contact">Liên hệ</a>
</nav>

<div class="banner">
    <h1>WELCOME TO NOTPAS</h1>
    <p>Khám phá thế giới mỹ phẩm và chăm sóc sắc đẹp</p>
    <button onclick="location.href='#products'">
        Mua sắm ngay
    </button>
</div>

<section id="about">
    <h2>Về NOTPAS COSMETICS</h2>
    <p>Chúng tôi mang đến những sản phẩm làm đẹp,
    chăm sóc da và mỹ phẩm chất lượng.</p>
</section>

<section id="products">
    <h2>SẢN PHẨM NỔI BẬT</h2>
    <br>
    <div class="products">

        <div class="product">
            <img src="https://placehold.co/300x200?text=Serum" alt="Serum">
            <h3>Serum dưỡng da</h3>
            <p class="price">189.000đ</p>
            <button onclick="alert('Đã thêm vào giỏ hàng!')">
                Mua ngay
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x200?text=Cleanser" alt="Sữa rửa mặt">
            <h3>Sữa rửa mặt</h3>
            <p class="price">129.000đ</p>
            <button onclick="alert('Đã thêm vào giỏ hàng!')">
                Mua ngay
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x200?text=Lipstick" alt="Son môi">
            <h3>Son môi</h3>
            <p class="price">159.000đ</p>
            <button onclick="alert('Đã thêm vào giỏ hàng!')">
                Mua ngay
            </button>
        </div>

        <div class="product">
            <img src="https://placehold.co/300x200?text=Sunscreen" alt="Kem chống nắng">
            <h3>Kem chống nắng</h3>
            <p class="price">199.000đ</p>
            <button onclick="alert('Đã thêm vào giỏ hàng!')">
                Mua ngay
            </button>
        </div>

    </div>
</section>

<section id="contact">
    <h2>LIÊN HỆ VỚI CHÚNG TÔI</h2>
    <p>Email: notpascosmetics@gmail.com</p>
    <p>Hotline: 0988 888 888</p>
</section>

<footer>
    <p>© 2026 NOTPAS COSMETICS</p>
    <p>Cảm ơn bạn đã lựa chọn chúng tôi!</p>
</footer>

</body>
</html>
