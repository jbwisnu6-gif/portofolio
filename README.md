#Portofolio<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio | Wisnu Widodo</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #1f4068, #162447);
            color: #fff;
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        .container {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 20px;
        }

        section {
            background: #fff;
            padding: 30px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        h2 {
            color: #1f4068;
            border-bottom: 2px solid #e4e4e4;
            padding-bottom: 8px;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        .info-grid {
            display: grid;
            grid-template-columns: 150px 1fr;
            row-gap: 10px;
        }

        .info-label {
            font-weight: bold;
            color: #555;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 10px;
        }

        .skill-badge {
            background-color: #e1e8f0;
            color: #1f4068;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        .project-item {
            margin-bottom: 15px;
        }

        .project-item h3 {
            color: #162447;
            font-size: 1.2rem;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.9rem;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <!-- Header / Hero Section -->
    <header>
        <h1>Wisnu Widodo</h1>
        <p>Siswa Kelas XI | Pelajar & Kreator Digital</p>
    </header>

    <div class="container">

        <!-- Tentang Saya -->
        <section id="tentang">
            <h2>Tentang Saya</h2>
            <p>Halo! Saya Wisnu Widodo, seorang siswa kelas XI yang memiliki ketertarikan kuat di dunia teknologi, manajemen kasual, dan pengembangan kreativitas digital. Saya senang mempelajari hal-hal baru, adaptif terhadap tantangan, serta selalu berkomitmen untuk menyelesaikan setiap tugas atau proyek sekolah secara maksimal.</p>
        </section>

        <!-- Biodata Diri -->
        <section id="biodata">
            <h2>Biodata Diri</h2>
            <div class="info-grid">
                <div class="info-label">Nama Lengkap</div>
                <div>Wisnu Widodo</div>

                <div class="info-label">Status</div>
                <div>Pelajar Aktif (Kelas XI)</div>

                <div class="info-label">Lokasi</div>
                <div>Indonesia</div>

                <div class="info-label">Kontak / Email</div>
                <div>wisnuwidodo@example.com (Sesuaikan dengan emailmu)</div>
            </div>
        </section>

        <!-- Skill / Keahlian -->
        <section id="keahlian">
            <h2>Keahlian & Minat</h2>
            <p>Beberapa bidang dan keterampilan yang sedang saya tekuni saat ini meliputi:</p>
            <div class="skills-list">
                <span class="skill-badge">HTML & CSS Dasar</span>
                <span class="skill-badge">Dokumentasi Video</span>
                <span class="skill-badge">Perencanaan Bisnis Dasar</span>
                <span class="skill-badge">Manajemen Organisasi</span>
                <span class="skill-badge">Kerja Sama Tim</span>
            </div>
        </section>

        <!-- Pengalaman / Proyek -->
        <section id="proyek">
            <h2>Pengalaman & Proyek Akademik</h2>
            
            <div class="project-item">
                <h3>1. Proyek Video Kreatif</h3>
                <p>Berpengalaman dalam menyusun konsep alur cerita (storyline) dan teknis dasar dalam pembuatan video dokumentasi kreatif berkelompok untuk kegiatan sekolah.</p>
            </div>

            <div class="project-item" style="margin-top: 20px;">
                <h3>2. Rancangan Strategi Wirausaha Dasar</h3>
                <p>Pernah menyusun rancangan sederhana untuk model bisnis mikro, berfokus pada strategi pemasaran dan pengelolaan stok barang kebutuhan pokok secara efektif.</p>
            </div>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Wisnu Widodo. Dibuat dengan semangat.</p>
    </footer>

</body>
</html>
