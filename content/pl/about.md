---
title: "O mnie"
---

<style>
  /* Dodajemy ogólny styl dla kontenera, by uniknąć konfliktów z markdown-body */
  .cv-section-content ul {
    list-style: disc; /* Przywracamy kropki, bo były nadpisywane */
    padding-left: 20px;
    margin-bottom: 30px; /* Dodaje odstęp między sekcjami */
  }

  .cv-section-content li {
    margin-bottom: 8px; /* Zmniejsza odstęp między punktami listy */
  }

  /* Usunięte spacje po pojedynczych literach w CSS, by replaceRE ich nie popsuł */
  .cv-style-header {
    display:block;
    border-bottom:1px solid var(--gorska-zielen);
    margin-top:35px;
    margin-bottom:15px;
    font-size:1.1em;
    font-weight:bold;
    text-transform:uppercase;
    letter-spacing:0.5px;
    color:var(--gorska-zielen);
  }

  /* Pancerne pudełko teraz działa wewnątrz listy LI */
  .flex-row {
    display:flex !important;
    flex-wrap:wrap;
    align-items:baseline;
    gap:0 10px;
    /* Usunięto margin-bottom, bo mamy margin-bottom na li */
  }
  
  .no-wrap { white-space:nowrap; }

  .skills-grid {
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:30px;
    margin-top:10px;
  }

  .cv-link {
    color:var(--gorska-zielen);
    text-decoration:none;
    border-bottom:1px dotted var(--gorska-zielen);
  }

  @media (max-width:600px) {
    .skills-grid { grid-template-columns:1fr; gap:10px; }
  }
</style>

<span class="cv-style-header">Wykształcenie</span>

<div class="cv-section-content">
  <ul>
    <li>
      <div class="flex-row">
        <strong>Studia doktoranckie</strong> <span class="no-wrap">| 1 października 2021 – obecnie</span>
      </div>
      <ul>
        <li>dyscyplina: nauki fizyczne</li>
        <li>
          <!-- Zagnieżdżony flex-row wewnątrz LI -->
          <div class="flex-row">
            <a href="https://www.ift.pwr.edu.pl" class="cv-link" target="_blank">Instytut Fizyki Teoretycznej</a> <span class="no-wrap">| Politechnika Wrocławska</span>
          </div>
        </li>
        <li>7 stycznia 2026 r. — <a href="https://bip.pwr.edu.pl" class="cv-link" target="_blank">złożenie rozprawy doktorskiej</a></li>
        <li>tytuł pracy: *Rezonansowa fluorescencja emitera kwantowego w&nbsp;ciele stałym z&nbsp;fluktuacjami energii przejścia*</li>
        <li>promotor: <a href="https://pm.kft.pwr.edu.pl" class="cv-link" target="_blank"><strong>prof. dr hab. inż. Paweł Machnikowski</strong></a></li>
      </ul>
    </li>
    <!-- Resztę wykształcenia (magisterka, inżynierka) musisz ustrukturyzować analogicznie, 
         opakowując każdy blok lat/uczelni w jeden nadrzędny znacznik <li> -->
  </ul>
</div>

<span class="cv-style-header">Doświadczenie</span>

<div class="cv-section-content">
  <ul>
    <li>
      <div class="flex-row">
        <a href="https://www.cft.edu.pl" class="cv-link" target="_blank"><strong>Centrum Fizyki Teoretycznej Polskiej Akademii Nauk</strong></a> <span class="no-wrap">| 2 września 2019 – 27 września 2019</span>
      </div>
      <ul>
        <li>staż naukowy — teoretyczne badania nad splątaniem kwantowym</li>
        <li>opiekun: <a href="https://raugusiak.weebly.com" class="cv-link" target="_blank"><strong>dr hab. inż. Remigiusz Augusiak, prof. CFT PAN</strong></a></li>
      </ul>
    </li>
    <li>
      <div class="flex-row">
        <a href="https://www.ift.pwr.edu.pl" class="cv-link" target="_blank"><strong>Instytut Fizyki Teoretycznej Politechniki Wrocławskiej</strong></a> <span class="no-wrap">| marzec 2019 – obecnie</span>
      </div>
      <ul>
         <li>współpraca badawcza z&nbsp;**prof. drem hab. inż. Pawłem Machnikowskim** w&nbsp;zakresie optyki kwantowej ciała stałego</li>
      </ul>
    </li>
  </ul>
</div>

<span class="cv-style-header">Granty</span>
<!-- ... (tutaj analogicznie zorganizuj resztę grantów w strukturę <li> + <ul>) ... -->

<span class="cv-style-header">Umiejętności</span>
<!-- ... (tutaj struktura skills-grid może zostać bez zmian, działa poprawnie) ... -->
