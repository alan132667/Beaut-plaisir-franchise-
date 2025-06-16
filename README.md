<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Franchise Beauté Plaisir</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #fff8f0;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #f06a4a;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-weight: 700;
      letter-spacing: 2px;
    }
    nav {
      background-color: #fa8c6e;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      padding: 6px 12px;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    nav a:hover {
      background-color: #f06a4a;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #f06a4a;
      border-bottom: 2px solid #f06a4a;
      padding-bottom: 6px;
    }
    ul {
      list-style: disc inside;
    }
    .contact-form {
      background-color: #fdf0e6;
      border: 1px solid #f06a4a;
      padding: 20px;
      border-radius: 6px;
      max-width: 500px;
      margin: 0 auto;
    }
    .contact-form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
    }
    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    .contact-form button {
      background-color: #f06a4a;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 4px;
      font-weight: 700;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .contact-form button:hover {
      background-color: #d85b3d;
    }
    footer {
      text-align: center;
      padding: 20px 10px;
      background-color: #f06a4a;
      color: white;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Franchise Beauté Plaisir</h1>
    <p>Rejoignez notre réseau et développez votre propre boutique beauté</p>
  </header>
  <nav>
    <a href="#concept">Concept</a>
    <a href="#avantages">Avantages</a>
    <a href="#profil">Profil Recherché</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <section id="concept">
      <h2>Notre Concept</h2>
      <p>Beauté Plaisir est une enseigne spécialisée dans la vente de cosmétiques exclusifs et les services esthétiques personnalisés. Notre concept allie qualité, innovation et expérience client pour offrir une offre complète autour de la beauté et du bien-être.</p>
      <ul>
        <li>Produits soigneusement sélectionnés (cosmétiques, parfums d’ambiance, accessoires)</li>
        <li>Services esthétiques rapides et de qualité (manucure, maquillage express)</li>
        <li>Un univers chaleureux et moderne qui fidélise la clientèle</li>
      </ul>
    </section>

    <section id="avantages">
      <h2>Pourquoi choisir Beauté Plaisir ?</h2>
      <ul>
        <li>Un concept clé en main avec accompagnement complet</li>
        <li>Formation initiale et support marketing</li>
        <li>Fournisseurs exclusifs et produits innovants</li>
        <li>Emplacements stratégiques pour maximiser votre chiffre d’affaires</li>
        <li>Réseau dynamique et échanges entre franchisés</li>
      </ul>
    </section>

    <section id="profil">
      <h2>Profil Recherché</h2>
      <p>Nous recherchons des entrepreneurs passionnés par l’univers de la beauté et motivés pour gérer leur propre boutique avec notre accompagnement :</p>
      <ul>
        <li>Esprit commercial et sens du service client</li>
        <li>Volonté d’apprendre et de développer un business</li>
        <li>Respect des valeurs de la marque et volonté de fidéliser la clientèle</li>
        <li>Apport financier personnel selon les conditions de la franchise</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contactez-nous</h2>
      <p>Pour en savoir plus sur la franchise Beauté Plaisir et discuter de votre projet, remplissez le formulaire ci-dessous :</p>
      <form class="contact-form" action="mailto:contact@beauteplaisir.fr" method="post" enctype="text/plain">
        <label for="name">Nom complet</label>
        <input type="text" id="name" name="Nom" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="Email" required />

        <label for="phone">Téléphone</label>
        <input type="tel" id="phone" name="Téléphone" />

        <label for="message">Votre message</label>
        <textarea id="message" name="Message" rows="5" required></textarea>

        <button type="submit">Envoyer</button>
      </form>
    </section>
  </main>
  <footer>
    &copy; 2025 Beauté Plaisir - Tous droits réservés
  </footer>
</body>
</html>
