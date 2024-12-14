# Ex.07 Restaurant Website
# Date:08/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DFC Chicken - Home</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>DFC Chicken</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="main">
        <div class="main-content">
            <h2>Welcome to DFC Chicken!</h2>
            <p>Serving the best fried chicken in town. Crispy, juicy, and delicious!</p>
            <a href="menu.html" class="cta-button">Explore Our Menu</a>
        </div>
    </section>

    <footer>
        <p>With love from DFC Chicken!</p>
    </footer>
</body>
</html>

~~~
menu.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DFC Chicken - Menu</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>DFC Chicken</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="fchichen.jpeg" alt="Classic Fried Chicken">
                <h3>Classic Fried Chicken</h3>
                <h4>$5.99</h4>
                <button class="cart">Add to Cart</button>
            </div>
            <div class="menu-item">
                <img src="wings.jpeg" alt="Spicy Wings">
                <h3>Spicy Wings</h3>
                <h4>$6.99</h4>
                <button class="cart">Add to Cart</button>
            </div>
            <div class="menu-item">
                <img src="sandwich.jpg" alt="Chicken Sandwich">
                <h3>Chicken Sandwich</h3>
                <h4>$5.00</h4>
                <button class="cart">Add to Cart</button>
            </div>
            <div class="menu-item">
                <img src="bucket.jpg" alt="Classic Fried Chicken">
                <h3>Bucket Fried Chicken</h3>
                <h4>$9.00</h4>
                <button class="cart">Add to Cart</button>
            </div>
        </div>
    </section>
    <div class="menu-items">
        <div class="menu-item">
            <img src="burger1.jpg" alt="Classic Fried Chicken">
            <h3>Classic Burger</h3>
            <h4>$10</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="burger2.jpg" alt="Spicy Wings">
            <h3>Cheese Burger</h3>
            <h4>$10</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="burger3.jpg" alt="Chicken Sandwich">
            <h3>Cream Burger</h3>
            <h4>$10</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="burger4.jpg" alt="Classic Fried Chicken">
            <h3>Classic Bun Burger</h3>
            <h4>$10</h4>
            <button class="cart">Add to Cart</button>
        </div>
    </div>
    <div class="menu-items">
        <div class="menu-item">
            <img src="rice1.jpg" alt="Classic Fried Chicken">
            <h3>Fried Chicken Rice</h3>
            <h4>$15</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="rice2.jpg" alt="Spicy Wings">
            <h3>Round chicken Rice</h3>
            <h4>$15</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="rice4.jpg" alt="Chicken Sandwich">
            <h3>Chicken Balls Rice</h3>
            <h4>$15</h4>
            <button class="cart">Add to Cart</button>
        </div>
        <div class="menu-item">
            <img src="combo1.jpg" alt="Classic Fried Chicken">
            <h3>Fried Chicken Combo</h3>
            <h4>$19.99</h4>
            <button class="cart">Add to Cart</button>
        </div>
    </div>
   
    <footer>
        <p>With love from DFC Chicken!</p>
    </footer>
</body>
</html>

~~~
admin.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DFC Chicken - Admin</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>DFC Chicken</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="admin">
        <h2>Our Admin Team</h2>
        <div class="admin-photos">
            <div class="admin-photo">
                <img src="admin1.png" alt="Admin 1">
                <p>John</p>
            </div>
            <div class="admin-photo">
                <img src="admin2.png" alt="Admin 2">
                <p>Tony</p>
            </div>
            <div class="admin-photo">
                <img src="admin3.jpeg" alt="Admin 3">
                <p>Hemsworth</p>
            </div>
            <div class="admin-photo">
                <img src="admin4.jpeg" alt="Admin 4">
                <p>Andrew</p>
            </div>
            <div class="admin-photo">
                <img src="admin5.jpeg" alt="Admin 5">
                <p>Tom</p>
            </div>
            <div class="admin-photo">
                <img src="admin6.jpeg" alt="Admin 6">
                <p>Chris Evans</p>
            </div>
        </div>
    </section>

    <footer>
        <p>With love from DFC Chicken!</p>
    </footer>
</body>
</html>

~~~
contact.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DFC Chicken - Contact Us</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>DFC Chicken</h1>
        </div>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-details">
            <p><strong>Address:</strong> 123 Chicken Lane, Flavor Town</p>
            <p><strong>Phone:</strong> +123 456 7890</p>
            <p><strong>Email:</strong> support@dfcchicken.com</p>
        </div>
    </section>

    <footer>
        <p>With love from DFC Chicken!</p>
    </footer>
</body>
</html>

~~~
rest.css
~~~
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background-color: #ffcc00;
}

header .logo h1 {
    margin: 0;
    color: #fff;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 1.5rem;
    margin: 0;
    padding: 0;
}

header nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 3rem 1rem;
    background: url('dfcbanner3.png') no-repeat center/cover;
    color: #fff;
}

.hero-content h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-button {
    display: inline-block;
    padding: 0.8rem 1.5rem;
    background-color: #ff6600;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

#menu {
    padding: 2rem;
    background-color: #f8f8f8;
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 1.5rem;
}

.menu-item {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 1rem;
    text-align: center;
    width: 250px;
}

.menu-item img {
    max-width: 100%;
    border-radius: 5px;
}

.menu-item h3, .menu-item h4 {
    margin: 0.5rem 0;
}

.cart {
    background-color: #ff6600;
    color: #fff;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
}

#admin {
    padding: 2rem;
    background-color: #fff;
    text-align: center;
}

.admin-photos {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 1.5rem;
}

.admin-photo {
    text-align: center;
    width: 150px;
}

.admin-photo img {
    width: 100%;
    border-radius: 50%;
    border: 2px solid #ffcc00;
}

.admin-photo p {
    margin-top: 0.5rem;
    font-weight: bold;
}

#contact {
    padding: 2rem;
    background-color: #f0f0f0;
    text-align: center;
}

.contact-details p {
    margin: 0.5rem 0;
    font-size: 1rem;
}

.contact-details strong {
    color: #ff6600;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: #fff;
}
~~~
# OUTPUT:
![home](https://github.com/user-attachments/assets/0f0fbfe9-989f-420c-b8a7-8812fea55057)

![menu](https://github.com/user-attachments/assets/739ef449-ee9b-4414-95e1-e0e7f2b46ade)

![admi](https://github.com/user-attachments/assets/11c11178-5626-4827-b130-93ddfb3b2c31)

![cont](https://github.com/user-attachments/assets/b2fe64be-89c7-410a-b8cc-a6763af70d8a)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
