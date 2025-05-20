<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Servicios Eléctricos</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d1117;
      color: #fff;
    }

    header {
      text-align: center;
      padding: 60px 20px 30px;
      background-color: #161b22;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      color: #8b949e;
    }

    .galeria {
      display: flex;
      overflow-x: auto;
      gap: 20px;
      padding: 20px;
      scroll-behavior: smooth;
    }

    .galeria img {
      height: 200px;
      border-radius: 12px;
      transition: transform 0.3s ease;
      animation: flotar 4s ease-in-out infinite;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }

    @keyframes flotar {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .servicios {
      padding: 40px 20px;
      background-color: #21262d;
    }

    .servicio {
      background-color: #30363d;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    .servicio h3 {
      margin-bottom: 10px;
      color: #58a6ff;
    }

    .servicio p {
      color: #c9d1d9;
    }

    footer {
      text-align: center;
      background-color: #161b22;
      padding: 20px;
      font-size: 0.9em;
      color: #8b949e;
    }
  </style>
</head>
<body>

  <header>
    <h1>ElectroPower</h1>
    <p>Soluciones eléctricas modernas y seguras</p>
  </header>

  <!-- Galería con imágenes animadas -->
  <div class="galeria">
    <img src="https://cdn.pixabay.com/photo/2018/04/18/18/56/electricity-3330244_960_720.jpg" alt="Electricidad 1">
    <img src="https://cdn.pixabay.com/photo/2017/08/06/06/59/electric-2598146_960_720.jpg" alt="Electricidad 2">
    <img src="https://cdn.pixabay.com/photo/2018/05/11/08/31/electric-3389289_960_720.jpg" alt="Electricidad 3">
    <img src="https://cdn.pixabay.com/photo/2017/07/12/18/39/electrician-2494532_960_720.jpg" alt="Electricidad 4">
  </div>

  <!-- Sección de servicios -->
  <div class="servicios">
    <div class="servicio">
      <h3>Instalaciones Eléctricas</h3>
      <p>Diseño e instalación segura de sistemas eléctricos en hogares y empresas.</p>
    </div>
    <div class="servicio">
      <h3>Mantenimiento y Reparación</h3>
      <p>Revisión, diagnóstico y reparación de instalaciones eléctricas.</p>
    </div>
    <div class="servicio">
      <h3>Paneles Solares</h3>
      <p>Instalación de paneles solares para ahorro energético y cuidado del ambiente.</p>
    </div>
  </div>

  <footer>
    © 2025 ElectroPower. Todos los derechos reservados.
  </footer>

</body>
</html>
