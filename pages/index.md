---
title: Accueil
layout: home
---

<section class="hero">
  <div class="container">
    <div class="hero-content">
      <div class="hero-text">
        <span class="greeting">👋 Salut, c'est</span>
        <h1><strong>Jonathan Bayikehya</strong></h1>
        <p class="tagline">Développeur passionné par la technologie, les projets innovants et le partage de connaissances.</p>
        <div class="hero-buttons">
          <a href="#projets" class="btn btn-primary">Voir mes projets</a>
          <a href="#contact" class="btn btn-secondary">Me contacter</a>
        </div>
      </div>
      <div class="hero-image">
        <div class="avatar">
          <i class="fas fa-code"></i>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="about" id="about">
  <div class="container">
    <h2>À propos de moi</h2>
    <div class="about-content">
      <div class="about-text">
        <p>Je suis Jonathan Bayikehya, étudiant développeur passionné par la création de solutions numériques innovantes. Mon parcours m'a permis de travailler sur divers projets allant du développement web aux applications mobiles.</p>
        
        <div class="skills">
          <h3>Compétences</h3>
          <div class="skill-tags">
            <span class="skill-tag">JavaScript</span>
            <span class="skill-tag">React</span>
            <span class="skill-tag">Node.js</span>
            <span class="skill-tag">Python</span>
            <span class="skill-tag">UI/UX Design</span>
            <span class="skill-tag">Gestion de projet</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="projects" id="projets">
  <div class="container">
    <h2>Mes Projets</h2>
    <div class="projects-grid">
      
      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-mobile-alt"></i>
        </div>
        <h3>Application Mobile E-commerce</h3>
        <p>Développement d'une application React Native avec système de paiement intégré.</p>
        <div class="project-tech">
          <span>React Native</span>
          <span>Firebase</span>
          <span>Stripe</span>
        </div>
      </div>
      
      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-chart-line"></i>
        </div>
        <h3>Dashboard Analytics</h3>
        <p>Tableau de bord interactif pour visualisation de données en temps réel.</p>
        <div class="project-tech">
          <span>Vue.js</span>
          <span>D3.js</span>
          <span>Express</span>
        </div>
      </div>
      
      <div class="project-card">
        <div class="project-icon">
          <i class="fas fa-graduation-cap"></i>
        </div>
        <h3>Plateforme Éducative</h3>
        <p>Site web d'apprentissage en ligne avec système de cours interactifs.</p>
        <div class="project-tech">
          <span>Laravel</span>
          <span>MySQL</span>
          <span>Bootstrap</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="values">
  <div class="container">
    <h2>Mes Valeurs</h2>
    <div class="values-grid">
      <div class="value-card">
        <i class="fas fa-lightbulb"></i>
        <h3>Innovation</h3>
        <p>Je cherche toujours à créer des solutions novatrices et efficaces.</p>
      </div>
      
      <div class="value-card">
        <i class="fas fa-hands-helping"></i>
        <h3>Collaboration</h3>
        <p>Je crois en la force du travail d'équipe et du partage des connaissances.</p>
      </div>
      
      <div class="value-card">
        <i class="fas fa-code"></i>
        <h3>Qualité</h3>
        <p>Je m'engage à livrer un code propre, maintenable et de haute qualité.</p>
      </div>
    </div>
  </div>
</section>

<section class="cta" id="contact">
  <div class="container">
    <h2>Travaillons ensemble</h2>
    <p>Vous avez un projet en tête ? N'hésitez pas à me contacter !</p>
    <div class="cta-buttons">
      <a href="mailto:jonathanbayikehya1960@gmail.com" class="btn btn-primary">
        <i class="fas fa-envelope"></i>
        M'envoyer un email
      </a>
      <a href="https://github.com/Jonathanbayikehya" class="btn btn-secondary" target="_blank">
        <i class="fab fa-github"></i>
        Voir mon GitHub
      </a>
    </div>
  </div>
</section>

<style>
:root {
  --primary: #2563eb;      /* Bleu professionnel moderne */
  --secondary: #1e40af;    /* Bleu foncé élégant */
  --accent: #f59e0b;       /* Orange chaleureux pour les accents */
  --dark: #1e293b;         /* Gris bleu foncé sophistiqué */
  --light: #f8fafc;        /* Gris très clair pour le fond */
  --text: #334155;         /* Gris foncé lisible */
  --text-light: #64748b;   /* Gris moyen */
  --shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  --transition: all 0.3s ease;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: var(--text);
  background-color: var(--light);
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

/* Hero Section */
.hero {
  padding: 120px 0 80px;
  background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
  color: white;
  text-align: center;
}

.hero-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 40px;
}

.hero-text {
  max-width: 600px;
}

.greeting {
  font-size: 1.2rem;
  margin-bottom: 10px;
  display: block;
  opacity: 0.9;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 20px;
  line-height: 1.2;
}

.tagline {
  font-size: 1.3rem;
  margin-bottom: 30px;
  opacity: 0.9;
}

.hero-buttons {
  display: flex;
  gap: 15px;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 12px 30px;
  border-radius: 50px;
  text-decoration: none;
  font-weight: 600;
  transition: var(--transition);
  border: 2px solid transparent;
}

.btn-primary {
  background: var(--accent);
  color: white;
}

.btn-primary:hover {
  background: transparent;
  border-color: var(--accent);
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(245, 158, 11, 0.3);
}

.btn-secondary {
  background: transparent;
  color: white;
  border-color: white;
}

.btn-secondary:hover {
  background: white;
  color: var(--dark);
  transform: translateY(-2px);
}

.avatar {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.1);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 4rem;
  border: 4px solid rgba(255, 255, 255, 0.2);
  transition: var(--transition);
}

.avatar:hover {
  transform: scale(1.05);
  border-color: rgba(255, 255, 255, 0.4);
}

/* Sections communes */
section {
  padding: 80px 0;
}

h2 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 50px;
  color: var(--dark);
  position: relative;
}

h2::after {
  content: '';
  display: block;
  width: 80px;
  height: 4px;
  background: var(--accent);
  margin: 15px auto;
  border-radius: 2px;
}

/* About Section */
.about {
  background: white;
}

.about-content {
  max-width: 800px;
  margin: 0 auto;
  text-align: center;
}

.about-text p {
  font-size: 1.1rem;
  margin-bottom: 30px;
  color: var(--text-light);
  line-height: 1.7;
}

.skills h3 {
  margin-bottom: 20px;
  color: var(--dark);
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.skill-tag {
  background: var(--light);
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.9rem;
  color: var(--primary);
  border: 1px solid #e2e8f0;
  transition: var(--transition);
}

.skill-tag:hover {
  background: var(--primary);
  color: white;
  transform: translateY(-2px);
}

/* Projects Section */
.projects {
  background: var(--light);
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.project-card {
  background: white;
  padding: 30px;
  border-radius: 15px;
  box-shadow: var(--shadow);
  transition: var(--transition);
  text-align: center;
  border: 1px solid #f1f5f9;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
  border-color: var(--primary);
}

.project-icon {
  font-size: 2.5rem;
  color: var(--primary);
  margin-bottom: 20px;
}

.project-card h3 {
  margin-bottom: 15px;
  color: var(--dark);
}

.project-card p {
  color: var(--text-light);
  margin-bottom: 20px;
  line-height: 1.6;
}

.project-tech {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  justify-content: center;
}

.project-tech span {
  background: var(--light);
  padding: 4px 12px;
  border-radius: 15px;
  font-size: 0.8rem;
  color: var(--primary);
  border: 1px solid #e2e8f0;
}

/* Values Section */
.values {
  background: white;
}

.values-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.value-card {
  background: var(--light);
  padding: 40px 30px;
  border-radius: 15px;
  text-align: center;
  box-shadow: var(--shadow);
  transition: var(--transition);
  border: 1px solid #f1f5f9;
}

.value-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
  background: white;
}

.value-card i {
  font-size: 2.5rem;
  color: var(--primary);
  margin-bottom: 20px;
}

.value-card h3 {
  margin-bottom: 15px;
  color: var(--dark);
}

.value-card p {
  color: var(--text-light);
  line-height: 1.6;
}

/* CTA Section */
.cta {
  background: var(--dark);
  color: white;
  text-align: center;
}

.cta h2 {
  color: white;
}

.cta h2::after {
  background: var(--accent);
}

.cta p {
  font-size: 1.2rem;
  margin-bottom: 30px;
  opacity: 0.9;
}

.cta-buttons {
  display: flex;
  gap: 15px;
  justify-content: center;
  flex-wrap: wrap;
}

/* Responsive */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 2.2rem;
  }
  
  .tagline {
    font-size: 1.1rem;
  }
  
  h2 {
    font-size: 2rem;
  }
  
  .hero-buttons, .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .btn {
    width: 200px;
    justify-content: center;
  }
  
  .hero-content {
    gap: 30px;
  }
  
  .avatar {
    width: 150px;
    height: 150px;
    font-size: 3rem;
  }
}

@media (max-width: 480px) {
  .hero {
    padding: 100px 0 60px;
  }
  
  section {
    padding: 60px 0;
  }
  
  .projects-grid {
    grid-template-columns: 1fr;
  }
  
  .values-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<script>
// Animation simple au défilement
document.addEventListener('DOMContentLoaded', function() {
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
  };

  const observer = new IntersectionObserver(function(entries) {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.style.opacity = '1';
        entry.target.style.transform = 'translateY(0)';
      }
    });
  }, observerOptions);

  // Animer les éléments au scroll
  document.querySelectorAll('.project-card, .value-card, .skill-tag').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
    observer.observe(el);
  });

  // Navigation fluide
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });
      }
    });
  });
});
</script>
