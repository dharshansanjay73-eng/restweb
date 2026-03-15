# Ex.06 Restaurant Website
## Date:16/3/2026

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
Publish the website in Localhost.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<title>Spice Garden Restaurant</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Spice Garden Restaurant</h1>
<p>Delicious Food | Fresh Ingredients | Great Taste</p>
</header>

<nav>
<a href="index.html">Home</a>
<a href="menu.html">Menu</a>
<a href="admin.html">Administration</a>
<a href="contact.html">Contact Us</a>
</nav>

<img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5" class="banner">

<div class="container">
<h2>Welcome to Spice Garden</h2>

<p>
Spice Garden Restaurant offers a wide variety of delicious Indian and
international dishes prepared with fresh ingredients and authentic
spices. Our chefs ensure every meal is served with the best taste
and quality.
</p>

</div>

<footer>
<p>Designed by Dharshan Sanjay</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Menu - Spice Garden</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Spice Garden Restaurant</h1>
<p>Our Delicious Non-Veg Menu</p>
</header>

<nav>
<a href="index.html">Home</a>
<a href="menu.html">Menu</a>
<a href="admin.html">Administration</a>
<a href="contact.html">Contact Us</a>
</nav>

<h2 class="menu-title">Restaurant Menu</h2>

<div class="menu-container">

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d">
<h3>Chicken Biryani</h3>
<p>Classic aromatic basmati rice cooked with spicy chicken.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7">
<h3>Mutton Biryani</h3>
<p>Traditional slow cooked mutton biryani.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1601050690597-df0568f70950">
<h3>Butter Chicken</h3>
<p>Creamy tomato based chicken curry.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1627308595171-d1b5d67129c4">
<h3>Tandoori Chicken</h3>
<p>Char grilled spicy marinated chicken.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1598514983318-2f64f8f4796c">
<h3>Chicken 65</h3>
<p>South Indian crispy spicy fried chicken.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1603894584373-5ac82b2ae398">
<h3>Mutton Rogan Josh</h3>
<p>Rich Kashmiri style mutton curry.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1625943553852-781c6dd46faa">
<h3>Grilled Fish</h3>
<p>Fresh fish grilled with herbs and spices.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1562967914-608f82629710">
<h3>Prawn Masala</h3>
<p>Juicy prawns cooked in spicy masala gravy.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1600891964092-4316c288032e">
<h3>Chicken Shawarma</h3>
<p>Middle Eastern style roasted chicken wrap.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1544025162-d76694265947">
<h3>Chicken Steak</h3>
<p>Juicy grilled chicken served with sauce.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1598515214211-89d3c73ae83b">
<h3>Lamb Chops</h3>
<p>Tender lamb chops grilled to perfection.</p>
</div>

<div class="menu-item">
<img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1">
<h3>BBQ Chicken Wings</h3>
<p>Smoky barbecue glazed chicken wings.</p>
</div>

</div>

<footer>
<p>Designed by Dharshan Sanjay</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Administration</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Spice Garden Restaurant</h1>
<p>Meet Our Culinary Team</p>
</header>

<nav>
<a href="index.html">Home</a>
<a href="menu.html">Menu</a>
<a href="admin.html">Administration</a>
<a href="contact.html">Contact Us</a>
</nav>

<h2 style="text-align:center;">Our Chef Team</h2>

<div class="admin-container">

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922510.png">
<h3>Chef Arjun</h3>
<p>Head Chef</p>
</div>

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922561.png">
<h3>Chef Rahul</h3>
<p>Grill Specialist</p>
</div>

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922516.png">
<h3>Chef Kiran</h3>
<p>Seafood Chef</p>
</div>

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922522.png">
<h3>Chef Meena</h3>
<p>Pastry Chef</p>
</div>

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922550.png">
<h3>Chef Sanjay</h3>
<p>Kitchen Manager</p>
</div>

<div class="admin-card">
<img src="https://cdn-icons-png.flaticon.com/512/2922/2922543.png">
<h3>Chef Priya</h3>
<p>Food Stylist</p>
</div>

</div>

<footer>
<p>Designed by Dharshan Sanjay</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Visit and Contact Us:</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Contact Us</h1>
</header>

<nav>
<a href="index.html">Home</a>
<a href="menu.html">Menu</a>
<a href="admin.html">Administration</a>
<a href="contact.html">Contact Us</a>
</nav>

<div class="container">

<h2>Visit us at:</h2>

<p><b>Address:</b>  
Spice Garden Restaurant 
@
9/4a ,1sr cross street,balaiya garden,madipakkam, Chennai</p>

<p><b>Phone:</b> 7010542638</p>

<p><b>Email:</b> spicegarden@gmail.com</p>
<P>
    copyright @ spice garden restaurent

</P>

</div>

<footer>
<p>Designed by Dharshan Sanjay</p>
</footer>

</body>
</html>
body{
margin:0;
font-family:Arial, sans-serif;
background-image:linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
url("https://images.unsplash.com/photo-1552566626-52f8b828add9");
background-size:cover;
background-position:center;
background-attachment:fixed;
color:white;
}

header{
background-color:#8B0000;
color:white;
text-align:center;
padding:20px;
}

nav{
background-color:#333;
text-align:center;
padding:10px;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-size:18px;
}

nav a:hover{
color:#FFD700;
}

.banner{
width:100%;
height:400px;
object-fit:cover;
}

.container{
padding:30px;
text-align:center;
}

.menu-title{
text-align:center;
margin-top:20px;
}

.menu-container{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
padding:30px;
}

.menu-item{
background:#e6d8c3;
padding:15px;
border-radius:10px;
text-align:center;
}

.menu-item img{
width:100%;
height:150px;
object-fit:cover;
border-radius:8px;
margin-bottom:10px;
}

.menu-item h3{
margin:5px 0;
}

.menu-item p{
font-weight:bold;
color:#8B0000;
}

```


## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
