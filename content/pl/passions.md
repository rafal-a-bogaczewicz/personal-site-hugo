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
    color: var(--gorska-zielen);
  }

  /* Układ siatki dla zdjęć */
  .passions-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-bottom: 30px;
  }
  
  .passions-grid-alt {
    display: grid;
    gap: 30px;
    align-items: center;
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
  @media (max-width: 600px) {
    .passions-grid, .passions-grid-alt {
      grid-template-columns: 1fr !important;
    }
    .passions-grid-alt img { order: 2; }
    .passions-grid-alt div { order: 1; }
  }
</style>

<p style="text-align: center; font-size: 1.1em; margin-bottom: 15px; color: var(--text-color);">
    Nie samą fizyką kwantową żyje <i>pasjonat odkrywania świata</i>. 
</p>

<p style="text-align: center; font-size: 1.05em; margin-bottom: 40px; color: var(--gray-quote); font-style: italic;">
    Poniższe zainteresowania to inne ścieżki zgłębiania rzeczywistości i&nbsp;zachwytu nad&nbsp;jej pięknem.
</p>

<span class="cv-style-header">Podróże i zwiedzanie ciekawych miejsc</span>

<div class="values-header" style="margin-top: 10px; margin-bottom: 25px;">
    <div class="quote-text">Kto podróżował, pełen jest zaradności, a kto ma wielkie doświadczenie, mądrze przemawiać będzie.</div>
    <div class="quote-ref">— <b>Syr 34, 9</b></div>
</div>

<div class="passions-grid">
    <div class="passion-item">
        <img src="/images/sansebastian.webp" alt="San Sebastian" class="img-responsive">
        <p class="img-caption">
            San Sebastian — zwiedzanie miasta po 
            <a href="/conferences/" class="pub-link">konferencji (nr 1)</a>.
        </p>
    </div>
    <div class="passion-item">
        <img src="/images/lot.webp" alt="Zatoka Biskajska" class="img-responsive">
        <p class="img-caption">Widok na Zatokę Biskajską w drodze powrotnej.</p>
    </div>
</div>

<span class="cv-style-header">Rower i góry</span>
<p>Trening charakteru, samodyscypliny i&nbsp;pokory wobec sił natury. Cisza szczytów to przestrzeń niezbędna do&nbsp;pracy intelektualnej.</p>

<div class="passions-grid-alt" style="grid-template-columns: 1fr 1.2fr;">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Ląd i wytrzymałość</h4>
        <p>Rower oraz góry to droga do&nbsp;samokontroli i&nbsp;budowania wewnętrznej dyscypliny.</p>
    </div>
    <img src="/images/gory.jpg" alt="Góry" class="img-responsive">
</div>

<span class="cv-style-header">Pływanie i snorkeling</span>
<p>Odkrywanie złożoności podwodnego świata i&nbsp;zachwyt nad&nbsp;precyzją stworzenia.</p>

<div class="passions-grid-alt" style="grid-template-columns: 1.2fr 1fr;">
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
