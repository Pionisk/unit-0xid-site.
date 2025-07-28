<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>UNIT 0xID - Digital Resistance</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      background: radial-gradient(circle at top left, #111, #000);
      color: #e5e5e5;
      font-family: monospace;
      overflow-x: hidden;
    }
    .glitch {
      font-size: 3rem;
      font-weight: bold;
      position: relative;
      animation: glitch 1s infinite;
      color: #ff0000;
      text-shadow: 0 0 5px #ff0000, 0 0 10px #ff0000;
    }
    @keyframes glitch {
      0% { text-shadow: 2px 0 red, -2px 0 cyan; }
      20% { text-shadow: -2px 0 red, 2px 0 cyan; }
      40% { text-shadow: 2px 0 red, -2px 0 cyan; }
      60% { text-shadow: -2px 0 red, 2px 0 cyan; }
      80% { text-shadow: 2px 0 red, -2px 0 cyan; }
      100% { text-shadow: -2px 0 red, 2px 0 cyan; }
    }
    .terminal {
      background: rgba(0, 0, 0, 0.8);
      border: 1px solid #333;
      padding: 20px;
      border-radius: 8px;
      font-size: 14px;
      color: #00ff00;
      width: 90%;
      max-width: 600px;
      margin-top: 2rem;
    }
    .blink {
      animation: blink 1s step-start 0s infinite;
    }
    @keyframes blink {
      50% { opacity: 0; }
    }
  </style>
</head>
<body class="flex flex-col items-center justify-center min-h-screen p-6 text-center">
  <div class="glitch">UNIT 0xID</div>
  <p class="mt-4 text-gray-400 max-w-xl">
    Perlawanan terhadap sistem keuangan terpusat dimulai di sini.<br>
    Kami menolak Payment ID.<br>
    Kami membangun ekosistem tanpa otoritas pusat.
  </p>

  <div class="terminal mt-6 text-left">
    <p><span class="text-red-500">root@unit0xid:</span>~$ ./revolt.sh</p>
    <p>Memulai koneksi ke jaringan bebas...</p>
    <p>Otoritas: <span class="text-red-500">DITOLAK</span></p>
    <p>Sistem: <span class="text-green-500">TERDESENTRALISASI</span></p>
    <p><span class="blink">█</span></p>
  </div>

  <a href="#" class="mt-10 text-sm text-red-500 hover:underline">JOIN THE RESISTANCE</a>

  <footer class="mt-12 text-gray-600 text-xs">
    <p>&copy; 2025 UNIT 0xID | Freedom Has No ID</p>
  </footer>
</body>
</html>
