body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
  transition: background-color 0.3s, color 0.3s;
}

.dark-mode {
  background-color: #1e1e1e;
  color: #f4f4f4;
}

header {
  padding: 2rem;
  text-align: center;
  background-color: #007acc;
  color: white;
}

header .toggle-container {
  position: absolute;
  top: 1rem;
  right: 1rem;
}

section {
  padding: 2rem;
}

h2 {
  border-bottom: 2px solid #007acc;
  padding-bottom: 0.5rem;
}

ul {
  list-style-type: square;
  margin-left: 1.5rem;
}

.experience-item {
  margin-bottom: 1.5rem;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: white;
}

.switch {
  position: relative;
  display: inline-block;
  width: 40px;
  height: 20px;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  transition: 0.4s;
  border-radius: 20px;
}

.slider:before {
  position: absolute;
  content: "";
  height: 14px;
  width: 14px;
  left: 3px;
  bottom: 3px;
  background-color: white;
  transition: 0.4s;
  border-radius: 50%;
}

input:checked + .slider {
  background-color: #007acc;
}

input:checked + .slider:before {
  transform: translateX(20px);
}

a {
  color: #007acc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

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