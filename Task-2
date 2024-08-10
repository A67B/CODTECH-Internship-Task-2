# CODTECH-Internship-Task-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ATON</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <!-- Menu Bar Icon -->
    <div id="menu-bar-icon" onclick="toggleSidebar()">&#9776;</div>

    <!-- Sidebar -->
    <div id="sidebar" class="sidebar">
        <a href="javascript:void(0)" class="closebtn" onclick="toggleSidebar()">&times;</a>
        <a href="project2.html" id="Home">Home</a>
        <a href="mens.html" id="Mens">Men</a>
        <a href="womens.html" id="womens">Women</a>
        <a href="kids.html" id="kids">Kids</a>
        <a href="javascript:void(0)" id="About" class="about-option">About</a>
    </div>
  
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
    </nav>

    <!-- Other pages and content -->
    <div id="login-page" class="page">
        <h2>Login</h2>
        <form id="login-form">
            <label for="login-email">Email:</label>
            <input type="email" id="login-email" required>
            <label for="login-password">Password:</label>
            <input type="password" id="login-password" required>
            <button type="submit">Login</button>
        </form>
    </div>

    <div id="signup-page" class="page">
        <h2>Sign Up</h2>
        <form id="signup-form">
            <label for="signup-name">Name:</label>
            <input type="text" id="signup-name" required>
            <label for="signup-email">Email:</label>
            <input type="email" id="signup-email" required>
            <label for="signup-password">Password:</label>
            <input type="password" id="signup-password" required>
            <button type="submit">Sign Up</button>
        </form>
    </div>

    <div id="product-list-page" class="page">
        <h2>Welcome to ATON!!</h2>
        <div class="product-list">
            <div class="product-item" data-id="1">
                <h3>Mens Clothing</h3>
                <img srcset="imagee1.jpg" width="250px" height="250px">
                <button class="w3-button w3-red checkout-button" data-url="mens.html">Checkout</button>
            </div>
            <div class="product-item" data-id="2">
                <h3>Womens Clothing</h3>
                <img srcset="imagee2.jpg" width="250px" height="250px">
                <button class="w3-button w3-red checkout-button" data-url="womens.html">Checkout</button>
            </div>
            <div class="product-item" data-id="3">
                <h3>Kids Clothing</h3>
                <img srcset="imagee3.jpg" width="250px" height="250px">
                <button class="w3-button w3-red checkout-button" data-url="kids.html">Checkout</button>
            </div>
        </div>
    </div>
    

    <div id="cart-page" class="page">
        <h2>Shopping Cart</h2>
        <div id="cart-items">
            <!-- Cart items will be dynamically added here -->
        </div>
        <div id="cart-total">
            <h3>Total: $<span id="total-price">0</span></h3>
            <button id="checkout">Checkout</button>
        </div>
    </div>
    <div id="about-aton" style="padding: 20px; text-align: center; background-color: #f8f8f8;">
        <h2>About ATON</h2>
        <p>Welcome to ATON, your one-stop shop for the latest in men's, women's, and kids fashion. This website was established this 2024.
           We offer a wide variety of high-quality clothing at competitive prices. 
           Our mission is to provide stylish and comfortable clothing for everyone.</p>
           
        <h3>Subscribe to Our Newsletter</h3>
        <p>For further information, subscribe to our email list.</p>
        
        <form id="subscribe-form" style="margin-top: 20px;">
            <input type="email" id="email-input" placeholder="Enter your email" required style="padding: 10px; width: 300px;">
            <button type="submit" class="w3-button w3-green" style="margin-top: 10px;">Subscribe</button>
        </form>
    
        <p id="thank-you-message" style="display: none; margin-top: 20px; font-weight: bold;">Thank you for the subscription!</p>
    </div>
    
    
    <script src="script2.js"></script>
    <script>
        document.getElementById('subscribe-form').addEventListener('submit', function(event) {
            event.preventDefault();
            
            // Show thank you message
            document.getElementById('thank-you-message').style.display = 'block';
            
            // Optionally, clear the email input field
            document.getElementById('email-input').value = '';
        });
        </script>
        <script>
            document.querySelector('.sidebar .about-option').addEventListener('click', function(event) {
                event.preventDefault();
                window.scrollTo({
                    top: document.body.scrollHeight,
                    behavior: 'smooth'
                });
            });
            </script>
            
            
</body>
</html>
 body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #fa1a12f9, #720501);
}

/* Menu Bar Icon */
#menu-bar-icon {
  font-size: 30px;
  cursor: pointer;
  position: fixed;
  top: 20px;
  left: 15px;
  z-index: 1001; /* Ensures it's above other content */
  color: #fff; /* White color for the menu icon */
  margin-right: 30px; /* Gap between the icon and logo */
}


/* Sidebar */
.sidebar {
  height: 100%;
  width: 0;
  position: fixed;
  top: 0;
  left: 0;
  background-color: #333;
  overflow-x: hidden;
  transition: 0.3s;
  padding-top: 60px;
  z-index: 1000; /* Ensures it's above other content */
}

/* Sidebar Links */
.sidebar a {
  padding: 10px 15px;
  text-decoration: none;
  font-size: 25px;
  color: white;
  display: block;
  transition: 0.3s;
}

.sidebar a:hover {
  color: #f1f1f1;
}

/* Close Button */
.closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

/* Sidebar open state */
.sidebar-open .sidebar {
  width: 250px;
}
.contact-section {
  padding: 20px;
  background-color: #f9f9f9;
  text-align: center;
}

.contact-section h2 {
  margin-bottom: 20px;
}

.contact-section form {
  display: inline-block;
}

.contact-section input[type="email"] {
  padding: 10px;
  font-size: 16px;
  margin-right: 10px;
}

.contact-section button {
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  cursor: pointer;
}

.contact-section button:hover {
  background-color: #45a049;
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}
/* User Menu Styles */
.w3-dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.w3-dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.w3-dropdown-content a:hover {
  background-color: #f1f1f1;
}

.w3-dropdown-click:hover .w3-dropdown-content {
  display: block;
}

.page {
  padding: 20px;
  display: none;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
}

.product-item {
  background-color: #f19180;
  border: 3px solid #333;
  border-radius: 5px;
  padding: 20px;
  margin: 20px;
  width: 300px;
  text-align: center;
}

.add-to-cart {
  background-color: #28a745;
  color: #fff;
  border: none;
  padding: 10px;
  cursor: pointer;
}

#cart-items {
  border: 1px solid #ddd;
  padding: 10px;
  margin-bottom: 10px;
  background-color: #fff;
}

#cart-total {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.checkout-button {
  margin-top: 10px; /* Adjust this value to move the button downwards */
}

.w3-button.w3-red:hover {
  background-color: blue !important; /* Blue hover effect */
}

.hidden {
  display: none;
}
document.addEventListener("DOMContentLoaded", () => {
    const cart = [];
    let totalPrice = 0;

    // Show the product list page by default
    document.getElementById("product-list-page").style.display = "block";

    // Add event listeners to checkout buttons
    document.querySelectorAll(".checkout-button").forEach(button => {
        button.addEventListener("click", function() {
            const productUrl = this.getAttribute("data-url");
            if (productUrl) {
                // Open product page in a new tab
                window.open(productUrl, '_blank');
            } else {
                console.error("No URL found for this product.");
            }
        });
    });

    // Function to add products to the cart
    function addToCart(id, name, price) {
        cart.push({ id, name, price });
        totalPrice += price;
        updateCartCount();
        updateCartItems();
    }

    // Update cart count
    function updateCartCount() {
        document.getElementById("cart-count").textContent = cart.length;
    }

    // Update cart items
    function updateCartItems() {
        const cartItemsContainer = document.getElementById("cart-items");
        cartItemsContainer.innerHTML = "";
        cart.forEach(item => {
            const cartItem = document.createElement("div");
            cartItem.textContent = `${item.name} - $${item.price}`;
            cartItemsContainer.appendChild(cartItem);
        });

        document.getElementById("total-price").textContent = totalPrice.toFixed(2);
    }

    // Handle login and sign-up forms
    document.getElementById("login-form").addEventListener("submit", event => {
        event.preventDefault();
        // Handle login logic here
        alert("Logged in successfully!");
    });

    document.getElementById("signup-form").addEventListener("submit", event => {
        event.preventDefault();
        // Handle sign-up logic here
        alert("Signed up successfully!");
    });

    // Checkout button functionality
    document.getElementById("checkout").addEventListener("click", () => {
        alert("Purchase successful!");
        cart.length = 0;
        totalPrice = 0;
        updateCartCount();
        updateCartItems();
    });

    // Sidebar toggle function
    function toggleSidebar() {
        document.body.classList.toggle('sidebar-open');
    }

    // Attach toggle function to global window object
    window.toggleSidebar = toggleSidebar;

    // Handle user menu toggle
    function toggleUserMenu() {
        document.getElementById('user-menu-content').classList.toggle('w3-show');
    }

    // Handle user logout
    function logout() {
        // Clear user session data (e.g., remove user info from localStorage)
        localStorage.removeItem('user');

        // Redirect to home page or login page
        window.location.href = 'project2.html';

        // Optionally, alert the user
        alert('You have been logged out.');
    }

    // Check if user is logged in and update the navigation bar
    const user = JSON.parse(localStorage.getItem('user'));
    if (user) {
        // Display user menu and update account button text
        document.getElementById('user-menu').style.display = 'block';
        document.querySelector('#user-menu button').textContent = `Hello, ${user.username}`;
    } else {
        // Hide user menu if no user is logged in
        document.getElementById('user-menu').style.display = 'none';
    }

    // Attach user menu toggle function to global window object
    window.toggleUserMenu = toggleUserMenu;
   
    });
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mens Clothing</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="mens.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Product List for Men's Clothing -->
    <div id="mens-clothing-page" class="page">
        <h2>Men's Clothing</h2>
        <div class="product-list">
            <div class="product-item">
                <h3>Shirt</h3>
                <img src="shirt.jpg" width="250px" height="250px">
                <p>₹599</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="shirt" data-price="599">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item">
                <h3>T-Shirt</h3>
                <img src="tshirt.jpg" width="250px" height="250px">
                <p>₹399</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="tshirt" data-price="399">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item">
                <h3>Jacket</h3>
                <img src="jacket.jpg" width="250px" height="250px">
                <p>₹1199</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="jacket" data-price="1199">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item">
                <h3>Hoodie</h3>
                <img src="Hoodie.jpg" width="250px" height="250px">
                <p>₹799</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="Hoodie" data-price="799">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item">
              <h3>Pants</h3>
              <img src="Pant.jpg" width="250px" height="250px">
              <p>₹549</p>
              <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="Pant" data-price="549">Buy</button>
              <button class="w3-button w3-green add-to-cart">Add to Cart</button>
          </div>
          <div class="product-item">
            <h3>Men's Watch</h3>
            <img src="watch.jpg" width="250px" height="250px">
            <p>₹949</p>
            <button class="w3-button w3-red buy-button" data-url="payment.html" data-product="Watch" data-price="949">Buy</button>
            <button class="w3-button w3-green add-to-cart">Add to Cart</button>
        </div>
        </div>
    </div>

    <script src="mens.js"></script>
    
  
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #7202fa, #391073);
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}

.page {
  padding: 20px;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
}

.product-item {
  background-color: #8833f1;
  border: 3px solid #333;
  border-radius: 5px;
  padding: 20px;
  margin: 20px;
  width: 300px;
  text-align: center;
}

.buy-button, .add-to-cart {
  margin-top: 10px;
  display: block;
  width: 100%;
}

.w3-button.w3-red:hover {
  background-color: blue !important;
}

.w3-button.w3-green:hover {
  background-color: darkgreen !important;
}
document.addEventListener("DOMContentLoaded", () => {
  // Add event listeners to "Buy" buttons
  document.querySelectorAll(".buy-button").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          // Save the product details to localStorage for use in the payment page
          localStorage.setItem('selectedProduct', JSON.stringify({ name, price, image }));
          
          // Redirect to the payment page
          window.location.href = "payment.html";
      });
  });

  // Existing "Add to Cart" functionality
  document.querySelectorAll(".add-to-cart").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          updateCart(image, name, price);
      });
  });

  function updateCart(image, name, price) {
      let cartItems = JSON.parse(localStorage.getItem('cartItems')) || [];
      let cartCount = parseInt(localStorage.getItem('cartCount')) || 0;
      let totalPrice = parseFloat(localStorage.getItem('totalPrice')) || 0;

      // Add the new item to the cart
      cartItems.push({ image, name, price });
      cartCount++;
      totalPrice += price;

      // Save the updated cart to localStorage
      localStorage.setItem('cartItems', JSON.stringify(cartItems));
      localStorage.setItem('cartCount', cartCount);
      localStorage.setItem('totalPrice', totalPrice);

      // Update the cart count in the navigation bar
      document.getElementById('cart-count').textContent = cartCount;

      alert("Item added to cart!");
  }
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Womens Clothing</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="womens.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Womens Clothing Page -->
    <div id="womens-clothing-page">
        <h2>Womens Clothing</h2>
        <div class="product-list">
            <div class="product-item" data-id="1">
                <h3>Women's Top</h3>
                <img src="womenstop.jpg" width="250px" height="250px">
                <p>₹489</p>
                <button class="w3-button w3-red buy-button" data-url="womens-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="2">
                <h3>Women's T-Shirt</h3>
                <img src="womenstshirt.jpg" width="250px" height="250px">
                <p>₹379</p>
                <button class="w3-button w3-red buy-button" data-url="womens-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="3">
                <h3>Women's Hoodie</h3>
                <img src="womenshoodie.jpg" width="250px" height="250px">
                <p>₹699</p>
                <button class="w3-button w3-red buy-button" data-url="womens-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="4">
                <h3>Women's Jacket</h3>
                <img src="womensjacket.jpg" width="250px" height="250px">
                <p>₹1249</p>
                <button class="w3-button w3-red buy-button" data-url="womens-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
              </div>
                <div class="product-item">
                  <h3>Women's Pants</h3>
                  <img src="Womenspants.jpg" width="250px" height="250px">
                  <p>₹899</p>
                  <button class="w3-button w3-red buy-button" data-url="payment.html">Buy</button>
                  <button class="w3-button w3-green add-to-cart">Add to Cart</button>
              </div>
              <div class="product-item">
                <h3>Women's Watch</h3>
                <img src="Womenswatch.jpg" width="250px" height="250px">
                <p>₹1099</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
              </div>
        </div>
    </div>

    <script src="womens.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #ff66b3, #ffccff);
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
}

.product-item {
  background-color: #ffccff;
  border: 3px solid #333;
  border-radius: 5px;
  padding: 20px;
  margin: 20px;
  width: 300px;
  text-align: center;
}

.buy-button {
  margin-top: 10px;
}

.add-to-cart {
  margin-top: 10px;
}
document.addEventListener("DOMContentLoaded", () => {
  // Add event listeners to "Buy" buttons
  document.querySelectorAll(".buy-button").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          // Save the product details to localStorage for use in the payment page
          localStorage.setItem('selectedProduct', JSON.stringify({ name, price, image }));
          
          // Redirect to the payment page
          window.location.href = "payment.html";
      });
  });

  // Existing "Add to Cart" functionality
  document.querySelectorAll(".add-to-cart").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          updateCart(image, name, price);
      });
  });

  function updateCart(image, name, price) {
      let cartItems = JSON.parse(localStorage.getItem('cartItems')) || [];
      let cartCount = parseInt(localStorage.getItem('cartCount')) || 0;
      let totalPrice = parseFloat(localStorage.getItem('totalPrice')) || 0;

      // Add the new item to the cart
      cartItems.push({ image, name, price });
      cartCount++;
      totalPrice += price;

      // Save the updated cart to localStorage
      localStorage.setItem('cartItems', JSON.stringify(cartItems));
      localStorage.setItem('cartCount', cartCount);
      localStorage.setItem('totalPrice', totalPrice);

      // Update the cart count in the navigation bar
      document.getElementById('cart-count').textContent = cartCount;

      alert("Item added to cart!");
  }
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kids Clothing</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="kids.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Kids Clothing Page -->
    <div id="kids-clothing-page">
        <h2>Kids Clothing</h2>
        <div class="product-list">
            <div class="product-item" data-id="1">
                <h3>Kids Shirt</h3>
                <img src="kidsshirt.jpg" width="250px" height="250px">
                <p>₹599</p>
                <button class="w3-button w3-red buy-button" data-url="kids-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="2">
                <h3>Kids T-Shirt</h3>
                <img src="kidstshirt.jpg" width="250px" height="250px">
                <p>₹449</p>
                <button class="w3-button w3-red buy-button" data-url="kids-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="3">
                <h3>Kids Hoodie</h3>
                <img src="kidshoodie.jpg" width="250px" height="250px">
                <p>₹679</p>
                <button class="w3-button w3-red buy-button" data-url="kids-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
            <div class="product-item" data-id="4">
                <h3>Kids Jacket</h3>
                <img src="kidsjacket.jpg" width="250px" height="250px">
                <p>₹559</p>
                <button class="w3-button w3-red buy-button" data-url="kids-payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
            </div>
                <div class="product-item">
                  <h3>Kids Pants</h3>
                  <img src="kidspants.jpg" width="250px" height="250px">
                  <p>₹229</p>
                  <button class="w3-button w3-red buy-button" data-url="payment.html">Buy</button>
                  <button class="w3-button w3-green add-to-cart">Add to Cart</button>
              </div>
              <div class="product-item">
                <h3>Kids Watch</h3>
                <img src="kidswatch.jpg" width="250px" height="250px">
                <p>₹899</p>
                <button class="w3-button w3-red buy-button" data-url="payment.html">Buy</button>
                <button class="w3-button w3-green add-to-cart">Add to Cart</button>
              </div>
        </div>
    </div>

    <script src="kids.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #f78da7, #ffde9e);
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
}

.product-item {
  background-color: #ffde9e;
  border: 3px solid #333;
  border-radius: 5px;
  padding: 20px;
  margin: 20px;
  width: 300px;
  text-align: center;
}

.buy-button {
  margin-top: 10px;
}

.add-to-cart {
  margin-top: 10px;
}
document.addEventListener("DOMContentLoaded", () => {
  // Add event listeners to "Buy" buttons
  document.querySelectorAll(".buy-button").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          // Save the product details to localStorage for use in the payment page
          localStorage.setItem('selectedProduct', JSON.stringify({ name, price, image }));
          
          // Redirect to the payment page
          window.location.href = "payment.html";
      });
  });

  // Existing "Add to Cart" functionality
  document.querySelectorAll(".add-to-cart").forEach(button => {
      button.addEventListener("click", () => {
          const productItem = button.closest('.product-item');
          const name = productItem.querySelector('h3').textContent;
          const price = parseFloat(productItem.querySelector('p').textContent.replace('₹', ''));
          const image = productItem.querySelector('img').src;

          updateCart(image, name, price);
      });
  });

  function updateCart(image, name, price) {
      let cartItems = JSON.parse(localStorage.getItem('cartItems')) || [];
      let cartCount = parseInt(localStorage.getItem('cartCount')) || 0;
      let totalPrice = parseFloat(localStorage.getItem('totalPrice')) || 0;

      // Add the new item to the cart
      cartItems.push({ image, name, price });
      cartCount++;
      totalPrice += price;

      // Save the updated cart to localStorage
      localStorage.setItem('cartItems', JSON.stringify(cartItems));
      localStorage.setItem('cartCount', cartCount);
      localStorage.setItem('totalPrice', totalPrice);

      // Update the cart count in the navigation bar
      document.getElementById('cart-count').textContent = cartCount;

      alert("Item added to cart!");
  }
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link rel="stylesheet" href="login.css">
</head>
<body>
    <div class="container">
        <h2>Login</h2>
        <form id="login-form">
            <label for="login-username">Username:</label>
            <input type="text" id="login-username" required>

            <label for="login-password">Password:</label>
            <input type="password" id="login-password" required>

            <button type="submit">Login</button>
        </form>
        <p id="login-error" style="color: red; display: none;">Invalid login</p>
        <p>New member? <a href="signup.html">Click here to sign up</a></p>
    </div>

    <script src="login.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #22f402, #02630a);
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  background-color: white;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.1);
  width: 500px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
}

label {
  display: block;
  margin-bottom: 8px;
  font-weight: bold;
}

input[type="text"],
input[type="password"] {
  width: 50%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  width: 100%;
  padding: 10px;
  background-color: #28a745;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #218838;
}

p {
  text-align: center;
  margin-top: 15px;
}

document.getElementById("login-form").addEventListener("submit", function(event) {
  event.preventDefault();

  const username = document.getElementById("login-username").value;
  const password = document.getElementById("login-password").value;

  const storedUsername = localStorage.getItem("username");
  const storedPassword = localStorage.getItem("password");

  if (username === storedUsername && password === storedPassword) {
      alert("Login successful!");
      window.location.href = "project2.html";
  } else {
      document.getElementById("login-error").style.display = "block";
  }
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign up</title>
    <link rel="stylesheet" href="signup.css">
</head>
<body>
    <div class="container">
        <h2>Sign Up</h2>
        <form id="login-form">
            <label for="signup">Username:</label>
            <input type="text" id="signup-username" required>
            <label for="signup-password">Password:</label>
            <input type="password" id="signup-password" required>
            <button type="submit">Sign Up</button>
        </form>
        <p>Already Signed Up? <a href="login.html">Click here to Login</a></p>
    </div>

    <script src="signup.js"></script>
</body>
</html>
/* General form container styling */
.form-container {
  width: 300px;
  margin: 100px auto;
  padding: 20px;
  background-color: #f9f9f9;
  border: 1px solid #ccc;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  text-align: center;
}

/* Heading styling */
.form-container h2 {
  margin-bottom: 20px;
  font-size: 24px;
  color: #333;
}

/* Input field styling */
.form-container label {
  display: block;
  margin-bottom: 8px;
  font-size: 14px;
  color: #333;
}

.form-container input[type="text"],
.form-container input[type="password"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-sizing: border-box;
}

/* Button styling */
.form-container button {
  width: 100%;
  padding: 10px;
  background-color: #28a745;
  border: none;
  border-radius: 5px;
  color: #fff;
  font-size: 16px;
  cursor: pointer;
}

.form-container button:hover {
  background-color: #218838;
}

/* Paragraph and link styling */
.form-container p {
  margin-top: 20px;
  font-size: 14px;
  color: #555;
}

.form-container a {
  color: #007bff;
  text-decoration: none;
}

.form-container a:hover {
  text-decoration: underline;
}
document.getElementById("signup-form").addEventListener("submit", function(event) {
  event.preventDefault();

  const username = document.getElementById("signup-username").value;
  const password = document.getElementById("signup-password").value;

  if (username && password) {
      localStorage.setItem("username", username);
      localStorage.setItem("password", password);

      alert("Signed up successfully!");
      window.location.href = "project2.html";
  }
});
document.getElementById("signup-form").addEventListener("submit", function(event) {
  event.preventDefault();

  const username = document.getElementById("signup-username").value;
  const password = document.getElementById("signup-password").value;

  if (username && password) {
      localStorage.setItem("username", username);
      localStorage.setItem("password", password);

      alert("Signed up successfully!");
      window.location.href = "project2.html";
  }
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="payment.css">
</head>
<body>

    <!-- Payment Details -->
    <div class="payment-container">
        <h2>Complete Your Purchase</h2>
        <p><strong>Product:</strong> <span id="product-name"></span></p>
        <p><strong>Price per item:</strong> <span id="product-price"></span></p>
        <img id="product-image" width="100" height="100" src="" alt="Product Image">
        
        <p><strong>Quantity:</strong> 
            <input type="number" id="quantity" value="1" min="1">
        </p>
        <p><strong>Total Amount:</strong> <span id="total-amount">₹0.00</span></p>

        <h3>Payment Method</h3>
        <input type="radio" name="payment-method" value="cash" id="cash"> Cash on Delivery<br>
        <input type="radio" name="payment-method" value="card" id="card"> Credit/Debit Card<br>
        <input type="radio" name="payment-method" value="upi" id="upi"> UPI<br>

        <div id="card-details" class="hidden">
            <h4>Card Details</h4>
            <p>Card Number: <input type="text" id="card-number" placeholder="Enter your card number"></p>
            <p>CVV: <input type="text" id="cvv" placeholder="Enter CVV"></p>
        </div>

        <div id="upi-details" class="hidden">
            <h4>UPI Details</h4>
            <p>UPI ID: <input type="text" id="upi-id" placeholder="Enter your UPI ID"></p>
        </div>

        <button class="w3-button w3-green" id="pay-button">Pay</button>
        <button class="w3-button w3-red" id="cancel-button">Cancel</button>
        <button class="w3-button w3-blue" id="refresh-btn">⟳</button>
    </div>

    <script src="payment.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #34c4f0, #1d72b8);
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}

.page {
  padding: 20px;
}

#total-amount {
  font-size: 18px;
  margin-bottom: 20px;
}

.payment-option {
  margin-bottom: 20px;
}

.payment-option input[type="radio"] {
  margin-right: 10px;
}

.hidden {
  display: none;
}

#card-details,
#upi-details {
  margin-top: 10px;
}

#pay-button,
#cancel-button {
  margin-top: 20px;
  display: block;
  width: 100%;
}
document.addEventListener("DOMContentLoaded", () => {
  // Retrieve the selected product from localStorage
  const selectedProduct = JSON.parse(localStorage.getItem('selectedProduct'));
  
  if (selectedProduct) {
      document.getElementById('product-name').textContent = selectedProduct.name;
      document.getElementById('product-price').textContent = `₹${selectedProduct.price}`;
      document.getElementById('product-image').src = selectedProduct.image;

      // Listen to the quantity input change to update the total price
      document.getElementById('quantity').addEventListener('input', (e) => {
          const quantity = parseInt(e.target.value);
          const total = selectedProduct.price * quantity;
          document.getElementById('total-amount').textContent = `₹${total.toFixed(2)}`;
      });
  }

  // Refresh button functionality to reset amount
  document.getElementById('refresh-btn').addEventListener('click', () => {
      document.getElementById('quantity').value = 1;
      document.getElementById('total-amount').textContent = `₹${selectedProduct.price.toFixed(2)}`;
  });

  // Show/hide payment details based on selected method
  const cardDetails = document.getElementById('card-details');
  const upiDetails = document.getElementById('upi-details');

  document.querySelectorAll('input[name="payment-method"]').forEach(radio => {
      radio.addEventListener('change', () => {
          if (radio.value === 'card') {
              cardDetails.classList.remove('hidden');
              upiDetails.classList.add('hidden');
          } else if (radio.value === 'upi') {
              upiDetails.classList.remove('hidden');
              cardDetails.classList.add('hidden');
          } else {
              cardDetails.classList.add('hidden');
              upiDetails.classList.add('hidden');
          }
      });
  });

  // Pay button functionality
  document.getElementById('pay-button').addEventListener('click', () => {
      const paymentMethod = document.querySelector('input[name="payment-method"]:checked').value;

      if (paymentMethod === 'card' || paymentMethod === 'upi') {
          alert("Wait, processing payment...");
          setTimeout(() => {
              alert("Thank you for purchasing from ATON, your order has been placed.");
          }, 2000); // 2-second delay for payment processing simulation
      } else {
          alert("Thank you for purchasing from ATON, your order has been placed.");
      }
  });

  // Cancel button functionality
  document.getElementById('cancel-button').addEventListener('click', () => {
      window.location.href = "project2.html"; // Redirect to home page
  });
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="payment2.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Payment Page -->
    <div id="payment-page" class="page">
        <button id="refresh-button" class="w3-button w3-gray">⟳</button>
        <h2>Payment</h2>
        <p id="total-amount">Your total amount is: ₹<span id="amount">0</span></p>
        <form id="payment-form">
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="cash" checked>
                    Cash on Delivery
                </label>
            </div>
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="card">
                    Card
                </label>
                <div id="card-details" class="hidden">
                    <label for="card-no">Card Number:</label>
                    <input type="text" id="card-no" name="card-no">
                    <label for="cvv">CVV:</label>
                    <input type="text" id="cvv" name="cvv">
                </div>
            </div>
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="upi">
                    UPI
                </label>
                <div id="upi-details" class="hidden">
                    <label for="upi-id">UPI ID:</label>
                    <input type="text" id="upi-id" name="upi-id">
                </div>
            </div>
            <button type="button" id="pay-button" class="w3-button w3-blue">Pay</button>
            <button type="button" id="cancel-button" class="w3-button w3-red">Cancel</button>
        </form>
        <div id="processing-message" class="hidden">
            <p>Wait, processing payment...</p>
        </div>
        <div id="thank-you-message" class="hidden">
            <p>Thank you for purchasing from ATON. Your order has been placed.</p>
        </div>
    </div>

    <script src="payment2.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment</title>
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="payment2.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav>
        <div class="nav-left">
            <a href="#" class="logo">ATON</a>
        </div>
        <div class="nav-links">
            <a href="project2.html">Home</a>
            <a href="login.html">Login</a>
            <a href="signup.html">Sign Up</a>
            <a href="cart.html">Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Payment Page -->
    <div id="payment-page" class="page">
        <button id="refresh-button" class="w3-button w3-gray">⟳</button>
        <h2>Payment</h2>
        <p id="total-amount">Your total amount is: ₹<span id="amount">0</span></p>
        <form id="payment-form">
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="cash" checked>
                    Cash on Delivery
                </label>
            </div>
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="card">
                    Card
                </label>
                <div id="card-details" class="hidden">
                    <label for="card-no">Card Number:</label>
                    <input type="text" id="card-no" name="card-no">
                    <label for="cvv">CVV:</label>
                    <input type="text" id="cvv" name="cvv">
                </div>
            </div>
            <div class="payment-option">
                <label>
                    <input type="radio" name="payment-method" value="upi">
                    UPI
                </label>
                <div id="upi-details" class="hidden">
                    <label for="upi-id">UPI ID:</label>
                    <input type="text" id="upi-id" name="upi-id">
                </div>
            </div>
            <button type="button" id="pay-button" class="w3-button w3-blue">Pay</button>
            <button type="button" id="cancel-button" class="w3-button w3-red">Cancel</button>
        </form>
        <div id="processing-message" class="hidden">
            <p>Wait, processing payment...</p>
        </div>
        <div id="thank-you-message" class="hidden">
            <p>Thank you for purchasing from ATON. Your order has been placed.</p>
        </div>
    </div>

    <script src="payment2.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: linear-gradient(to right, #34c4f0, #1d72b8);
}

nav {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .nav-left {
  display: flex;
  align-items: center;
  margin-left: 60px;
  margin-top: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  margin: 0 15px;
}

.logo {
  font-size: 24px;
}

.page {
  padding: 20px;
  position: relative; /* Added for button positioning */
}

#total-amount {
  font-size: 18px;
  margin-bottom: 20px;
}

.payment-option {
  margin-bottom: 20px;
}

.payment-option input[type="radio"] {
  margin-right: 10px;
}

.hidden {
  display: none;
}

#card-details,
#upi-details {
  margin-top: 10px;
}

#pay-button,
#cancel-button {
  margin-top: 20px;
  display: block;
  width: 100%;
}

#refresh-button {
  position: absolute;
  top: 20px;
  right: 20px;
}
document.addEventListener("DOMContentLoaded", () => {
  const cardDetails = document.getElementById('card-details');
  const upiDetails = document.getElementById('upi-details');
  const processingMessage = document.getElementById('processing-message');
  const thankYouMessage = document.getElementById('thank-you-message');
  const payButton = document.getElementById('pay-button');
  const cancelButton = document.getElementById('cancel-button');
  const refreshButton = document.getElementById('refresh-button');
  const amountElement = document.getElementById('amount');

  // Example total amount (this could be set dynamically based on cart total)
  const initialAmount = 2495; // This value should come from cart data
  amountElement.textContent = initialAmount;

  // Show/hide payment details based on selected method
  document.querySelectorAll('input[name="payment-method"]').forEach(radio => {
      radio.addEventListener('change', () => {
          if (radio.value === 'card') {
              cardDetails.classList.remove('hidden');
              upiDetails.classList.add('hidden');
          } else if (radio.value === 'upi') {
              upiDetails.classList.remove('hidden');
              cardDetails.classList.add('hidden');
          } else {
              cardDetails.classList.add('hidden');
              upiDetails.classList.add('hidden');
          }
      });
  });

  // Handle Pay button click
  payButton.addEventListener('click', () => {
      processingMessage.classList.remove('hidden');
      setTimeout(() => {
          processingMessage.classList.add('hidden');
          thankYouMessage.classList.remove('hidden');
          setTimeout(() => {
              window.location.href = 'project2.html'; // Redirect to homepage after thank you message
          }, 2000);
      }, 2000); // Simulate processing time
  });

  // Handle Cancel button click
  cancelButton.addEventListener('click', () => {
      window.location.href = 'project2.html'; // Redirect to homepage
  });

  // Handle Refresh button click
  refreshButton.addEventListener('click', () => {
      amountElement.textContent = '0'; // Reset amount to zero
  });
});





