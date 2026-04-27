
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil - Serba-Serbi Store</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }

        header {
            background-color: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }

        .welcome {
            background: url('https://via.placeholder.com/1200x400') no-repeat center;
            background-size: cover;
            color: black;
            text-align: center;
            padding: 100px 20px;
        }

        .welcome h1 {
            font-size: 40px;
            margin: 0;
        }

        .welcome p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .btn-toko {
            display: inline-block;
            padding: 12px 25px;
            background-color: #e30707;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            transition: 0.3s;
        }

        .btn-toko:hover {
            background-color: #e30707;
        }

        .profil {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #222;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h2>Serba-Serbi Store</h2>
</header>

<section class="welcome">
    <h1>Welcome to Serba-Serbi Store</h1>
    <p>Tempat belanja kebutuhan kamu dengan harga terjangkau</p>

    <!-- Tombol ke toko -->
    <a href="index1.html" class="btn-toko">Masuk ke Toko</a>
</section>

<section class="profil">
    <h2>Tentang Kami</h2>
    <p>
        Serba Serbi Store adalah toko online yang menyediakan berbagai macam produk
        mulai dari fashion, aksesoris, hingga kebutuhan sehari-hari.
    </p>
</section>

<footer>
    <p>&copy; 2026 Serba Serbi Store</p>
</footer>

</body>
</html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Serba-Serbi Store</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #f9fafb;
}

/* HEADER */
header {
    background: #333;
    color: white;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

/* HERO */
.hero {
    height: 300px;
    background: url('https://images.unsplash.com/photo-1516826957135-700dedea698c?auto=format&fit=crop&w=1000&q=80') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-content {
    background: rgba(0,0,0,0.5);
    color: white;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

/* KATEGORI */
.kategori {
    padding: 20px;
    text-align: center;
}

.kategori-list a {
    display: inline-block;
    margin: 8px;
    padding: 8px 12px;
    background: #e30707;
    color: white;
    border-radius: 20px;
    text-decoration: none;
    font-size: 13px;
}

/* PRODUK */
.produk {
    padding: 20px;
}

.produk h2 {
    text-align: center;
    margin-bottom: 15px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 15px;
}

/* CARD */
.card {
    background: white;
    padding: 10px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.2s ease;
    position: relative;
}

/* HOVER */
.card:hover {
    transform: translateY(-5px);
}

/* CLICK */
.card:active {
    transform: scale(0.95);
}

.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
    transition: transform 0.2s;
}

.card:active img {
    transform: scale(1.1);
}

/* BADGE */
.badge {
    position: absolute;
    top: 8px;
    left: 8px;
    background: #facc15;
    font-size: 11px;
    padding: 3px 6px;
    border-radius: 5px;
}

/* TEXT */
.card h3 {
    font-size: 14px;
    margin: 8px 0;
}

.price {
    color: #e30707;
    font-weight: bold;
}

/* BUTTON */
button {
    margin-top: 8px;
    padding: 8px;
    width: 100%;
    border: none;
    background: #e30707;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

button:active {
    transform: scale(0.95);
}

/* FOOTER */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>
    <h1>🛒 Serba-Serbi Store</h1>
    <nav>
        <a href="index2.html">Home</a>
        <a href="#produk">Produk</a>
        <a href="#kategori">Kategori</a>
        <a href="#keranjang">Keranjang</a>
    </nav>
</header>

<main>

<!-- HERO -->
<section class="hero" id="home">
    <div class="hero-content">
        <h2>Selamat Datang di Toko Online</h2>
        <p>Temukan gaya casual favoritmu setiap hari 👕🧢</p>
        <button>Belanja Sekarang</button>
    </div>
</section>

<!-- KATEGORI -->
<section class="kategori" id="kategori">
    <h2>Kategori</h2>
    <div class="kategori-list">
        <a href="#sepatu">Sepatu</a>
        <a href="#kaos">Kaos</a>
        <a href="#tas">Tas</a>
        <a href="#topi">Topi</a>
    </div>
</section>

<!-- PRODUK -->
<section class="produk" id="produk">
    <h2>Produk Unggulan</h2>

    <div class="grid">

        <div class="card" id="sepatu">
            <span class="badge">🔥 Best Seller</span>
            <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?auto=format&fit=crop&w=500&q=80" alt="Sepatu">
            <h3>Sneakers nike air force1 x Carhartt WIP</h3>
            <p class="price">Rp 4.500.000</p>
            <button>Tambah ke Keranjang</button>
        </div>

        <div class="card" id="kaos">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=500&q=80" alt="Kaos">
            <h3>Kaos putih casual</h3>
            <p class="price">Rp 199.000</p>
            <button>Tambah ke Keranjang</button>
        </div>

        <div class="card" id="tas">
            <img src="https://images.unsplash.com/photo-1509762774605-f07235a08f1f?auto=format&fit=crop&w=500&q=80" alt="Tas">
            <h3>Tas sport</h3>
            <p class="price">Rp 350.000</p>
            <button>Tambah ke Keranjang</button>
        </div>

        <div class="card" id="topi">
            <img src="https://images.unsplash.com/photo-1521369909029-2afed882baee?auto=format&fit=crop&w=500&q=80" alt="Topi">
            <h3>Topi Casual</h3>
            <p class="price">Rp 120.000</p>
            <button>Tambah ke Keranjang</button>
        </div>

    </div>
</section>

<!-- KERANJANG -->
<section class="produk" id="keranjang">
    <h2>Keranjang</h2>
    <p style="text-align:center;">Belum ada produk ditambahkan</p>
</section>

</main>

<footer>
    <p>📞 083101143920 | ✉️ wiliagustira75@gmail.com</p>
    <p>&copy; 2026 Serba-Serbi Store</p>
</footer>

</body>
</html>
