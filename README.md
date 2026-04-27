<!DOCTYPE html>
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

/* LANDING (WELCOME) */
.landing {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=1000&q=80') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
}

.landing-box {
    background: rgba(0,0,0,0.6);
    color: white;
    padding: 30px;
    border-radius: 15px;
    text-align: center;
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

.card:hover {
    transform: translateY(-5px);
}

.card:active {
    transform: scale(0.95);
}

.card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.badge {
    position: absolute;
    top: 8px;
    left: 8px;
    background: #facc15;
    font-size: 11px;
    padding: 3px 6px;
    border-radius: 5px;
}

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

<!-- LANDING -->
<section class="landing">
    <div class="landing-box">
        <h1>Selamat Datang di Serba-Serbi Store</h1>
        <p>Toko online fashion casual terbaik untuk kamu</p>
        <a href="#produk">
            <button>Masuk ke Toko</button>
        </a>
    </div>
</section>

<header>
    <h1>🛒 Serba-Serbi Store</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#produk">Produk</a>
        <a href="#kategori">Kategori</a>
        <a href="#keranjang">Keranjang</a>
    </nav>
</header>

<main>

<!-- HERO -->
<section class="hero">
    <div class="hero-content">
        <h2>Belanja Mudah & Cepat</h2>
        <p>Temukan produk favoritmu sekarang</p>
        <a href="#produk">
            <button>Belanja Sekarang</button>
        </a>
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
            <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?auto=format&fit=crop&w=500&q=80">
            <h3>Sneakers Casual</h3>
            <p class="price">Rp 4.500.000</p>
            <button>Beli Sekarang</button>
        </div>

        <div class="card" id="kaos">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=500&q=80">
            <h3>Kaos Casual</h3>
            <p class="price">Rp 250.000</p>
            <button>Beli Sekarang</button>
        </div>

        <div class="card" id="tas">
            <img src="https://images.unsplash.com/photo-1509762774605-f07235a08f1f?auto=format&fit=crop&w=500&q=80">
            <h3>Tas Ransel</h3>
            <p class="price">Rp 500.000</p>
            <button>Beli Sekarang</button>
        </div>

        <div class="card" id="topi">
            <img src="https://images.unsplash.com/photo-1521369909029-2afed882baee?auto=format&fit=crop&w=500&q=80">
            <h3>Topi Casual</h3>
            <p class="price">Rp 120.000</p>
            <button>Beli Sekarang</button>
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
