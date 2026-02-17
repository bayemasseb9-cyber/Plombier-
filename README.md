<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Plombier à Mbour 24/7 | Réservation en ligne - Plomberie Express</title>
<meta name="description" content="Plombier professionnel à Mbour disponible 24/7. Réservez votre dépannage, débouchage ou installation sanitaire en ligne. Intervention rapide à Mbour.">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins', sans-serif;
}

body{
  background:#f4f6f8;
  color:#333;
}

header{
  background:linear-gradient(135deg,#0077cc,#00c6ff);
  color:white;
  text-align:center;
  padding:40px 20px;
}

.logo{
  width:150px;
  margin-bottom:15px;
}

header h1{
  font-size:2em;
  margin-bottom:10px;
}

.btn{
  display:inline-block;
  padding:12px 25px;
  margin:10px 5px;
  border-radius:30px;
  text-decoration:none;
  color:white;
  font-weight:600;
  transition:0.3s;
}

.call{ background:#28a745; }
.whatsapp{ background:#25d366; }

.btn:hover{
  transform:scale(1.05);
}

.section{
  padding:60px 20px;
  max-width:1100px;
  margin:auto;
}

.section h2{
  text-align:center;
  margin-bottom:30px;
  color:#0077cc;
}

.services{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
}

.card{
  background:white;
  padding:25px;
  border-radius:15px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
  transition:0.3s;
  text-align:center;
}

.card img{
  width:100%;
  border-radius:12px;
  margin-bottom:15px;
}

.card:hover{
  transform:translateY(-8px);
}

/* FORMULAIRE */
form{
  background:white;
  padding:30px;
  border-radius:15px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

form input, form select, form textarea{
  width:100%;
  padding:12px;
  margin-bottom:15px;
  border-radius:8px;
  border:1px solid #ccc;
}

form button{
  background:#0077cc;
  color:white;
  padding:12px;
  border:none;
  border-radius:30px;
  cursor:pointer;
  font-weight:600;
}

form button:hover{
  background:#005fa3;
}

#confirmation{
  display:none;
  text-align:center;
  color:green;
  margin-top:15px;
  font-weight:600;
}

iframe{
  width:100%;
  height:300px;
  border:none;
  border-radius:15px;
}

footer{
  background:#0077cc;
  color:white;
  text-align:center;
  padding:20px;
  margin-top:40px;
}

/* FLOAT WHATSAPP */
.float{
  position:fixed;
  bottom:20px;
  right:20px;
  width:60px;
  height:60px;
  background:#25d366;
  border-radius:50%;
  display:flex;
  justify-content:center;
  align-items:center;
  font-size:26px;
  color:white;
  text-decoration:none;
  box-shadow:0 5px 15px rgba(0,0,0,0.3);
}
</style>
</head>

<body>

<header>
  <img src="https://i.ibb.co/LzB5dLjm/poh.png" alt="Logo Plombier Mbour" class="logo">
  <h1>Plombier Professionnel à Mbour</h1>
  <p>Disponible 24/7 • Intervention rapide</p>
  <a href="tel:+221782778704" class="btn call">📞 Appeler</a>
  <a href="https://wa.me/221782778704" class="btn whatsapp">WhatsApp</a>
</header>

<section class="section">
  <h2>Nos Services</h2>
  <div class="services">
    <div class="card">
      <img src="https://i.ibb.co/mF0NJTQy/yop.png" alt="Installation Sanitaire">
      <h3>Installation Sanitaire</h3>
      <p>Installation complète WC, lavabos et équipements modernes.</p>
    </div>
    <div class="card">
      <img src="https://i.ibb.co/7JxwmBp0/kop.png" alt="Débouchage">
      <h3>Débouchage</h3>
      <p>Canalisations et WC débouchés rapidement à Mbour.</p>
    </div>
    <div class="card">
      <img src="https://i.ibb.co/7JDqMJV1/uop.png" alt="Dépannage Urgent">
      <h3>Dépannage Urgent</h3>
      <p>Réparation fuite d’eau et intervention urgente 24h/24.</p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Réserver une intervention</h2>
  <form id="reservationForm" action="https://formsubmit.co/bayemasseba20@gmail.com" method="POST">
    <input type="text" name="Nom" placeholder="Votre nom" required>
    <input type="tel" name="Téléphone" placeholder="Votre numéro" required>
    <select name="Service" required>
      <option value="">Choisir un service</option>
      <option>Installation</option>
      <option>Débouchage</option>
      <option>Dépannage urgent</option>
    </select>
    <textarea name="Message" placeholder="Décrivez votre problème" rows="4"></textarea>
    <input type="hidden" name="_captcha" value="false">
    <button type="submit">Réserver maintenant</button>
  </form>
  <div id="confirmation">Merci ! Votre réservation a été envoyée. Nous vous contacterons bientôt.</div>
</section>

<section class="section">
  <h2>Zone d’intervention</h2>
  <iframe src="https://www.google.com/maps?q=Mbour,+Senegal&output=embed" loading="lazy"></iframe>
</section>

<footer>
  © 2026 Plomberie Express Mbour | +221 78 277 87 04
</footer>

<a href="https://wa.me/221782778704" class="float">💬</a>

<script>
document.getElementById("reservationForm").addEventListener("submit", function(e){
    e.preventDefault();
    const form = e.target;
    fetch(form.action, {
        method: "POST",
        body: new FormData(form),
        headers: { 'Accept': 'application/json' }
    }).then(response => {
        document.getElementById("confirmation").style.display = "block";
        form.reset();
    }).catch(error => {
        alert("Erreur lors de l'envoi. Veuillez réessayer.");
    });
});
</script>

</body>
</html>
