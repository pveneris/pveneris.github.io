---
layout: splash
title: ""
permalink: /
---

<style>

/* ==================================================
   GLOBAL DARK THEME
   ================================================== */

html,
body {
  background-color: #000 !important;
  color: #e6e6e6 !important;
}

#main,
.page,
.page__inner-wrap,
.page__content,
.initial-content {
  background-color: #000 !important;
}

/* Hide original theme navigation */
.masthead {
  display: none !important;
}

/* General links */
.page__content a {
  color: #4da3c7;
  text-decoration: none;
}

.page__content a:hover {
  color: #79c4e3;
  text-decoration: none;
}

/* Horizontal rules */
hr {
  border: 0;
  border-top: 1px solid #333 !important;
}


/* ==================================================
   CUSTOM TOP NAVIGATION
   ================================================== */

.custom-nav {
  width: 100%;
  background-color: #000;
  border-bottom: 1px solid #333;
}

.custom-nav-inner {
  max-width: 930px;
  height: 70px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.custom-nav-name {
  color: #ffffff !important;
  font-size: 1.05em;
  font-weight: 700;
  text-decoration: none !important;
}

.custom-nav-links {
  display: flex;
  align-items: center;
  gap: 35px;
}

.custom-nav-links a {
  color: #ffffff !important;
  text-decoration: none !important;
  font-size: 0.85em;
  font-weight: 600;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  padding: 10px 8px;
}

/* Yellow when hovering */
.custom-nav-links a:hover {
  color: #ffd700 !important;
}

/* Yellow for the currently selected page */
.custom-nav-links a.active {
  color: #ffd700 !important;
}


/* ==================================================
   MAIN HOMEPAGE CONTAINER
   ================================================== */

.home-container {
  max-width: 930px;
  margin: 0 auto;
}


/* ==================================================
   PROFILE
   ================================================== */

.profile-section {
  display: flex;
  align-items: center;
  gap: 36px;
  margin-top: 45px;
  margin-bottom: 30px;
}

.profile-photo {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%;
  flex-shrink: 0;
}

.profile-info h1 {
  margin: 0 0 10px 0;
  color: #ffffff !important;
  font-weight: 700;
}

.profile-position {
  font-size: 1.05em;
  margin-bottom: 6px;
  color: #e6e6e6;
}

.profile-fields {
  font-size: 1em;
  color: #b8b8b8;
  margin-bottom: 18px;
}


/* ==================================================
   PROFILE LINKS / ICONS
   ================================================== */

.profile-links {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 28px;
  font-size: 1.25em;
}

.profile-links a {
  color: #4da3c7;
  text-decoration: none;
}

.profile-links a:hover {
  color: #79c4e3;
  text-decoration: none;
}

.cv-group {
  display: flex;
  align-items: center;
  gap: 4px;
}

.cv-box {
  border: 2px solid #4da3c7;
  padding: 1px 7px;
  border-radius: 6px;
  font-size: 0.65em;
  font-weight: 600;
  text-decoration: none;
}


/* ==================================================
   BIO
   ================================================== */

.bio-section {
  max-width: 900px;
  line-height: 1.65;
  text-align: justify;
  margin-top: 20px;
}

.bio-section p {
  color: #e6e6e6;
  font-size: 0.95em;
  margin-top: 14px;
}


/* ==================================================
   SECTION HEADINGS
   ================================================== */

.section-title {
  margin-top: 48px;
  margin-bottom: 20px;
  border-bottom: none !important;
  padding-bottom: 0 !important;
  color: #ffd700 !important;
  font-weight: 600;
}


/* ==================================================
   RESEARCH INTERESTS
   ================================================== */

.interests-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 12px 60px;
  margin-bottom: 50px;
}

.interest-item {
  color: #e6e6e6;
  font-size: 0.98em;
}



/* ==================================================
   MOBILE
   ================================================== */

@media (max-width: 700px) {

  .custom-nav-inner {
    padding: 0 18px;
  }

  .custom-nav-links {
    gap: 12px;
  }

  .custom-nav-links a {
    font-size: 0.68em;
  }

  .custom-nav-name {
    font-size: 0.88em;
  }

  .home-container {
    width: auto;
    margin-left: 18px;
    margin-right: 18px;
  }

  .profile-section {
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
  }

  .profile-photo {
    width: 145px;
    height: 145px;
  }

  .interests-grid {
    grid-template-columns: 1fr;
  }

  .feature-grid {
    grid-template-columns: 1fr;
    gap: 30px;
  }

}

</style>


<!-- ==================================================
     TOP NAVIGATION
     ================================================== -->

<nav class="custom-nav">

  <div class="custom-nav-inner">

    <a href="/" class="custom-nav-name">
      Panagiotis Veneris
    </a>

    <div class="custom-nav-links">

      <a href="/"
         class="{% if page.url == '/' %}active{% endif %}">
        Home
      </a>

      <a href="/research/"
         class="{% if page.url == '/research/' %}active{% endif %}">
        Research
      </a>

      <a href="/publications/"
         class="{% if page.url == '/publications/' %}active{% endif %}">
        Publications
      </a>

      <a href="/teaching/"
         class="{% if page.url == '/teaching/' %}active{% endif %}">
        Teaching
      </a>

      <a href="/files/Veneris_CV.pdf" target="_blank">
        Vitae
      </a>

    </div>

  </div>

</nav>


<!-- ==================================================
     MAIN CONTENT
     ================================================== -->

<div class="home-container">


<!-- ==================================================
     PROFILE
     ================================================== -->

<div class="profile-section">

  <img
    src="/images/panosven_picture.png"
    alt="Panagiotis Veneris"
    class="profile-photo"
  >

  <div class="profile-info">

    <h1>Panagiotis Veneris</h1>

    <div class="profile-position">
      PhD in Economics, University of Liverpool
    </div>

    <!-- ICONS -->

    <div class="profile-links">

      <!-- Email -->

      <a
        href="mailto:pveneris@hotmail.gr"
        title="Email"
      >
        <i class="fas fa-envelope"></i>
      </a>


      <!-- Google Scholar -->

      <a
        href="YOUR_GOOGLE_SCHOLAR_URL"
        title="Google Scholar"
        target="_blank"
      >
        <i class="fas fa-graduation-cap"></i>
      </a>


      <!-- Twitter -->

      <a
        href="https://x.com/PanagiotisVene1"
        title="Twitter / X"
        target="_blank"
      >
        <i class="fab fa-twitter"></i>
      </a>


      <!-- GitHub -->

      <a
        href="https://github.com/pveneris/NumericalMethods"
        title="GitHub"
        target="_blank"
      >
        <i class="fab fa-github"></i>
      </a>

    </div>

  </div>

</div>


<hr>


<!-- ==================================================
     BIO
     ================================================== -->

<div class="bio-section">

  <p>
    Hi, and welcome! I am on the job market.
  </p>

  <p>
    My research interests lie in the area of quantitative macroeconomics,
    with a special interest in monetary policy, macro-finance, and
    international economics. In my research, I develop general equilibrium
    models to quantify the effects of central bank policies on aggregate
    outcomes.
  </p>

  <p>
    I recently completed my PhD in Economics at the University of Liverpool,
    supervised by
    <a
      href="https://sites.google.com/site/oliverdegroot/"
      target="_blank"
    >
      Oliver de Groot
    </a>
    and
    <a
      href="https://luhan.io/"
      target="_blank"
    >
      Lu Han
    </a>.
  </p>

  <p>
    Over the years, I have conducted research at the Bank of Greece,
    the European Central Bank, and the Bank of Lithuania.
  </p>

</div>


<!-- ==================================================
     RESEARCH INTERESTS
     ================================================== -->

<h2 class="section-title">
  Research Interests
</h2>


<div class="interests-grid">

  <div class="interest-item">
    Quantitative Macroeconomics
  </div>

  <div class="interest-item">
    Monetary Economics
  </div>

  <div class="interest-item">
    Macro-Finance
  </div>

  <div class="interest-item">
    Monetary Policy
  </div>

  <div class="interest-item">
    International Economics
  </div>

  <div class="interest-item">
    Financial Frictions
  </div>

</div>

</div>
