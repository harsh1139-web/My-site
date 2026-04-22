# My-site
Trial
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Jolly Shoes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }

    header {
      background: #111;
      color: white;
      padding: 15px;
      text-align: center;
      font-size: 24px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }

    .card {
      background: white;
      width: 250px;
      margin: 15px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }

    .card img {
      width: 100%;
      border-radius: 10px;
    }

    .price {
      font-size: 18px;
      color: green;
      margin: 10px 0;
    }

    .btn {
      padding: 10px;
      margin: 5px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
      font-weight: bold;
    }

    .buy {
      background: orange;
      color: white;
    }

    .cart {
      background: #007bff;
      color: white;
    }
  </style>
</head>
<body>

<header>
  Jolly Shoes 👟
</header>

<div class="container">

  <div class="card">
    <img src="https://via.placeholder.com/250" alt="Shoe">
    <h3>Jolly Runner</h3>
    <p class="price">₹1,999</p>
    <button class="btn buy" onclick="buyNow()">Buy Now</button>
    <button class="btn cart" onclick="addToCart('Jolly Runner')">Add to Cart</button>
  </div>

  <div class="card">
    <img src="https://via.placeholder.com/250" alt="Shoe">
    <h3>Jolly Casual</h3>
    <p class="price">₹1,499</p>
    <button class="btn buy" onclick="buyNow()">Buy Now</button>
    <button class="btn cart" onclick="addToCart('Jolly Casual')">Add to Cart</button>
  </div>

</div>

<script>
  function buyNow() {
    alert("Redirecting to checkout...");
  }

  function addToCart(product) {
    alert(product + " added to cart!");
  }
</script>

</body>
</html>
