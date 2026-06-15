<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GWA Result Analysis</title>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&family=Montserrat:wght@400;600;700;800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --navy:#1a2e5a;--navy2:#243870;--gold:#c9a84c;--gold2:#e8c46a;
  --bg:#f4f6fa;--white:#fff;--border:#e2e8f0;
  --text:#1e293b;--text2:#64748b;--radius:12px;--shadow:0 2px 12px rgba(0,0,0,.08);
  --att:#1565b0;--prog:#6a1b9a;
  --above:#2d7d46;--inline:#1565b0;--below:#b71c1c;
}
body{font-family:"Montserrat",sans-serif;background:var(--bg);color:var(--text);min-height:100vh;font-size:14px}
.ar{font-family:"Tajawal",sans-serif;font-weight:800;font-size:.88em;color:#c62828}
.en{font-family:"Montserrat",sans-serif;font-weight:700}
.bi{display:inline-flex;align-items:baseline;gap:5px}

/* SCREENS */
#entryScreen{position:fixed;inset:0;background:linear-gradient(135deg,#1a2e5a,#243870);display:flex;align-items:center;justify-content:center;z-index:100}
#passScreen{position:fixed;inset:0;background:rgba(0,0,0,.6);display:none;align-items:center;justify-content:center;z-index:200}
#adminScreen{position:fixed;inset:0;background:linear-gradient(135deg,#1a2e5a,#243870);display:none;align-items:center;justify-content:center;z-index:150}
#modalScreen{position:fixed;inset:0;background:rgba(0,0,0,.55);display:none;align-items:flex-start;justify-content:center;padding-top:4vh;z-index:300}

.ecard{background:#fff;border-radius:20px;padding:36px;width:400px;max-width:95vw;text-align:center;position:relative;box-shadow:0 20px 60px rgba(0,0,0,.35)}
.admin-arrow{position:absolute;top:12px;right:12px;border:1.5px solid var(--border);background:transparent;border-radius:8px;padding:5px 10px;cursor:pointer;font-size:11px;color:var(--text2);display:flex;align-items:center;gap:4px;font-family:Montserrat,sans-serif}
.admin-arrow:hover{border-color:var(--navy);color:var(--navy)}
.etitle{font-size:22px;font-weight:800;color:var(--navy);margin-bottom:4px}
.esub{font-size:11px;color:var(--text2);margin-bottom:20px;line-height:1.6}
hr{border:none;border-top:1px solid var(--border);margin:16px 0}
.field{margin-bottom:12px;text-align:left}
.field label{display:block;font-size:12px;font-weight:600;margin-bottom:4px;color:var(--text2)}
.field input,.field select{width:100%;padding:10px 13px;border:1.5px solid var(--border);border-radius:8px;font-size:14px;font-family:Montserrat,sans-serif;outline:none;transition:border .2s}
.field input:focus{border-color:var(--navy)}
.lbtn{width:100%;background:var(--navy);color:#fff;border:none;border-radius:10px;padding:12px;font-size:15px;font-weight:700;cursor:pointer;font-family:Montserrat,sans-serif;margin-top:6px;display:flex;align-items:center;justify-content:center;gap:8px;transition:opacity .2s}
.lbtn:hover{opacity:.9}
.err{color:#c62828;font-size:12px;margin-top:6px;min-height:18px}
.demo-box{background:#eff6ff;border:1px solid #bfdbfe;border-radius:8px;padding:8px 12px;font-size:11px;margin-bottom:14px;text-align:left;font-family:Montserrat,sans-serif}

/* PASS / ADMIN */
.pcard{background:#fff;border-radius:16px;padding:28px;width:320px;text-align:center;box-shadow:0 20px 50px rgba(0,0,0,.3)}
.acard{background:#fff;border-radius:20px;padding:32px;width:480px;max-width:95vw;text-align:center;box-shadow:0 20px 60px rgba(0,0,0,.3)}
.agrid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:20px 0}
.abtn{border:2px solid var(--border);background:var(--bg);border-radius:14px;padding:20px 10px;cursor:pointer;transition:all .2s;font-family:Montserrat,sans-serif}
.abtn:hover{border-color:var(--navy);background:#eef2ff;transform:translateY(-2px)}
.abtn .ai{font-size:36px;color:var(--navy);margin-bottom:8px}
.abtn .al{font-size:13px;font-weight:700;color:var(--navy)}
.abtn .al2{font-size:10px;color:var(--text2);margin-top:3px}

/* MODAL */
.minner{background:#fff;border-radius:16px;padding:24px;width:560px;max-width:95vw;max-height:82vh;overflow-y:auto;box-shadow:0 20px 60px rgba(0,0,0,.3)}
.mtitle{font-size:16px;font-weight:800;color:var(--navy);margin-bottom:16px;display:flex;align-items:center;gap:8px}

/* TOPBAR */
#topbar{background:var(--navy);height:54px;display:none;align-items:center;justify-content:space-between;padding:0 20px;position:sticky;top:0;z-index:50;box-shadow:0 2px 8px rgba(0,0,0,.25)}
.tlogo{font-size:14px;font-weight:800;color:#fff;line-height:1.3}
.tlogo small{display:block;font-size:10px;color:var(--gold2);font-weight:400}
.tright{display:flex;align-items:center;gap:8px}
.tbtn{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.15);color:#fff;border-radius:8px;padding:6px 10px;cursor:pointer;font-size:12px;display:flex;align-items:center;gap:5px;font-family:Montserrat,sans-serif;font-weight:600}
.tbtn:hover{background:rgba(255,255,255,.2)}
.langbtn{background:var(--gold);border:none;color:var(--navy);font-weight:700;border-radius:6px;padding:4px 10px;cursor:pointer;font-size:12px;font-family:Montserrat,sans-serif}
.uavatar{width:32px;height:32px;border-radius:50%;background:var(--gold);color:var(--navy);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:12px;font-family:Montserrat,sans-serif}

/* LAYOUT */
#mainApp{display:none;min-height:calc(100vh - 54px)}
.layout{display:flex;min-height:calc(100vh - 54px)}
.sidebar{width:230px;background:var(--white);border-right:1px solid var(--border);padding:12px 0;flex-shrink:0}
.main{flex:1;padding:20px;overflow-y:auto}

/* SIDEBAR */
.sbsec{padding:6px 16px;font-size:10px;color:var(--text2);font-weight:700;text-transform:uppercase;letter-spacing:.5px;margin-top:10px}
.sbitem{display:flex;align-items:center;gap:10px;padding:10px 16px;cursor:pointer;font-size:13px;color:var(--text);border-left:3px solid transparent;transition:all .15s}
.sbitem:hover{background:var(--bg)}
.sbitem.on-att{background:#eff6ff;color:var(--att);border-left-color:var(--att)}
.sbitem.on-prog{background:#f5f3ff;color:var(--prog);border-left-color:var(--prog)}
.sbitem .sbi-en{font-weight:700;font-size:13px}
.sbitem .sbi-ar{font-size:10px;display:block;margin-top:1px}
.sbitem .sbi-ar.att{color:var(--att);opacity:.8}
.sbitem .sbi-ar.prog{color:var(--prog);opacity:.8}

/* BREADCRUMB */
.bc{display:flex;align-items:center;gap:5px;font-size:12px;color:var(--text2);margin-bottom:14px;flex-wrap:wrap}
.bc span{cursor:pointer;font-weight:600}.bc span:hover{color:var(--navy)}
.bcsep{color:var(--border);cursor:default!important;font-weight:400!important}
.bccur{color:var(--navy)!important;cursor:default!important}

/* PAGE HEADER */
.pghdr{display:flex;align-items:center;justify-content:space-between;margin-bottom:16px}
.pgtitle .en{font-size:20px;font-weight:800;display:block}
.pgtitle .ar{font-size:13px;display:block;margin-top:2px}
.att-color{color:var(--att)}.prog-color{color:var(--prog)}

/* CARDS */
.card{background:var(--white);border:1px solid var(--border);border-radius:var(--radius);padding:16px;box-shadow:var(--shadow);margin-bottom:14px}
.ctitle{font-size:15px;font-weight:800;color:var(--navy);margin-bottom:12px;display:flex;align-items:center;gap:8px}
.pgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(155px,1fr));gap:12px;margin-top:8px}
.icard{background:var(--white);border:2px solid var(--border);border-radius:12px;padding:18px 12px;text-align:center;cursor:pointer;transition:all .2s;position:relative}
.icard:hover{box-shadow:0 4px 16px rgba(0,0,0,.12);transform:translateY(-2px)}
.icard.att-card:hover{border-color:var(--att)}
.icard.prog-card:hover{border-color:var(--prog)}
.icard .ico{font-size:28px;margin-bottom:8px}
.icard .att-card-ico{color:var(--att)}.icard .prog-card-ico{color:var(--prog)}
.icard .ilbl-en{font-size:13px;font-weight:700;color:var(--text)}
.icard .ilbl-ar{font-size:10px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:700;color:var(--text2)}
.icard .ibdg{position:absolute;top:6px;right:6px;background:var(--gold);color:var(--navy);font-size:9px;font-weight:700;padding:2px 5px;border-radius:8px;font-family:Montserrat,sans-serif}
.icard.att-main{border-color:var(--att);background:linear-gradient(135deg,#eff6ff,#fff)}
.icard.prog-main{border-color:var(--prog);background:linear-gradient(135deg,#f5f3ff,#fff)}

/* TABLE */
.tbl{width:100%;border-collapse:collapse;font-size:12px}
.tbl th{background:var(--navy);color:#fff;padding:8px 8px;text-align:center;font-size:11px;font-weight:700}
.tbl th:first-child{text-align:left}
.tbl td{padding:7px 8px;text-align:center;border-bottom:1px solid var(--border)}
.tbl tr:last-child td{border-bottom:none}
.tbl tr:hover td{background:#f8faff}
.tbl td:first-child{text-align:left;font-weight:600;color:var(--navy)}
.ni{width:62px;padding:4px 4px;border:1.5px solid var(--border);border-radius:6px;text-align:center;font-family:Montserrat,sans-serif;font-size:12px;outline:none;transition:all .2s}
.ni:focus{border-color:var(--att)}
.ni.ch{color:var(--att);font-weight:700;border-color:var(--att);background:#eff6ff}
.jb{display:inline-block;padding:3px 9px;border-radius:12px;font-size:11px;font-weight:700;font-family:Montserrat,sans-serif}
.j-weak{background:#ffebee;color:#b71c1c}.j-acceptable{background:#fff3e0;color:#e65100}
.j-good{background:#e3f2fd;color:#1565b0}.j-verygood{background:#f3e5f5;color:#6a1b9a}
.j-outstanding{background:#e8f5e9;color:#1b5e20}.j-na{background:var(--bg);color:var(--text2)}
.above-row td{background:#f0fdf4}.inline-row td{background:#eff6ff}.below-row td{background:#fff5f5}

/* BUTTONS */
.btn{display:inline-flex;align-items:center;gap:5px;padding:7px 13px;border-radius:8px;font-size:12px;font-weight:700;cursor:pointer;border:none;font-family:Montserrat,sans-serif;transition:all .2s}
.btn-p{background:var(--navy);color:#fff}.btn-att{background:var(--att);color:#fff}
.btn-prog{background:var(--prog);color:#fff}.btn-s{background:#2d7d46;color:#fff}
.btn-g{background:var(--gold);color:var(--navy)}.btn-d{background:#c62828;color:#fff}
.btn-o{background:transparent;color:var(--navy);border:1.5px solid var(--navy)}.btn-sm{padding:4px 9px;font-size:11px}
.arow{display:flex;gap:7px;flex-wrap:wrap;margin-top:12px}

/* MISC */
.cwrap{margin-top:14px;background:var(--bg);border-radius:10px;padding:12px}
.ctitle2{font-size:12px;font-weight:700;color:var(--navy);margin-bottom:8px;text-align:center}
.sgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:14px}
.sc{background:var(--bg);border-radius:10px;padding:10px;text-align:center}
.sc .sv{font-size:20px;font-weight:800;font-family:Montserrat,sans-serif}
.adrow{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border)}
.adrow:last-of-type{border-bottom:none}
.rbadge{padding:2px 8px;border-radius:10px;font-size:11px;font-weight:700;font-family:Montserrat,sans-serif}
.r-editor{background:#e3f2fd;color:#1565b0}.r-viewer{background:#f3e5f5;color:#6a1b9a}
.notify{position:fixed;bottom:18px;right:18px;color:#fff;padding:11px 16px;border-radius:10px;font-size:13px;font-weight:600;z-index:999;display:none;font-family:Montserrat,sans-serif}
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:400;display:none;align-items:center;justify-content:center}
.modal-overlay.on{display:flex}
.modal{background:#fff;border-radius:14px;padding:24px;width:400px;max-width:95vw}
.fbtn{display:inline-flex;align-items:center;gap:5px;padding:6px 12px;border-radius:16px;font-size:12px;font-weight:700;cursor:pointer;border:1.5px solid var(--border);background:#fff;transition:all .2s;font-family:Montserrat,sans-serif}
.fbtn:hover,.fbtn.on{border-color:var(--navy);background:var(--navy);color:#fff}
.twrap{position:relative;display:inline-block;width:42px;height:22px;flex-shrink:0}
.twrap input{opacity:0;width:0;height:0}
.tslider{position:absolute;cursor:pointer;inset:0;background:#ccc;border-radius:22px;transition:.3s}
.tslider:before{position:absolute;content:"";height:16px;width:16px;left:3px;bottom:3px;background:#fff;border-radius:50%;transition:.3s}
.twrap input:checked+.tslider{background:var(--navy)}
.twrap input:checked+.tslider:before{transform:translateX(20px)}
.gcblbl{display:inline-flex;align-items:center;gap:4px;cursor:pointer;padding:3px 8px;border:1.5px solid var(--border);border-radius:6px;font-size:11px;background:#fff;margin:2px;transition:all .2s;font-family:Montserrat,sans-serif;font-weight:600}
.gcblbl.on{border-color:var(--navy);background:#eef2ff}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.7}}
select{font-family:Montserrat,sans-serif;font-size:13px}
@media print{#topbar,.sidebar,.arow,.bc{display:none!important}.main{max-height:none}}
</style>
</head>
<body>

<!-- ENTRY -->
<div id="entryScreen">
  <div class="ecard">
    <button class="admin-arrow" onclick="showPass()">
      <i class="ti ti-settings"></i>
      <span style="font-family:Montserrat,sans-serif;font-weight:800;color:var(--navy)">Admin</span>
      <span style="font-family:Tajawal,sans-serif;font-weight:800;color:#c62828;font-size:12px"> الإدارة</span>
    </button>
    <div class="etitle">GEMS World Academy</div>
    <div class="esub">
      <strong style="color:#1a2e5a">Result Analysis Platform</strong><br>
      <span class="ar" style="font-size:12px">منصة تحليل النتائج</span>
    </div>
    <div style="margin:10px auto 16px;width:80px;height:80px">
      <svg viewBox="0 0 80 80" xmlns="http://www.w3.org/2000/svg">
        <rect width="80" height="80" rx="16" fill="#1a2e5a"/>
        <rect x="8" y="44" width="10" height="28" rx="3" fill="#c9a84c"/>
        <rect x="22" y="32" width="10" height="40" rx="3" fill="#4a90d9"/>
        <rect x="36" y="20" width="10" height="52" rx="3" fill="#2d7d46"/>
        <rect x="50" y="34" width="10" height="38" rx="3" fill="#7e57c2"/>
        <rect x="64" y="26" width="10" height="46" rx="3" fill="#e65100"/>
        <polyline points="13,40 27,28 41,16 55,30 69,22"
          fill="none" stroke="#e8c46a" stroke-width="2.5"
          stroke-linecap="round" stroke-linejoin="round"/>
        <circle cx="13" cy="40" r="3" fill="#e8c46a"/>
        <circle cx="27" cy="28" r="3" fill="#e8c46a"/>
        <circle cx="41" cy="16" r="3" fill="#e8c46a"/>
        <circle cx="55" cy="30" r="3" fill="#e8c46a"/>
        <circle cx="69" cy="22" r="3" fill="#e8c46a"/>
      </svg>
    </div>
    <div class="demo-box">
      <strong style="color:#1e40af">Demo:</strong>
      sara@gwa / Sara@123
    </div>
    <div class="field">
      <label>Username</label>
      <input type="text" id="loginUser" value="sara@gwa" placeholder="username@gwa">
    </div>
    <div class="field">
      <label>Password</label>
      <input type="password" id="loginPass" value="Sara@123" placeholder="password" onkeydown="if(event.key==='Enter')doLogin()">
    </div>
    <button class="lbtn" onclick="doLogin()">
      <i class="ti ti-login"></i> Sign In
    </button>
    <div class="err" id="loginErr"></div>
  </div>
</div>

<!-- PASS SCREEN -->
<div id="passScreen" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,.6);align-items:center;justify-content:center;z-index:200">
  <div class="pcard">
    <i class="ti ti-lock" style="font-size:40px;color:var(--navy);display:block;margin-bottom:10px"></i>
    <div style="font-size:16px;font-weight:800;color:var(--navy);margin-bottom:4px">Admin Access</div>
    <div class="ar" style="font-size:12px;color:var(--text2);margin-bottom:14px">دخول الإدارة</div>
    <input type="password" id="adminPass" placeholder="Admin password"
      style="width:100%;padding:9px 12px;border:1.5px solid var(--border);border-radius:8px;font-family:Montserrat,sans-serif;outline:none;margin-bottom:8px"
      onkeydown="if(event.key==='Enter')checkPass()">
    <div class="err" id="passErr"></div>
    <div style="display:flex;gap:8px;justify-content:center;margin-top:10px">
      <button class="btn btn-o btn-sm" onclick="hidePass()">Cancel</button>
      <button class="btn btn-p" onclick="checkPass()">Enter</button>
    </div>
  </div>
</div>

<!-- ADMIN SCREEN -->
<div id="adminScreen" style="display:none;position:fixed;inset:0;background:linear-gradient(135deg,#1a2e5a,#243870);align-items:center;justify-content:center;z-index:150">
  <div class="acard">
    <div style="margin-bottom:6px;display:flex;align-items:center;justify-content:center;gap:10px">
      <span style="font-size:20px;font-weight:800;color:var(--navy)">Admin Panel</span>
      <span style="font-size:16px;font-weight:800;color:#c62828;font-family:Tajawal,sans-serif">لوحة الإدارة</span>
    </div>
    <div style="font-size:11px;color:var(--text2);margin-bottom:4px;font-family:Montserrat,sans-serif">GEMS World Academy</div>
    <div class="agrid">
      <div class="abtn" onclick="openMod('users')">
        <div class="ai"><i class="ti ti-user-plus"></i></div>
        <div class="al">Create Users</div>
        <div class="al2 ar">تخليق مستخدمين</div>
      </div>
      <div class="abtn" onclick="openMod('subjects')">
        <div class="ai"><i class="ti ti-books"></i></div>
        <div class="al">Create Subjects</div>
        <div class="al2 ar">تخليق مواد</div>
      </div>
      <div class="abtn" onclick="openMod('years')">
        <div class="ai"><i class="ti ti-calendar-plus"></i></div>
        <div class="al">Create Years</div>
        <div class="al2 ar">تخليق سنوات</div>
      </div>
    </div>
    <button class="btn btn-o" onclick="closeAdmin()">
      <i class="ti ti-arrow-left"></i> Back
    </button>
  </div>
</div>

<!-- MODAL -->
<div id="modalScreen" style="display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);align-items:flex-start;justify-content:center;padding-top:4vh;z-index:300">
  <div class="minner">
    <div class="mtitle" id="modTitle"></div>
    <div id="modBody"></div>
    <div style="margin-top:14px;border-top:1px solid var(--border);padding-top:12px">
      <button class="btn btn-o btn-sm" onclick="closeMod()"><i class="ti ti-x"></i> Close</button>
    </div>
  </div>
</div>

<!-- TOPBAR -->
<div id="topbar">
  <div class="tlogo">GEMS World Academy
    <small>Result Analysis Platform &nbsp;|&nbsp; <span class="ar" style="font-size:10px">منصة تحليل النتائج</span></small>
  </div>
  <div class="tright">
    <button class="langbtn" onclick="toggleLang()">AR / EN</button>
    <div style="display:flex;align-items:center;gap:8px">
      <div style="text-align:right">
        <div style="font-size:12px;font-weight:700;color:#fff" id="topName"></div>
        <div style="font-size:10px;color:var(--gold2)" id="topRole"></div>
      </div>
      <div class="uavatar" id="topAv"></div>
    </div>
    <button class="tbtn" onclick="doLogout()"><i class="ti ti-logout"></i> <span id="logoutLbl">Sign Out</span></button>
  </div>
</div>

<!-- APP -->
<div id="mainApp">
  <div class="layout">
    <div class="sidebar">
      <div class="sbsec">Analysis Sections</div>
      <div class="sbitem" id="sb-att" onclick="goSection('att')">
        <i class="ti ti-chart-bar" style="font-size:18px;color:var(--att)"></i>
        <div>
          <span class="sbi-en att-color" style="font-weight:800">Attainment</span>
          <span style="font-size:10px;display:block;margin-top:1px;color:#c62828;font-family:Tajawal,sans-serif;font-weight:800">التحصيل الدراسي</span>
        </div>
      </div>
      <div class="sbitem" id="sb-prog" onclick="goSection('prog')">
        <i class="ti ti-trending-up" style="font-size:18px;color:var(--prog)"></i>
        <div>
          <span class="sbi-en prog-color" style="font-weight:800">Progress</span>
          <span style="font-size:10px;display:block;margin-top:1px;color:#c62828;font-family:Tajawal,sans-serif;font-weight:800">التقدم الدراسي</span>
        </div>
      </div>
    </div>
    <div class="main" id="mainContent"></div>
  </div>
</div>

<!-- UNSAVED -->
<div class="modal-overlay" id="unsavedMod">
  <div class="modal">
    <div style="font-size:15px;font-weight:700;color:#b71c1c;margin-bottom:10px;display:flex;align-items:center;gap:8px">
      <i class="ti ti-alert-triangle"></i> <span id="unsavedMsg"></span>
    </div>
    <p style="font-size:12px;color:var(--text2);margin-bottom:6px" id="unsavedSub"></p>
    <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:16px">
      <button class="btn btn-o btn-sm" onclick="closeUnsaved()">Cancel</button>
      <button class="btn btn-d btn-sm" onclick="doExit()">Exit without saving</button>
      <button class="btn btn-s btn-sm" onclick="saveExit()">Save &amp; Exit</button>
    </div>
  </div>
</div>

<!-- SHARE -->
<div class="modal-overlay" id="shareMod">
  <div class="modal">
    <div class="ctitle"><i class="ti ti-share"></i> Share Data</div>
    <div class="field"><label>Email Address</label>
      <input type="email" id="shareEmail" placeholder="example@school.com"></div>
    <div style="display:flex;gap:14px;margin-top:6px">
      <label style="display:flex;align-items:center;gap:5px;font-size:12px;font-weight:600;cursor:pointer">
        <input type="radio" name="sfmt" value="pdf" checked> PDF</label>
      <label style="display:flex;align-items:center;gap:5px;font-size:12px;font-weight:600;cursor:pointer">
        <input type="radio" name="sfmt" value="excel"> Excel</label>
    </div>
    <div style="display:flex;gap:8px;justify-content:flex-end;margin-top:16px">
      <button class="btn btn-o btn-sm" onclick="closeShare()">Cancel</button>
      <button class="btn btn-p btn-sm" onclick="doShare()"><i class="ti ti-send"></i> Send</button>
    </div>
  </div>
</div>

<div class="notify" id="notify"></div>

<script>
var ADMIN_PASS = 'Gems@2050';
var USERS = [
  {u:'sara@gwa',    p:'Sara@123',  role:'editor', name:'Sara Ahmed',    email:'sara@Gwadatabank'},
  {u:'viewer@gwa',  p:'View@123',  role:'viewer', name:'Viewer User',   email:'viewer@Gwadatabank'},
  {u:'teacher@gwa', p:'Teacher@1', role:'editor', name:'Ahmed Teacher', email:'teacher@Gwadatabank'}
];
var ALL_SUBJECTS_40 = [
  {id:'s01',en:'Arabic For Arabs',           ar:'اللغة العربية كلغة أولى',     icon:'ti-a-b',   active:true},
  {id:'s02',en:'Arabic For Non-Arabs',        ar:'العربية للناطقين بغيرها', icon:'ti-language',active:true},
  {id:'s03',en:'Islamic Education',           ar:'التربية الإسلامية',    icon:'ti-moon',  active:true},
  {id:'s04',en:'Social Studies For Arabs',    ar:'الاجتماعيات',           icon:'ti-world',  active:true},
  {id:'s05',en:'Subject 5',ar:'مادة 5', icon:'ti-book',active:false},
  {id:'s06',en:'Subject 6',ar:'مادة 6', icon:'ti-book',active:false},
  {id:'s07',en:'Subject 7',ar:'مادة 7', icon:'ti-book',active:false},
  {id:'s08',en:'Subject 8',ar:'مادة 8', icon:'ti-book',active:false},
  {id:'s09',en:'Subject 9',ar:'مادة 9', icon:'ti-book',active:false},
  {id:'s10',en:'Subject 10',ar:'مادة 10',icon:'ti-book',active:false},
  {id:'s11',en:'Subject 11',ar:'مادة 11',icon:'ti-book',active:false},
  {id:'s12',en:'Subject 12',ar:'مادة 12',icon:'ti-book',active:false},
  {id:'s13',en:'Subject 13',ar:'مادة 13',icon:'ti-book',active:false},
  {id:'s14',en:'Subject 14',ar:'مادة 14',icon:'ti-book',active:false},
  {id:'s15',en:'Subject 15',ar:'مادة 15',icon:'ti-book',active:false},
  {id:'s16',en:'Subject 16',ar:'مادة 16',icon:'ti-book',active:false},
  {id:'s17',en:'Subject 17',ar:'مادة 17',icon:'ti-book',active:false},
  {id:'s18',en:'Subject 18',ar:'مادة 18',icon:'ti-book',active:false},
  {id:'s19',en:'Subject 19',ar:'مادة 19',icon:'ti-book',active:false},
  {id:'s20',en:'Subject 20',ar:'مادة 20',icon:'ti-book',active:false},
  {id:'s21',en:'Subject 21',ar:'مادة 21',icon:'ti-book',active:false},
  {id:'s22',en:'Subject 22',ar:'مادة 22',icon:'ti-book',active:false},
  {id:'s23',en:'Subject 23',ar:'مادة 23',icon:'ti-book',active:false},
  {id:'s24',en:'Subject 24',ar:'مادة 24',icon:'ti-book',active:false},
  {id:'s25',en:'Subject 25',ar:'مادة 25',icon:'ti-book',active:false},
  {id:'s26',en:'Subject 26',ar:'مادة 26',icon:'ti-book',active:false},
  {id:'s27',en:'Subject 27',ar:'مادة 27',icon:'ti-book',active:false},
  {id:'s28',en:'Subject 28',ar:'مادة 28',icon:'ti-book',active:false},
  {id:'s29',en:'Subject 29',ar:'مادة 29',icon:'ti-book',active:false},
  {id:'s30',en:'Subject 30',ar:'مادة 30',icon:'ti-book',active:false},
  {id:'s31',en:'Subject 31',ar:'مادة 31',icon:'ti-book',active:false},
  {id:'s32',en:'Subject 32',ar:'مادة 32',icon:'ti-book',active:false},
  {id:'s33',en:'Subject 33',ar:'مادة 33',icon:'ti-book',active:false},
  {id:'s34',en:'Subject 34',ar:'مادة 34',icon:'ti-book',active:false},
  {id:'s35',en:'Subject 35',ar:'مادة 35',icon:'ti-book',active:false},
  {id:'s36',en:'Subject 36',ar:'مادة 36',icon:'ti-book',active:false},
  {id:'s37',en:'Subject 37',ar:'مادة 37',icon:'ti-book',active:false},
  {id:'s38',en:'Subject 38',ar:'مادة 38',icon:'ti-book',active:false},
  {id:'s39',en:'Subject 39',ar:'مادة 39',icon:'ti-book',active:false},
  {id:'s40',en:'Subject 40',ar:'مادة 40',icon:'ti-book',active:false}
];

var SUBJECTS = ALL_SUBJECTS_40.filter(function(s){return s.active;});
var ALL_POSSIBLE_YEARS = (function(){
  var yrs=[];
  for(var y=2021;y<=2198;y++){
    var label=y+'-'+(y+1);
    yrs.push({id:String(y)+String(y+1),label:label,code:'AY'+String(y+1).slice(2)+String(y+2).slice(2)});
  }
  return yrs;
})();

var ACTIVE_YEAR_IDS = ['20232024','20242025','20252026'];
var YEARS = ALL_POSSIBLE_YEARS.filter(function(y){return ACTIVE_YEAR_IDS.indexOf(y.id)>=0;});

var GRADES = [
  {id:'kg1', en:'KG1',     ar:'KG1 \u0631\u0648\u0636\u0629',    g:'KG'},
  {id:'kg2', en:'KG2',     ar:'KG2 \u0631\u0648\u0636\u0629',    g:'KG'},
  {id:'g1',  en:'Grade 1', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u0623\u0648\u0644',  g:'PYP'},
  {id:'g2',  en:'Grade 2', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u062b\u0627\u0646\u064a', g:'PYP'},
  {id:'g3',  en:'Grade 3', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u062b\u0627\u0644\u062b', g:'PYP'},
  {id:'g4',  en:'Grade 4', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u0631\u0627\u0628\u0639', g:'PYP'},
  {id:'g5',  en:'Grade 5', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u062e\u0627\u0645\u0633',g:'PYP'},
  {id:'g6',  en:'Grade 6', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u0633\u0627\u062f\u0633',g:'MYP'},
  {id:'g7',  en:'Grade 7', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u0633\u0627\u0628\u0639',g:'MYP'},
  {id:'g8',  en:'Grade 8', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u062b\u0627\u0645\u0646',g:'MYP'},
  {id:'g9',  en:'Grade 9', ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u062a\u0627\u0633\u0639',g:'MYP'},
  {id:'g10', en:'Grade 10',ar:'\u0627\u0644\u0635\u0641 \u0627\u0644\u0639\u0627\u0634\u0631',g:'MYP'},
  {id:'g11', en:'Grade 11',ar:'\u0627\u0644\u062d\u0627\u062f\u064a \u0639\u0634\u0631', g:'DP'},
  {id:'g12', en:'Grade 12',ar:'\u0627\u0644\u062b\u0627\u0646\u064a \u0639\u0634\u0631', g:'DP'}
];

// Separate DBs for Attainment and Progress
var ATT_DB = {};
var PROG_DB = {};

function seedDB(db){
  SUBJECTS.forEach(function(s){
    db[s.id]={};
    YEARS.forEach(function(y){
      db[s.id][y.id]={};
      ['t1','t2','t3'].forEach(function(tm){
        db[s.id][y.id][tm]={};
        GRADES.forEach(function(g){
          var tot=Math.floor(Math.random()*30)+20, m=Math.floor(tot*.48);
          var ab=Math.floor(Math.random()*55)+20, il=Math.floor(Math.random()*(100-ab))+10, bl=Math.max(0,100-ab-il);
          db[s.id][y.id][tm][g.id]={
            st:{tot:tot,m:m,f:tot-m,gt:Math.floor(tot*.1),sod:Math.floor(tot*.05),em:Math.floor(tot*.15)},
            j:{ab:ab,il:il,bl:bl,abm:0,abf:0,abgt:0,absod:0,abem:0,ilm:0,ilf:0,ilgt:0,ilsod:0,ilem:0,blm:0,blf:0,blgt:0,blsod:0,blem:0},
            saved:false
          };
        });
      });
    });
  });
}
seedDB(ATT_DB);
seedDB(PROG_DB);

var lang='en', cu=null, section='att';
var sel={s:null,y:null,t:null};
var cp='home';
var unsaved={}, charts={}, unsavedCb=null, shareGid=null;
var activeFilt='all';

function el(id){return document.getElementById(id);}
function notify(msg,type){
  var n=el('notify');n.textContent=msg;n.style.display='block';
  n.style.background=type==='ok'?'#2d7d46':type==='err'?'#c62828':'#1565b0';
  setTimeout(function(){n.style.display='none';},3000);
}
function show(id){el(id).style.display='flex';}
function hide(id){el(id).style.display='none';}
function DB(){return section==='att'?ATT_DB:PROG_DB;}
function secColor(){return section==='att'?'var(--att)':'var(--prog)';}
function secClass(){return section==='att'?'att-color':'prog-color';}

// ── ADMIN ──
function showPass(){el('adminPass').value='';el('passErr').textContent='';show('passScreen');setTimeout(function(){el('adminPass').focus();},100);}
function hidePass(){hide('passScreen');}
function checkPass(){
  if(el('adminPass').value===ADMIN_PASS){hidePass();hide('entryScreen');show('adminScreen');}
  else{el('passErr').textContent='Incorrect password';}
}
function closeAdmin(){hide('adminScreen');show('entryScreen');}


// ── ADMIN MODAL DISPATCHER ──
function openMod(type){
  var t=el('modTitle'), b=el('modBody');
  if(type==='users'){
    t.innerHTML='<i class="ti ti-user-plus"></i> <strong>Create Users</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:13px">\u062a\u062e\u0644\u064a\u0642 \u0645\u0633\u062a\u062e\u062f\u0645\u064a\u0646</span>';
    b.innerHTML=buildUsers();
  } else if(type==='subjects'){
    t.innerHTML='<i class="ti ti-books"></i> <strong>Manage Subjects</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:13px">\u0625\u062f\u0627\u0631\u0629 \u0627\u0644\u0645\u0648\u0627\u062f</span>';
    b.innerHTML=buildSubjects();
  } else if(type==='years'){
    t.innerHTML='<i class="ti ti-calendar-plus"></i> <strong>Manage Academic Years</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:13px">\u0625\u062f\u0627\u0631\u0629 \u0627\u0644\u0633\u0646\u0648\u0627\u062a</span>';
    b.innerHTML=buildYears();
  }
  show('modalScreen');
}
function closeMod(){hide('modalScreen');}

// ── USERS ──
function buildUsers(){
  var rows='';
  USERS.forEach(function(u){
    var ini=u.name.split(' ').map(function(n){return n[0];}).join('').slice(0,2).toUpperCase();
    rows+='<div class="adrow">'
      +'<div style="width:36px;height:36px;border-radius:50%;background:#eef2ff;display:flex;align-items:center;justify-content:center;font-weight:800;color:var(--navy);font-size:13px">'+ini+'</div>'
      +'<div style="flex:1"><div style="font-weight:700">'+u.name+'</div>'
      +'<div style="font-size:11px;color:var(--text2)">'+u.u+'</div></div>'
      +'<span class="rbadge r-'+u.role+'">'+u.role+'</span>'
      +'<button class="btn btn-d btn-sm" data-uid="'+u.u+'" onclick="delUser(this)"><i class="ti ti-trash"></i></button>'
      +'</div>';
  });
  return '<div style="max-height:180px;overflow-y:auto;margin-bottom:14px">'+rows+'</div>'
    +'<div style="border-top:1px solid var(--border);padding-top:12px">'
    +'<div style="font-weight:800;margin-bottom:10px">Add New User <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:12px">\u0625\u0636\u0627\u0641\u0629 \u0645\u0633\u062a\u062e\u062f\u0645</span></div>'
    +'<div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">'
    +'<div class="field" style="margin:0"><label>Full Name</label><input type="text" id="nu-name" placeholder="Ahmed Ali"></div>'
    +'<div class="field" style="margin:0"><label>Username</label><input type="text" id="nu-user" placeholder="ahmed@gwa"></div>'
    +'<div class="field" style="margin:0"><label>Password</label><input type="password" id="nu-pass" placeholder="Pass@123"></div>'
    +'<div class="field" style="margin:0"><label>Role</label>'
    +'<select id="nu-role" style="width:100%;padding:9px;border:1.5px solid var(--border);border-radius:8px">'
    +'<option value="editor">Editor</option><option value="viewer">Viewer</option></select></div>'
    +'</div>'
    +'<button class="btn btn-p" style="width:100%;margin-top:10px" onclick="saveUser()">'
    +'<i class="ti ti-user-check"></i> Create User</button></div>';
}
function delUser(btn){
  if(!confirm('Delete this user?'))return;
  var uid=btn.getAttribute('data-uid');
  USERS=USERS.filter(function(u){return u.u!==uid;});
  notify('User deleted','ok'); openMod('users');
}
function saveUser(){
  var name=el('nu-name').value.trim(), u=el('nu-user').value.trim();
  var p=el('nu-pass').value.trim(), role=el('nu-role').value;
  if(!name||!u||!p){notify('Fill all fields','err');return;}
  if(USERS.find(function(x){return x.u===u;})){notify('Username exists','err');return;}
  USERS.push({u:u,p:p,role:role,name:name,email:u+'@Gwadatabank'});
  notify('Created: '+name,'ok'); openMod('users');
}

// ── SUBJECTS (40 subjects with toggle + edit) ──
function buildSubjects(){
  var rows='';
  ALL_SUBJECTS_40.forEach(function(s,i){
    var num=i+1;
    rows+='<div class="adrow" style="padding:8px 0">'
      +'<div style="width:28px;height:28px;border-radius:6px;background:'+(s.active?'#dcfce7':'#f1f5f9')+';display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;color:'+(s.active?'#166534':'#94a3b8')+'">'+num+'</div>'
      +'<div style="flex:1;min-width:0">'
      +'<div style="font-weight:700;font-size:13px">'+s.en+'</div>'
      +'<div style="font-size:11px;color:#c62828;font-family:Tajawal,sans-serif;font-weight:800">'+s.ar+'</div>'
      +'</div>'
      +'<label style="display:flex;align-items:center;gap:5px;cursor:pointer;font-size:11px;font-weight:700;margin-left:8px">'
      +'<input type="checkbox" '+(s.active?'checked':'')+' data-sid="'+s.id+'" onchange="toggleSubActive(this)">'
      +(s.active?'<span style="color:#166534">Active</span>':'<span style="color:#94a3b8">Inactive</span>')
      +'</label>'
      +'<button class="btn btn-o btn-sm" data-sid="'+s.id+'" onclick="editSubject(this)" style="margin-left:4px"><i class="ti ti-edit"></i></button>'
      +'</div>';
  });
  return '<div style="font-size:11px;color:var(--text2);margin-bottom:8px">Showing '+ALL_SUBJECTS_40.filter(function(s){return s.active;}).length+' active of 40 subjects</div>'
    +'<div style="max-height:420px;overflow-y:auto">'+rows+'</div>';
}
function toggleSubActive(cb){
  var sid=cb.getAttribute('data-sid');
  var s=ALL_SUBJECTS_40.find(function(x){return x.id===sid;});
  if(s){
    s.active=cb.checked;
    // Re-seed DB if newly activated
    if(s.active){
      if(!ATT_DB[s.id])ATT_DB[s.id]={};
      if(!PROG_DB[s.id])PROG_DB[s.id]={};
      YEARS.forEach(function(y){
        if(!ATT_DB[s.id][y.id])ATT_DB[s.id][y.id]={};
        if(!PROG_DB[s.id][y.id])PROG_DB[s.id][y.id]={};
        ['t1','t2','t3'].forEach(function(tm){
          if(!ATT_DB[s.id][y.id][tm])ATT_DB[s.id][y.id][tm]={};
          if(!PROG_DB[s.id][y.id][tm])PROG_DB[s.id][y.id][tm]={};
        });
      });
    }
    SUBJECTS = ALL_SUBJECTS_40.filter(function(x){return x.active;});
  }
  notify(s.active?'Subject activated':'Subject deactivated','ok');
  openMod('subjects');
}
function editSubject(btn){
  var sid=btn.getAttribute('data-sid');
  var s=ALL_SUBJECTS_40.find(function(x){return x.id===sid;});
  if(!s)return;
  var newEn=prompt('English name:',s.en);
  if(newEn===null)return;
  var newAr=prompt('\u0627\u0644\u0627\u0633\u0645 \u0628\u0627\u0644\u0639\u0631\u0628\u064a\u0629:',s.ar);
  if(newAr===null)return;
  if(newEn.trim())s.en=newEn.trim();
  if(newAr.trim())s.ar=newAr.trim();
  SUBJECTS=ALL_SUBJECTS_40.filter(function(x){return x.active;});
  notify('Updated: '+s.en,'ok');
  openMod('subjects');
}

// ── YEARS (select 3 active from full list) ──
function buildYears(){
  var activeIds=YEARS.map(function(y){return y.id;});
  // Show years in ranges - show 2020s and nearby
  var display=ALL_POSSIBLE_YEARS.filter(function(y){
    var yr=parseInt(y.id.slice(0,4));
    return yr>=2021 && yr<=2035;
  });
  var rows='';
  display.forEach(function(y){
    var isActive=activeIds.indexOf(y.id)>=0;
    rows+='<div class="adrow" style="padding:7px 0">'
      +'<i class="ti ti-calendar" style="font-size:18px;color:'+(isActive?'var(--navy)':'#94a3b8')+'"></i>'
      +'<div style="flex:1"><div style="font-weight:700;font-family:Montserrat,sans-serif;font-size:13px">'+y.label+'</div>'
      +'<div style="font-size:10px;color:var(--text2);font-family:Montserrat,sans-serif">'+y.code+'</div></div>'
      +'<label style="display:flex;align-items:center;gap:5px;cursor:pointer;font-size:11px;font-weight:700">'
      +'<input type="checkbox" '+(isActive?'checked':'')+' data-yid="'+y.id+'" onchange="toggleYear(this)">'
      +(isActive?'<span style="color:#166534">Active</span>':'<span style="color:#94a3b8">Inactive</span>')
      +'</label>'
      +'</div>';
  });
  var activeCount=YEARS.length;
  return '<div style="font-size:11px;margin-bottom:10px;padding:8px;border-radius:8px;background:'+(activeCount===3?'#dcfce7':'#fef9c3')+'">'
    +'<strong>'+(activeCount===3?'✓ 3 active years selected':'⚠ Select exactly 3 active years (currently '+activeCount+')')+'</strong></div>'
    +'<div style="max-height:380px;overflow-y:auto">'+rows+'</div>';
}
function toggleYear(cb){
  var yid=cb.getAttribute('data-yid');
  var activeIds=YEARS.map(function(y){return y.id;});
  if(cb.checked){
    if(activeIds.length>=3){
      cb.checked=false;
      notify('Maximum 3 active years allowed','err');
      return;
    }
    var yr=ALL_POSSIBLE_YEARS.find(function(y){return y.id===yid;});
    if(yr){
      YEARS.push(yr);
      YEARS.sort(function(a,b){return a.id.localeCompare(b.id);});
      // Seed DB for this year
      SUBJECTS.forEach(function(s){
        if(!ATT_DB[s.id])ATT_DB[s.id]={};
        if(!PROG_DB[s.id])PROG_DB[s.id]={};
        ATT_DB[s.id][yid]={};PROG_DB[s.id][yid]={};
        ['t1','t2','t3'].forEach(function(tm){ATT_DB[s.id][yid][tm]={};PROG_DB[s.id][yid][tm]={};});
      });
      notify('Year activated: '+yr.label,'ok');
    }
  } else {
    YEARS=YEARS.filter(function(y){return y.id!==yid;});
    notify('Year deactivated','ok');
  }
  openMod('years');
}

// ── REPORT HELPER ──
function goReportBtn(el2){
  var page=el2.getAttribute('data-rp');
  if(!sel.t)sel.t='t1';
  cp=page;render();
}
function goReport(page){
  if(!sel.t)sel.t='t1';
  cp=page;render();
}


// ── AUTH ──
function doLogin(){
  var u=el('loginUser').value.trim(),p=el('loginPass').value.trim();
  var user=USERS.find(function(x){return x.u===u&&x.p===p;});
  if(!user){el('loginErr').textContent='Invalid username or password';return;}
  cu=user;
  hide('entryScreen');
  el('topbar').style.display='flex';
  el('mainApp').style.display='block';
  el('topName').textContent=user.name;
  el('topRole').textContent=user.role;
  el('topAv').textContent=user.name.split(' ').map(function(n){return n[0];}).join('').slice(0,2).toUpperCase();
  goSection('att');
}
function doLogout(){
  if(Object.keys(unsaved).length){
    showUnsaved(Object.values(unsaved)[0].lbl,function(){
      cu=null;unsaved={};
      show('entryScreen');el('topbar').style.display='none';el('mainApp').style.display='none';
    });return;
  }
  cu=null;show('entryScreen');el('topbar').style.display='none';el('mainApp').style.display='none';
}

// ── LANG ──
function toggleLang(){
  lang=lang==='en'?'ar':'en';
  document.documentElement.dir=lang==='ar'?'rtl':'ltr';
  document.documentElement.lang=lang;
  el('logoutLbl').textContent=lang==='ar'?'\u062e\u0631\u0648\u062c':'Sign Out';
  render();
}

// ── SECTION NAV ──
function goSection(sec){
  if(Object.keys(unsaved).length){
    showUnsaved(Object.values(unsaved)[0].lbl,function(){_goSection(sec);});return;
  }
  _goSection(sec);
}
function _goSection(sec){
  section=sec;
  sel={s:null,y:null,t:null};cp='home';
  document.querySelectorAll('.sbitem').forEach(function(i){i.classList.remove('on-att','on-prog');});
  el('sb-'+sec).classList.add('on-'+sec);
  render();
}

function render(){
  charts={};
  var c=el('mainContent');
  if(cp==='home')        c.innerHTML=pgHome();
  else if(cp==='years')  c.innerHTML=pgYears();
  else if(cp==='terms')  c.innerHTML=pgTerms();
  else if(cp==='data')   c.innerHTML=pgData();
  else if(cp==='compare')c.innerHTML=pgCompare();
  setTimeout(attachCharts,150);
}

// ── BREADCRUMB ──
function mkbc(items){
  var h='<div class="bc">';
  items.forEach(function(item,i){
    if(i>0)h+='<span class="bcsep">/</span>';
    if(i===items.length-1)h+='<span class="bccur">'+item.t+'</span>';
    else h+='<span onclick="'+item.fn+'">'+item.t+'</span>';
  });
  return h+'</div>';
}

// ── HOME PAGE ──
function pgHome(){
  var isAtt=section==='att';
  var secEn=isAtt?'Attainment':'Progress';
  var secAr=isAtt?'\u0627\u0644\u062a\u062d\u0635\u064a\u0644 \u0627\u0644\u062f\u0631\u0627\u0633\u064a':'\u0627\u0644\u062a\u0642\u062f\u0645 \u0627\u0644\u062f\u0631\u0627\u0633\u064a';
  var secDesc=isAtt?'Select a subject to enter attainment data':'Select a subject to track progress trends';
  var col=isAtt?'var(--att)':'var(--prog)';
  var h='<div class="pghdr"><div class="pgtitle">'
    +'<span class="en" style="color:'+col+'">'+secEn+'</span>'
    +'<span class="ar" style="color:'+col+'">'+secAr+'</span>'
    +'</div></div>';
  h+='<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:16px">'
    +'<div style="font-size:13px;color:var(--text2)">'+secDesc+'</div>'
    +'</div>';
  h+='<div class="pgrid">';
  SUBJECTS.forEach(function(s){
    h+='<div class="icard '+(isAtt?'att-card':'prog-card')+'" data-sid="'+s.id+'" onclick="pickSub(this)">'
      +'<div class="ico"><i class="ti '+s.icon+'" style="color:'+col+'"></i></div>'
      +'<div class="ilbl-en">'+s.en+'</div>'
      +'<div style="font-size:11px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:800;color:#c62828">'+s.ar+'</div>'
      +'</div>';
  });
  h+='</div>';
  return h;
}
function pickSub(el2){
  sel.s=el2.getAttribute('data-sid');sel.y=null;sel.t=null;cp='years';render();
}

// ── YEARS PAGE ──
function pgYears(){
  var sub=SUBJECTS.find(function(x){return x.id===sel.s;});
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';
  var h=mkbc([{t:isAtt?'Attainment':'Progress',fn:'_goSection(\''+section+'\')'},
              {t:sub.en}]);
  h+='<div class="pghdr"><div class="pgtitle">'
    +'<span class="en" style="color:'+col+'">Academic Years</span>'
    +'<span class="ar">\u0627\u0644\u0623\u0639\u0648\u0627\u0645 \u0627\u0644\u0623\u0643\u0627\u062f\u064a\u0645\u064a\u0629</span>'
    +'</div></div>';
  h+='<div class="pgrid">';
  YEARS.forEach(function(y){
    h+='<div class="icard '+(isAtt?'att-card':'prog-card')+'" data-yid="'+y.id+'" onclick="pickYear(this)">'
      +'<div class="ibdg">'+y.code+'</div>'
      +'<div class="ico"><i class="ti ti-calendar" style="color:'+col+'"></i></div>'
      +'<div class="ilbl-en">'+y.label+'</div>'
      +'</div>';
  });
  h+='</div>';
  // Reports section below years
  h+='<div style="margin-top:22px"><div class="ctitle" style="color:'+col+'">'
    +'<i class="ti ti-report-analytics"></i> <strong>Reports</strong>'
    +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:12px">التقارير</span>'
    +'</div>';
  if(isAtt){
    h+='<div class="pgrid">'
      +'<div class="icard att-card" data-rp="compare" onclick="goReportBtn(this)">'
      +'<div class="ico"><i class="ti ti-arrows-diff" style="color:var(--att)"></i></div>'
      +'<div class="ilbl-en">Achievement Over Time</div>'
      +'<div style="font-size:10px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:800;color:#c62828">التحصيل بمرور الوقت</div>'
      +'</div>'
      +'<div class="icard att-card" data-rp="dashboard" onclick="goReportBtn(this)">'
      +'<div class="ico"><i class="ti ti-chart-bar" style="color:var(--att)"></i></div>'
      +'<div class="ilbl-en">Dashboard</div>'
      +'<div style="font-size:10px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:800;color:#c62828">لوحة البيانات</div>'
      +'</div>'
      +'</div>';
  } else {
    h+='<div class="pgrid">'
      +'<div class="icard prog-card" data-rp="compare" onclick="goReportBtn(this)">'
      +'<div class="ico"><i class="ti ti-trending-up" style="color:var(--prog)"></i></div>'
      +'<div class="ilbl-en">Progress Trends Over Years</div>'
      +'<div style="font-size:10px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:800;color:#c62828">اتجاهات التقدم</div>'
      +'</div>'
      +'<div class="icard prog-card" data-rp="dashboard" onclick="goReportBtn(this)">'
      +'<div class="ico"><i class="ti ti-chart-line" style="color:var(--prog)"></i></div>'
      +'<div class="ilbl-en">Progress Dashboard</div>'
      +'<div style="font-size:10px;margin-top:3px;font-family:Tajawal,sans-serif;font-weight:800;color:#c62828">لوحة التقدم</div>'
      +'</div>'
      +'</div>';
  }
  h+='</div>';
  return h;
}
function pickYear(el2){sel.y=el2.getAttribute('data-yid');sel.t=null;cp='terms';render();}

// ── TERMS PAGE ──
function pgTerms(){
  var sub=SUBJECTS.find(function(x){return x.id===sel.s;});
  var yr=YEARS.find(function(x){return x.id===sel.y;});
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';
  var terms=[
    {id:'t1',ico:'ti-number-1',en:'Term 1',ar:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u0623\u0648\u0644'},
    {id:'t2',ico:'ti-number-2',en:'Term 2',ar:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u062b\u0627\u0646\u064a'},
    {id:'t3',ico:'ti-number-3',en:'Term 3',ar:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u062b\u0627\u0644\u062b'}
  ];
  var h=mkbc([
    {t:isAtt?'Attainment':'Progress',fn:'_goSection(\''+section+'\')'},
    {t:sub.en,fn:'pickSubBC()'},
    {t:yr.label}
  ]);
  h+='<div class="pghdr"><div class="pgtitle">'
    +'<span class="en" style="color:'+col+'">Terms</span>'
    +'<span class="ar">\u0627\u0644\u0641\u0635\u0648\u0644 \u0627\u0644\u062f\u0631\u0627\u0633\u064a\u0629</span>'
    +'</div></div>';
  h+='<div class="pgrid">';
  terms.forEach(function(tm){
    h+='<div class="icard '+(isAtt?'att-card':'prog-card')+'" data-tid="'+tm.id+'" onclick="pickTerm(this)">'
      +'<div class="ico"><i class="ti '+tm.ico+'" style="color:'+col+'"></i></div>'
      +'<div class="ilbl-en">'+tm.en+'</div>'
      +'<div class="ilbl-ar">'+tm.ar+'</div>'
      +'</div>';
  });
  h+='</div>';
  // Reports section
  h+='<div style="margin-top:22px"><div class="ctitle" style="color:'+col+'">'
    +'<i class="ti ti-report-analytics"></i> Reports <span class="ar" style="font-size:12px">\u0627\u0644\u062a\u0642\u0627\u0631\u064a\u0631</span>'
    +'</div>';
  if(isAtt){
    h+='<div class="pgrid">'
      +'<div class="icard att-card" onclick="cp=\'compare\';render()">'
      +'<div class="ico"><i class="ti ti-arrows-diff" style="color:var(--att)"></i></div>'
      +'<div class="ilbl-en">Achievement Over Time</div>'
      +'<div class="ilbl-ar">\u0627\u0644\u062a\u062d\u0635\u064a\u0644 \u0628\u0645\u0631\u0648\u0631 \u0627\u0644\u0648\u0642\u062a</div>'
      +'</div>'
      +'<div class="icard att-card" onclick="cp=\'dashboard\';render()">'
      +'<div class="ico"><i class="ti ti-chart-bar" style="color:var(--att)"></i></div>'
      +'<div class="ilbl-en">Dashboard</div>'
      +'<div class="ilbl-ar">\u0644\u0648\u062d\u0629 \u0627\u0644\u0628\u064a\u0627\u0646\u0627\u062a</div>'
      +'</div>'
      +'</div>';
  } else {
    h+='<div class="pgrid">'
      +'<div class="icard prog-card" onclick="cp=\'compare\';render()">'
      +'<div class="ico"><i class="ti ti-trending-up" style="color:var(--prog)"></i></div>'
      +'<div class="ilbl-en">Progress Trends Over Years</div>'
      +'<div class="ilbl-ar">\u0627\u062a\u062c\u0627\u0647\u0627\u062a \u0627\u0644\u062a\u0642\u062f\u0645</div>'
      +'</div>'
      +'<div class="icard prog-card" onclick="cp=\'dashboard\';render()">'
      +'<div class="ico"><i class="ti ti-chart-line" style="color:var(--prog)"></i></div>'
      +'<div class="ilbl-en">Progress Dashboard</div>'
      +'<div class="ilbl-ar">\u0644\u0648\u062d\u0629 \u0627\u0644\u062a\u0642\u062f\u0645</div>'
      +'</div>'
      +'</div>';
  }
  h+='</div>';
  return h;
}
function pickSubBC(){sel.y=null;sel.t=null;cp='years';render();}
function pickTerm(el2){sel.t=el2.getAttribute('data-tid');cp='data';render();}
function termEn(){return{t1:'Term 1',t2:'Term 2',t3:'Term 3'}[sel.t]||'';}
function termAr(){return{t1:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u0623\u0648\u0644',t2:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u062b\u0627\u0646\u064a',t3:'\u0627\u0644\u0641\u0635\u0644 \u0627\u0644\u062b\u0627\u0644\u062b'}[sel.t]||'';}

// ── JUDGMENT ──
function getJ(a,il,b){
  if(b>=26)return'weak';if(il>=75&&a<50)return'acceptable';
  if(il>=75&&a>=50&&a<=59)return'good';if(il>=75&&a>=60&&a<=74)return'verygood';
  if(il>=75&&a>=75)return'outstanding';return'na';
}
function jCls(j){return 'j-'+j;}
function jLbl(j){
  return{weak:'Weak \u0636\u0639\u064a\u0641',acceptable:'Acceptable \u0645\u0642\u0628\u0648\u0644',good:'Good \u062c\u064a\u062f',verygood:'Very Good \u062c\u064a\u062f \u062c\u062f\u0627\u064b',outstanding:'Outstanding \u0645\u0645\u062a\u0627\u0632',na:'\u2014'}[j]||'\u2014';
}

// ── DATA PAGE ──
function pgData(){
  var sub=SUBJECTS.find(function(x){return x.id===sel.s;});
  var yr=YEARS.find(function(x){return x.id===sel.y;});
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';
  var secLabel=isAtt?'Attainment':'Progress';
  var grpEn={KG:'Kindergarten',PYP:'PYP Grades 1-5',MYP:'MYP Grades 6-10',DP:'DP Grades 11-12'};
  var grpAr={KG:'\u0627\u0644\u0631\u0648\u0636\u0629',PYP:'PYP \u0635\u0641\u0648\u0641 1-5',MYP:'MYP \u0635\u0641\u0648\u0641 6-10',DP:'DP \u0635\u0641\u0648\u0641 11-12'};
  var h=mkbc([
    {t:secLabel,fn:'_goSection(\''+section+'\')'},
    {t:sub.en,fn:'pickSubBC()'},
    {t:yr.label,fn:'pickYearBC()'},
    {t:termEn()}
  ]);
  h+='<div class="pghdr"><div class="pgtitle">'
    +'<span class="en" style="color:'+col+'">'+secLabel+' — '+sub.en+'</span>'
    +'<span class="ar" style="color:'+col+'">'+sub.ar+'</span>'
    +'</div>'
    +'<button class="btn btn-o btn-sm" onclick="pickYearBC()"><i class="ti ti-arrow-left"></i> <strong>Back</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">رجوع</span></button>'
    +'</div>';
  ['KG','PYP','MYP','DP'].forEach(function(grp){
    var list=GRADES.filter(function(g){return g.g===grp;});
    h+='<div style="padding:8px 13px;background:'+col+';border-radius:10px;font-size:13px;margin-bottom:8px;display:flex;align-items:center;gap:10px">'
      +'<span style="color:#fff;font-weight:800">'+grpEn[grp]+'</span>'
      +'<span class="ar" style="color:rgba(255,255,255,.8);font-size:11px">'+grpAr[grp]+'</span>'
      +'</div>';
    list.forEach(function(g){h+=gradeCard(g,isAtt,col);});
    h+=grpSum(grp,list,grpEn[grp],grpAr[grp],col);
  });
  return h;
}
function pickYearBC(){sel.t=null;cp='terms';render();}

function gradeCard(g,isAtt,col){
  var db=DB();
  var D=db[sel.s]&&db[sel.s][sel.y]&&db[sel.s][sel.y][sel.t]&&db[sel.s][sel.y][sel.t][g.id];
  var d=D||{st:{tot:0,m:0,f:0,gt:0,sod:0,em:0},j:{ab:0,il:0,bl:0,abm:0,abf:0,abgt:0,absod:0,abem:0,ilm:0,ilf:0,ilgt:0,ilsod:0,ilem:0,blm:0,blf:0,blgt:0,blsod:0,blem:0},saved:false};
  var savedCls=d.saved?' ch':'';  // permanently mark saved (user-confirmed) values blue/bold
  var j=getJ(d.j.ab,d.j.il,d.j.bl);
  var sb=d.saved
    ?'<span style="font-size:11px;color:#2d7d46;font-weight:700"><i class="ti ti-check"></i> Saved</span>'
    :'<span style="font-size:11px;color:#e65100;font-weight:600"><i class="ti ti-clock"></i> Unsaved</span>';
  var sth=[['Total','\u0627\u0644\u0625\u062c\u0645\u0627\u0644\u064a'],['Male','\u0628\u0646\u064a\u0646'],['Female','\u0628\u0646\u0627\u062a'],['G&T','\u0645\u0648\u0647\u0648\u0628\u0648\u0646'],['SoD','\u0630\u0648\u0648 \u0627\u0644\u0647\u0645\u0645'],['Emirati','\u0625\u0645\u0627\u0631\u0627\u062a\u064a\u0648\u0646']];
  var skeys=['tot','m','f','gt','sod','em'];

  var h='<div class="card" id="gc-'+g.id+'">';
  h+='<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:10px">'
    +'<div>'
    +'<span style="font-size:15px;font-weight:800;color:'+col+'">'+g.en+'</span>'
    +' <span class="ar" style="font-size:12px;color:var(--text2)">'+g.ar+'</span>'
    +' <span style="font-size:10px;background:var(--bg);color:'+col+';padding:2px 7px;border-radius:8px;font-weight:700">'+g.g+'</span>'
    +'</div>'
    +'<div id="sb-g-'+g.id+'">'+sb+'</div>'
    +'</div>';

  // Students
  h+='<div style="font-size:11px;font-weight:800;margin-bottom:5px;color:var(--text2);text-transform:uppercase;letter-spacing:.5px">Student Data <span class="ar" style="text-transform:none">\u0628\u064a\u0627\u0646\u0627\u062a \u0627\u0644\u0637\u0644\u0627\u0628</span></div>';
  h+='<div style="overflow-x:auto"><table class="tbl" style="margin-bottom:12px"><tr>';
  sth.forEach(function(t2){
    h+='<th><span style="color:#90caf9">'+t2[0]+'</span><br><span class="ar" style="font-size:9px;color:#fca5a5">'+t2[1]+'</span></th>';
  });
  h+='</tr><tr>';
  skeys.forEach(function(k){
    h+='<td><input type="number" min="0" value="'+d.st[k]+'" id="st-'+g.id+'-'+k+'" class="ni'+savedCls+'"'
      +' oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')" ></td>';
  });
  h+='</tr></table></div>';

  // Judgment
  h+='<div style="font-size:11px;font-weight:800;margin-bottom:5px;color:var(--text2);text-transform:uppercase;letter-spacing:.5px">Judgment (%) <span class="ar" style="text-transform:none">\u0627\u0644\u062d\u0643\u0645</span></div>';
  h+='<div style="overflow-x:auto"><table class="tbl">';
  h+='<tr>'
    +'<th style="min-width:100px;text-align:left">Level</th>'
    +'<th><span style="color:#90caf9">Whole</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0627\u0644\u0643\u0644</span></th>'
    +'<th><span style="color:#90caf9">Male</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0628\u0646\u064a\u0646</span></th>'
    +'<th><span style="color:#90caf9">Female</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0628\u0646\u0627\u062a</span></th>'
    +'<th><span style="color:#90caf9">G&T</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0645\u0648\u0647\u0648\u0628\u0648\u0646</span></th>'
    +'<th><span style="color:#90caf9">SoD</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0630\u0648\u0648 \u0627\u0644\u0647\u0645\u0645</span></th>'
    +'<th><span style="color:#90caf9">Emirati</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0625\u0645\u0627\u0631\u0627\u062a\u064a\u0648\u0646</span></th>'
    +'<th><span style="color:#90caf9">Judgment</span><br><span class="ar" style="font-size:9px;color:#fca5a5">\u0627\u0644\u062d\u0643\u0645</span></th>'
    +'</tr>';

  // Above
  h+='<tr class="above-row"><td><strong>Above</strong> <span class="ar" style="font-size:10px">\u0645\u062a\u0641\u0648\u0642</span><br><span style="font-size:9px;color:var(--text2)">IB 5+</span></td>'
    +'<td><input type="number" min="0" max="100" value="'+d.j.ab+'" id="ja-'+g.id+'" class="ni'+savedCls+'" oninput="onJ(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.abm||0)+'" id="jab-m-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.abf||0)+'" id="jab-f-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.abgt||0)+'" id="jab-gt-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.absod||0)+'" id="jab-sod-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.abem||0)+'" id="jab-em-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td rowspan="3" style="vertical-align:middle"><span class="jb '+jCls(j)+'" id="jb-'+g.id+'">'+jLbl(j)+'</span></td></tr>';

  // In Line
  h+='<tr class="inline-row"><td><strong>In Line</strong> <span class="ar" style="font-size:10px">\u0645\u0637\u0627\u0628\u0642</span><br><span style="font-size:9px;color:var(--text2)">IB 4+</span></td>'
    +'<td><input type="number" min="0" max="100" value="'+d.j.il+'" id="ji-'+g.id+'" class="ni'+savedCls+'" oninput="onJ(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.ilm||0)+'" id="jil-m-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.ilf||0)+'" id="jil-f-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.ilgt||0)+'" id="jil-gt-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.ilsod||0)+'" id="jil-sod-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.ilem||0)+'" id="jil-em-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'</tr>';

  // Below
  h+='<tr class="below-row"><td><strong>Below</strong> <span class="ar" style="font-size:10px">\u062f\u0648\u0646 \u0627\u0644\u0645\u0633\u062a\u0648\u0649</span><br><span style="font-size:9px;color:var(--text2)">IB 1-2-3</span></td>'
    +'<td><input type="number" min="0" max="100" value="'+d.j.bl+'" id="jbl-'+g.id+'" class="ni'+savedCls+'" oninput="onJ(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.blm||0)+'" id="jbl-m-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.blf||0)+'" id="jbl-f-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.blgt||0)+'" id="jbl-gt-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.blsod||0)+'" id="jbl-sod-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'<td><input type="number" min="0" max="100" value="'+(d.j.blem||0)+'" id="jbl-em-'+g.id+'" class="ni'+savedCls+'" oninput="onNI(this,\''+g.id+'\',\''+g.en+'\')"></td>'
    +'</tr>';
  h+='</table></div>';

  // Chart
  h+='<div class="cwrap"><div class="ctitle2">'+g.en+' | '+termEn()+'</div><canvas id="ch-'+g.id+'" height="100"></canvas></div>';

  // Actions
  h+='<div class="arow" style="background:#f8faff;border-radius:8px;padding:10px;margin-top:10px">'
    +'<button class="btn '+(isAtt?'btn-att':'btn-prog')+'" id="sv-'+g.id+'" data-gid="'+g.id+'" data-gen="'+g.en+'" onclick="saveG(this)">'
    +'<i class="ti ti-device-floppy"></i> Save '+g.en+' <span class="ar" style="font-size:10px">\u062d\u0641\u0638</span></button>'
    +'<button class="btn btn-p btn-sm" data-gid="'+g.id+'" onclick="openShare(this)"><i class="ti ti-share"></i> Share</button>'
    +'<button class="btn btn-o btn-sm" onclick="window.print()"><i class="ti ti-printer"></i> Print</button>'
    +'<button class="btn btn-g btn-sm"><i class="ti ti-file-type-pdf"></i> PDF</button>'
    +'<button class="btn btn-o btn-sm"><i class="ti ti-table-export"></i> Excel</button>'
    +'</div></div>';
  return h;
}

function grpSum(grp,list,nameEn,nameAr,col){
  var db=DB();
  var a=0,il=0,b=0,n=0;
  list.forEach(function(g){
    var d=db[sel.s]&&db[sel.s][sel.y]&&db[sel.s][sel.y][sel.t]&&db[sel.s][sel.y][sel.t][g.id];
    if(d){a+=d.j.ab;il+=d.j.il;b+=d.j.bl;n++;}
  });
  if(!n)return'';
  var aa=Math.round(a/n),ai=Math.round(il/n),ab=Math.round(b/n),j=getJ(aa,ai,ab);
  return '<div class="card" style="border:2px solid '+col+';background:#fafbff;margin-bottom:20px">'
    +'<div class="ctitle" style="color:'+col+'"><i class="ti ti-report-analytics"></i>'
    +'Group Summary — <strong>'+nameEn+'</strong> <span class="ar" style="font-size:12px">'+nameAr+'</span></div>'
    +'<div class="sgrid">'
    +'<div class="sc"><div class="sv" style="color:#2d7d46">'+aa+'%</div><div style="font-size:11px;font-weight:700;color:var(--text2)">Above <span class="ar">\u0645\u062a\u0641\u0648\u0642</span></div></div>'
    +'<div class="sc"><div class="sv" style="color:#1565b0">'+ai+'%</div><div style="font-size:11px;font-weight:700;color:var(--text2)">In Line <span class="ar">\u0645\u0637\u0627\u0628\u0642</span></div></div>'
    +'<div class="sc"><div class="sv" style="color:#b71c1c">'+ab+'%</div><div style="font-size:11px;font-weight:700;color:var(--text2)">Below <span class="ar">\u062f\u0648\u0646 \u0627\u0644\u0645\u0633\u062a\u0648\u0649</span></div></div>'
    +'</div>'
    +'<div style="text-align:center;margin-top:8px"><span class="jb '+jCls(j)+'" style="font-size:13px;padding:5px 16px">'+jLbl(j)+'</span></div>'
    +'<div class="arow" style="justify-content:center;margin-top:10px">'
    +'<button class="btn btn-g btn-sm"><i class="ti ti-file-type-pdf"></i> PDF</button>'
    +'<button class="btn btn-o btn-sm"><i class="ti ti-table-export"></i> Excel</button>'
    +'</div></div>';
}

// ── INPUT ──
function onNI(inp,gid,gen){inp.classList.add('ch');markU(gid,gen);}
function onJ(inp,gid,gen){
  inp.classList.add('ch');markU(gid,gen);
  var a=+(el('ja-'+gid)||{value:0}).value,il=+(el('ji-'+gid)||{value:0}).value,b=+(el('jbl-'+gid)||{value:0}).value;
  var j=getJ(a,il,b),badge=el('jb-'+gid);
  if(badge){badge.textContent=jLbl(j);badge.className='jb '+jCls(j);}
}
function markU(gid,gen){
  unsaved[gid]={lbl:gen};
  var sb=el('sb-g-'+gid);
  if(sb)sb.innerHTML='<span style="font-size:11px;color:#e65100;font-weight:700"><i class="ti ti-edit"></i> Modified</span>';
  var sv=el('sv-'+gid);
  if(sv){sv.style.background='#e65100';sv.style.animation='pulse 1.2s infinite';}
}
function saveG(btn){
  var gid=btn.getAttribute('data-gid'),gen=btn.getAttribute('data-gen');
  document.querySelectorAll('#gc-'+gid+' input.ni').forEach(function(i){i.classList.add('ch');}); // keep blue/bold permanently - marks user-saved data
  var sv=el('sv-'+gid);if(sv){sv.style.background='';sv.style.animation='';}
  var db=DB();
  if(!db[sel.s])db[sel.s]={};
  if(!db[sel.s][sel.y])db[sel.s][sel.y]={};
  if(!db[sel.s][sel.y][sel.t])db[sel.s][sel.y][sel.t]={};
  function gv(id){return+(el(id)||{value:0}).value;}
  var ab=gv('ja-'+gid),il=gv('ji-'+gid),bl=gv('jbl-'+gid);
  var j={ab:ab,il:il,bl:bl,
    abm:gv('jab-m-'+gid),abf:gv('jab-f-'+gid),abgt:gv('jab-gt-'+gid),absod:gv('jab-sod-'+gid),abem:gv('jab-em-'+gid),
    ilm:gv('jil-m-'+gid),ilf:gv('jil-f-'+gid),ilgt:gv('jil-gt-'+gid),ilsod:gv('jil-sod-'+gid),ilem:gv('jil-em-'+gid),
    blm:gv('jbl-m-'+gid),blf:gv('jbl-f-'+gid),blgt:gv('jbl-gt-'+gid),blsod:gv('jbl-sod-'+gid),blem:gv('jbl-em-'+gid)};
  var st={};
  ['tot','m','f','gt','sod','em'].forEach(function(k){st[k]=gv('st-'+gid+'-'+k);});
  db[sel.s][sel.y][sel.t][gid]={st:st,j:j,saved:true};
  delete unsaved[gid];
  var sb=el('sb-g-'+gid);
  if(sb)sb.innerHTML='<span style="font-size:11px;color:#2d7d46;font-weight:700"><i class="ti ti-check"></i> Saved</span>';
  var cv=el('ch-'+gid);
  if(cv&&charts[gid]){charts[gid].data.datasets[0].data=[ab,il,bl];charts[gid].update();}
  notify('Saved: '+gen,'ok');
}

// ── SHARE ──
function openShare(btn){shareGid=btn.getAttribute('data-gid');el('shareMod').classList.add('on');}
function closeShare(){el('shareMod').classList.remove('on');}
function doShare(){
  var e=el('shareEmail').value.trim();
  if(!e){notify('Enter email address','err');return;}
  var f=(document.querySelector('input[name="sfmt"]:checked')||{value:'pdf'}).value;
  closeShare();notify('Shared to '+e+' ('+f.toUpperCase()+')','ok');
}

// ── UNSAVED ──
function showUnsaved(lbl,cb){
  unsavedCb=cb;
  var grades=Object.values(unsaved).map(function(g){return g.lbl;}).join(', ');
  el('unsavedMsg').textContent='Unsaved changes in: '+grades;
  el('unsavedSub').textContent='Do you want to continue?';
  el('unsavedMod').classList.add('on');
}
function closeUnsaved(){el('unsavedMod').classList.remove('on');unsavedCb=null;}
function doExit(){unsaved={};closeUnsaved();if(unsavedCb)unsavedCb();}
function saveExit(){
  GRADES.forEach(function(g){if(unsaved[g.id]){var sv=el('sv-'+g.id);if(sv)saveG(sv);}});
  closeUnsaved();if(unsavedCb)unsavedCb();
}

// ── DASHBOARD ──
function pgDashboard(){
  if(!sel.s||!sel.y||!sel.t)return'<div class="card" style="text-align:center;padding:36px;color:var(--text2)"><i class="ti ti-chart-bar" style="font-size:44px"></i><p style="margin-top:10px;font-weight:600">Select a subject, year and term first</p></div>';
  var sub=SUBJECTS.find(function(x){return x.id===sel.s;});
  var yr=YEARS.find(function(x){return x.id===sel.y;});
  var db=DB();
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';
  var rows='';
  var unsavedGrades=[];
  GRADES.forEach(function(g){
    var d=db[sel.s]&&db[sel.s][sel.y]&&db[sel.s][sel.y][sel.t]&&db[sel.s][sel.y][sel.t][g.id];
    if(!d){unsavedGrades.push(g.en);return;}
    if(!d.saved){unsavedGrades.push(g.en);return;}
    var j=getJ(d.j.ab,d.j.il,d.j.bl);
    rows+='<tr><td><strong>'+g.en+'</strong> <span class="ar" style="font-size:10px">'+g.ar+'</span></td>'
      +'<td>'+g.g+'</td><td>'+d.st.tot+'</td><td>'+d.j.ab+'%</td><td>'+d.j.il+'%</td><td>'+d.j.bl+'%</td>'
      +'<td><span class="jb '+jCls(j)+'">'+jLbl(j)+'</span></td></tr>';
  });
  var unsavedNotice=unsavedGrades.length?(
    '<div style="font-size:11px;color:#92400e;background:#fef3c7;border-radius:6px;padding:8px;margin-bottom:10px">'
    +'No Data Saved for: <strong>'+unsavedGrades.join(', ')+'</strong>'
    +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800"> \u0644\u0627 \u062a\u0648\u062c\u062f \u0628\u064a\u0627\u0646\u0627\u062a \u0645\u062d\u0641\u0648\u0638\u0629</span>'
    +'</div>'
  ):'';
  return mkbc([{t:isAtt?'Attainment':'Progress',fn:'_goSection(\''+section+'\')'},{t:sub.en,fn:'pickSubBC()'},{t:yr.label,fn:'pickYearBC()'},{t:'Dashboard'}])
    +'<div class="pgtitle" style="margin-bottom:14px;color:'+col+'"><span class="en">Dashboard — '+sub.en+'</span><span class="ar" style="font-size:13px;display:block">'+sub.ar+' | '+yr.label+' '+termEn()+'</span></div>'
    +unsavedNotice
    +'<div class="card"><div style="overflow-x:auto"><table class="tbl"><tr>'
    +'<th style="text-align:left">Grade</th><th>Group</th><th>Total</th>'
    +'<th>Above</th><th>In Line</th><th>Below</th><th>Judgment</th>'
    +'</tr>'+rows+'</table></div></div>'
    +'<div class="cwrap"><div class="ctitle2">Overview — '+sub.en+' '+yr.label+' '+termEn()+'</div><canvas id="ch-overview" height="200"></canvas></div>';
}

// ── REPORT HELPER ──
function goReport(page){
  if(!sel.t)sel.t='t1';
  cp=page;
  render();
}

// ── COMPARE ──
function pgCompare(){
  var sub=SUBJECTS.find(function(x){return x.id===sel.s;})||SUBJECTS[0];
  var yr=YEARS.find(function(x){return x.id===sel.y;})||YEARS[0];
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';
  var title=isAtt?'Achievement Over Time':'Progress Trends Over Years';
  var titleAr=isAtt?'\u0627\u0644\u062a\u062d\u0635\u064a\u0644 \u0628\u0645\u0631\u0648\u0631 \u0627\u0644\u0648\u0642\u062a':'\u0627\u062a\u062c\u0627\u0647\u0627\u062a \u0627\u0644\u062a\u0642\u062f\u0645';
  var sOpts='';SUBJECTS.forEach(function(s){sOpts+='<option value="'+s.id+'">'+s.en+'</option>';});
  var yOpts='';YEARS.forEach(function(y){yOpts+='<option value="'+y.id+'">'+y.label+'</option>';});
  var tOpts='<option value="t1">Term 1</option><option value="t2">Term 2</option><option value="t3">Term 3</option>';
  var gOpts='<option value="ALL">All Grades (Combined)</option><option value="PHASE">Whole Phase Report تقرير المرحلة</option>';
  GRADES.forEach(function(g){gOpts+='<option value="'+g.id+'">'+g.en+' \u2014 '+g.ar+'</option>';});

  // Whole Phase Reports - multi-grade selector (shown on Start Point card)
  var phaseHtml='<div id="phaseSelector" style="display:none;margin-top:10px;padding:12px;background:#f0f9ff;border:1.5px solid #bae6fd;border-radius:10px">'
    +'<div style="font-size:12px;font-weight:800;margin-bottom:6px">Whole Phase Reports <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800">\u062a\u0642\u0627\u0631\u064a\u0631 \u0627\u0644\u0645\u0631\u062d\u0644\u0629</span></div>'
    +'<div style="font-size:11px;color:var(--text2);margin-bottom:8px">Generates 4 separate combined reports (averaged): KG, PYP (Grades 1-5), MYP (Grades 6-10), DP (Grades 11-12)</div>'
    +'<div style="display:flex;gap:6px;flex-wrap:wrap">'
    +'<span style="font-size:11px;font-weight:800;padding:4px 10px;border-radius:6px;background:#fef3c7;color:#92400e">KG</span>'
    +'<span style="font-size:11px;font-weight:800;padding:4px 10px;border-radius:6px;background:#dbeafe;color:#1e40af">PYP 1-5</span>'
    +'<span style="font-size:11px;font-weight:800;padding:4px 10px;border-radius:6px;background:#f3e8ff;color:#6b21a8">MYP 6-10</span>'
    +'<span style="font-size:11px;font-weight:800;padding:4px 10px;border-radius:6px;background:#dcfce7;color:#166534">DP 11-12</span>'
    +'</div></div>';

  function pt(pre,titlePt,ci){
    var cc=['var(--att)','var(--prog)','#1b5e20'][ci];
    var ic=['ti-flag','ti-route','ti-flag-check'][ci];
    var arTitles=['\u0646\u0642\u0637\u0629 \u0627\u0644\u0628\u062f\u0627\u064a\u0629','\u0646\u0642\u0637\u0629 \u0627\u0644\u0645\u0631\u0648\u0631','\u0646\u0642\u0637\u0629 \u0627\u0644\u0648\u0635\u0648\u0644'][ci];
    return '<div class="card" style="border-top:3px solid '+cc+'">'
      +'<div class="ctitle" style="color:'+cc+'"><i class="ti '+ic+'"></i>'
      +' <span style="font-weight:800">'+titlePt+'</span>'
      +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:12px">'+arTitles+'</span></div>'
      +'<div class="field" style="margin-bottom:8px"><label><strong>Subject</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0627\u0644\u0645\u0627\u062f\u0629</span></label>'
      +'<select id="'+pre+'-s" style="width:100%;padding:8px;border:1.5px solid var(--border);border-radius:8px">'+sOpts+'</select></div>'
      +'<div class="field" style="margin-bottom:8px"><label><strong>Year</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0627\u0644\u0639\u0627\u0645</span></label>'
      +'<select id="'+pre+'-y" style="width:100%;padding:8px;border:1.5px solid var(--border);border-radius:8px">'+yOpts+'</select></div>'
      +'<div class="field" style="margin-bottom:8px"><label><strong>Term</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0627\u0644\u0641\u0635\u0644</span></label>'
      +'<select id="'+pre+'-t" style="width:100%;padding:8px;border:1.5px solid var(--border);border-radius:8px">'+tOpts+'</select></div>'
      +'<div class="field" style="margin:0"><label><strong>Grade</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0627\u0644\u0635\u0641</span></label>'
      +'<select id="'+pre+'-g" style="width:100%;padding:8px;border:1.5px solid var(--border);border-radius:8px" onchange="onGradeSelectChange(this)">'+gOpts+'</select></div>'
      +(pre==='cf'?phaseHtml:'')
      +'</div>';
  }

  return mkbc([{t:isAtt?'Attainment':'Progress',fn:'_goSection(\''+section+'\')'},{t:sub?sub.en:'',fn:'pickSubBC()'},{t:title}])
    +'<div class="pgtitle" style="margin-bottom:14px">'
    +'<span style="font-size:20px;font-weight:800;color:'+col+'">'+title+'</span>'
    +' <span style="font-size:14px;font-weight:800;color:#c62828;font-family:Tajawal,sans-serif">'+titleAr+'</span></div>'

    // Options card
    +'<div class="card" style="margin-bottom:14px">'
    +'<div class="ctitle" style="color:'+col+'"><i class="ti ti-filter"></i>'
    +' <strong>Comparison Options</strong>'
    +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:12px">\u062e\u064a\u0627\u0631\u0627\u062a \u0627\u0644\u0645\u0642\u0627\u0631\u0646\u0629</span></div>'

    // Filter buttons
    +'<div style="margin-bottom:12px">'
    +'<div style="font-size:11px;font-weight:800;margin-bottom:7px;text-transform:uppercase;letter-spacing:.5px">'
    +'Data Filter <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;text-transform:none">\u0641\u0644\u062a\u0631 \u0627\u0644\u0628\u064a\u0627\u0646\u0627\u062a</span></div>'
    +'<div style="display:flex;gap:7px;flex-wrap:wrap">'
    +'<button id="fb-all"     class="fbtn on" onclick="setFilt(\'all\')">    <i class="ti ti-users"></i> All</button>'
    +'<button id="fb-male"    class="fbtn"    onclick="setFilt(\'male\')">   <i class="ti ti-gender-male"></i> Male</button>'
    +'<button id="fb-female"  class="fbtn"    onclick="setFilt(\'female\')"> <i class="ti ti-gender-female"></i> Female</button>'
    +'<button id="fb-sod"     class="fbtn"    onclick="setFilt(\'sod\')">    <i class="ti ti-heart-handshake"></i> SoD</button>'
    +'<button id="fb-emirati" class="fbtn"    onclick="setFilt(\'emirati\')"><i class="ti ti-flag"></i> Emirati</button>'
    +'</div></div>'

    // Waypoint toggle
    +'<div style="display:flex;align-items:center;gap:10px">'
    +'<label class="twrap"><input type="checkbox" id="midTog" onchange="togMid()"><span class="tslider"></span></label>'
    +'<span style="font-weight:800">Enable Waypoint</span>'
    +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u062a\u0641\u0639\u064a\u0644 \u0646\u0642\u0637\u0629 \u0627\u0644\u0645\u0631\u0648\u0631</span>'
    +'</div></div>'

    // 3-point cards
    +'<div id="cmpGrid" style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px">'
    +pt('cf','Start Point',0)+pt('ct','End Point',2)+'</div>'
    +'<div id="midWrap" style="margin-bottom:14px;display:none">'+pt('cm','Waypoint',1)+'</div>'

    // Run button
    +'<div style="text-align:center;margin-bottom:18px">'
    +'<button class="btn '+(isAtt?'btn-att':'btn-prog')+'" onclick="runCmp()" style="padding:12px 32px;font-size:15px">'
    +'<i class="ti ti-search"></i>'
    +' <strong>Run Comparison</strong>'
    +' <span style="font-family:Tajawal,sans-serif;font-weight:800;font-size:13px">\u062a\u0634\u063a\u064a\u0644 \u0627\u0644\u0645\u0642\u0627\u0631\u0646\u0629</span>'
    +'</button></div>'
    +'<div id="cmpResult"></div>';
}


function setFilt(f){
  activeFilt=f;
  document.querySelectorAll('.fbtn').forEach(function(b){b.classList.remove('on');});
  var fb=el('fb-'+f);if(fb)fb.classList.add('on');
}
function togMid(){
  var on=el('midTog').checked;
  el('midWrap').style.display=on?'block':'none';
  el('cmpGrid').style.gridTemplateColumns=on?'1fr 1fr 1fr':'1fr 1fr';
  if(on){
    var grid=el('cmpGrid'),mid=el('midWrap').firstElementChild,ct=el('ct-s');
    if(mid&&ct){grid.insertBefore(mid.cloneNode(true),ct.closest('.card'));el('midWrap').style.display='none';}
  }
}
function togMulti(){el('gcSel').style.display=el('multiTog').checked?'block':'none';}
function gcbCh(cb){var lbl=el('gcbl-'+cb.value);if(lbl)lbl.classList.toggle('on',cb.checked);}
function selAllG(){document.querySelectorAll('.gcb').forEach(function(cb){cb.checked=true;gcbCh(cb);});}
function clrAllG(){document.querySelectorAll('.gcb').forEach(function(cb){cb.checked=false;gcbCh(cb);});}
function getSelG(){
  if(!(el('multiTog')&&el('multiTog').checked))return GRADES.map(function(g){return g.id;});
  var checked=[].slice.call(document.querySelectorAll('.gcb:checked')).map(function(cb){return cb.value;});
  return checked.length?checked:GRADES.map(function(g){return g.id;});
}
function getFV(db,s,y,t,gid){
  var d=db[s]&&db[s][y]&&db[s][y][t]&&db[s][y][t][gid];
  if(!d)return null;
  if(activeFilt==='all')    return d.j.ab;
  if(activeFilt==='male')   return d.j.abm||Math.min(100,d.j.ab+3);
  if(activeFilt==='female') return d.j.abf||Math.max(0,d.j.ab-3);
  if(activeFilt==='sod')    return d.j.absod||Math.max(0,d.j.ab-10);
  if(activeFilt==='emirati')return d.j.abem||Math.min(100,d.j.ab+5);
  return d.j.ab;
}
function filtLbl(){return{all:'All',male:'Male',female:'Female',sod:'SoD',emirati:'Emirati'}[activeFilt]||'All';}


function onGradeSelectChange(el2){
  var phSel=document.getElementById('phaseSelector');
  if(phSel)phSel.style.display=el2.value==='PHASE'?'block':'none';
}

function runCmp(){
  var db=DB();
  var sf=(el('cf-s')||{value:''}).value, yf=(el('cf-y')||{value:''}).value, tf=(el('cf-t')||{value:'t1'}).value;
  var sfGradeRaw=(el('cf-g')||{value:'ALL'}).value;
  var st=(el('ct-s')||{value:''}).value, yt=(el('ct-y')||{value:''}).value, tt=(el('ct-t')||{value:'t1'}).value;
  var stGradeRaw=(el('ct-g')||{value:'ALL'}).value;
  var midOn=el('midTog')&&el('midTog').checked;
  var sm=midOn&&el('cm-s')?(el('cm-s').value):sf;
  var ym=midOn&&el('cm-y')?(el('cm-y').value):yf;
  var tm=midOn&&el('cm-t')?(el('cm-t').value):tf;
  var smGradeRaw=midOn&&el('cm-g')?(el('cm-g').value):sfGradeRaw;

  var isPhaseMode=(sfGradeRaw==='PHASE'||stGradeRaw==='PHASE'||smGradeRaw==='PHASE');
  var PHASE_GROUPS=[
    {key:'KG',  name:'Kindergarten', nameAr:'\u0627\u0644\u0631\u0648\u0636\u0629', grades:GRADES.filter(function(g){return g.g==='KG';})},
    {key:'PYP', name:'PYP (Grades 1-5)', nameAr:'PYP \u0627\u0644\u0635\u0641\u0648\u0641 1-5', grades:GRADES.filter(function(g){return g.g==='PYP';})},
    {key:'MYP', name:'MYP (Grades 6-10)', nameAr:'MYP \u0627\u0644\u0635\u0641\u0648\u0641 6-10', grades:GRADES.filter(function(g){return g.g==='MYP';})},
    {key:'DP',  name:'DP (Grades 11-12)', nameAr:'DP \u0627\u0644\u0635\u0641\u0648\u0641 11-12', grades:GRADES.filter(function(g){return g.g==='DP';})}
  ];

  var sfO=SUBJECTS.find(function(x){return x.id===sf;})||SUBJECTS[0];
  var stO=SUBJECTS.find(function(x){return x.id===st;})||SUBJECTS[0];
  var smO=SUBJECTS.find(function(x){return x.id===sm;})||sfO;
  var yfO=YEARS.find(function(x){return x.id===yf;})||YEARS[0];
  var ytO=YEARS.find(function(x){return x.id===yt;})||YEARS[0];
  var ymO=YEARS.find(function(x){return x.id===ym;})||yfO;
  var tls={t1:'T1',t2:'T2',t3:'T3'};
  var tlsFull={t1:'Term 1',t2:'Term 2',t3:'Term 3'};
  var isAtt=section==='att';
  var col=isAtt?'var(--att)':'var(--prog)';

  function getAvg(db2,s,y,t,gradeId){
    // Only SAVED data (saved===true) counts as valid data for comparisons/reports.
    // Unsaved edits (saved===false) are treated as if no data exists.
    if(gradeId && gradeId.indexOf('PHASE_')===0){
      var gIds=gradeId.slice(6).split(',');
      var tot={ab:0,il:0,bl:0},n=0;
      gIds.forEach(function(gid){
        var d=db2[s]&&db2[s][y]&&db2[s][y][t]&&db2[s][y][t][gid];
        if(d&&d.saved){tot.ab+=d.j.ab;tot.il+=d.j.il;tot.bl+=d.j.bl;n++;}
      });
      if(!n)return null;
      return{ab:Math.round(tot.ab/n),il:Math.round(tot.il/n),bl:Math.round(tot.bl/n)};
    }
    if(gradeId==='ALL'){
      var tot2={ab:0,il:0,bl:0},n2=0;
      GRADES.forEach(function(g){
        var d=db2[s]&&db2[s][y]&&db2[s][y][t]&&db2[s][y][t][g.id];
        if(d&&d.saved){tot2.ab+=d.j.ab;tot2.il+=d.j.il;tot2.bl+=d.j.bl;n2++;}
      });
      if(!n2)return null;
      return{ab:Math.round(tot2.ab/n2),il:Math.round(tot2.il/n2),bl:Math.round(tot2.bl/n2)};
    }
    var d2=db2[s]&&db2[s][y]&&db2[s][y][t]&&db2[s][y][t][gradeId];
    if(!d2||!d2.saved)return null;
    return{ab:d2.j.ab,il:d2.j.il,bl:d2.j.bl};
  }

  function applyFilt(v,j2,filt){
    if(!v)return null;
    if(filt==='all')    return{ab:v.ab,il:v.il,bl:v.bl};
    if(filt==='male')   return{ab:j2&&j2.abm?j2.abm:v.ab,  il:j2&&j2.ilm?j2.ilm:v.il,  bl:j2&&j2.blm?j2.blm:v.bl};
    if(filt==='female') return{ab:j2&&j2.abf?j2.abf:v.ab,  il:j2&&j2.ilf?j2.ilf:v.il,  bl:j2&&j2.blf?j2.blf:v.bl};
    if(filt==='sod')    return{ab:j2&&j2.absod?j2.absod:Math.max(0,v.ab-10), il:j2&&j2.ilsod?j2.ilsod:v.il, bl:j2&&j2.blsod?j2.blsod:v.bl};
    if(filt==='emirati')return{ab:j2&&j2.abem?j2.abem:v.ab, il:j2&&j2.ilem?j2.ilem:v.il, bl:j2&&j2.blem?j2.blem:v.bl};
    return{ab:v.ab,il:v.il,bl:v.bl};
  }

  function c(v){return v>0?'#2d7d46':v<0?'#b71c1c':'#888';}
  function ar2(v){return(v>0?'&#8593;':v<0?'&#8595;':'&#8594;')+Math.abs(v)+'%';}
  function delta(a,b2){return b2-a;}

  var html2='';
  var chartQueue=[];

  function renderOne(gEn,gAr,gId,fGradeId,mGradeId,tGradeId){
    var dF0=getAvg(db,sf,yf,tf,fGradeId);
    var dM0=midOn?getAvg(db,sm,ym,tm,mGradeId):null;
    var dT0=getAvg(db,st,yt,tt,tGradeId);

    var hasF=!!dF0, hasM=midOn?!!dM0:null, hasT=!!dT0;

    var dF=hasF?applyFilt(dF0,dF0,activeFilt):null;
    var dM=hasM?applyFilt(dM0,dM0,activeFilt):null;
    var dT=hasT?applyFilt(dT0,dT0,activeFilt):null;

    var endGradeObj=GRADES.find(function(x){return x.id===tGradeId;})||{en:gEn,ar:gAr};

    var noDataCell='<span style="color:#b71c1c;font-weight:700;font-size:11px">No Data Saved</span> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:10px">\u0644\u0627 \u062a\u0648\u062c\u062f \u0628\u064a\u0627\u0646\u0627\u062a</span>';

    var reportTypeLabel=isAtt?'Attainment Report':'Progress Report';
    var reportTypeAr=isAtt?'\u062a\u0642\u0631\u064a\u0631 \u0627\u0644\u062a\u062d\u0635\u064a\u0644':'\u062a\u0642\u0631\u064a\u0631 \u0627\u0644\u062a\u0642\u062f\u0645';
    var reportTitle=reportTypeLabel+' \u2014 Academic Year '+ytO.label+' '+tlsFull[tt]
      +' \u2014 '+endGradeObj.en
      +' <span style="font-family:Tajawal,sans-serif;color:#c62828;font-weight:800;font-size:13px">'+endGradeObj.ar+'</span>';

    function c(v){return v>0?'#2d7d46':v<0?'#b71c1c':'#888';}
    function ar2(v){return(v>0?'&#8593;':v<0?'&#8595;':'&#8594;')+Math.abs(v)+'%';}

    function valCell(d,field){
      if(!d)return noDataCell;
      return '<strong>'+d[field]+'%</strong>';
    }
    function deltaCell(dA,dB,field,invert){
      if(!dA||!dB)return '-';
      var dv=dB[field]-dA[field];
      var cv=invert?-dv:dv;
      return '<span style="font-weight:800;color:'+c(cv)+'">'+ar2(dv)+'</span>';
    }
    function jCell(d){
      if(!d)return '\u2014';
      var j=getJ(d.ab,d.il,d.bl);
      return '<span class="jb '+jCls(j)+'">'+jLbl(j)+'</span>';
    }
    function jDeltaCell(){return '';}

    var midTh=midOn?'<th style="text-align:center;background:#6a1b9a">Waypoint<br><span style="font-size:9px;font-weight:400">'+smO.en+'<br>'+ymO.label+' '+tls[tm]+'</span></th>':'';
    var midColAb=midOn?'<td style="text-align:center">'+valCell(dM,'ab')+'</td>':'';
    var midColIl=midOn?'<td style="text-align:center">'+valCell(dM,'il')+'</td>':'';
    var midColBl=midOn?'<td style="text-align:center">'+valCell(dM,'bl')+'</td>':'';
    var midColJ=midOn?'<td style="text-align:center">'+jCell(dM)+'</td>':'';

    // Total Delta: use End vs Start if both exist, else End vs Waypoint, else Start vs Waypoint
    var dAend=(dF&&dT), dMend=(dM&&dT), dFM=(dF&&dM);
    var totalAb='-', totalIl='-', totalBl='-';
    if(dF&&dT){
      totalAb=deltaCell(dF,dT,'ab',false);
      totalIl=deltaCell(dF,dT,'il',false);
      totalBl=deltaCell(dF,dT,'bl',true);
    } else if(midOn&&dM&&dT){
      totalAb=deltaCell(dM,dT,'ab',false);
      totalIl=deltaCell(dM,dT,'il',false);
      totalBl=deltaCell(dM,dT,'bl',true);
    } else if(midOn&&dF&&dM){
      totalAb=deltaCell(dF,dM,'ab',false);
      totalIl=deltaCell(dF,dM,'il',false);
      totalBl=deltaCell(dF,dM,'bl',true);
    }

    html2+='<div class="card" style="margin-bottom:16px;border-top:3px solid '+col+'">'
      +'<div style="font-size:11px;color:var(--text2);font-weight:700;margin-bottom:4px;text-transform:uppercase;letter-spacing:.5px">Report Title</div>'
      +'<div style="font-size:15px;font-weight:800;color:'+col+';margin-bottom:12px">'+reportTitle+'</div>'
      +'<div style="display:flex;align-items:center;gap:8px;margin-bottom:12px">'
      +'<i class="ti ti-chart-bar" style="font-size:18px"></i>'
      +gEn+' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">'+gAr+'</span>'
      +' <span style="font-size:11px;background:var(--bg);color:var(--text2);padding:2px 8px;border-radius:8px;font-weight:600">'+filtLbl()+'</span>'
      +'</div>'
      +'<div style="overflow-x:auto"><table class="tbl" style="border:2px solid '+col+'">'
      +'<tr>'
      +'<th style="text-align:left;background:#1a2e5a;min-width:130px">Performance Levels<br><span style="color:#fca5a5;font-family:Tajawal,sans-serif;font-size:9px">\u0645\u0633\u062a\u0648\u064a\u0627\u062a \u0627\u0644\u0623\u062f\u0627\u0621</span></th>'
      +'<th style="text-align:center;background:#1565b0">Start<br><span style="font-size:9px;font-weight:400">'+sfO.en+'<br>'+yfO.label+' '+tls[tf]+'</span></th>'
      +midTh
      +'<th style="text-align:center;background:#1b5e20">End<br><span style="font-size:9px;font-weight:400">'+stO.en+'<br>'+ytO.label+' '+tls[tt]+'</span></th>'
      +'<th style="text-align:center;background:#374151">Total &#916;<br><span style="color:#fca5a5;font-family:Tajawal,sans-serif;font-size:9px">\u0645\u0624\u0634\u0631 \u0627\u0644\u062a\u0641\u064a\u064a\u0631\u0627\u062a</span></th>'
      +'</tr>'
      +'<tr class="above-row">'
      +'<td><strong>Above</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0645\u062a\u0641\u0648\u0642</span></td>'
      +'<td style="text-align:center">'+valCell(dF,'ab')+'</td>'
      +midColAb
      +'<td style="text-align:center">'+valCell(dT,'ab')+'</td>'
      +'<td style="text-align:center">'+totalAb+'</td>'
      +'</tr>'
      +'<tr class="inline-row">'
      +'<td><strong>In Line</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0645\u0637\u0627\u0628\u0642</span></td>'
      +'<td style="text-align:center">'+valCell(dF,'il')+'</td>'
      +midColIl
      +'<td style="text-align:center">'+valCell(dT,'il')+'</td>'
      +'<td style="text-align:center">'+totalIl+'</td>'
      +'</tr>'
      +'<tr class="below-row">'
      +'<td><strong>Below</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u062f\u0648\u0646 \u0627\u0644\u0645\u0633\u062a\u0648\u0649</span></td>'
      +'<td style="text-align:center">'+valCell(dF,'bl')+'</td>'
      +midColBl
      +'<td style="text-align:center">'+valCell(dT,'bl')+'</td>'
      +'<td style="text-align:center">'+totalBl+'</td>'
      +'</tr>'
      +'<tr style="background:#f8f9fa">'
      +'<td><strong>Judgment</strong> <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800;font-size:11px">\u0627\u0644\u062d\u0643\u0645</span></td>'
      +'<td style="text-align:center">'+jCell(dF)+'</td>'
      +midColJ
      +'<td style="text-align:center">'+jCell(dT)+'</td>'
      +'<td></td>'
      +'</tr>'
      +'</table></div>';

    if(!hasF||hasM===false||!hasT){
      var missingPoints=[];
      if(!hasF)missingPoints.push('Start Point (\u0646\u0642\u0637\u0629 \u0627\u0644\u0628\u062f\u0627\u064a\u0629)');
      if(midOn&&!hasM)missingPoints.push('Waypoint (\u0646\u0642\u0637\u0629 \u0627\u0644\u0645\u0631\u0648\u0631)');
      if(!hasT)missingPoints.push('End Point (\u0646\u0642\u0637\u0629 \u0627\u0644\u0648\u0635\u0648\u0644)');
      html2+='<div style="font-size:11px;color:#92400e;background:#fef3c7;border-radius:6px;padding:8px;margin-top:10px">'
        +'No Data is shown for: <strong>'+missingPoints.join(', ')+'</strong>'
        +' <span style="color:#c62828;font-family:Tajawal,sans-serif;font-weight:800"> \u0644\u0627 \u062a\u0648\u062c\u062f \u0628\u064a\u0627\u0646\u0627\u062a</span>'
        +'</div>';
    }

    if(hasF||hasM||hasT){
      html2+='<div class="cwrap"><div class="ctitle2">'+gEn+'</div>'
        +'<canvas id="ch-cmp-'+gId+'" height="130"></canvas></div>';
      chartQueue.push({id:gId,dF:dF,dM:dM,dT:dT});
    }

    html2+='<div class="arow">'
      +'<button class="btn btn-g btn-sm"><i class="ti ti-file-type-pdf"></i> PDF</button>'
      +'<button class="btn btn-o btn-sm"><i class="ti ti-table-export"></i> Excel</button>'
      +'<button class="btn btn-o btn-sm" onclick="window.print()"><i class="ti ti-printer"></i> Print</button>'
      +'</div></div>';
  }

  if(isPhaseMode){
    PHASE_GROUPS.forEach(function(grp){
      var gids=grp.grades.map(function(g){return g.id;});
      var phaseId='PHASE_'+gids.join(',');
      var fG=sfGradeRaw==='PHASE'?phaseId:sfGradeRaw;
      var mG=smGradeRaw==='PHASE'?phaseId:(midOn?smGradeRaw:phaseId);
      var tG=stGradeRaw==='PHASE'?phaseId:stGradeRaw;
      renderOne(grp.name,grp.nameAr,grp.key,fG,mG,tG);
    });
  } else {
    var gradesToShow=sfGradeRaw==='ALL'?GRADES:GRADES.filter(function(g){return g.id===sfGradeRaw;});
    gradesToShow.forEach(function(g){
      var fGradeId=sfGradeRaw==='ALL'?g.id:sfGradeRaw;
      var mGradeId=smGradeRaw==='ALL'?g.id:smGradeRaw;
      var tGradeId=stGradeRaw==='ALL'?g.id:stGradeRaw;
      renderOne(g.en,g.ar,g.id,fGradeId,mGradeId,tGradeId);
    });
  }

  el('cmpResult').innerHTML=html2;

  setTimeout(function(){
    chartQueue.forEach(function(item){
      var cv=el('ch-cmp-'+item.id);if(!cv)return;
      var lbls=['Above','In Line','Below'];
      var ds=[];
      if(item.dF)ds.push({label:'Start '+yfO.label,data:[item.dF.ab,item.dF.il,item.dF.bl],backgroundColor:'rgba(21,101,176,.5)',borderColor:'#1565b0',borderWidth:2,borderRadius:4});
      if(midOn&&item.dM)ds.push({label:'Waypoint',data:[item.dM.ab,item.dM.il,item.dM.bl],backgroundColor:'rgba(106,27,154,.4)',borderColor:'#6a1b9a',borderWidth:2,borderRadius:4});
      if(item.dT)ds.push({label:'End '+ytO.label,data:[item.dT.ab,item.dT.il,item.dT.bl],backgroundColor:'rgba(27,94,32,.5)',borderColor:'#1b5e20',borderWidth:2,borderRadius:4});
      if(!ds.length)return;
      new Chart(cv.getContext('2d'),{type:'bar',data:{labels:lbls,datasets:ds},
        options:{responsive:true,plugins:{legend:{labels:{font:{family:'Montserrat',weight:'600'}}}},
          scales:{y:{beginAtZero:true,max:100,ticks:{callback:function(v){return v+'%';}}}}}});
    });
  },100);
}

// ── CHARTS ──
function attachCharts(){
  var db=DB();
  GRADES.forEach(function(g){
    var cv=el('ch-'+g.id);if(!cv)return;
    var d=db[sel.s]&&db[sel.s][sel.y]&&db[sel.s][sel.y][sel.t]&&db[sel.s][sel.y][sel.t][g.id];
    if(!d)return; // grade card chart shows current entered values (saved or not) - this is fine for data entry view
    if(charts[g.id])charts[g.id].destroy();
    var isAtt=section==='att';
    charts[g.id]=new Chart(cv.getContext('2d'),{type:'bar',
      data:{labels:['Above','In Line','Below'],datasets:[{label:'%',data:[d.j.ab,d.j.il,d.j.bl],
        backgroundColor:['#2d7d46','#1565b0','#b71c1c'],borderRadius:5}]},
      options:{responsive:true,plugins:{legend:{display:false}},
        scales:{y:{beginAtZero:true,max:100,ticks:{callback:function(v){return v+'%';}}}}}});
  });
  var ov=el('ch-overview');
  if(ov&&sel.s&&sel.y&&sel.t){
    var db2=DB();var lb=[],ad=[],bd=[];
    GRADES.forEach(function(g){
      var d=db2[sel.s]&&db2[sel.s][sel.y]&&db2[sel.s][sel.y][sel.t]&&db2[sel.s][sel.y][sel.t][g.id];
      if(d&&d.saved){lb.push(g.en);ad.push(d.j.ab);bd.push(d.j.bl);}
    });
    new Chart(ov.getContext('2d'),{type:'bar',data:{labels:lb,datasets:[
      {label:'Above',data:ad,backgroundColor:'#2d7d46',borderRadius:4},
      {label:'Below',data:bd,backgroundColor:'#b71c1c',borderRadius:4}]},
      options:{responsive:true,scales:{y:{beginAtZero:true,max:100,ticks:{callback:function(v){return v+'%';}}}}}});
  }
}

// Fix for dashboard page routing
var pgDashOrig=pgDashboard;
function render(){
  charts={};var c=el('mainContent');
  if(cp==='home')c.innerHTML=pgHome();
  else if(cp==='years')c.innerHTML=pgYears();
  else if(cp==='terms')c.innerHTML=pgTerms();
  else if(cp==='data')c.innerHTML=pgData();
  else if(cp==='compare')c.innerHTML=pgCompare();
  else if(cp==='dashboard')c.innerHTML=pgDashboard();
  setTimeout(attachCharts,150);
}
</script>
</body>
</html>
