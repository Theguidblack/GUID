# GUID
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Le Journal Du G.U.I.D</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    header {
      background: url('couverture.jpg') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: #fff;
    }
    nav {
      display: flex;
      justify-content: space-between;
      padding: 1rem;
    }
    nav ul {
      list-style: none;
      display: flex;
    }
    nav ul li {
      padding: 0 0.5rem;
    }
    nav ul li a {
      text-decoration: none;
      color: #333;
    }
    nav ul li a:hover {
      color: #777;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      overflow: auto;
      padding: 0 1rem;
    }
    .synopsis {
      padding: 2rem;
      background: #f4f4f4;
    }
    .chapters,
    .characters,
    .artifacts {
      padding: 1rem;
    }
    .reviews {
      padding: 1rem;
      background: #f4f4f4;
    }
    .social {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 1rem;
    }
    .social a {
      text-decoration: none;
      color: #333;
      margin: 0 0.5rem;
    }
    .social a:hover {
      color: #777;
    }
    .subscribe {
      background: #f4f4f4;
      padding: 2rem;
      text-align: center;
    }
    .subscribe form {
      display: inline-block;
    }
    .subscribe input[type="email"] {
      border: 1px solid #333;
      padding: 0.5rem;
      width: 300px;
    }
    .subscribe input[type="submit"] {
      background: #333;
      color: #fff;
      border: none;
      padding: 0.5rem 1rem;
      cursor: pointer;
    }
    .subscribe input[type="submit"]:hover {
      background: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>Le Journal Du G.U.I.D</h1>
    <img src="URL_de_la_couverture_du_roman" alt="Couverture du roman" style="max-width: 300px;">
    <p>Un roman passionnant</p>
  </header>
  
  <nav>
    <ul>
      <li><a href="#chapters">Chapitres</a></li>
      <li><a href="#characters">Personnages</a></li>
      <li><a href="#artifacts">Artefacts</a></
    </ul>
    <div class="social">
      <a href="https://www.instagram.com/votre_nom_dutilisateur" target="_blank">Instagram</a>
      <a href="https://www.wattpad.com/user/votre_nom_dutilisateur" target="_blank">Wattpad</a>
      <a href="https://www.snapchat.com/add/votre_nom_dutilisateur" target="_blank">Snapchat</a>
    </div>
  </nav>

  <div class="container">
    <section class="synopsis">
      <h2>Synopsis</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.</p>
    </section>

    <section id="chapters" class="chapters">
      <h2>Chapitres</h2>
      <!-- Ajoutez ici les liens vers les chapitres et leurs illustrations (si disponibles) -->
      <img src="URL_de_l_illustration_du_chapitre" alt="Illustration du chapitre" style="max-width: 200px;">
    </section>

    <section id="characters" class="characters">
      <h2>Personnages</h2>
      <!-- Ajoutez ici les descriptions et illustrations des personnages -->
      <img src="URL_de_l_illustration_du_personnage" alt="Illustration du personnage" style="max-width: 200px;">
    </section>

    <section id="artifacts" class="artifacts">
      <h2>Artefacts</h2>
      <!-- Ajoutez ici les descriptions et illustrations des artefacts -->
      <img src="URL_de_l_illustration_du_artefact" alt="Illustration de l'artefact" style="max-width: 200px;">
    </section>

    <section class="subscribe">
      <h2>Abonnez-vous pour accéder à la lecture des chapitres et aux illustrations</h2>
      <form action="/subscribe" method="post">
        <input type="email" name="email" placeholder="Entrez votre adresse e-mail" required>
        <input type="submit" value="S'abonner">
      </form>
    </section>
  </div>

  <footer>
    <p>Tous droits réservés &copy; 2023. Le Journal Du G.U.I.D.</p>
  </footer>

</body>
</html>
