---
title: "Pasje"
date: 2026-01-18
slug: "passions"
---

<style>
  /* STYL SPÓJNY Z HOME ORAZ ABOUT */
  .cv-style-header {
    display: block;
    border-bottom: 1px solid var(--gorska-zielen);
    margin-top: 35px;
    margin-bottom: 15px;
    font-size: 1.1em;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    color: var(--text-color);
  }

  /* Układ siatki dla sekcji Podróże */
  .passions-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-bottom: 30px;
  }
  
  /* Układ dwukolumnowy: ROWER | GÓRY */
  .passion-split-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
    margin-bottom: 40px;
    margin-top: 20px;
  }

  .img-responsive {
    width: 100%;
    height: auto;
    border-radius: 8px;
    border: 1px solid var(--gorska-zielen);
    display: block;
  }

  .img-caption {
    font-size: 0.85em;
    font-style: italic;
    margin-top: 8px;
    color: var(--gray-quote);
    text-align: center;
  }

  /* Responsywność dla urządzeń mobilnych */
  @media (max-width: 800px) {
    .passions-grid, .passion-split-grid {
      grid-template-columns: 1fr !important;
      gap: 30px;
    }
  }
</style>

<!-- Scalone zdanie wyrównane do lewej -->
<p style="text-align: left; font-size: 1.1em; margin-bottom: 40px; color: var(--text-color);">
    Nie samą fizyką kwantową żyje <i>pasjonat odkrywania świata</i> — poniższe zainteresowania to inne ścieżki zgłębiania rzeczywistości i&nbsp;zachwytu nad&nbsp;jej pięknem.
</p>

<span class="cv-style-header">Podróże do ciekawych miejsc</span>

<div class="values-header" style="margin-top: 10px; margin-bottom: 25px;">
    <div class="quote-text">Kto podróżował, pełen jest zaradności, a kto ma wielkie doświadczenie, mądrze przemawiać będzie.</div>
    <div class="quote-ref">— <b>Syr 34, 9</b></div>
</div>

<div class="passions-grid">
    <div class="passion-item">
        <img src="/images/sansebastian.webp" alt="San Sebastián o zmierzchu" class="img-responsive">
        <p class="img-caption">
            Zwiedzanie San Sebastián po 
            <a href="/conferences/#conf-2024-07-22" class="pub-link">konferencji</a>.
        </p>
    </div>
    <div class="passion-item">
        <img src="/images/lot.webp" alt="Widok na Zatokę Biskajską z lotu ptaka" class="img-responsive">
        <p class="img-caption">Widok na Zatokę Biskajską w drodze powrotnej.</p>
    </div>
</div>

<!-- Sekcja dwukolumnowa: ROWER | GÓRY -->
<div class="passion-split-grid">
  <div>
    <span class="cv-style-header" style="margin-top: 0;">Rower</span>
    <p>Długie dystanse w&nbsp;dolinie Odry oraz trasy przez dolnośląskie niziny to dla mnie trening rytmu i&nbsp;wytrzymałości.</p>
    <img src="/images/rower.jpg" alt="Wyprawa rowerowa - tabliczka Węgry" class="img-responsive">
    <p class="img-caption">Odkrywanie świata tuż obok — wyprawa na Węgry (dolnośląskie).</p>
  </div>
  <div>
    <span class="cv-style-header" style="margin-top: 0;">Góry</span>
    <p>Beskidzkie szlaki i&nbsp;cisza szczytów to przestrzeń niezbędna do&nbsp;pracy intelektualnej i&nbsp;budowania charakteru.</p>
    <img src="/images/gory.jpg" alt="Beskidy" class="img-responsive">
    <p class="img-caption">Moment kontemplacji na&nbsp;szlaku.</p>
  </div>
</div>

<span class="cv-style-header">Pływanie i snorkeling</span>
<p>Odkrywanie złożoności podwodnego świata i&nbsp;zachwyt nad&nbsp;precyzją stworzenia.</p>

<div style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px; align-items: center; margin-bottom: 40px; margin-top: 20px;">
    <img src="/images/rafa.jpg" alt="Rafa koralowa" class="img-responsive">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Uważność i detal</h4>
        <p>Eksploracja podwodnego świata uczy dostrzegania systemów, które na&nbsp;pierwszy rzut oka pozostają ukryte.</p>
    </div>
</div>

<span class="cv-style-header">Oczarowanie tajemnicą</span>
<p>Mam też inne pasje, ale...</p>

<div class="values-header" style="margin-top: 30px; margin-bottom: 50px;">
    <div class="quote-text">Najpiękniejszą rzeczą, jakiej możemy doświadczyć, jest oczarowanie tajemnicą.</div>
    <div class="quote-ref">— <b>Albert Einstein</b></div>
</div>
