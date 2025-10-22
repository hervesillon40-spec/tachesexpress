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
css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #0077cc;
  color: white;
  padding: 40px 20px;
  text-align: center;
}

.cta-button {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #ffcc00;
  color: #333;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 40px 20px;
  background-color: white;
  margin: 20px;
  border-radius: 8px;
}

.steps {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.steps div {
  flex: 1;
  min-width: 200px;
  background-color: #e9f5ff;
  padding: 20px;
  border-radius: 5px;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

input, textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 10px;
  background-color: #0077cc;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background-color: #333;
  color: white;
}

@media (max-width: 768px) {
  header, section, footer {
    padding: 20px;
  }

  .steps {
    flex-direction: column;
  }

  .cta-button, button {
    width: 100%;
    font-size: 1.1em;
  }

  input, textarea {
    font-size: 1em;
  }
}
