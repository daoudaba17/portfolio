<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portfolio - Daouda Ba</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f0f2f5;
      color: #333;
    }
    .profile-img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #ffc107;
      margin-bottom: 15px;
    }
    .section-title {
      font-weight: bold;
      font-size: 1.8rem;
      margin-bottom: 40px;
      border-bottom: 3px solid #ffc107;
      padding-bottom: 5px;
      text-align: center;
      width: fit-content;
      margin-left: auto;
      margin-right: auto;
      display: block;
    }
    .card {
      border: none;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card i {
      font-size: 1.4rem;
      margin-right: 8px;
    }
    .nav-link {
      position: relative;
      font-weight: bold;
    }
    .nav-link::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 0;
      height: 2px;
      background-color: #ffc107;
      transition: width 0.3s;
    }
    .nav-link:hover::after {
      width: 100%;
    }
    .language-card {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 150px;
    }
    .language-card h5 {
      margin-bottom: 5px;
    }
    .language-card p {
      margin-bottom: 10px;
      font-weight: 500;
    }
    .flag {
      font-size: 1.5rem;
      margin-top: auto;
    }
    .download-btn {
      margin-top: 20px;
    }
    footer {
      background-color: #212529;
      color: white;
    }
    @media (max-width: 767px) {
      .section-title {
        font-size: 1.5rem;
      }
      .card {
        font-size: 0.9rem;
      }
      .profile-img {
        width: 150px;
        height: 150px;
      }
      /* Ajuster hauteur langue sur mobile */
      .language-card {
        height: auto;
        padding: 15px;
      }
    }

    /* Style pour le texte de l'université (marquee) */
  marquee {
    font-size: 1.2rem;
    font-weight: 600;
    color: #ffc107; /* couleur jaune/orangé comme le thème */
    letter-spacing: 1px;
    margin: 10px 0 5px;
    text-transform: uppercase;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

/* Animation plus fluide et moderne (alternative au marquee natif, facultatif) */
/* Vous pouvez remplacer le <marquee> par ce CSS si vous voulez un effet défilant plus contrôlé */

/* Faculté */
  header h3 {
    font-size: 1.1rem;
    font-weight: 500;
    color: #444;
    font-style: italic;
    margin-top: 0;
    margin-bottom: 20px;
    letter-spacing: 0.5px;
    text-align: center;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
  }

  </style>
</head>
<body>

<header class="bg-primary text-white text-center py-5">
  <img src="david_photo.jpg" alt="Photo de Daouda Ba, étudiant en Master Informatique" class="profile-img">
  <h1 class="mt-2">Daouda Ba</h1>
  <p>Étudiant en Master Informatique</p>
  <marquee behavior="" direction="">Université Cheikh Anta Diop, Dakar</marquee>
  <h3>Faculté des Sciences et Techniques - Département de Mathématiques-Informatique</h3>
</header>

<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm sticky-top">
  <div class="container">
    <a class="navbar-brand fw-bold" href="#">Daouda Ba</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
      <ul class="navbar-nav gap-4">
        <li class="nav-item"><a class="nav-link" href="#about">À propos</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Compétences</a></li>
        <li class="nav-item"><a class="nav-link" href="#education">Études</a></li>
        <li class="nav-item"><a class="nav-link" href="#languages">Langues</a></li>
        <li class="nav-item"><a class="nav-link" href="#interests">Centres d’intérêt</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<section id="about" class="container py-5 text-center">
  <h2 class="section-title">À propos de moi</h2>
  <p>Étudiant en Informatique, rigoureux, sociable et passionné par le travail en équipe. Actuellement en Master à l’UCAD en Systèmes d’Information Répartis.</p>
</section>

<section id="skills" class="py-5 bg-light">
  <div class="container">
    <h2 class="section-title text-center">Compétences</h2>
    <div class="row g-4 justify-content-center">
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-code-slash text-warning"></i> <strong>Développement Web :</strong> HTML, CSS, JavaScript, JQuery, Ajax</div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-phone text-success"></i> <strong>Développement Mobile :</strong> Flutter, Dart</div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-terminal text-primary"></i> <strong>Programmation :</strong> C, C++, Java, Python</div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-braces text-info"></i> <strong>Java EE, Hibernate, Spring Boot</strong></div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-database text-danger"></i> <strong>Bases de données :</strong> MySQL, PostgreSQL, Oracle</div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-palette text-secondary"></i> <strong>Infographie</strong></div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-router text-dark"></i> <strong>Réseaux :</strong> Adressage IP, Routage statique et dynamique</div>
      </div>
      <div class="col-md-4">
        <div class="card p-3"><i class="bi bi-windows text-dark"></i> <strong>Outils bureautiques :</strong> Word, Excel, PowerPoint</div>
      </div>
    </div>
  </div>
</section>

<section id="education" class="container py-5">
  <h2 class="section-title text-center">Études et Diplômes</h2>
  <div class="row g-4 justify-content-center">
    <div class="col-md-6"><div class="card p-3"><i class="bi bi-mortarboard text-warning"></i> Master 1 – UCAD (2024-2025)</div></div>
    <div class="col-md-6"><div class="card p-3"><i class="bi bi-mortarboard text-warning"></i> Licence Informatique – UCAD (2023-2024)</div></div>
    <div class="col-md-6"><div class="card p-3"><i class="bi bi-book text-primary"></i> Bac S1 – Lycée de Ourossogui (2020)</div></div>
    <div class="col-md-6"><div class="card p-3"><i class="bi bi-book text-primary"></i> BFEM – Collège de Aoure (2017)</div></div>
    <div class="col-md-6"><div class="card p-3"><i class="bi bi-book text-primary"></i> CFEE – École de Koly (2013)</div></div>
  </div>
</section>

<section id="languages" class="bg-light py-5">
  <div class="container">
    <h2 class="section-title text-center">Langues parlées</h2>
    <div class="row g-4 justify-content-center">
      <div class="col-6 col-md-4 col-lg-3">
        <div class="language-card">
          <h5>Français</h5>
          <p>Très bon niveau</p>
          <span class="flag" aria-label="Drapeau français" role="img">🇫🇷</span>
        </div>
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <div class="language-card">
          <h5>Anglais</h5>
          <p>Bon niveau</p>
          <span class="flag" aria-label="Drapeau américain" role="img">🇺🇸</span>
        </div>
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <div class="language-card">
          <h5>Arabe</h5>
          <p>Niveau moyen</p>
          <span class="flag" aria-label="Drapeau saoudien" role="img">🇸🇦</span>
        </div>
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <div class="language-card">
          <h5>Poular</h5>
          <p>Langue maternelle</p>
          <span class="flag" aria-label="Drapeau Sénégalais" role="img">🇸🇳</span>
        </div>
      </div>
      <div class="col-6 col-md-4 col-lg-3">
        <div class="language-card">
          <h5>Wolof</h5>
          <p>Bon niveau</p>
          <span class="flag" aria-label="Drapeau Sénégalais" role="img">🇸🇳</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="interests" class="container py-5">
  <h2 class="section-title text-center">Centres d’intérêt</h2>
  <div class="row g-4 text-center justify-content-center">
    <div class="col-md-4"><div class="card p-3"><i class="bi bi-trophy text-warning"></i> Football</div></div>
    <div class="col-md-4"><div class="card p-3"><i class="bi bi-book text-primary"></i> Lecture</div></div>
    <div class="col-md-4"><div class="card p-3"><i class="bi bi-music-note-beamed text-danger"></i> Musique</div></div>
  </div>
</section>

<section id="contact" class="bg-light py-5">
  <div class="container text-center">
    <h2 class="section-title">Contact</h2>
    <p><i class="bi bi-envelope text-warning"></i> <a href="mailto:daoudaba2001@gmail.com">daoudaba2001@gmail.com</a></p>
    <p><i class="bi bi-phone text-success"></i> <a href="tel:+221785417619">+221 78 541 76 19</a></p>
    <p><i class="bi bi-geo-alt text-danger"></i> Médina Rue 37x32, Dakar</p>
    <div class="mt-3">
      <a href="https://www.facebook.com/daouda.ba.802206" class="btn btn-outline-primary me-2" target="_blank" aria-label="Facebook"><i class="bi bi-facebook"></i></a>
      <a href="#" class="btn btn-outline-info me-2" target="_blank" aria-label="Twitter"><i class="bi bi-twitter"></i></a>
      <a href="https://www.instagram.com/daoudaba.17/" class="btn btn-outline-danger me-2" target="_blank" aria-label="Instagram"><i class="bi bi-instagram"></i></a>
      <a href="https://wa.me/221785417619" class="btn btn-outline-success" target="_blank" aria-label="WhatsApp"><i class="bi bi-whatsapp"></i></a>
    </div>
  </div>
</section>

<footer class="text-center py-4">
  &copy; 2025 Daouda Ba. Tous droits réservés.
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
