<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ClientFlow - Courtier de Confiance</title>
<style>
/* RESET SIMPLE */
* { box-sizing: border-box; margin:0; padding:0; font-family: Arial, sans-serif; }

/* GLOBAL */
body { background: #f4f4f7; color: #222; line-height: 1.6; }
a { text-decoration: none; color: inherit; }

/* HEADER */
header { background:#1a1a1a; color:#fff; padding:40px 20px; text-align:center; }
header h1 { margin-bottom:10px; font-size:2rem; }
header p { font-size:1rem; }

/* SECTIONS */
section { padding:40px 20px; max-width:1000px; margin:auto; }
section h2 { font-size:1.8rem; margin-bottom:20px; color:#1a1a1a; text-align:center; }

/* PRODUITS */
.products { display:grid; grid-template-columns: repeat(auto-fit, minmax(250px,1fr)); gap:20px; }
.product { background:#fff; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); overflow:hidden; transition: transform 0.2s; }
.product:hover { transform: translateY(-5px); }
.product img { width:100%; height:auto; }
.product-content { padding:15px; }
.product-content h3 { margin-bottom:10px; font-size:1.2rem; }
.product-content p { margin-bottom:10px; font-size:0.95rem; }
.contact-btn { display:inline-block; padding:10px 15px; background:#1a1a1a; color:#fff; border-radius:5px; font-weight:bold; transition: background 0.2s; }
.contact-btn:hover { background:#333; }

/* COMMENT ÇA MARCHE */
.steps { display:grid; grid-template-columns: repeat(auto-fit, minmax(200px,1fr)); gap:20px; margin-top:20px; }
.step { background:#fff; padding:20px; border-radius:8px; text-align:center; box-shadow:0 2px 8px rgba(0,0,0,0.1); }

/* FOOTER */
footer { text-align:center; padding:20px; background:#eee; margin-top:20px; font-size:0.9rem; }
</style>
</head>
<body>

<header>
<h1>ClientFlow</h1>
<p>Votre courtier de confiance pour vendre et acheter rapidement et en toute sécurité</p>
</header>

<section>
<h2>Produits en Vente</h2>
<div class="products">
  <div class="product">
    <img src="montre.jpg" alt="Montre Noire">
    <div class="product-content">
      <h3>Montre Noire Minimaliste</h3>
      <p>Design élégant, batterie incluse, bracelet ajustable, parfaite pour tous les styles.</p>
      <p><strong>Prix :</strong> 2000 FD</p>
      <a href="https://wa.me/77510033" class="contact-btn">Contacter via WhatsApp</a>
    </div>
  </div>
  <!-- Ajouter d'autres produits ici de la même manière -->
</div>
</section>

<section>
<h2>Comment ça marche</h2>
<div class="steps">
  <div class="step">
    <h3>1. Trouver un produit ou client</h3>
    <p>Vous avez un produit à vendre ou cherchez un produit ? ClientFlow vous met en contact.</p>
  </div>
  <div class="step">
    <h3>2. Facilitation de la vente</h3>
    <p>Nous gérons la communication entre vendeur et acheteur pour sécuriser la transaction.</p>
  </div>
  <div class="step">
    <h3>3. Recevez votre produit ou commission</h3>
    <p>Le produit est livré ou la commission est perçue selon l’accord convenu.</p>
  </div>
</div>
</section>

<section>
<h2>Contact</h2>
<p>Pour acheter un produit ou proposer un article à vendre :</p>
<p><a href="https://wa.me/77510033" class="contact-btn">Contacter via WhatsApp : 77 51 00 33</a></p>
</section>

<footer>
<p>&copy; 2026 ClientFlow. Tous droits réservés.</p>
</footer>

</body>
</html>
