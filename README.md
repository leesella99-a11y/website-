<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ĂN NGON MỖI NGÀY</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#f4efe7;
    color:#3a2d23;
}

/* ===== NAV ===== */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 80px;
    background:#f1e8dc;
}

.logo{
    font-family:'Playfair Display',serif;
    font-size:28px;
    font-weight:700;
}

nav ul{
    display:flex;
    gap:30px;
    list-style:none;
}

nav a{
    text-decoration:none;
    color:#3a2d23;
    font-weight:500;
    transition:0.3s;
}

nav a:hover{
    color:#b07d4f;
}

.order-btn{
    background:#b07d4f;
    color:white;
    padding:8px 20px;
    border-radius:20px;
}

/* ===== HERO ===== */
.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px;
    background:#efe6d8;
}

.hero-text h1{
    font-family:'Playfair Display',serif;
    font-size:48px;
    margin-bottom:20px;
}

.hero-text button{
    background:#8b5e3c;
    color:white;
    border:none;
    padding:12px 30px;
    border-radius:25px;
    cursor:pointer;
    transition:0.3s;
}

.hero-text button:hover{
    transform:scale(1.1);
}

.hero img{
    width:450px;
    border-radius:20px;
}

/* ===== WHY CHOOSE US ===== */
.why{
    text-align:center;
    padding:80px;
}

.why h2{
    font-family:'Playfair Display',serif;
    font-size:35px;
    margin-bottom:50px;
}

.cards{
    display:flex;
    justify-content:center;
    gap:40px;
    flex-wrap:wrap;
}

.card{
    background:white;
    width:260px;
    padding-bottom:20px;
    border-radius:15px;
    box-shadow:0 10px 20px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
    border-radius:15px 15px 0 0;
}

.card h3{
    margin:15px 0;
}

.card button{
    background:#b07d4f;
    color:white;
    border:none;
    padding:6px 15px;
    border-radius:20px;
    cursor:pointer;
}

/* ===== VISIT SECTION ===== */
.visit{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px;
    background:#efe6d8;
}

.visit-text{
    max-width:400px;
}

.visit-text h2{
    font-family:'Playfair Display',serif;
    font-size:32px;
    margin-bottom:20px;
}

.visit-text button{
    background:#8b5e3c;
    color:white;
    border:none;
    padding:10px 25px;
    border-radius:20px;
    margin-top:15px;
    cursor:pointer;
}

.visit img{
    width:400px;
    border-radius:20px;
}

/* ===== GALLERY ===== */
.gallery{
    display:flex;
    gap:20px;
    padding:80px;
    justify-content:center;
    flex-wrap:wrap;
}

.gallery img{
    width:300px;
    border-radius:15px;
    transition:0.3s;
}

.gallery img:hover{
    transform:scale(1.05);
}

/* ===== FOOTER ===== */
footer{
    text-align:center;
    padding:20px;
    background:#f1e8dc;
}

</style>
</head>
<body>

<nav>
    <div class="logo">QUÁN ĂN DÂN DÃ</div>
    <ul>
        <li><a href="#">TRANG CHỦ</a></li>
        <li><a href="#why">MENU</a></li>
        <li><a href="#visit">ABOUT</a></li>
        <li><a href="#">BLOG</a></li>
    </ul>
    <a href="#" class="order-btn">ĐẶT HÀNG NGAY</a>
</nav>

<section class="hero">
    <div class="hero-text">
        <h1>Đậm đà<br>Hương vị Việt</h1>
        <button>ĂN NGON MỖI NGÀY</button>
    </div>
    <img src="https://exotrails.com/wp-content/uploads/2024/11/vietnamese-food-thumb-1024x682-01-08-2024.jpg">
</section>

<section id="why" class="why">
    <h2>Những món nên thử</h2>
    <div class="cards">
        <div class="card">
            <img src="https://media.phunumoi.net.vn/files/hvtoan/2025/05/05/bun-bo-hue-6-0935-090800.jpeg">
            <h3>Bún bò</h3>
             <a href='https://nhile6108-stack.github.io/bunbohue/'><button>Tìm hiểu thêm</button></a>
        </div>
        <div class="card">
            <img src="https://phole.vn/upload/filemanager/files/Ph%E1%BB%9F%20Ngon%20Qu%E1%BA%ADn%203(1).jpg">
            <h3>Phở</h3>
             <a href='https://leesella99-a11y.github.io/pho/'><button>Tìm hiểu thêm</button></a>
        </div>
        <div class="card">
            <img src="https://i-giadinh.vnecdn.net/2024/03/07/7-Hoan-thien-thanh-pham-1-6244-1709800134.jpg">
            <h3>Cơm tấm</h3>
 <a href='https://leesella99-a11y.github.io/comtam/'><button>Tìm hiểu thêm</button></a>
        </div>
    </div>
</section>

<section id="visit" class="visit">
    <div class="visit-text">
        <h2>"Mỗi món ăn được tạo ra đều chứa đựng một tâm tình"</h2>
        <p>Mong rằng sẽ mang đến cho bạn những trải nghiệm tốt nhất. Chúc bạn một ngày tràn đầy niềm.</p>
    </div>
</section>

<footer>
© 2026 Cơm quê dân dã
</footer>

</body>
</html>
