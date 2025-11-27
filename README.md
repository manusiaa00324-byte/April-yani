<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portofolio Saya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Poppins", sans-serif;
        }

        body {
            background:  #808080;
            color: #222;
        }

        header {
            width: 100%;
            padding: 20px 50px;
            background: #0a3d62;
            color: white
      ;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            font-size: 24px;
            font-weight: 600;
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: white;
            font-weight: 500;
        }

        nav a:hover {
            color: #82ccdd;
        }

        section {
            padding: 100px 50px;
            min-height: 100vh;
        }

        /* HOME */
        #home {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), 
    ('https://ibb.co.com/YBZw6P71');
            background-size: cover;
            background-position: center;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
        
        }

        #home h2 {
            font-size: 48px;
            font-weight: 700;<style>
      background-image: url('https://ibb.co.com/YBZw6P71');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 50px;
}
  
        }

        #home p {
            margin-top: 10px;
            font-size: 20px;
            max-width: 600px;
        }

        /* TENTANG */
        #tentang {
            background: white;
        }

        #tentang h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        #tentang p {
            font-size: 18px;
            line-height: 1.7;
            max-width: 700px;
        }

        /* PROJEK */
        #projek {
            background: #ecf0f1;
        }

        .grid-projek {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }

        .card h3 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        /* CONTACT */
        #contact {
            background: white;
        }

        form {
            max-width: 400px;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            border-radius: 8px;
            border: 1px solid #aaa;
        }

        button {
            margin-top: 15px;
            padding: 12px 20px;
            background: #0a3d62;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background: #3c6382;
        }
    </style>
</head>

<body>
    <header>
        <h1>portofolia Ai sri </h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#tentang">Tentang</a>
            <a href="#projek">Projek</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home">
        <h2>Halo, Saya ai sri apiyani</h2>
        <p>Saya membuat website modern, responsif, dan menarik menggunakan HTML,dan  CSS, yang sederhana</p>
        <img src="https://i.ibb.co/F4VC9mby/Screenshot-20251126-180623.png" alt="Foto Saya" class="foto-lingkaran"></img>
        
    </section>

    <section id="tentang">
        <h2>Tentang Saya</h2>
        <p>Saya Ai sri apyani  seorang  yang suka membuat desain website yang bersih, modern, dan nyaman dilihat. Saya menguasai sedikit dasar coding  HTML, dan CSS, </p>
        <p>
        
Saya memiliki kemampuan dalam menggunakan HTML untuk membangun struktur halaman web yang rapi dan fungsional. Saya dapat membuat elemen-elemen seperti form, tabel, teks, gambar, dan link, serta mengatur susunan konten agar mudah dibaca dan diakses. Keahlian ini menjadi dasar dalam proyek-proyek web yang saya kembangkan.
        </p>
    </section>

    <section id="projek">
        <h2>Projek Saya</h2>
        <div class="grid-projek">
            <div class="card">
                <img src="https://source.unsplash.com/random/400x300?website" alt="projek 1">
                <h3>Website Landing Page</h3>
                <p>Desain landing page modern dan bersih.</p>
            </div>

            <div class="card">
                <img src="https://source.unsplash.com/random/400x300?coding" alt="projek 2">
                <h3>Portfolio Online</h3>
                <p>Website portofolio responsif yang menarik.</p>
            </div>

            <div class="card">
                <img src="https://source.unsplash.com/random/400x300?app" alt="projek 3">
                <h3>Dashboard UI</h3>
                <p>Tampilan dashboard minimalis untuk aplikasi.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Hubungi Saya</h2>
        <form>
            <input type="text" placeholder="nama anda" required />
            <input type="email" placeholder="masukan email" required />
            <textarea rows="5" placeholder="Pesan Anda"></textarea>
            <button>Kirim</button>
        </form>
    </section>
</body>

</html>

