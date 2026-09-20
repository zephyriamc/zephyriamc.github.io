<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Zephyria Staff — Panel Oficial</title>
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
  
  <!-- CSS del Tema Oscuro Elegante (Docsify Themeable Simple Dark) -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify-themeable@0/dist/css/theme-simple-dark.css">

  <style>
    /* Estilos personalizados para Zephyria Network */
    :root {
      --theme-color: #5865F2; /* Púrpura/Azul estilo Discord */
      --base-background-color: #0b0e14;
      --sidebar-background: #11151c;
      --sidebar-width: 260px;
      --code-font-family: 'JetBrains Mono', Consolas, monospace;
      --content-max-width: 900px;
    }

    /* Navbar superior con estilo de botones flotantes */
    .app-nav {
      position: fixed;
      top: 15px;
      right: 25px;
      margin: 0;
      z-index: 100;
    }

    .app-nav ul {
      display: flex;
      gap: 10px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    .app-nav a {
      background: #1a1f2c;
      border: 1px solid #2d3548;
      color: #e2e8f0 !important;
      padding: 8px 18px;
      border-radius: 8px;
      font-weight: 600;
      font-size: 0.9rem;
      text-decoration: none !important;
      transition: all 0.2s ease-in-out;
    }

    .app-nav a:hover {
      background: var(--theme-color);
      border-color: var(--theme-color);
      color: #ffffff !important;
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(88, 101, 242, 0.3);
    }

    /* Cajas y Tarjetas de la Portada */
    .grid-cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: #141822;
      border: 1px solid #232a3b;
      border-radius: 12px;
      padding: 22px;
      transition: all 0.25s ease;
    }

    .card:hover {
      border-color: var(--theme-color);
      transform: translateY(-4px);
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
    }

    .card h3 {
      margin-top: 0;
      color: #ffffff;
      font-size: 1.15rem;
    }

    .card p {
      color: #94a3b8;
      font-size: 0.9rem;
      line-height: 1.5;
    }

    .card a {
      display: inline-block;
      margin-top: 10px;
      color: var(--theme-color);
      font-weight: 600;
      text-decoration: none;
    }

    .card a:hover {
      text-decoration: underline;
    }

    /* Tablas oscuras estilizadas */
    table {
      border-collapse: collapse;
      width: 100%;
      background: #141822;
      border-radius: 8px;
      overflow: hidden;
    }

    th {
      background: #1e2433 !important;
      color: #ffffff !important;
    }

    td, th {
      border: 1px solid #232a3b !important;
      padding: 12px 16px !important;
    }
  </style>
</head>
<body>
  <div id="app">Cargando panel de Zephyria...</div>

  <script>
    window.$docsify = {
      name: '<b style="color:#5865F2">ZEPHYRIA</b> STAFF',
      repo: '',
      loadNavbar: true,  /* Carga los botones superiores desde _navbar.md */
      loadSidebar: false, /* Estilo portal sin barra lateral estorbosa */
      auto2top: true,
      search: {
        placeholder: 'Buscar sanción, comando o regla...',
        noData: 'No se encontraron resultados'
      }
    }
  </script>
  
  <!-- Scripts esenciales -->
  <script src="https://cdn.jsdelivr.net/npm/docsify@4/lib/docsify.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/docsify-themeable@0/dist/js/docsify-themeable.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
</body>
</html>
