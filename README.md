<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Centering the content */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            width: 80%;
            max-width: 1200px;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        .main {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        /* Profile Image Styles */
        .foto img {
            width: 150px; /* Adjust size as needed */
            height: 150px; /* Make it square */
            object-fit: cover;
            border-radius: 50%; /* Makes the image round */
            border: 3px solid #ddd; /* Optional: Add border around image */
        }

        .aboutme {
            margin-top: 20px;
        }

        .aboutme h1 {
            font-size: 2rem;
            margin: 10px 0;
        }

        .aboutme h2 {
            font-size: 1.2rem;
            margin: 5px 0;
        }

        .aboutme p {
            font-size: 1rem;
            color: #555;
            margin: 5px 0;
        }

        .title h2 {
            text-align: center;
            margin-top: 40px;
            font-size: 1.5rem;
            color: #333;
        }

        .content p {
            font-size: 1rem;
            margin: 5px 0;
            color: #666;
        }

        section {
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="main">
            <div class="foto">
                <img src="aul.jpg" alt="Aul" />
            </div>
            <div class="aboutme">
                <h1>Evi Aulia</h1>
                <h2>Tentang saya</h2>
                <p>Mahasiswa program Studi Informatika</p>
                <p>Fakultas Teknik Komputer</p>
                <p>Sekolah Tinggi Teknologi Ilmu Komputer Insan Unggul</p>
                <p>Jabatan Mahasiswa IT</p>
            </div>
        </div>

        <section>
            <div class="title">
                <h2>Kontak</h2>
            </div>
            <div class="content">
                <p>auliavi@IT.ac.id</p> 
                <p>087832119473</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Pendidikan</h2>
            </div>
            <div class="content">
                <p>SDN Serang 2011-2017</p>
                <p>SMPN Cilegon 2017-2020</p>
                <p>SMAN Cilegon 2020-2023 - Jurusan IPA</p>
                <p>STTIKOM Insan Unggul 2023-Sekarang - Program Studi Teknik Informatika</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Pengalaman</h2>
            </div>
            <div class="content">
                <p>Panitia Volunteer Young On Top</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Kemampuan</h2>
            </div>
            <div class="content">
                <p>Bahasa Inggris</p>
                <p>Ms. Office (Word, Excel, Access, PowerPoint)</p>
                <p>Editor</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Penghargaan</h2>
            </div>
            <div class="content">
                <p>Sertifikat siswa terbaik di sekolah SMP 2019</p>
                <p>Sertifikat siswa terbaik SMA 2023</p>
                <p>Mendapat julukan Student Merit Awards 2023</p>
                <p>Sertifikat Beasiswa Roberto Rocca dari Perusahaan 2023</p>
                <p>Sertifikat panitia sekaligus peserta volunteer 2024</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Hobi & Minat</h2>
            </div>
            <div class="content">
                <p>Mendengarkan musik</p>
                <p>Membaca buku/novel</p>
                <p>Menulis</p>
            </div>
        </section>

        <section>
            <div class="title">
                <h2>Organisasi</h2>
            </div>
            <div class="content">
                <p>Aktif dalam organisasi kepramukaan</p>
                <p>Aktif dalam organisasi KIR (Karya Ilmiah Remaja)</p>
                <p>Aktif dalam komunitas Youth Ranger Indonesia</p>
                <p>Aktif dalam komunitas Young On Top</p>
            </div>
        </section>
    </div>
</body>
