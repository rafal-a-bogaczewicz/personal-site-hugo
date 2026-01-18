---
title: "Pasje"
date: 2026-01-18
slug: "passions"
---

<p style="text-align: center; font-size: 1.1em; margin-bottom: 40px; color: var(--text-color);">
    Nie samą fizyką teoretyczną żyje <i>pasjonat odkrywania świata</i>, lecz ma też inne zainteresowania:
</p>

<h3 class="section-title">PODRÓŻE I ZWIEDZANIE CIEKAWYCH MIEJSC</h3>

<div class="values-header" style="margin-top: 10px; margin-bottom: 25px;">
    <div class="quote-text">„Kto podróżował, pełen jest zaradności, a kto ma wielkie doświadczenie, mądrze przemawiać będzie.”</div>
    <div class="quote-ref"><b>Syr 34, 9</b></div>
</div>

<!-- SEKCJA FOTO: RESPONSYWNY GRID -->
<div class="passions-grid">
    <div class="passion-item">
        <img src="/images/sansebastian.webp" alt="San Sebastian o zmierzchu" class="img-responsive">
        <p class="img-caption">
            San Sebastian — zwiedzanie miasta po 
            <a href="/conferences/#conf-1" class="pub-link">konferencji (nr 1)</a>.
        </p>
    </div>
    <div class="passion-item">
        <img src="/images/lot.webp" alt="Zatoka Biskajska z lotu ptaka" class="img-responsive">
        <p class="img-caption">
            Widok na Zatokę Biskajską w drodze powrotnej.
        </p>
    </div>
</div>

<h3 class="section-title">ROWER I GÓRY</h3>
<p>Trening charakteru, samodyscypliny i pokory wobec sił natury. Cisza szczytów to przestrzeń niezbędna do pracy intelektualnej.</p>

<div class="passions-grid-alt" style="display: grid; grid-template-columns: 1fr 1.2fr; gap: 30px; align-items: center; margin-bottom: 40px; margin-top: 20px;">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Ląd i wytrzymałość</h4>
        <p>Rower oraz góry to droga do samokontroli i budowania wewnętrznej dyscypliny.</p>
    </div>
    <img src="/images/gory.jpg" alt="Góry" class="img-responsive">
</div>

<h3 class="section-title">PŁYWANIE I SNORKELING</h3>
<p>Odkrywanie złożoności podwodnego świata i zachwyt nad precyzją stworzenia.</p>

<div class="passions-grid-alt" style="display: grid; grid-template-columns: 1.2fr 1fr; gap: 30px; align-items: center; margin-bottom: 40px; margin-top: 20px;">
    <img src="/images/rafa.jpg" alt="Rafa koralowa" class="img-responsive">
    <div>
        <h4 style="color: var(--gorska-zielen); margin-top: 0;">Uważność i detal</h4>
        <p>Eksploracja podwodnego świata uczy dostrzegania systemów, które na pierwszy rzut oka pozostają ukryte.</p>
    </div>
</div>

### Oczarowanie tajemnicą

Mam też inne pasje, ale...

<div class="values-header" style="margin-top: 30px;">
    <div class="quote-text">„Najpiękniejszą rzeczą, jakiej możemy doświadczyć, jest oczarowanie tajemnicą.”</div>
    <div class="quote-ref"><b>Albert Einstein</b></div>
</div>

<style>
    /* Nowa klasa dla tytułów sekcji z zieloną linią */
    .section-title {
        color: var(--gorska-zielen);
        border-bottom: 3px solid var(--gorska-zielen);
        padding-bottom: 5px;
        margin-top: 40px;
        margin-bottom: 20px;
        text-transform: uppercase;
        font-size: 1.2rem;
        letter-spacing: 1px;
    }

    .passions-grid {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
        margin-bottom: 30px;
    }
    
    .img-responsive {
        width: 100%;
        height: auto;
        border-radius: 8px;
        border: 3px solid var(--gorska-zielen);
        display: block;
    }

    .img-caption {
        font-size: 0.85em;
        font-style: italic;
        margin-top: 8px;
        color: var(--gray-quote);
        text-align: center;
    }

    @media (max-width: 600px) {
        .passions-grid, .passions-grid-alt {
            grid-template-columns: 1fr !important;
        }
        .passions-grid-alt img { order: 2; }
        .passions-grid-alt div { order: 1; }
    }
</style>
