# fortopolio-<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Digital</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --main: #00d2ff; --bg: #0f172a; --card: #1e293b; }
        * { margin:0; padding:0; box-sizing:border-box; font-family: 'Poppins', sans-serif; }
        body { background-color: var(--bg); color: white; line-height: 1.6; scroll-behavior: smooth; }
        header { height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; background: linear-gradient(rgba(15,23,42,0.7), rgba(15,23,42,0.7)), url('https://images.unsplash.com/photo-1451187580459-43490279c0fa?auto=format&fit=crop&q=80&w=1000') center/cover; padding: 20px; }
        .profile-img { width: 140px; height: 140px; border-radius: 50%; border: 4px solid var(--main); margin-bottom: 20px; box-shadow: 0 0 25px var(--main); object-fit: cover; }
        h1 { font-size: 2.8rem; color: var(--main); margin-bottom: 10px; }
        .tagline { font-size: 1.2rem; color: #94a3b8; margin-bottom: 30px; }
        .btn { padding: 12px 30px; background: var(--main); color: #0f172a; text-decoration: none; border-radius: 50px; font-weight: bold; transition: 0.3s; box-shadow: 0 5px 15px rgba(0,210,255,0.4); }
        .container { padding: 60px 20px; max-width: 900px; margin: auto; }
        h2 { border-left: 6px solid var(--main); padding-left: 15px; margin-bottom: 30px; font-size: 2rem; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 20px; margin-top: 20px; }
        .card { background: var(--card); padding: 30px 20px; border-radius: 20px; text-align: center; transition: 0.3s; border: 1px solid #334155; cursor: pointer; }
        .card:hover { transform: translateY(-10px); border-color: var(--main); box-shadow: 0 10px 20px rgba(0,210,255,0.2); }
        .card i { font-size: 3rem; color: var(--main); margin-bottom: 15px; }
        .p-card { background: var(--card); border-radius: 20px; overflow: hidden; margin-bottom: 30px; border: 1px solid #334155; transition: 0.3s; }
        .p-card:hover { transform: scale(1.02); }
        .p-img { width: 100%; height: 200px; background: #2d3748; display: flex; align-items: center; justify-content: center; font-size: 4rem; color: #475569; }
        .p-info { padding: 25px; }
        .p-info h3 { color: var(--main); margin-bottom: 10px; }
        .tag { background: #334155; padding: 4px 12px; border-radius: 8px; font-size: 0.85rem; margin-right: 8px; color: #cbd5e1; }
        .social-links { display: flex; justify-content: center; gap: 30px; margin-top: 40px; }
        .social-links a { color: white; font-size: 2.5rem; transition: 0.3s; }
        .social-links a:hover { color: var(--main); transform: scale(1.2); }
        footer { text-align: center; padding: 50px; color: #64748b; border-top: 1px solid #1e293b; margin-top: 50px; }
    </style>
</head>
<body>
    <header id="home">
        <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" class="profile-img">
        <h1>[NAMA KAMU]</h1>
        <p class="tagline">Digital Content Creator | Video Editor | AI Enthusiast</p>
        <a href="#projects" class="btn">Lihat Karya Saya</a>
    </header>

    <div class="container">
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Halo! Saya adalah seorang kreator yang fokus pada pembuatan konten digital dan eksplorasi teknologi AI. Saya suka belajar hal baru dan menerapkannya dalam proyek-proyek kreatif.</p>
        </section>

        <section id="skills">
            <h2>Keahlian</h2>
            <div class="grid">
                <div class="card" onclick="alert('Mahir edit video transisi dan cinematic di CapCut')">
                    <i class="fas fa-video"></i>
                    <p>CapCut</p>
                </div>
                <div class="card" onclick="alert('Ahli membuat prompt AI untuk gambar dan teks')">
                    <i class="fas fa-robot"></i>
                    <p>AI Tools</p>
                </div>
                <div class="card" onclick="alert('Desain poster, feed, dan logo di Canva')">
                    <i class="fas fa-palette"></i>
                    <p>Canva Design</p>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>Proyek Kegiatan</h2>
            <div class="p-card">
                <div class="p-img"><i class="fas fa-camera-retro"></i></div>
                <div class="p-info">
                    <h3>Konten Video Viral TikTok</h3>
                    <p>Proyek editing video pendek edukasi teknologi yang mencapai ribuan views.</p>
                    <div style="margin-top:10px;">
                        <span class="tag">#CapCut</span><span class="tag">#ContentCreator</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Mari Terhubung</h2>
            <p style="text-align: center;">Jangan ragu untuk menyapa saya di media sosial!</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-tiktok"></i></a>
                <a href="#"><i class="fas fa-envelope"></i></a>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 [NAMA KAMU]. Dibuat dengan semangat.</p>
    </footer>
</body>
</html>
