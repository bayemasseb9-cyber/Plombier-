<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Plomberie Express - Services 24/7</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: Arial, sans-serif; }
    body { background-color: #f5f5f5; color: #333; line-height: 1.6; }
    header { background-color: #0077cc; color: white; padding: 30px 20px; text-align: center; }
    header h1 { margin-bottom: 10px; font-size: 2em; }
    header p { font-size: 1.2em; }

    .container { max-width: 1200px; margin: 30px auto; padding: 0 20px; }
    .services { display: flex; flex-wrap: wrap; gap: 25px; justify-content: center; }

    .service-card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      width: 300px;
      text-align: center;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }
    .service-card:hover {
      transform: translateY(-10px) scale(1.05);
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }
    .service-card img { width: 100%; height: 200px; object-fit: cover; }

    .service-card h3 { padding: 15px 0 5px 0; font-size: 1.3em; color: #0077cc; }
    .service-card p { padding: 0 15px 20px 15px; font-size: 1em; }

    .contact-buttons { display: flex; justify-content: center; gap: 20px; margin: 30px 0; flex-wrap: wrap; }
    .contact-buttons a {
      display: inline-block;
      padding: 12px 25px;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .contact-buttons a:hover { transform: scale(1.05); box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
    .call-btn { background-color: #28a745; }
    .whatsapp-btn { background-color: #25d366; }

    footer { text-align: center; padding: 20px; background-color: #0077cc; color: white; margin-top: 40px; font-size: 0.95em; }

    @media(max-width: 960px) {
      .services { flex-direction: column; align-items: center; }
      .service-card { width: 90%; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Plomberie Express</h1>
    <p>Disponible 24/7 pour toutes vos urgences plomberie !</p>
  </header>

  <div class="container">
    <div class="services">
      <!-- Installation -->
      <div class="service-card">
        <img src="image.jpg" alt="Installation plomberie">
        <h3>Installation</h3>
        <p>Vous cherchez un installateur plombier fiable ? Contactez-moi dès maintenant !</p>
      </div>

      <!-- Débouchage -->
      <div class="service-card">
        <img src="image 1.jpg" alt="Débouchage plomberie">
        <h3>Débouchage</h3>
        <p>Canalisation bouchée ? Je débouche vos tuyaux rapidement et efficacement.</p>
      </div>

      <!-- Dépannage -->
      <div class="service-card">
        <img src="image 2.jpg" alt="Dépannage plomberie">
        <h3>Dépannage</h3>
        <p>Besoin d’un dépannage urgent ? Contactez-moi pour intervenir immédiatement.</p>
      </div>
    </div>

    <!-- Contact -->
    <div class="contact-buttons">
      <a class="call-btn" href="tel:+221782778704">Appeler</a>
      <a class="whatsapp-btn" href="https://wa.me/221782778704" target="_blank">WhatsApp</a>
    </div>
  </div>

  <footer>
    &copy; 2026 Plomberie Express. Disponible 24/7 | +221 782 778 704
  </footer>

</body>
</html>
