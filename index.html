<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sèche · Programme Personnalisé</title>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;500;600;700&family=DM+Sans:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#FFFFFF;
  --bg2:#F5F5F3;
  --bg3:#EBEBEA;
  --ink:#0A0A0A;
  --ink2:#3D3D3D;
  --ink3:#888;
  --fire:#FF4500;
  --fire2:#FF6B35;
  --fire-dim:rgba(255,69,0,.08);
  --blue:#1A56DB;
  --blue-dim:rgba(26,86,219,.08);
  --green:#0D7A5F;
  --green-dim:rgba(13,122,95,.08);
  --gold:#D4A017;
  --border:#E5E5E3;
  --border2:#F0F0EE;
  --r:12px;
  --r-sm:7px;
  --H:'Oswald',sans-serif;
  --B:'DM Sans',sans-serif;
  --shadow:0 1px 3px rgba(0,0,0,.08),0 4px 16px rgba(0,0,0,.06);
  --shadow-up:0 8px 32px rgba(0,0,0,.12);
}

html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--ink);font-family:var(--B);-webkit-font-smoothing:antialiased;overflow-x:hidden}

/* ── HERO ── */
.hero{
  background:var(--ink);
  color:#fff;
  padding:32px 20px 0;
  position:relative;overflow:hidden;
}
.hero::after{
  content:'';position:absolute;
  bottom:-1px;left:0;right:0;height:28px;
  background:var(--bg);
  clip-path:ellipse(60% 100% at 50% 100%);
}
.hero-tag{
  display:inline-flex;align-items:center;gap:6px;
  font-family:var(--H);font-size:10px;font-weight:600;
  letter-spacing:2px;text-transform:uppercase;
  color:var(--fire);margin-bottom:14px;
}
.hero-tag::before{content:'';width:20px;height:2px;background:var(--fire);}
.hero-h{
  font-family:var(--H);font-size:42px;font-weight:700;
  line-height:.95;letter-spacing:-1px;
  text-transform:uppercase;margin-bottom:6px;
}
.hero-h span{color:var(--fire);}
.hero-sub{font-size:13px;color:rgba(255,255,255,.5);margin-bottom:24px;font-weight:300;}

/* Stats strip */
.stats-strip{
  display:grid;grid-template-columns:repeat(4,1fr);
  gap:1px;background:rgba(255,255,255,.08);
  border-radius:12px 12px 0 0;overflow:hidden;
  border:1px solid rgba(255,255,255,.1);border-bottom:none;
}
.stat-box{
  background:rgba(255,255,255,.04);
  padding:14px 10px;text-align:center;
}
.stat-num{
  font-family:var(--H);font-size:22px;font-weight:700;
  color:#fff;line-height:1;
}
.stat-num.fire{color:var(--fire);}
.stat-lbl{font-size:9px;color:rgba(255,255,255,.4);margin-top:3px;letter-spacing:.8px;text-transform:uppercase;}

/* ── MAIN NAV ── */
.main-nav{
  display:flex;gap:0;
  background:var(--bg2);
  border-bottom:1px solid var(--border);
  overflow-x:auto;scrollbar-width:none;
  position:sticky;top:0;z-index:100;
}
.main-nav::-webkit-scrollbar{display:none}
.nav-tab{
  flex:1;min-width:fit-content;
  padding:14px 16px;
  font-family:var(--H);font-size:13px;font-weight:600;
  letter-spacing:.8px;text-transform:uppercase;
  color:var(--ink3);cursor:pointer;
  border-bottom:3px solid transparent;
  transition:all .2s;white-space:nowrap;
  text-align:center;
}
.nav-tab.active{color:var(--fire);border-bottom-color:var(--fire);}
.nav-tab:hover:not(.active){color:var(--ink2);}

/* ── PANELS ── */
.panel{display:none;}
.panel.active{display:block;animation:up .22s ease;}
@keyframes up{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}

/* ── SECTION HEADER ── */
.sec-head{
  padding:20px 20px 0;
  display:flex;align-items:flex-end;justify-content:space-between;
  margin-bottom:14px;
}
.sec-title{font-family:var(--H);font-size:26px;font-weight:700;letter-spacing:-.5px;text-transform:uppercase;}
.sec-count{font-size:11px;color:var(--ink3);font-weight:500;}

/* ── WEEK PILLS ── */
.week-bar{
  display:flex;gap:6px;
  padding:0 20px 14px;
  overflow-x:auto;scrollbar-width:none;
}
.week-bar::-webkit-scrollbar{display:none}
.wpill{
  flex-shrink:0;padding:7px 16px;
  border-radius:40px;border:1.5px solid var(--border);
  font-family:var(--H);font-size:12px;font-weight:600;
  letter-spacing:.5px;text-transform:uppercase;
  color:var(--ink3);cursor:pointer;transition:all .18s;
  background:var(--bg);
}
.wpill.active{background:var(--ink);color:#fff;border-color:var(--ink);}

/* ── KCAL BANNER ── */
.kcal-banner{
  margin:0 20px 14px;
  background:var(--ink);
  border-radius:var(--r);
  padding:14px 16px;
  display:flex;align-items:center;justify-content:space-between;
  position:relative;overflow:hidden;
}
.kcal-banner::before{
  content:'';position:absolute;right:-20px;top:-20px;
  width:80px;height:80px;border-radius:50%;
  background:rgba(255,69,0,.2);
}
.kb-left{}
.kb-tag{font-size:9px;color:rgba(255,255,255,.4);letter-spacing:1.5px;text-transform:uppercase;margin-bottom:2px;}
.kb-num{font-family:var(--H);font-size:28px;font-weight:700;color:#fff;line-height:1;}
.kb-unit{font-size:12px;color:rgba(255,255,255,.5);margin-left:2px;}
.kb-right{display:flex;gap:12px;}
.kb-macro{text-align:center;}
.kb-mval{font-family:var(--H);font-size:16px;font-weight:600;color:#fff;line-height:1;}
.kb-mval.p{color:#7DCEA0;}
.kb-mval.g{color:#F7DC6F;}
.kb-mval.l{color:#F1948A;}
.kb-mlbl{font-size:9px;color:rgba(255,255,255,.35);letter-spacing:.8px;text-transform:uppercase;margin-top:2px;}

/* ── DAY SCROLLER ── */
.day-scroll{
  display:flex;gap:6px;
  padding:0 20px 12px;
  overflow-x:auto;scrollbar-width:none;
}
.day-scroll::-webkit-scrollbar{display:none}
.dpill{
  flex-shrink:0;
  display:flex;flex-direction:column;align-items:center;
  padding:8px 12px;min-width:56px;
  border-radius:10px;border:1.5px solid var(--border);
  cursor:pointer;transition:all .18s;background:var(--bg);
}
.dpill.active{background:var(--fire);border-color:var(--fire);}
.dpill.active .dp-day,.dpill.active .dp-tag{color:#fff;}
.dp-day{font-family:var(--H);font-size:13px;font-weight:700;color:var(--ink);letter-spacing:.3px;}
.dp-tag{font-size:8px;color:var(--ink3);letter-spacing:.5px;text-transform:uppercase;margin-top:2px;}
.dpill.m .dp-dot{background:#1A56DB;}
.dpill.h .dp-dot{background:#FF4500;}
.dpill.c .dp-dot{background:#0D7A5F;}
.dpill.r .dp-dot{background:var(--ink3);}
.dp-dot{width:5px;height:5px;border-radius:50%;margin-top:5px;}

/* ── CARDS ── */
.card-wrap{padding:0 20px;}
.card{
  background:var(--bg);
  border:1px solid var(--border);
  border-radius:var(--r);
  margin-bottom:10px;
  overflow:hidden;
  box-shadow:var(--shadow);
}
.card-top{
  padding:14px 16px 0;
  display:flex;align-items:center;gap:8px;
  flex-wrap:wrap;
}
.card-day-lbl{
  font-family:var(--H);font-size:20px;font-weight:700;
  letter-spacing:-.3px;
}
.badge{
  font-family:var(--H);font-size:10px;font-weight:600;
  padding:3px 8px;border-radius:5px;
  letter-spacing:.8px;text-transform:uppercase;
}
.bm{background:var(--blue-dim);color:var(--blue);}
.bh{background:var(--fire-dim);color:var(--fire);}
.bc{background:var(--green-dim);color:var(--green);}
.br{background:var(--bg2);color:var(--ink3);border:1px solid var(--border);}
.bn{background:#FFF3CD;color:#856404;font-size:8px;padding:2px 5px;}
.bt{background:var(--bg3);color:var(--ink3);margin-left:auto;}
.card-body{padding:12px 16px 14px;}

/* ── SECTION LABEL ── */
.slbl{
  font-size:9px;font-weight:700;letter-spacing:1.5px;
  text-transform:uppercase;color:var(--ink3);
  margin:10px 0 6px;
  display:flex;align-items:center;gap:6px;
}
.slbl::after{content:'';flex:1;height:1px;background:var(--border2);}

/* ── EX ROW ── */
.ex{
  display:flex;justify-content:space-between;align-items:flex-start;
  gap:10px;font-size:13px;padding:5px 0;
  border-bottom:1px solid var(--border2);
}
.ex:last-child{border:none;padding-bottom:0;}
.en{flex:1;color:var(--ink2);line-height:1.35;}
.en.new-item{color:var(--green);font-weight:600;}
.es{color:var(--ink3);font-size:11px;white-space:nowrap;font-family:var(--H);letter-spacing:.3px;font-weight:600;}

/* ── ALERT BOXES ── */
.alert{
  border-radius:var(--r-sm);padding:10px 14px;
  font-size:12px;line-height:1.5;margin:0 20px 10px;
  display:flex;align-items:flex-start;gap:8px;
}
.alert-icon{font-size:14px;flex-shrink:0;margin-top:1px;}
.alert-fire{background:var(--fire-dim);color:var(--fire);border-left:3px solid var(--fire);}
.alert-blue{background:var(--blue-dim);color:var(--blue);border-left:3px solid var(--blue);}
.alert-green{background:var(--green-dim);color:var(--green);border-left:3px solid var(--green);}
.alert-gold{background:#FFF8E1;color:var(--gold);border-left:3px solid var(--gold);}

/* ── DURATION BAR ── */
.dur{
  display:flex;align-items:center;gap:8px;
  margin-top:10px;padding-top:10px;
  border-top:1px solid var(--border2);
}
.dur-lbl{font-size:9px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--ink3);}
.dur-val{font-family:var(--H);font-size:18px;font-weight:700;color:var(--fire);}
.dur-detail{font-size:10px;color:var(--ink3);margin-left:auto;text-align:right;line-height:1.4;}

/* ── SEPARATOR ── */
.sep{border:none;border-top:1px solid var(--border2);margin:10px 0;}

/* ── ABDO HERO ── */
.abdo-hero{
  margin:0 20px 14px;
  background:linear-gradient(135deg,#0A0A0A 0%,#1c1c1c 100%);
  border-radius:var(--r);padding:20px;
  position:relative;overflow:hidden;
}
.abdo-hero::after{
  content:'6';
  position:absolute;right:-10px;top:-20px;
  font-family:var(--H);font-size:120px;font-weight:700;
  color:rgba(255,69,0,.08);line-height:1;
  pointer-events:none;
}
.ah-tag{font-size:9px;letter-spacing:2px;text-transform:uppercase;color:var(--fire);margin-bottom:6px;font-family:var(--H);font-weight:600;}
.ah-title{font-family:var(--H);font-size:28px;font-weight:700;color:#fff;line-height:.95;text-transform:uppercase;margin-bottom:8px;}
.ah-sub{font-size:12px;color:rgba(255,255,255,.45);line-height:1.5;}

/* ── ABDO CIRCUIT CARD ── */
.abdo-card{
  background:var(--bg);
  border:1px solid var(--border);
  border-radius:var(--r);
  margin-bottom:10px;
  overflow:hidden;
  box-shadow:var(--shadow);
}
.abdo-card-head{
  display:flex;align-items:center;
  padding:12px 14px;gap:10px;
  border-bottom:1px solid var(--border2);
}
.ach-icon{
  width:36px;height:36px;border-radius:9px;
  display:flex;align-items:center;justify-content:center;
  font-size:16px;flex-shrink:0;
}
.ach-icon.fire{background:var(--fire-dim);}
.ach-icon.blue{background:var(--blue-dim);}
.ach-icon.green{background:var(--green-dim);}
.ach-title{font-family:var(--H);font-size:15px;font-weight:700;letter-spacing:.2px;}
.ach-sub{font-size:11px;color:var(--ink3);margin-top:1px;}
.ach-sets{
  margin-left:auto;
  font-family:var(--H);font-size:14px;font-weight:700;
  color:var(--fire);
}
.abdo-card-body{padding:12px 14px;}

/* ── ABDO EX ── */
.abdo-ex{
  display:flex;align-items:center;gap:12px;
  padding:8px 0;border-bottom:1px solid var(--border2);
}
.abdo-ex:last-child{border:none;padding-bottom:0;}
.abdo-num{
  font-family:var(--H);font-size:13px;font-weight:700;
  color:var(--ink3);width:20px;flex-shrink:0;text-align:center;
}
.abdo-info{flex:1;}
.abdo-name{font-size:13px;color:var(--ink);font-weight:500;}
.abdo-target{font-size:10px;color:var(--ink3);margin-top:1px;}
.abdo-set{
  font-family:var(--H);font-size:13px;font-weight:700;
  color:var(--ink);white-space:nowrap;
}
.abdo-muscle{
  font-size:9px;background:var(--bg2);color:var(--ink3);
  padding:2px 6px;border-radius:4px;flex-shrink:0;
  letter-spacing:.5px;
}

/* ── PROG BARS ── */
.prog-row{margin-bottom:12px;}
.prog-head{display:flex;justify-content:space-between;font-size:12px;margin-bottom:5px;}
.prog-name{color:var(--ink2);font-weight:500;}
.prog-val{color:var(--fire);font-weight:700;font-family:var(--H);}
.prog-track{height:5px;background:var(--bg3);border-radius:3px;overflow:hidden;}
.prog-fill{height:100%;border-radius:3px;background:linear-gradient(90deg,var(--fire),var(--fire2));transition:width .6s ease;}

/* ── MACRO GRID ── */
.macro-grid{
  display:grid;grid-template-columns:repeat(4,1fr);
  gap:8px;margin-bottom:14px;
}
.mbox{
  background:var(--bg2);border:1px solid var(--border);
  border-radius:var(--r-sm);padding:12px 8px;text-align:center;
}
.mnum{font-family:var(--H);font-size:22px;font-weight:700;line-height:1;}
.mlbl{font-size:9px;color:var(--ink3);margin-top:3px;font-weight:600;letter-spacing:.8px;text-transform:uppercase;}

/* ── FOOD ── */
.food-row{
  display:flex;justify-content:space-between;align-items:flex-start;
  font-size:13px;padding:7px 0;
  border-bottom:1px solid var(--border2);gap:10px;
}
.food-row:last-child{border:none;}
.food-kcal{color:var(--ink3);font-size:11px;font-weight:700;white-space:nowrap;font-family:var(--H);}

/* ── RULES ── */
.rule-item{
  display:flex;align-items:flex-start;gap:12px;
  padding:11px 0;border-bottom:1px solid var(--border2);
}
.rule-item:last-child{border:none;}
.rule-num{
  font-family:var(--H);font-size:24px;font-weight:700;
  color:var(--fire);line-height:1;flex-shrink:0;width:28px;
}
.rule-text{font-size:13px;line-height:1.5;color:var(--ink2);}
.rule-text strong{color:var(--ink);}

/* ── PROFILE CARD ── */
.profile-card{
  margin:0 20px 14px;
  background:var(--bg2);
  border:1px solid var(--border);
  border-radius:var(--r);
  padding:16px;
}
.profile-grid{
  display:grid;grid-template-columns:repeat(3,1fr);
  gap:8px;margin-bottom:14px;
}
.pstat{
  background:var(--bg);border:1px solid var(--border);
  border-radius:var(--r-sm);padding:10px;text-align:center;
}
.pstat-val{font-family:var(--H);font-size:20px;font-weight:700;color:var(--ink);line-height:1;}
.pstat-lbl{font-size:9px;color:var(--ink3);letter-spacing:.8px;text-transform:uppercase;margin-top:3px;}

/* ── SUPPL ── */
.suppl-item{
  display:flex;align-items:flex-start;gap:10px;
  padding:9px 0;border-bottom:1px solid var(--border2);
}
.suppl-item:last-child{border:none;}
.suppl-ico{font-size:18px;flex-shrink:0;}
.suppl-name{font-size:13px;font-weight:600;color:var(--ink);}
.suppl-desc{font-size:11px;color:var(--ink3);margin-top:1px;line-height:1.4;}

/* ── OBJECTIVE PROGRESS ── */
.obj-strip{
  margin:0 20px 14px;
  background:var(--ink);
  border-radius:var(--r);padding:16px;
  display:grid;grid-template-columns:1fr 1fr;gap:14px;
}
.obj-item{text-align:center;}
.obj-val{font-family:var(--H);font-size:26px;font-weight:700;color:#fff;line-height:1;}
.obj-val.fire{color:var(--fire);}
.obj-lbl{font-size:9px;color:rgba(255,255,255,.4);letter-spacing:1px;text-transform:uppercase;margin-top:3px;}

/* ── WEEK day panels ── */
.wday-panel{display:none;}
.wday-panel.active{display:block;animation:up .18s ease;}

/* ── NUTRI WEEK TABS ── */
.nutri-tabs{display:flex;gap:6px;margin:0 20px 14px;}
.ntab{
  flex:1;text-align:center;padding:9px;
  background:var(--bg2);border:1.5px solid var(--border);
  border-radius:var(--r-sm);cursor:pointer;
  font-family:var(--H);font-size:12px;font-weight:600;
  color:var(--ink3);transition:all .2s;letter-spacing:.5px;text-transform:uppercase;
}
.ntab.active{background:var(--ink);border-color:var(--ink);color:#fff;}
.nutri-panel{display:none;}
.nutri-panel.active{display:block;}

/* ── SCROLLBAR ── */
::-webkit-scrollbar{width:3px;height:3px}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:2px}

/* ── BOTTOM PADDING ── */
.pb{padding-bottom:60px;}
</style>
</head>
<body>

<!-- ██ HERO ██ -->
<div class="hero">
  <div class="hero-tag">Programme Personnalisé</div>
  <div class="hero-h">SÈCHE &amp;<br><span>ABDOS</span></div>
  <div class="hero-sub">3 semaines · Calibré pour toi · 1m65 · 66,6 kg</div>

  <div class="stats-strip">
    <div class="stat-box">
      <div class="stat-num">66<span style="font-size:14px">,6</span></div>
      <div class="stat-lbl">Poids kg</div>
    </div>
    <div class="stat-box">
      <div class="stat-num">24<span style="font-size:14px">,5</span></div>
      <div class="stat-lbl">IMC</div>
    </div>
    <div class="stat-box">
      <div class="stat-num fire">147</div>
      <div class="stat-lbl">Prot. g/j</div>
    </div>
    <div class="stat-box">
      <div class="stat-num">−2,5</div>
      <div class="stat-lbl">Obj. kg</div>
    </div>
  </div>
</div>

<!-- ██ MAIN NAV ██ -->
<div class="main-nav">
  <div class="nav-tab active" onclick="showMain('accueil',this)">Accueil</div>
  <div class="nav-tab" onclick="showMain('training',this)">Training</div>
  <div class="nav-tab" onclick="showMain('abdos',this)">Abdos</div>
  <div class="nav-tab" onclick="showMain('nutrition',this)">Nutrition</div>
  <div class="nav-tab" onclick="showMain('regles',this)">Règles</div>
</div>


<!-- ══════════════════════════════════════
     ACCUEIL
══════════════════════════════════════ -->
<div id="accueil" class="panel active pb">
  <div style="height:20px"></div>

  <!-- Profile -->
  <div class="profile-card">
    <div class="sec-title" style="font-size:18px;margin-bottom:12px;">Ton profil</div>
    <div class="profile-grid">
      <div class="pstat"><div class="pstat-val">1m65</div><div class="pstat-lbl">Taille</div></div>
      <div class="pstat"><div class="pstat-val">66,6</div><div class="pstat-lbl">Poids kg</div></div>
      <div class="pstat"><div class="pstat-val" style="color:var(--fire)">24,5</div><div class="pstat-lbl">IMC</div></div>
    </div>
    <div class="slbl">Objectif 3 semaines</div>
    <div class="prog-row">
      <div class="prog-head"><span class="prog-name">Perte de gras</span><span class="prog-val">−2 à −2,5 kg</span></div>
      <div class="prog-track"><div class="prog-fill" style="width:75%"></div></div>
    </div>
    <div class="prog-row">
      <div class="prog-head"><span class="prog-name">Définition musculaire</span><span class="prog-val">+++ visible</span></div>
      <div class="prog-track"><div class="prog-fill" style="width:88%"></div></div>
    </div>
    <div class="prog-row">
      <div class="prog-head"><span class="prog-name">Abdos visibles</span><span class="prog-val">objectif S3</span></div>
      <div class="prog-track"><div class="prog-fill" style="width:60%"></div></div>
    </div>
  </div>

  <!-- Objectif poids -->
  <div class="obj-strip">
    <div class="obj-item">
      <div class="obj-val">66,6 kg</div>
      <div class="obj-lbl">Poids actuel</div>
    </div>
    <div class="obj-item">
      <div class="obj-val fire">~64 kg</div>
      <div class="obj-lbl">Objectif J21</div>
    </div>
    <div class="obj-item">
      <div class="obj-val">1900</div>
      <div class="obj-lbl">Kcal S1</div>
    </div>
    <div class="obj-item">
      <div class="obj-val fire">147g</div>
      <div class="obj-lbl">Prot./jour</div>
    </div>
  </div>

  <div class="alert alert-fire"><span class="alert-icon">🔥</span><span><strong>Pourquoi ça va marcher.</strong> À 66,6 kg / 1m65 avec un bon niveau de muscu, tu peux perdre 2–2,5 kg de gras en 3 semaines en conservant le muscle — à condition de manger 147g de protéines par jour.</span></div>

  <!-- Plan vue d'ensemble -->
  <div style="padding:0 20px;margin-bottom:14px;">
    <div class="slbl">Vue d'ensemble du programme</div>
    <div class="card" style="box-shadow:none;">
      <div class="card-body" style="padding:0;">
        <div class="ex"><span class="en"><strong>Semaine 1</strong> — Mise en route</span><span class="es">1900 kcal</span></div>
        <div class="ex"><span class="en"><strong>Semaine 2</strong> — Accélération</span><span class="es">1750 kcal</span></div>
        <div class="ex"><span class="en"><strong>Semaine 3</strong> — Phase finale</span><span class="es">1600 kcal</span></div>
        <div class="ex"><span class="en">Séances / semaine</span><span class="es">7 jours</span></div>
        <div class="ex"><span class="en">Volume abdo quotidien</span><span class="es">20–30 min</span></div>
        <div class="ex"><span class="en">TDEE estimé (activité modérée)</span><span class="es">~2 400 kcal</span></div>
        <div class="ex" style="border:none"><span class="en">Déficit calorique</span><span class="es" style="color:var(--fire)">−400 à −700 kcal</span></div>
      </div>
    </div>
  </div>

  <div class="alert alert-gold"><span class="alert-icon">⭐</span><span>À ton IMC de 24,5 tu es en zone normale mais en limite haute. 3 semaines suffisent pour révéler une définition nette si tu suis le plan à 100%.</span></div>
</div>


<!-- ══════════════════════════════════════
     TRAINING
══════════════════════════════════════ -->
<div id="training" class="panel pb">

  <!-- Week selector -->
  <div style="height:16px"></div>
  <div class="week-bar">
    <div class="wpill active" onclick="showWeek('w1',this)">Semaine 1 · 1900 kcal</div>
    <div class="wpill" onclick="showWeek('w2',this)">Semaine 2 · 1750 kcal</div>
    <div class="wpill" onclick="showWeek('w3',this)">Semaine 3 · 1600 kcal</div>
  </div>

  <!-- ── SEMAINE 1 ── -->
  <div id="w1" class="wk-panel" style="display:block;">
    <div class="kcal-banner">
      <div class="kb-left">
        <div class="kb-tag">Semaine 1 · Calories / jour</div>
        <div class="kb-num">1900<span class="kb-unit">kcal</span></div>
      </div>
      <div class="kb-right">
        <div class="kb-macro"><div class="kb-mval p">147g</div><div class="kb-mlbl">Prot.</div></div>
        <div class="kb-macro"><div class="kb-mval g">196g</div><div class="kb-mlbl">Gluc.</div></div>
        <div class="kb-macro"><div class="kb-mval l">55g</div><div class="kb-mlbl">Lip.</div></div>
      </div>
    </div>

    <div class="day-scroll" id="ds-w1">
      <div class="dpill m active" onclick="showDay('w1','lun',this)"><div class="dp-day">LUN</div><div class="dp-tag">Muscu</div><div class="dp-dot"></div></div>
      <div class="dpill h" onclick="showDay('w1','mar',this)"><div class="dp-day">MAR</div><div class="dp-tag">HIIT</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w1','mer',this)"><div class="dp-day">MER</div><div class="dp-tag">Dos</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w1','jeu',this)"><div class="dp-day">JEU</div><div class="dp-tag">Jambes</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w1','ven',this)"><div class="dp-day">VEN</div><div class="dp-tag">Épaules</div><div class="dp-dot"></div></div>
      <div class="dpill c" onclick="showDay('w1','sam',this)"><div class="dp-day">SAM</div><div class="dp-tag">Cardio</div><div class="dp-dot"></div></div>
      <div class="dpill r" onclick="showDay('w1','dim',this)"><div class="dp-day">DIM</div><div class="dp-tag">Récup</div><div class="dp-dot"></div></div>
    </div>

    <div class="card-wrap">
      <!-- LUN -->
      <div class="wday-panel active" id="w1-lun">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Lundi</span><span class="badge bm">Poitrine + Triceps</span><span class="badge bt">⏱ 75 min</span></div>
          <div class="card-body">
            <div class="slbl">Poitrine</div>
            <div class="ex"><span class="en">Développé couché barre</span><span class="es">4×10 · 60s</span></div>
            <div class="ex"><span class="en">Développé incliné haltères</span><span class="es">4×10</span></div>
            <div class="ex"><span class="en">Écarté câbles (chest fly)</span><span class="es">3×12</span></div>
            <div class="slbl">Triceps</div>
            <div class="ex"><span class="en">Dips lestés</span><span class="es">3×12</span></div>
            <div class="ex"><span class="en">Extension triceps poulie haute</span><span class="es">3×15</span></div>
            <div class="slbl">Abdos — inclus quotidien</div>
            <div class="ex"><span class="en">→ Voir onglet Abdos pour le circuit du jour</span><span class="es">20 min</span></div>
          </div>
        </div>
      </div>

      <!-- MAR -->
      <div class="wday-panel" id="w1-mar">
        <div class="alert alert-fire"><span class="alert-icon">⚡</span>40s à fond / 20s repos. HIIT pur — brûle jusqu'à 400 kcal en 30 min.</div>
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mardi</span><span class="badge bh">HIIT</span><span class="badge bt">⏱ 55 min</span></div>
          <div class="card-body">
            <div class="slbl">Échauffement</div>
            <div class="ex"><span class="en">Vélo ou rameur léger</span><span class="es">5 min</span></div>
            <div class="slbl">HIIT · 12 rounds</div>
            <div class="ex"><span class="en">Sprint 40s / repos 20s</span><span class="es">12 rounds</span></div>
            <div class="slbl">Abdos HIIT finisher</div>
            <div class="ex"><span class="en">Mountain climbers</span><span class="es">3×40s</span></div>
            <div class="ex"><span class="en">Russian twist lesté</span><span class="es">3×20</span></div>
            <div class="ex"><span class="en">Gainage latéral</span><span class="es">3×40s</span></div>
            <div class="slbl">Retour au calme</div>
            <div class="ex"><span class="en">Vélo modéré</span><span class="es">10 min</span></div>
          </div>
        </div>
      </div>

      <!-- MER -->
      <div class="wday-panel" id="w1-mer">
        <div class="alert alert-blue"><span class="alert-icon">💡</span>Séance dos + biceps + épaules arrière complète. La plus longue de la semaine.</div>
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mercredi</span><span class="badge bm">Dos + Biceps + Épaules arr.</span><span class="badge bt">⏱ 110 min</span></div>
          <div class="card-body">
            <div class="slbl">Échauffement</div>
            <div class="ex"><span class="en">Rameur léger</span><span class="es">10 min</span></div>
            <div class="slbl">Dos — tirage vertical</div>
            <div class="ex"><span class="en">Tractions pronation</span><span class="es">4×10</span></div>
            <div class="ex"><span class="en">Tirage poulie haute supination</span><span class="es">4×12</span></div>
            <div class="slbl">Dos — tirage horizontal</div>
            <div class="ex"><span class="en">Rowing barre</span><span class="es">4×10</span></div>
            <div class="ex"><span class="en">Tirage horizontal câble</span><span class="es">4×12</span></div>
            <div class="ex"><span class="en">Rowing haltère unilatéral</span><span class="es">3×12/côté</span></div>
            <div class="slbl">Épaules arrière + Trapèzes</div>
            <div class="ex"><span class="en">Face pull câble <span class="badge bn">+</span></span><span class="es">4×15</span></div>
            <div class="ex"><span class="en">Oiseau haltères rear delt <span class="badge bn">+</span></span><span class="es">4×15</span></div>
            <div class="ex"><span class="en">Shrugs haltères <span class="badge bn">+</span></span><span class="es">3×20</span></div>
            <div class="slbl">Biceps</div>
            <div class="ex"><span class="en">Curl barre droite</span><span class="es">3×12</span></div>
            <div class="ex"><span class="en">Curl marteau haltères</span><span class="es">3×12</span></div>
            <div class="ex"><span class="en">Curl concentré sur banc <span class="badge bn">+</span></span><span class="es">3×15/bras</span></div>
            <div class="slbl">Abdos — inclus</div>
            <div class="ex"><span class="en">Ab wheel</span><span class="es">4×15</span></div>
            <div class="ex"><span class="en">Crunch inversé</span><span class="es">4×20</span></div>
            <div class="ex"><span class="en">Relevé de jambes suspendu</span><span class="es">3×20</span></div>
            <div class="ex"><span class="en">Planche frontale</span><span class="es">3×1 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">110 min</span><span class="dur-detail">Échauff 10 · Dos 40 · Épaules arr 20 · Biceps 20 · Abdos 20</span></div>
          </div>
        </div>
      </div>

      <!-- JEU -->
      <div class="wday-panel" id="w1-jeu">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Jeudi</span><span class="badge bm">Jambes + Fessiers</span><span class="badge bt">⏱ 80 min</span></div>
          <div class="card-body">
            <div class="slbl">Quadriceps + Fessiers</div>
            <div class="ex"><span class="en">Squat barre</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Presse à cuisse</span><span class="es">4×12</span></div>
            <div class="ex"><span class="en">Fentes marchées haltères</span><span class="es">3×12/jambe</span></div>
            <div class="slbl">Ischio + Mollets</div>
            <div class="ex"><span class="en">Leg curl couché</span><span class="es">3×15</span></div>
            <div class="ex"><span class="en">Mollets debout</span><span class="es">4×20</span></div>
            <div class="slbl">Abdos finisher</div>
            <div class="ex"><span class="en">Planche 1 min + Crunch 25 reps</span><span class="es">3 rounds</span></div>
          </div>
        </div>
      </div>

      <!-- VEN -->
      <div class="wday-panel" id="w1-ven">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Vendredi</span><span class="badge bm">Épaules + Abdos intensif</span><span class="badge bt">⏱ 75 min</span></div>
          <div class="card-body">
            <div class="slbl">Épaules</div>
            <div class="ex"><span class="en">Développé militaire barre</span><span class="es">4×10</span></div>
            <div class="ex"><span class="en">Élévations latérales haltères</span><span class="es">4×15</span></div>
            <div class="ex"><span class="en">Oiseau haltères arrière épaule</span><span class="es">3×15</span></div>
            <div class="ex"><span class="en">Face pull câble</span><span class="es">3×15</span></div>
            <div class="slbl">Circuit abdos × 4 rounds · 0 repos</div>
            <div class="ex"><span class="en">Crunch</span><span class="es">20 reps</span></div>
            <div class="ex"><span class="en">Relevé de jambes</span><span class="es">15 reps</span></div>
            <div class="ex"><span class="en">Planche</span><span class="es">45s</span></div>
            <div class="ex"><span class="en">Russian twist lesté</span><span class="es">20 reps</span></div>
          </div>
        </div>
      </div>

      <!-- SAM -->
      <div class="wday-panel" id="w1-sam">
        <div class="alert alert-green"><span class="alert-icon">🚶</span>Cardio faible intensité = brûle directement les graisses. Ne pas courir — marcher incliné.</div>
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Samedi</span><span class="badge bc">Cardio + Full body léger</span><span class="badge bt">⏱ 105 min</span></div>
          <div class="card-body">
            <div class="slbl">Cardio brûle-graisses</div>
            <div class="ex"><span class="en">Marche inclinée tapis 8–10%</span><span class="es">45 min</span></div>
            <div class="slbl">Circuit muscu léger · 3 rounds · 15–20 reps</div>
            <div class="ex"><span class="en">Squat goblet haltère</span><span class="es">3×20</span></div>
            <div class="ex"><span class="en">Pompes</span><span class="es">3×20</span></div>
            <div class="ex"><span class="en">Fentes statiques haltères</span><span class="es">3×15/jambe</span></div>
            <div class="ex"><span class="en">Tirage poulie buste penché</span><span class="es">3×20</span></div>
            <div class="ex"><span class="en">Élévations latérales légères</span><span class="es">3×20</span></div>
            <div class="slbl">Abdos · 4 rounds</div>
            <div class="ex"><span class="en">Crunch 25 · Relevé jambes 20 · Planche 1min · Russian twist 20</span><span class="es">4×</span></div>
            <div class="slbl">Retour calme</div>
            <div class="ex"><span class="en">Vélo ou elliptique modéré</span><span class="es">10 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">105 min</span><span class="dur-detail">Cardio 45 · Muscu léger 25 · Abdos 25 · Récup 10</span></div>
          </div>
        </div>
      </div>

      <!-- DIM -->
      <div class="wday-panel" id="w1-dim">
        <div class="alert alert-gold"><span class="alert-icon">🧘</span>Dimanche = récupération active. Le gainage profond sculpte la sangle abdominale sans fatiguer les muscles du training.</div>
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Dimanche</span><span class="badge br">Récupération active</span><span class="badge bt">⏱ 90 min</span></div>
          <div class="card-body">
            <div class="slbl">Cardio doux</div>
            <div class="ex"><span class="en">Marche pente douce 3–4%</span><span class="es">35 min</span></div>
            <div class="slbl">Gainage profond — core stability</div>
            <div class="ex"><span class="en">Planche frontale</span><span class="es">5×1 min</span></div>
            <div class="ex"><span class="en">Planche latérale chaque côté</span><span class="es">4×45s</span></div>
            <div class="ex"><span class="en">Bird dog</span><span class="es">3×15/côté</span></div>
            <div class="ex"><span class="en">Dead bug</span><span class="es">3×15</span></div>
            <div class="ex"><span class="en">Hollow body hold</span><span class="es">4×30s</span></div>
            <div class="slbl">Mobilité + Étirements</div>
            <div class="ex"><span class="en">Ischio-jambiers</span><span class="es">3×45s</span></div>
            <div class="ex"><span class="en">Hip flexor stretch</span><span class="es">3×45s</span></div>
            <div class="ex"><span class="en">Rotation thoracique sol</span><span class="es">2×10/côté</span></div>
            <div class="ex"><span class="en">Cat-cow + Child's pose</span><span class="es">5 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">90 min</span><span class="dur-detail">Cardio 35 · Gainage 30 · Mobilité 25</span></div>
          </div>
        </div>
      </div>
    </div><!-- /card-wrap -->
  </div><!-- /w1 -->

  <!-- ── SEMAINE 2 ── -->
  <div id="w2" class="wk-panel" style="display:none;">
    <div class="kcal-banner">
      <div class="kb-left">
        <div class="kb-tag">Semaine 2 · Charges +5% · Repos 45s</div>
        <div class="kb-num">1750<span class="kb-unit">kcal</span></div>
      </div>
      <div class="kb-right">
        <div class="kb-macro"><div class="kb-mval p">147g</div><div class="kb-mlbl">Prot.</div></div>
        <div class="kb-macro"><div class="kb-mval g">158g</div><div class="kb-mlbl">Gluc.</div></div>
        <div class="kb-macro"><div class="kb-mval l">50g</div><div class="kb-mlbl">Lip.</div></div>
      </div>
    </div>
    <div class="day-scroll" id="ds-w2">
      <div class="dpill m active" onclick="showDay('w2','lun',this)"><div class="dp-day">LUN</div><div class="dp-tag">Muscu</div><div class="dp-dot"></div></div>
      <div class="dpill h" onclick="showDay('w2','mar',this)"><div class="dp-day">MAR</div><div class="dp-tag">HIIT</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w2','mer',this)"><div class="dp-day">MER</div><div class="dp-tag">Dos</div><div class="dp-dot"></div></div>
      <div class="dpill h" onclick="showDay('w2','jeu',this)"><div class="dp-day">JEU</div><div class="dp-tag">HIIT</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w2','ven',this)"><div class="dp-day">VEN</div><div class="dp-tag">Upper</div><div class="dp-dot"></div></div>
      <div class="dpill c" onclick="showDay('w2','sam',this)"><div class="dp-day">SAM</div><div class="dp-tag">Cardio</div><div class="dp-dot"></div></div>
      <div class="dpill r" onclick="showDay('w2','dim',this)"><div class="dp-day">DIM</div><div class="dp-tag">Récup</div><div class="dp-dot"></div></div>
    </div>
    <div class="card-wrap">
      <div class="wday-panel active" id="w2-lun">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Lundi</span><span class="badge bm">Poitrine + Triceps supersets</span><span class="badge bt">⏱ 80 min</span></div>
          <div class="card-body">
            <div class="alert alert-blue" style="margin:0 0 10px;"><span class="alert-icon">🔗</span>Tous en supersets — 45s repos max</div>
            <div class="slbl">Poitrine — supersets</div>
            <div class="ex"><span class="en">Développé couché / Écarté câble</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Développé incliné / Pompes pondérées</span><span class="es">4×12</span></div>
            <div class="slbl">Triceps — supersets</div>
            <div class="ex"><span class="en">Dips lestés / Extension poulie</span><span class="es">4×12</span></div>
            <div class="slbl">Abdos finisher · 4 rounds</div>
            <div class="ex"><span class="en">Crunch 25 · Relevé jambes 20 · Planche 1min</span><span class="es">4×</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-mar">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mardi</span><span class="badge bh">HIIT max + Abdos</span><span class="badge bt">⏱ 60 min</span></div>
          <div class="card-body">
            <div class="slbl">HIIT · 15 rounds</div>
            <div class="ex"><span class="en">50s effort / 10s repos — full intensité</span><span class="es">15 rounds</span></div>
            <div class="slbl">Abdos intensif</div>
            <div class="ex"><span class="en">Ab wheel</span><span class="es">5×20</span></div>
            <div class="ex"><span class="en">Relevé de jambes suspendu</span><span class="es">4×20</span></div>
            <div class="ex"><span class="en">Planche 1 min</span><span class="es">×5</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-mer">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mercredi</span><span class="badge bm">Dos + Biceps + Épaules arr.</span><span class="badge bt">⏱ 115 min</span></div>
          <div class="card-body">
            <div class="slbl">Dos — supersets · charges +5%</div>
            <div class="ex"><span class="en">Tractions lestées</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Rowing barre + Rowing haltère</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Tirage horizontal + Pull-over câble</span><span class="es">4×12</span></div>
            <div class="slbl">Épaules arrière</div>
            <div class="ex"><span class="en">Face pull + Oiseau superset</span><span class="es">4×15</span></div>
            <div class="ex"><span class="en">Shrugs haltères lourds</span><span class="es">4×20</span></div>
            <div class="slbl">Biceps</div>
            <div class="ex"><span class="en">Curl barre + Curl concentré</span><span class="es">4×12</span></div>
            <div class="ex"><span class="en">Curl marteau + Curl câble</span><span class="es">3×15</span></div>
            <div class="slbl">Abdos · 5 rounds circuit</div>
            <div class="ex"><span class="en">Ab wheel 15 · Relevé jambes 20 · Planche 1min · Russian twist 25</span><span class="es">5×</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">115 min</span><span class="dur-detail">Échauff 10 · Dos/épaules 55 · Biceps 25 · Abdos 25</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-jeu">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Jeudi</span><span class="badge bh">HIIT + Circuit total</span><span class="badge bt">⏱ 65 min</span></div>
          <div class="card-body">
            <div class="slbl">HIIT rameur · max intensité</div>
            <div class="ex"><span class="en">Rameur HIIT</span><span class="es">20 min</span></div>
            <div class="slbl">Circuit full body · 5 rounds</div>
            <div class="ex"><span class="en">Burpees</span><span class="es">15 reps</span></div>
            <div class="ex"><span class="en">Squat sauté</span><span class="es">20 reps</span></div>
            <div class="ex"><span class="en">Pompes</span><span class="es">20 reps</span></div>
            <div class="slbl">Circuit abdos · 5 rounds</div>
            <div class="ex"><span class="en">Crunch · Relevé jambes · Planche · Russian twist</span><span class="es">5×</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-ven">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Vendredi</span><span class="badge bm">Upper + Abdos finisher</span><span class="badge bt">⏱ 80 min</span></div>
          <div class="card-body">
            <div class="slbl">Upper body supersets · 5×12 · 45s repos</div>
            <div class="ex"><span class="en">Développé couché</span><span class="es">5×12</span></div>
            <div class="ex"><span class="en">Tractions</span><span class="es">5×12</span></div>
            <div class="ex"><span class="en">Développé militaire</span><span class="es">5×12</span></div>
            <div class="ex"><span class="en">Rowing</span><span class="es">5×12</span></div>
            <div class="slbl">Abdos finisher · 6 rounds · 0 repos</div>
            <div class="ex"><span class="en">Circuit abdos enchaîné</span><span class="es">6×</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-sam">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Samedi</span><span class="badge bc">Cardio + Full body + Abdos</span><span class="badge bt">⏱ 110 min</span></div>
          <div class="card-body">
            <div class="ex"><span class="en">Marche inclinée 10%</span><span class="es">50 min</span></div>
            <div class="ex"><span class="en">Circuit muscu léger × 4 rounds (charges +)</span><span class="es">30 min</span></div>
            <div class="ex"><span class="en">Circuit abdos × 5 rounds</span><span class="es">25 min</span></div>
            <div class="ex"><span class="en">Vélo retour calme</span><span class="es">5 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">110 min</span><span class="dur-detail">Cardio 50 · Muscu 30 · Abdos 25 · Récup 5</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w2-dim">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Dimanche</span><span class="badge br">Récupération active</span><span class="badge bt">⏱ 95 min</span></div>
          <div class="card-body">
            <div class="ex"><span class="en">Marche ou vélo léger</span><span class="es">40 min</span></div>
            <div class="ex"><span class="en">Circuit gainage profond × 4 rounds</span><span class="es">30 min</span></div>
            <div class="ex"><span class="en">Mobilité + étirements</span><span class="es">25 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">95 min</span><span class="dur-detail">Cardio 40 · Gainage 30 · Mobilité 25</span></div>
          </div>
        </div>
      </div>
    </div>
  </div><!-- /w2 -->

  <!-- ── SEMAINE 3 ── -->
  <div id="w3" class="wk-panel" style="display:none;">
    <div class="kcal-banner" style="background:linear-gradient(135deg,#1a0000,#330000);">
      <div class="kb-left">
        <div class="kb-tag">Semaine 3 · FINALE · Tout donner</div>
        <div class="kb-num">1600<span class="kb-unit">kcal</span></div>
      </div>
      <div class="kb-right">
        <div class="kb-macro"><div class="kb-mval p">150g</div><div class="kb-mlbl">Prot.</div></div>
        <div class="kb-macro"><div class="kb-mval g">115g</div><div class="kb-mlbl">Gluc.</div></div>
        <div class="kb-macro"><div class="kb-mval l">48g</div><div class="kb-mlbl">Lip.</div></div>
      </div>
    </div>
    <div class="alert alert-fire" style="margin-top:0;"><span class="alert-icon">💀</span><strong>Semaine finale.</strong> Déficit maximal. Tu as passé 2 semaines à t'y préparer — le corps est prêt. Zéro écart.</div>
    <div class="day-scroll" id="ds-w3">
      <div class="dpill m active" onclick="showDay('w3','lun',this)"><div class="dp-day">LUN</div><div class="dp-tag">Muscu</div><div class="dp-dot"></div></div>
      <div class="dpill h" onclick="showDay('w3','mar',this)"><div class="dp-day">MAR</div><div class="dp-tag">HIIT</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w3','mer',this)"><div class="dp-day">MER</div><div class="dp-tag">Dos</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w3','jeu',this)"><div class="dp-day">JEU</div><div class="dp-tag">Jambes</div><div class="dp-dot"></div></div>
      <div class="dpill m" onclick="showDay('w3','ven',this)"><div class="dp-day">VEN</div><div class="dp-tag">Upper</div><div class="dp-dot"></div></div>
      <div class="dpill c" onclick="showDay('w3','sam',this)"><div class="dp-day">SAM</div><div class="dp-tag">Cardio</div><div class="dp-dot"></div></div>
      <div class="dpill r" onclick="showDay('w3','dim',this)"><div class="dp-day">DIM</div><div class="dp-tag">Récup</div><div class="dp-dot"></div></div>
    </div>
    <div class="card-wrap">
      <div class="wday-panel active" id="w3-lun">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Lundi</span><span class="badge bm">Upper · charges max</span><span class="badge bt">⏱ 85 min</span></div>
          <div class="card-body">
            <div class="slbl">Poitrine + Triceps supersets · 45s repos</div>
            <div class="ex"><span class="en">Développé couché / Écarté câble</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Développé incliné / Pompes pondérées</span><span class="es">5×12</span></div>
            <div class="ex"><span class="en">Dips lestés / Extension triceps</span><span class="es">4×12</span></div>
            <div class="slbl">Abdos finisher · 5 rounds</div>
            <div class="ex"><span class="en">Crunch 25 · Relevé jambes 20 · Planche 1min · Russian twist 25</span><span class="es">5×</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-mar">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mardi</span><span class="badge bh">HIIT ultime</span><span class="badge bt">⏱ 65 min</span></div>
          <div class="card-body">
            <div class="slbl">HIIT · 15 rounds · intensité max</div>
            <div class="ex"><span class="en">50s sprint / 10s repos</span><span class="es">15 rounds</span></div>
            <div class="slbl">Abdos finisher</div>
            <div class="ex"><span class="en">Ab wheel</span><span class="es">5×20</span></div>
            <div class="ex"><span class="en">Relevé de jambes suspendu</span><span class="es">4×20</span></div>
            <div class="ex"><span class="en">Planche 1 min</span><span class="es">×5</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-mer">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Mercredi</span><span class="badge bm">Dos + Biceps + Épaules arr.</span><span class="badge bt">⏱ 120 min</span></div>
          <div class="card-body">
            <div class="slbl">Dos — volume max</div>
            <div class="ex"><span class="en">Tractions lestées max</span><span class="es">6×10</span></div>
            <div class="ex"><span class="en">Rowing barre + Pull-over superset</span><span class="es">5×10</span></div>
            <div class="ex"><span class="en">Tirage horizontal + Rowing haltère</span><span class="es">5×12</span></div>
            <div class="slbl">Épaules arrière tri-set</div>
            <div class="ex"><span class="en">Face pull + Oiseau + Shrugs</span><span class="es">5×15</span></div>
            <div class="slbl">Biceps tri-set</div>
            <div class="ex"><span class="en">Curl barre + Curl concentré + Curl câble</span><span class="es">4×12</span></div>
            <div class="slbl">Abdos · 6 rounds</div>
            <div class="ex"><span class="en">Ab wheel 20 · Relevé jambes 25 · Planche 1min · Russian twist 30</span><span class="es">6×</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">120 min</span><span class="dur-detail">Échauff 10 · Dos/épaules 60 · Biceps 25 · Abdos 25</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-jeu">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Jeudi</span><span class="badge bm">Full lower body</span><span class="badge bt">⏱ 85 min</span></div>
          <div class="card-body">
            <div class="slbl">Lower body volume max</div>
            <div class="ex"><span class="en">Squat barre</span><span class="es">6×10</span></div>
            <div class="ex"><span class="en">Soulevé de terre jambes tendues</span><span class="es">4×12</span></div>
            <div class="ex"><span class="en">Fentes + Presse superset</span><span class="es">4×12</span></div>
            <div class="ex"><span class="en">Mollets</span><span class="es">5×25</span></div>
            <div class="slbl">Gainage finisher</div>
            <div class="ex"><span class="en">Gainage 1 min</span><span class="es">×6</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-ven">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Vendredi</span><span class="badge bm">Upper + Abdos finisher total</span><span class="badge bt">⏱ 90 min</span></div>
          <div class="card-body">
            <div class="slbl">Upper supersets · 45s repos · 5×12</div>
            <div class="ex"><span class="en">Développé couché / Tractions / Dev militaire / Rowing</span><span class="es">5×12</span></div>
            <div class="slbl">Abdos finisher ultime · 6 rounds · 0 repos</div>
            <div class="ex"><span class="en">Circuit complet enchaîné — tout donner</span><span class="es">6×</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-sam">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Samedi</span><span class="badge bc">Cardio long + Full body + Abdos</span><span class="badge bt">⏱ 120 min</span></div>
          <div class="card-body">
            <div class="ex"><span class="en">Marche inclinée 10%</span><span class="es">60 min</span></div>
            <div class="ex"><span class="en">Circuit muscu léger × 5 rounds · 20s repos</span><span class="es">30 min</span></div>
            <div class="ex"><span class="en">Abdos finisher × 6 rounds sans repos</span><span class="es">25 min</span></div>
            <div class="ex"><span class="en">Étirements</span><span class="es">5 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">120 min</span><span class="dur-detail">Cardio 60 · Muscu 30 · Abdos 25 · Étirements 5</span></div>
          </div>
        </div>
      </div>
      <div class="wday-panel" id="w3-dim">
        <div class="card">
          <div class="card-top"><span class="card-day-lbl">Dimanche</span><span class="badge br">Récupération active finale</span><span class="badge bt">⏱ 100 min</span></div>
          <div class="card-body">
            <div class="ex"><span class="en">Marche inclinée légère</span><span class="es">45 min</span></div>
            <div class="ex"><span class="en">Circuit gainage × 5 rounds + Hollow body 5×45s</span><span class="es">35 min</span></div>
            <div class="ex"><span class="en">Mobilité + Étirements profonds</span><span class="es">20 min</span></div>
            <div class="dur"><span class="dur-lbl">Durée</span><span class="dur-val">100 min</span><span class="dur-detail">Cardio 45 · Gainage 35 · Mobilité 20</span></div>
          </div>
        </div>
      </div>
    </div>
  </div><!-- /w3 -->

</div><!-- /training -->


<!-- ══════════════════════════════════════
     ABDOS
══════════════════════════════════════ -->
<div id="abdos" class="panel pb">
  <div style="height:16px"></div>

  <div class="abdo-hero">
    <div class="ah-tag">Programme Abdos · 3 Semaines</div>
    <div class="ah-title">SCULPTER<br>LA SANGLE</div>
    <div class="ah-sub">Circuit quotidien progressif. Chaque muscle abdominal ciblé. Exécuté à jeun le matin pour brûler max de graisses.</div>
  </div>

  <div class="alert alert-fire"><span class="alert-icon">🔥</span><strong>Règle n°1 des abdos :</strong> On ne voit pas les abdos qu'on travaille, on voit ceux qu'on révèle en brûlant la graisse qui les recouvre. Le cardio et la nutrition font 80% du travail.</div>

  <!-- ── MUSCLES CIBLÉS ── -->
  <div style="padding:0 20px;margin-bottom:14px;">
    <div class="slbl">Muscles ciblés par exercice</div>
    <div class="card" style="box-shadow:none;">
      <div class="card-body" style="padding:0;">
        <div class="ex"><span class="en">Crunch</span><span class="es">Grand droit — partie haute</span></div>
        <div class="ex"><span class="en">Relevé de jambes / suspendu</span><span class="es">Grand droit — partie basse</span></div>
        <div class="ex"><span class="en">Russian twist lesté</span><span class="es">Obliques externes + internes</span></div>
        <div class="ex"><span class="en">Planche frontale</span><span class="es">Transverse + stabilisateurs profonds</span></div>
        <div class="ex"><span class="en">Planche latérale</span><span class="es">Obliques + carré des lombes</span></div>
        <div class="ex"><span class="en">Ab wheel</span><span class="es">Grand droit + transverse + épaules</span></div>
        <div class="ex"><span class="en">Crunch inversé</span><span class="es">Bas du ventre + iliopsoas</span></div>
        <div class="ex"><span class="en">Bird dog</span><span class="es">Transverse + érecteurs spinaux</span></div>
        <div class="ex"><span class="en">Dead bug</span><span class="es">Transverse profond — ventre plat</span></div>
        <div class="ex"><span class="en">Hollow body hold</span><span class="es">Sangle complète — ceinture serrée</span></div>
        <div class="ex"><span class="en">Mountain climbers</span><span class="es">Cardio + grand droit + obliques</span></div>
      </div>
    </div>
  </div>

  <!-- ── SEMAINE 1 ── -->
  <div style="padding:0 20px;margin-bottom:8px;">
    <div class="sec-title" style="font-size:18px;">Semaine 1 <span style="color:var(--ink3);font-size:14px;font-weight:400;">— Mise en route</span></div>
  </div>

  <div style="padding:0 20px;margin-bottom:10px;">
    <div class="abdo-card">
      <div class="abdo-card-head">
        <div class="ach-icon fire">🔴</div>
        <div><div class="ach-title">Circuit A — Quotidien (Lun/Mer/Ven)</div><div class="ach-sub">Après ta séance muscu · 20 min</div></div>
        <div class="ach-sets">4 rounds</div>
      </div>
      <div class="abdo-card-body">
        <div class="abdo-ex">
          <div class="abdo-num">1</div>
          <div class="abdo-info"><div class="abdo-name">Crunch classique</div><div class="abdo-target">Contraction en haut · ne pas tirer la nuque</div></div>
          <div class="abdo-set">25 reps</div>
          <div class="abdo-muscle">Haut</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">2</div>
          <div class="abdo-info"><div class="abdo-name">Relevé de jambes allongé</div><div class="abdo-target">Jambes tendues · bas du dos plaqué au sol</div></div>
          <div class="abdo-set">20 reps</div>
          <div class="abdo-muscle">Bas</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">3</div>
          <div class="abdo-info"><div class="abdo-name">Russian twist lesté</div><div class="abdo-target">2–4 kg · rotation complète · pieds levés</div></div>
          <div class="abdo-set">20 reps</div>
          <div class="abdo-muscle">Obliques</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">4</div>
          <div class="abdo-info"><div class="abdo-name">Planche frontale</div><div class="abdo-target">Corps droit · fessiers contractés</div></div>
          <div class="abdo-set">45s</div>
          <div class="abdo-muscle">Profond</div>
        </div>
      </div>
    </div>

    <div class="abdo-card">
      <div class="abdo-card-head">
        <div class="ach-icon blue">🔵</div>
        <div><div class="ach-title">Circuit B — Cardio-Abdos (Mar/Jeu)</div><div class="ach-sub">Intégré au HIIT · 15 min</div></div>
        <div class="ach-sets">3 rounds</div>
      </div>
      <div class="abdo-card-body">
        <div class="abdo-ex">
          <div class="abdo-num">1</div>
          <div class="abdo-info"><div class="abdo-name">Mountain climbers</div><div class="abdo-target">Rythme soutenu · hanches stables</div></div>
          <div class="abdo-set">40s</div>
          <div class="abdo-muscle">Cardio</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">2</div>
          <div class="abdo-info"><div class="abdo-name">Gainage latéral G + D</div><div class="abdo-target">Hanche levée · ne pas s'affaisser</div></div>
          <div class="abdo-set">40s/côté</div>
          <div class="abdo-muscle">Obliques</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">3</div>
          <div class="abdo-info"><div class="abdo-name">Crunch inversé</div><div class="abdo-target">Bassin vers le haut · contrôle total</div></div>
          <div class="abdo-set">20 reps</div>
          <div class="abdo-muscle">Bas</div>
        </div>
      </div>
    </div>

    <div class="abdo-card">
      <div class="abdo-card-head">
        <div class="ach-icon green">🟢</div>
        <div><div class="ach-title">Gainage profond (Sam/Dim)</div><div class="ach-sub">Récupération active · ventre plat</div></div>
        <div class="ach-sets">5 séries</div>
      </div>
      <div class="abdo-card-body">
        <div class="abdo-ex">
          <div class="abdo-num">1</div>
          <div class="abdo-info"><div class="abdo-name">Planche frontale</div><div class="abdo-target">Respiration abdominale pendant l'effort</div></div>
          <div class="abdo-set">5×1 min</div>
          <div class="abdo-muscle">Profond</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">2</div>
          <div class="abdo-info"><div class="abdo-name">Planche latérale G + D</div><div class="abdo-target">Maintenir l'alignement · ne pas tourner</div></div>
          <div class="abdo-set">4×45s</div>
          <div class="abdo-muscle">Obliques</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">3</div>
          <div class="abdo-info"><div class="abdo-name">Bird dog</div><div class="abdo-target">Bras G + jambe D simultanément · lentement</div></div>
          <div class="abdo-set">3×15/côté</div>
          <div class="abdo-muscle">Profond</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">4</div>
          <div class="abdo-info"><div class="abdo-name">Dead bug</div><div class="abdo-target">Bas du dos plaqué · jambe opposée au bras</div></div>
          <div class="abdo-set">3×15</div>
          <div class="abdo-muscle">Transverse</div>
        </div>
        <div class="abdo-ex">
          <div class="abdo-num">5</div>
          <div class="abdo-info"><div class="abdo-name">Hollow body hold</div><div class="abdo-target">Creuser le ventre · jambes basses · tenir</div></div>
          <div class="abdo-set">4×30s</div>
          <div class="abdo-muscle">Ceinture</div>
        </div>
      </div>
    </div>
  </div>

  <!-- ── SEMAINE 2 ── -->
  <div style="padding:0 20px;margin-bottom:8px;">
    <div class="sec-title" style="font-size:18px;">Semaine 2 <span style="color:var(--ink3);font-size:14px;font-weight:400;">— Intensification</span></div>
  </div>
  <div style="padding:0 20px;margin-bottom:10px;">
    <div class="abdo-card">
      <div class="abdo-card-head">
        <div class="ach-icon fire">🔴</div>
        <div><div class="ach-title">Circuit A+ — Quotidien</div><div class="ach-sub">+1 round · charges augmentées</div></div>
        <div class="ach-sets">5 rounds</div>
      </div>
      <div class="abdo-card-body">
        <div class="abdo-ex"><div class="abdo-num">1</div><div class="abdo-info"><div class="abdo-name">Crunch avec poids sur poitrine</div><div class="abdo-target">2–5 kg · amplitude maximale</div></div><div class="abdo-set">25 reps</div><div class="abdo-muscle">Haut</div></div>
        <div class="abdo-ex"><div class="abdo-num">2</div><div class="abdo-info"><div class="abdo-name">Relevé de jambes suspendu</div><div class="abdo-target">À la barre · jambes tendues · monter haut</div></div><div class="abdo-set">20 reps</div><div class="abdo-muscle">Bas</div></div>
        <div class="abdo-ex"><div class="abdo-num">3</div><div class="abdo-info"><div class="abdo-name">Russian twist 5 kg</div><div class="abdo-target">Vitesse contrôlée · pas de balancier</div></div><div class="abdo-set">25 reps</div><div class="abdo-muscle">Obliques</div></div>
        <div class="abdo-ex"><div class="abdo-num">4</div><div class="abdo-info"><div class="abdo-name">Ab wheel</div><div class="abdo-target">Dos plat · gainage total pendant le mouvement</div></div><div class="abdo-set">15 reps</div><div class="abdo-muscle">Total</div></div>
        <div class="abdo-ex"><div class="abdo-num">5</div><div class="abdo-info"><div class="abdo-name">Planche frontale</div><div class="abdo-target">Tenir 1 min sans trembler</div></div><div class="abdo-set">1 min</div><div class="abdo-muscle">Profond</div></div>
      </div>
    </div>
  </div>

  <!-- ── SEMAINE 3 ── -->
  <div style="padding:0 20px;margin-bottom:8px;">
    <div class="sec-title" style="font-size:18px;">Semaine 3 <span style="color:var(--fire);font-size:14px;font-weight:400;">— Phase finale · 0 repos</span></div>
  </div>
  <div style="padding:0 20px;margin-bottom:10px;">
    <div class="abdo-card">
      <div class="abdo-card-head">
        <div class="ach-icon fire">⚡</div>
        <div><div class="ach-title">Circuit Ultimate Abdos</div><div class="ach-sub">0 repos entre exercices · uniquement entre rounds</div></div>
        <div class="ach-sets">6 rounds</div>
      </div>
      <div class="abdo-card-body">
        <div class="abdo-ex"><div class="abdo-num">1</div><div class="abdo-info"><div class="abdo-name">Crunch lesté</div></div><div class="abdo-set">25 reps</div><div class="abdo-muscle">Haut</div></div>
        <div class="abdo-ex"><div class="abdo-num">2</div><div class="abdo-info"><div class="abdo-name">Relevé jambes suspendu</div></div><div class="abdo-set">25 reps</div><div class="abdo-muscle">Bas</div></div>
        <div class="abdo-ex"><div class="abdo-num">3</div><div class="abdo-info"><div class="abdo-name">Russian twist 6–8 kg</div></div><div class="abdo-set">30 reps</div><div class="abdo-muscle">Obliques</div></div>
        <div class="abdo-ex"><div class="abdo-num">4</div><div class="abdo-info"><div class="abdo-name">Ab wheel — 20 reps</div></div><div class="abdo-set">20 reps</div><div class="abdo-muscle">Total</div></div>
        <div class="abdo-ex"><div class="abdo-num">5</div><div class="abdo-info"><div class="abdo-name">Hollow body hold</div></div><div class="abdo-set">45s</div><div class="abdo-muscle">Ceinture</div></div>
        <div class="abdo-ex"><div class="abdo-num">6</div><div class="abdo-info"><div class="abdo-name">Mountain climbers</div></div><div class="abdo-set">45s</div><div class="abdo-muscle">Cardio</div></div>
      </div>
    </div>
  </div>

  <div class="alert alert-green"><span class="alert-icon">✅</span><strong>Bird dog + Dead bug</strong> = les 2 exercices les plus efficaces pour le ventre plat. Ils activent le muscle transverse qui agit comme une gaine naturelle autour du ventre.</div>
</div>


<!-- ══════════════════════════════════════
     NUTRITION
══════════════════════════════════════ -->
<div id="nutrition" class="panel pb">
  <div style="height:16px"></div>

  <div class="alert alert-blue" style="margin-bottom:14px;"><span class="alert-icon">🧮</span><strong>Calculé sur ton poids.</strong> 66,6 kg × 2,2 = 147g protéines/jour. Ces macros sont taillées pour toi, pas pour un programme générique.</div>

  <div class="nutri-tabs">
    <div class="ntab active" onclick="showNutri('n1',this)">S1 · 1900</div>
    <div class="ntab" onclick="showNutri('n2',this)">S2 · 1750</div>
    <div class="ntab" onclick="showNutri('n3',this)">S3 · 1600</div>
  </div>

  <div id="n1" class="nutri-panel active" style="padding:0 20px;">
    <div class="macro-grid">
      <div class="mbox"><div class="mnum" style="color:var(--blue)">1900</div><div class="mlbl">kcal</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--green)">147g</div><div class="mlbl">Prot.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--gold)">196g</div><div class="mlbl">Gluc.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--fire)">55g</div><div class="mlbl">Lip.</div></div>
    </div>
  </div>
  <div id="n2" class="nutri-panel" style="padding:0 20px;">
    <div class="macro-grid">
      <div class="mbox"><div class="mnum" style="color:var(--blue)">1750</div><div class="mlbl">kcal</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--green)">147g</div><div class="mlbl">Prot.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--gold)">158g</div><div class="mlbl">Gluc.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--fire)">50g</div><div class="mlbl">Lip.</div></div>
    </div>
  </div>
  <div id="n3" class="nutri-panel" style="padding:0 20px;">
    <div class="macro-grid">
      <div class="mbox"><div class="mnum" style="color:var(--blue)">1600</div><div class="mlbl">kcal</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--green)">150g</div><div class="mlbl">Prot.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--gold)">115g</div><div class="mlbl">Gluc.</div></div>
      <div class="mbox"><div class="mnum" style="color:var(--fire)">48g</div><div class="mlbl">Lip.</div></div>
    </div>
  </div>

  <div style="padding:0 20px;margin-bottom:10px;">
    <div class="card" style="box-shadow:none;">
      <div class="card-top" style="padding-bottom:12px;"><span class="card-day-lbl" style="font-size:16px;">Menu type · Toutes semaines</span></div>
      <div class="card-body" style="padding-top:0;">
        <div class="food-row"><span>☕ Réveil à jeun — café noir</span><span class="food-kcal">0 kcal</span></div>
        <div class="food-row"><span>🥚 Petit-déj : 4 œufs brouillés + flocons d'avoine 60g</span><span class="food-kcal">~480 kcal</span></div>
        <div class="food-row"><span>🍗 Déjeuner : poulet 200g + riz 150g cuit + légumes verts</span><span class="food-kcal">~550 kcal</span></div>
        <div class="food-row"><span>🥛 Collation : fromage blanc 0% 250g + amandes 10g</span><span class="food-kcal">~180 kcal</span></div>
        <div class="food-row"><span>🐟 Dîner : poisson 200g + légumes vapeur 300g <em style="color:var(--ink3);font-size:11px;">(S3 sans féculent)</em></span><span class="food-kcal">~350 kcal</span></div>
        <div class="food-row"><span>💪 Post-training : whey 35g dans eau</span><span class="food-kcal">~140 kcal</span></div>
        <div class="food-row"><span>🥗 Snack si faim : légumes crus + yaourt grec</span><span class="food-kcal">~100 kcal</span></div>
      </div>
    </div>

    <div class="slbl">Sources protéines recommandées · 147g/j</div>
    <div class="card" style="box-shadow:none;">
      <div class="card-body" style="padding:0;">
        <div class="ex"><span class="en">Poulet / dinde (200g)</span><span class="es">~46g prot</span></div>
        <div class="ex"><span class="en">Œufs (4 entiers)</span><span class="es">~28g prot</span></div>
        <div class="ex"><span class="en">Whey (35g)</span><span class="es">~28g prot</span></div>
        <div class="ex"><span class="en">Fromage blanc 0% (250g)</span><span class="es">~22g prot</span></div>
        <div class="ex"><span class="en">Poisson (200g)</span><span class="es">~40g prot</span></div>
        <div class="ex" style="border:none"><span class="en"><strong>TOTAL</strong></span><span class="es" style="color:var(--fire);font-size:13px;"><strong>164g ✓</strong></span></div>
      </div>
    </div>
  </div>

  <div class="alert alert-fire"><span class="alert-icon">🚫</span><strong>Interdit 3 semaines :</strong> alcool · sucre raffiné · sauce · pain blanc · viennoiseries · sodas · fromage gras. C'est court, tiens bon.</div>
  <div class="alert alert-green"><span class="alert-icon">♾️</span><strong>À volonté :</strong> brocoli · épinards · courgette · haricots verts · salade · concombre · champignons. Aucun risque de trop manger ces légumes.</div>
</div>


<!-- ══════════════════════════════════════
     RÈGLES
══════════════════════════════════════ -->
<div id="regles" class="panel pb">
  <div style="height:16px"></div>

  <div style="padding:0 20px;margin-bottom:14px;">
    <div class="card" style="box-shadow:none;">
      <div class="card-top" style="padding-bottom:12px;"><span class="card-day-lbl" style="font-size:18px;">Les 5 règles absolues</span></div>
      <div class="card-body" style="padding-top:0;">
        <div class="rule-item"><div class="rule-num">1</div><div class="rule-text"><strong>Peser TOUS les aliments.</strong> Balance de cuisine obligatoire — "à vue d'œil" c'est ±30% d'erreur.</div></div>
        <div class="rule-item"><div class="rule-num">2</div><div class="rule-text"><strong>7h30 de sommeil minimum.</strong> Sans sommeil le cortisol monte, la lipolyse s'effondre et le muscle fond.</div></div>
        <div class="rule-item"><div class="rule-num">3</div><div class="rule-text"><strong>3 litres d'eau par jour.</strong> Élimine la rétention, améliore la définition, coupe la faim.</div></div>
        <div class="rule-item"><div class="rule-num">4</div><div class="rule-text"><strong>Zéro écart pendant 21 jours.</strong> Un écart n'annule pas tout — mais le fait mentalement et psychologiquement.</div></div>
        <div class="rule-item"><div class="rule-num">5</div><div class="rule-text"><strong>Protéines à chaque repas.</strong> 147g/jour pour toi. C'est le seul moyen de perdre du gras sans perdre le muscle.</div></div>
      </div>
    </div>

    <div class="card" style="box-shadow:none;">
      <div class="card-top" style="padding-bottom:12px;"><span class="card-day-lbl" style="font-size:18px;">Suppléments <span style="font-size:13px;color:var(--ink3);font-weight:400;">(optionnel)</span></span></div>
      <div class="card-body" style="padding-top:0;">
        <div class="suppl-item"><div class="suppl-ico">🥛</div><div><div class="suppl-name">Whey protéine · post-training</div><div class="suppl-desc">Si tu atteins pas 147g/j par l'alimentation seule</div></div></div>
        <div class="suppl-item"><div class="suppl-ico">💊</div><div><div class="suppl-name">Créatine · 5g/jour</div><div class="suppl-desc">Conserve la force et le volume musculaire en déficit</div></div></div>
        <div class="suppl-item"><div class="suppl-ico">☕</div><div><div class="suppl-name">Caféine · avant HIIT</div><div class="suppl-desc">Booste la lipolyse de 10–15% et améliore la performance</div></div></div>
        <div class="suppl-item"><div class="suppl-ico">🌙</div><div><div class="suppl-name">Magnésium · le soir</div><div class="suppl-desc">Améliore la qualité du sommeil = récupération + sèche</div></div></div>
        <div class="suppl-item"><div class="suppl-ico">🐟</div><div><div class="suppl-name">Oméga-3 · 3g/jour</div><div class="suppl-desc">Anti-inflammatoire · préserve la masse musculaire en déficit</div></div></div>
      </div>
    </div>
  </div>

  <div class="alert alert-gold"><span class="alert-icon">🎯</span><strong>Résultat réaliste en 3 semaines à 1m65 / 66,6 kg :</strong> −2 à −2,5 kg de gras, abdos nettement plus définis, définition musculaire visible sur tout le corps. Si tu pars de moins de 16% de masse grasse, les abdos deviennent visibles.</div>
  <div class="alert alert-fire"><span class="alert-icon">📸</span>Prends une photo avant le Jour 1. Tu comprendras après 21 jours pourquoi c'était une bonne idée.</div>
</div>


<script>
// ── MAIN NAV ──
function showMain(id, el) {
  document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(t => t.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  el.classList.add('active');
}

// ── WEEK SELECTOR ──
function showWeek(id, el) {
  document.querySelectorAll('.wk-panel').forEach(p => p.style.display = 'none');
  document.querySelectorAll('.wpill').forEach(t => t.classList.remove('active'));
  document.getElementById(id).style.display = 'block';
  el.classList.add('active');
}

// ── DAY SELECTOR ──
function showDay(week, day, el) {
  const wPanel = document.getElementById(week);
  wPanel.querySelectorAll('.wday-panel').forEach(p => p.classList.remove('active'));
  const ds = document.getElementById('ds-' + week);
  ds.querySelectorAll('.dpill').forEach(t => t.classList.remove('active'));
  document.getElementById(week + '-' + day).classList.add('active');
  el.classList.add('active');
}

// ── NUTRITION ──
function showNutri(id, el) {
  document.querySelectorAll('.nutri-panel').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.ntab').forEach(t => t.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  el.classList.add('active');
}
</script>
</body>
</html>
