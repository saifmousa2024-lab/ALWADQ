<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Al-Wadaq Wallpaper | شركة الودق لصناعة ورق الجدران المحدودة</title>
  <meta name="description" content="Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq. Manufacturer of wallpapers with multiple materials and finishes for residential and commercial projects." />

  <!-- Open Graph -->
  <meta property="og:title" content="Al-Wadaq Wallpaper Manufacturing Co. Ltd" />
  <meta property="og:description" content="Wallpaper manufacturer in Babel, Iraq — materials, finishes, and project supply." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="ar_IQ" />

  <style>
    :root{
      --bg:#0b0f15;
      --card:#0f1624;
      --muted:#a9b4c7;
      --text:#eef3ff;
      --brand:#67b7ff;
      --brand2:#7c5cff;
      --border:rgba(255,255,255,.08);
      --shadow: 0 18px 45px rgba(0,0,0,.35);
      --radius:18px;
      --container:1100px;
    }

    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans Arabic", sans-serif;
      background: radial-gradient(1200px 600px at 20% 0%, rgba(124,92,255,.15), transparent 60%),
                  radial-gradient(900px 500px at 90% 20%, rgba(103,183,255,.14), transparent 55%),
                  var(--bg);
      color:var(--text);
      line-height:1.6;
    }

    a{color:inherit; text-decoration:none}
    .container{max-width:var(--container); margin:0 auto; padding:0 18px}
    .section{padding:46px 0}
    .grid{display:grid; gap:16px}
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      border:1px solid var(--border);
      border-radius: var(--radius);
      padding:18px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(8px);
    }
    .hr{height:1px; background:var(--border); margin:16px 0}
    .small{font-size:.92rem; color:var(--muted)}
    .badge{
      display:inline-flex;
      padding:6px 10px;
      border-radius:999px;
      border:1px solid var(--border);
      color:var(--muted);
      font-size:.85rem;
      background: rgba(255,255,255,.03);
    }

    /* NAV */
    .nav{
      position:sticky; top:0; z-index:50;
      background: rgba(11,15,21,.55);
      border-bottom:1px solid var(--border);
      backdrop-filter: blur(10px);
    }
    .navbar{
      display:flex; align-items:center; justify-content:space-between;
      padding:12px 0; gap:12px;
    }
    .brand{
      display:flex; align-items:center; gap:10px;
      font-weight:700;
      letter-spacing:.3px;
    }
    .logo{
      width:34px; height:34px; border-radius:10px;
      background:
        radial-gradient(circle at 30% 30%, rgba(255,255,255,.9), rgba(255,255,255,0) 55%),
        linear-gradient(135deg, var(--brand), var(--brand2));
      box-shadow: 0 10px 30px rgba(103,183,255,.18);
    }
    .links{
      display:flex; align-items:center; gap:14px;
      padding:8px 10px;
      border:1px solid var(--border);
      border-radius:999px;
      background: rgba(255,255,255,.03);
    }
    .link{
      padding:8px 10px;
      border-radius:999px;
      color:var(--muted);
      transition: .2s ease;
      font-weight:600;
      font-size:.95rem;
    }
    .link:hover{color:var(--text); background: rgba(255,255,255,.06)}
    .link.active{color:var(--text); background: rgba(103,183,255,.14); border:1px solid rgba(103,183,255,.22)}
    .nav-actions{display:flex; align-items:center; gap:10px}

    /* BUTTONS */
    .btn{
      border:1px solid var(--border);
      background: rgba(255,255,255,.03);
      color:var(--text);
      padding:10px 12px;
      border-radius:12px;
      cursor:pointer;
      font-weight:700;
      transition:.2s ease;
    }
    .btn:hover{transform: translateY(-1px); background: rgba(255,255,255,.06)}
    .btn.primary{
      border-color: rgba(103,183,255,.35);
      background: linear-gradient(135deg, rgba(103,183,255,.20), rgba(124,92,255,.18));
    }
    .menu-btn{display:none}

    /* HERO */
    .hero{
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:16px;
      align-items:stretch;
    }
    h1{margin:10px 0 0; font-size:2rem; line-height:1.2}
    h2{margin:0 0 10px; font-size:1.3rem}
    p{margin:10px 0 0; color:var(--muted)}
    .actions{display:flex; gap:12px; flex-wrap:wrap; margin-top:14px}

    .kpis{
      display:grid;
      grid-template-columns: repeat(2, 1fr);
      gap:10px;
    }
    .kpi{
      border:1px solid var(--border);
      border-radius:14px;
      padding:10px 12px;
      background: rgba(255,255,255,.03);
      display:flex;
      justify-content:space-between;
      gap:10px;
      font-size:.95rem;
    }
    .kpi strong{color:var(--text)}
    .kpi span{color:var(--muted)}

    /* PRODUCTS */
    .products{
      grid-template-columns: repeat(3, 1fr);
    }
    .product .tag{
      display:inline-flex;
      padding:6px 10px;
      border-radius:999px;
      border:1px solid rgba(103,183,255,.26);
      background: rgba(103,183,255,.10);
      color: var(--text);
      font-weight:800;
      font-size:.85rem;
    }
    .product h3{margin:10px 0 0; font-size:1.05rem}
    .product p{margin-top:8px}

    /* FORMS */
    label{display:block; font-weight:800; margin:12px 0 6px}
    input, textarea, select{
      width:100%;
      padding:12px 12px;
      border-radius:14px;
      border:1px solid var(--border);
      background: rgba(0,0,0,.15);
      color:var(--text);
      outline:none;
    }
    textarea{min-height:120px; resize:vertical}
    .two{display:grid; grid-template-columns:1fr 1fr; gap:14px}

    /* FOOTER */
    .footer{
      border-top:1px solid var(--border);
      padding:24px 0;
      background: rgba(255,255,255,.02);
    }
    .row{
      display:flex; gap:16px; align-items:flex-start; justify-content:space-between;
      flex-wrap:wrap;
    }

    /* TOAST */
    .toast{
      position: fixed;
      inset-inline-start: 16px;
      bottom: 16px;
      min-width: 260px;
      max-width: 360px;
      padding: 12px 14px;
      border-radius: 14px;
      background: rgba(0,0,0,.55);
      border: 1px solid var(--border);
      color: var(--text);
      box-shadow: var(--shadow);
      opacity: 0;
      transform: translateY(12px);
      pointer-events:none;
      transition: .25s ease;
    }
    .toast.show{opacity:1; transform: translateY(0)}

    /* RESPONSIVE */
    @media (max-width: 980px){
      .hero{grid-template-columns:1fr}
      .products{grid-template-columns: repeat(2, 1fr)}
    }
    @media (max-width: 820px){
      .menu-btn{display:inline-block}
      .links{
        display:none;
        position:absolute;
        top:60px;
        inset-inline-start:18px;
        inset-inline-end:18px;
        border-radius:16px;
        flex-direction:column;
        align-items:stretch;
        padding:10px;
      }
      .links.open{display:flex}
      .navbar{position:relative}
      .two{grid-template-columns:1fr}
      .products{grid-template-columns: 1fr}
    }

    /* Section anchor offset for sticky nav */
    section[id]{scroll-margin-top: 90px}
  </style>
</head>

<body>
  <header class="nav">
    <div class="container">
      <div class="navbar">
        <a class="brand" href="#home" aria-label="Al-Wadaq">
          <span class="logo" aria-hidden="true"></span>
          <span>Al-Wadaq</span>
        </a>

        <button id="menuBtn" class="btn menu-btn" type="button">Menu</button>

        <nav id="navLinks" class="links" aria-label="Navigation">
          <a class="link" data-nav href="#home" data-i18n="nav_home">Home</a>
          <a class="link" data-nav href="#about" data-i18n="nav_about">About</a>
          <a class="link" data-nav href="#products" data-i18n="nav_products">Products</a>
          <a class="link" data-nav href="#contact" data-i18n="nav_contact">Contact</a>
        </nav>

        <div class="nav-actions">
          <button id="langBtn" class="btn" type="button">English</button>
          <a class="btn primary" href="#contact" data-i18n="home_cta_quote">Request a Quote</a>
        </div>
      </div>
    </div>
  </header>

  <main>
    <!-- HOME -->
    <section id="home" class="section">
      <div class="container hero">
        <div class="card">
          <span class="badge" data-i18n="home_badge">Wallpaper manufacturer — quality and modern designs</span>
          <h1 data-i18n="home_title">Al-Wadaq Wallpaper Manufacturing Co. Ltd</h1>
          <p data-i18n="home_sub">
            We manufacture high-quality wallpapers with a wide range of materials and finishes for residential and commercial projects in Iraq.
          </p>

          <div class="actions">
            <a class="btn primary" href="#products" data-i18n="home_cta_products">View Products</a>
            <a class="btn" href="#contact" data-i18n="home_cta_quote">Request a Quote</a>
          </div>

          <div class="hr"></div>

          <div class="kpis">
            <div class="kpi"><strong data-i18n="kpi1">Multiple designs</strong><span data-i18n="kpi_suffix">—</span></div>
            <div class="kpi"><strong data-i18n="kpi2">Materials & finishes</strong><span data-i18n="kpi_suffix">—</span></div>
            <div class="kpi"><strong data-i18n="kpi3">Project supply</strong><span data-i18n="kpi_suffix">—</span></div>
            <div class="kpi"><strong data-i18n="kpi4">Quality control</strong><span data-i18n="kpi_suffix">—</span></div>
          </div>
        </div>

        <div class="card">
          <h2 data-i18n="home_why_title">Why Al-Wadaq?</h2>
          <div class="grid" style="margin-top:14px;">
            <div class="card" style="background:rgba(255,255,255,.04);">
              <strong data-i18n="home_why_1_t">Measurable quality</strong>
              <div class="small" data-i18n="home_why_1_d">Controls for thickness, color consistency, and surface finish.</div>
            </div>
            <div class="card" style="background:rgba(255,255,255,.04);">
              <strong data-i18n="home_why_2_t">Material variety</strong>
              <div class="small" data-i18n="home_why_2_d">Vinyl, non-woven, and tailored options for different environments.</div>
            </div>
            <div class="card" style="background:rgba(255,255,255,.04);">
              <strong data-i18n="home_why_3_t">Supply readiness</strong>
              <div class="small" data-i18n="home_why_3_d">Order management and delivery scheduling for projects and distributors.</div>
            </div>
          </div>

          <div class="hr"></div>

          <div class="small">
            <div><strong data-i18n="address_label">Address</strong>: <span data-i18n="city">Babel, Iraq</span></div>
            <div style="margin-top:6px;"><strong data-i18n="phone_label">Phone</strong>: <span data-i18n="phone_value">+964 7XX XXX XXXX</span></div>
            <div><strong data-i18n="email_label">Email</strong>: <span data-i18n="email_value">info@alwadaq-wallpaper.com</span></div>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section" style="padding-top:0;">
      <div class="container grid" style="grid-template-columns:1.1fr .9fr; align-items:start;">
        <div class="card">
          <span class="badge" data-i18n="about_badge">About</span>
          <h1 style="margin-top:10px;" data-i18n="about_title">Local manufacturing with dependable quality and stable supply.</h1>
          <p data-i18n="about_p">
            Al-Wadaq Wallpaper Manufacturing Co. Ltd operates in Babel Province, Iraq, supplying wallpapers for residential and commercial applications through distributors and project partners.
          </p>

          <div class="hr"></div>

          <h2 data-i18n="about_vision_t">Our Vision</h2>
          <p data-i18n="about_vision_p">
            To be Iraq’s leading locally manufactured wallpaper brand, recognized for consistent quality, modern design, and reliable supply.
          </p>

          <h2 style="margin-top:18px;" data-i18n="about_values_t">Our Values</h2>
          <ul style="color:var(--muted); margin:0; padding-inline-start:18px;">
            <li data-i18n="about_val1">Quality and operational discipline.</li>
            <li data-i18n="about_val2">Specification and order transparency.</li>
            <li data-i18n="about_val3">Innovation in design and materials.</li>
            <li data-i18n="about_val4">Customer service and supply partnerships.</li>
          </ul>
        </div>

        <div class="card">
          <h2 data-i18n="contact_info_title">Company Details</h2>
          <div class="small" style="margin-top:10px;">
            <div><strong data-i18n="address_label">Address</strong>: <span data-i18n="city">Babel, Iraq</span></div>
            <div style="margin-top:6px;"><strong data-i18n="phone_label">Phone</strong>: <span data-i18n="phone_value">+964 7XX XXX XXXX</span></div>
            <div><strong data-i18n="email_label">Email</strong>: <span data-i18n="email_value">info@alwadaq-wallpaper.com</span></div>
          </div>
          <div class="hr"></div>
          <div class="small" data-i18n="about_note">
            Note: Replace the phone/email placeholders with real company contacts before publishing.
          </div>
        </div>
      </div>
    </section>

    <!-- PRODUCTS -->
    <section id="products" class="section" style="padding-top:0;">
      <div class="container">
        <div class="card">
          <span class="badge" data-i18n="prod_badge">Products</span>
          <h1 style="margin-top:10px;" data-i18n="prod_title">Wallpaper products across materials and finish options.</h1>
          <p data-i18n="prod_p">Choose the suitable category and request samples or a quote.</p>
        </div>

        <div class="section" style="padding-bottom:0;">
          <div class="grid products">
            <div class="card product">
              <span class="tag" data-i18n="p1_tag">Vinyl</span>
              <h3 data-i18n="p1_name">Vinyl Wallpaper</h3>
              <p data-i18n="p1_desc">Better moisture resistance and durability; suitable for high-traffic areas.</p>
            </div>
            <div class="card product">
              <span class="tag" data-i18n="p2_tag">Non-woven</span>
              <h3 data-i18n="p2_name">Non-woven Wallpaper</h3>
              <p data-i18n="p2_desc">Easier installation and removal; breathable with good dimensional stability.</p>
            </div>
            <div class="card product">
              <span class="tag" data-i18n="p3_tag">Classic</span>
              <h3 data-i18n="p3_name">Classic Collection</h3>
              <p data-i18n="p3_desc">Traditional patterns, textures, and premium looks for formal interiors.</p>
            </div>
            <div class="card product">
              <span class="tag" data-i18n="p4_tag">Modern</span>
              <h3 data-i18n="p4_name">Modern Collection</h3>
              <p data-i18n="p4_desc">Clean lines and contemporary designs for modern homes and offices.</p>
            </div>
            <div class="card product">
              <span class="tag" data-i18n="p5_tag">Kids</span>
              <h3 data-i18n="p5_name">Kids Rooms</h3>
              <p data-i18n="p5_desc">Cheerful themes and colors with safe, easy-to-clean material options.</p>
            </div>
            <div class="card product">
              <span class="tag" data-i18n="p6_tag">Custom</span>
              <h3 data-i18n="p6_name">Project Customization</h3>
              <p data-i18n="p6_desc">Custom designs, specification matching, and project-ready supply support.</p>
            </div>
          </div>
        </div>

        <div class="section">
          <div class="card">
            <h2>MOQ / Specifications</h2>
            <p class="small" data-i18n="prod_moq">
              Share your required roll sizes, material type, and finish. We will provide MOQ, lead time, and pricing (wholesale and project supply).
            </p>
            <a class="btn primary" href="#contact" data-i18n="prod_cta_contact">Request Samples/Quote</a>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section" style="padding-top:0;">
      <div class="container grid" style="grid-template-columns:1fr 1fr; align-items:start;">
        <div class="card">
          <span class="badge" data-i18n="contact_badge">Contact</span>
          <h1 style="margin-top:10px;" data-i18n="contact_title">Samples, wholesale pricing, or project supply — contact us.</h1>
          <p data-i18n="contact_p">
            Fill the form and we will respond. For urgent inquiries, use WhatsApp.
          </p>

          <div class="hr"></div>

          <form id="contactForm">
            <div class="two">
              <div>
                <label data-i18n="c_company">Company (optional)</label>
                <input id="cCompany" type="text" placeholder="Company (optional)" />
              </div>
              <div>
                <label data-i18n="c_name">Full name</label>
                <input id="cName" type="text" required placeholder="Full name" />
              </div>
            </div>

            <div class="two">
              <div>
                <label data-i18n="c_email">Email</label>
                <input id="cEmail" type="email" required placeholder="Email" />
              </div>
              <div>
                <label data-i18n="c_phone">Phone (optional)</label>
                <input id="cPhone" type="tel" placeholder="Phone (optional)" />
              </div>
            </div>

            <div>
              <label data-i18n="c_need">Inquiry type</label>
              <select id="cNeed">
                <option value="samples" data-i18n="need1">Samples</option>
                <option value="wholesale" data-i18n="need2">Wholesale pricing</option>
                <option value="project" data-i18n="need3">Project supply</option>
                <option value="distribution" data-i18n="need4">Distribution partnership</option>
              </select>
            </div>

            <div>
              <label data-i18n="c_details">Details</label>
              <textarea id="cDetails" required placeholder="Details"></textarea>
            </div>

            <div class="actions" style="margin-top:14px;">
              <button class="btn primary" type="submit" data-i18n="c_submit">Send</button>
              <a class="btn" href="https://wa.me/9647XXXXXXXXX" target="_blank" rel="noopener" data-i18n="whatsapp_btn">WhatsApp</a>
            </div>

            <div class="small" style="margin-top:10px;" data-i18n="contact_note">
              Note: This form is client-side demo. For real email sending, connect it to a backend or form service.
            </div>
          </form>
        </div>

        <div class="card">
          <h2 data-i18n="contact_info_title">Company Details</h2>
          <div class="small" style="margin-top:10px;">
            <div><strong data-i18n="address_label">Address</strong>: <span data-i18n="city">Babel, Iraq</span></div>
            <div style="margin-top:6px;"><strong data-i18n="phone_label">Phone</strong>: <span data-i18n="phone_value">+964 7XX XXX XXXX</span></div>
            <div><strong data-i18n="email_label">Email</strong>: <span data-i18n="email_value">info@alwadaq-wallpaper.com</span></div>
          </div>

          <div class="hr"></div>

          <h3 style="margin:0 0 10px;" data-i18n="map_title">Location on Map</h3>
          <iframe
            title="Al-Wadaq Location"
            style="width:100%;height:280px;border:0;border-radius:16px;"
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
            src="https://www.google.com/maps?q=Babel%20Iraq&output=embed">
          </iframe>

          <div class="small" style="margin-top:10px;" data-i18n="map_note">
            You can replace the map query with your exact factory location for accuracy.
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <div class="row">
        <div>
          <div class="brand" style="margin-bottom:8px;">
            <span class="logo" aria-hidden="true"></span>
            <span>Al-Wadaq</span>
          </div>
          <div class="small" data-i18n="footer_tagline">Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq</div>
        </div>
        <div class="small">
          <div><span data-i18n="phone_label">Phone</span>: <span data-i18n="phone_value">+964 7XX XXX XXXX</span></div>
          <div><span data-i18n="email_label">Email</span>: <span data-i18n="email_value">info@alwadaq-wallpaper.com</span></div>
          <div>© <span id="year"></span> Al-Wadaq — <span data-i18n="footer_rights">All rights reserved</span></div>
        </div>
      </div>
    </div>
  </footer>

  <div id="toast" class="toast" role="status" aria-live="polite"></div>

  <script>
    /* ---------------------------
       i18n Dictionary (AR/EN)
    ----------------------------*/
    const DICT = {
      ar: {
        nav_home: "الرئيسية",
        nav_about: "من نحن",
        nav_products: "المنتجات",
        nav_contact: "اتصل بنا",
        home_cta_quote: "طلب عرض سعر",
        home_cta_products: "عرض المنتجات",

        home_badge: "مصنع ورق جدران — جودة وتصاميم حديثة",
        home_title: "شركة الودق لصناعة ورق الجدران المحدودة",
        home_sub: "نصنّع ورق جدران عالي الجودة بخامات وتشطيبات متنوعة للمشاريع السكنية والتجارية داخل العراق.",
        home_why_title: "لماذا الودق؟",
        home_why_1_t: "جودة قابلة للقياس",
        home_why_1_d: "ضبط السماكة وثبات اللون وجودة السطح.",
        home_why_2_t: "تنوع الخامات",
        home_why_2_d: "فينيل، غير منسوج، وخيارات متعددة لظروف مختلفة.",
        home_why_3_t: "جاهزية التوريد",
        home_why_3_d: "إدارة طلبات وجدولة تسليم للمشاريع والموزعين.",

        kpi1: "تصاميم متعددة",
        kpi2: "خامات وتشطيبات",
        kpi3: "توريد للمشاريع",
        kpi4: "رقابة جودة",
        kpi_suffix: "—",

        about_badge: "من نحن",
        about_title: "تصنيع محلي بجودة موثوقة وتوريد مستقر.",
        about_p: "تعمل شركة الودق في محافظة بابل، العراق، وتزوّد السوق بورق الجدران للاستخدام السكني والتجاري عبر الموزعين وشركاء المشاريع.",
        about_vision_t: "رؤيتنا",
        about_vision_p: "أن نكون العلامة المحلية الرائدة في العراق في مجال ورق الجدران، مع جودة ثابتة وتصاميم حديثة وتوريد موثوق.",
        about_values_t: "قيمنا",
        about_val1: "الجودة والانضباط التشغيلي.",
        about_val2: "الوضوح في المواصفات والطلبات.",
        about_val3: "الابتكار في التصميم والخامات.",
        about_val4: "خدمة العملاء وشراكات التوريد.",
        about_note: "ملاحظة: استبدل الهاتف/الإيميل الافتراضيين ببيانات الشركة الحقيقية قبل النشر.",

        prod_badge: "المنتجات",
        prod_title: "منتجات ورق جدران بخامات وخيارات تشطيب متعددة.",
        prod_p: "اختر الفئة المناسبة واطلب عينات أو عرض سعر.",
        p1_tag: "فينيل",
        p1_name: "ورق جدران فينيل",
        p1_desc: "مقاومة أفضل للرطوبة ومتانة أعلى؛ مناسب للأماكن كثيرة الاستخدام.",
        p2_tag: "غير منسوج",
        p2_name: "ورق جدران Non-woven",
        p2_desc: "أسهل في التركيب والإزالة؛ قابل للتنفس وثابت الأبعاد.",
        p3_tag: "كلاسيك",
        p3_name: "مجموعة كلاسيكية",
        p3_desc: "نقوش تقليدية ولمسات فاخرة للديكورات الرسمية.",
        p4_tag: "مودرن",
        p4_name: "مجموعة حديثة",
        p4_desc: "تصاميم عصرية وخطوط نظيفة للمنازل والمكاتب الحديثة.",
        p5_tag: "أطفال",
        p5_name: "غرف الأطفال",
        p5_desc: "ألوان مبهجة وخيارات آمنة وسهلة التنظيف.",
        p6_tag: "مخصص",
        p6_name: "تخصيص للمشاريع",
        p6_desc: "تصاميم مخصصة ومطابقة مواصفات ودعم توريد للمشاريع.",
        prod_moq: "أرسل قياسات الرول والخامة والتشطيب المطلوب، ونزوّدك بالحد الأدنى للطلب ومدة التنفيذ والتسعير (جملة/مشاريع).",
        prod_cta_contact: "طلب عينات/عرض سعر",

        contact_badge: "اتصل بنا",
        contact_title: "عينات، تسعير جملة، أو توريد مشاريع — تواصل معنا.",
        contact_p: "املأ النموذج وسنرد عليك. للاستفسارات العاجلة استخدم واتساب.",
        contact_info_title: "بيانات الشركة",
        address_label: "العنوان",
        city: "بابل، العراق",
        phone_label: "الهاتف",
        phone_value: "+964 7XX XXX XXXX",
        email_label: "الإيميل",
        email_value: "info@alwadaq-wallpaper.com",
        map_title: "الموقع على الخريطة",
        map_note: "يمكنك استبدال الاستعلام بموقع المصنع الدقيق لزيادة الدقة.",

        c_company: "الشركة (اختياري)",
        c_name: "الاسم الكامل",
        c_email: "البريد الإلكتروني",
        c_phone: "الهاتف (اختياري)",
        c_need: "نوع الاستفسار",
        c_details: "التفاصيل",
        c_submit: "إرسال",
        need1: "عينات",
        need2: "أسعار الجملة",
        need3: "توريد مشروع",
        need4: "شراكة توزيع",
        whatsapp_btn: "واتساب",
        contact_note: "ملاحظة: هذا نموذج تجريبي يعمل داخل المتصفح. للإرسال الحقيقي تحتاج ربطه بخدمة/سيرفر.",

        footer_tagline: "شركة الودق لصناعة ورق الجدران المحدودة — بابل، العراق",
        footer_rights: "جميع الحقوق محفوظة"
      },

      en: {
        nav_home: "Home",
        nav_about: "About",
        nav_products: "Products",
        nav_contact: "Contact",
        home_cta_quote: "Request a Quote",
        home_cta_products: "View Products",

        home_badge: "Wallpaper manufacturer — quality and modern designs",
        home_title: "Al-Wadaq Wallpaper Manufacturing Co. Ltd",
        home_sub: "We manufacture high-quality wallpapers with a wide range of materials and finishes for residential and commercial projects in Iraq.",
        home_why_title: "Why Al-Wadaq?",
        home_why_1_t: "Measurable quality",
        home_why_1_d: "Controls for thickness, color consistency, and surface finish.",
        home_why_2_t: "Material variety",
        home_why_2_d: "Vinyl, non-woven, and tailored options for different environments.",
        home_why_3_t: "Supply readiness",
        home_why_3_d: "Order management and delivery scheduling for projects and distributors.",

        kpi1: "Multiple designs",
        kpi2: "Materials & finishes",
        kpi3: "Project supply",
        kpi4: "Quality control",
        kpi_suffix: "—",

        about_badge: "About",
        about_title: "Local manufacturing with dependable quality and stable supply.",
        about_p: "Al-Wadaq Wallpaper Manufacturing Co. Ltd operates in Babel Province, Iraq, supplying wallpapers for residential and commercial applications through distributors and project partners.",
        about_vision_t: "Our Vision",
        about_vision_p: "To be Iraq’s leading locally manufactured wallpaper brand, recognized for consistent quality, modern design, and reliable supply.",
        about_values_t: "Our Values",
        about_val1: "Quality and operational discipline.",
        about_val2: "Specification and order transparency.",
        about_val3: "Innovation in design and materials.",
        about_val4: "Customer service and supply partnerships.",
        about_note: "Note: Replace placeholders (phone/email) with real company contacts before publishing.",

        prod_badge: "Products",
        prod_title: "Wallpaper products across materials and finish options.",
        prod_p: "Choose the suitable category and request samples or a quote.",
        p1_tag: "Vinyl",
        p1_name: "Vinyl Wallpaper",
        p1_desc: "Better moisture resistance and durability; suitable for high-traffic areas.",
        p2_tag: "Non-woven",
        p2_name: "Non-woven Wallpaper",
        p2_desc: "Easier installation and removal; breathable with good dimensional stability.",
        p3_tag: "Classic",
        p3_name: "Classic Collection",
        p3_desc: "Traditional patterns, textures, and premium looks for formal interiors.",
        p4_tag: "Modern",
        p4_name: "Modern Collection",
        p4_desc: "Clean lines and contemporary designs for modern homes and offices.",
        p5_tag: "Kids",
        p5_name: "Kids Rooms",
        p5_desc: "Cheerful themes and colors with safe, easy-to-clean material options.",
        p6_tag: "Custom",
        p6_name: "Project Customization",
        p6_desc: "Custom designs, specification matching, and project-ready supply support.",
        prod_moq: "Share your roll sizes, material type, and finish. We will provide MOQ, lead time, and pricing (wholesale and project supply).",
        prod_cta_contact: "Request Samples/Quote",

        contact_badge: "Contact",
        contact_title: "Samples, wholesale pricing, or project supply — contact us.",
        contact_p: "Fill the form and we will respond. For urgent inquiries, use WhatsApp.",
        contact_info_title: "Company Details",
        address_label: "Address",
        city: "Babel, Iraq",
        phone_label: "Phone",
        phone_value: "+964 7XX XXX XXXX",
        email_label: "Email",
        email_value: "info@alwadaq-wallpaper.com",
        map_title: "Location on Map",
        map_note: "You can replace the map query with your exact factory location for accuracy.",

        c_company: "Company (optional)",
        c_name: "Full name",
        c_email: "Email",
        c_phone: "Phone (optional)",
        c_need: "Inquiry type",
        c_details: "Details",
        c_submit: "Send",
        need1: "Samples",
        need2: "Wholesale pricing",
        need3: "Project supply",
        need4: "Distribution partnership",
        whatsapp_btn: "WhatsApp",
        contact_note: "Note: This is a client-side demo form. For real sending, connect to a backend or form service.",

        footer_tagline: "Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq",
        footer_rights: "All rights reserved"
      }
    };

    /* ---------------------------
       Core helpers
    ----------------------------*/
    const toastEl = document.getElementById("toast");
    const navLinks = document.getElementById("navLinks");
    const menuBtn = document.getElementById("menuBtn");
    const langBtn = document.getElementById("langBtn");
    const yearEl = document.getElementById("year");

    function toast(msg){
      if(!toastEl) return;
      toastEl.textContent = msg;
      toastEl.classList.add("show");
      setTimeout(()=> toastEl.classList.remove("show"), 2400);
    }

    function setLang(lang){
      const dict = DICT[lang];
      if(!dict) return;

      document.documentElement.lang = lang;
      document.documentElement.dir  = (lang === "ar") ? "rtl" : "ltr";
      langBtn.textContent = (lang === "ar") ? "English" : "العربية";

      // text
      document.querySelectorAll("[data-i18n]").forEach(el=>{
        const k = el.getAttribute("data-i18n");
        if(dict[k]) el.textContent = dict[k];
      });

      // select options (by data-i18n on option itself)
      document.querySelectorAll("option[data-i18n]").forEach(opt=>{
        const k = opt.getAttribute("data-i18n");
        if(dict[k]) opt.textContent = dict[k];
      });

      // placeholders (lightweight approach: map by label keys)
      const phMap = {
        c_company: "cCompany",
        c_name: "cName",
        c_email: "cEmail",
        c_phone: "cPhone",
        c_details: "cDetails"
      };
      Object.entries(phMap).forEach(([k, id])=>{
        const el = document.getElementById(id);
        if(el && dict[k]) el.placeholder = dict[k];
      });

      // persist
      localStorage.setItem("lang", lang);
    }

    // Mobile menu
    if(menuBtn && navLinks){
      menuBtn.addEventListener("click", ()=>{
        navLinks.classList.toggle("open");
      });

      // close menu on link click (mobile)
      navLinks.querySelectorAll("a[data-nav]").forEach(a=>{
        a.addEventListener("click", ()=> navLinks.classList.remove("open"));
      });
    }

    // Active nav link by hash
    function setActiveNav(){
      const hash = location.hash || "#home";
      document.querySelectorAll(".link[data-nav]").forEach(a=>{
        a.classList.toggle("active", a.getAttribute("href") === hash);
      });
    }
    window.addEventListener("hashchange", setActiveNav);

    // Lang toggle
    langBtn?.addEventListener("click", ()=>{
      const current = document.documentElement.lang || "ar";
      setLang(current === "ar" ? "en" : "ar");
      toast(current === "ar" ? "Language: English" : "اللغة: العربية");
    });

    // Footer year
    if(yearEl) yearEl.textContent = new Date().getFullYear();

    // Contact form (demo)
    document.getElementById("contactForm")?.addEventListener("submit", (e)=>{
      e.preventDefault();
      const lang = document.documentElement.lang || "ar";
      toast(lang === "ar" ? "تم الإرسال بنجاح (تجريبي)" : "Sent successfully (demo)");

      // Optional: clear fields
      e.target.reset();
    });

    // Init
    const saved = localStorage.getItem("lang") || "ar";
    setLang(saved);
    setActiveNav();
  </script>
</body>
</html>
