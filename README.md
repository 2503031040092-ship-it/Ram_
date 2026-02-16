<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Food Transfer Service</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    background: linear-gradient(135deg, #ff7a18, #ffb347);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

.hero{
    width:90%;
    max-width:1100px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background: rgba(255,255,255,0.15);
    backdrop-filter: blur(15px);
    border-radius:20px;
    padding:50px;
    box-shadow:0 20px 40px rgba(0,0,0,0.2);
}

.hero-text{
    width:50%;
    color:white;
}

.hero-text h1{
    font-size:48px;
    font-weight:700;
    margin-bottom:20px;
}

.hero-text p{
    font-size:18px;
    font-weight:300;
    margin-bottom:30px;
    line-height:1.6;
}

.btn{
    display:inline-block;
    padding:14px 30px;
    background:white;
    color:#ff7a18;
    font-weight:600;
    text-decoration:none;
    border-radius:50px;
    transition:0.3s ease;
}

.btn:hover{
    background:#111;
    color:white;
    transform:translateY(-3px);
}

.hero-image{
    width:40%;
}

.hero-image img{
    width:100%;
    border-radius:20px;
}

@media(max-width:900px){
    .hero{
        flex-direction:column;
        text-align:center;
    }
    .hero-text, .hero-image{
        width:100%;
    }
    .hero-text h1{
        font-size:36px;
    }
}
</style>
</head>

<body>

<div class="hero">
    <div class="hero-text">
        <h1>Fast & Fresh Food Transfer</h1>
        <p>Professional and reliable food delivery service. We bring your favorite meals quickly and safely to your doorstep.</p>
        <a href="https://wa.me/98754566" class="btn">Order Now</a>
    </div>

    <div class="hero-image">
        <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092" alt="Food Delivery">
    </div>
</div>

</body>
</html>
