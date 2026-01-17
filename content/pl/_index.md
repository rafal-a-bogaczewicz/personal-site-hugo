---
title: ""
---

<style>
  .intro-container {
    display: flex;
    flex-direction: row;
    gap: 30px;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .uni-logos {
    display: flex;
    gap: 20px;
    align-items: center;
    flex-shrink: 0;
  }

  .intro-text {
    flex: 1;
  }

  .uni-logo-img {
    height: 55px; 
    width: auto;
    transition: all 0.3s ease;
  }

  /* LOGO IFT: Dodajemy poświatę (cień), żeby białe elementy były widoczne na jasnym tle */
  .logo-ift {
    filter: drop-shadow(0px 0px 2px rgba(0,0,0,0.5));
  }

  /* TRYB CIEMNY */
  /* Logo PWR zostaje bez zmian (oryginalne barwy) */
  [data-theme="dark"] .logo-pwr {
    filter: none;
  }

  /* Logo IFT w trybie ciemnym - podbijamy jasność, by kropka i "I" były czytelne, ale nie odwracamy kolorów */
  [data-theme="dark"] .logo-ift {
    filter: drop-shadow(0px 0px 2px rgba(255,255,255,0.3)) brightness(1.2);
  }

  @media (max-width: 800px) {
    .intro-container {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    .uni-logos {
      margin-bottom: 10px;
    }
    .intro-text {
        text-align: left;
    }
  }
</style>

<div class="intro-container">
  <div class="uni-logos">
    <a href="https://pwr.edu.pl" target="_blank">
        <img src="/images/logopwr.png" alt="Logo PWr" class="uni-logo-img logo-pwr">
    </a>
    <a href="https://www.kft.pwr.edu.pl" target="_blank">
        <img src="/images/logoift.png" alt="Logo IFT" class="uni-logo-img logo-ift">
    </a>
  </div>

  <div class="intro-text">
    Cześć, jestem fizykiem teoretykiem, doktorantem w&nbsp;<a href="https://www.kft.pwr.edu.pl" class="pub-link" target="_blank">Instytucie Fizyki Teoretycznej PWr</a>.
    <br><br>
    Pracuję w&nbsp;grupie naukowej <a href="https://pm.kft.pwr.edu.pl" class="pub-link" target="_blank">prof.&nbsp;Pawła Machnikowskiego</a>.
  </div>
</div>

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Zainteresowania naukowe</span>

*   Optyka kwantowa ciała stałego
*   Dekoherencja i&nbsp;dynamika fononowa w&nbsp;układach kwantowych
*   Kwantowe układy otwarte

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Kontakt i profile naukowe</span>

**e-mail:** rafal.bogaczewicz<span>@</span>pwr.edu.pl

<a href="https://orcid.org" class="pub-link" target="_blank">ORCID</a> | <a href="https://www.researchgate.net" class="pub-link" target="_blank">ResearchGate</a> | <a href="https://pwr-wroc.academia.edu" class="pub-link" target="_blank">Academia.edu</a> | <a href="https://pl.linkedin.com" class="pub-link" target="_blank">LinkedIn</a>

Instytut Fizyki Teoretycznej | Politechnika Wrocławska
