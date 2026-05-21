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

	•	style.css


body{
  margin:0;
  font-family:Arial;
  background:#081428;
  color:white;
}

/* NAV */
nav{
  position:sticky;
  top:0;
  background:#0b1b33;
  display:flex;
  justify-content:center;
  gap:20px;
  padding:14px;
}

nav a{
  color:white;
  text-decoration:none;
  opacity:0.8;
}

/* HERO */
.hero{
  text-align:center;
  padding:120px 20px;
  background:linear-gradient(135deg,#1e90ff,#081428);
}

.hero h1{
  font-size:54px;
}

.hero p{
  color:#cfe3ff;
}

.hero-btns{
  margin-top:20px;
}

.btn{
  padding:12px 18px;
  border-radius:10px;
  margin:5px;
  text-decoration:none;
  display:inline-block;
  font-weight:bold;
}

.blue{background:#1e90ff;color:white;}
.orange{background:#ff9800;color:white;}

/* SECTIONS */
section{
  max-width:1000px;
  margin:auto;
  padding:60px 20px;
}

h2{
  color:#ffb347;
}

/* CARD */
.card{
  background:#111f3a;
  padding:20px;
  border-radius:14px;
  margin:15px 0;
}

.about p{
  line-height:1.7;
  color:#dbe9ff;
}

/* LIST */
ul{
  padding-left:20px;
}

li{
  margin-bottom:8px;
}

/* BUTTON PAY */
.pay-btn{
  margin-top:15px;
  width:100%;
  padding:14px;
  border:none;
  border-radius:12px;
  font-size:16px;
  font-weight:bold;
  cursor:pointer;

  background:linear-gradient(90deg,#1e90ff,#00c3ff);
  color:white;

  transition:0.3s;
}

.pay-btn:hover{
  background:linear-gradient(90deg,#ff9800,#ffb347);
  transform:scale(1.03);
}

/* PAYMENT BOX */
.payment-box{
  margin-top:25px;
  text-align:center;
}

.payment-box h3{
  color:#ffb347;
}

.payment-circle{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.pay-item{
  width:100px;
  height:100px;
  border-radius:50%;
  background:#0f223f;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  border:1px solid rgba(255,255,255,0.1);
}

.pay-item p{
  font-size:12px;
  color:#dbe9ff;
  margin-top:5px;
}

/* FOOTER */
.footer{
  text-align:center;
  padding:40px;
  opacity:0.7;
}
