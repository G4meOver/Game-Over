<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Top Up Games</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #000;
      color: #fff;
      text-align: center;
    }
    header {
      background-color: #111;
      padding: 20px;
    }
    header img {
      height: 100px;
    }
    h1 {
      margin-top: 0;
    }
    .content {
      padding: 40px 20px;
    }
    .topup-form {
      max-width: 400px;
      margin: 0 auto;
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
    }
    button {
      background-color: red;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    .history, .admin-panel {
      max-width: 600px;
      margin: 40px auto;
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      text-align: left;
    }
    footer {
      margin-top: 40px;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Game Over Logo">
    <h1>Top Up Game Favoritmu</h1>
  </header>

  <div class="content">
    <div class="topup-form">
      <h2>Form Top Up</h2>
      <input type="text" placeholder="Masukkan ID Pemain">
      <select>
        <option>Pilih Game</option>
        <option>Mobile Legends</option>
        <option>Free Fire</option>
        <option>PUBG</option>
        <option>Genshin Impact</option>
      </select>
      <select>
        <option>Pilih Nominal</option>
        <option>50 Diamonds</option>
        <option>100 Diamonds</option>
        <option>200 Diamonds</option>
      </select>
      <select>
        <option>Metode Pembayaran</option>
        <option>OVO</option>
        <option>DANA</option>
        <option>Gopay</option>
        <option>Transfer Bank</option>
      </select>
      <button>Top Up Sekarang</button>
    </div>

    <div class="history">
      <h2>Riwayat Transaksi</h2>
      <ul>
        <li>12/05/2025 - Mobile Legends - 100 Diamonds - OVO</li>
        <li>10/05/2025 - Free Fire - 50 Diamonds - DANA</li>
      </ul>
    </div>

    <div class="admin-panel">
      <h2>Panel Admin</h2>
      <p>Total Transaksi Hari Ini: 5</p>
      <p>Jumlah Pengguna Terdaftar: 120</p>
      <p>Status Server: <strong style="color:lime;">Online</strong></p>
    </div>
  </div>

  <footer>
    &copy; 2025 Top Up Game. All rights reserved.
  </footer>
</body>
</html>
