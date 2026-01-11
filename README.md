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
