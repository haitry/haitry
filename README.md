- 👋 Hi, I’m @haitry
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
haitry/haitry is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
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

