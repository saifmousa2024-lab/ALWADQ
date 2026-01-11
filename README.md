<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Al-Wadaq | Contact - شركة الودق</title>
  <meta name="description" content="Contact Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq. Samples, wholesale pricing, and project supply." />
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>

  <header class="nav">
    <div class="container">
      <div class="navbar">
        <a class="brand" href="index.html"><span class="logo"></span><span>Al-Wadaq</span></a>
        <button id="menuBtn" class="btn menu-btn" type="button">Menu</button>

        <nav id="navLinks" class="links">
          <a class="link" data-nav href="index.html" data-i18n="nav_home">Home</a>
          <a class="link" data-nav href="about.html" data-i18n="nav_about">About</a>
          <a class="link" data-nav href="products.html" data-i18n="nav_products">Products</a>
          <a class="link" data-nav href="contact.html" data-i18n="nav_contact">Contact</a>
        </nav>

        <div class="nav-actions">
          <button id="langBtn" class="btn" type="button">English</button>
          <!-- ضع رقم واتساب الحقيقي هنا -->
          <a class="btn primary" href="https://wa.me/9647XXXXXXXXX" target="_blank" rel="noopener" data-i18n="whatsapp_btn">WhatsApp</a>
        </div>
      </div>
    </div>
  </header>

  <main>
    <section class="section">
      <div class="container grid" style="grid-template-columns:1fr 1fr; align-items:start;">
        <div class="card">
          <span class="badge" data-i18n="contact_badge">Contact</span>
          <h1 style="margin-top:10px;" data-i18n="contact_title">Samples, wholesale pricing, or project supply — contact us.</h1>
          <p style="color:var(--muted);" data-i18n="contact_p">
            Fill the form and we will respond...
          </p>

          <div class="hr"></div>

          <form id="contactForm">
            <div class="two">
              <div>
                <label data-i18n="c_company">Company (optional)</label>
                <input id="cCompany" type="text" data-i18n-placeholder="c_company" placeholder="Company (optional)" />
              </div>
              <div>
                <label data-i18n="c_name">Full name</label>
                <input id="cName" type="text" required />
              </div>
            </div>

            <div class="two">
              <div>
                <label data-i18n="c_email">Email</label>
                <input id="cEmail" type="email" required />
              </div>
              <div>
                <label data-i18n="c_phone">Phone (optional)</label>
                <input id="cPhone" type="tel" />
              </div>
            </div>

            <div>
              <label data-i18n="c_need">Inquiry type</label>
              <select id="cNeed">
                <option value="samples" data-i18n-value="need1">Samples</option>
                <option value="wholesale" data-i18n-value="need2">Wholesale pricing</option>
                <option value="project" data-i18n-value="need3">Project supply</option>
                <option value="distribution" data-i18n-value="need4">Distribution partnership</option>
              </select>
            </div>

            <div>
              <label data-i18n="c_details">Details</label>
              <textarea id="cDetails" required></textarea>
            </div>

            <button class="btn primary" type="submit" data-i18n="c_submit">Send</button>

            <div class="notice">
              للتشغيل الحقيقي: استبدل التخزين المحلي بربط API (مثل Formspree/Netlify Forms أو Backend).
            </div>
          </form>
        </div>

        <div class="card">
          <h2 style="margin-top:0;" data-i18n="contact_info_title">Company Details</h2>
          <div class="small" style="margin-top:10px;">
            <div><strong data-i18n="address_label">Address</strong>: <span data-i18n="city">Babel, Iraq</span></div>
            <div style="margin-top:6px;"><strong data-i18n="phone_label">Phone</strong>: +964 7XX XXX XXXX</div>
            <div><strong data-i18n="email_label">Email</strong>: info@alwadaq-wallpaper.com</div>
          </div>

          <div class="hr"></div>

          <h3 style="margin:0 0 10px;" data-i18n="map_title">Location on Map</h3>
          <!-- ضع رابط خرائط Google الحقيقي لموقع الشركة عند توفره -->
          <iframe
            title="Al-Wadaq Location"
            style="width:100%;height:280px;border:0;border-radius:16px;"
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
            src="https://www.google.com/maps?q=Babel%20Iraq&output=embed">
          </iframe>

          <div class="small" style="margin-top:10px;">
            إذا أعطيتني رابط Google Maps لموقع الشركة بالضبط، أضعه هنا بشكل صحيح.
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <div class="row">
        <div>
          <div class="brand" style="margin-bottom:8px;"><span class="logo"></span><span>Al-Wadaq</span></div>
          <div class="small" data-i18n="footer_tagline">Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq</div>
        </div>
        <div class="small">© <span id="year"></span> Al-Wadaq — <span data-i18n="footer_rights">All rights reserved</span></div>
      </div>
    </div>
  </footer>

  <div id="toast" class="toast" role="status" aria-live="polite"></div>
  <script src="assets/js/i18n.js"></script>
</body>
</html>
:root{
  --bg:#0b1220;
  --card:#101a33;
  --text:#eaf0ff;
  --muted:#a9b3c9;
  --brand:#7dd3fc;
  --brand2:#86efac;
  --border:rgba(255,255,255,.10);
  --shadow:0 10px 30px rgba(0,0,0,.35);
  --radius:18px;
  --max:1120px;
  --font: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Arial, "Noto Sans Arabic", "Noto Sans", sans-serif;
}

*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  font-family:var(--font);
  background:
    radial-gradient(900px 600px at 10% 10%, rgba(125,211,252,.20), transparent 60%),
    radial-gradient(900px 600px at 90% 20%, rgba(134,239,172,.18), transparent 60%),
    radial-gradient(800px 500px at 60% 90%, rgba(125,211,252,.12), transparent 60%),
    var(--bg);
  color:var(--text);
  line-height:1.7;
}

a{color:inherit;text-decoration:none}
img{max-width:100%;display:block;border-radius:14px}
.container{max-width:var(--max);margin:0 auto;padding:0 18px}
.section{padding:64px 0}
.grid{display:grid;gap:18px}

.card{
  background:rgba(16,26,51,.70);
  border:1px solid var(--border);
  border-radius:var(--radius);
  box-shadow:var(--shadow);
  padding:18px;
}

.badge{
  display:inline-flex;align-items:center;gap:8px;
  padding:8px 12px;border:1px solid var(--border);
  border-radius:999px;background:rgba(255,255,255,.06);
  color:var(--muted);font-size:14px;
}

.btn{
  display:inline-flex;align-items:center;justify-content:center;gap:10px;
  padding:12px 16px;border-radius:14px;border:1px solid var(--border);
  background:rgba(255,255,255,.06);color:var(--text);
  cursor:pointer;transition:.2s transform,.2s background,.2s border-color;
}
.btn:hover{transform:translateY(-1px);background:rgba(255,255,255,.10);border-color:rgba(255,255,255,.18)}
.btn.primary{
  background:linear-gradient(90deg, rgba(125,211,252,.95), rgba(134,239,172,.85));
  color:#04101b;border-color:transparent;font-weight:800;
}
.btn.ghost{background:transparent}

.hr{height:1px;background:var(--border);margin:18px 0}

.nav{
  position:sticky;top:0;z-index:50;
  backdrop-filter: blur(10px);
  background: rgba(11,18,32,.65);
  border-bottom:1px solid var(--border);
}
.navbar{
  display:flex;align-items:center;justify-content:space-between;
  padding:14px 0;gap:14px;flex-wrap:wrap;
}
.brand{
  display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.2px
}
.logo{
  width:38px;height:38px;border-radius:14px;
  background: linear-gradient(135deg, rgba(125,211,252,.95), rgba(134,239,172,.85));
  box-shadow: 0 10px 25px rgba(125,211,252,.18);
}
.links{display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.link{
  padding:10px 12px;border-radius:12px;color:var(--muted);
  border:1px solid transparent;
}
.link:hover{color:var(--text);border-color:var(--border);background:rgba(255,255,255,.06)}
.link.active{color:var(--text);background:rgba(255,255,255,.08);border-color:var(--border)}
.nav-actions{display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.menu-btn{display:none}

.hero{
  display:grid;
  grid-template-columns: 1.2fr .8fr;
  gap:18px;
  align-items:stretch;
}
.hero h1{margin:10px 0 0;font-size:42px;line-height:1.2}
.hero p{color:var(--muted);margin:14px 0 18px}
.hero .actions{display:flex;gap:12px;flex-wrap:wrap}

.kpis{
  display:grid;
  grid-template-columns: repeat(4, minmax(0,1fr));
  gap:14px;
}
.kpi{padding:16px;border-radius:16px;border:1px solid var(--border);background:rgba(255,255,255,.05)}
.kpi strong{display:block;font-size:22px}
.kpi span{color:var(--muted);font-size:13px}

.products{
  grid-template-columns: repeat(3, minmax(0,1fr));
}
.product h3{margin:10px 0 6px}
.product p{margin:0;color:var(--muted)}
.tag{
  display:inline-block;
  padding:6px 10px;border-radius:999px;
  background:rgba(125,211,252,.12);
  border:1px solid rgba(125,211,252,.22);
  font-size:13px;
}

form{display:grid;gap:12px}
label{font-size:14px;color:var(--muted)}
input,textarea,select{
  width:100%;padding:12px 12px;border-radius:14px;
  border:1px solid var(--border);
  background:rgba(255,255,255,.05);color:var(--text);
  outline:none;
}
textarea{min-height:130px;resize:vertical}
.two{display:grid;grid-template-columns:1fr 1fr;gap:12px}

.footer{
  padding:28px 0;border-top:1px solid var(--border);
  color:var(--muted);background: rgba(11,18,32,.55);
}
.footer .row{display:flex;align-items:flex-start;justify-content:space-between;gap:18px;flex-wrap:wrap}
.small{font-size:13px;color:var(--muted)}

.notice{
  border:1px dashed rgba(255,255,255,.22);
  background:rgba(255,255,255,.04);
  border-radius:16px;padding:12px 14px;color:var(--muted);
}

.toast{
  position:fixed;bottom:18px;left:18px;
  background:rgba(16,26,51,.92);
  border:1px solid var(--border);
  border-radius:16px;padding:12px 14px;
  box-shadow:var(--shadow);
  min-width: 240px;
  display:none;
}
.toast.show{display:block}

/* responsive */
@media (max-width: 960px){
  .hero{grid-template-columns: 1fr}
  .kpis{grid-template-columns: repeat(2, minmax(0,1fr))}
  .products{grid-template-columns: repeat(2, minmax(0,1fr))}
}
@media (max-width: 680px){
  .menu-btn{display:inline-flex}
  .links{display:none;width:100%;flex-direction:column;align-items:stretch;padding:10px 0 0}
  .links.open{display:flex}
  .two{grid-template-columns: 1fr}
  .products{grid-template-columns: 1fr}
  .hero h1{font-size:34px}
}
