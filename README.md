(function () {
  const LS_LANG = "alwadaq_lang";

  const I18N = {
    ar: {
      dir: "rtl",
      nav_home: "الرئيسية",
      nav_about: "من نحن",
      nav_products: "المنتجات",
      nav_contact: "تواصل معنا",
      lang_btn: "English",

      // Shared footer
      footer_tagline: "شركة الودق لصناعة ورق الجدران المحدودة — العراق، بابل",
      footer_rights: "جميع الحقوق محفوظة",
      phone_label: "الهاتف",
      email_label: "البريد",
      address_label: "العنوان",

      // Home
      home_badge: "مصنع ورق جدران — جودة وتصاميم معاصرة",
      home_title: "شركة الودق لصناعة ورق الجدران المحدودة",
      home_sub:
        "نصنع ورق جدران بمواصفات تشغيلية عالية، مع تنوع واسع في الخامات والتشطيبات. نخدم الأسواق المحلية والمشاريع التجارية والسكنية في العراق.",
      home_cta_products: "استعراض المنتجات",
      home_cta_quote: "اطلب عرض سعر",
      kpi1: "تصاميم متعددة",
      kpi2: "خامات وتشطيبات",
      kpi3: "توريد للمشاريع",
      kpi4: "ضبط جودة",

      home_why_title: "لماذا الودق؟",
      home_why_1_t: "جودة قابلة للقياس",
      home_why_1_d: "رقابة على السماكة، ثبات اللون، ومقاومة الاستخدام وفق متطلبات المشاريع.",
      home_why_2_t: "تنوع في المواد",
      home_why_2_d: "Vinyl، Non-woven، وتشطيبات مطفية/لامعة حسب خطوط المنتج.",
      home_why_3_t: "جاهزية توريد",
      home_why_3_d: "إدارة طلبات وجدولة تسليم لدعم المقاولين والموزعين.",

      home_services_title: "ماذا نقدم؟",
      home_services_li1: "ورق جدران للاستخدام السكني والتجاري.",
      home_services_li2: "تشكيلات مودرن وكلاسيك وخيارات حسب الطلب للمشاريع.",
      home_services_li3: "توصيات تركيب وخدمات دعم للموزعين.",
      home_services_li4: "تسعير بالجملة للموزعين وشركات التنفيذ.",

      // About
      about_badge: "من نحن",
      about_title: "خبرة صناعية محلية تدعم جودة المنتج واستقرار التوريد.",
      about_p:
        "شركة الودق لصناعة ورق الجدران المحدودة تعمل في محافظة بابل — العراق. نركز على جودة المواد، دقة الطباعة، وثبات الألوان مع تطوير مستمر في التصاميم بما يلائم ذوق السوق.",
      about_vision_t: "رؤيتنا",
      about_vision_p: "أن نكون الخيار الأول لورق الجدران المصنّع محلياً في العراق من حيث الجودة والتنوع.",
      about_values_t: "قيمنا",
      about_val1: "الجودة والانضباط التشغيلي.",
      about_val2: "الشفافية في المواصفات والطلب.",
      about_val3: "الابتكار في التصميم والخامة.",
      about_val4: "خدمة العملاء وشراكات التوريد.",

      // Products
      prod_badge: "المنتجات",
      prod_title: "منتجات ورق جدران بخيارات متعددة للخامة والتشطيب.",
      prod_p:
        "اختر الفئة المناسبة واطلب عينات أو عرض سعر. يمكن توفير مواصفات خاصة للمشاريع حسب الكمية.",
      prod_cta_contact: "اطلب عينات/سعر",

      p1_tag: "Vinyl",
      p1_name: "ورق جدران فينيل",
      p1_desc: "مقاومة أعلى للرطوبة وسهولة تنظيف، مناسب للمنازل والمكاتب.",

      p2_tag: "Non-woven",
      p2_name: "Non-woven",
      p2_desc: "تركيب أسهل وثبات أفضل، مناسب لمساحات كبيرة ومشاريع.",

      p3_tag: "Classic",
      p3_name: "كلاسيك",
      p3_desc: "نقوش كلاسيكية وألوان متوازنة للديكورات التقليدية.",

      p4_tag: "Modern",
      p4_name: "مودرن",
      p4_desc: "تصاميم عصرية وخطوط بسيطة لمظهر حديث.",

      p5_tag: "Kids",
      p5_name: "غرف الأطفال",
      p5_desc: "ألوان مبهجة وخيارات آمنة مناسبة لغرف الأطفال.",

      p6_tag: "Custom",
      p6_name: "حسب الطلب للمشاريع",
      p6_desc: "تنفيذ تصميم/مواصفة خاصة عند توفر الحد الأدنى للطلب.",

      // Contact
      contact_badge: "تواصل معنا",
      contact_title: "للعينات، التسعير بالجملة، أو توريد المشاريع — تواصل الآن.",
      contact_p:
        "املأ النموذج وسنرد عليك. في الموقع الحقيقي يتم ربط النموذج ببريد الشركة/CRM (هنا نسخة جاهزة للربط).",
      c_company: "الشركة (اختياري)",
      c_name: "الاسم",
      c_email: "البريد الإلكتروني",
      c_phone: "الهاتف (اختياري)",
      c_need: "نوع الطلب",
      c_details: "تفاصيل الطلب",
      c_submit: "إرسال",

      need1: "عينات",
      need2: "تسعير جملة",
      need3: "مشروع (توريد)",
      need4: "شراكة توزيع",

      contact_info_title: "بيانات الشركة",
      city: "العراق — بابل",
      map_title: "الموقع على الخريطة",
      whatsapp_btn: "واتساب"
    },

    en: {
      dir: "ltr",
      nav_home: "Home",
      nav_about: "About",
      nav_products: "Products",
      nav_contact: "Contact",
      lang_btn: "العربية",

      footer_tagline: "Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq",
      footer_rights: "All rights reserved",
      phone_label: "Phone",
      email_label: "Email",
      address_label: "Address",

      home_badge: "Wallpaper manufacturer — quality and modern designs",
      home_title: "Al-Wadaq Wallpaper Manufacturing Co. Ltd",
      home_sub:
        "We manufacture high-quality wallpapers with a wide range of materials and finishes. We serve local Iraqi markets and support residential and commercial projects.",
      home_cta_products: "View Products",
      home_cta_quote: "Request a Quote",
      kpi1: "Multiple designs",
      kpi2: "Materials & finishes",
      kpi3: "Project supply",
      kpi4: "Quality control",

      home_why_title: "Why Al-Wadaq?",
      home_why_1_t: "Measurable quality",
      home_why_1_d: "Controls for thickness, color consistency, and durability based on project needs.",
      home_why_2_t: "Material variety",
      home_why_2_d: "Vinyl, non-woven, and matte/gloss finishes across product lines.",
      home_why_3_t: "Supply readiness",
      home_why_3_d: "Order management and delivery scheduling for contractors and distributors.",

      home_services_title: "What we offer",
      home_services_li1: "Wallpaper for residential and commercial use.",
      home_services_li2: "Modern/classic collections and project-ready customization options.",
      home_services_li3: "Installation guidance and distributor support.",
      home_services_li4: "Wholesale pricing for distributors and contractors.",

      about_badge: "About",
      about_title: "Local manufacturing with dependable quality and stable supply.",
      about_p:
        "Al-Wadaq Wallpaper Manufacturing Co. Ltd operates in Babel Province, Iraq. We focus on material quality, printing accuracy, and color consistency, with continuous design development to match market taste.",
      about_vision_t: "Our Vision",
      about_vision_p: "To be Iraq’s leading locally manufactured wallpaper brand in quality and variety.",
      about_values_t: "Our Values",
      about_val1: "Quality and operational discipline.",
      about_val2: "Specification and order transparency.",
      about_val3: "Innovation in design and materials.",
      about_val4: "Customer service and supply partnerships.",

      prod_badge: "Products",
      prod_title: "Wallpaper products across materials and finish options.",
      prod_p:
        "Choose the suitable category and request samples or a quote. Project-specific specs are available based on quantity.",
      prod_cta_contact: "Request Samples/Quote",

      p1_tag: "Vinyl",
      p1_name: "Vinyl Wallpaper",
      p1_desc: "Better moisture resistance and easy cleaning for homes and offices.",

      p2_tag: "Non-woven",
      p2_name: "Non-woven Wallpaper",
      p2_desc: "Easier installation and strong stability for large areas and projects.",

      p3_tag: "Classic",
      p3_name: "Classic Collection",
      p3_desc: "Traditional patterns and balanced colors for classic interiors.",

      p4_tag: "Modern",
      p4_name: "Modern Collection",
      p4_desc: "Clean lines and contemporary designs for a modern look.",

      p5_tag: "Kids",
      p5_name: "Kids Rooms",
      p5_desc: "Cheerful colors and safe options for children’s rooms.",

      p6_tag: "Custom",
      p6_name: "Project Customization",
      p6_desc: "Custom design/specification available subject to minimum order quantity.",

      contact_badge: "Contact",
      contact_title: "Samples, wholesale pricing, or project supply — contact us.",
      contact_p:
        "Fill the form and we will respond. This template is ready to connect to your email/CRM in production.",
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

      contact_info_title: "Company Details",
      city: "Babel, Iraq",
      map_title: "Location on Map",
      whatsapp_btn: "WhatsApp"
    }
  };

  function toast(msg) {
    const el = document.getElementById("toast");
    if (!el) return alert(msg);
    el.textContent = msg;
    el.classList.add("show");
    setTimeout(() => el.classList.remove("show"), 2800);
  }

  function getLang() {
    return localStorage.getItem(LS_LANG) || "ar";
  }

  function setLang(lang) {
    localStorage.setItem(LS_LANG, lang);
  }

  function applyI18n(lang) {
    const dict = I18N[lang] || I18N.ar;

    // dir + lang
    document.documentElement.setAttribute("lang", lang);
    document.documentElement.setAttribute("dir", dict.dir);

    // Apply all data-i18n keys
    document.querySelectorAll("[data-i18n]").forEach(el => {
      const key = el.getAttribute("data-i18n");
      if (dict[key] !== undefined) el.textContent = dict[key];
    });

    // placeholders
    document.querySelectorAll("[data-i18n-placeholder]").forEach(el => {
      const key = el.getAttribute("data-i18n-placeholder");
      if (dict[key] !== undefined) el.setAttribute("placeholder", dict[key]);
    });

    // select options
    document.querySelectorAll("[data-i18n-value]").forEach(el => {
      const key = el.getAttribute("data-i18n-value");
      if (dict[key] !== undefined) el.textContent = dict[key];
    });

    // language button label
    const btn = document.getElementById("langBtn");
    if (btn) btn.textContent = dict.lang_btn;

    // Active link highlight
    const path = (location.pathname.split("/").pop() || "index.html").toLowerCase();
    document.querySelectorAll('[data-nav]').forEach(a => {
      const target = (a.getAttribute("href") || "").toLowerCase();
      a.classList.toggle("active", target === path);
    });
  }

  // Mobile menu
  const menuBtn = document.getElementById("menuBtn");
  const navLinks = document.getElementById("navLinks");
  if (menuBtn && navLinks) {
    menuBtn.addEventListener("click", () => navLinks.classList.toggle("open"));
  }

  // Language toggle
  const langBtn = document.getElementById("langBtn");
  if (langBtn) {
    langBtn.addEventListener("click", () => {
      const current = getLang();
      const next = current === "ar" ? "en" : "ar";
      setLang(next);
      applyI18n(next);
      toast(next === "ar" ? "تم التبديل للعربية." : "Switched to English.");
    });
  }

  // Contact form (demo-ready; connect to backend/email later)
  const contactForm = document.getElementById("contactForm");
  if (contactForm) {
    contactForm.addEventListener("submit", (e) => {
      e.preventDefault();
      const name = document.getElementById("cName")?.value?.trim();
      const email = document.getElementById("cEmail")?.value?.trim();
      const details = document.getElementById("cDetails")?.value?.trim();

      if (!name || !email || !details) {
        toast(getLang() === "ar" ? "يرجى إدخال الاسم والبريد والتفاصيل." : "Please enter name, email, and details.");
        return;
      }

      // Store locally as a demo; replace with API call in production
      const payload = {
        company: document.getElementById("cCompany")?.value?.trim() || "",
        name,
        email,
        phone: document.getElementById("cPhone")?.value?.trim() || "",
        need: document.getElementById("cNeed")?.value || "",
        details,
        at: new Date().toISOString()
      };

      const key = "alwadaq_leads";
      const items = JSON.parse(localStorage.getItem(key) || "[]");
      items.unshift(payload);
      localStorage.setItem(key, JSON.stringify(items));

      toast(getLang() === "ar" ? "تم إرسال الطلب بنجاح." : "Your request has been sent.");
      contactForm.reset();
    });
  }

  // Init
  const y = document.getElementById("year");
  if (y) y.textContent = new Date().getFullYear();
  applyI18n(getLang());
})();
