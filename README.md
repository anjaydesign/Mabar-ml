<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mabar Mobile Legends</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Mabar Mobile Legends</h1>
        <button id="toggleMode">🌙</button>
    </header>

    <!-- Slider -->
    <section class="slider">
        <div class="slides">
            <img src="img1.jpg" alt="Gambar 1">
            <img src="img2.jpg" alt="Gambar 2">
            <img src="img3.jpg" alt="Gambar 3">
        </div>
    </section>

    <!-- Leaderboard -->
    <section class="leaderboard">
        <h2>Leaderboard</h2>
        <ul>
            <li>1. PlayerA - 5000 Poin</li>
            <li>2. PlayerB - 4500 Poin</li>
            <li>3. PlayerC - 4000 Poin</li>
        </ul>
    </section>

    <!-- Formulir Pendaftaran -->
    <section class="form">
        <h2>Daftar Mabar</h2>
        <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
            <input type="text" name="nama" placeholder="Nama Anda" required>
            <input type="email" name="email" placeholder="Email" required>
            <button type="submit">Daftar</button>
        </form>
    </section>

    <!-- Chat Box -->
    <section class="chat">
        <h2>Chat Mabar</h2>
        <div id="chatBox">
            <p><strong>PlayerX:</strong> Siap mabar malam ini?</p>
        </div>
        <input type="text" id="chatInput" placeholder="Ketik pesan...">
        <button onclick="sendMessage()">Kirim</button>
    </section>

    <!-- Tautan WhatsApp -->
    <footer>
        <a href="https://wa.me/YOUR_PHONE_NUMBER" class="whatsapp">Gabung Grup WhatsApp</a>
    </footer>
</body>
</html>
