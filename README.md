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
      background-color: #f8f9fa;
    }
    .profile-img {
      width: 250px;
      height: 250px;
      object-fit: cover;
      border-radius: 50%;
      border: 2px solid #ffc107;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      margin-bottom: 20px;
    }
    .section-title {
      font-weight: 600;
      margin-bottom: 40px;
      border-bottom: 3px solid #ffc107;
      display: inline-block;
      padding-bottom: 5px;
    }
    .card i {
      margin-right: 8px;
    }
    .flag {
      font-size: 1.2rem;
      margin-top: 10px;
      display: block;
    }
    .language-card {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      text-align: center;
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }


    /* Survol des liens du menu */
.nav-link {
  position: relative;
  transition: color 0.3s ease;
}

.nav-link::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: 0;
  width: 0;
  height: 2px;
  background-color: #ffc107;
  transition: width 0.3s ease;
}

.nav-link:hover {
  color: #ffc107;
}

.nav-link:hover::after {
  width: 100%;
}

/* Boutons réseaux sociaux */
.btn:hover {
  transform: scale(1.05);
  box-shadow: 0 0 10px rgba(0,0,0,0.15);
  transition: all 0.3s ease-in-out;
}

  </style>
</head>
<body>

<!-- En-tête -->
<header class="bg-primary text-white text-center py-5">
  <img src="david_photo.jpg" alt="Photo de Daouda Ba" class="profile-img">
  <h1 class="mt-3">Daouda Ba</h1>
  <p>Étudiant en Master Informatique – UCAD, Dakar</p>
</header>

<!-- Navigation -->
<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm sticky-top">
  <div class="container justify-content-center">
    <ul class="navbar-nav gap-3">
      <li class="nav-item"><a class="nav-link fw-bold" href="#about">À propos</a></li>
      <li class="nav-item"><a class="nav-link fw-bold" href="#skills">Compétences</a></li>
      <li class="nav-item"><a class="nav-link fw-bold" href="#education">Études</a></li>
      <li class="nav-item"><a class="nav-link fw-bold" href="#languages">Langues</a></li>
      <li class="nav-item"><a class="nav-link fw-bold" href="#interests">Centres d’intérêt</a></li>
      <li class="nav-item"><a class="nav-link fw-bold" href="#contact">Contact</a></li>
    </ul>
  </div>
</nav>

<!-- À propos -->
<section id="about" class="container text-center py-5">
  <h2 class="section-title">À propos de moi</h2>
  <p>Étudiant en Informatique, rigoureux, sociable et passionné par le travail en équipe. Actuellement en Master à l’UCAD en Systèmes d’Information Répartis.</p>
</section>

<!-- Compétences -->
<section id="skills" class="bg-light py-5">
  <div class="container">
    <h2 class="text-center section-title">Compétences</h2>
    <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col"><div class="card p-3"><i class="bi bi-code-slash text-warning"></i> HTML, CSS, JavaScript</div></div>
      <div class="col"><div class="card p-3"><i class="bi bi-terminal text-primary"></i> C, C++, Java</div></div>
      <div class="col"><div class="card p-3"><i class="bi bi-braces text-info"></i> Java EE, JDBC</div></div>
      <div class="col"><div class="card p-3"><i class="bi bi-phone text-success"></i> Flutter, Dart</div></div>
      <div class="col"><div class="card p-3"><i class="bi bi-database text-danger"></i> MySQL, PostgreSQL, Oracle</div></div>
      <div class="col"><div class="card p-3"><i class="bi bi-windows text-dark"></i> Word, Excel, PowerPoint</div></div>
    </div>
  </div>
</section>

<!-- Études -->
<section id="education" class="container py-5">
  <h2 class="text-center section-title">Études et formation</h2>
  <div class="row row-cols-1 row-cols-md-2 g-4">
    <div class="col"><div class="card p-3"><i class="bi bi-mortarboard text-warning"></i> Master 1 – UCAD (2024-2025)</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-mortarboard text-warning"></i> Licence Informatique – UCAD (2021-2024)</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-book text-primary"></i> Bac S1 – Lycée de Ourossogui (2020)</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-book text-primary"></i> BFEM – Collège de Aoure (2017)</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-book text-primary"></i> CFEE – École de Koly (2013)</div></div>
  </div>
</section>

<!-- Langues -->
<section id="languages" class="bg-light py-5">
  <div class="container">
    <h2 class="text-center section-title">Langues parlées</h2>
    <div class="row row-cols-1 row-cols-md-3 g-4 text-center">
      <div class="col">
        <div class="language-card">
          <div>
            <h5>Français</h5>
            <p>Très bon niveau</p>
          </div>
          <small class="flag">🇫🇷</small>
        </div>
      </div>
      <div class="col">
        <div class="language-card">
          <div>
            <h5>Anglais</h5>
            <p>Bon niveau</p>
          </div>
          <small class="flag">🇺🇸</small>
        </div>
      </div>
      <div class="col">
        <div class="language-card">
          <div>
            <h5>Arabe</h5>
            <p>Niveau moyen</p>
          </div>
          <small class="flag">🇸🇦</small>
        </div>
      </div>
      <div class="col">
        <div class="language-card">
          <div>
            <h5>Poular</h5>
            <p>Langue maternelle</p>
          </div>
          <small class="flag">🇸🇳</small>
        </div>
      </div>
      <div class="col">
        <div class="language-card">
          <div>
            <h5>Wolof</h5>
            <p>Bon niveau</p>
          </div>
          <small class="flag">🇸🇳</small>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Centres d’intérêt -->
<section id="interests" class="container py-5">
  <h2 class="text-center section-title">Centres d’intérêt</h2>
  <div class="row row-cols-1 row-cols-md-3 g-3 text-center">
    <div class="col"><div class="card p-3"><i class="bi bi-trophy text-warning"></i> Football</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-music-note-beamed text-danger"></i> Musique</div></div>
    <div class="col"><div class="card p-3"><i class="bi bi-book text-primary"></i> Lecture</div></div>
  </div>
</section>

<!-- Contact -->
<section id="contact" class="bg-light py-5">
  <div class="container text-center">
    <h2 class="section-title">Contact</h2>
    <p><i class="bi bi-envelope text-warning"></i> daoudaba2001@gmail.com</p>
    <p><i class="bi bi-phone text-success"></i> +221 78 541 76 19</p>
    <p><i class="bi bi-geo-alt text-danger"></i> Médina Rue 37x32, Dakar</p>
    <div class="mt-3">
      <a href="https://www.facebook.com/daouda.ba.802206" class="btn btn-outline-primary me-2" target="_blank"><i class="bi bi-facebook"></i> Facebook</a>
      <a href="https://twitter.com/daoudaba" class="btn btn-outline-info me-2" target="_blank"><i class="bi bi-twitter"></i> Twitter</a>
      <a href="https://www.instagram.com/daoudaba.17/" class="btn btn-outline-danger me-2" target="_blank"><i class="bi bi-instagram"></i> Instagram</a>
      <a href="https://wa.me/221785417619" class="btn btn-outline-success" target="_blank"><i class="bi bi-whatsapp"></i> WhatsApp</a>
    </div>
  </div>
</section>

<!-- Pied de page -->
<footer class="bg-dark text-white text-center py-4">
  &copy; 2025 Daouda Ba. Tous droits réservés.
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
