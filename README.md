<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TsHiRt X - Trendy T-Shirts</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
      color: #f1f1f1;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.8em;
      color: #ffcc00; 
    }

    nav a {
      color: white;
      margin-left: 25px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffcc00;
    }

    .banner {
      width: 100%;
      height: 80vh;
      background: url('image/img.jpg') no-repeat center center;
      background-size: cover;
      background-color: #222;
    }

    .products {
      padding: 60px 40px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .product {
      background: #1e1e1e;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 25px rgba(0, 0, 0, 0.6);
    }

    .product img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      border-radius: 10px;
    }

    .product h3 {
      margin: 15px 0 10px;
      font-size: 1.2em;
      color: #fff;
    }

    .product p {
      color: #28a745;
      font-weight: bold;
      font-size: 1.1em;
    }

    .buttons {
      margin-top: 15px;
    }

    .buttons button {
      padding: 10px 15px;
      margin: 5px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s ease;
    }

    .buy {
      background-color: #28a745;
      color: white;
    }

    .cart {
      background-color: #0d6efd;
      color: white;
    }

    .buy:hover {
      background-color: #218838;
    }

    .cart:hover {
      background-color: #0a58ca;
    }

    footer {
      background-color: #111;
      color: white;
      padding: 40px 20px;
      margin-top: 50px;
    }

    .footer-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 30px;
      max-width: 1200px;
      margin: auto;
    }

    .footer-column h4 {
      margin-bottom: 15px;
      font-size: 1.2em;
      border-bottom: 2px solid #555;
      padding-bottom: 5px;
    }

    .footer-column ul {
      list-style: none;
    }

    .footer-column ul li {
      margin-bottom: 10px;
    }

    .footer-column ul li a {
      color: #ccc;
      text-decoration: none;
    }

    .footer-column ul li a:hover {
      color: white;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav a {
        margin: 10px 10px 0 0;
        display: inline-block;
      }

      .product img {
        height: 200px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>TsHiRt X</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="collection.html">Collection</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <div class="banner"></div>

  <section class="products">
    <div class="product">
      <img src="image/img01.jpg" alt="T-shirt 1" />
      <h3>Classic White Tee</h3>
      <p>₹499</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img02.jpg" alt="T-shirt 2" />
      <h3>Black Urban Fit</h3>
      <p>₹599</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img03.jpg" alt="T-shirt 3" />
      <h3>Graphic Street Tee</h3>
      <p>₹649</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img04.jpg" alt="T-shirt 4" />
      <h3>Modern Red Tee</h3>
      <p>₹599</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img05.jpg" alt="T-shirt 5" />
      <h3>Summer Blue Tee</h3>
      <p>₹559</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img06.jpg" alt="T-shirt 6" />
      <h3>Olive Green Tee</h3>
      <p>₹499</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img07.jpg" alt="T-shirt 7" />
      <h3>Navy Blue Tee</h3>
      <p>₹599</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>

    <div class="product">
      <img src="image/img08.jpg" alt="T-shirt 8" />
      <h3>Casual Yellow Tee</h3>
      <p>₹449</p>
      <div class="buttons">
        <button class="buy">Buy Now</button>
        <button class="cart">Add to Cart</button>
      </div>
    </div>
  </section>

  <footer>
    <div class="footer-container">
      <div class="footer-column">
        <h4>About Us</h4>
        <p>TsHiRt X offers high-quality, trendy T-shirts for every style. Comfort and fashion combined at unbeatable prices.</p>
      </div>
      <div class="footer-column">
        <h4>Quick Links</h4>
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="collection.html">Collection</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </div>
      <div class="footer-column">
        <h4>Contact</h4>
        <ul>
          <li>Email: support@tshirtx.com</li>
          <li>Phone: +91-9876543210</li>
          <li>Location: Chandigarh, India</li>
        </ul>
      </div>
    </div>
  </footer>

</body>
</html>
