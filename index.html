<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Informasi Desa Haidupan</title>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

    <style>
        /* --- CSS GLOBAL --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* --- HALAMAN LOGIN --- */
        #login-page {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                        url('https://pbs.twimg.com/media/B4YaZgoCAAAkkFQ.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .login-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 45px;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            width: 100%;
            max-width: 400px;
            text-align: center;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        .login-card i { color: #2c3e50; font-size: 3.5rem; margin-bottom: 15px; }
        .login-card h2 { color: #2c3e50; margin-bottom: 5px; }
        .login-card p { color: #555; margin-bottom: 30px; font-size: 0.9rem; }

        .input-group { margin-bottom: 20px; text-align: left; }
        .input-group label { display: block; margin-bottom: 8px; font-weight: 600; color: #333; }
        .input-group input {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ccc;
            border-radius: 10px;
            outline: none;
            font-size: 1rem;
        }

        .btn-login {
            background: #2c3e50;
            color: white;
            border: none;
            padding: 14px;
            width: 100%;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
            transition: 0.3s;
        }
        .btn-login:hover { background: #1a252f; transform: translateY(-2px); }

        /* --- DASHBOARD (Hidden by default) --- */
        #main-dashboard {
            display: none;
        }

        .sidebar {
            width: 260px;
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            position: fixed;
            height: 100%;
        }

        .sidebar h2 { text-align: center; margin-bottom: 30px; font-size: 1.2rem; border-bottom: 1px solid #34495e; padding-bottom: 15px; }
        .sidebar ul { list-style: none; }
        .sidebar ul li a {
            color: #bdc3c7;
            text-decoration: none;
            padding: 12px 15px;
            display: flex;
            align-items: center;
            gap: 12px;
            border-radius: 8px;
            margin-bottom: 8px;
            transition: 0.3s;
        }
        .sidebar ul li a:hover, .sidebar ul li a.active { background: #34495e; color: white; }

        .main-content { margin-left: 260px; padding: 30px; }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: white;
            padding: 20px 30px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .card { padding: 25px; border-radius: 15px; color: white; }
        .card-blue { background: linear-gradient(135deg, #3498db, #2980b9); }
        .card-green { background: linear-gradient(135deg, #2ecc71, #27ae60); }
        .card-orange { background: linear-gradient(135deg, #e67e22, #d35400); }

        .card h3 { font-size: 0.9rem; opacity: 0.9; margin-bottom: 10px; }
        .card p { font-size: 2.5rem; font-weight: bold; }

        .form-section { background: white; padding: 35px; border-radius: 15px; box-shadow: 0 10px 25px rgba(0,0,0,0.05); max-width: 650px; }
        .form-section h2 { margin-bottom: 25px; color: #2c3e50; }
        
        .form-group { margin-bottom: 20px; }
        .form-group label { display: block; margin-bottom: 8px; font-weight: 600; }
        
        input[type="number"], select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }

        .btn-submit {
            background: #2c3e50;
            color: white;
            padding: 14px;
            border: none;
            border-radius: 8px;
            width: 100%;
            cursor: pointer;
            font-weight: bold;
        }

        .btn-logout {
            background: #e74c3c;
            color: white;
            border: none;
            padding: 8px 18px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 600;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .sidebar { width: 70px; padding: 10px; }
            .sidebar h2, .sidebar span { display: none; }
            .main-content { margin-left: 70px; }
        }
    </style>
</head>
<body>

    <div id="login-page">
        <div class="login-card">
            <i class="fas fa-landmark"></i>
            <h2>DESA HAIDUPAN</h2>
            <p>SISTEM INFORMASI ADMINISTRASI</p>
            
            <form id="loginForm">
                <div class="input-group">
                    <label>Username</label>
                    <input type="text" id="username" placeholder="admin" required>
                </div>
                <div class="input-group">
                    <label>Password</label>
                    <input type="password" id="password" placeholder="desa123" required>
                </div>
                <button type="submit" class="btn-login">Masuk</button>
            </form>
            <p style="margin-top:15px; font-size:0.8rem; color:#888;">admin / desa123</p>
        </div>
    </div>

    <div id="main-dashboard">
        <nav class="sidebar">
            <h2>S.I. DESA</h2>
            <ul>
                <li><a href="#" class="active"><i class="fas fa-home"></i> <span>Dashboard</span></a></li>
                <li><a href="#"><i class="fas fa-envelope-open"></i> <span>Surat Masuk</span></a></li>
                <li><a href="#"><i class="fas fa-paper-plane"></i> <span>Surat Keluar</span></a></li>
                <li><a href="#"><i class="fas fa-id-card"></i> <span>Data Penduduk</span></a></li>
            </ul>
        </nav>

        <div class="main-content">
            <header>
                <div>
                    <h1>Beranda Utama</h1>
                    <p id="welcome-msg" style="color: #7f8c8d;"></p>
                </div>
                <button class="btn-logout" onclick="logout()">
                    Keluar <i class="fas fa-power-off"></i>
                </button>
            </header>

            <section class="stats-container">
                <div class="card card-blue">
                    <h3>Surat Masuk</h3>
                    <p>32</p>
                </div>
                <div class="card card-green">
                    <h3>Surat Selesai</h3>
                    <p>189</p>
                </div>
                <div class="card card-orange">
                    <h3>Proses</h3>
                    <p id="countProses">12</p>
                </div>
            </section>

            <section class="form-section">
                <h2><i class="fas fa-edit"></i> Buat Surat</h2>
                <form id="formSurat">
                    <div class="form-group">
                        <label>NIK Penduduk</label>
                        <input type="number" id="nikInput" placeholder="16 Digit NIK" required>
                    </div>
                    <div class="form-group">
                        <label>Jenis Surat</label>
                        <select id="jenisSurat">
                            <option>Surat Keterangan Usaha</option>
                            <option>Surat Domisili</option>
                            <option>Surat Kematian</option>
                        </select>
                    </div>
                    <button type="submit" class="btn-submit">Proses Surat</button>
                </form>
            </section>
        </div>
    </div>

    <script>
        // DOM Elements
        const loginPage = document.getElementById('login-page');
        const mainDashboard = document.getElementById('main-dashboard');
        const loginForm = document.getElementById('loginForm');
        const welcomeMsg = document.getElementById('welcome-msg');

        // 1. FUNGSI CEK STATUS LOGIN (Berjalan saat halaman dibuka/refresh)
        function checkLoginStatus() {
            const isLoggedIn = localStorage.getItem('isLoggedIn');
            if (isLoggedIn === 'true') {
                showDashboard();
            } else {
                showLoginPage();
            }
        }

        function showDashboard() {
            loginPage.style.display = 'none';
            mainDashboard.style.display = 'block';
            welcomeMsg.innerText = "Selamat bertugas, Administrator!";
        }

        function showLoginPage() {
            loginPage.style.display = 'flex';
            mainDashboard.style.display = 'none';
        }

        // 2. LOGIKA LOGIN
        loginForm.addEventListener('submit', function(e) {
            e.preventDefault();
            const user = document.getElementById('username').value;
            const pass = document.getElementById('password').value;

            if(user === "admin" && pass === "desa123") {
                // Simpan status login di memori browser
                localStorage.setItem('isLoggedIn', 'true');
                showDashboard();
            } else {
                alert("Username atau Password salah!");
            }
        });

        // 3. LOGIKA LOGOUT
        function logout() {
            if(confirm("Yakin ingin keluar?")) {
                // Hapus status login
                localStorage.removeItem('isLoggedIn');
                showLoginPage();
            }
        }

        // Jalankan pengecekan setiap kali halaman dimuat
        checkLoginStatus();

        // Logika tambahan untuk Form Surat
        document.getElementById('formSurat').addEventListener('submit', function(e) {
            e.preventDefault();
            alert("Surat berhasil diproses!");
            const countProses = document.getElementById('countProses');
            countProses.innerText = parseInt(countProses.innerText) + 1;
            this.reset();
        });
    </script>
</body>
</html>
