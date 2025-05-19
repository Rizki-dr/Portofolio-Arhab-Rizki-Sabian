<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portofolio Arhab Rizki Sabian</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="toggle-container">
      <label class="switch">
        <input type="checkbox" id="modeToggle" />
        <span class="slider"></span>
      </label>
    </div>
    <h1>Arhab Rizki Sabian</h1>
    <p>Teknisi jaringan yang antusias, teliti, dan siap menghadapi tantangan teknologi masa kini.</p>
  </header>

  <section id="skills">
    <h2>Keahlian</h2>
    <ul>
      <li>Troubleshooting Jaringan</li>
      <li>Konfigurasi Infrastruktur Jaringan</li>
      <li>Cisco Packet Tracer</li>
      <li>Microsoft Office</li>
    </ul>
  </section>

  <section id="experience">
    <h2>Pengalaman</h2>
    <div class="experience-item">
      <h3>PKL di Percetakan Tugu</h3>
      <p>Desember 2023 - Februari 2024</p>
      <p>Staf produksi dan pengumpulan data. Terlibat dalam proses cetak serta membantu dokumentasi dan pengolahan data internal perusahaan.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Kontak</h2>
    <p>Email: arhabrizkisabian12@gmail.com</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/arhab-rizki-sabian-4a58a3311" target="_blank">Arhab Rizki Sabian</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Arhab Rizki Sabian</p>
  </footer>

  <script>
    const toggle = document.getElementById('modeToggle');
    toggle.addEventListener('change', () => {
      document.body.classList.toggle('dark-mode');
    });
  </script>
</body>
</html>