#<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Dennis Satriya | Biodata & Motivasi</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', 'Segoe UI', system-ui, -apple-system, 'Inter', sans-serif;
            background: linear-gradient(145deg, #0b2b26 0%, #1a4a44 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 1.5rem;
            position: relative;
        }

        /* background motif */
        body::before {
            content: "✨";
            font-size: 280px;
            position: absolute;
            bottom: 0;
            left: -50px;
            opacity: 0.08;
            pointer-events: none;
            white-space: nowrap;
        }

        body::after {
            content: "🍃";
            font-size: 220px;
            position: absolute;
            top: 20px;
            right: -30px;
            opacity: 0.08;
            pointer-events: none;
            transform: rotate(15deg);
        }

        .card-container {
            max-width: 550px;
            width: 100%;
            background: rgba(255, 248, 235, 0.96);
            backdrop-filter: blur(2px);
            border-radius: 72px;
            box-shadow: 0 35px 60px rgba(0, 0, 0, 0.4), inset 0 1px 2px rgba(255, 255, 200, 0.6);
            overflow: hidden;
            transition: transform 0.2s ease;
            z-index: 2;
        }

        .card-container:hover {
            transform: scale(1.01);
        }

        /* header dengan aksen */
        .profile-header {
            background: linear-gradient(135deg, #ffb347, #ff8c42);
            padding: 2rem 2rem 1.8rem;
            text-align: center;
            color: white;
            clip-path: polygon(0 0, 100% 0, 100% 88%, 0 100%);
        }

        .avatar {
            background: white;
            width: 110px;
            height: 110px;
            border-radius: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1rem;
            box-shadow: 0 12px 20px rgba(0,0,0,0.2);
            border: 4px solid #fff5e6;
        }

        .avatar span {
            font-size: 4.2rem;
        }

        .profile-header h1 {
            font-size: 2rem;
            font-weight: 800;
            letter-spacing: -0.5px;
            text-shadow: 2px 2px 0 #c55f1a;
            word-break: break-word;
        }

        .badge {
            background: #f5e7d3c9;
            display: inline-block;
            padding: 0.3rem 1rem;
            border-radius: 80px;
            font-size: 0.8rem;
            font-weight: 600;
            color: #b64926;
            margin-top: 10px;
            backdrop-filter: blur(2px);
        }

        /* isi biodata */
        .bio-content {
            padding: 2rem 2rem 1.8rem;
        }

        .info-grid {
            background: #fffaf3;
            border-radius: 48px;
            padding: 1rem 1.5rem;
            margin-bottom: 1.8rem;
            box-shadow: inset 0 0 0 1px #ffe6cd, 0 5px 12px rgba(0,0,0,0.05);
        }

        .info-item {
            display: flex;
            align-items: baseline;
            padding: 0.8rem 0;
            border-bottom: 1px dashed #ffddb0;
        }

        .info-item:last-child {
            border-bottom: none;
        }

        .info-label {
            width: 95px;
            font-weight: 700;
            color: #b44d1a;
            font-size: 1rem;
        }

        .info-value {
            flex: 1;
            color: #2d2b26;
            font-weight: 500;
            font-size: 1.05rem;
            word-break: break-word;
        }

        .quote-box {
            background: #eef3e8;
            border-radius: 2rem;
            padding: 1.2rem 1.5rem;
            margin: 1.2rem 0 1.8rem;
            text-align: center;
            border-left: 8px solid #f39c12;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }

        .quote-text {
            font-size: 1.1rem;
            font-weight: 500;
            color: #2c5a2e;
            font-style: italic;
        }

        .quote-author {
            margin-top: 8px;
            font-size: 0.8rem;
            color: #6d6b48;
        }

        /* tombol link */
        .btn-link {
            display: block;
            background: linear-gradient(95deg, #2c7a47, #1f9e5c);
            text-align: center;
            text-decoration: none;
            padding: 1rem 1rem;
            border-radius: 60px;
            font-weight: bold;
            font-size: 1.2rem;
            color: white;
            transition: all 0.2s ease;
            margin: 1.5rem 0 0.8rem;
            box-shadow: 0 8px 14px rgba(0, 0, 0, 0.2);
            border: none;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .btn-link:hover {
            background: linear-gradient(95deg, #1f673c, #148a4b);
            transform: translateY(-3px);
            box-shadow: 0 15px 20px rgba(0, 0, 0, 0.25);
        }

        .btn-link:active {
            transform: translateY(2px);
        }

        .footer-note {
            text-align: center;
            font-size: 0.7rem;
            color: #b9a684;
            margin-top: 1rem;
            padding-bottom: 0.5rem;
        }

        /* dekorasi tambahan */
        .leaf-icon {
            display: inline-block;
            margin: 0 4px;
        }

        @media (max-width: 480px) {
            .profile-header h1 { font-size: 1.6rem; }
            .info-label { width: 80px; font-size: 0.9rem; }
            .info-value { font-size: 0.95rem; }
            .btn-link { font-size: 1rem; padding: 0.8rem; }
            .bio-content { padding: 1.5rem; }
        }
    </style>
</head>
<body>
    <div class="card-container">
        <div class="profile-header">
            <div class="avatar">
                <span>🧑‍🎓</span>
            </div>
            <h1>Dennis Satriya</h1>
            <div class="badge">✨ Generasi penerus ✨</div>
        </div>

        <div class="bio-content">
            <div class="info-grid">
                <div class="info-item">
                    <div class="info-label">🌟 Nama lengkap</div>
                    <div class="info-value">Dennis Satriya</div>
                </div>
                <div class="info-item">
                    <div class="info-label">🎂 Usia</div>
                    <div class="info-value">16 tahun</div>
                </div>
                <div class="info-item">
                    <div class="info-label">🏫 Sekolah</div>
                    <div class="info-value">SMAN 15 JAKARTA - Kelas X5</div>
                </div>
                <div class="info-item">
                    <div class="info-label">📌 Motto</div>
                    <div class="info-value">Belajar, tumbuh, dan berkarya</div>
                </div>
            </div>

            <div class="quote-box">
                <div class="quote-text">“Belajarlah untuk menjadi lebih baik, setiap hari adalah kesempatan baru untuk versi terbaik dirimu.”</div>
                <div class="quote-author">— Dennis Satriya —</div>
            </div>

            <!-- Tombol menuju web ninja -->
            <a href="https://denissatriyalibels.github.io/Ninja-denn/" target="_blank" rel="noopener noreferrer" class="btn-link">
                <span>⚔️🍉</span> Kunjungi Ninja-Denn <span>🗡️✨</span>
            </a>
            
            <div class="footer-note">
                🌱 Semangat terus, Dennis! Masa depan cerah menanti 🌟
            </div>
        </div>
    </div>

    <!-- efek tambahan untuk interaksi (opsional) -->
    <script>
        // sedikit animasi halus pada hover tombol, sudah pakai css
        // memastikan link terbuka dengan aman
        console.log("Biodata Dennis Satriya — jadilah lebih baik setiap hari");
    </script>
</body>
</html>
```
