<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Amphi Blanc — Affectations</title>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;600&family=IBM+Plex+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg:       #0F0F0F;
    --surface:  #181818;
    --surface2: #222222;
    --border:   rgba(255,255,255,0.08);
    --border2:  rgba(255,255,255,0.15);
    --text:     #F0EDE8;
    --text2:    #9A9690;
    --text3:    #5A5652;
    --gold:     #C9A84C;
    --gold-bg:  rgba(201,168,76,0.12);
    --gold-lt:  rgba(201,168,76,0.06);
    --green:    #4CAF7D;
    --green-bg: rgba(76,175,125,0.12);
    --red:      #E05555;
    --red-bg:   rgba(224,85,85,0.12);
    --blue:     #5B8FD4;
    --radius:   6px;
    --radius-lg:10px;
  }
  html { font-family: 'IBM Plex Sans', sans-serif; background: var(--bg); color: var(--text); font-size: 14px; line-height: 1.5; }
  body { min-height: 100vh; }

  /* ── Layout ── */
  .page { max-width: 1000px; margin: 0 auto; padding: 2rem 1.5rem 4rem; }
  .header { display: flex; align-items: flex-end; justify-content: space-between; margin-bottom: 2rem; padding-bottom: 1.5rem; border-bottom: 1px solid var(--border2); }
  .header-left {}
  .title { font-family: 'IBM Plex Mono', monospace; font-size: 22px; font-weight: 600; color: var(--text); letter-spacing: -0.02em; }
  .title span { color: var(--gold); }
  .subtitle { font-size: 12px; color: var(--text3); margin-top: 3px; letter-spacing: 0.04em; text-transform: uppercase; }
  .sync-indicator { font-family: 'IBM Plex Mono', monospace; font-size: 11px; color: var(--text3); display: flex; align-items: center; gap: 6px; }
  .dot { width: 6px; height: 6px; border-radius: 50%; background: var(--text3); flex-shrink: 0; }
  .dot.live { background: var(--green); box-shadow: 0 0 6px var(--green); animation: pulse 2s infinite; }
  @keyframes pulse { 0%,100% { opacity:1; } 50% { opacity:0.5; } }

  /* ── Screens ── */
  .screen { display: none; }
  .screen.active { display: block; }

  /* ── Lock ── */
  .lock-wrap { display: flex; align-items: center; justify-content: center; min-height: 60vh; }
  .lock-box { background: var(--surface); border: 1px solid var(--border2); border-radius: var(--radius-lg); padding: 2.5rem 2rem; width: 100%; max-width: 360px; }
  .lock-box h2 { font-family: 'IBM Plex Mono', monospace; font-size: 16px; font-weight: 600; margin-bottom: 4px; }
  .lock-box p { font-size: 12px; color: var(--text2); margin-bottom: 1.5rem; }
  .lock-divider { border: none; border-top: 1px solid var(--border); margin: 1.5rem 0; }

  /* ── Forms ── */
  .field { margin-bottom: 12px; }
  .field label { display: block; font-size: 11px; font-weight: 500; color: var(--text3); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 5px; }
  input[type="text"], input[type="password"], textarea, select {
    width: 100%; background: var(--bg); border: 1px solid var(--border2); border-radius: var(--radius);
    padding: 8px 10px; color: var(--text); font-family: 'IBM Plex Sans', sans-serif; font-size: 13px; outline: none;
    transition: border-color .15s, box-shadow .15s;
  }
  input:focus, textarea:focus, select:focus { border-color: var(--gold); box-shadow: 0 0 0 3px rgba(201,168,76,0.15); }
  textarea { min-height: 120px; resize: vertical; line-height: 1.6; }
  select { appearance: none; background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='10' height='6' viewBox='0 0 10 6'%3E%3Cpath d='M1 1l4 4 4-4' stroke='%239A9690' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E"); background-repeat: no-repeat; background-position: right 10px center; padding-right: 28px; cursor: pointer; }
  select option { background: #222; }
  .pin-row { display: flex; gap: 8px; }
  .err-msg { font-size: 11px; color: var(--red); margin-top: 6px; min-height: 14px; }

  /* ── Buttons ── */
  .btn { display: inline-flex; align-items: center; gap: 5px; border-radius: var(--radius); padding: 0 14px; height: 34px; cursor: pointer; font-size: 12px; font-weight: 500; font-family: 'IBM Plex Sans', sans-serif; border: 1px solid var(--border2); background: var(--surface2); color: var(--text); transition: background .15s, border-color .15s; white-space: nowrap; }
  .btn:hover { background: #2a2a2a; border-color: var(--border2); }
  .btn-gold { background: var(--gold); border-color: var(--gold); color: #0F0F0F; font-weight: 600; }
  .btn-gold:hover { background: #d4b05a; }
  .btn-green { background: var(--green-bg); border-color: rgba(76,175,125,0.3); color: var(--green); }
  .btn-green:hover { background: rgba(76,175,125,0.2); }
  .btn-red { background: var(--red-bg); border-color: rgba(224,85,85,0.3); color: var(--red); }
  .btn-red:hover { background: rgba(224,85,85,0.2); }
  .btn-lg { height: 42px; font-size: 14px; border-radius: var(--radius); }
  .btn-sm { height: 28px; padding: 0 10px; font-size: 11px; }
  .btn-full { width: 100%; justify-content: center; }

  /* ── Tabs ── */
  .tabs { display: flex; border-bottom: 1px solid var(--border); margin-bottom: 1.5rem; gap: 0; }
  .tab { background: none; border: none; border-bottom: 2px solid transparent; padding: 10px 16px; cursor: pointer; font-size: 12px; font-weight: 500; color: var(--text3); font-family: 'IBM Plex Sans', sans-serif; white-space: nowrap; transition: color .15s, border-color .15s; margin-bottom: -1px; letter-spacing: 0.02em; text-transform: uppercase; }
  .tab:hover { color: var(--text); }
  .tab.active { color: var(--gold); border-bottom-color: var(--gold); }
  .admin-tab { display: none; }

  /* ── Cards ── */
  .card { background: var(--surface); border: 1px solid var(--border); border-radius: var(--radius-lg); padding: 1.25rem; margin-bottom: 1rem; }
  .card-title { font-family: 'IBM Plex Mono', monospace; font-size: 12px; font-weight: 600; color: var(--text2); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 1rem; }

  /* ── Stats ── */
  .stats { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 1.5rem; }
  .stat { background: var(--surface); border: 1px solid var(--border); border-radius: var(--radius); padding: 1rem; }
  .stat-label { font-size: 10px; font-weight: 500; color: var(--text3); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 4px; }
  .stat-value { font-family: 'IBM Plex Mono', monospace; font-size: 28px; font-weight: 600; color: var(--text); }
  .stat-value.gold { color: var(--gold); }

  /* ── Progress bar ── */
  .progress-wrap { margin-bottom: 1.5rem; }
  .progress-label { display: flex; justify-content: space-between; font-size: 11px; color: var(--text3); margin-bottom: 6px; }
  .progress-bar { height: 4px; background: var(--surface2); border-radius: 99px; overflow: hidden; }
  .progress-fill { height: 100%; background: var(--gold); border-radius: 99px; transition: width .4s ease; }

  /* ── Main affectation table ── */
  .aff-table-wrap { background: var(--surface); border: 1px solid var(--border); border-radius: var(--radius-lg); overflow: hidden; }
  .aff-table-head { display: flex; justify-content: space-between; align-items: center; padding: 12px 16px; border-bottom: 1px solid var(--border); }
  .aff-table-title { font-family: 'IBM Plex Mono', monospace; font-size: 12px; font-weight: 600; color: var(--text2); text-transform: uppercase; letter-spacing: 0.06em; }
  table { width: 100%; border-collapse: collapse; }
  th { text-align: left; padding: 8px 14px; font-size: 10px; font-weight: 600; color: var(--text3); border-bottom: 1px solid var(--border); text-transform: uppercase; letter-spacing: 0.06em; background: var(--bg); }
  td { padding: 0; border-bottom: 1px solid var(--border); vertical-align: middle; }
  tr:last-child td { border-bottom: none; }
  .td-inner { padding: 8px 14px; display: flex; align-items: center; }
  tr:hover td { background: rgba(255,255,255,0.02); }

  /* Rang badge */
  .rang { font-family: 'IBM Plex Mono', monospace; font-size: 12px; font-weight: 600; color: var(--text3); min-width: 32px; }
  .rang.top3 { color: var(--gold); }

  /* Nom */
  .nom { font-size: 13px; font-weight: 500; color: var(--text); }

  /* Select inline */
  .select-poste { background: transparent; border: 1px solid transparent; border-radius: var(--radius); padding: 5px 28px 5px 8px; color: var(--text); font-size: 12px; font-family: 'IBM Plex Sans', sans-serif; cursor: pointer; transition: border-color .15s, background .15s; min-width: 240px; max-width: 100%; }
  .select-poste:hover { border-color: var(--border2); background: var(--surface2); }
  .select-poste:focus { border-color: var(--gold); background: var(--surface2); box-shadow: 0 0 0 2px rgba(201,168,76,0.15); }
  .select-poste.chosen { color: var(--gold); font-weight: 500; border-color: rgba(201,168,76,0.3); background: var(--gold-bg); }

  /* Status pill */
  .pill { display: inline-flex; align-items: center; gap: 4px; font-family: 'IBM Plex Mono', monospace; font-size: 10px; font-weight: 600; padding: 3px 8px; border-radius: 99px; }
  .pill-done { background: var(--green-bg); color: var(--green); border: 1px solid rgba(76,175,125,0.2); }
  .pill-pending { background: var(--surface2); color: var(--text3); border: 1px solid var(--border); }

  /* Admin table */
  .admin-table-wrap { background: var(--surface); border: 1px solid var(--border); border-radius: var(--radius-lg); overflow: hidden; margin-bottom: 1rem; }
  .admin-table-head { display: flex; justify-content: space-between; align-items: center; padding: 10px 14px; border-bottom: 1px solid var(--border); }
  .admin-table-title { font-family: 'IBM Plex Mono', monospace; font-size: 11px; font-weight: 600; color: var(--text3); text-transform: uppercase; letter-spacing: 0.06em; }
  .badge { display: inline-block; font-family: 'IBM Plex Mono', monospace; font-size: 10px; font-weight: 600; padding: 2px 8px; border-radius: 99px; background: var(--surface2); color: var(--text3); border: 1px solid var(--border); }
  .del-btn { background: none; border: none; cursor: pointer; color: var(--text3); font-size: 12px; padding: 3px 6px; border-radius: 4px; transition: color .15s, background .15s; }
  .del-btn:hover { color: var(--red); background: var(--red-bg); }
  .empty { text-align: center; padding: 2.5rem; color: var(--text3); font-size: 12px; }
  .flex-gap { display: flex; align-items: center; gap: 8px; flex-wrap: wrap; }
  .flex-between { display: flex; align-items: center; justify-content: space-between; }

  /* Status msg */
  .status-msg { font-size: 11px; min-height: 16px; font-weight: 500; }
  .ok { color: var(--green); }
  .er { color: var(--red); }

  code { font-family: 'IBM Plex Mono', monospace; font-size: 11px; background: var(--surface2); padding: 1px 5px; border-radius: 3px; color: var(--text2); }

  @media (max-width: 600px) {
    .stats { grid-template-columns: 1fr 1fr; }
    .select-poste { min-width: 160px; }
    .header { flex-direction: column; align-items: flex-start; gap: 8px; }
  }
</style>
</head>
<body>

<script>
const firebaseConfig = {
  apiKey: "AIzaSyDjAt_9gox702UaXf7-EYGojv-nbfYwYuY",
  authDomain: "amphi-blanc---voeux-finaux.firebaseapp.com",
  databaseURL: "https://amphi-blanc---voeux-finaux-default-rtdb.europe-west1.firebasedatabase.app",
  projectId: "amphi-blanc---voeux-finaux",
  storageBucket: "amphi-blanc---voeux-finaux.firebasestorage.app",
  messagingSenderId: "91659498687",
  appId: "1:91659498687:web:33b4a83265eaaef4e5c20a",
  measurementId: "G-S6P9DLTJ2N"
};
// Utilise un nœud Firebase séparé pour ne pas interférer avec l'autre plateforme
const FB_ROOT = 'amphi';
const FIREBASE_CONFIGURED = !FIREBASE_CONFIG.apiKey.startsWith('VOTRE');
</script>

<div class="page">
  <div class="header">
    <div class="header-left">
      <div class="title">Amphi <span>Blanc</span></div>
      <div class="subtitle">Affectations définitives — Promotion 50</div>
    </div>
    <div class="sync-indicator">
      <span class="dot" id="sync-dot"></span>
      <span id="sync-label">—</span>
    </div>
  </div>

  <!-- ══ LOCK ══ -->
  <div id="screen-lock" class="screen active">
    <div class="lock-wrap">
      <div class="lock-box">
        <h2>Accès</h2>
        <p>Entrez le code administrateur pour gérer les données, ou accédez directement à l'amphi.</p>
        <div class="field">
          <label>Code administrateur</label>
          <div class="pin-row">
            <input type="password" id="admin-pin-input" placeholder="Code admin" onkeydown="if(event.key==='Enter')tryAdmin()" />
            <button class="btn btn-gold" onclick="tryAdmin()">Entrer</button>
          </div>
          <div class="err-msg" id="pin-err"></div>
        </div>
        <hr class="lock-divider" />
        <button class="btn btn-lg btn-full" onclick="showScreen('screen-amphi')" style="background:var(--surface2);border-color:var(--border2);">
          → Accéder à l'amphi blanc
        </button>
      </div>
    </div>
  </div>

  <!-- ══ ADMIN ══ -->
  <div id="screen-admin" class="screen">
    <div class="flex-between" style="margin-bottom:1.5rem;">
      <div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:16px;font-weight:600;">Administration</div>
        <div style="font-size:11px;color:var(--text3);margin-top:2px;">Gérez les élèves et les postes</div>
      </div>
      <div class="flex-gap">
        <button class="btn btn-sm" onclick="exportCSV()">Exporter CSV</button>
        <button class="btn btn-sm" onclick="showScreen('screen-amphi')">→ Amphi</button>
        <button class="btn btn-sm" onclick="showScreen('screen-lock')">Verrouiller</button>
      </div>
    </div>

    <div class="tabs">
      <button class="tab active" onclick="switchTab('tab-eleves',this)">Élèves</button>
      <button class="tab" onclick="switchTab('tab-postes',this)">Postes</button>
      <button class="tab" onclick="switchTab('tab-resultats',this)">Résultats</button>
      <button class="tab" onclick="switchTab('tab-settings',this)">Paramètres</button>
    </div>

    <!-- Tab élèves -->
    <div id="tab-eleves" class="admin-tab" style="display:block;">
      <div class="card">
        <div class="card-title">Importer des élèves</div>
        <p style="font-size:12px;color:var(--text2);margin-bottom:10px;">Un élève par ligne : <code>rang;Prénom Nom</code> — ex : <code>1;Marie Dupont</code></p>
        <div class="field"><textarea id="eleves-bulk" placeholder="1;Marie Dupont&#10;2;Jean Martin&#10;3;Sophie Bernard"></textarea></div>
        <div class="flex-gap">
          <button class="btn btn-gold" onclick="importEleves()">Importer</button>
          <button class="btn btn-red btn-sm" onclick="clearEleves()">Tout effacer</button>
        </div>
        <div class="status-msg" id="eleves-status"></div>
      </div>
      <div class="admin-table-wrap">
        <div class="admin-table-head">
          <span class="admin-table-title">Élèves enregistrés</span>
          <span class="badge" id="eleves-count">0</span>
        </div>
        <div id="eleves-table"><div class="empty">Aucun élève enregistré.</div></div>
      </div>
    </div>

    <!-- Tab postes -->
    <div id="tab-postes" class="admin-tab">
      <div class="card">
        <div class="card-title">Importer des postes</div>
        <p style="font-size:12px;color:var(--text2);margin-bottom:10px;">Un poste par ligne. Les doublons sont gérés automatiquement (ex : 8 fois le même nom = 8 exemplaires).</p>
        <div class="field"><textarea id="postes-bulk" placeholder="Chargé de mission préfectoral&#10;Chargé de mission préfectoral&#10;Chargé de mission DASEN&#10;Attaché d'administration hospitalière"></textarea></div>
        <div class="flex-gap">
          <button class="btn btn-gold" onclick="importPostes()">Importer</button>
          <button class="btn btn-red btn-sm" onclick="clearPostes()">Tout effacer</button>
        </div>
        <div class="status-msg" id="postes-status"></div>
      </div>
      <div class="admin-table-wrap">
        <div class="admin-table-head">
          <span class="admin-table-title">Postes enregistrés</span>
          <span class="badge" id="postes-count">0</span>
        </div>
        <div id="postes-table"><div class="empty">Aucun poste enregistré.</div></div>
      </div>
    </div>

    <!-- Tab résultats -->
    <div id="tab-resultats" class="admin-tab">
      <div class="flex-between" style="margin-bottom:1rem;">
        <div style="font-size:12px;color:var(--text2);">Affectations enregistrées en temps réel.</div>
        <div class="flex-gap">
          <button class="btn btn-sm" onclick="exportCSV()">Exporter CSV</button>
          <button class="btn btn-red btn-sm" onclick="resetAffectations()">Réinitialiser</button>
        </div>
      </div>
      <div class="admin-table-wrap">
        <div id="resultats-table"><div class="empty">Aucune affectation enregistrée.</div></div>
      </div>
    </div>

    <!-- Tab paramètres -->
    <div id="tab-settings" class="admin-tab">
      <div class="card">
        <div class="card-title">Code administrateur</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px;">
          <div class="field"><label>Nouveau code</label><input type="password" id="new-pin" placeholder="Nouveau code" /></div>
          <div class="field"><label>Confirmer</label><input type="password" id="confirm-pin" placeholder="Confirmer" /></div>
        </div>
        <button class="btn btn-gold" onclick="changePin()">Enregistrer</button>
        <div class="status-msg" id="pin-change-status"></div>
      </div>
    </div>
  </div>

  <!-- ══ AMPHI ══ -->
  <div id="screen-amphi" class="screen">
    <div class="flex-between" style="margin-bottom:1.5rem;">
      <div>
        <div style="font-family:'IBM Plex Mono',monospace;font-size:16px;font-weight:600;">Affectations en direct</div>
        <div style="font-size:11px;color:var(--text3);margin-top:2px;">Sélectionnez le poste de chaque élève au fur et à mesure</div>
      </div>
      <button class="btn btn-sm" onclick="showScreen('screen-lock')">← Retour</button>
    </div>

    <div class="stats">
      <div class="stat">
        <div class="stat-label">Affectés</div>
        <div class="stat-value gold" id="stat-affectes">0</div>
      </div>
      <div class="stat">
        <div class="stat-label">En attente</div>
        <div class="stat-value" id="stat-attente">—</div>
      </div>
      <div class="stat">
        <div class="stat-label">Postes restants</div>
        <div class="stat-value" id="stat-postes">—</div>
      </div>
    </div>

    <div class="progress-wrap">
      <div class="progress-label">
        <span>Progression</span>
        <span id="progress-pct">0%</span>
      </div>
      <div class="progress-bar"><div class="progress-fill" id="progress-fill" style="width:0%"></div></div>
    </div>

    <div class="aff-table-wrap">
      <div class="aff-table-head">
        <span class="aff-table-title">Liste des élèves</span>
        <input type="text" id="amphi-search" placeholder="Rechercher…" style="width:180px;height:28px;font-size:11px;" oninput="renderAmphiTable()" />
      </div>
      <div id="amphi-table"><div class="empty">Chargement…</div></div>
    </div>
  </div>
</div>

<script src="https://www.gstatic.com/firebasejs/10.12.2/firebase-app-compat.js"></script>
<script src="https://www.gstatic.com/firebasejs/10.12.2/firebase-database-compat.js"></script>

<script>
// ════════════════════════════════════════════════════
//  ÉTAT
// ════════════════════════════════════════════════════
let eleves = [];       // [{rang, nom}]
let postes = [];       // [{id, nom, order}]
let affectations = {}; // { rang: posteId }
let db = null;

// ════════════════════════════════════════════════════
//  FIREBASE
// ════════════════════════════════════════════════════
function initFirebase() {
  if (!FIREBASE_CONFIGURED) { loadLocal(); return; }
  try {
    firebase.initializeApp(FIREBASE_CONFIG);
    db = firebase.database();
    setSync('Connexion…', false);
    setupListeners();
  } catch(e) { setSync('Erreur', false); }
}

function setSync(label, live) {
  document.getElementById('sync-label').textContent = label;
  document.getElementById('sync-dot').className = 'dot' + (live ? ' live' : '');
}

function setupListeners() {
  [['eleves', v => { eleves = v ? Object.values(v).sort((a,b)=>a.rang-b.rang) : []; }],
   ['postes', v => { postes = v ? Object.values(v).sort((a,b)=>(a.order||0)-(b.order||0)) : []; }],
   ['affectations', v => { affectations = v || {}; }]
  ].forEach(([path, handler]) => {
    db.ref(FB_ROOT+'/'+path).on('value', snap => {
      handler(snap.val());
      refresh();
      setSync('Sync · '+new Date().toLocaleTimeString('fr-FR',{hour:'2-digit',minute:'2-digit'}), true);
    });
  });
}

const LS = {
  get: k => { try { return JSON.parse(localStorage.getItem('amphi_'+k)); } catch(e){ return null; } },
  set: (k,v) => localStorage.setItem('amphi_'+k, JSON.stringify(v))
};
function loadLocal() {
  eleves       = LS.get('eleves')       || [];
  postes       = (LS.get('postes')      || []).sort((a,b)=>(a.order||0)-(b.order||0));
  affectations = LS.get('affectations') || {};
  refresh();
  setSync('Local', false);
}

// ════════════════════════════════════════════════════
//  NAVIGATION
// ════════════════════════════════════════════════════
function showScreen(id) {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  refresh();
}
function switchTab(tabId, btn) {
  document.querySelectorAll('.admin-tab').forEach(t => t.style.display='none');
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  document.getElementById(tabId).style.display = 'block';
  btn.classList.add('active');
}

// ════════════════════════════════════════════════════
//  AUTH
// ════════════════════════════════════════════════════
async function tryAdmin() {
  const pin = document.getElementById('admin-pin-input').value;
  let stored = 'admin2024';
  if (db) { try { const s = await db.ref(FB_ROOT+'/settings/pin').get(); if (s.val()) stored = s.val(); } catch(e){} }
  else stored = LS.get('pin') || 'admin2024';
  if (pin === stored) {
    document.getElementById('admin-pin-input').value = '';
    document.getElementById('pin-err').textContent = '';
    showScreen('screen-admin');
  } else {
    document.getElementById('pin-err').textContent = 'Code incorrect.';
  }
}
async function changePin() {
  const p1 = document.getElementById('new-pin').value;
  const p2 = document.getElementById('confirm-pin').value;
  if (!p1) { setStatus('pin-change-status','Entrez un code.','er'); return; }
  if (p1 !== p2) { setStatus('pin-change-status','Les codes ne correspondent pas.','er'); return; }
  if (db) await db.ref(FB_ROOT+'/settings/pin').set(p1);
  else LS.set('pin', p1);
  document.getElementById('new-pin').value = '';
  document.getElementById('confirm-pin').value = '';
  setStatus('pin-change-status','Code modifié.','ok');
}

// ════════════════════════════════════════════════════
//  LOGIQUE — postes disponibles
// ════════════════════════════════════════════════════
function postesDisponibles() {
  // IDs déjà pris
  const pris = new Set(Object.values(affectations).filter(Boolean));
  return postes.filter(p => !pris.has(p.id));
}

function nomPoste(id) {
  return postes.find(p => p.id === id)?.nom || '';
}

// ════════════════════════════════════════════════════
//  AFFECTATION
// ════════════════════════════════════════════════════
async function setAffectation(rang, posteId) {
  if (db) {
    if (posteId) {
      await db.ref(`${FB_ROOT}/affectations/${rang}`).set(posteId);
    } else {
      await db.ref(`${FB_ROOT}/affectations/${rang}`).remove();
    }
  } else {
    if (posteId) affectations[rang] = posteId;
    else delete affectations[rang];
    LS.set('affectations', affectations);
    refresh();
  }
}

// ════════════════════════════════════════════════════
//  REFRESH GLOBAL
// ════════════════════════════════════════════════════
function refresh() {
  renderAdminEleves();
  renderAdminPostes();
  renderResultats();
  renderAmphiTable();
  updateStats();
}

// ════════════════════════════════════════════════════
//  STATS
// ════════════════════════════════════════════════════
function updateStats() {
  const nbAff = Object.keys(affectations).filter(k => affectations[k]).length;
  const nbTotal = eleves.length;
  const nbRestants = postesDisponibles().length;
  document.getElementById('stat-affectes').textContent  = nbAff;
  document.getElementById('stat-attente').textContent   = Math.max(0, nbTotal - nbAff);
  document.getElementById('stat-postes').textContent    = nbRestants;
  const pct = nbTotal > 0 ? Math.round((nbAff / nbTotal) * 100) : 0;
  document.getElementById('progress-fill').style.width  = pct + '%';
  document.getElementById('progress-pct').textContent   = pct + '%';
}

// ════════════════════════════════════════════════════
//  RENDER — AMPHI
// ════════════════════════════════════════════════════
function renderAmphiTable() {
  const el = document.getElementById('amphi-table');
  if (!el) return;
  if (!eleves.length) { el.innerHTML = '<div class="empty">Aucun élève enregistré. Configurez la liste dans l\'administration.</div>'; return; }

  const q = (document.getElementById('amphi-search')?.value || '').toLowerCase();
  const filtered = eleves.filter(e =>
    !q || String(e.rang) === q.trim() || e.nom.toLowerCase().includes(q)
  );
  if (!filtered.length) { el.innerHTML = '<div class="empty">Aucun résultat.</div>'; return; }

  const dispo = postesDisponibles();

  const rows = filtered.map(e => {
    const affId = affectations[e.rang] || '';
    const affNom = affId ? nomPoste(affId) : '';
    const isAff = !!affId;

    // Options : poste actuel (même s'il est "pris") + postes disponibles
    let options = `<option value="">— Choisir un poste —</option>`;
    // Si un poste est déjà affecté à cet élève, l'afficher en premier
    if (affId) {
      options += `<option value="${affId}" selected>${esc(affNom)}</option>`;
    }
    // Ajouter tous les postes disponibles (non encore pris)
    dispo.forEach(p => {
      if (p.id !== affId) { // ne pas dupliquer si déjà affiché
        options += `<option value="${p.id}">${esc(p.nom)}</option>`;
      }
    });

    const rangClass = e.rang <= 3 ? 'rang top3' : 'rang';

    return `<tr>
      <td><div class="td-inner"><span class="${rangClass}">${e.rang}</span></div></td>
      <td><div class="td-inner"><span class="nom">${esc(e.nom)}</span></div></td>
      <td style="width:100%">
        <div class="td-inner" style="gap:10px;">
          <select class="select-poste${isAff?' chosen':''}"
            onchange="handleSelectChange(${e.rang}, this)">
            ${options}
          </select>
          ${isAff ? `<button class="btn btn-sm btn-red" onclick="setAffectation(${e.rang},'')">✕</button>` : ''}
        </div>
      </td>
      <td><div class="td-inner">
        <span class="pill ${isAff?'pill-done':'pill-pending'}">${isAff?'✓ Affecté':'En attente'}</span>
      </div></td>
    </tr>`;
  }).join('');

  el.innerHTML = `<table>
    <thead><tr><th style="width:50px;">Rang</th><th style="width:200px;">Élève</th><th>Poste affecté</th><th style="width:110px;">Statut</th></tr></thead>
    <tbody>${rows}</tbody>
  </table>`;
}

function handleSelectChange(rang, sel) {
  const posteId = sel.value;
  setAffectation(rang, posteId);
}

// ════════════════════════════════════════════════════
//  RENDER — ADMIN ÉLÈVES
// ════════════════════════════════════════════════════
function renderAdminEleves() {
  document.getElementById('eleves-count').textContent = eleves.length;
  const el = document.getElementById('eleves-table');
  if (!el) return;
  if (!eleves.length) { el.innerHTML = '<div class="empty">Aucun élève.</div>'; return; }
  el.innerHTML = `<table><thead><tr><th>Rang</th><th>Nom</th><th></th></tr></thead><tbody>` +
    eleves.map(e => `<tr>
      <td><div class="td-inner"><span style="font-family:'IBM Plex Mono',monospace;font-size:11px;color:var(--text3);">${e.rang}</span></div></td>
      <td><div class="td-inner">${esc(e.nom)}</div></td>
      <td><div class="td-inner"><button class="del-btn" onclick="delEleve(${e.rang})">✕</button></div></td>
    </tr>`).join('') + `</tbody></table>`;
}

// ════════════════════════════════════════════════════
//  RENDER — ADMIN POSTES
// ════════════════════════════════════════════════════
function renderAdminPostes() {
  document.getElementById('postes-count').textContent = postes.length;
  const el = document.getElementById('postes-table');
  if (!el) return;
  if (!postes.length) { el.innerHTML = '<div class="empty">Aucun poste.</div>'; return; }

  // Grouper par nom pour afficher le décompte
  const grouped = {};
  postes.forEach(p => { grouped[p.nom] = (grouped[p.nom]||0)+1; });
  const uniqueNames = [...new Set(postes.map(p=>p.nom))];

  el.innerHTML = `<table><thead><tr><th>#</th><th>Poste</th><th>Exemplaires</th><th></th></tr></thead><tbody>` +
    uniqueNames.map((nom,i) => `<tr>
      <td><div class="td-inner"><span style="font-family:'IBM Plex Mono',monospace;font-size:11px;color:var(--text3);">${i+1}</span></div></td>
      <td><div class="td-inner">${esc(nom)}</div></td>
      <td><div class="td-inner"><span class="badge">${grouped[nom]}</span></div></td>
      <td><div class="td-inner"><button class="del-btn" onclick="delPosteByNom('${esc(nom)}')">✕</button></div></td>
    </tr>`).join('') + `</tbody></table>`;
}

// ════════════════════════════════════════════════════
//  RENDER — RÉSULTATS ADMIN
// ════════════════════════════════════════════════════
function renderResultats() {
  const el = document.getElementById('resultats-table');
  if (!el) return;
  const aff = eleves.filter(e => affectations[e.rang]);
  if (!aff.length) { el.innerHTML = '<div class="empty">Aucune affectation enregistrée.</div>'; return; }
  el.innerHTML = `<table><thead><tr><th>Rang</th><th>Élève</th><th>Poste affecté</th></tr></thead><tbody>` +
    aff.map(e => `<tr>
      <td><div class="td-inner"><span style="font-family:'IBM Plex Mono',monospace;font-size:11px;color:var(--text3);">${e.rang}</span></div></td>
      <td><div class="td-inner">${esc(e.nom)}</div></td>
      <td><div class="td-inner" style="color:var(--gold);font-weight:500;">${esc(nomPoste(affectations[e.rang]))}</div></td>
    </tr>`).join('') + `</tbody></table>`;
}

// ════════════════════════════════════════════════════
//  IMPORT / DELETE
// ════════════════════════════════════════════════════
async function importEleves() {
  const lines = document.getElementById('eleves-bulk').value.trim().split('\n').filter(l=>l.trim());
  const toImport = [];
  for (const line of lines) {
    const parts = line.split(';'); if (parts.length < 2) continue;
    const rang = parseInt(parts[0].trim()), nom = parts.slice(1).join(';').trim();
    if (!rang || !nom) continue;
    toImport.push({rang, nom});
  }
  if (!toImport.length) { setStatus('eleves-status','Format invalide.','er'); return; }
  if (db) {
    const u = {};
    toImport.forEach(e => { u[`${FB_ROOT}/eleves/${e.rang}`] = e; });
    await db.ref().update(u);
  } else {
    toImport.forEach(ne => {
      const i = eleves.findIndex(e=>e.rang===ne.rang);
      if (i>=0) eleves[i]=ne; else eleves.push(ne);
    });
    eleves.sort((a,b)=>a.rang-b.rang);
    LS.set('eleves', eleves);
    refresh();
  }
  document.getElementById('eleves-bulk').value = '';
  setStatus('eleves-status', `${toImport.length} élève(s) importé(s).`, 'ok');
}

async function importPostes() {
  const lines = document.getElementById('postes-bulk').value.trim().split('\n').filter(l=>l.trim());
  const toImport = [];
  const maxOrder = postes.length ? Math.max(...postes.map(p=>p.order||0)) : 0;
  lines.forEach((line, idx) => {
    const nom = line.trim(); if (!nom) return;
    toImport.push({id:'p_'+Date.now()+'_'+Math.random().toString(36).slice(2,6), nom, order: maxOrder+idx+1});
  });
  if (!toImport.length) { setStatus('postes-status','Aucun poste valide.','er'); return; }
  if (db) {
    const u = {}; toImport.forEach(p => { u[`${FB_ROOT}/postes/${p.id}`] = p; });
    await db.ref().update(u);
  } else {
    postes = [...postes, ...toImport].sort((a,b)=>(a.order||0)-(b.order||0));
    LS.set('postes', postes); refresh();
  }
  document.getElementById('postes-bulk').value = '';
  setStatus('postes-status', `${toImport.length} poste(s) importé(s).`, 'ok');
}

async function clearEleves() {
  if (!confirm('Effacer tous les élèves ?')) return;
  if (db) await db.ref(`${FB_ROOT}/eleves`).remove();
  else { eleves=[]; LS.set('eleves',[]); refresh(); }
}
async function clearPostes() {
  if (!confirm('Effacer tous les postes ?')) return;
  if (db) await db.ref(`${FB_ROOT}/postes`).remove();
  else { postes=[]; LS.set('postes',[]); refresh(); }
}
async function delEleve(rang) {
  if (db) await db.ref(`${FB_ROOT}/eleves/${rang}`).remove();
  else { eleves=eleves.filter(e=>e.rang!==rang); LS.set('eleves',eleves); refresh(); }
}
async function delPosteByNom(nom) {
  const toDelete = postes.filter(p=>p.nom===nom);
  if (!confirm(`Supprimer tous les exemplaires de "${nom}" (${toDelete.length}) ?`)) return;
  if (db) {
    const u={};
    toDelete.forEach(p=>{ u[`${FB_ROOT}/postes/${p.id}`]=null; });
    await db.ref().update(u);
  } else {
    postes=postes.filter(p=>p.nom!==nom); LS.set('postes',postes); refresh();
  }
}
async function resetAffectations() {
  if (!confirm('Réinitialiser toutes les affectations ?')) return;
  if (db) await db.ref(`${FB_ROOT}/affectations`).remove();
  else { affectations={}; LS.set('affectations',{}); refresh(); }
}

// ════════════════════════════════════════════════════
//  EXPORT CSV
// ════════════════════════════════════════════════════
function exportCSV() {
  const rows = [['Rang','Élève','Poste affecté']];
  eleves.forEach(e => {
    rows.push([e.rang, e.nom, nomPoste(affectations[e.rang])||'']);
  });
  const csv = rows.map(r=>r.map(v=>`"${String(v).replace(/"/g,'""')}"`).join(',')).join('\n');
  const a = document.createElement('a');
  a.href = 'data:text/csv;charset=utf-8,'+encodeURIComponent('\uFEFF'+csv);
  a.download = 'affectations-amphi-blanc.csv';
  a.click();
}

// ════════════════════════════════════════════════════
//  UTILITAIRES
// ════════════════════════════════════════════════════
function setStatus(id, msg, cls) {
  const el = document.getElementById(id); if (!el) return;
  el.textContent = msg; el.className = 'status-msg '+cls;
  setTimeout(()=>{ el.textContent=''; }, 4000);
}
function esc(s){ return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }

initFirebase();
</script>
</body>
</html>
