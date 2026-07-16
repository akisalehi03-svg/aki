<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>وب‌سایت مدرن</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Tahoma,sans-serif;
}

body{
    background:#eef2f7;
}

header{
    background:linear-gradient(135deg,#4facfe,#00f2fe);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:48px;
}

header p{
    margin-top:15px;
    font-size:20px;
}

button{
    margin-top:25px;
    padding:12px 25px;
    border:none;
    border-radius:30px;
    background:white;
    color:#0077ff;
    font-size:18px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

.container{
    width:90%;
    max-width:1100px;
    margin:40px auto;
}

.cards{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
    justify-content:center;
}

.card{
    background:white;
    width:300px;
    padding:20px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#0077ff;
    margin-bottom:10px;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
<h1>به وب‌سایت من خوش آمدید</h1>
<p>یک نمونه طراحی مدرن با HTML و CSS</p>
<button onclick="alert('سلام! از بازدید شما متشکریم 🌹')">
شروع کنید
</button>
</header>

<div class="container">
<div class="cards">

<div class="card">
<h3>طراحی وب</h3>
<p>ساخت وب‌سایت‌های مدرن، سریع و واکنش‌گرا.</p>
</div>

<div class="card">
<h3>برنامه‌نویسی</h3>
<p>توسعه پروژه‌های HTML، CSS و JavaScript.</p>
</div>

<div class="card">
<h3>پشتیبانی</h3>
<p>ارائه خدمات پشتیبانی و به‌روزرسانی وب‌سایت.</p>
</div>

</div>
</div>

<footer>
<p>© 2026 | طراحی شده با ❤️ و HTML + CSS</p>
</footer>

</body>
</html>
