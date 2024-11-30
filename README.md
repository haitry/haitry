<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Bisnis</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Bisnis Kami</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#">Beranda</a></li>
        <li><a href="#gallery">Galeri</a></li>
        <li><a href="#shop">Toko</a></li>
        <li><a href="#contact">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Selamat Datang di Website Kami</h2>
    <p>Temukan produk terbaik dan layanan terbaik untuk kebutuhan Anda.</p>
  </section>

  <section id="gallery" class="gallery">
    <h2>Galeri Foto</h2>
    <div class="gallery-grid">
      <div class="gallery-item"><img src="image1.jpg" alt="Foto 1"></div>
      <div class="gallery-item"><img src="image2.jpg" alt="Foto 2"></div>
      <div class="gallery-item"><img src="image3.jpg" alt="Foto 3"></div>
    </div>
  </section>

  <section id="shop" class="shop">
    <h2>Produk Kami</h2>
    <div class="shop-items">
      <div class="shop-item">
        <img src="product1.jpg" alt="Produk 1">
        <p>Produk 1</p>
        <p>Rp 100.000</p>
        <button>Beli Sekarang</button>
      </div>
      <div class="shop-item">
        <img src="product2.jpg" alt="Produk 2">
        <p>Produk 2</p>
        <p>Rp 200.000</p>
        <button>Beli Sekarang</button>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Kontak Kami</h2>
    <form>
      <label for="name">Nama:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <button type="submit">Kirim</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Bisnis Kami. Semua hak dilindungi.</p>
  </footer>

</body>
</html>
/* Reset dasar */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body dan font */
body {
  font-family: 'Courier New', Courier, monospace;
  background-color: #111;
  color: #fff;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  padding: 20px;
  background-color: #000;
}

header .logo h1 {
  font-size: 2.5rem;
  color: #00f;
}

header nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

header nav a {
  color: #fff;
  text-decoration: none;
  font-size: 1.1rem;
  transition: color 0.3s ease;
}

header nav a:hover {
  color: #00f;
}

/* Hero Section */
.hero {
  background: #111;
  color: #00f;
  padding: 50px 20px;
  text-align: center;
}

.hero h2 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.5rem;
}

/* Gallery Section */
.gallery {
  background-color: #222;
  padding: 50px 20px;
  text-align: center;
}

.gallery h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.gallery-item img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.gallery-item img:hover {
  transform: scale(1.05);
}

/* Shop Section */
.shop {
  padding: 50px 20px;
  text-align: center;
  background-color: #111;
}

.shop h2 {
  font-size: 2.5rem;
  margin-bottom: 30px;
}

.shop-items {
  display: flex;
  justify-content: space-around;
}

.shop-item {
  background-color: #222;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  width: 200px;
}

.shop-item img {
  width: 100%;
  border-radius: 8px;
}

.shop-item p {
  margin: 10px 0;
  font-size: 1.1rem;
}

.shop-item button {
  padding: 10px;
  background-color: #00f;
  border: none;
  color: #fff;
  font-size: 1.2rem;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.shop-item button:hover {
  background-color: #00d;
}

/* Contact Section */
.contact {
  padding: 50px 20px;
  background-color: #222;
  text-align: center;
}

.contact form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.contact label {
  margin-bottom: 10px;
  font-size: 1.2rem;
}

.contact input {
  padding: 10px;
  margin-bottom: 20px;
  font-size: 1.1rem;
  border: 1px solid #fff;
  background-color: #444;
  color: #fff;
  width: 300px;
}

.contact button {
  padding: 10px 20px;
  font-size: 1.2rem;
  background-color: #00f;
  border: none;
  color: #fff;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact button:hover {
  background-color: #00d;
}

/* Footer */
footer {
  background-color: #000;
  text-align: center;
  padding: 20px;
}

footer p {
  font-size: 1rem;
  color: #aaa;
}

/* Animation effect (Gravitasi) */
@keyframes gravityEffect {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
  100% {
    transform: scale(1);
  }
}

body {
  animation: gravityEffect 2s infinite ease-in-out;
}
