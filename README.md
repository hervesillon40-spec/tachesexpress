html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tâches Express</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Tâches Express</h1>
    <p>La solution rapide pour connecter clients et entreprises</p>
    <a href="#contact" class="cta-button">Demander un devis</a>
  </header>

  <section id="about">
    <h2>À propos</h2>
    <p>Tâches Express est une plateforme qui connecte les clients à des entreprises fiables pour réaliser des tâches rapidement. Notre mission : simplifier la mise en relation et garantir un service de qualité.</p>
  </section>

  <section id="services">
    <h2>Nos services</h2>
    <div class="steps">
      <div>
        <h3>1. Décrivez votre besoin</h3>
        <p>Le client soumet une tâche à réaliser.</p>
      </div>
      <div>
        <h3>2. Nous trouvons l’entreprise</h3>
        <p>Nous sélectionnons un prestataire qualifié.</p>
      </div>
      <div>
        <h3>3. Paiement du forfait</h3>
        <p>Le client règle un forfait fixe pour la mise en relation.</p>
      </div>
    </div>
  </section>

  <section id="faq">
    <h2>FAQ</h2>
    <details>
      <summary>Comment fonctionne le forfait ?</summary>
      <p>Le client paie un montant fixe pour accéder à notre réseau de prestataires.</p>
    </details>
    <details>
      <summary>Les entreprises sont-elles vérifiées ?</summary>
      <p>Oui, nous validons chaque entreprise avant de la proposer.</p>
    </details>
  </section>

  <section id="payment">
    <h2>Paiement sécurisé</h2>
    <p>Réglez votre forfait en toute sécurité via Stripe :</p>
    <form action="https://checkout.stripe.com/pay/cs_test_1234567890" method="GET">
      <button type="submit">Payer le forfait</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contactez-nous</h2>
    <form>
      <input type="text" placeholder="Votre nom" required>
      <input type="email" placeholder="Votre email" required>
      <textarea placeholder="Votre message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Tâches Express. Tous droits réservés.</p>
  </footer>
</body>
</html>
