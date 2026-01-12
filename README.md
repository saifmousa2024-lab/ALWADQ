{
  --bg:#f4f7ff;
  --bg2:#eef2ff;
  --card:#ffffff;
  --card2:#f9fbff;
  --stroke:#dbe4ff;
  --text:#1f2937;
  --muted:#5b6b8a;

  --c1:#2563eb;   /* blue */
  --c2:#7c3aed;   /* violet */
  --c3:#ec4899;   /* pink */
  --c4:#22c55e;   /* green */

  --shadow: 0 20px 45px rgba(37,99,235,.15);
  --r:20px;
  --container:1120px;
}

*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color:var(--text);
  background:
    radial-gradient(800px 500px at 10% 0%, rgba(37,99,235,.18), transparent 60%),
    radial-gradient(700px 450px at 90% 10%, rgba(236,72,153,.18), transparent 60%),
    linear-gradient(180deg, var(--bg), var(--bg2));
  line-height:1.65;
}

a{color:inherit; text-decoration:none}
.container{max-width:var(--container); margin:0 auto; padding:0 18px}
.section{padding:60px 0}
.grid{display:grid; gap:16px}

.card{
  background: linear-gradient(180deg, var(--card), var(--card2));
  border:1px solid var(--stroke);
  border-radius: var(--r);
  padding:22px;
  box-shadow: var(--shadow);
}

.hr{height:1px; background:var(--stroke); margin:18px 0}

.badge{
  display:inline-flex;
  padding:7px 12px;
  border-radius:999px;
  border:1px solid var(--stroke);
  background:#f1f5ff;
  color:var(--muted);
  font-weight:700;
}

.small{font-size:.95rem; color:var(--muted)}
h1{margin:12px 0 0; font-size:2.3rem}
h2{margin:0 0 10px; font-size:1.35rem}
h3{margin:12px 0 0; font-size:1.05rem}
p{margin:12px 0 0; color:var(--muted)}

/* NAV */
.nav{
  position:sticky; top:0; z-index:100;
  background: rgba(244,247,255,.9);
  border-bottom:1px solid var(--stroke);
  backdrop-filter: blur(10px);
}

.navbar{
  display:flex; align-items:center; justify-content:space-between;
  padding:14px 0;
}

.brand{
  display:flex; align-items:center; gap:10px;
  font-weight:900;
}

.logo{
  width:36px; height:36px; border-radius:10px;
  background: linear-gradient(135deg, var(--c1), var(--c2));
}

.links{
  display:flex; gap:10px;
  padding:6px;
  border-radius:999px;
  background:#ffffff;
  border:1px solid var(--stroke);
}

.link{
  padding:8px 14px;
  border-radius:999px;
  font-weight:700;
  color:var(--muted);
}

.link.active{
  background: linear-gradient(135deg, var(--c1), var(--c3));
  color:#fff;
}

.nav-actions{display:flex; gap:10px}
.menu-btn{display:none}

/* BUTTONS */
.btn{
  padding:10px 14px;
  border-radius:14px;
  border:1px solid var(--stroke);
  background:#ffffff;
  font-weight:800;
  cursor:pointer;
}

.btn.primary{
  background: linear-gradient(135deg, var(--c1), var(--c2));
  color:#fff;
  border:none;
}

/* HERO */
.hero{
  display:grid;
  grid-template-columns:1.2fr .8fr;
  gap:18px;
}

.kpis{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:12px;
}

.kpi{
  background:#f8faff;
  border:1px solid var(--stroke);
  border-radius:14px;
  padding:12px;
  display:flex;
  justify-content:space-between;
}

/* PRODUCTS */
.products{grid-template-columns:repeat(3,1fr)}
.product .tag{
  background:#eef2ff;
  padding:6px 10px;
  border-radius:999px;
  font-weight:800;
  color:var(--c1);
}

/* FORM */
label{font-weight:800}
input,textarea,select{
  width:100%;
  padding:12px;
  border-radius:14px;
  border:1px solid var(--stroke);
  background:#fff;
}

textarea{min-height:120px}
.two{display:grid; grid-template-columns:1fr 1fr; gap:14px}

/* FOOTER */
.footer{
  border-top:1px solid var(--stroke);
  padding:26px 0;
  background:#f1f5ff;
}

.row{display:flex; justify-content:space-between; flex-wrap:wrap}

/* RESPONSIVE */
@media (max-width:900px){
  .hero{grid-template-columns:1fr}
  .products{grid-template-columns:1fr 1fr}
}
@media (max-width:700px){
  .products{grid-template-columns:1fr}
}
