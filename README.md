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
