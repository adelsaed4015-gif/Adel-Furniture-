# Adel-Furniture-
صفحه اثاث
<! src="https://images.unsplash.com/photo-1616628182504-ff5f9c9b2c6c">
        <div class="d
</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Adel Furniture</title>

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;600;900&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Cairo',sans-serif;
scroll-behavior:smooth;
}

body{
background:#1c1c1c;
color:#eee;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#111;
position:sticky;
top:0;
z-index:1000;
}

.logo{
font-weight:900;
font-size:22px;
color:#c6a75e;
}

nav a{
color:#ccc;
text-decoration:none;
margin:0 15px;
font-weight:600;
}

nav a:hover{
color:#c6a75e;
}

.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1618220179428-22790b461013?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
}

.hero::after{
content:"";
position:absolute;
inset:0;
background:rgba(0,0,0,0.6);
}

.hero-content{
position:relative;
z-index:2;
}

.hero h1{
font-size:55px;
color:#c6a75e;
}

.hero p{
margin-top:20px;
font-size:20px;
color:#ddd;
}

.section{
padding:100px 8%;
}

.section h2{
font-size:35px;
margin-bottom:60px;
color:#c6a75e;
text-align:center;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:40px;
}

.card{
background:#232323;
padding:20px;
border-radius:12px;
transition:0.4s;
overflow:hidden;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 15px 40px rgba(198,167,94,0.2);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
border-radius:8px;
}

.card h3{
margin:20px 0 10px;
}

.price{
color:#c6a75e;
font-weight:600;
margin-bottom:15px;
}

.btn{
display:inline-block;
padding:10px 20px;
background:#c6a75e;
color:#111;
text-decoration:none;
border-radius:6px;
font-weight:600;
}

.btn:hover{
background:#b8964e;
}

.whatsapp{
position:fixed;
bottom:20px;
left:20px;
background:#25d366;
color:white;
padding:15px 18px;
border-radius:50%;
font-size:20px;
text-decoration:none;
box-shadow:0 5px 20px rgba(0,0,0,0.3);
}

footer{
background:#111;
text-align:center;
padding:40px;
margin-top:80px;
color:#888;
}
</style>
</head>

<body>

<nav>
<div class="logo">Adel Furniture</div>
<div>
<a href="#">الرئيسية</a>
<a href="#products">المنتجات</a>
<a href="#">تواصل</a>
</div>
</nav>

<section class="hero">
<div class="hero-content">
<h1>فخامة بمعايير عاليه</h1>
<p>تصميمات راقية وجودة لا تقارن</p>
</div>
</section>

<section class="section" id="products">
<h2>منتجاتنا</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1615873968403-89e068629265?auto=format&fit=crop&w=800&q=80">
<h3>كنبة مودرن فاخرة</h3>
<div class="price">12,500 جنيه</div>
<a class="btn" href="https://wa.me/201278497449?text=عايز اطلب كنبة مودرن فاخرة">اطلب الآن</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80">
<h3>غرفة نوم ملكي</h3>
<div class="price">38,000 جنيه</div>
<a class="btn" href="https://wa.me/201278497449?text=عايز اطلب غرفة نوم ملكي">اطلب الآن</a>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1598300056393-4aac492f4344?auto=format&fit=crop&w=800&q=80">
<h3>مكتب خشب طبيعي</h3>
<div class="price">9,800 جنيه</div>
<a class="btn" href="https://wa.me/201278497449?text=عايز اطلب مكتب خشب طبيعي">اطلب الآن</a>
</div>

</div>
</section>

<a class="whatsapp" href="https://wa.me/201278497449" target="_blank">💬</a>

<footer>
© 2026 Adel Furniture — All Rights Reserved
</footer>

</body>
</html>

<
