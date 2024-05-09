# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
          }
        .image-container {
            display: flex;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .contact-info {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }
        .contact-item {
            margin: 20px;
            text-align: left;
        }
        .contact-item img {
            width: 40px;
            height: 40px;
            margin-right: 10px;
        }
        .contact-item p {
            margin: 0;
        }
        .contact-item p span {
            color: #007bff;
        }
        .contact-item p a {
            color: #007bff;
            text-decoration: none;
            display: block;
        }
        .contact-item p a:hover {
            text-decoration: underline;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
          }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Connect with us through...</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>Links</h2>
        <div class="contact-info">
            <div class="contact-item">
                <img src="phone.png" alt="Phone Logo">
                <p>Phone Number: <span>+91 8610730085</span></p>
            </div>
            <div class="contact-item">
                <img src="address.png" alt="Address Logo">
                <p>Address: <span>44, srinivasa nagar, thirumullaivoyal, Chennai-62</span></p>
            </div>
            <div class="contact-item">
                <img src="linkedin.png" alt="LinkedIn Logo">
                <p>LinkedIn:</p>
                <ul>
                    <li><a href="https://www.linkedin.com/in/tarunika-damod-b83ab72b2/" target="_blank">Tarunika.D</a></li>
                </ul>
            </div>
            <div class="contact-item">
                <img src="gmail.png" alt="Gmail Logo">
                <p>Gmail: <a href="mailto:tarunikadamod.com">tarunikadamod@gmail.com</a></p>
            </div>
        </div>
    </div>
    <footer>
        <p1>&#Tarunika.D [212223040227]~SEC</p1>
    </footer>
</body>
</html>
```
```
<html>
<head>
    <title>SDev Company - Council</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #007bff;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Council Members</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Members</h2>

        <div class="product">
            <img src="p.jpg" alt="Python Programming" width="200" height="200">
            <h3>person 1</h3>
        </div>
        
        <div class="product">
            <img src="p2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 2</h3>
        </div>
        
        <div class="product">
            <img src="p3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 3</h3>
        </div>
        
        <div class="product">
            <img src="p4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 4</h3>
        </div>
        
        <div class="product">
            <img src="p5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>person 5</h3>
        </div>
        
        <div class="product">
            <img src="p6.avif" alt="Python Programming" width="200" height="200">
            <h3>person 6</h3>
        </div>
           

    </div>
    <footer>
        <p1>&#Tarunika.D [212223040227]~SEC</p1>
    </footer>
</body>
</html>
```
```
<!DOCTYPE html>
<html>
<head>
    <title>SDev Company - Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
        }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
        }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        .product {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        .product img{
           max-width: 100%;
           height: auto;
           border-radius: 50%;
        }
        .product h3 {
            color: #fff;
        }
        .product p {
            color: #007bff;
            font-size: 18px;
        }
        p1 {
            color: #fff;
            margin-bottom: 20px; 
            font-size: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company - Products</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
    
        <h2>Our Products</h2>

        <div class="product">
            <img src="prod1.jpeg" alt="Python Programming" width="200" height="200">
            <h3>1. Accounting Software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod2.jpeg" alt="Python Programming" width="200" height="200">
            <h3>2. Tax Software</h3>
            <p>Price: $4999</p>
        </div>
        
        <div class="product">
            <img src="prod3.jpeg" alt="Python Programming" width="200" height="200">
            <h3>3. Bookkeeping Software</h3>
            <p>Price: $5999</p>
        </div>
        
        <div class="product">
            <img src="prod4.jpeg" alt="Python Programming" width="200" height="200">
            <h3>4. Time Tracking Software</h3>
            <p>Price: $3499</p>
        </div>
        
        <div class="product">
            <img src="prod5.jpeg" alt="Python Programming" width="200" height="200">
            <h3>5. Project Management Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod6.jpeg" alt="Python Programming" width="200" height="200">
            <h3>6. Customer Relationship Management Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod7.jpeg" alt="Python Programming" width="200" height="200">
            <h3>7. Communication Software</h3>
            <p>Price: $4499</p>
        </div>
        
        <div class="product">
            <img src="prod8.jpeg" alt="Python Programming" width="200" height="200">
            <h3>8. Website Building Software</h3>
            <p>Price: $6999</p>
        </div>
        
        <div class="product">
            <img src="prod9.jpeg" alt="Python Programming" width="200" height="200">
            <h3>9. Payment Transaction Software</h3>
            <p>Price: $7999</p>
        </div>
        
        <div class="product">
            <img src="prod10.jpeg" alt="Python Programming" width="200" height="200">
            <h3>10. Sales, Marketing, and PR Software</h3>
            <p>Price: $8999</p>
        </div>
        
        <div class="product">
            <img src="prod11.jpeg" alt="Python Programming" width="200" height="200">
            <h3>11. Medical software</h3>
            <p>Price: $9999</p>
        </div>
        
        <div class="product">
            <img src="prod12.png" alt="Python Programming" width="200" height="200">
            <h3>12. ERP Software</h3>
            <p>Price: $10999</p>
        </div>
        

    </div>
    <footer>
        <p1>&#Tarunika.D [212223040227]~SEC</p1>
    </footer>
</body>
</html>
```
```
<html>
<head>
<title>SDev Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #fff;
        }
        header {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
            text-align: center;
        }
        nav a {
            margin: 0 40px;
            text-decoration: none;
            color: #fff;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007bff;
        }
        footer {
            background-image: url('background.jpg');
            background-size: cover;
            background-position: center;
            background-color: #333;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .content {
            padding: 20px;
            text-align: center;
        }
        h2 {
            color: #fff;
            text-decoration: underline;
            transition: color 0.3s;
        }
        h2:hover {
            color: #007bff;
        }
        p {
            color: #ffffff;
            margin-bottom: 20px; 
            font-size: 20px;
          }
        .image-container {
            display: fill;
            justify-content: space-around;
            margin-bottom: 20px; 
                         }
        .image-container img {
            max-width: 80%; 
            border-radius: 8px; 
        }
        p1 {
            color: #fff  ;
            margin-bottom: 20px; 
            font-size: 15px;
          }
    </style>
</head>
<body>
    <header>
        <h1>SDev Company</h1>
    </header>
    <nav>
        <a href="soft.html">Home</a>
        <a href="products.html">Products</a>
        <a href="council.html">Council</a>
        <a href="contact_us.html">Contact Us</a>
    </nav>
    <div class="content">
        <h2>About Our Company</h2>
        <p>
            Our SDev company specializes in creating tailored software solutions for diverse clients,<br>
            spanning industries like healthcare, finance, and e-commerce. Utilizing a range of technologies<br>
            and methodologies such as Agile and Scrum, these companies employ multidisciplinary teams of<br>
            software engineers, designers, and project managers to deliver high-quality products. Offering<br>
            services including <strong>custom software development, web and mobile app development, and quality assurance,</strong><br>
            they prioritize customer satisfaction through close collaboration, iterative development cycles, and<br>
            rigorous testing processes. Continuously adapting to emerging technologies and industry trends, software<br>
            development companies strive for innovation, efficiency, and excellence in delivering robust and reliable<br>
            software solutions to meet the evolving needs of their clients.
        </p>
        <div class="image-container">
            <img src="image.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
        </div>
    </div>
    <footer>
        <p1>&#Tarunika.d [212223040227]~SEC</p1>
    </footer>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-05-09 162506.png>)

![alt text](<Screenshot 2024-05-09 162520.png>)
![alt text](<Screenshot 2024-05-09 162534.png>)
![alt text](<Screenshot 2024-05-09 162544.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
