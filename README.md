<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arabic for Hospitality - Kursus Profesional Bahasa Arab Perhotelan</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #1a5f7a;
            --primary-dark: #114257;
            --secondary: #57c5b6;
            --accent: #159895;
            --accent-light: #1bb5b2;
            --light: #f9f9f9;
            --dark: #2c3e50;
            --gray: #7f8c8d;
            --light-gray: #e0e6ed;
            --transition: all 0.3s ease;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.7;
            color: var(--dark);
            margin: 0;
            padding: 0;
            background-color: white;
            overflow-x: hidden;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--accent));
            color: white;
            padding: 4rem 2rem 3rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1531545514256-b1400bc00f31?q=80&w=1974&auto=format&fit=crop') center/cover;
            opacity: 0.15;
            z-index: 0;
        }
        
        .header-content {
            position: relative;
            z-index: 1;
            max-width: 900px;
            margin: 0 auto;
        }
        
        nav {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-bottom: 2rem;
            flex-wrap: wrap;
        }
        
        nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            transition: var(--transition);
            font-size: 0.95rem;
            background-color: rgba(255,255,255,0.1);
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255,255,255,0.2);
        }
        
        nav a:hover {
            background-color: rgba(255,255,255,0.3);
            transform: translateY(-2px);
        }
        
        .cta-button {
            display: inline-block;
            background-color: white;
            color: var(--primary);
            padding: 0.8rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 1.5rem;
            transition: var(--transition);
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.15);
            background-color: var(--light);
        }
        
        .cta-button.secondary {
            background-color: transparent;
            color: white;
            border: 2px solid white;
            margin-left: 1rem;
        }
        
        .cta-button.secondary:hover {
            background-color: rgba(255,255,255,0.1);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
            font-weight: 700;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .subtitle {
            font-size: 1.3rem;
            margin-bottom: 1.5rem;
            font-weight: 300;
            opacity: 0.9;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .instructor {
            background-color: rgba(255,255,255,0.3);
            display: inline-flex;
            align-items: center;
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            font-weight: 500;
            margin-top: 1.5rem;
            backdrop-filter: blur(5px);
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .center-title {
            text-align: center;
            margin: 3rem 0;
            position: relative;
        }
        
        .center-title h3 {
            color: var(--primary);
            font-size: 1.8rem;
            margin: 0;
            display: inline-block;
            padding: 0 2rem;
            background-color: white;
            position: relative;
            z-index: 1;
        }
        
        .center-title::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 0;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, var(--secondary), var(--accent));
            z-index: 0;
        }
        
        h2 {
            color: var(--primary);
            font-size: 1.8rem;
            margin-top: 2.5rem;
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }
        
        h2:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 60px;
            height: 4px;
            background: var(--secondary);
            border-radius: 2px;
        }
        
        h3 {
            color: var(--accent);
            font-size: 1.4rem;
            margin-top: 2rem;
            margin-bottom: 1rem;
        }
        
        h4 {
            color: var(--dark);
            font-size: 1.1rem;
            margin-bottom: 0.8rem;
            font-weight: 600;
        }
        
        ul {
            padding-left: 1.2rem;
        }
        
        li {
            margin-bottom: 0.8rem;
            position: relative;
            padding-left: 1.5rem;
        }
        
        li:before {
            content: '\f00c';
            font-family: 'Font Awesome 6 Free';
            font-weight: 900;
            position: absolute;
            left: 0;
            color: var(--secondary);
            font-size: 0.8rem;
        }
        
        .highlight {
            background-color: rgba(87,197,182,0.15);
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            color: var(--accent);
            font-weight: 500;
        }
        
        .example {
            background-color: #f5f9fa;
            padding: 1.2rem 1.5rem;
            border-left: 4px solid var(--secondary);
            margin: 1.5rem 0;
            border-radius: 0 4px 4px 0;
            font-family: 'Courier New', monospace;
            color: var(--dark);
            position: relative;
            overflow: hidden;
        }
        
        .example::before {
            content: 'Contoh';
            position: absolute;
            top: 0;
            right: 0;
            background-color: var(--secondary);
            color: white;
            padding: 0.2rem 0.8rem;
            font-size: 0.7rem;
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            border-radius: 0 0 0 4px;
        }
        
        .card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            margin: 2rem 0;
            box-shadow: 0 8px 30px rgba(0,0,0,0.08);
            border: 1px solid var(--light-gray);
            transition: var(--transition);
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 35px rgba(0,0,0,0.12);
        }
        
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }
        
        .feature-card {
            background: white;
            border-radius: 12px;
            padding: 1.8rem;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
            border: 1px solid var(--light-gray);
            transition: var(--transition);
            text-align: center;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: var(--accent);
            margin-bottom: 1rem;
        }
        
        .benefits-box {
            background: linear-gradient(135deg, rgba(26,95,122,0.03), rgba(87,197,182,0.03));
            border-radius: 12px;
            padding: 2rem;
            margin: 3rem 0;
            border: 1px solid rgba(87,197,182,0.2);
            position: relative;
            overflow: hidden;
        }
        
        .benefits-box::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 5px;
            height: 100%;
            background: linear-gradient(to bottom, var(--primary), var(--accent));
        }
        
        .benefits-box h3 {
            margin-top: 0;
            color: var(--primary);
            font-size: 1.5rem;
        }
        
        .testimonial {
            background: white;
            border-radius: 12px;
            padding: 1.8rem;
            margin: 2rem 0;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
            border-left: 4px solid var(--accent);
            position: relative;
        }
        
        .testimonial::before {
            content: '\201C';
            position: absolute;
            top: 10px;
            left: 10px;
            font-size: 4rem;
            color: rgba(87,197,182,0.2);
            font-family: serif;
            line-height: 1;
        }
        
        .testimonial-content {
            position: relative;
            z-index: 1;
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
            margin-top: 1rem;
        }
        
        .author-info h5 {
            margin: 0;
            font-size: 1rem;
            color: var(--dark);
        }
        
        .author-info p {
            margin: 0;
            font-size: 0.8rem;
            color: var(--gray);
        }
        
        .price-box {
            background: linear-gradient(135deg, var(--primary), var(--primary-dark));
            color: white;
            border-radius: 12px;
            padding: 2.5rem;
            text-align: center;
            margin: 3rem auto;
            max-width: 600px;
            box-shadow: 0 10px 30px rgba(26,95,122,0.2);
        }
        
        .price {
            font-size: 2.5rem;
            font-weight: 700;
            margin: 1rem 0;
        }
        
        .price span {
            font-size: 1rem;
            font-weight: 400;
            opacity: 0.8;
        }
        
        .price-features {
            margin: 1.5rem 0;
            text-align: left;
            padding-left: 1rem;
        }
        
        .price-features li {
            color: white;
            margin-bottom: 0.8rem;
        }
        
        .price-features li:before {
            color: var(--secondary);
        }
        
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.7);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }
        
        .modal-content {
            background-color: white;
            padding: 2rem;
            border-radius: 12px;
            max-width: 500px;
            width: 90%;
            position: relative;
            animation: modalFadeIn 0.3s ease;
        }
        
        @keyframes modalFadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .close-modal {
            position: absolute;
            top: 15px;
            right: 15px;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--gray);
        }
        
        form {
            display: grid;
            gap: 1rem;
        }
        
        input, textarea {
            padding: 0.8rem;
            border: 1px solid var(--light-gray);
            border-radius: 6px;
            font-family: 'Poppins', sans-serif;
        }
        
        .submit-btn {
            background: linear-gradient(to right, var(--accent), var(--accent-light));
            color: white;
            border: none;
            padding: 0.8rem;
            border-radius: 6px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .submit-btn:hover {
            background: linear-gradient(to right, var(--accent-light), var(--accent));
            transform: translateY(-2px);
        }
        
        footer {
            text-align: center;
            margin-top: 4rem;
            padding: 3rem 2rem;
            background-color: var(--primary-dark);
            color: white;
        }
        
        .footer-content {
            max-width: 900px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            text-align: left;
        }
        
        .footer-column h4 {
            color: white;
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }
        
        .footer-column ul {
            list-style: none;
            padding: 0;
        }
        
        .footer-column li {
            margin-bottom: 0.8rem;
        }
        
        .footer-column a {
            color: rgba(255,255,255,0.7);
            text-decoration: none;
            transition: var(--transition);
        }
        
        .footer-column a:hover {
            color: white;
            padding-left: 5px;
        }
        
        .social-links {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin-top: 1.5rem;
        }
        
        .social-links a {
            color: white;
            background-color: rgba(255,255,255,0.1);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: var(--transition);
        }
        
        .social-links a:hover {
            background-color: var(--accent);
            transform: translateY(-3px);
        }
        
        .copyright {
            opacity: 0.8;
            font-size: 0.9rem;
            margin-top: 2rem;
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255,255,255,0.1);
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .subtitle {
                font-size: 1.1rem;
            }
            
            .cta-button {
                display: block;
                margin: 1rem auto;
                width: 80%;
            }
            
            .cta-button.secondary {
                margin-left: auto;
                margin-right: auto;
            }
            
            .container {
                padding: 1.5rem;
            }
            
            .center-title h3 {
                font-size: 1.4rem;
            }
            
            .card-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <nav>
                <a href="#"><i class="fas fa-home"></i> Home</a>
                <a href="#materi"><i class="fas fa-book"></i> Materi</a>
                <a href="#keunggulan"><i class="fas fa-star"></i> Keunggulan</a>
                <a href="#harga"><i class="fas fa-tag"></i> Harga</a>
                <a href="#" id="contact-link"><i class="fas fa-envelope"></i> Kontak</a>
            </nav>
            
            <h1>Arabic for Hospitality</h1>
            <p class="subtitle">Tingkatkan karir hospitality Anda dengan penguasaan bahasa Arab profesional yang dibutuhkan industri perhotelan Timur Tengah</p>
            
            <a href="#harga" class="cta-button"><i class="fas fa-arrow-right"></i> Daftar Sekarang</a>
            <a href="#materi" class="cta-button secondary"><i class="fas fa-play-circle"></i> Lihat Materi</a>
            
            <div class="instructor">
                <span>Pengajar: Khairul Hasbi</span>
            </div>
        </div>
    </header>
    
    <div class="container">
        <div class="center-title">
            <h3>Kursus Bahasa Arab untuk Hospitality</h3>
        </div>
        
        <p>Program intensif ini dirancang khusus untuk profesional hospitality yang ingin bekerja atau sudah bekerja di hotel-hotel Timur Tengah. Dalam 12 pertemuan selama 3 bulan, Anda akan menguasai bahasa Arab praktis yang langsung aplikatif di dunia kerja perhotelan.</p>
        
        <div class="card" id="materi">
            <h3><i class="fas fa-graduation-cap"></i> Materi Pembelajaran</h3>
            
            <h4>Materi 1: Interaksi dengan Tamu Hotel (التعامل مع النزلاء)</h4>
            <p><strong>Topik:</strong> Memproses Check-in dan Permintaan Tamu</p>
            
            <div class="example">
                <strong>Contoh Percakapan + Terjemahan:</strong><br><br>
                الموظف: "مرحباً! هل لديكم حجز مُسبق؟"<br>
                <em>(Petugas: "Halo! Apakah Anda memiliki reservasi sebelumnya?")</em><br><br>
                
                الضيف: "نعم، الاسم أحمد عبد الله."<br>
                <em>(Tamu: "Ya, nama saya Ahmad Abdullah.")</em><br><br>
                
                الموظف: "شكراً، هذه بطاقة المفتاح الإلكتروني. هل لديكم أي طلبات إضافية؟"<br>
                <em>(Petugas: "Terima kasih, ini kartu kunci elektroniknya. Apakah Anda ada permintaan tambahan?")</em><br><br>
                
                الضيف: "نعم، أريد وسادة إضافية."<br>
                <em>(Tamu: "Ya, saya ingin bantal tambahan.")</em>
            </div>
            
            <h4>Materi 2: Menangani Keluhan Tamu (التعامل مع شكاوى النزلاء)</h4>
            <p><strong>Topik:</strong> Merespons Masalah di Kamar</p>
            
            <div class="example">
                <strong>Contoh Percakapan + Terjemahan:</strong><br><br>
                الضيف: "السلام عليكم، التكييف في غرفتي لا يعمل."<br>
                <em>(Tamu: "Assalamualaikum, AC di kamar saya tidak berfungsi.")</em><br><br>
                
                الموظف: "عذراً للإزعاج، سنرسل الفني فوراً."<br>
                <em>(Petugas: "Mohon maaf atas ketidaknyamanan, kami akan mengirim teknisi segera.")</em><br><br>
                
                الضيف: "كم من الوقت سيستغرق الإصلاح؟"<br>
                <em>(Tamu: "Berapa lama perbaikannya akan selesai?")</em><br><br>
                
                الموظف: "سيتم حل المشكلة خلال ٣٠ دقيقة، هل تفضل الانتظار في اللوبي؟"<br>
                <em>(Petugas: "Masalah akan diperbaiki dalam 30 menit, apakah Anda ingin menunggu di lobi?")</em>
            </div>
            
            <h4>Struktur Kursus:</h4>
            <ul>
                <li>12 pertemuan intensif (1x per minggu)</li>
                <li>Durasi 3 bulan dengan materi terstruktur</li>
                <li>Pembelajaran interaktif dengan role-play</li>
                <li>Latihan percakapan situasional</li>
                <li>Praktik langsung dengan skenario hotel nyata</li>
            </ul>
        </div>
        
        <div class="benefits-box" id="keunggulan">
            <h3><i class="fas fa-medal"></i> Keunggulan Program Kami</h3>
            <div class="card-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chalkboard-teacher"></i>
                    </div>
                    <h4>Pengajar Berpengalaman</h4>
                    <p>Khairul Hasbi dengan pengalaman mengajar bahasa Arab untuk hospitality</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-briefcase"></i>
                    </div>
                    <h4>Kurikulum Praktis</h4>
                    <p>Materi berdasarkan kasus nyata di hotel-hotel Arab</p>
                </div>
            </div>
            
            <ul>
                <li><strong>Sertifikat kelulusan</strong> yang diakui oleh lembaga mitra</li>
                <li><strong>Modul digital</strong> lengkap dengan audio pronunciation</li>
                <li><strong>Konsultasi pribadi</strong> dengan pengajar</li>
                <li><strong>Garansi uang kembali</strong> jika tidak puas dengan kualitas</li>
            </ul>
        </div>
        
        <div class="price-box" id="harga">
            <h3>Investasi Pendidikan Anda</h3>
            <p>Mulai karir internasional Anda dengan investasi terjangkau</p>
            <div class="price">Rp 500.000 <span>/peserta</span></div>
            <div class="price-features">
                <ul>
                    <li>12 pertemuan intensif (3 bulan)</li>
                    <li>Modul digital + audio pronunciation</li>
                    <li>Sertifikat kelulusan</li>
                    <li>Pembelajaran interaktif</li>
                    <li>Garansi kepuasan</li>
                </ul>
            </div>
            <a href="#" class="cta-button" id="enroll-button"><i class="fas fa-user-plus"></i> Daftar Sekarang</a>
            <p style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.8;">Pembayaran bisa dicicil 2x tanpa bunga</p>
        </div>
    </div>
    
    <div class="modal" id="contact-modal">
        <div class="modal-content">
            <span class="close-modal">&times;</span>
            <h3>Hubungi Kami</h3>
            <p>Isi form berikut untuk informasi lebih lanjut tentang program Arabic for Hospitality</p>
            <form id="contact-form">
                <input type="text" placeholder="Nama Lengkap" required>
                <input type="email" placeholder="Email" required>
                <input type="tel" placeholder="Nomor WhatsApp">
                <textarea placeholder="Pertanyaan Anda" rows="4"></textarea>
                <button type="submit" class="submit-btn">Kirim Pesan</button>
            </form>
        </div>
    </div>
    
    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h4>Arabic for Hospitality</h4>
                <p>Program pelatihan bahasa Arab profesional khusus untuk industri perhotelan dan hospitality.</p>
                <div class="social-links">
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-whatsapp"></i></a>
                    <a href="#"><i class="fab fa-linkedin"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
            
            <div class="footer-column">
                <h4>Link Cepat</h4>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#materi">Materi</a></li>
                    <li><a href="#keunggulan">Keunggulan</a></li>
                    <li><a href="#harga">Harga</a></li>
                    <li><a href="#" id="footer-contact">Kontak</a></li>
                </ul>
            </div>
            
            <div class="footer-column">
                <h4>Kontak Kami</h4>
                <ul>
                    <li><i class="fas fa-envelope"></i> info@arabicforhospitality.com</li>
                    <li><i class="fas fa-phone"></i> +62 812 3456 7890</li>
                    <li><i class="fas fa-map-marker-alt"></i> Pekanbaru, Indonesia</li>
                </ul>
            </div>
        </div>
        
        <div class="copyright">
            Copyright © 2025 Arabic for Hospitality by Khairul Hasbi. All rights reserved.
        </div>
    </footer>
    
    <script>
        // Modal functionality
        const contactLink = document.getElementById('contact-link');
        const footerContact = document.getElementById('footer-contact');
        const contactModal = document.getElementById('contact-modal');
        const closeModal = document.querySelector('.close-modal');
        const enrollButton = document.getElementById('enroll-button');
        
        contactLink.addEventListener('click', function(e) {
            e.preventDefault();
            contactModal.style.display = 'flex';
            document.body.style.overflow = 'hidden';
        });
        
        footerContact.addEventListener('click', function(e) {
            e.preventDefault();
            contactModal.style.display = 'flex';
            document.body.style.overflow = 'hidden';
        });
        
        enrollButton.addEventListener('click', function(e) {
            e.preventDefault();
            contactModal.style.display = 'flex';
            document.body.style.overflow = 'hidden';
        });
        
        closeModal.addEventListener('click', function() {
            contactModal.style.display = 'none';
            document.body.style.overflow = 'auto';
        });
        
        window.addEventListener('click', function(e) {
            if (e.target === contactModal) {
                contactModal.style.display = 'none';
                document.body.style.overflow = 'auto';
            }
        });
        
        // Form submission
        const contactForm = document.getElementById('contact-form');
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Terima kasih! Pesan Anda telah terkirim. Kami akan menghubungi Anda segera.');
            contactModal.style.display = 'none';
            document.body.style.overflow = 'auto';
            contactForm.reset();
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
