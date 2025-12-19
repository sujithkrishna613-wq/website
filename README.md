# Ex.06 Restaurant Website
# Date: 17-12-2025
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
```
menu.html 

<html>
<head>
    <title>CHOCO PLAZA</title>

    <style>
        body {
            background-color: rgb(239, 211, 119);
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

       
        h1 {
            text-align: center;
            background-color: rgba(127, 226, 138, 0.956);
            color: rgb(25, 0, 255);
            margin: 0;
            padding: 30px;
            border-radius: 0 0 15px 15px;
            font-size: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }

        h1 img {
            width: 60px;
            height: 60px;
           
        }

        p {
            text-align: center;
            font-size: 18px;
            background-color: rgb(255, 0, 51);
            color: rgb(118, 184, 217);
            padding: 10px;
            border-radius: 10px;
            width: 80%;
            margin: 20px auto;
        }

       
        nav {
            background-color: rgb(255, 0, 38);
            padding: 15px;
            display: flex;
            justify-content: center;
            gap: 40px;
        }

        nav a {
            text-decoration: none;
            color: rgb(238, 152, 236);
            font-size: 18px;
            padding: 8px 12px;
            border-radius: 5px;
        }

        nav a:hover {
            background-color: rgb(218, 50, 50);
        }

        
        .cta {
            display: block;
            text-align: center;
            background-color: rgb(233, 194, 138);
            width: 150px;
            margin: 15px auto;
            padding: 10px;
            color: black;
            text-decoration: none;
            border-radius: 10px;
            font-weight: bold;
        }

        .menu-items {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
            padding: 20px;
            
        }

        .item {
            text-align: center;
            width: 200px;
        }

        .item img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }

        .item h3 {
            margin: 10px 0 5px;
        }

        .item span {
            font-size: 18px;
            font-weight: bold;
        }
        footer{
            background-color: rgb(255, 0, 38);
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;   
        }
    </style>
</head>

<body>

    <h1>
        CHOCO PLAZA
    </h1>

    

    <nav>
        <a href="menu.html">Menu</a>
        <a href="adm.html">Administration</a>
        <a href="contact.html">Contact</a>

    </nav>

    <p>"No distractions, just pure chocolate art,
Choco Plaza—the home of a chocoholic heart."</p>

    <a class="cta" href="#menu-section">Our chocolaty Menu</a>

    
    <div class="menu-items" id="menu-section">

        <div class="item">
            <img src="/static/monster.jpg">
            <h3>CHOCOLATE MONSTER SHAKE</h3>
            <span>₹249</span>
            <p>The Shake that Shakes Up Everything: More than a drink, it Is a chocolate experience.</p>
        </div>

        

        <div class="item">
            <img src="/static/lava.jpg">
            <h3>CHOCO LAVA CAKE</h3>
            <span>₹99</span>
            <p>"I Lava You!": The classic, adorable pun for the ultimate chocolate gift.</p>
        </div>

        <div class="item">
            <img src="/static/cake.jpg">
            <h3>CHOCOLATE CAKE</h3>
            <span>₹399</span>
            <p>"Life is what you bake of it, especially if it's chocolate."</p>
        </div>

        <div class="item">
            <img src="/static/moose.jpg">
            <h3>HONEY CARAMEL WAFFLE</h3>
            <span>₹299</span>
            <p>“Crispy waffles drizzled in sweet, sticky luxury.”</p>
        </div>

        <div class="item">
            <img src="/static/hotchocolate.jpg">
            <h3>HOT CHOCOLATE</h3>
            <span>₹199</span>
            <p>"Winter Liquid Hug": Perfect for emphasizing the comfort of a warm mug.</p>
        </div>

        <div class="item">
            <img src="/static/brownie.jpg">
            <h3>CHOCO BROWNIE</h3>
            <span>₹289</span>
            <p>"A brownie a day keeps the frownies away!"</p>
        </div>

        

        <div class="item">
            <img src="/static/cookies.jpg">
            <h3>COOKIES</h3>
            <span>₹99</span>
            <p>"Warm, Fresh, and Ready to Share."</p>
        </div>
        <div class="item">
            <img src="/static/balls.jpg">
            <h3>CHOCO BALLS</h3>
            <span>₹199</span>
            <p>"Roll Into Bliss": A simple, rhythmic tagline for pure chocolate indulgence.</p>
        </div>

        <div class="item">
            <img src="/static/ice.jpg">
            <h3>CHOCOLATE ICE CREAM </h3>
            <span>₹99</span>
            <p>"Double the Cocoa, Double the Bliss": Perfect for rich, dark chocolate varieties.</p>
        </div>
        <div class="item">
            <img src="/static/swissroll.jpg">
            <h3>CHOCO SWIZZ ROLL</h3>
            <span>₹399</span>
            <p>"Unroll the Magic, Taste the Chocolate": Encourages the interactive experience of serving.</p>  
        </div>

        <div class="item">
            <img src="/static/waffels.jpg">
            <h3>WAFFELS</h3>
            <span>₹199</span>
            <p>"Life is Better with Chocolate Squares": Highlighting the waffle's signature grid.</p>
        </div>

    </div>
    <footer>
      <div class="meta container">
        <div>© 2025 CHOCO PLAZA</div>
      <div>Designed by <strong>SUJITH KRISHNA</strong></div>
      </div>
    </footer>

</body>
</html>

contact.html

<html>
<head>
    <title>Contact – CHOCO PLAZA</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #ffb700;
        }

        h1 {
            text-align: center;
            background-color: #825650;
            padding: 20px;
            color: #4b1f10;
            margin: 0;
            border-radius: 0 0 15px 15px;
        }

        .contact-container {
            width: 80%;
            margin: 40px auto;
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            justify-content: center;
        }

        .contact-box, .form-box {
            background: #cfe089;
            padding: 25px;
            border-radius: 15px;
            width: 350px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }

        .contact-box h2, .form-box h2 {
            text-align: center;
            color: #002aff;
        }

        .contact-item {
            margin: 15px 0;
            font-size: 18px;
        }

        iframe {
            width: 100%;
            height: 250px;
            border-radius: 10px;
            border: none;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 8px;
            border-radius: 10px;
            border: 1px solid #e1a38f;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #d3a29c;
            border: none;
            border-radius: 10px;
            font-size: 18px;
            color: #fff;
            cursor: pointer;
        }

        button:hover {
            background-color: #b57d74;
        }
    </style>
</head>

<body>

    <h1>CONTACT US</h1>

    <div class="contact-container">

        
        <div class="contact-box">
            <h2>Reach us </h2>

            <div class="contact-item"><strong> Address:</strong><br>
            CHOCO PLAZA,<br>
            PERAMBUR,CHENNAI 600082</div>

            <div class="contact-item"><strong> Phone:</strong><br>
            +91 9482728394</div>

            <div class="contact-item"><strong> Email:</strong><br>
            chocoplaza007@gmail.com</div>
        </div>

        


    </div>

</body>
</html>

adm.html

<html>
<head>
    <title>ADMINISTRATION</title>
    <style>
        body{
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #ffba0a;
        }
        .adm h1{
            text-align: center;
            background-color: #770f01;
            padding: 20px;
            color: #218a2c;
            margin: 0;
            border-radius: 0 0 15px 15px;
        }
        .adm p{
            text-align: center;
            font-size: 18px;
            background-color: rgb(246, 8, 55);
            color: white;
            padding: 10px;
            border-radius: 10px;
            width: 80%;
            margin: 20px auto;
        }

        .adm {
            display: flex;
            flex-wrap: wrap;              
            justify-content: space-around; 
            gap: 20px;                     
            width: 90%;
            margin: 20px auto;
        }

        
        #container{
            width: 80%;
            max-width: 600px;
            margin: 20px auto;
            background: #a54d4d;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            display: flex;
            justify-content: space-between;
            flex-direction: row;
            align-items: center;
        }
        #name{
            font-size: 20px;
            font-weight: bold;
            color: #f85013;
        }
        #position{
            font-size: 18px;
            color: #130453;
        }
        img{
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
        }   


    </style>
</head>
<body>
    <div class="adm">
        <h1>Administration</h1>
        <p>HERE COMES OUR ADMINISTERS

        </p>

        <div id="container">
            <div id="name"> MIKE </div>
            <div id="position">Executive Chef</div>
            <img src="/static/mike.jpg" alt="MIKE">
        </div>
        <div id="container">
            <div id="name"> IVAN</div>
            <div id="position">Manager</div>
            <img src="/static/ivan.jpg" alt="IVAN">
        </div>
        <div id="container">
            <div id="name"> ROSE </div>
            <div id="position">BAKING</div>
            <img src="/static/rose.jpg" alt="ROSE">
        </div>
    </div>
    <div class="adm">
        <div id="container">
            <div id="name"> KRITI </div>
            <div id="position">CO BAKER</div>
            <img src="/static/kirti.jpg" alt="KRITI">
        </div>
    </div>
</body>
</html>

views.py

from django.shortcuts import render

def menu(request):
    return render(request, 'menu.html')

def contact(request):
    return render(request, 'contact.html')

def admin(request):
    return render(request, 'adm.html')

urls.py

from django.urls import path
from app import views

urlpatterns = [
    path('', views.menu, name='menu'),
    path('contact.html/', views.contact, name='contact'),
    path('adm.html/', views.admin, name='adm'),
]
```
# OUTPUT:
![alt text](<Screenshot 2025-12-18 223543.png>)
![alt text](<Screenshot 2025-12-18 223558.png>)
![alt text](<Screenshot 2025-12-18 223614.png>)
![alt text](<Screenshot 2025-12-18 223628.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
