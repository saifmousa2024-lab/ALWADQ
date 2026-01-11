 Al-Wadaq (EN) — Vibrant, high-quality UI
   - Bright gradients + glass + crisp spacing
   - Accessible contrast; motion reduced if user prefers
------------------------------------------ */

:root{
  --bg0:#060916;
  --bg1:#0a0f2a;
  --card: rgba(255,255,255,.07);
  --card2: rgba(255,255,255,.05);
  --stroke: rgba(255,255,255,.12);
  --text:#f3f6ff;
  --muted:#b7c0d6;

  --c1:#00e5ff;  /* cyan */
  --c2:#7c4dff;  /* violet */
  --c3:#ff3d81;  /* pink */
  --c4:#ffe66d;  /* warm highlight */
  --ok:#20e3b2;

  --shadow: 0 30px 80px rgba(0,0,0,.45);
  --r:22px;
  --container: 1120px;

  --ring: 0 0 0 4px rgba(0,229,255,.15), 0 0 0 1px rgba(255,255,255,.08) inset;
}

*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  color:var(--text);
  background:
    radial-gradient(1100px 650px at 18% -10%, rgba(0,229,255,.22), transparent 55%),
    radial-gradient(900px 520px at 92% 6%, rgba(255,61,129,.18), transparent 60%),
    radial-gradient(900px 520px at 70% 110%, rgba(124,77,255,.20), transparent 62%),
    linear-gradient(180deg, var(--bg0), var(--bg1));
  line-height:1.65;
}

a{color:inherit; text-decoration:none}
img{max-width:100%; display:block}
.container{max-width:var(--container); margin:0 auto; padding:0 18px}

.section{padding:58px 0}
.grid{display:grid; gap:16px}

.card{
  background: linear-gradient(180deg, var(--card), var(--card2));
  border:1px solid var(--stroke);
  border-radius: var(--r);
  padding:20px;
  box-shadow: var(--shadow);
  backdrop-filter: blur(12px);
  position:relative;
  overflow:hidden;
}

.card::before{
  content:"";
  position:absolute;
  inset:-2px;
  background:
    radial-gradient(600px 240px at 20% 0%, rgba(0,229,255,.18), transparent 60%),
    radial-gradient(480px 220px at 90% 15%, rgba(255,61,129,.14), transparent 62%),
    radial-gradient(540px 260px at 65% 120%, rgba(124,77,255,.14), transparent 60%);
  opacity:.65;
  pointer-events:none;
  filter:saturate(1.15);
}

.card > *{position:relative}

.hr{height:1px; background:rgba(255,255,255,.14); margin:18px 0}

.badge{
  display:inline-flex;
  align-items:center;
  gap:8px;
  padding:7px 11px;
  border-radius:999px;
  border:1px solid rgba(255,255,255,.16);
  background: rgba(0,0,0,.18);
  color:var(--muted);
  font-size:.88rem;
  letter-spacing:.2px;
}

.badge .dot{
  width:9px; height:9px; border-radius:50%;
  background: linear-gradient(135deg, var(--c1), var(--c3));
  box-shadow: 0 0 0 3px rgba(0,229,255,.12);
}

.small{font-size:.94rem; color:var(--muted)}
h1{margin:12px 0 0; font-size:2.25rem; line-height:1.15; letter-spacing:-.3px}
h2{margin:0 0 10px; font-size:1.35rem; letter-spacing:-.2px}
h3{margin:12px 0 0; font-size:1.05rem}
p{margin:12px 0 0; color:var(--muted)}

/* -----------------------------------------
   NAV
------------------------------------------ */
.nav{
  position:sticky; top:0; z-index:100;
  background: rgba(6,9,22,.55);
  border-bottom: 1px solid rgba(255,255,255,.12);
  backdrop-filter: blur(14px);
}

.navbar{
  display:flex; align-items:center; justify-content:space-between;
  padding:12px 0; gap:12px;
}

.brand{
  display:flex; align-items:center; gap:10px;
  font-weight:900;
  letter-spacing:.4px;
}

.logo{
  width:36px; height:36px; border-radius:12px;
  background:
    radial-gradient(circle at 35% 35%, rgba(255,255,255,.95), rgba(255,255,255,0) 60%),
    conic-gradient(from 220deg, var(--c1), var(--c2), var(--c3), var(--c1));
  box-shadow: 0 18px 45px rgba(0,229,255,.16);
  position:relative;
}

.logo::after{
  content:"";
  position:absolute; inset:1px;
  border-radius:11px;
  background: rgba(0,0,0,.08);
  mix-blend-mode: overlay;
}

.links{
  display:flex; align-items:center; gap:10px;
  padding:8px 10px;
  border-radius:999px;
  border:1px solid rgba(255,255,255,.14);
  background: rgba(0,0,0,.20);
}

.link{
  padding:8px 12px;
  border-radius:999px;
  color: var(--muted);
  font-weight:800;
  font-size:.95rem;
  transition: .18s ease;
}

.link:hover{
  color: var(--text);
  background: rgba(255,255,255,.06);
}

.link.active{
  color: var(--text);
  background:
    linear-gradient(135deg, rgba(0,229,255,.20), rgba(124,77,255,.16));
  border: 1px solid rgba(0,229,255,.24);
}

.nav-actions{display:flex; align-items:center; gap:10px}

.menu-btn{display:none}

/* -----------------------------------------
   Buttons
------------------------------------------ */
.btn{
  border:1px solid rgba(255,255,255,.14);
  background: rgba(0,0,0,.18);
  color:var(--text);
  padding:10px 13px;
  border-radius:14px;
  cursor:pointer;
  font-weight:900;
  transition:.2s ease;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  gap:8px;
}

.btn:hover{
  transform: translateY(-1px);
  box-shadow: 0 14px 30px rgba(0,0,0,.30);
  background: rgba(255,255,255,.06);
}

.btn:focus-visible{
  outline:none;
  box-shadow: var(--ring);
}

.btn.primary{
  border-color: rgba(0,229,255,.28);
  background:
    linear-gradient(135deg, rgba(0,229,255,.26), rgba(124,77,255,.18), rgba(255,61,129,.16));
}

.btn.primary:hover{
  filter:saturate(1.1);
}

/* -----------------------------------------
   Hero
------------------------------------------ */
.hero{
  display:grid;
  grid-template-columns: 1.15fr .85fr;
  gap:16px;
  align-items:stretch;
}

.hero-visual{
  position:relative;
  min-height: 360px;
}

.hero-visual .glow{
  position:absolute; inset:-40px;
  background:
    radial-gradient(300px 300px at 30% 30%, rgba(0,229,255,.38), transparent 65%),
    radial-gradient(320px 320px at 70% 40%, rgba(255,61,129,.30), transparent 66%),
    radial-gradient(340px 340px at 55% 85%, rgba(124,77,255,.32), transparent 65%);
  filter: blur(12px);
  opacity:.95;
}

.hero-visual .panel{
  position:absolute;
  inset:16px;
  border-radius: calc(var(--r) - 2px);
  background: rgba(0,0,0,.18);
  border: 1px solid rgba(255,255,255,.14);
  overflow:hidden;
}

.hero-visual .panel::before{
  content:"";
  position:absolute;
  inset:-2px;
  background:
    linear-gradient(120deg, rgba(0,229,255,.16), transparent 40%),
    linear-gradient(240deg, rgba(255,61,129,.14), transparent 45%),
    radial-gradient(600px 260px at 50% 0%, rgba(255,230,109,.10), transparent 65%);
  opacity:.9;
}

.hero-visual .gridlines{
  position:absolute; inset:0;
  background-image:
    linear-gradient(rgba(255,255,255,.07) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.07) 1px, transparent 1px);
  background-size: 44px 44px;
  opacity:.35;
  mix-blend-mode: overlay;
}

.hero-visual .caption{
  position:absolute;
  left:18px; right:18px; bottom:18px;
  display:flex;
  gap:12px;
  flex-wrap:wrap;
}

.pill{
  display:inline-flex;
  align-items:center;
  gap:8px;
  padding:9px 11px;
  border-radius:999px;
  border:1px solid rgba(255,255,255,.14);
  background: rgba(0,0,0,.22);
  color: var(--text);
  font-weight:900;
  font-size:.92rem;
}

.pill svg{opacity:.9}

/* -----------------------------------------
   KPIs
------------------------------------------ */
.kpis{
  display:grid;
  grid-template-columns: repeat(2, 1fr);
  gap:10px;
}
.kpi{
  border:1px solid rgba(255,255,255,.14);
  border-radius:16px;
  padding:12px 12px;
  background: rgba(0,0,0,.16);
  display:flex;
  justify-content:space-between;
  gap:10px;
  font-size:.95rem;
}
.kpi strong{color:var(--text)}
.kpi span{color:var(--muted)}

/* -----------------------------------------
   Feature cards
------------------------------------------ */
.features{grid-template-columns: repeat(3, 1fr)}
.feature{
  padding:18px;
  border-radius:18px;
  border:1px solid rgba(255,255,255,.12);
  background: rgba(0,0,0,.14);
}
.icon{
  width:40px; height:40px;
  border-radius:14px;
  display:flex; align-items:center; justify-content:center;
  border:1px solid rgba(255,255,255,.14);
  background: linear-gradient(135deg, rgba(0,229,255,.22), rgba(255,61,129,.12));
  box-shadow: 0 18px 40px rgba(0,0,0,.35);
}

/* -----------------------------------------
   Products
------------------------------------------ */
.products{grid-template-columns: repeat(3, 1fr)}
.product .tag{
  display:inline-flex;
  padding:7px 11px;
  border-radius:999px;
  border:1px solid rgba(0,229,255,.25);
  background: rgba(0,229,255,.10);
  color: var(--text);
  font-weight:950;
  font-size:.85rem;
}
.product p{margin-top:10px}

/* -----------------------------------------
   Forms
------------------------------------------ */
label{display:block; font-weight:950; margin:12px 0 6px}
input, textarea, select{
  width:100%;
  padding:12px 12px;
  border-radius:16px;
  border:1px solid rgba(255,255,255,.14);
  background: rgba(0,0,0,.18);
  color:var(--text);
  outline:none;
}
input:focus, textarea:focus, select:focus{box-shadow: var(--ring)}
textarea{min-height:128px; resize:vertical}
.two{display:grid; grid-template-columns:1fr 1fr; gap:14px}
.notice{
  border:1px solid rgba(255,255,255,.14);
  background: rgba(0,0,0,.18);
  border-radius: 18px;
  padding:14px 14px;
  color: var(--muted);
  margin-top: 12px;
}

/* -----------------------------------------
   Footer
------------------------------------------ */
.footer{
  border-top:1px solid rgba(255,255,255,.12);
  padding:26px 0;
  background: rgba(0,0,0,.18);
}
.row{
  display:flex; gap:16px; align-items:flex-start; justify-content:space-between;
  flex-wrap:wrap;
}

/* Toast */
.toast{
  position: fixed;
  left: 16px;
  bottom: 16px;
  min-width: 260px;
  max-width: 360px;
  padding: 12px 14px;
  border-radius: 16px;
  background: rgba(0,0,0,.60);
  border: 1px solid rgba(255,255,255,.16);
  color: var(--text);
  box-shadow: var(--shadow);
  opacity: 0;
  transform: translateY(12px);
  pointer-events:none;
  transition: .25s ease;
}
.toast.show{opacity:1; transform: translateY(0)}

/* Section anchor offset for sticky nav */
section[id]{scroll-margin-top: 92px}

/* Responsive */
@media (max-width: 1020px){
  .hero{grid-template-columns:1fr}
  .features{grid-template-columns: 1fr}
  .products{grid-template-columns: repeat(2, 1fr)}
}
@media (max-width: 820px){
  .menu-btn{display:inline-block}
  .links{
    display:none;
    position:absolute;
    top:60px;
    left:18px;
    right:18px;
    border-radius:18px;
    flex-direction:column;
    align-items:stretch;
    padding:10px;
  }
  .links.open{display:flex}
  .navbar{position:relative}
  .two{grid-template-columns:1fr}
  .products{grid-template-columns: 1fr}
}

/* Reduced motion */
@media (prefers-reduced-motion: reduce){
  *{scroll-behavior:auto}
  .btn:hover{transform:none}
}
