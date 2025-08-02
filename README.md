<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ginolin Brico - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(180deg, #f0f4f8, #ffffff);
      color: #333;
    }
    header {
      background-color: #005288;
      color: white;
      padding: 3rem 1rem;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
      background: white;
      margin-top: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }
    h2 {
      color: #005288;
      margin-top: 2rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.5rem;
    }
    ul {
      padding-left: 1.5rem;
    }
    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
    }
    .contact a {
      color: #005288;
      text-decoration: none;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      section {
        padding: 1.2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Ginolin Brico</h1>
    <p>Technicien Réseau & Système | Passionné d'informatique</p>
  </header>

  <section>
    <h2>À propos de moi</h2>
    <p>Je suis un jeune professionnel en technologies de l'information, passionné par les systèmes et les réseaux. Curieux, adaptable et motivé, je suis prêt à relever des défis à l'international et à contribuer activement à des projets concrets, notamment au Canada.</p>

    <h2>Compétences</h2>
    <ul>
      <li>Réseaux informatiques</li>
      <li>Linux & Windows Server</li>
      <li>Virtualisation</li>
      <li>Outils d'automatisation (Puppet)</li>
      <li>Pack Office</li>
    </ul>

    <h2>Expériences professionnelles</h2>
    <ul>
      <li><strong>Control Room - Hap-HITA</strong> (Juin 2024 - Décembre 2024)</li>
      <li><strong>Technicien Inventaire - Madacan-Ambatovy</strong> (Juin 2023 - Décembre 2023)</li>
      <li><strong>Admin-sys - Nogae Développement</strong> (avec outils comme Puppet)</li>
    </ul>

    <h2>Formation</h2>
    <ul>
      <li><strong>Licence en IT</strong> (2019 - 2022), Université OniFra, Tananarivo</li>
      <li><strong>Baccalauréat série D</strong> (2019), Lycée Jacques Rabemananjara, Toamasina</li>
    </ul>

    <h2>Langues</h2>
    <ul>
      <li>Français : avancé</li>
      <li>Anglais : intermédiaire</li>
      <li>Malagasy : langue maternelle</li>
      <li>Chinois : débutant</li>
    </ul>
<h2>Contact</h2>
    <form action="mailto:ginoline11@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="Nom" placeholder="Votre nom" required />
      <input type="email" name="Email" placeholder="Votre email" required />
      <textarea name="Message" placeholder="Votre message..." rows="5" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
    <h2>Contact</h2>
    <p class="contact">
      Email : <a href="mailto:ginoline11@gmail.com">ginoline11@gmail.com</a><br />
      WhatsApp : +261 34 92 158 24
    </p>
  </section>
  

    
  
  <footer>
    <p>&copy; 2025 Ginolin Brico. Tous droits réservés.</p>
  </footer>
</body>
</html>
