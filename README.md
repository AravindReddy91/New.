# <!DOCTYPE html>
<html>
<head>
  <title>My E-Commerce Website</title>
</head>
<body>
  <h1>Welcome to My E-Commerce Website</h1>

  <h2>Featured Products:</h2>
  <ul>
    <li>Product 1</li>
    <li>Product 2</li>
    <li>Product 3</li>
  </ul>

  <h2>Special Deals:</h2>
  <ul>
    <li>Deal 1</li>
    <li>Deal 2</li>
    <li>Deal 3</li>
  </ul>

  <form action="/cart" method="POST">
    <h2>Shopping Cart:</h2>
    <p>
      Product: <input type="text" name="product" />
      Quantity: <input type="number" name="quantity" />
      <button type="submit">Add to Cart</button>
    </p>
  </form>
</body>
</html>
