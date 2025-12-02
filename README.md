<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>KHALEEJI KLOSET — Essentials & Streetwear</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
  /* Elegant + streetwear theme */
  :root{
    --bg:#0f1113;
    --card:#0f1720;
    --muted:#9aa3ad;
    --accent:#d4af37; /* gold accent */
    --glass: rgba(255,255,255,0.04);
    --glass-strong: rgba(255,255,255,0.06);
  }
  *{box-sizing:border-box}
  html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,'Segoe UI',Roboto,'Helvetica Neue',Arial}
  body{background:linear-gradient(180deg,#0b0c0d 0%, #101214 100%);color:#e6eef6;line-height:1.45}

  header{
    display:flex;align-items:center;justify-content:space-between;padding:28px 6%;background:linear-gradient(90deg,rgba(255,255,255,0.02),transparent);backdrop-filter:blur(6px);border-bottom:1px solid rgba(255,255,255,0.03)
  }
  .brand{display:flex;align-items:center;gap:14px}
  .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,#111316,#1b1f26);display:flex;align-items:center;justify-content:center;font-weight:800;color:var(--accent);font-size:20px;box-shadow:0 6px 18px rgba(0,0,0,0.6)}
  .brand h1{margin:0;font-size:20px;letter-spacing:0.06em}
  .brand p{margin:0;color:var(--muted);font-size:13px}

  nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-weight:600}
  nav a:hover{color:var(--accent)}

  main{max-width:1200px;margin:36px auto;padding:0 24px}

  .hero{display:grid;grid-template-columns:1fr 420px;gap:36px;align-items:center}
  .hero-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:36px;border-radius:14px;border:1px solid rgba(255,255,255,0.03);box-shadow:0 10px 30px rgba(2,6,23,0.6)}
  .hero h2{font-size:34px;margin:0 0 12px;color:#fff}
  .hero p.lead{color:var(--muted);font-size:16px;margin:0 0 20px}
  .cta{display:inline-block;padding:10px 16px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#f6d37a);color:#071018;font-weight:700;text-decoration:none}

  .products-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:28px}
  .product{background:linear-gradient(180deg,var(--card),rgba(255,255,255,0.02));border-radius:12px;padding:14px;border:1px solid rgba(255,255,255,0.03);transition:transform .25s ease, box-shadow .25s ease}
  .product:hover{transform:translateY(-8px);box-shadow:0 20px 40px rgba(2,6,23,0.6)}
  .product img{width:100%;height:220px;object-fit:cover;border-radius:8px}
  .product h3{margin:10px 0 6px;font-size:18px}
  .product .price{font-weight:700;color:var(--accent)}
  .product .sizes{margin-top:8px}
  .chip{display:inline-block;padding:6px 10px;border-radius:8px;background:var(--glass);color:var(--muted);font-weight:600;margin-right:8px;font-size:13px}

  .brand-section{margin-top:46px}
  .brand-title{display:flex;align-items:center;justify-content:space-between}
  .brand-title h3{margin:0}
  .coming{font-weight:700;color:var(--muted)}

  footer{margin-top:60px;padding:36px 6%;text-align:center;color:var(--muted);border-top:1px solid rgba(255,255,255,0.03)}

  /* responsive */
  @media (max-width:1000px){
    .hero{grid-template-columns:1fr}
    .products-grid{grid-template-columns:repeat(2,1fr)}
  }
  @media (max-width:640px){
    nav a{margin-left:12px;font-size:14px}
    .products-grid{grid-template-columns:1fr}
    .hero h2{font-size:26px}
  }
</style>
</head>
<body>
  <header style="padding:20px;background:white;display:flex;justify-content:space-between;align-items:center;box-shadow:0 2px 5px rgba(0,0,0,0.05);">
    <h1 style="margin:0;font-size:24px;">KHALEEJI KLOSET</h1>
    <nav style="display:flex;gap:20px;font-weight:600;">
      <a href="#essentials">Essentials</a>
      <a href="#bape">Bape</a>
      <a href="#represent">Represent</a>
      <a href="#brokenplanet">Broken Planet</a>
    </nav>
  </header>

  <main style="max-width:1100px;margin:30px auto;padding:20px;">

    <!-- Broken Planet Page -->
    <section id="brokenplanet">
      <h2>Broken Planet</h2>
      <p>DM us on TikTok, Instagram, or Snapchat to order. Sizes available: XS, S, M, L.</p>

      <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:20px;margin-top:20px;">

        <div style="background:white;padding:15px;border-radius:10px;box-shadow:0 3px 10px rgba(0,0,0,0.1);">
          <img src="https://via.placeholder.com/400x300?text=Mystery+Hoodie" style="width:100%;border-radius:8px;" />
          <h3>Mystery Hoodie</h3>
          <p>Price: <strong>43 BD</strong></p>
          <p>Sizes: XS, S, M, L</p>
        </div>

        <div style="background:white;padding:15px;border-radius:10px;box-shadow:0 3px 10px rgba(0,0,0,0.1);">
          <img src="https://via.placeholder.com/400x300?text=Mystery+Shirt" style="width:100%;border-radius:8px;" />
          <h3>Mystery Shirt</h3>
          <p>Price: <strong>20 BD</strong></p>
          <p>Sizes: XS, S, M, L</p>
        </div>

        <div style="background:white;padding:15px;border-radius:10px;box-shadow:0 3px 10px rgba(0,0,0,0.1);">
          <img src="https://via.placeholder.com/400x300?text=Mystery+Set" style="width:100%;border-radius:8px;" />
          <h3>Mystery Set</h3>
          <p>Price: <strong>70 BD</strong></p>
          <p>Sizes: XS, S, M, L</p>
        </div>

      </div>
    </section>

    <!-- Placeholder sections for other brands -->
    <section id="essentials" style="margin-top:60px;">
      <h2>Essentials</h2>
      <p style="font-size:18px;color:gray;font-weight:600;">Coming soon!</p>
    </section>

    <section id="bape" style="margin-top:60px;">
      <h2>Bape</h2>
      <p style="font-size:18px;color:gray;font-weight:600;">Coming soon!</p>
    </section>

    <section id="represent" style="margin-top:60px;">
      <h2>Represent</h2>
      <p style="font-size:18px;color:gray;font-weight:600;">Coming soon!</p>
    </section>

  

<!-- CART PANEL -->
<div id="cartPanel" style="position:fixed;top:0;right:-400px;width:360px;height:100%;background:#0f1720;border-left:1px solid rgba(255,255,255,0.08);box-shadow:-6px 0 20px rgba(0,0,0,0.6);transition:0.35s;padding:24px;overflow-y:auto;z-index:9999;">
  <h2 style="margin-top:0;color:var(--accent);">Your Cart</h2>
  <div id="cartItems" style="margin-top:14px;color:#fff;"></div>
  <hr style="border-color:rgba(255,255,255,0.08);margin:20px 0;">
  <button onclick="openCheckout()" style="width:100%;padding:12px;background:var(--accent);border:0;border-radius:10px;font-weight:700;color:#000;font-size:16px;cursor:pointer;">Checkout</button>
</div>

<!-- CHECKOUT FORM -->
<div id="checkoutPage" style="display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:#0f1113;z-index:99999;padding:40px;overflow-y:auto;">
  <h2 style="color:var(--accent);">Checkout</h2>
  <p style="color:var(--muted);">Fill your details and we’ll confirm your order through email.</p>

  <form action="mailto:bhcandy454@gmail.com" method="POST" enctype="text/plain" style="margin-top:20px;max-width:420px;">
    <label>Name</label>
    <input name="Name" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #333;background:#1b1f26;color:#fff;margin-bottom:12px;">

    <label>Phone Number</label>
    <input name="Phone" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #333;background:#1b1f26;color:#fff;margin-bottom:12px;">

    <label>Address</label>
    <input name="Address" required style="width:100%;padding:10px;border-radius:8px;border:1px solid #333;background:#1b1f26;color:#fff;margin-bottom:12px;">

    <label>Your Order</label>
    <textarea id="orderDetails" name="Order Details" readonly style="width:100%;height:140px;padding:10px;border-radius:8px;border:1px solid #333;background:#1b1f26;color:#fff;margin-bottom:18px;"></textarea>

    <button style="width:100%;padding:12px;background:var(--accent);border:0;border-radius:10px;font-weight:700;color:#000;font-size:16px;cursor:pointer;">Send Order</button>
  </form>

  <button onclick="closeCheckout()" style="margin-top:20px;color:var(--accent);background:none;border:0;font-size:16px;cursor:pointer;">Cancel</button>
</div>

<script>
let cart = [];

function addToCart(name, price) {
  cart.push({ name, price });
  updateCartUI();
  openCart();
}

function updateCartUI() {
  const box = document.getElementById("cartItems");
  box.innerHTML = "";
  cart.forEach((item, i) => {
    box.innerHTML += `<div style='margin-bottom:12px;'>
      <strong>${item.name}</strong><br>
      <span style='color:var(--accent);'>${item.price} BHD</span>
      <button onclick='removeItem(${i})' style='float:right;background:none;border:0;color:#f55;cursor:pointer;'>Remove</button>
    </div>`;
  });
}

function removeItem(i) {
  cart.splice(i, 1);
  updateCartUI();
}

function openCart() {
  document.getElementById("cartPanel").style.right = "0";
}

function openCheckout() {
  document.getElementById("checkoutPage").style.display = "block";
  document.getElementById("orderDetails").value = cart.map(x => `${x.name} - ${x.price} BHD`).join("\n");
}
function closeCheckout() {
  document.getElementById("checkoutPage").style.display = "none";
}
</script>

</main>

</body>
</html>
