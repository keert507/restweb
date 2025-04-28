# Ex.07 Restaurant Website
## Date:28.04.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Roast & Toast</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="banner">
        <h1>Welcome to Roast & Toast </h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="intro">
        <h2>Where every flavor tells a story.</h2>
        <p>Hundreds of flavors under one roof.</p>
    </section>

    <footer>
        <p>© KEERTHANA T (212224100031)</p>
    </footer>
</body>
</html>
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header.banner {
            background-color: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header.banner h1 {
            margin: 0;
        }

        header.banner nav ul {
            list-style: none;
            padding: 0;
            margin: 10px 0 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        header.banner nav ul li {
            display: inline;
        }

        header.banner nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header.banner nav ul li a:hover {
            color: #ff6347;
        }

        .menu {
            padding: 20px;
            text-align: center;
        }

        .menu h2 {
            font-size: 2em;
            color: #222;
            margin-bottom: 20px;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 0;
        }

        .item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 15px;
        }

        .item img {
            max-width: 100%;
            height: auto;
            border-bottom: 2px solid #f4f4f4;
        }
        .item h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .item p {
            font-size: 1.2em;
            color: #555;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section class="menu">
        <h2>Our Delicious Menu</h2>
        <div class="menu-items">
            <div class="item">
                <img src="DHALL RICE.jpg" alt="dhall rice">
                <h3>dhall rice</h3>
                <p>Rs.250</p>
            </div>

            <div class="item">
                <img src="FISH.jpeg" alt="fish">
                <h3>fish</h3>
                <p>Rs. 500</p>
            </div>

            <div class="item">
                <img src="M.jpg" alt="macroni">
                <h3>macroni</h3>
                <p>Rs. 350</p>
            </div>

            <div class="item">
                <img src="B.jpeg" alt="briyani">
                <h3>briyani </h3>
                <p>Rs. 400</p>
            </div>

            <div class="item">
                <img src="K.jpeg" alt="keema roll">
                <h3>keema roll</h3>
                <p>Rs. 300</p>
            </div>

            <div class="item">
                <img src="P.jpg" alt="parotta">
                <h3>parotta</h3>
                <p>Rs. 250</p>
            </div>
            <div class="item">
                <img src="S.jpeg" alt="samosa">
                <h3>samosa</h3>
                <p>Rs. 25</p>
            </div>

            <div class="item">
                <img src="F.jpeg" alt="fries">
                <h3>fries</h3>
                <p>Rs. 250</p>
            </div>

            <div class="item">
                <img src="N.webp" alt="noodles">
                <h3>noodles</h3>
                <p>Rs. 200</p>
            </div>

            <div class="item">
                <img src="D.jpeg" alt="dosa">
                <h3>dosa</h3>
                <p>Rs. 120</p>
            </div>

            <div class="item">
                <img src="PI.jpeg" alt="pizza.">
                <h3>=pizza</h3>
                <p>Rs. 560</p>
            </div>

            <div class="item">
                <img src="BR.jpeg" alt="brownie">
                <h3>brownie</h3>
                <p>Rs. 300</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 KEERTHANA</p>
    </footer>
</body>
</html>
style.css
/* General Reset */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-image: url('rest bg.jpg'); /* Replace with your image file path */
    background-size: cover; /* Ensures the image covers the entire screen */
    background-position: center; /* Centers the image */
    background-attachment: fixed; /* Makes the background fixed on scroll */
    background-repeat: no-repeat; /* Prevents repeating of the image */
}

/* Header Styling */
header.banner {
    background-color: #222;
    color: white;
    padding: 20px 10px;
    text-align: center;
}

header.banner h1 {
    margin: 0;
    font-size: 2.5em;
    letter-spacing: 2px;
}

header.banner nav ul {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}
header.banner nav ul li {
    display: inline;
}

header.banner nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.2em;
    transition: color 0.3s;
}

header.banner nav ul li a:hover {
    color: #ff6347;
}

/* Intro Section */
section.intro {
    padding: 40px 20px;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    margin: 20px;
    border-radius: 10px;
}

section.intro h2 {
    font-size: 2em;
    color: #222;
    margin-bottom: 10px;
}

section.intro p {
    font-size: 1.1em;
    color: #555;
    margin: 0;
}

/* Footer Styling */
footer {
    text-align: center;
    padding: 10px 0;
    background-color: #222;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}

/* Responsive Design */
@media (max-width: 768px) {
    header.banner nav ul {
        flex-direction: column;
        gap: 10px;
    }

    section.intro {
        margin: 10px;
    }
}

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }
        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .contact {
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .contact p {
            font-size: 1.2em;
            margin: 10px 0;
            color: #555;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner">
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="adminstration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Get in Touch</h2>
        <p><strong>Address:</strong>2nd Ave, A E Block, Anna Nagar West, Anna Nagar, Chennai, Tamil Nadu 600040</p>
        <p><strong>Phone:</strong>8925411734</p>
        <p><strong>Email:</strong> Roast & Toast@restaurant.com</p>
    </section>

    <footer>
        <p>&copy; 2025 KEERTHANA T</p>
    </footer>
</body>
</html>

Adminsitration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        .banner {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .banner h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav ul li {
            margin: 0;
        }

        nav ul li a {
            display: block;
            padding: 10px 20px;
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            background-color: #4CAF50;
        }

        .team {
            padding: 40px 20px;
            text-align: center;
        }

        .team h2 {
            margin-bottom: 20px;
            font-size: 2em;
            color: #4CAF50;
        }

        .team-members {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .member {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 200px;
            padding: 20px;
            text-align: center;
        }

        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .member h3, .member h4, .member h5, .member h6 {
            margin: 10px 0 5px;
            font-size: 1.2em;
            color: #333;
        }

        .member p {
            margin: 0;
            font-size: 0.9em;
            color: #666;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header class="banner"> 
        <h1>Our Team</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administrative 3.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="team">        <h2>Meet Our Team</h2>
        <div class="team-members">
            <div class="member">
                <img src="tae.jpg" alt="Kim Taehyung">
                <h3>Kim Taehyung</h3>
                <p>owner</p>
            </div>
            <div class="member">
                <img src="jk.webp" alt="Jeon Jungkook ">
                <h3>Jeon Jungkook</h3>
                <p>management team</p>
            </div>
            <div class="member">
                <img src="JIM.avif" alt="Park Jimin">
                <h3>Park Jimin</h3>
                <p>barista</p>
            </div>
            <div class="member">
                <img src="jkjk.jpg" alt="Jung Ho-seok">
                <h3>Jung Ho-seok</h3>
                <p>accountant</p>
            </div>
            <div class="member">
                <img src="BRAT.jpg" alt="Kim Seok Jin">
                <h3>Kim Seok Jin</h3>
                <p>chef1</p>
            </div>
            <div class="member">
                <img src="r1.jpg" alt="Kim Namjoon">
                <h3>Kim Namjoon</h3>
                <p>manager</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 KEERTAHNA T</p>
    </footer>
</body>
</html>
```


## OUTPUT:
![Screenshot 2025-04-28 224727](https://github.com/user-attachments/assets/ec827399-b5ff-4a16-9616-68f730051ae5)

![Screenshot 2025-04-28 224936](https://github.com/user-attachments/assets/3632cf7f-cd13-42e6-a311-36cc88dea744)

![Screenshot 2025-04-28 225016](https://github.com/user-attachments/assets/fec3ebc9-6339-4242-b06e-bd9c0d421518)

![Screenshot 2025-04-28 225121](https://github.com/user-attachments/assets/cdb5846b-f62b-4ad5-b3df-b439ae989449)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
