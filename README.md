<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Hotel Website</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#f5f5f5;
}

header{
background:#111;
color:white;
padding:15px;
text-align:center;
}

header h1{
font-size:32px;
}

nav{
margin-top:10px;
}

nav a{
color:white;
text-decoration:none;
margin:10px;
font-size:18px;
}

.hero{
height:300px;
background:url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?q=80&w=1200') center/cover;
display:flex;
align-items:center;
justify-content:center;
color:white;
text-align:center;
}

.hero h2{
font-size:40px;
background:rgba(0,0,0,0.5);
padding:10px 20px;
border-radius:10px;
}

.section{
padding:40px 20px;
text-align:center;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
margin-top:20px;
}

.card{
background:white;
width:280px;
border-radius:15px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card h3{
padding:10px;
}

.card p{
padding:0 10px 15px;
}

.btn{
display:inline-block;
margin-top:10px;
padding:10px 20px;
background:green;
color:white;
text-decoration:none;
border-radius:8px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 18px;
border-radius:50%;
font-size:24px;
text-decoration:none;
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}
</style>
</head>

<body>

<header>
<h1>Rajshekhar Hotel</h1>

<nav>
<a href="#">Home</a>
<a href="#">Menu</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<h2>Welcome To Our Hotel</h2>
</section>

<section class="section">
<h2>Our Special Foods</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?q=80&w=1000">
<h3>Veg Meals</h3>
<p>Tasty South Indian Meals</p>
<a class="btn" href="https://wa.me/919999999999">Order Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1604908176997-4319d6b52b4d?q=80&w=1000">
<h3>Biryani</h3>
<p>Hot Chicken Biryani</p>
<a class="btn" href="https://wa.me/919999999999">Order Now</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?q=80&w=1000">
<h3>Pizza</h3>
<p>Cheesy Pizza Available</p>
<a class="btn" href="https://wa.me/919999999999">Order Now</a>
</div>

</div>
</section>

<section class="section">
<h2>Contact Us</h2>
<p>📍 Bangalore, Karnataka</p>
<p>📞 +91 9999999999</p>
</section>

<a class="whatsapp" href="https://wa.me/919999999999">💬</a>

<footer>
<p>© 2026 Rajshekhar Hotel. All Rights Reserved.</p>
</footer>

</body>
</html>
