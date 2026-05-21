# -biotech-nutrition
	•	index.html


<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Biotech Nutrition</title>

<link rel="stylesheet" href="style.css">
</head>

<body>

<nav>
  <a href="#home">Home</a>
  <a href="#chi">Chi siamo</a>
  <a href="#metodo">Metodo</a>
  <a href="#prodotti">Prodotti</a>
  <a href="#checkout">Carrello</a>
</nav>

<header class="hero" id="home">
  <h1>Biotech Nutrition</h1>
  <p>Scienza, nutrizione e integrazione avanzata</p>

  <div class="hero-btns">
    <a href="#metodo" class="btn blue">Scopri il Metodo</a>
    <a href="#prodotti" class="btn orange">Accedi ai Prodotti</a>
  </div>
</header>

<!-- CHI SIAMO -->
<section id="chi">
  <h2>Chi siamo</h2>

  <div class="card about">
    <p>
      Biotech Nutrition nasce con l’obiettivo di offrire ai professionisti della nutrizione un sistema integrato e innovativo, che unisce scienza, alimentazione e integrazione mirata per migliorare la salute e la composizione corporea dei pazienti.
    </p>

    <p>
      Attraverso protocolli strutturati e strumenti dedicati, supportiamo nutrizionisti e pazienti in percorsi efficaci, personalizzati e duraturi.
    </p>
  </div>
</section>

<!-- METODO -->
<section id="metodo">
  <h2>Metodo DPM SYSTEM</h2>

  <div class="card">

    <h3>Il metodo DPM SYSTEM – Dieta Proteica Mediterranea</h3>

    <p>
      Il Metodo DPM SYSTEM è un protocollo nutrizionale integrato che combina dieta proteica e mediterranea, alternando fasi metaboliche e integrazione mirata per favorire un dimagrimento efficace, preservare la massa magra e garantire risultati duraturi sotto la guida del nutrizionista.
    </p>

    <p><b>Vantaggi principali:</b></p>

    <ul>
      <li>Riduzione massa grassa</li>
      <li>Controllo fame</li>
      <li>Metabolismo attivo</li>
      <li>Risultati stabili nel tempo</li>
    </ul>

  </div>
</section>

<!-- PRODOTTI -->
<section id="prodotti">
  <h2>Prodotti</h2>

  <div class="card">

    <h3>Prodotti Biotech Nutrition</h3>

    <p>
      I prodotti Biotech Nutrition sono formulati per essere utilizzati all’interno del Metodo, in abbinamento ai protocolli nutrizionali personalizzati.
    </p>

    <p>
      Supportano metabolismo, sazietà, drenaggio e risultati ottimali.
    </p>

    <p><b>Elenco prodotti:</b> ……. (in arrivo)</p>

  </div>
</section>

<!-- CARRELLO -->
<section id="checkout">
  <h2>Carrello</h2>

  <div class="card">

    <div id="cart"></div>

    <p><b>Totale: €<span id="total">0</span></b></p>

    <button class="pay-btn" onclick="checkout()">
      💳 Paga ora in sicurezza
    </button>

    <!-- METODI PAGAMENTO -->
    <div class="payment-box">

      <h3>Metodi di pagamento</h3>

      <div class="payment-circle">

        <div class="pay-item">
          💳
          <p>Carta</p>
        </div>

        <div class="pay-item">
          🟡
          <p>PayPal</p>
        </div>

      </div>

    </div>

  </div>
</section>

<footer>
  <div class="footer">
    <p>I prodotti non sono farmaci. Consultare sempre un professionista della salute prima dell’uso.</p>
    <p>© 2026 Biotech Nutrition — Tutti i diritti riservati</p>
  </div>
</footer>

<script src="script.js"></script>

</body>
</html>
