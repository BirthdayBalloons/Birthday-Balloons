<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Birthday Balloons</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" crossorigin="anonymous" />
  <style>
    @keyframes backgroundAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(-45deg, #ffe4ec, #ffccda, #ffd6e8, #ffe4ec);
      background-size: 400% 400%;
      animation: backgroundAnimation 20s ease infinite;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #ff69b4;
      padding: 30px 20px;
      text-align: center;
      color: white;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }
    header h1 {
      font-size: 2.8em;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
      margin: 0;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }
    section {
      padding: 30px;
      margin: 20px auto;
      background: #fff0f5;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      border-left: 6px solid #ff99cc;
      max-width: 900px;
    }
    h2 {
      font-family: 'Georgia', serif;
      font-size: 1.7em;
      color: #d63384;
      border-bottom: 2px solid #ff99cc;
      padding-bottom: 5px;
    }
    ul {
      list-style: none;
      padding-left: 0;
      margin-top: 15px;
    }
    li {
      margin-bottom: 14px;
      padding: 12px 14px;
      background: #ffe6f0;
      border-radius: 10px;
      display: flex;
      align-items: center;
    }
    li i {
      margin-right: 10px;
      color: #ff69b4;
      font-size: 1.2em;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-top: 20px;
    }
    .gallery img {
      max-width: 250px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .paypal-button {
      text-align: center;
      margin-top: 20px;
    }
    .paypal-button iframe {
      max-width: 100%;
    }
    footer {
      background-color: #ff99cc;
      padding: 20px;
      text-align: center;
      font-size: 15px;
      color: #fff;
      font-weight: 500;
      border-top: 4px solid #ff69b4;
    }
    a {
      color: #c2185b;
      font-weight: 500;
    }
    a:hover {
      text-decoration: underline;
    }
    .cta-banner {
      text-align: center;
      background: #ffe0ef;
      color: #ad1457;
      padding: 20px;
      margin: 30px auto;
      font-size: 1.3em;
      border-radius: 10px;
      max-width: 900px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>Birthday Balloons</h1>
    <p>Un espacio profesional para emprendedores con estilo</p>
  </header>

  <div class="cta-banner">
    ¡Apoya el talento local! Encuentra lo que necesitas o haz crecer tu negocio con nosotros.
  </div>

  <section>
    <h2>¿Qué es Birthday Balloons?</h2>
    <p>
      Birthday Balloons es un colectivo profesional que ofrece espacios en renta para que emprendedores puedan exhibir y vender sus productos en un entorno estratégico, con excelente ubicación y diseño atractivo.
    </p>
  </section>

  <section>
    <h2>Productos disponibles</h2>
    <ul>
      <li><i class="fas fa-gem"></i>Joyería</li>
      <li><i class="fas fa-shoe-prints"></i>Calzado</li>
      <li><i class="fas fa-spray-can"></i>Perfumería</li>
      <li><i class="fas fa-paint-brush"></i>Maquillaje</li>
      <li><i class="fas fa-glasses"></i>Lentes y accesorios</li>
      <li><i class="fas fa-mobile-alt"></i>Artículos para celular</li>
      <li><i class="fas fa-wallet"></i>Carteras para dama y caballero</li>
      <li><i class="fas fa-mug-hot"></i>Termos y gadgets</li>
      <li><i class="fas fa-clock"></i>Relojes</li>
      <li><i class="fas fa-cookie-bite"></i>Snacks</li>
      <li><i class="fas fa-capsules"></i>Vitaminas y omegas</li>
      <li><i class="fas fa-star"></i>Y más artículos exclusivos</li>
    </ul>
  </section>

  <section>
    <h2>Galería de productos y espacios</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/250x150?text=Producto+1" alt="Producto 1">
      <img src="https://via.placeholder.com/250x150?text=Producto+2" alt="Producto 2">
      <img src="https://via.placeholder.com/250x150?text=Espacio+1" alt="Espacio 1">
      <img src="https://via.placeholder.com/250x150?text=Decoraci%C3%B3n" alt="Decoración">
    </div>
  </section>

  <section>
    <h2>Beneficios para vendedores</h2>
    <ul>
      <li><i class="fas fa-hand-holding-usd"></i>Espacios accesibles</li>
      <li><i class="fas fa-map-marker-alt"></i>Ubicación estratégica con alto flujo de visitantes</li>
      <li><i class="fas fa-bullhorn"></i>Difusión profesional en redes sociales</li>
      <li><i class="fas fa-users"></i>Red de colaboración entre emprendedores</li>
      <li><i class="fas fa-chart-line"></i>Asesoría personalizada para incrementar ventas</li>
      <li><i class="fas fa-thumbs-up"></i>Atención cercana y profesional</li>
    </ul>
  </section>

  <section>
    <h2>Ubicación</h2>
    <p>
      <i class="fas fa-map-marker-alt"></i>
      Av. 20 de Noviembre #176.
    </p>
  </section>

  <section>
    <h2>Contacto</h2>
    <p>
      <i class="fab fa-whatsapp"></i> WhatsApp: 687 166 1825<br />
      <i class="fab fa-instagram"></i> Instagram: <a href="https://instagram.com/_birthdayballoons" target="_blank">@_birthdayballoons</a><br />
      <i class="fas fa-envelope"></i> Email: <a href="mailto:balloonsbirthday96@gmail.com">balloonsbirthday96@gmail.com</a>
    </p>
  </section>

  <section>
    <h2>Pago en línea</h2>
    <div class="paypal-button">
      <p>Realiza tu pago de manera segura con PayPal:</p>
      <a href="https://www.paypal.com/paypalme/tuusuario" target="_blank">
        <img src="https://www.paypalobjects.com/webstatic/en_US/i/buttons/checkout-logo-large.png" alt="Pagar con PayPal">
      </a>
    </div>
  </section>

  <footer>
    Gracias por confiar en Birthday Balloons. Apoyamos el emprendimiento local con profesionalismo y creatividad.
  </footer>
</body>
</html>
