# product-detail
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Gà Rán Pop Art</title>
<style>
body {
  margin: 0;
  font-family: 'Arial Black', sans-serif;
  background: #ff2d2d;
  color: #fff;
}

/* HERO */
.hero {
  padding: 60px;
  text-align: center;
  background: radial-gradient(circle, #ff4d4d, #cc0000);
}

.hero h1 {
  font-size: 60px;
  text-transform: uppercase;
  text-shadow: 4px 4px #000;
}

.hero p {
  font-size: 20px;
}

/* PRODUCT */
.product {
  display: flex;
  padding: 50px;
  gap: 40px;
  align-items: center;
}

.product img {
  width: 350px;
  border: 5px solid #000;
  box-shadow: 10px 10px #000;
}

/* INFO */
.info {
  max-width: 500px;
}

.price {
  font-size: 40px;
  color: #ffd400;
  text-shadow: 2px 2px #000;
}

.btn {
  margin-top: 20px;
  padding: 15px 30px;
  background: #ffd400;
  color: #000;
  border: none;
  font-size: 18px;
  cursor: pointer;
  box-shadow: 5px 5px #000;
  transition: 0.2s;
}

.btn:hover {
  transform: scale(1.1);
}

/* POP ART DECOR */
.bubble {
  position: absolute;
  top: 20px;
  left: 20px;
  background: yellow;
  color: black;
  padding: 10px 20px;
  font-weight: bold;
  border: 3px solid black;
  transform: rotate(-10deg);
}

/* FOOTER */
.footer {
  text-align: center;
  padding: 20px;
  background: black;
}
</style>
</head>

<body>

<div class="bubble">HOT!</div>

<section class="hero">
  <h1>CRISPY CHICKEN</h1>
  <p>Giòn rụm – Cay nhẹ – Ăn là ghiền!</p>
</section>

<section class="product">
  <img src="https://images.unsplash.com/photo- fried-chicken" alt="gà rán">

  <div class="info">
    <h2>Gà rán siêu giòn</h2>
    <p>
      Lớp vỏ giòn tan, thịt mềm mọng nước,
      tẩm ướp gia vị đặc biệt theo phong cách Mỹ.
    </p>

    <div class="price">79.000đ</div>

    <button class="btn">MUA NGAY</button>
  </div>
</section>

<section class="footer">
  <p>🔥 Free ship toàn quốc - Đặt ngay!</p>
</section>

</body>
</html>
