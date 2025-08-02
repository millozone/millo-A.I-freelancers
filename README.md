<!DOCTYPE html>
<html lang="ro">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MySite</title>
    <link rel="stylesheet" href="style.css" />
    <script
      src="https://kit.fontawesome.com/a2e8efac31.js"
      crossorigin="anonymous"
    ></script>
    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <div id="loader-wrapper">
      <div id="loader"></div>
    </div>

    <nav class="navbar">
      <div class="logo fade-in">millo & A.I</div>
      <button class="hamburger" id="hamburger">&#9776;</button>
      <ul class="menu" id="menu">
        <li><a href="#acasa">Acasa</a></li>
        <li><a href="#despre">Despre</a></li>
        <li class="dropdown">
          <a href="#servicii">Servicii ▾</a>
          <ul class="dropdown-content">
            <li><a href="#web">Web Design</a></li>
            <li><a href="#seo">SEO</a></li>
            <li><a href="#consultanta">Consultanță</a></li>
          </ul>
        </li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#testimoniale">Testimoniale</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <label class="switch" for="theme-switch">
        <input type="checkbox" id="theme-switch" />
        <span class="slider"></span>
      </label>
    </nav>

    <main id="main-content">
      <section id="acasa">
        <div class="hidden" style="text-align: center;">
          <h2 style="font-size: 3rem; margin-bottom: 1rem;">Transform ideile în prezență online de succes</h2>
          <p style="font-size: 1.2rem; margin-bottom: 2rem; max-width: 800px; margin-left: auto; margin-right: auto;">
            Salut, sunt Millo. Ca freelancer, alături de un partener A.I., creez soluții digitale unice. De la design-uri web personalizate, la strategii SEO de top, folosesc inovația pentru a-ți propulsa afacerea în mediul online.
          </p>
          
          <div class="benefits-grid">
            <div class="benefit-item" style="background-color: rgba(255, 255, 255, 0.1); color: white;">
              <h3><i class="fas fa-rocket"></i> Viteză și Performanță</h3>
              <p>Îți ofer site-uri rapide, optimizate pentru motoarele de căutare și cu o experiență de utilizare impecabilă, create cu suportul inovației AI.</p>
            </div>
            <div class="benefit-item" style="background-color: rgba(255, 255, 255, 0.1); color: white;">
              <h3><i class="fas fa-magic"></i> Design Personalizat</h3>
              <p>Folosesc instrumente AI pentru a genera rapid concepte unice, pe care le adaptez și finisez manual pentru a-ți crea o identitate vizuală de neuitat.</p>
            </div>
            <div class="benefit-item" style="background-color: rgba(255, 255, 255, 0.1); color: white;">
              <h3><i class="fas fa-users"></i> Suport dedicat</h3>
              <p>Îți sunt alături la fiecare pas, de la concept la lansare și mentenanță, oferind o colaborare directă și transparentă.</p>
            </div>
          </div>
          
          <a href="#start-project" class="cta-button">Începe proiectul tău</a>
        </div>
      </section>

      <section id="start-project">
        <h2>E timpul să transformăm ideile în realitate</h2>
        <p>Te voi contacta în cel mai scurt timp pentru a discuta despre cum putem construi o prezență online de succes pentru afacerea ta.</p>
        <form action="https://formspree.io/f/mjkoeybv" method="POST">
            <div class="form-group">
                <label for="full-name">Numele tău complet:</label>
                <input type="text" id="full-name" name="full-name" required>
                <span class="error-message">Acest câmp este obligatoriu.</span>
            </div>
            <div class="form-group">
                <label for="email">Adresa ta de email:</label>
                <input type="email" id="email" name="email" required>
                <span class="error-message">Acest câmp este obligatoriu și trebuie să fie un email valid.</span>
            </div>
            <div class="form-group">
                <label for="phone">Numărul de telefon (opțional):</label>
                <input type="tel" id="phone" name="phone">
            </div>
            <div class="form-group">
                <label for="budget">Bugetul estimat pentru proiect:</label>
                <select id="budget" name="budget">
                    <option value="500-1000">500 - 1000 EUR</option>
                    <option value="1000-3000">1000 - 3000 EUR</option>
                    <option value="3000+">peste 3000 EUR</option>
                    <option value="discutie">Încă nu sunt sigur</option>
                </select>
            </div>
            <div class="form-group">
                <label for="project-details">Spune-mi mai multe despre proiectul tău:</label>
                <textarea id="project-details" name="project-details" required></textarea>
                <span class="error-message">Acest câmp este obligatoriu.</span>
            </div>
            <button type="submit">Trimite propunerea</button>
        </form>
      </section>

      <section id="despre">
        <h2 class="hidden">Despre mine</h2>
        <div class="hidden">
          <p>
            Sunt Millo, un freelancer pasionat de tehnologie, creativitate și eficiență. În parteneriat cu A.I., un set avansat de instrumente de inteligență artificială, îmi amplific abilitățile pentru a crea soluții web unice și performante.
          </p>
          <p>
            Munca mea se bazează pe trei piloni esențiali: **creativitate**, **precizie** și **colaborare**. Fiecare proiect este o colaborare directă, transparentă, unde îmi pun toată expertiza pentru a-ți construi o prezență online care te reprezintă perfect.
          </p>
        </div>
      </section>

      <section id="servicii">
        <h2 class="hidden">Servicii complete pentru o prezență online de succes</h2>
        <div class="hidden">
          <p>
            De la design web captivant la strategii SEO eficiente, ofer soluții personalizate care transformă viziunea ta în realitate. Misiunea mea este să construiesc o fundație digitală solidă, adaptată perfect nevoilor tale, folosind cele mai noi tehnologii, inclusiv AI.
          </p>
          <p>
            Explorează portofoliul meu de servicii și alege ce se potrivește cel mai bine pentru afacerea ta.
          </p>
        </div>
      </section>

      <section id="web" class="hidden">
        <h2 class="hidden">Servicii de Web Design</h2>
        <div class="hidden">
          <p>
            Un site web este cartea ta de vizită digitală. Creez experiențe online memorabile, cu design-uri moderne, intuitive și 100% responsive. Cu ajutorul AI, procesul de design este mai rapid, iar codul este optimizat pentru viteză și performanță maximă.
          </p>
          <ul>
            <li>Design UI/UX personalizat</li>
            <li>Dezvoltare Front-End & Back-End</li>
            <li>Site-uri de prezentare și bloguri</li>
            <li>Magazine online (E-commerce)</li>
            <li>Mentenanță și suport tehnic</li>
          </ul>
          <p>
            Transformă-ți ideile în realitate cu un site care arată impecabil și funcționează perfect pe orice dispozitiv.
          </p>
        </div>
      </section>

      <section id="seo" class="hidden">
        <h2 class="hidden">Optimizare SEO (Search Engine Optimization)</h2>
        <div class="hidden">
          <p>
            Vrei să fii găsit de clienți? O strategie SEO eficientă este cheia. Mă asigur că site-ul tău apare în topul rezultatelor de căutare pe Google, atrăgând astfel trafic organic și de calitate. Folosesc instrumente AI pentru a analiza cuvinte cheie, a optimiza conținut și a monitoriza performanța cu o precizie de neegalat.
          </p>
          <ul>
            <li>Analiza cuvintelor cheie și a concurenței</li>
            <li>Optimizare tehnică On-Page și Off-Page</li>
            <li>Creare de conținut optimizat</li>
            <li>Monitorizare și rapoarte de performanță</li>
          </ul>
          <p>
            Investește în SEO și transformă vizitatorii în clienți fideli.
          </p>
        </div>
      </section>

      <section id="consultanta" class="hidden">
        <h2 class="hidden">Consultanță Digitală Strategică</h2>
        <div class="hidden">
          <p>
            Fiecare proiect de succes începe cu o viziune clară. Ofer consultanță de specialitate pentru a-ți defini obiectivele, a-ți optimiza strategia online și a-ți maximiza impactul digital. Folosesc analize bazate pe AI pentru a-ți oferi o perspectivă completă și a te ajuta să iei cele mai bune decizii.
          </p>
          <ul>
            <li>Audit complet al site-ului și strategiei actuale</li>
            <li>Planificare strategică a prezenței online</li>
            <li>Consiliere în alegerea celor mai bune tehnologii</li>
            <li>Sesiuni de training și suport personalizat</li>
          </ul>
          <p>
            Te ajut să iei deciziile corecte pentru a-ți atinge obiectivele de business.
          </p>
        </div>
      </section>

      <section id="blog">
        <h2 class="hidden">Ultimele articole de pe blog</h2>
        <div class="blog-container hidden">
          <div class="blog-post">
            <img src="https://via.placeholder.com/400x250" alt="Imagine blog post 1">
            <h3>Cum să-ți optimizezi site-ul pentru Google</h3>
            <small>Publicat pe 24 iulie 2024 de Ion Popescu</small>
            <p>O analiză detaliată a celor mai bune practici SEO pentru a te poziționa în topul rezultatelor de căutare...</p>
            <a href="#">Citește mai mult &rarr;</a>
          </div>
          <div class="blog-post">
            <img src="https://via.placeholder.com/400x250" alt="Imagine blog post 2">
            <h3>Design-ul web modern în 2024</h3>
            <small>Publicat pe 15 iulie 2024 de Ana Vasilescu</small>
            <p>Descoperă tendințele actuale în design-ul web, de la animații subtile la interfețe intuitive...</p>
            <a href="#">Citește mai mult &rarr;</a>
          </div>
          <div class="blog-post">
            <img src="https://via.placeholder.com/400x250" alt="Imagine blog post 3">
            <h3>E-commerce: de la idee la succes</h3>
            <small>Publicat pe 3 iulie 2024 de George Enescu</small>
            <p>Ghidul complet pentru a lansa un magazin online de succes, de la platformă la strategie de marketing...</p>
            <a href="#">Citește mai mult &rarr;</a>
          </div>
        </div>
      </section>

      <section id="testimoniale">
        <h2 class="hidden">Ce spun clienții mei</h2>
        <div class="testimoniale-container hidden">
            <div class="testimonial-card">
                <p>"Colaborarea cu Millo a fost excepțională. Nu doar că a creat un site web minunat, dar a înțeles cu adevărat viziunea afacerii noastre. Faptul că folosește și inteligența artificială s-a văzut în rapiditatea și calitatea rezultatelor!"</p>
                <h4>Alexandru Popescu</h4>
                <small>CEO, TechSolutions</small>
            </div>
            <div class="testimonial-card">
                <p>"Serviciile sale SEO au transformat prezența noastră online. Am văzut o creștere masivă a traficului organic și a conversiilor."</p>
                <h4>Maria Ionescu</h4>
                <small>Marketing Manager, GreenFarm</small>
            </div>
            <div class="testimonial-card">
                <p>"Recomand cu încredere! A fost rapid, profesionist și a livrat un produs final care ne-a depășit toate așteptările."</p>
                <h4>Cristian Mihai</h4>
                <small>Fondator, FreshEats</small>
            </div>
        </div>
      </section>

      <section id="contact">
        <h2 class="hidden">E timpul să-ți transformi ideile în realitate</h2>
        <p class="hidden">Contactează-mă astăzi pentru o discuție liberă despre proiectul tău. Vom găsi împreună cea mai bună soluție pentru tine, fără niciun fel de obligație.</p>
        <form class="hidden" action="https://formspree.io/f/mjkoeybv" method="POST">
          <div class="form-group">
            <label>Numele tău complet:</label><br />
            <input type="text" name="nume" required /><br />
            <span class="error-message">Acest câmp este obligatoriu.</span>
          </div>
          <div class="form-group">
            <label>Adresa ta de email:</label><br />
            <input type="email" name="email" required /><br />
            <span class="error-message">Acest câmp este obligatoriu și trebuie să fie un email valid.</span>
          </div>
          <div class="form-group">
            <label>Spune-mi despre proiectul tău:</label><br />
            <textarea name="mesaj" required></textarea><br />
            <span class="error-message">Acest câmp este obligatoriu.</span>
          </div>
          <button type="submit">Trimite mesajul</button>
        </form>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 MilloSite. Toate drepturile rezervate.</p>
    </footer>

    <button id="backToTop" title="Sus">↑</button>

    <script src="script.js"></script>
  </body>
</html>
document.addEventListener("DOMContentLoaded", () => {
  // Ascunde loader-ul după ce pagina s-a încărcat
  const loaderWrapper = document.getElementById("loader-wrapper");
  if (loaderWrapper) {
    loaderWrapper.style.opacity = '0';
    setTimeout(() => {
      loaderWrapper.style.display = 'none';
    }, 500);
  }

  // 1. Meniu Hamburger și Navigație Fluidă
  const hamburger = document.getElementById("hamburger");
  const menu = document.getElementById("menu");
  const sections = document.querySelectorAll("main section");
  const navLinks = document.querySelectorAll(".menu a");

  const changeSection = (targetId) => {
    sections.forEach(section => {
      section.classList.remove('visible');
      section.style.display = 'none';
      section.querySelectorAll('.hidden').forEach(el => el.classList.remove('visible'));
    });
    
    const targetSection = document.getElementById(targetId);
    if (targetSection) {
      targetSection.style.display = 'block';
      setTimeout(() => {
        targetSection.querySelectorAll('.hidden').forEach(el => el.classList.add('visible'));
      }, 50);
    }
  };

  const initialSection = 'acasa';
  changeSection(initialSection);

  navLinks.forEach(link => {
    link.addEventListener("click", (e) => {
      e.preventDefault();
      const targetId = link.getAttribute("href").substring(1);
      changeSection(targetId);
      if (menu.classList.contains("active")) {
        menu.classList.remove("active");
      }
    });
  });

  hamburger.addEventListener("click", () => {
    menu.classList.toggle("active");
  });

  // 2. Butonul "Înapoi sus"
  const backToTop = document.getElementById("backToTop");
  window.addEventListener("scroll", () => {
    if (window.scrollY > 300) {
      backToTop.classList.add("show");
    } else {
      backToTop.classList.remove("show");
    }
  });

  backToTop.addEventListener("click", () => {
    window.scrollTo({ top: 0, behavior: "smooth" });
  });

  // 3. Tema întunecată (Dark Mode)
  const themeSwitch = document.getElementById("theme-switch");
  const prefersDark = window.matchMedia("(prefers-color-scheme: dark)").matches;

  function applyTheme(isDark) {
    if (isDark) {
      document.body.classList.add("dark-mode");
      themeSwitch.checked = true;
    } else {
      document.body.classList.remove("dark-mode");
      themeSwitch.checked = false;
    }
    localStorage.setItem("dark-mode", isDark);
  }

  const savedTheme = localStorage.getItem("dark-mode");
  if (savedTheme !== null) {
    applyTheme(savedTheme === "true");
  } else {
    applyTheme(prefersDark);
  }

  themeSwitch.addEventListener("change", (e) => {
    applyTheme(e.target.checked);
  });

  // 4. Validarea Formularelor
  const forms = document.querySelectorAll('form');

  forms.forEach(form => {
    form.addEventListener('submit', function (e) {
      let isFormValid = true;
      const requiredInputs = form.querySelectorAll('input[required], textarea[required]');

      requiredInputs.forEach(input => {
        if (!input.value.trim()) {
          input.classList.add('invalid');
          isFormValid = false;
        } else {
          input.classList.remove('invalid');
        }
      });
      
      const emailInput = form.querySelector('input[type="email"]');
      if (emailInput && !emailInput.value.trim().match(/^[^@]+@\w+.\w+$/)) {
        emailInput.classList.add('invalid');
        isFormValid = false;
      } else if (emailInput) {
        emailInput.classList.remove('invalid');
      }

      if (!isFormValid) {
        e.preventDefault();
      }
    });
  });
});
/* Stiluri generale și resetare */
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #f8f9fa;
  --card-background-color: #ffffff;
  --text-color: #343a40;
  --header-color: #212529;
  --border-color: #dee2e6;
  --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  --error-color: #dc3545;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: 'Montserrat', sans-serif;
  line-height: 1.6;
  background-color: var(--background-color);
  color: var(--text-color);
  transition: background-color 0.3s, color 0.3s;
}

/* Stiluri pentru loader */
#loader-wrapper {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: var(--background-color);
  z-index: 1000;
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 1;
  transition: opacity 0.5s ease-out;
}

#loader {
  border: 8px solid var(--border-color);
  border-top: 8px solid var(--primary-color);
  border-radius: 50%;
  width: 60px;
  height: 60px;
  animation: spin 1s linear infinite;
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* Stiluri pentru Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: var(--card-background-color);
  box-shadow: var(--box-shadow);
  position: sticky;
  top: 0;
  z-index: 999;
}

.navbar .logo {
  font-size: 1.5rem;
  font-weight: 600;
  color: var(--header-color);
}

.navbar .menu {
  list-style: none;
  display: flex;
  align-items: center;
}

.navbar .menu li {
  margin-left: 1.5rem;
  position: relative;
}

.navbar .menu a {
  text-decoration: none;
  color: var(--text-color);
  font-weight: 400;
  padding: 0.5rem 0;
  display: block;
}

.navbar .menu a:hover {
  color: var(--primary-color);
}

.dropdown-content {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background-color: var(--card-background-color);
  box-shadow: var(--box-shadow);
  min-width: 150px;
  border-radius: 5px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown-content li {
  margin: 0;
}

.dropdown-content a {
  padding: 10px 15px;
  cursor: pointer;
}

.hamburger {
  display: none;
  font-size: 2rem;
  background: none;
  border: none;
  color: var(--text-color);
  cursor: pointer;
}

/* Stiluri pentru Comutator (Toggle Switch) */
.switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
  margin-left: 1rem;
  cursor: pointer;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: var(--secondary-color);
  transition: 0.4s;
  border-radius: 34px;
}

.slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  transition: 0.4s;
  border-radius: 50%;
}

input:checked + .slider {
  background-color: var(--primary-color);
}

input:checked + .slider:before {
  transform: translateX(26px);
}

/* Stiluri pentru secțiuni */
section {
  padding: 4rem 2rem;
  max-width: 1200px;
  margin: auto;
}

h2 {
  text-align: center;
  margin-bottom: 2rem;
  font-size: 2.5rem;
  color: var(--header-color);
}

/* Stiluri pentru carduri (proiecte) */
.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.card {
  background-color: var(--card-background-color);
  padding: 2rem;
  border-radius: 10px;
  box-shadow: var(--box-shadow);
  transition: transform 0.3s ease-in-out;
}

.card:hover {
  transform: translateY(-10px);
}

.card h3 {
  margin-bottom: 1rem;
  color: var(--primary-color);
}

/* Stiluri pentru formularul de contact */
form {
  display: flex;
  flex-direction: column;
  max-width: 600px;
  margin: 2rem auto;
  background-color: var(--card-background-color);
  padding: 2rem;
  border-radius: 10px;
  box-shadow: var(--box-shadow);
}

form label {
  margin-top: 1rem;
  font-weight: 600;
}

form input, form textarea, form select {
  width: 100%;
  padding: 0.75rem;
  margin-top: 0.5rem;
  border: 1px solid var(--border-color);
  border-radius: 5px;
  font-family: 'Montserrat', sans-serif;
  transition: border-color 0.3s ease, box-shadow 0.3s ease;
}

form input:focus, form textarea:focus, form select:focus {
  outline: none;
  border-color: var(--primary-color);
  box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
}

form button {
  margin-top: 1.5rem;
  padding: 0.75rem;
  background-color: var(--primary-color);
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

form button:hover {
  background-color: #0056b3;
}

/* Stiluri pentru validare */
.form-group {
  position: relative;
}

.form-group input.invalid,
.form-group textarea.invalid {
  border-color: var(--error-color);
}

.form-group .error-message {
  color: var(--error-color);
  font-size: 0.8rem;
  margin-top: 0.25rem;
  display: none;
}

.form-group input.invalid ~ .error-message,
.form-group textarea.invalid ~ .error-message {
  display: block;
}


/* Stiluri pentru footer */
footer {
  text-align: center;
  padding: 2rem;
  background-color: var(--card-background-color);
  color: var(--secondary-color);
}

/* Stiluri pentru butonul back to top */
#backToTop {
  display: none;
  position: fixed;
  bottom: 2rem;
  right: 2rem;
  z-index: 99;
  width: 50px;
  height: 50px;
  background-color: var(--primary-color);
  color: white;
  border: none;
  border-radius: 50%;
  font-size: 1.8rem;
  line-height: 50px;
  text-align: center;
  cursor: pointer;
  box-shadow: var(--box-shadow);
  transition: all 0.3s ease-in-out;
  opacity: 0;
  transform: scale(0.9);
}

#backToTop.show {
  opacity: 1;
  transform: scale(1);
  display: block;
}

#backToTop:hover {
  background-color: #0056b3;
  transform: scale(1.1);
}

/* Stiluri pentru animații fluide */
.hidden {
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.8s ease-in-out, transform 0.8s ease-in-out;
}

.visible {
  opacity: 1;
  transform: translateY(0);
}

/* Stiluri pentru Dark Mode */
body.dark-mode {
  --background-color: #121212;
  --card-background-color: #1e1e1e;
  --text-color: #f1f1f1;
  --header-color: #ffffff;
  --border-color: #333333;
}

body.dark-mode .navbar {
  box-shadow: 0 4px 6px rgba(255, 255, 255, 0.1);
}

body.dark-mode .card, body.dark-mode form {
  box-shadow: 0 4px 6px rgba(255, 255, 255, 0.1);
}

body.dark-mode .slider {
  background-color: #555;
}

body.dark-mode input:checked + .slider {
  background-color: #2196F3;
}

/* Media Queries pentru a face site-ul responsive */
@media (max-width: 768px) {
  .navbar .menu {
    display: none;
    flex-direction: column;
    width: 100%;
    position: absolute;
    top: 60px;
    left: 0;
    background-color: var(--card-background-color);
    box-shadow: var(--box-shadow);
  }

  .navbar .menu.active {
    display: flex;
  }

  .navbar .menu li {
    margin: 0;
    width: 100%;
    text-align: center;
    border-bottom: 1px solid var(--border-color);
  }
  
  .navbar .menu li:last-child {
    border-bottom: none;
  }

  .dropdown-content {
    position: static;
    box-shadow: none;
    text-align: center;
  }

  .dropdown:hover .dropdown-content {
    display: block;
  }

  .hamburger {
    display: block;
  }

  h2 {
    font-size: 2rem;
  }
}

/* Stiluri pentru secțiunea Acasa (Hero) */
#acasa {
    background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('background.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: white;
    min-height: 80vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 4rem 2rem;
}

#acasa h2 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: white;
}

#acasa p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
    color: white;
}

.benefits-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-bottom: 3rem;
    text-align: left;
}

.benefit-item {
    padding: 1.5rem;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 10px;
    box-shadow: var(--box-shadow);
    transition: transform 0.3s ease;
    color: white;
}

.benefit-item:hover {
    transform: translateY(-5px);
}

.benefit-item h3 {
    color: var(--primary-color);
    margin-bottom: 0.5rem;
    font-size: 1.3rem;
}

.benefit-item i {
    font-size: 2rem;
    margin-right: 1rem;
    vertical-align: middle;
}

.cta-button {
    background-color: transparent;
    color: white;
    text-decoration: none;
    border: 2px solid white;
    border-radius: 5px;
    font-weight: 600;
    transition: background-color 0.3s ease, border-color 0.3s ease;
}

.cta-button:hover {
    background-color: var(--primary-color);
    border-color: var(--primary-color);
}

/* Stiluri pentru sectiunea 'start-project' */
#start-project {
    background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('birou.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: white;
    text-align: center;
    border-radius: 10px;
    padding: 4rem 2rem;
}

#start-project h2, #start-project p {
    color: white;
}

#start-project form {
    max-width: 800px;
    background-color: rgba(255, 255, 255, 0.1);
    padding: 2rem;
    border-radius: 10px;
    box-shadow: var(--box-shadow);
    margin: 2rem auto;
}

#start-project label {
    font-weight: 600;
    color: white;
}

#start-project input, #start-project textarea, #start-project select {
    background-color: rgba(255, 255, 255, 0.1);
    border: 1px solid rgba(255, 255, 255, 0.3);
    color: white;
}

#start-project button {
    background-color: var(--primary-color);
    color: white;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

#start-project button:hover {
    background-color: #0056b3;
}

/* Stiluri pentru secțiunea Blog */
#blog {
    background-color: var(--background-color);
}

.blog-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.blog-post {
    background-color: var(--card-background-color);
    border-radius: 10px;
    overflow: hidden;
    box-shadow: var(--box-shadow);
    transition: transform 0.3s ease-in-out;
}

.blog-post:hover {
    transform: translateY(-5px);
}

.blog-post img {
    width: 100%;
    height: auto;
    display: block;
}

.blog-post-content {
    padding: 1.5rem;
}

.blog-post h3 {
    margin-top: 0;
    font-size: 1.5rem;
    color: var(--header-color);
}

.blog-post small {
    display: block;
    margin-bottom: 1rem;
    color: var(--secondary-color);
}

.blog-post p {
    margin-bottom: 1rem;
}

.blog-post a {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
}

.blog-post a:hover {
    color: #0056b3;
}

body.dark-mode .blog-post {
    background-color: #1a1a1a;
}
/* Stiluri pentru secțiunea Testimoniale */
#testimoniale {
    background-color: var(--card-background-color);
}

.testimoniale-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
}

.testimonial-card {
    background-color: var(--background-color);
    padding: 2rem;
    border-radius: 10px;
    box-shadow: var(--box-shadow);
    text-align: center;
    transition: transform 0.3s ease;
}

body.dark-mode .testimonial-card {
  background-color: #1a1a1a;
}

.testimonial-card:hover {
    transform: translateY(-5px);
}

.testimonial-card p {
    font-style: italic;
    margin-bottom: 1rem;
    color: var(--text-color);
}

.testimonial-card h4 {
    color: var(--primary-color);
    margin-bottom: 0.25rem;
}

.testimonial-card small {
    color: var(--secondary-color);
}
