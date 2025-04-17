<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MNGF - Conseil en Gestion de Patrimoine</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background-color: #1a1a2e;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #1a1a2e;
    }
    .services, .contact-info {
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
    }
    footer {
      background-color: #1a1a2e;
      color: white;
      text-align: center;
      padding: 1.5rem;
    }

    @media (min-width: 768px) {
      .services, .contact-info {
        flex-direction: row;
        justify-content: space-between;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>MNGF</h1>
    <p>Conseil en Gestion de Patrimoine</p>
    <nav>
      <a href="#services">Services</a>
      <a href="#a-propos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="services">
    <h2>Nos Services</h2>
    <div class="services">
      <div>
        <h3>Investissements financiers</h3>
        <p>Optimisation de votre portefeuille en fonction de vos objectifs à court, moyen et long terme.</p>
      </div>
      <div>
        <h3>Immobilier</h3>
        <p>Accompagnement dans vos projets d’acquisition, de défiscalisation ou de transmission immobilière.</p>
      </div>
      <div>
        <h3>Préparation retraite</h3>
        <p>Stratégies personnalisées pour anticiper et sécuriser votre avenir financier.</p>
      </div>
    </div>
  </section>

  <section id="a-propos">
    <h2>À propos de MNGF</h2>
    <p>MNGF est une agence indépendante fondée par Mickaël NOISIER, spécialiste en gestion de portefeuille et marchés financiers. Notre mission : vous aider à faire les bons choix pour construire et protéger votre patrimoine.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="contact-info">
      <div>
        <p><strong>Email :</strong> contact@mngf.fr</p>
        <p><strong>Téléphone :</strong> 06 66 14 64 46</p>
      </div>
      <div>
        <p><strong>Adresse :</strong> Lyon, France</p>
        <p><strong>Réseaux :</strong> LinkedIn, Instagram (@mngf_patrimoine)</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 MNGF. Tous droits réservés.
  </footer>
</body>
</html>
