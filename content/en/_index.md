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

  /* LOGO IFT: Shadow added to make white elements visible on light background */
  .logo-ift {
    filter: drop-shadow(0px 0px 2px rgba(0,0,0,0.5));
  }

  /* DARK MODE */
  /* PWr logo remains unchanged (original colors) */
  [data-theme="dark"] .logo-pwr {
    filter: none;
  }

  /* IFT logo in dark mode - increased brightness for readability of 'I' and dot */
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
        <img src="/images/logopwr.png" alt="WUST Logo" class="uni-logo-img logo-pwr">
    </a>
    <a href="https://www.kft.pwr.edu.pl" target="_blank">
        <img src="/images/logoift.png" alt="IFT Logo" class="uni-logo-img logo-ift">
    </a>
  </div>

  <div class="intro-text">
    Hi, I am a theoretical physicist, a PhD student at the <a href="https://www.kft.pwr.edu.pl" class="pub-link" target="_blank">Institute of Theoretical Physics (WUST)</a>.
    <br><br>
    I work in the scientific group of <a href="https://pm.kft.pwr.edu.pl" class="pub-link" target="_blank">prof.&nbsp;Paweł Machnikowski</a>.
  </div>
</div>

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Scientific interests</span>

*   solid-state quantum optics
*   decoherence and phonon dynamics in quantum systems
*   open quantum systems

<span class="cv-style-header" style="display: block; border-bottom: 1px solid var(--gorska-zielen); margin-top: 35px; margin-bottom: 15px; font-size: 1.1em; font-weight: bold; text-transform: uppercase; letter-spacing: 0.5px;">Contact and scientific profiles</span>

**e-mail:** rafal.bogaczewicz<span>@</span>pwr.edu.pl

<a href="https://orcid.org" class="pub-link" target="_blank">ORCID</a> | <a href="https://www.researchgate.net" class="pub-link" target="_blank">ResearchGate</a> | <a href="https://pwr-wroc.academia.edu" class="pub-link" target="_blank">Academia.edu</a> | <a href="https://www.linkedin.com" class="pub-link" target="_blank">LinkedIn</a>

Institute of Theoretical Physics | Wrocław University of Science and Technology

Wybrzeże Wyspiańskiego 27, 50-370 Wrocław, Poland
