<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: #121212; /* Couleur de fond sombre */
      color: #ffffff; /* Couleur du texte clair */
      font-family: Arial, sans-serif;
    }
    h1 {
      color: #00cc66; /* Couleur du titre */
      animation: bounce 2s infinite; /* Animation de rebondissement */
    }
    .section {
      background-color: #1f1f1f; /* Couleur de fond des sections */
      padding: 20px;
      margin: 10px 0;
      border-radius: 5px;
      animation: fadeIn 2s; /* Animation de fondu */
    }
    
    /* Définition des animations */
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
        transform: translateY(0);
      }
      40% {
        transform: translateY(-30px);
      }
      60% {
        transform: translateY(-15px);
      }
    }
    
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <h1>👋 Bonjour, je suis [Votre Nom]!</h1>
  <p>Développeur passionné par [vos domaines d'intérêt].</p>

  <div class="section">
    <h2>🚀 Compétences</h2>
    <!-- Ajoutez ici vos compétences -->
  </div>

  <div class="section">
    <h2>🔨 Projets Récents</h2>
    <!-- Ajoutez ici vos projets récents -->
  </div>

  <div class="section">
    <h2>👨‍💻 Contributions Open Source</h2>
    <!-- Ajoutez ici vos contributions open source -->
  </div>

  <div class="section">
    <h2>📫 Contact</h2>
    <!-- Ajoutez ici vos informations de contact -->
  </div>

  <!-- Ajoutez d'autres sections au besoin -->

  <p align="center">Merci de visiter mon profil GitHub!</p>
</body>
</html>
