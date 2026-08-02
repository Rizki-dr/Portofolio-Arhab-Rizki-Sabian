<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arhab Rizki Sabian — Portfolio</title>
<style>
  *, *::before, *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    background-color: #09090b;
    color: #f4f4f5;
    line-height: 1.6;
    padding-bottom: 50px;
  }

  .container {
    max-width: 960px;
    margin: 0 auto;
    padding: 0 24px;
  }

  /* Navbar Header */
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 28px 0;
    border-bottom: 1px solid #18181b;
  }

  .brand {
    font-size: 1.1rem;
    font-weight: 700;
    letter-spacing: -0.5px;
    color: #ffffff;
  }

  .brand span {
    color: #71717a;
    font-weight: 400;
    font-size: 0.9rem;
  }

  .status-badge {
    display: flex;
    align-items: center;
    font-size: 0.85rem;
    color: #10b981;
    font-weight: 500;
  }

  .status-dot {
    width: 8px;
    height: 8px;
    background-color: #10b981;
    border-radius: 50%;
    margin-right: 8px;
    box-shadow: 0 0 8px #10b981;
  }

  /* Hero Section */
  .hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    padding: 60px 0 40px 0;
  }

  .hero-content {
    flex: 1;
  }

  .tag-pill {
    display: inline-block;
    padding: 4px 12px;
    background-color: #18181b;
    color: #a1a1aa;
    border: 1px solid #27272a;
    border-radius: 20px;
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: 0.5px;
    margin-bottom: 16px;
    text-transform: uppercase;
  }

  .hero-title {
    font-size: 2.5rem;
    font-weight: 800;
    line-height: 1.15;
    letter-spacing: -1px;
    color: #ffffff;
    margin-bottom: 16px;
  }

  .hero-title .highlight {
    color: #a1a1aa;
  }

  .hero-subtitle {
    font-size: 1rem;
    color: #a1a1aa;
    margin-bottom: 28px;
    max-width: 520px;
  }

  /* Buttons */
  .btn-group {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
  }

  .btn {
    padding: 10px 20px;
    border-radius: 8px;
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none;
    transition: all 0.2s ease;
  }

  .btn-primary {
    background-color: #ffffff;
    color: #09090b;
  }

  .btn-primary:hover {
    background-color: #e4e4e7;
  }

  .btn-secondary {
    background-color: #18181b;
    color: #f4f4f5;
    border: 1px solid #27272a;
  }

  .btn-secondary:hover {
    background-color: #27272a;
  }

  /* Photo Frame */
  .hero-photo-wrapper {
    width: 220px;
    height: 260px;
    background-color: #121215;
    border: 1px dashed #3f3f46;
    border-radius: 16px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 20px;
  }

  /* Section Styling */
  .section {
    margin-top: 40px;
  }

  .section-header {
    margin-bottom: 20px;
  }

  .section-title {
    font-size: 1.25rem;
    font-weight: 700;
    color: #ffffff;
    letter-spacing: -0.3px;
  }

  .section-desc {
    font-size: 0.875rem;
    color: #71717a;
  }

  /* About Card */
  .about-card {
    background-color: #121215;
    border: 1px solid #1f1f23;
    border-radius: 14px;
    padding: 24px;
  }

  .about-card p {
    color: #a1a1aa;
    font-size: 0.95rem;
    line-height: 1.7;
    margin-bottom: 12px;
  }

  .about-card p:last-child {
    margin-bottom: 0;
  }

  /* Grid Cards */
  .cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 16px;
  }

  .card {
    background-color: #121215;
    border: 1px solid #1f1f23;
    border-radius: 14px;
    padding: 20px;
    transition: border-color 0.2s ease;
  }

  .card:hover {
    border-color: #3f3f46;
  }

  .card-tag {
    font-family: monospace;
    font-size: 0.75rem;
    color: #38bdf8;
    margin-bottom: 8px;
    text-transform: uppercase;
  }

  .card-title {
    font-size: 1.1rem;
    font-weight: 700;
    color: #ffffff;
    margin-bottom: 8px;
  }

  .card-desc {
    font-size: 0.875rem;
    color: #71717a;
  }

  /* Footer */
  .footer {
    margin-top: 60px;
    padding-top: 24px;
    border-top: 1px solid #18181b;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 16px;
    font-size: 0.85rem;
    color: #71717a;
  }

  .footer strong {
    color: #ffffff;
  }
</style>
</head>
<body>

<div class="container">
  <!-- Top Navigation -->
  <header class="navbar">
    <div class="brand">ARHAB RIZKI SABIAN <span>/ PORTFOLIO</span></div>
    <div class="status-badge">
      <span class="status-dot"></span> Available for Hiring & Projects
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <div class="tag-pill">E-COMMERCE & CREATIVE CONTENT</div>
      <h1 class="hero-title">E-Commerce Specialist & <span class="highlight">Visual Creator.</span></h1>
      <p class="hero-subtitle">
        Praktisi operasional e-commerce, pengelola toko online, serta pembuat konten visual yang terbiasa menangani operasional administratif digital dan pemasaran media sosial.
      </p>
      <div class="btn-group">
        <a href="https://wa.link/u0zwmr" target="_blank" class="btn btn-primary">💬 WhatsApp Me</a>
        <a href="mailto:arhabrizkisabian12@gmail.com" class="btn btn-secondary">✉️ Email</a>
        <a href="https://id.linkedin.com/in/arhab-rizki-sabian-987406363" target="_blank" class="btn btn-secondary">🔗 LinkedIn</a>
      </div>
    </div>
    
    <div class="hero-photo-wrapper">
      <div style="font-size: 2rem; margin-bottom: 8px;">👤</div>
      <div style="font-weight: 600; font-size: 0.85rem; color: #ffffff;">FOTO PROFIL</div>
      <div style="font-size: 0.75rem; color: #71717a; margin-top: 4px;">Ganti elemen ini dengan tag &lt;img&gt;</div>
    </div>
  </section>

  <!-- About Section -->
  <section class="section">
    <div class="section-header">
      <h2 class="section-title">About Me</h2>
      <p class="section-desc">Latar belakang, pengalaman operasional, dan fokus kerja saat ini.</p>
    </div>
    <div class="about-card">
      <p>
        Saya adalah seorang praktisi yang berpengalaman dalam pengelolaan operasional e-commerce dan penciptaan konten visual digital. Memiliki rekam jejak dalam mengelola toko online di berbagai marketplace (seperti Shopee, Tokopedia, dan Lazada), saya terbiasa menangani penataan dekorasi toko, manajemen katalog produk, hingga strategi pemasaran afiliasi.
      </p>
      <p>
        Selain menguasai operasional marketplace dan administrasi perkantoran (Microsoft Office), saya juga aktif dalam dokumentasi visual melalui fotografi dan videography sederhana. Dikenal teliti, adaptif, dan mandiri, saya selalu berfokus untuk memberikan hasil kerja yang rapi, efisien, dan mendukung pertumbuhan bisnis digital.
      </p>
    </div>
  </section>

  <!-- Capabilities Section -->
  <section class="section">
    <div class="section-header">
      <h2 class="section-title">Core Capabilities & Skills</h2>
      <p class="section-desc">Keahlian operasional dan kreatif yang dikuasai.</p>
    </div>
    <div class="cards-grid">
      <div class="card">
        <div class="card-tag">// E-COMMERCE</div>
        <h3 class="card-title">Marketplace & Store Operations</h3>
        <p class="card-desc">
          Pengelolaan toko online (Shopee, Tokopedia, Lazada), dekorasi toko, optimasi deskripsi produk, penataan katalog, dan layanan pelanggan.
        </p>
      </div>

      <div class="card">
        <div class="card-tag">// CREATIVE VISUAL</div>
        <h3 class="card-title">Basic Photography & Videography</h3>
        <p class="card-desc">
          Pengambilan foto/video produk, dokumentasi visual sederhana, pengeditan dasar untuk kebutuhan konten media sosial dan promosi marketplace.
        </p>
      </div>

      <div class="card">
        <div class="card-tag">// ADMINISTRATION</div>
        <h3 class="card-title">Microsoft Office & Admin Skills</h3>
        <p class="card-desc">
          Pengolahan data dan laporan penjualan menggunakan Microsoft Excel, penyusunan dokumen kerja dengan Word, serta pembuatan presentasi di PowerPoint.
        </p>
      </div>

      <div class="card">
        <div class="card-tag">// DIGITAL MARKETING</div>
        <h3 class="card-title">Affiliate & Content Creation</h3>
        <p class="card-desc">
          Pengelolaan Shopee Affiliate Program, riset tren produk, penyusunan materi promosi visual, dan strategi konten berorientasi penjualan.
        </p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div>
      <strong>Arhab Rizki Sabian</strong> &bull; E-Commerce & Visual Specialist
    </div>
    <div>
      © 2026 Arhab Rizki Sabian. Minimalist Style.
    </div>
  </footer>
</div>

</body>
</html>
