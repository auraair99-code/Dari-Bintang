
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untukmu Langitku</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,400&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * { box-sizing: border-box; }
        
        body {
            margin: 0;
            padding: 0;
            background-color: #010614;
            font-family: 'Montserrat', sans-serif;
            color: #ffffff;
            display: flex;
            justify-content: center;
            overflow-x: hidden;
            background-image: url('https://www.transparenttextures.com/patterns/dark-dotted.png');
        }

        .wrapper {
            width: 100%;
            max-width: 450px;
            background: rgba(2, 10, 30, 0.95);
            min-height: 100vh;
            position: relative;
            box-shadow: 0 0 40px rgba(0,0,0,0.5);
            padding-bottom: 120px;
        }

        .header {
            background-color: #1a3a5f;
            background-image: url('https://www.transparenttextures.com/patterns/dark-paths.png'), linear-gradient(180deg, #1a3a5f 0%, #010614 100%);
            color: white;
            padding: 60px 30px;
            position: relative;
            clip-path: polygon(0 0, 100% 0, 100% 88%, 85% 98%, 70% 88%, 55% 98%, 40% 88%, 25% 98%, 0 88%);
        }

        .header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            margin: 0;
        }

        .header p {
            font-family: 'Playfair Display', serif;
            font-style: italic;
            font-size: 18px;
            opacity: 0.9;
            margin: 5px 0 0 0;
        }

        .decor-star {
            position: absolute;
            color: #ffffff;
            font-size: 14px;
            animation: twinkle 2s infinite ease-in-out;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.2; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.1); }
        }

        .star1 { top: 20px; right: 30px; animation-delay: 0.2s; }
        .star2 { top: 110px; left: 40px; animation-delay: 0.7s; }
        .star3 { top: 300px; right: 80px; animation-delay: 1.2s; }
        .star4 { top: 550px; left: 60px; animation-delay: 0.4s; }
        .star5 { top: 780px; right: 40px; animation-delay: 0.9s; }

        .title-section {
            text-align: right;
            padding: 30px 30px 10px 30px;
            color: #ffffff;
        }

        .title-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 55px;
            line-height: 0.9;
            margin: 0;
            font-weight: bold;
        }

        .message-card {
            background: rgba(255, 255, 255, 0.08);
            margin: 0 25px 20px 25px;
            padding: 20px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
            transition: transform 0.3s ease;
        }

        .message-card h3 {
            font-size: 17px;
            font-weight: 600;
            color: #b5ccf1;
            margin-top: 0;
            margin-bottom: 10px;
            border-left: 4px solid #ffffff;
            padding-left: 10px;
        }

        .message-card p {
            font-size: 13px;
            line-height: 1.6;
            margin: 0;
            text-align: justify;
            color: #f0f0f0;
        }

        .footer {
            background-color: #1a3a5f;
            color: white;
            padding: 50px 20px 30px 20px;
            text-align: center;
            position: absolute;
            bottom: 0;
            width: 100%;
            clip-path: polygon(0 20%, 15% 0%, 30% 20%, 45% 0%, 60% 20%, 75% 0%, 90% 20%, 100% 0%, 100% 100%, 0 100%);
        }

        .footer p {
            font-size: 14px;
            font-weight: 600;
            margin: 0;
        }

        .fade-in {
            animation: fadeIn 2.5s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <div class="wrapper fade-in">
        <div class="header">
            <div class="decor-star star1">✦</div>
            <div class="decor-star star2">✦</div>
            <h1>Untukmu Langitku</h1>
            <p>Giselle Danisha Putri</p>
        </div>

        <div class="decor-star star3">✦</div>
        <div class="decor-star star4">✦</div>
        <div class="decor-star star5">✦</div>

        <div class="title-section">
            <h2>Happy<br>Birthday</h2>
        </div>

        <div class="message-card">
            <h3>Barakallah fii umrik, Sayangku.</h3>
            <p>Hari ini, di hari bertambahnya usiamu, aku bersyukur kamu masih ada di sini, tapi di sisi lain, hatiku selalu sesak kalau ingat betapa besarnya luka yang pernah aku buat di hatimu. Maaf saja nggak akan pernah cukup.</p>
        </div>

        <div class="message-card">
            <h3>Kesadaran & Kesempatan</h3>
            <p>Aku sadar betapa buruknya kelakuanku, mengkhianati ketulusanmu. Tapi hal hebatnya, kamu tetap memilih bersamaku, menemaniku dalam perubahanku. Kesempatan ini nggak boleh aku sia-siain lagi.</p>
        </div>

        <div class="message-card">
            <h3>Doa & Janji</h3>
            <p>Semoga Allah SWT selalu menjaga hatimu yang begitu luas, dan semoga cinta kita abadi hingga ke jenjang pernikahan nanti. Aku berjanji akan jadi laki-laki yang jujur dan setia.</p>
        </div>

        <div class="message-card">
            <h3>Lahir Kembali</h3>
            <p>27 bukan cuma soal umurmu yang bertambah, tapi soal hubungan kita yang "lahir kembali" dari luka yang pernah aku buat. Aku berjanji pada diriku sendiri untuk menebusnya dengan berubah jadi versi terbaikku.</p>
        </div>

        <div class="message-card">
            <h3>Harapan & Masa Depan Bersama</h3>
            <p>Di sisa usiamu ini, aku tidak berhenti meminta kepada Allah agar Dia selalu melindungimu, memudahkan langkahmu, dan menjaga senyummu agar tidak pernah hilang. Aku memohon agar diberikan umur yang berkah untuk kita, kesehatan yang baik, dan rezeki yang lancar agar aku bisa segera membawamu ke pelaminan dan membangun keluarga yang sakinah. Amin.</p>
        </div>

        <div class="message-card">
            <h3>Terima Kasih, Langitku</h3>
            <p>Terima kasih sudah lahir ke dunia ini, dan terima kasih sudah memilih untuk tinggal meski badai pernah aku datangkan. Kamu adalah bukti paling nyata dari kasih sayang Allah untukku. Aku tidak janji dunia akan selalu mudah, tapi aku janji kamu tidak akan pernah menghadapinya sendirian lagi. I love you, Langitku.</p>
        </div>

        <div class="footer">
            <p>Happy birthday, my visionary girl.<br>I love you more than words can say.</p>
        </div>
    </div>

</body>
</html>
