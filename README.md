<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mago Piero - Ilusionista Profesional</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }
    body { scroll-behavior: smooth; color: #333; }

    header {
      height: 100vh;
      background: linear-gradient(to bottom, rgba(0,0,0,0.6), rgba(0,0,0,0.8)), 
                  url('https://picsum.photos/1200/800?magic') center/cover no-repeat;
      color: white; 
      display: flex; 
      flex-direction: column; 
      justify-content: center; 
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    header h1 { font-size: 3rem; margin-bottom: 20px; }
    header p { font-size: 1.2rem; margin-bottom: 30px; }
    header a {
      background: #25D366; 
      color: white; 
      padding: 15px 30px; 
      border-radius: 50px; 
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    header a:hover { background: #1ebe5c; }

    section { padding: 60px 20px; max-width: 900px; margin: auto; }
    section h2 { text-align: center; font-size: 2rem; margin-bottom: 30px; }

    .about p { font-size: 1.1rem; line-height: 1.6; text-align: center; }

    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .gallery img { width: 100%; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.2); }

    footer {
      background: #111; color: white; text-align: center; padding: 30px 20px;
    }
    footer p { margin: 10px 0; }

    /* Botón flotante de WhatsApp */
    .whatsapp-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
      text-decoration: none;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      z-index: 100;
    }
  </style>
</head>
<body>

  <!-- Hero -->
  <header>
    <h1>Mago Piero</h1>
    <p>Ilusionista profesional con 15 años de experiencia creando momentos inolvidables.</p>
    <a href="https://wa.me/51916531576?text=Hola%20Mago%20Piero,%20quiero%20más%20información%20sobre%20tu%20show!" target="_blank">
      Contáctame por WhatsApp
    </a>
  </header>

  <!-- Sobre mí -->
  <section class="about" id="about">
    <h2>¿Quién soy?</h2>
    <p>
      Soy Mago Piero, especialista en magia e ilusión para todo tipo de eventos. 
      Mi pasión es sorprender y emocionar al público, creando experiencias mágicas que perduren en la memoria.
    </p>
  </section>

  <!-- Portafolio -->
  <section class="portfolio" id="portfolio">
    <h2>Momentos mágicos</h2>
    <div class="gallery">
      <img src="https://picsum.photos/400/300?1" alt="Show de magia 1">
      <img src="https://picsum.photos/400/300?2" alt="Show de magia 2">
      <img src="https://picsum.photos/400/300?3" alt="Show de magia 3">
    </div>
  </section>

  <!-- Contacto -->
  <footer>
    <h2>Contacto</h2>
    <p>📞 WhatsApp: +51 916 531 576</p>
    <p>📧 Email: ilusionistapiero@gmail.com</p>
    <p>📷 Instagram: @mago_piero</p>
    <p>📘 Facebook: <a href="https://www.facebook.com/MagoPiero/" target="_blank" style="color:#25D366">MagoPiero</a></p>
    <p>© 2025 Mago Piero - Todos los derechos reservados</p>
  </footer>

  <!-- Botón flotante WhatsApp -->
  <a href="https://wa.me/51916531576?text=Hola%20Mago%20Piero,%20quiero%20más%20información%20sobre%20tu%20show!" class="whatsapp-float" target="_blank">
    ☎
  </a>

</body>
</html>