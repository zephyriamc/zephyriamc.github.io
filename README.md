<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Zephyria Network — Wiki & Staff</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
  
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify-themeable@0/dist/css/theme-simple-dark.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --base-font-family: 'Plus Jakarta Sans', -apple-system, sans-serif;
      --theme-color: #38bdf8;
      --base-background-color: #0b0f19;
      --content-max-width: 950px;
    }

    body {
      background-color: #0b0f19 !important;
      font-family: var(--base-font-family);
    }

    /* Ocultar la barra lateral por completo */
    .sidebar { display: none !important; }
    .sidebar-toggle { display: none !important; }
    .content { padding-left: 0 !important; left: 0 !important; position: relative !important; width: 100% !important; }
    
    /* Centrar contenido */
    .markdown-section {
      max-width: var(--content-max-width) !important;
      margin: 0 auto !important;
      padding: 80px 30px 40px 30px !important;
    }

    /* Navbar superior */
    .app-nav {
      position: fixed;
      top: 20px;
      right: 40px;
      margin: 0;
      z-index: 100;
    }

    .app-nav ul {
      display: flex;
      gap: 12px;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .app-nav a {
      background: rgba(255, 255, 255, 0.04);
      border: 1px solid rgba(255, 255, 255, 0.08);
      color: #94a3b8 !important;
      padding: 8px 18px;
      border-radius: 20px;
      font-weight: 600;
      font-size: 0.88rem;
      text-decoration: none !important;
      transition: all 0.2s ease;
    }

    .app-nav a:hover {
      background: rgba(56, 189, 248, 0.12);
      border-color: #38bdf8;
      color: #38bdf8 !important;
    }

    /* Badges y Textos Hero */
    .badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: rgba(56, 189, 248, 0.1);
      border: 1px solid rgba(56, 189, 248, 0.25);
      color: #38bdf8;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 0.75rem;
      font-weight: 800;
      letter-spacing: 0.5px;
      text-transform: uppercase;
      margin-bottom: 20px;
    }

    .hero-title {
      font-size: 3.2rem !important;
      font-weight: 800 !important;
      color: #ffffff !important;
      margin: 0 0 10px 0 !important;
      letter-spacing: -1px;
      line-height: 1.15 !important;
    }

    .hero-title span {
      color: #38bdf8;
      text-shadow: 0 0 35px rgba(56, 189, 248, 0.45);
    }

    .hero-subtitle {
      color: #64748b !important;
      font-size: 1.05rem !important;
      max-width: 650px;
      margin-bottom: 40px !important;
      line-height: 1.6;
    }

    .section-tag {
      color: #38bdf8;
      font-size: 0.75rem;
      font-weight: 800;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      margin-bottom: 6px;
    }

    .section-title {
      font-size: 1.8rem !important;
      font-weight: 800 !important;
      color: #ffffff !important;
      margin-top: 0 !important;
      margin-bottom: 25px !important;
      border: none !important;
    }

    /* Grid de Tarjetas */
    .grid-cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 15px;
    }

    .card {
      background: #101625;
      border: 1px solid #1a2336;
      border-radius: 16px;
      padding: 24px;
      display: flex;
      gap: 18px;
      align-items: flex-start;
      transition: all 0.25s ease;
    }

    .card:hover {
      border-color: rgba(56, 189, 248, 0.4);
      background: #131a2c;
      transform: translateY(-2px);
    }

    .card-icon {
      font-size: 1.8rem;
      line-height: 1;
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.05);
      padding: 12px;
      border-radius: 12px;
    }

    .card-content h3 {
      margin: 0 0 8px 0 !important;
      color: #ffffff !important;
      font-size: 1.15rem !important;
      font-weight: 700 !important;
    }

    .card-content p {
      color: #64748b !important;
      font-size: 0.88rem !important;
      line-height: 1.5 !important;
      margin: 0 0 14px 0 !important;
    }

    .card-link {
      color: #38bdf8 !important;
      font-weight: 700;
      font-size: 0.88rem;
      text-decoration: none !important;
    }

    .card-disabled {
      color: #334155 !important;
      font-size: 0.85rem;
      font-weight: 600;
    }

    /* Tablas estilo pro */
    table {
      background: #101625 !important;
      border-radius: 12px !important;
      border-collapse: collapse !important;
      width: 100% !important;
      margin: 25px 0 !important;
      overflow: hidden;
    }

    th {
      background: #161e30 !important;
      color: #38bdf8 !important;
      font-weight: 700 !important;
      text-align: left !important;
    }

    td, th {
      border: 1px solid #1a2336 !important;
      padding: 14px 18px !important;
    }
  </style>
</head>
<body>
  <div id="app">Cargando Wiki...</div>

  <script>
    window.$docsify = {
      name: '<b style="color:#38bdf8">ZEPHYRIA</b>',
      loadNavbar: true,
      loadSidebar: false,
      homepage: 'README.md',
      auto2top: true
    }
  </script>
  
  <script src="https://cdn.jsdelivr.net/npm/docsify@4/lib/docsify.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/docsify-themeable@0/dist/js/docsify-themeable.min.js"></script>
</body>
</html>
