# IC-CREACIONES
<IC-CREACIONES>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PERSONALIZAMOS TUS IDEAS</title>
  <style>
    /* Reset & Estilos Básicos */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #faf7f5;
      color: #4a4a4a;
      line-height: 1.6;
    }

    /* Encabezado y Navegación */
    header {
      background-color: #ffffff;
      padding: 1.2rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .logo {
      font-size: 1.5rem;
      font-weight: bold;
      color: #b56576;
    }

    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: #6c584c;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #b56576;
    }

    /* Sección Principal (Hero) */
    .hero {
      text-align: center;
      padding: 4rem 1rem;
      background-color: #f2e9e4;
    }

    .hero h1 {
      font-size: 2.5rem;
      color: #6c584c;
      margin-bottom: 0.8rem;
    }

    .hero p {
      font-size: 1.1rem;
      color: #7f6a5d;
      max-width: 600px;
      margin: 0 auto 1.5rem auto;
    }

    .btn-primary {
      background-color: #b56576;
      color: white;
      padding: 0.8rem 1.8rem;
      border: none;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: background 0.3s;
    }

    .btn-primary:hover {
      background-color: #9d4edd;
    }

    /* Sección de Productos / Galería */
    .catalog {
      padding: 3rem 2rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 2rem;
      color: #6c584c;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card-img {
      width: 100%;
      height: 220px;
      object-fit: cover;
      background-color: #e0e0e0;
    }

    .card-body {
      padding: 1.2rem;
    }

    .card-title {
      font-size: 1.2rem;
      color: #4a4a4a;
      margin-bottom: 0.5rem;
    }

    .card-price {
      font-weight: bold;
      color: #b56576;
      font-size: 1.1rem;
      margin-top: 0.5rem;
    }

    /* Formulario de Contacto / Cotización */
    .contact-section {
      background-color: #ffffff;
      padding: 3rem 2rem;
      max-width: 600px;
      margin: 2rem auto;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    }

    .form-group {
      margin-bottom: 1.2rem;
    }

    .form-group label {
      display: block;
      margin-bottom: 0.4rem;
      font-weight: 500;
    }

    .form-group input,
    .form-group textarea,
    .form-group select {
      width: 100%;
      padding: 0.8rem;
      border: 1px solid #ddd;
      border-radius: 8px;
      font-size: 1rem;
    }

    /* Pie de página */
    footer {
      text-align: center;
      padding: 1.5rem;
      background-color: #6c584c;
      color: white;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <!-- Encabezado -->
  <header>
    <div class="logo">🧵 IC CREACIONES</div>
    <nav>
      <a href="#galeria">Galería</a>
      <a href="#pedidos">Pedidos Especiales</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Bordados Únicos & Personalizados</h1>
    <p>Transformamos tus ideas e ilustraciones en piezas de arte textil hechas a mano con dedicación y detalle.</p>
    <a href="#pedidos" class="btn-primary">Solicitar Cotización</a>
  </section>

  <!-- Catálogo / Galería -->
  <section class="catalog" id="galeria">
    <h2 class="section-title">Nuestra Colección</h2>
    <div class="grid">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1584100936595-c0654b55a2e2?w=500&auto=format&fit=crop" alt="Bastidor Bordado Botánico" class="card-img">
        <div class="card-body">
          <h3 class="card-title">Bastidor Botánico</h3>
          <p>Diseño de flores silvestres en tela de lino de 20 cm.</p>
          <div class="card-price">$25.00 USD</div>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1617038260897-41a1f14a8ca0?w=500&auto=format&fit=crop" alt="Bordado Personalizado" class="card-img">
        <div class="card-body">
          <h3 class="card-title">Retrato de Mascota</h3>
          <p>Bordado detallado a mano a partir de la foto de tu mascota.</p>
          <div class="card-price">$40.00 USD</div>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1528458876861-544fd1761a91?w=500&auto=format&fit=crop" alt="Ropa Bordada" class="card-img">
        <div class="card-body">
          <h3 class="card-title">Chaqueta / Casaca Personalizada</h3>
          <p>Intervención textil con bordados florales en espalda o solapa.</p>
          <div class="card-price">$55.00 USD</div>
        </div>
      </div>

    </div>
  </section>

  <!-- Formulario de Pedidos -->
  <section class="contact-section" id="pedidos">
    <h2 class="section-title">Pide tu Bordado Personalizado</h2>
    <form id="contactForm">
      <div class="form-group">
        <label for="name">Nombre completo</label>
        <input type="text" id="name" required placeholder="Ej. Ana García">
      </div>
      <div class="form-group">
        <label for="email">Correo electrónico</label>
        <input type="email" id="email" required placeholder="ana@ejemplo.com">
      </div>
      <div class="form-group">
        <label for="type">Tipo de Bordado</label>
        <select id="type">
          <option>Bastidor decorativo</option>
          <option>Prenda de vestir (Polera/Chaqueta)</option>
          <option>Retrato personalizado</option>
          <option>Otro</option>
        </select>
      </div>
      <div class="form-group">
        <label for="message">Detalles del diseño</label>
        <textarea id="message" rows="4" placeholder="Describe los colores, tamaño o ideas que tienes en mente..."></textarea>
      </div>
      <button type="submit" class="btn-primary" style="width: 100%;">Enviar Mensaje</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 Hilos & Puntadas. Todos los derechos reservados.</p>
  </footer>

  <!-- Lógica JavaScript -->
  <script>
    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault();
      const name = document.getElementById('name').value;
      alert(`¡Gracias, ${name}! Hemos recibido tu solicitud. Te contactaremos pronto para afinar los detalles de tu bordado.`);
      this.reset();
    });
  </script>
</body>
</html>
