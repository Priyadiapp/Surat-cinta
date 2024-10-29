<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Saya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f9;
        }

        .profil-container {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px;
            text-align: center;
            padding: 20px;
        }

        .profil-foto {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .profil-nama {
            font-size: 24px;
            font-weight: bold;
            color: #333;
        }

        .profil-deskripsi {
            font-size: 14px;
            color: #666;
            margin: 10px 0 20px;
        }

        .profil-sosial {
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .profil-sosial a {
            text-decoration: none;
            color: #fff;
            width: 30px;
            height: 30px;
            display: flex;
            justify-content: center;
            align-items: center;
            border-radius: 50%;
        }

        .profil-sosial a.facebook { background-color: #3b5998; }
        .profil-sosial a.twitter { background-color: #1da1f2; }
        .profil-sosial a.instagram { background-color: #e1306c; }

        .profil-sosial a:hover {
            opacity: 0.8;
        }
    </style>
</head>
<body>

<div class="profil-container">
    <img src="alkimia_pemurni_alkemi_sihir_alkemi_0_9e5df5f2-6e3d-4c32-a606-5837cec790ae_0.jpg" alt="Foto Profil" class="profil-foto">
    <h2 class="profil-nama">Nama Anda</h2>
    <p class="profil-deskripsi">Ini adalah deskripsi singkat tentang Anda. Contoh: Seorang pengembang web dengan hasrat untuk desain dan teknologi.</p>
    
    <div class="profil-sosial">
        <a href="#" class="facebook">F</a>
        <a href="#" class="twitter">T</a>
        <a href="#" class="instagram">I</a>
    </div>
</div>

</body>
</html>

