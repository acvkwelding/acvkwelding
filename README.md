<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ACVK Welding | Ferronnerie sur mesure</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans text-gray-800">

  <!-- Accueil -->
  <header class="bg-gray-900 text-white text-center py-20 px-4">
    <h1 class="text-4xl md:text-6xl font-bold mb-4">ACVK Welding</h1>
    <p class="text-xl md:text-2xl mb-6">Ferronnerie sur mesure & soudure artisanale</p>
    <p class="mb-8">Portails, escaliers, garde-corps, verrières, et plus encore</p>
    <a href="#contact" class="bg-white text-gray-900 px-6 py-3 rounded-full font-semibold hover:bg-gray-200 transition">Demander un devis</a>
  </header>

  <!-- Services -->
  <section id="services" class="py-16 px-6 max-w-5xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Nos Services</h2>
    <div class="grid md:grid-cols-2 gap-6">
      <div>
        <h3 class="font-semibold text-lg mb-2">Portails & Clôtures</h3>
        <p>Designs classiques ou contemporains, motorisation possible.</p>
      </div>
      <div>
        <h3 class="font-semibold text-lg mb-2">Escaliers & Rampes</h3>
        <p>Fabrication sur mesure pour intérieur ou extérieur.</p>
      </div>
      <div>
        <h3 class="font-semibold text-lg mb-2">Garde-corps & Balcons</h3>
        <p>Esthétique, sécurité et durabilité réunies.</p>
      </div>
      <div>
        <h3 class="font-semibold text-lg mb-2">Verrières & Décoration</h3>
        <p>Ajoutez du style et de la lumière à vos espaces.</p>
      </div>
      <div>
        <h3 class="font-semibold text-lg mb-2">Châssis métalliques</h3>
        <p>Conçus sur mesure pour toutes vos ouvertures.</p>
      </div>
    </div>
  </section>

  <!-- À propos -->
  <section id="a-propos" class="bg-gray-100 py-16 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-6">À propos</h2>
      <p class="mb-4">ACVK Welding est une entreprise jeune et passionnée, alliant maîtrise technique et souci du détail.</p>
      <p class="mb-4">Nous vous accompagnons de la conception à la pose pour des créations durables, esthétiques et parfaitement adaptées.</p>
      <p>Implantés localement, nous sommes réactifs et engagés dans chaque projet.</p>
    </div>
  </section>

  <!-- Réalisations -->
  <section id="realisations" class="py-16 px-6 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-10">Nos Réalisations</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <img src="projet1.jpg" alt="Portail sur mesure" class="rounded-xl shadow-md object-cover w-full h-64" />
      <img src="projet2.jpg" alt="Garde-corps design" class="rounded-xl shadow-md object-cover w-full h-64" />
      <img src="projet3.jpg" alt="Escalier métallique" class="rounded-xl shadow-md object-cover w-full h-64" />
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="bg-gray-900 text-white py-16 px-6">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">Contact</h2>
      <form class="space-y-6">
        <div>
          <label for="nom" class="block mb-1">Nom</label>
          <input type="text" id="nom" class="w-full p-3 rounded bg-gray-800 border border-gray-700" required />
        </div>
        <div>
          <label for="email" class="block mb-1">Email</label>
          <input type="email" id="email" class="w-full p-3 rounded bg-gray-800 border border-gray-700" required />
        </div>
        <div>
          <label for="message" class="block mb-1">Message</label>
          <textarea id="message" rows="4" class="w-full p-3 rounded bg-gray-800 border border-gray-700" required></textarea>
        </div>
        <button type="submit" class="bg-white text-gray-900 font-semibold px-6 py-3 rounded hover:bg-gray-200 transition">Envoyer</button>
      </form>
      <div class="text-center mt-8">
        <p>Tél : 0497230127
</p>
        <p>Email : acvk.welding@gmail.com</p>
      </div>
    </div>
  </section>

  <footer class="bg-gray-800 text-gray-400 text-center py-4 text-sm">
    &copy; 2025 ACVK Welding. Tous droits réservés.
  </footer>

</body>
</html>
