---
layout: default
title: Home
lang: it
ref: homepage
---

<!-- SEZIONE 1: CAROSELLO IMMAGINI -->
{% include news_carousel.html %}

<!-- SEZIONE 2: SCHEDE E NEWS (Senza blocco immagine PEPPOL) -->
<div class="container my-5">
  <div class="row">
    
    <!-- Scheda 1: Cos'è PEPPOL? -->
    <div class="col-12 col-lg-6 mb-4">
      <div class="card shadow-sm border h-100 p-4">
        <div class="card-body">
          <h3 class="h4 font-weight-bold text-primary mb-3">Cos'è PEPPOL?</h3>
          <p class="card-text text-secondary">
            PEPPOL abilita il commercio veloce, efficiente e senza confini.<br><br>
            Le specifiche dei documenti PEPPOL integrano i processi aziendali globali
            standardizzando il modo in cui le informazioni sono strutturate e scambiate.<br><br>
            PEPPOL oltre ai tracciati standard e ad una rete sicura fornisce la governance
            per farla funzionare, attraverso accordi vincolanti che garantiscono la
            conformità delle parti coinvolte.
          </p>
          <a href="{{ site.baseurl }}/it/cos-e-peppol/" class="btn btn-outline-primary btn-sm mt-3">
            Scopri di più &rarr;
          </a>
        </div>
      </div>
    </div>

    <!-- Scheda 2: AP Unico della PA -->
    <div class="col-12 col-lg-6 mb-4">
      <div class="card shadow-sm border h-100 p-4">
        <div class="card-body">
          <h3 class="h4 font-weight-bold text-primary mb-3">AP Unico della PA</h3>
          <p class="card-text text-secondary">
            L’Access Point Peppol unico per la PA è stato realizzato dalla Peppol Authority
            Nazionale per supportare la trasmissione in prima istanza degli ordini
            elettronici su rete Peppol. È un servizio, qualificato nella rete Peppol ed
            integrato con NSO – Nodo Smistamento Ordini, che ha il compito di trasmettere
            agli operatori economici attestati su rete Peppol un ordine elettronico inviato
            da una Pubblica Amministrazione italiana tramite canali tradizionali (PEC, FTP
            e WS9) a NSO.<br><br>
            Vai alle <a href="https://peppol-ap.agid.gov.it/notier/pub/risultatiAp.html" target="_blank" rel="noopener">Statistiche dell'Access Point unico della Pubblica Amministrazione</a>.
          </p>
        </div>
      </div>
    </div>

  </div>
</div>

<main class="container my-5" markdown="1">
  {% include news.html %}
</main>