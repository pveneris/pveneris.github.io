---
layout: custom
title: ""
permalink: /
---

<style>

/* ==================================================
   PROFILE
   ================================================== */

.profile-section {
  display: flex;
  align-items: center;
  gap: 36px;
  margin-top: 0;
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
  margin-bottom: 14px;
  color: #e6e6e6;
}


/* ==================================================
   PROFILE LINKS
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
   RESEARCH INTERESTS
   ================================================== */

.section-title {
  margin-top: 48px;
  margin-bottom: 20px;
  border-bottom: none !important;
  padding-bottom: 0 !important;
  color: #ffd700 !important;
  font-weight: 600;
}

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

}

</style>


<div class="home-container">

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

      <div class="profile-links">

        <a href="mailto:pveneris@hotmail.gr" title="Email">
          <i class="fas fa-envelope"></i>
        </a>

        <a
          href="YOUR_GOOGLE_SCHOLAR_URL"
          title="Google Scholar"
          target="_blank"
        >
          <i class="fas fa-graduation-cap"></i>
        </a>

        <a
          href="https://x.com/PanagiotisVene1"
          title="Twitter / X"
          target="_blank"
        >
          <i class="fab fa-twitter"></i>
        </a>

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
