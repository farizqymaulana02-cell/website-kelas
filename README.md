# website-kelas
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kelas Kita — Kenangan Bersama</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;800&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

    <!-- CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <!-- ===================== NAVIGASI ===================== -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="#beranda" class="nav-logo">Kelas Kita</a>

            <!-- Hamburger (mobile) -->
            <button class="nav-hamburger" id="hamburger" aria-label="Menu">
                <span></span>
                <span></span>
                <span></span>
            </button>

            <ul class="nav-menu" id="navMenu">
                <li><a href="#beranda" class="nav-link active">Beranda</a></li>
                <li><a href="#tentang" class="nav-link">Tentang</a></li>
                <li><a href="#anggota" class="nav-link">Anggota</a></li>
                <li><a href="#keluarga" class="nav-link">Keluarga Kami</a></li>
                <li><a href="#potret" class="nav-link">Potret Bersama</a></li>
            </ul>
        </div>
    </nav>

    <!-- ===================== HERO / BERANDA ===================== -->
    <section class="hero" id="beranda">
        <div class="hero-overlay"></div>
        <!-- Ganti src dengan foto bersama asli -->
        <img src="images/hero-bg.jpg" alt="Foto Bersama Kelas" class="hero-bg-img" id="heroBgImg">

        <div class="hero-content">
            <p class="hero-subtitle fade-up">Selamat Datang di Website</p>
            <h1 class="hero-title fade-up">Kelas Kita</h1>
            <div class="hero-divider fade-up"></div>
            <p class="hero-tagline fade-up">Kenangan yang Tak Terlupakan, Ikatan yang Tak Terputuskan</p>
            <a href="#anggota" class="hero-btn fade-up">Lihat Anggota</a>
        </div>

        <!-- Scroll indicator -->
        <div class="scroll-indicator">
            <span></span>
        </div>
    </section>

    <!-- ===================== TENTANG KAMI ===================== -->
    <section class="section tentang" id="tentang">
        <div class="container">
            <h2 class="section-title fade-up">Tentang Kami</h2>
            <div class="section-divider fade-up"></div>
            <div class="tentang-content fade-up">
                <p>
                    Kami adalah satu keluarga besar yang pernah duduk bersama di bangku yang sama,
                    berbagi tawa, cerita, dan mimpi. Website ini dibuat untuk mengenang setiap
                    momen berharga yang telah kita lalui bersama.
                </p>
                <p>
                    Meski waktu terus berjalan dan jalan hidup membawa kita ke arah yang berbeda,
                    ikatan persaudaraan ini akan selalu ada. Selamat menjelajahi kenangan kita!
                </p>
            </div>
        </div>
    </section>

    <!-- ===================== ANGGOTA KELAS ===================== -->
    <section class="section anggota" id="anggota">
        <div class="container">
            <h2 class="section-title fade-up">Anggota Kelas</h2>
            <div class="section-divider fade-up"></div>
            <p class="section-desc fade-up">Wajah-wajah yang membuat hari-hari di kelas penuh warna</p>

            <div class="anggota-grid" id="anggotaGrid">
                <!-- Anggota akan di-generate oleh JavaScript -->
            </div>
        </div>
    </section>

    <!-- ===================== KELUARGA KAMI ===================== -->
    <section class="section keluarga" id="keluarga">
        <div class="container">
            <h2 class="section-title fade-up">Keluarga Kami</h2>
            <div class="section-divider fade-up"></div>
            <p class="section-desc fade-up">Momen-momen kebersamaan yang menjadi kenangan terindah</p>

            <div class="keluarga-grid" id="keluargaGrid">
                <!-- Foto akan di-generate oleh JavaScript -->
            </div>
        </div>
    </section>

    <!-- ===================== POTRET BERSAMA ===================== -->
    <section class="section potret" id="potret">
        <div class="container">
            <h2 class="section-title fade-up">Potret Bersama</h2>
            <div class="section-divider fade-up"></div>
            <p class="section-desc fade-up">Dokumentasi kebersamaan kita dalam satu frame</p>

            <div class="potret-grid" id="potretGrid">
                <!-- Foto akan di-generate oleh JavaScript -->
            </div>
        </div>
    </section>

    <!-- ===================== FOOTER ===================== -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <h3 class="footer-logo">Kelas Kita</h3>
                <p class="footer-text">Kenangan Hari Ini, Cerita Untuk Selamanya</p>
                <div class="footer-divider"></div>
                <p class="footer-copy">&copy; 2025 Kelas Kita. Dibuat dengan ❤️ untuk kita semua.</p>
            </div>
        </div>
    </footer>

    <!-- ===================== LIGHTBOX ===================== -->
    <div class="lightbox" id="lightbox">
        <button class="lightbox-close" id="lightboxClose" aria-label="Tutup">&times;</button>
        <button class="lightbox-prev" id="lightboxPrev" aria-label="Sebelumnya">&#10094;</button>
        <button class="lightbox-next" id="lightboxNext" aria-label="Selanjutnya">&#10095;</button>
        <img src="" alt="Preview" class="lightbox-img" id="lightboxImg">
        <p class="lightbox-caption" id="lightboxCaption"></p>
    </div>

    <!-- Back to Top -->
    <button class="back-to-top" id="backToTop" aria-label="Kembali ke atas">&#8679;</button>

    <!-- JavaScript -->
    <script src="js/main.js"></script>
</body>
</html>
