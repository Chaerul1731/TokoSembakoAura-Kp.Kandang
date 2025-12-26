<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Sembako Aura Kp. Kandang</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .hero {
            background: linear-gradient(135deg, #00ff00, #ffff00, #ff0000);
            color: white;
            text-align: center;
            padding: 50px 20px;
            animation: fadeIn 2s;
        }
        .hero h1 {
            font-size: 3em;
            font-weight: bold;
            margin: 0;
        }
        .hero p {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .badge {
            display: inline-block;
            background: #ff4500;
            padding: 10px;
            border-radius: 5px;
            margin: 10px;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            padding: 15px 30px;
            margin: 10px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            text-decoration: none;
            color: white;
        }
        .btn-green { background: #00ff00; }
        .btn-red { background: #ff0000; }
        .products {
            padding: 20px;
            text-align: center;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        .product-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            animation: slideIn 1s;
        }
        .product-card h3 {
            color: #00ff00;
        }
        .highlight {
            background: #ffff00;
            padding: 20px;
            text-align: center;
            margin: 20px 0;
            border-radius: 10px;
        }
        .features {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background: #e0e0e0;
        }
        .feature {
            text-align: center;
        }
        .promo {
            padding: 20px;
            background: #ffcccc;
            text-align: center;
        }
        .contact {
            padding: 20px;
            text-align: center;
        }
        .footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        .floating-whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #25d366;
            color: white;
            padding: 15px;
            border-radius: 50%;
            font-size: 1.5em;
            text-decoration: none;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @media (max-width: 768px) {
            .hero h1 { font-size: 2em; }
            .product-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <h1>🏪 SEMBAKO LENGKAP • HARGA RAKYAT</h1>
        <p>Belanja kebutuhan harian jadi mudah di Toko Sembako Aura Kp. Kandang</p>
        <div class="badge">🔥 Murah Setiap Hari</div>
        <div class="badge">🚚 Siap Antar Sekitar Kp. Kandang</div>
        <a href="https://wa.me/6281234567890" class="btn btn-green">🟢 PESAN VIA WHATSAPP</a>
        <a href="#products" class="btn btn-red">🔴 CEK DAFTAR BARANG</a>
    </section>

    <!-- Produk Utama -->
    <section id="products" class="products">
        <h2>🛒 PRODUK UTAMA</h2>
        <div class="product-grid">
            <div class="product-card">
                <h3>🍚 Beras</h3>
                <p>Premium, Medium, Curah</p>
                <span class="badge">Best Seller</span>
            </div>
            <div class="product-card">
                <h3>🛢️ Minyak Goreng</h3>
                <p>Varian lengkap</p>
            </div>
            <div class="product-card">
                <h3>🍬 Gula Pasir</h3>
                <p>Kualitas terbaik</p>
            </div>
            <div class="product-card">
                <h3>🌾 Tepung Terigu</h3>
                <p>Untuk semua kebutuhan</p>
            </div>
            <div class="product-card">
                <h3>🥚 Telur Ayam</h3>
                <p>Segar setiap hari</p>
            </div>
            <div class="product-card">
                <h3>🍜 Mie Instan</h3>
                <p>Berbagai rasa</p>
            </div>
            <div class="product-card">
                <h3>🥛 Susu</h3>
                <p>Kental, Cair, Bubuk</p>
            </div>
            <div class="product-card">
                <h3>☕ Kopi & 🍵 Teh</h3>
                <p>Aromanya nikmat</p>
            </div>
            <div class="product-card">
                <h3>🧂 Garam</h3>
                <p>Esensial dapur</p>
            </div>
            <div class="product-card">
                <h3>🌶️ Bumbu Dapur Lengkap</h3>
                <p>Semua tersedia</p>
            </div>
        </div>
    </section>

    <!-- Produk Andal -->
    <section class="highlight">
        <h2>⛽💧 PRODUK ANDALAN</h2>
        <p>⛽ Gas LPG 3 Kg & 12 Kg – SELALU TERSEDIA</p>
        <p>💧 Galon Air Mineral – Isi Ulang & Baru</p>
        <p>“Stok aman, tidak perlu cari ke tempat lain!”</p>
    </section>

    <!-- Keunggulan Toko -->
    <section class="features">
        <div class="feature">
            <h3>💰 Harga Bersahabat</h3>
        </div>
        <div class="feature">
            <h3>📦 Barang Lengkap</h3>
        </div>
        <div class="feature">
            <h3>📍 Dekat & Mudah Dijangkau</h3>
        </div>
        <div class="feature">
            <h3>😊 Pelayanan Ramah</h3>
        </div>
    </section>

    <!-- Promo & Paket Hemat -->
    <section class="promo">
        <h2>🎁 PROMO & PAKET HEMAT</h2>
        <p>Paket sembako hemat keluarga</p>
        <p>Diskon pembelian banyak</p>
        <p>Promo harian & mingguan</p>
    </section>

    <!-- Hubungi Kami -->
    <section class="contact">
        <h2>📞 HUBUNGI KAMI</h2>
        <p>Lokasi: <a href="https://maps.app.goo.gl/2GS3uzBMqAprHxMA9" target="_blank">Kp. Kandang</a></p>
        <p>Jam Buka: 24 Jam</p>
        <a href="https://wa.me/6281234567890" class="btn btn-green">Pesan Sekarang</a>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <h3>Toko Sembako Aura Kp. Kandang</h3>
        <p>“Belanja dekat, hemat, dan nyaman”</p>
        <a href="https://wa.me/6281234567890">📱 WhatsApp</a> | <a href="https://maps.app.goo.gl/2GS3uzBMqAprHxMA9" target="_blank">🗺️ Maps</a>
    </footer>

    <!-- Floating WhatsApp -->
    <a href="https://wa.me/6281234567890" class="floating-whatsapp">💬</a>

    <script>
        // Simple animation for product cards
        const cards = document.querySelectorAll('.product-card');
        cards.forEach((card, index) => {
            card.style.animationDelay = `${index * 0.1}s`;
        });
    </script>
</body>
</html>
