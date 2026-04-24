
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OBE — D4 Teknik Listrik | Politeknik Caltex Riau</title>
<meta name="description" content="Outcome-Based Education: Peta Kurikulum Program Studi D4 Teknik Listrik Politeknik Caltex Riau — PEO, Profil Lulusan, dan CPL">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
:root {
  --bg:      #020c1a;
  --bg2:     #041020;
  --card:    #06172e;
  --card2:   #081d38;
  --border:  #0e2540;
  --border2: #163660;
  --gold:    #c8921a;
  --gold-l:  #e8b84a;
  --gold-xl: #ffd878;
  --teal:    #0fa880;
  --teal-l:  #2ed4a8;
  --rose:    #c8364a;
  --rose-l:  #f0667a;
  --amber:   #d47820;
  --amber-l: #f0a840;
  --sky:     #1878e0;
  --sky-l:   #58a8f8;
  --violet:  #7848d8;
  --violet-l:#a878f8;
  --text:    #b8c8e0;
  --text2:   #d8e8f8;
  --muted:   #486080;
  --white:   #eaf2ff;
  --ff-d: 'Libre Baskerville', Georgia, serif;
  --ff-b: 'Outfit', sans-serif;
  --r: 14px;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--ff-b);font-weight:300;line-height:1.6;overflow-x:hidden}

/* AMBIENT */
.ambient{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.orb{position:absolute;border-radius:50%}
.o1{width:900px;height:900px;top:-300px;left:-300px;background:radial-gradient(circle,rgba(200,146,26,.05) 0%,transparent 65%);animation:f1 22s ease-in-out infinite alternate}
.o2{width:700px;height:700px;bottom:-200px;right:-100px;background:radial-gradient(circle,rgba(15,168,128,.05) 0%,transparent 65%);animation:f2 28s ease-in-out infinite alternate}
.o3{width:500px;height:500px;top:40%;left:60%;background:radial-gradient(circle,rgba(24,120,224,.04) 0%,transparent 65%);animation:f3 18s ease-in-out infinite alternate}
@keyframes f1{from{transform:translate(0,0)}to{transform:translate(80px,80px)}}
@keyframes f2{from{transform:translate(0,0)}to{transform:translate(-70px,-50px)}}
@keyframes f3{from{transform:translate(0,0)}to{transform:translate(-40px,60px)}}

/* NAV */
nav{position:fixed;top:0;left:0;right:0;z-index:600;display:flex;align-items:center;justify-content:space-between;padding:0 40px;height:64px;background:rgba(2,12,26,.92);backdrop-filter:blur(24px);border-bottom:1px solid var(--border)}
.nav-brand{display:flex;align-items:center;gap:12px}
.nav-logo{width:36px;height:36px;border-radius:8px;background:linear-gradient(135deg,var(--gold),var(--gold-l));display:flex;align-items:center;justify-content:center;font-family:var(--ff-d);font-size:12px;font-weight:700;color:#020c1a;flex-shrink:0}
.nav-main{font-size:13px;font-weight:100;color:var(--white);line-height:1.2}
.nav-sub{font-size:10px;color:var(--muted);letter-spacing:.5px}
.nav-links{display:flex;gap:4px}
.nav-links a{color:var(--muted);font-size:12px;font-weight:500;text-decoration:none;letter-spacing:.8px;text-transform:uppercase;padding:6px 12px;border-radius:6px;transition:color .2s,background .2s}
.nav-links a:hover{color:var(--white);background:rgba(255,255,255,.05)}
.nav-obe{padding:5px 12px;border-radius:6px;font-size:10.5px;font-weight:600;letter-spacing:1px;text-transform:uppercase;background:rgba(200,146,26,.12);color:var(--gold-l);border:1px solid rgba(200,146,26,.25)}

/* HERO */
.hero{position:relative;z-index:1;min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:100px 40px 80px;overflow:hidden}
.hero::before{content:'';position:absolute;inset:0;background-image:linear-gradient(rgba(200,146,26,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(200,146,26,.035) 1px,transparent 1px);background-size:48px 48px;mask-image:radial-gradient(ellipse 80% 90% at 50% 50%,black 10%,transparent 75%)}
.hero::after{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--border2),transparent)}
.h-inst{display:inline-flex;align-items:center;gap:8px;font-size:11px;font-weight:500;letter-spacing:3px;text-transform:uppercase;color:var(--gold);padding:6px 16px;border-radius:40px;border:1px solid rgba(200,146,26,.25);background:rgba(200,146,26,.06);margin-bottom:28px;opacity:0;animation:fu .8s .1s forwards}
.h-inst::before{content:'';width:6px;height:6px;border-radius:50%;background:var(--gold);box-shadow:0 0 8px var(--gold)}
.h-title{font-family:var(--ff-d);font-size:clamp(40px,7.5vw,86px);font-weight:700;line-height:1;color:var(--white);opacity:0;animation:fu .8s .3s forwards}
.h-title em{font-style:italic;color:var(--gold-l)}
.h-title .sub{display:block;font-size:clamp(22px,4vw,46px);font-weight:400;font-style:italic;color:var(--teal-l);margin-top:8px}
.h-desc{font-size:clamp(13px,2vw,15px);color:var(--muted);max-width:600px;margin:32px auto 0;line-height:1.85;opacity:0;animation:fu .8s .5s forwards}
.h-pills{display:flex;align-items:center;justify-content:center;gap:8px;flex-wrap:wrap;margin-top:40px;opacity:0;animation:fu .8s .7s forwards}
.pill{display:flex;align-items:center;gap:6px;padding:7px 16px;border-radius:40px;font-size:11.5px;font-weight:500;border:1px solid}
.p-g{color:var(--gold-l);border-color:rgba(200,146,26,.3);background:rgba(200,146,26,.07)}
.p-t{color:var(--teal-l);border-color:rgba(15,168,128,.3);background:rgba(15,168,128,.07)}
.p-r{color:var(--rose-l);border-color:rgba(200,54,74,.3);background:rgba(200,54,74,.07)}
.p-s{color:var(--sky-l);border-color:rgba(24,120,224,.3);background:rgba(24,120,224,.07)}
.p-v{color:var(--violet-l);border-color:rgba(120,72,216,.3);background:rgba(120,72,216,.07)}
.p-a{color:var(--amber-l);border-color:rgba(212,120,32,.3);background:rgba(212,120,32,.07)}
.pdot{width:4px;height:4px;border-radius:50%;background:var(--border2);flex-shrink:0}
.obe-flow{margin-top:52px;opacity:0;animation:fu .8s .9s forwards}
.obe-flow-inner{display:inline-flex;border:1px solid var(--border2);border-radius:50px;overflow:hidden;font-size:11px;font-weight:600;letter-spacing:1px;text-transform:uppercase}
.fs{padding:10px 20px;border-right:1px solid var(--border2);transition:background .2s}
.fs:last-child{border-right:none}
.fs:hover{background:rgba(255,255,255,.04)}
.fs1{color:var(--gold-l)}.fs2{color:var(--teal-l)}.fs3{color:var(--sky-l)}.fs4{color:var(--rose-l)}
.fa{color:var(--muted);padding:10px 10px;border-right:1px solid var(--border2);font-size:12px}
.h-scroll{margin-top:56px;opacity:0;animation:fu .8s 1.1s forwards;display:flex;flex-direction:column;align-items:center;gap:8px}
.h-scroll span{font-size:9px;letter-spacing:4px;text-transform:uppercase;color:var(--muted)}
.sbar{width:1px;height:48px;background:linear-gradient(to bottom,var(--gold),transparent);animation:sp 2s ease-in-out infinite}
@keyframes sp{0%,100%{opacity:.3}50%{opacity:1}}
@keyframes fu{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:translateY(0)}}

/* WRAPPER */
.wrap{position:relative;z-index:1;max-width:1200px;margin:0 auto;padding:0 32px 120px}

/* STATS */
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(130px,1fr));gap:1px;background:var(--border);border:1px solid var(--border);border-radius:16px;overflow:hidden;margin-bottom:80px}
.sc{background:var(--card);padding:28px 20px;text-align:center;transition:background .2s}
.sc:hover{background:var(--card2)}
.sv{font-family:var(--ff-d);font-size:46px;font-weight:700;line-height:1;margin-bottom:6px;display:block}
.sc:nth-child(1) .sv{color:var(--gold-l)}
.sc:nth-child(2) .sv{color:var(--teal-l)}
.sc:nth-child(3) .sv{color:var(--rose-l)}
.sc:nth-child(4) .sv{color:var(--sky-l)}
.sc:nth-child(5) .sv{color:var(--amber-l)}
.sl{font-size:10.5px;font-weight:400;color:var(--muted);line-height:1.4}

/* SECTION */
.sec{margin-bottom:88px}
.sh{display:flex;align-items:flex-end;gap:16px;margin-bottom:36px;padding-bottom:16px;border-bottom:1px solid var(--border)}
.sn{font-family:var(--ff-d);font-size:56px;font-weight:400;font-style:italic;color:var(--border2);line-height:1;flex-shrink:0}
.sk{font-size:9.5px;font-weight:600;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:4px}
.st{font-family:var(--ff-d);font-size:clamp(20px,3vw,28px);font-weight:700;color:var(--white);line-height:1.2}
.st span{color:var(--gold-l);font-style:italic}

/* OBE INFO */
.obe-grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px;margin-bottom:36px}
.ob{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:20px;position:relative;overflow:hidden}
.ob::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--gold),var(--teal-l))}
.ob-ico{font-size:22px;margin-bottom:10px}
.ob h4{font-size:13px;font-weight:600;color:var(--white);margin-bottom:6px}
.ob p{font-size:11.5px;color:var(--muted);line-height:1.6}

/* PEO */
.peo-g{display:grid;grid-template-columns:repeat(auto-fill,minmax(350px,1fr));gap:20px}
.pc{background:var(--card);border:1px solid var(--border);border-radius:var(--r);padding:30px;position:relative;overflow:hidden;transition:transform .3s,box-shadow .3s,border-color .3s}
.pc:hover{transform:translateY(-5px);box-shadow:0 24px 60px rgba(0,0,0,.5)}
.pc::before{content:'';position:absolute;top:0;left:0;right:0;height:3px}
.pc::after{content:attr(data-n);position:absolute;bottom:-10px;right:16px;font-family:var(--ff-d);font-size:100px;font-weight:700;font-style:italic;color:rgba(255,255,255,.03);line-height:1;pointer-events:none;user-select:none}
.c1::before{background:linear-gradient(90deg,var(--gold),var(--amber-l))}.c1:hover{border-color:rgba(200,146,26,.35)}
.c2::before{background:linear-gradient(90deg,var(--teal),var(--teal-l))}.c2:hover{border-color:rgba(15,168,128,.35)}
.c3::before{background:linear-gradient(90deg,var(--rose),var(--rose-l))}.c3:hover{border-color:rgba(200,54,74,.35)}
.pt{display:inline-flex;align-items:center;gap:6px;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;padding:4px 12px;border-radius:4px;margin-bottom:14px}
.c1 .pt{background:rgba(200,146,26,.12);color:var(--gold-l)}
.c2 .pt{background:rgba(15,168,128,.12);color:var(--teal-l)}
.c3 .pt{background:rgba(200,54,74,.12);color:var(--rose-l)}
.pc h3{font-family:var(--ff-d);font-size:18px;font-weight:700;color:var(--white);margin-bottom:12px;line-height:1.3}
.pc p{font-size:12.5px;color:var(--muted);line-height:1.75}

/* PROFIL */
.pr-g{display:grid;grid-template-columns:repeat(auto-fill,minmax(500px,1fr));gap:20px}
.prc{background:var(--card);border:1px solid var(--border);border-radius:var(--r);padding:32px;position:relative;overflow:hidden;transition:transform .3s,box-shadow .3s,border-color .3s}
.prc:hover{transform:translateY(-4px);box-shadow:0 24px 60px rgba(0,0,0,.5)}
.prc::after{content:attr(data-n);position:absolute;bottom:-20px;right:20px;font-family:var(--ff-d);font-size:120px;font-weight:700;line-height:1;color:rgba(255,255,255,.025);pointer-events:none}
.pr1{border-top:3px solid var(--sky)}.pr1:hover{border-color:rgba(24,120,224,.4);border-top-color:var(--sky-l)}
.pr2{border-top:3px solid var(--violet)}.pr2:hover{border-color:rgba(120,72,216,.4);border-top-color:var(--violet-l)}
.prn{font-family:var(--ff-d);font-size:11px;font-style:italic;color:var(--muted);margin-bottom:8px;letter-spacing:1px}
.prr{font-size:10px;font-weight:700;letter-spacing:3px;text-transform:uppercase;margin-bottom:10px}
.pr1 .prr{color:var(--sky-l)}.pr2 .prr{color:var(--violet-l)}
.prc h3{font-family:var(--ff-d);font-size:20px;font-weight:700;color:var(--white);line-height:1.3;margin-bottom:14px}
.prc p{font-size:12.5px;color:var(--muted);line-height:1.75;margin-bottom:20px}
.prtags{display:flex;flex-wrap:wrap;gap:6px}
.prtag{font-size:10px;font-weight:500;padding:3px 10px;border-radius:4px;border:1px solid}
.pr1 .prtag{color:var(--sky-l);border-color:rgba(24,120,224,.25);background:rgba(24,120,224,.07)}
.pr2 .prtag{color:var(--violet-l);border-color:rgba(120,72,216,.25);background:rgba(120,72,216,.07)}

/* CPL TABS */
.tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:20px}
.tb{padding:8px 18px;border-radius:8px;font-size:12px;font-weight:500;cursor:pointer;border:1px solid var(--border);background:var(--card);color:var(--muted);transition:all .2s;user-select:none}
.tb:hover{color:var(--rose);border-color:var(--border2)}
.tb.a{color:var(--white);border-color:var(--gold);background:rgba(200,146,26,.08);box-shadow:0 0 14px rgba(200,146,26,.12)}
.tp{display:none}
.tp.a{display:block;animation:fi .25s ease}
@keyframes fi{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}

.cr{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:22px 24px;margin-bottom:10px;display:grid;grid-template-columns:52px 1fr auto;gap:18px;align-items:start;position:relative;overflow:hidden;transition:border-color .2s,transform .2s}
.cr:hover{border-color:var(--border2);transform:translateX(4px)}
.cr::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px}
.ds .cr::before{background:var(--teal)}
.du .cr::before{background:var(--sky)}
.dp .cr::before{background:var(--gold)}
.dk .cr::before{background:var(--rose)}
.cnb{width:52px;height:52px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-family:var(--ff-d);font-size:20px;font-weight:700;flex-shrink:0}
.ds .cnb{background:rgba(15,168,128,.1);color:var(--teal-l)}
.du .cnb{background:rgba(24,120,224,.1);color:var(--sky-l)}
.dp .cnb{background:rgba(200,146,26,.1);color:var(--gold-l)}
.dk .cnb{background:rgba(200,54,74,.1);color:var(--rose-l)}
.cb h4{font-size:13.5px;font-weight:600;color:var(--white);margin-bottom:5px}
.cb p{font-size:12px;color:var(--muted);line-height:1.65}
.ccs{display:flex;flex-direction:column;gap:4px;flex-shrink:0}
.ch{font-size:9px;font-weight:700;letter-spacing:1px;text-transform:uppercase;padding:3px 8px;border-radius:4px;border:1px solid;white-space:nowrap}
.c-p1{color:var(--gold-l);border-color:rgba(200,146,26,.3);background:rgba(200,146,26,.07)}
.c-p2{color:var(--teal-l);border-color:rgba(15,168,128,.3);background:rgba(15,168,128,.07)}
.c-p3{color:var(--rose-l);border-color:rgba(200,54,74,.3);background:rgba(200,54,74,.07)}
.c-r1{color:var(--sky-l);border-color:rgba(24,120,224,.3);background:rgba(24,120,224,.07)}
.c-r2{color:var(--violet-l);border-color:rgba(120,72,216,.3);background:rgba(120,72,216,.07)}

/* DOMAIN */
.dg{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:16px;margin-bottom:88px}
.db{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:22px;overflow:hidden;position:relative;transition:transform .2s,border-color .2s}
.db:hover{transform:translateY(-3px);border-color:var(--border2)}
.dstr{position:absolute;top:0;left:0;bottom:0;width:3px}
.dst{background:var(--teal)}.dss{background:var(--sky)}.dsg{background:var(--gold)}.dsr{background:var(--rose)}
.dh{font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;margin-bottom:14px;padding-bottom:10px;border-bottom:1px solid var(--border)}
.dht{color:var(--teal-l)}.dhs{color:var(--sky-l)}.dhg{color:var(--gold-l)}.dhr{color:var(--rose-l)}
.di{display:flex;gap:10px;margin-bottom:9px;align-items:flex-start}
.di:last-child{margin-bottom:0}
.dtag{font-size:9px;font-weight:700;padding:3px 7px;border-radius:4px;flex-shrink:0;margin-top:1px}
.dtt{background:rgba(15,168,128,.14);color:var(--teal-l)}
.dts{background:rgba(24,120,224,.12);color:var(--sky-l)}
.dtg{background:rgba(200,146,26,.14);color:var(--gold-l)}
.dtr{background:rgba(200,54,74,.12);color:var(--rose-l)}
.dtxt{font-size:11.5px;color:var(--muted);line-height:1.5}

/* MATRIX */
.mwrap{overflow-x:auto;border-radius:14px;border:1px solid var(--border);box-shadow:0 12px 60px rgba(0,0,0,.5)}
table{width:100%;border-collapse:collapse;min-width:800px}
thead th{padding:16px 12px;text-align:center;font-size:10px;font-weight:700;letter-spacing:1.2px;text-transform:uppercase;background:var(--bg2);border-bottom:1px solid var(--border);position:sticky;top:0;z-index:3}
thead th.tlbl{text-align:left;min-width:185px;color:var(--muted)}
.th1{color:var(--gold-l)}.th2{color:var(--teal-l)}.th3{color:var(--rose-l)}.th4{color:var(--sky-l)}.th5{color:var(--violet-l)}
tbody tr{border-bottom:1px solid var(--border);transition:background .15s}
tbody tr:last-child{border-bottom:none}
tbody tr:hover{background:rgba(255,255,255,.02)}
td{padding:12px 10px;text-align:center;border-right:1px solid var(--border);vertical-align:middle}
td:last-child{border-right:none}
td.tdlbl{text-align:left;padding:14px 18px;background:rgba(255,255,255,.015)}
.cn2{font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:var(--muted);display:block;margin-bottom:3px}
.ctxt{font-size:12px;font-weight:500;color:var(--muted);display:block}
.csh{font-size:10.5px;color:var(--muted);margin-top:2px;display:block}
.mk{display:inline-flex;align-items:center;justify-content:center;width:32px;height:32px;border-radius:50%;font-size:13px;font-weight:700;transition:transform .18s;cursor:default}
.mk:hover{transform:scale(1.4)}
.mks{box-shadow:0 0 10px 2px currentColor}
.mkw{opacity:.35}
.mkn{opacity:0;pointer-events:none}
.mg{background:var(--gold);color:#020c1a}
.mt2{background:var(--teal);color:#020c1a}
.mr2{background:var(--rose);color:#fff}
.mb2{background:var(--sky);color:#fff}
.mv2{background:var(--violet);color:#fff}
.mgw{background:rgba(200,146,26,.14);color:var(--gold-l)}
.mtw{background:rgba(15,168,128,.14);color:var(--teal-l)}
.mrw{background:rgba(200,54,74,.14);color:var(--rose-l)}
.mbw{background:rgba(24,120,224,.14);color:var(--sky-l)}
.mvw{background:rgba(120,72,216,.14);color:var(--violet-l)}
[data-tip]{position:relative}
[data-tip]:hover::after{content:attr(data-tip);position:absolute;bottom:calc(100% + 10px);left:50%;transform:translateX(-50%);background:#0a1a30;border:1px solid var(--border2);border-radius:8px;padding:10px 14px;font-family:var(--ff-b);font-size:11.5px;color:var(--text);width:230px;line-height:1.55;z-index:500;pointer-events:none;white-space:normal;box-shadow:0 12px 40px rgba(0,0,0,.7)}

/* FOOTER */
footer{position:relative;z-index:1;background:var(--card);border-top:1px solid var(--border)}
.ft{display:grid;grid-template-columns:1fr auto 1fr;gap:40px;align-items:start;padding:48px 60px 32px;max-width:1200px;margin:0 auto}
.fb-logo{display:flex;align-items:center;gap:10px;margin-bottom:10px}
.fb-icon{width:32px;height:32px;border-radius:6px;background:linear-gradient(135deg,var(--gold),var(--gold-l));display:flex;align-items:center;justify-content:center;font-family:var(--ff-d);font-size:12px;font-weight:700;color:#020c1a}
.fb-name{font-size:14px;font-weight:600;color:var(--white)}
.fb p{font-size:12px;color:var(--muted);line-height:1.6;max-width:260px}
.fdiv{width:1px;background:var(--border);align-self:stretch}
.fobe .fobl{font-size:9.5px;font-weight:700;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:6px;display:block}
.fobe .fobt{font-family:var(--ff-d);font-size:22px;font-weight:700;font-style:italic;color:var(--white);line-height:1.2}
.fobe p{font-size:11.5px;color:var(--muted);margin-top:6px}
.fbot{border-top:1px solid var(--border);padding:16px 60px;display:flex;align-items:center;justify-content:space-between;max-width:1200px;margin:0 auto}
.fcp{font-size:11px;color:var(--muted)}
.fn{display:flex;gap:20px}
.fn a{font-size:11px;color:var(--muted);text-decoration:none;transition:color .2s}
.fn a:hover{color:var(--white)}

/* REVEAL */
.rv{opacity:0;transform:translateY(28px);transition:opacity .65s ease,transform .65s ease}
.rv.vi{opacity:1;transform:translateY(0)}

/* RESPONSIVE */
@media(max-width:768px){
  nav{padding:0 20px}
  .nav-links,.nav-obe{display:none}
  .wrap{padding:0 18px 80px}
  .pr-g{grid-template-columns:1fr}
  .obe-grid{grid-template-columns:1fr}
  .cr{grid-template-columns:48px 1fr}
  .ccs{flex-direction:row;flex-wrap:wrap;grid-column:1/-1}
  .ft{grid-template-columns:1fr}
  .fdiv{display:none}
  .fobe{text-align:left}
  .fbot{flex-direction:column;gap:10px}
  .obe-flow-inner{flex-wrap:wrap;border-radius:12px}
}
</style>
</head>
<body>

<div class="ambient">
  <div class="orb o1"></div>
  <div class="orb o2"></div>
  <div class="orb o3"></div>
</div>

<nav>
  <div class="nav-brand">
    <div class="nav-logo">PCR</div>
    <div>
      <div class="nav-main">D4 Teknik Listrik</div>
      <div class="nav-sub">Politeknik Caltex Riau</div>
    </div>
  </div>
  <div class="nav-links">
    <a href="#peo">PEO</a>
    <a href="#profil">Profil</a>
    <a href="#cpl">CPL</a>
    <a href="#domain">Domain</a>
    <a href="#matriks">Matriks</a>
  </div>
  <div class="nav-obe">OBE Framework</div>
</nav>

<section class="hero">
  <div class="h-inst">Politeknik Caltex Riau &mdash; D4 Teknik Listrik</div>
  <h1 class="h-title">
    <em>Outcome-Based</em>
    <span class="sub">Education Curriculum</span>
  </h1>
  <p class="h-desc">
    Peta kurikulum berbasis OBE Program Studi Sarjana Terapan D4 Teknik Listrik
    Politeknik Caltex Riau &mdash; menghubungkan Program Educational Objectives,
    Profil Lulusan, dan Capaian Pembelajaran Lulusan secara komprehensif dan sistematis.
  </p>
  <div class="h-pills">
    <span class="pill p-g">3 PEO</span>
    <div class="pdot"></div>
    <span class="pill p-s">2 Profil Lulusan</span>
    <div class="pdot"></div>
    <span class="pill p-t">10 CPL</span>
    <div class="pdot"></div>
    <span class="pill p-a">4 Domain Kompetensi</span>
    <div class="pdot"></div>
    <span class="pill p-r">K3 &amp; Berkelanjutan</span>
    <div class="pdot"></div>
    <span class="pill p-v">Berdaya Saing Global</span>
  </div>
  <div class="obe-flow">
    <div class="obe-flow-inner">
      <div class="fs fs1">Define Outcomes</div>
      <div class="fa">→</div>
      <div class="fs fs2">Align Curriculum</div>
      <div class="fa">→</div>
      <div class="fs fs3">Deliver &amp; Assess</div>
      <div class="fa">→</div>
      <div class="fs fs4">Continuous Improvement</div>
    </div>
  </div>
  <div class="h-scroll">
    <span>Scroll untuk menjelajahi</span>
    <div class="sbar"></div>
  </div>
</section>

<div class="wrap">

<!-- STATS -->
<div class="stats rv">
  <div class="sc"><span class="sv">3</span><div class="sl">Program Educational<br>Objectives (PEO)</div></div>
  <div class="sc"><span class="sv">2</span><div class="sl">Profil Lulusan<br>Unggulan</div></div>
  <div class="sc"><span class="sv">10</span><div class="sl">Capaian Pembelajaran<br>Lulusan (CPL)</div></div>
  <div class="sc"><span class="sv">4</span><div class="sl">Domain<br>Kompetensi</div></div>
  <div class="sc"><span class="sv">D4</span><div class="sl">Sarjana Terapan<br>Teknik Listrik</div></div>
</div>

<!-- OBE INTRO -->
<section class="sec rv">
  <div class="sh">
    <div class="sn">00</div>
    <div><div class="sk">Pendekatan Kurikulum</div><div class="st">Outcome-Based <span>Education</span></div></div>
  </div>
  <div class="obe-grid">
    <div class="ob"><div class="ob-ico">🎯</div><h4>Apa itu OBE?</h4><p>Outcome-Based Education (OBE) adalah pendekatan kurikulum yang berfokus pada hasil akhir pembelajaran. Seluruh desain, pengajaran, dan penilaian diarahkan untuk mencapai kompetensi yang telah ditetapkan sesuai kebutuhan industri dan masyarakat.</p></div>
    <div class="ob"><div class="ob-ico">🔗</div><h4>Keterkaitan PEO–CPL</h4><p>PEO mendefinisikan tujuan program jangka panjang (3–5 tahun setelah lulus), Profil Lulusan menggambarkan peran karir, dan CPL merumuskan kompetensi spesifik yang harus dicapai mahasiswa saat lulus.</p></div>
    <div class="ob"><div class="ob-ico">🔄</div><h4>Continuous Improvement</h4><p>OBE mendorong evaluasi dan perbaikan kurikulum secara berkelanjutan berdasarkan capaian mahasiswa (CPS) dan umpan balik dari pemangku kepentingan industri, alumni, dan pengguna lulusan.</p></div>
  </div>
</section>

<!-- PEO -->
<section class="sec" id="peo">
  <div class="sh rv">
    <div class="sn">01</div>
    <div><div class="sk">Program Educational Objectives</div><div class="st">Tujuan <span>Program</span></div></div>
  </div>
  <div class="peo-g">
    <div class="pc c1 rv" data-n="1">
      <div class="pt">⚡ PEO 1 &mdash; Kompetensi Teknik</div>
      <h3>Engineer Profesional Berkompetensi Teknik Tinggi</h3>
      <p>Sarjana Terapan yang mampu bekerja sebagai Engineer Profesional Ketenagalistrikan dengan menguasai dan menerapkan prinsip-prinsip teknik ketenagalistrikan yang dilandasi ilmu dasar rekayasa, meliputi perancangan, instalasi, proteksi, otomasi, pemeliharaan, serta pengoperasian sistem tenaga listrik, sesuai standar K3 dan prinsip pembangunan berkelanjutan, serta mampu menghasilkan solusi teknik yang inovatif dan berdaya saing.</p>
    </div>
    <div class="pc c2 rv" data-n="2">
      <div class="pt">🎯 PEO 2 &mdash; Karakter &amp; Etika</div>
      <h3>Pemimpin Berkarakter Unggul, Inovatif &amp; Adaptif</h3>
      <p>Lulusan yang mampu menjalankan peran sebagai Engineer Profesional Ketenagalistrikan dengan menjunjung tinggi nilai-nilai Pancasila, etika akademik, etika profesi, nilai-nilai IDEAL, jiwa kepemimpinan, tanggung jawab, kerja sama tim, dan komunikasi efektif, serta memiliki karakter unggul, inovatif, dan adaptif dalam mendorong inovasi solusi teknis untuk peningkatan berkelanjutan di bidang ketenagalistrikan.</p>
    </div>
    <div class="pc c3 rv" data-n="3">
      <div class="pt">🌐 PEO 3 &mdash; Daya Saing Global</div>
      <h3>Kompetitor Tangguh di Tingkat Nasional &amp; Global</h3>
      <p>Lulusan yang mampu bersaing di tingkat nasional maupun global sebagai Engineer Profesional Ketenagalistrikan dengan kompetensi troubleshooting, optimalisasi, dan pemeliharaan sistem tenaga listrik di lingkungan industri, serta kemampuan mengadopsi dan mengimplementasikan teknologi ketenagalistrikan terkini secara efektif dan efisien untuk menjamin keandalan, keselamatan, dan keberlanjutan operasi sistem tenaga listrik.</p>
    </div>
  </div>
</section>

<!-- PROFIL LULUSAN -->
<section class="sec" id="profil">
  <div class="sh rv">
    <div class="sn">02</div>
    <div><div class="sk">Graduate Profile</div><div class="st">Profil <span>Lulusan</span></div></div>
  </div>
  <div class="pr-g">
    <div class="prc pr1 rv" data-n="1">
      <div class="prn">Profil Lulusan &middot; 01</div>
      <div class="prr">Electrical Systems Designer &amp; Operational Engineer</div>
      <h3>Electrical Systems Designer<br>&amp; Operational Engineer</h3>
      <p>Lulusan Sarjana Terapan yang mampu merencanakan, merancang, dan mengoperasikan sistem tenaga listrik meliputi instalasi, proteksi, dan otomasi industri sesuai standar teknik yang berlaku, serta mampu menganalisis, mendiagnosis, dan mengoptimalkan kinerja sistem tenaga listrik secara komprehensif, dengan menjunjung tinggi nilai etika, integritas, profesionalisme, kepemimpinan, dan komunikasi efektif untuk menghasilkan solusi teknik yang inovatif dan berdaya saing global.</p>
      <div class="prtags">
        <span class="prtag">Perancangan Sistem</span><span class="prtag">Proteksi</span><span class="prtag">Otomasi Industri</span><span class="prtag">Analisis &amp; Diagnosa</span><span class="prtag">Kepemimpinan</span><span class="prtag">Solusi Inovatif</span><span class="prtag">Berdaya Saing Global</span>
      </div>
    </div>
    <div class="prc pr2 rv" data-n="2">
      <div class="prn">Profil Lulusan &middot; 02</div>
      <div class="prr">Electrical Installation, Automation &amp; Maintenance Engineer</div>
      <h3>Electrical Installation, Automation<br>&amp; Maintenance Engineer</h3>
      <p>Lulusan Sarjana Terapan yang mampu menginstalasi, mengotomasi, dan memelihara sistem tenaga listrik secara sistematis, efektif, dan efisien sesuai standar teknik yang berlaku, serta mampu melakukan troubleshooting dan optimasi sistem di lapangan untuk menjamin keandalan, keselamatan, dan keberlanjutan operasi sistem tenaga listrik di industri, dengan memiliki karakter unggul, inovatif, dan adaptif.</p>
      <div class="prtags">
        <span class="prtag">Instalasi Sistem</span><span class="prtag">Troubleshooting</span><span class="prtag">Pemeliharaan</span><span class="prtag">Optimalisasi Lapangan</span><span class="prtag">Keandalan Sistem</span><span class="prtag">Karakter Inovatif</span><span class="prtag">Adaptif</span>
      </div>
    </div>
  </div>
</section>

<!-- CPL -->
<section class="sec" id="cpl">
  <div class="sh rv">
    <div class="sn">03</div>
    <div><div class="sk">Student Outcomes / Program Outcomes</div><div class="st">Capaian Pembelajaran <span>Lulusan</span></div></div>
  </div>
  <div class="tabs rv">
    <div class="tb a" onclick="showTab('all',this)">Semua CPL</div>
    <div class="tb" onclick="showTab('sikap',this)">🟢 Sikap &amp; Nilai</div>
    <div class="tb" onclick="showTab('umum',this)">🔵 Keterampilan Umum</div>
    <div class="tb" onclick="showTab('penget',this)">🟡 Pengetahuan Rekayasa</div>
    <div class="tb" onclick="showTab('khusus',this)">🔴 Keterampilan Khusus</div>
  </div>

  <div class="tp a" id="tp-all">
    <div class="cr ds"><div class="cnb">1</div><div class="cb"><h4>Sikap &amp; Nilai Kebangsaan</h4><p>Bertakwa kepada Tuhan YME, menjunjung nilai kemanusiaan, berkontribusi pada kemajuan bangsa berdasarkan Pancasila, cinta tanah air, menghargai keberagaman, taat hukum, menginternalisasi etika akademik, etika profesi, bertanggung jawab atas pekerjaannya, serta memiliki semangat kemandirian dan kewirausahaan dalam kehidupan bermasyarakat, berbangsa, dan bernegara.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p1">PEO 1</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr ds"><div class="cnb">2</div><div class="cb"><h4>Nilai IDEAL &amp; Berpikir Kritis</h4><p>Memiliki karakter yang menunjukkan pemahaman yang kuat pada nilai-nilai IDEAL (Integrity, Dignity, Excellence, Agility, dan Loyalty) yang mencerminkan sikap anti korupsi dan selaras dengan nilai budaya melayu, serta berperilaku sebagai pembelajar mandiri, kreatif dan mampu berpikir kritis.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr du"><div class="cnb">3</div><div class="cb"><h4>Komunikasi Efektif &amp; Kerja Tim Multidisiplin</h4><p>Kemampuan berkomunikasi tertulis, lisan, dan grafis secara efektif dan inklusif dengan berbagai komunitas dan lingkungan yang cukup luas, dengan mempertimbangkan perbedaan budaya, bahasa, dan pembelajaran, baik sebagai individu, anggota atau pemimpin yang bekerja dalam tim yang beragam, inklusif, dan multidisiplin dengan berbagai lingkungan kerja.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span></div></div>
    <div class="cr dp"><div class="cnb">4</div><div class="cb"><h4>Perancangan Sistem &amp; Pembangunan Berkelanjutan</h4><p>Kemampuan merancang sistem, komponen, ataupun proses sesuai dengan kebutuhan untuk menyelesaikan permasalahan yang telah dikenal secara luas dalam disiplin ilmunya, dengan mempertimbangkan aspek-aspek keselamatan dan kesehatan publik, lingkungan dan menerapkan prinsip pembangunan yang berkelanjutan.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span></div></div>
    <div class="cr dp"><div class="cnb">5</div><div class="cb"><h4>Ilmu Dasar &amp; Rekayasa Terapan</h4><p>Mampu mengidentifikasi dan menerapkan pengetahuan matematika, ilmu pengetahuan alam, komputasi, dasar-dasar rekayasa, dan atau ilmu-ilmu rekayasa khusus sesuai dengan disiplinnya terhadap prosedur, proses, sistem, ataupun metodologi rekayasa terapan yang telah dikenal.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dp"><div class="cnb">6</div><div class="cb"><h4>Analisis &amp; Pemodelan Sistem Tenaga Listrik</h4><p>Mampu menerapkan pengetahuan ilmu dasar rekayasa ketenagalistrikan untuk menganalisis, memodelkan, dan memecahkan permasalahan teknis pada sistem tenaga listrik secara sistematis, terstandar, dan sesuai dengan prosedur rekayasa terapan yang berlaku di industri.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dk"><div class="cnb">7</div><div class="cb"><h4>Rancang, Instalasi, Proteksi, Otomasi &amp; Operasi Sistem</h4><p>Mampu merancang, menginstalasi, memproteksi, mengotomasi, dan mengoperasikan sistem tenaga listrik secara komprehensif sesuai standar teknik yang berlaku, serta mampu menganalisis dan mengoptimalkan kinerja sistem tenaga listrik untuk menghasilkan solusi teknik yang inovatif, aman, dan berdaya saing di tingkat nasional maupun global, dengan memastikan keselamatan kerja dan keandalan sistem selama siklus operasi berlangsung.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dk"><div class="cnb">8</div><div class="cb"><h4>Troubleshooting, Pemeliharaan &amp; Optimalisasi Industri</h4><p>Mampu melakukan troubleshooting, pemeliharaan, dan optimalisasi sistem tenaga listrik di lingkungan industri secara sistematis, efektif, dan efisien sesuai standar teknik yang berlaku, guna menjamin keandalan, keselamatan, dan keberlanjutan operasi sistem tenaga listrik, serta mampu menerapkan solusi teknis yang tepat di lapangan berdasarkan hasil diagnosis permasalahan nyata.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dk"><div class="cnb">9</div><div class="cb"><h4>Adopsi &amp; Implementasi Teknologi Ketenagalistrikan Terkini</h4><p>Mampu mengadopsi, mengevaluasi, dan mengimplementasikan teknologi ketenagalistrikan terkini secara efektif dan efisien di lingkungan industri dengan menilai kelayakan dan kesesuaian teknologi terhadap kebutuhan sistem, serta mampu mengintegrasikan inovasi teknologi ke dalam solusi operasional sistem tenaga listrik yang berkelanjutan dan berdaya saing di tingkat nasional maupun global.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr du"><div class="cnb">10</div><div class="cb"><h4>Profesionalisme &amp; Kepemimpinan Engineer Profesional</h4><p>Mampu menjalankan peran sebagai Engineer Profesional Ketenagalistrikan dengan menjunjung tinggi integritas, tanggung jawab profesional, semangat kerja sama tim, dan jiwa kepemimpinan yang efektif, serta mampu mendorong inovasi teknis dan peningkatan berkelanjutan di bidang ketenagalistrikan melalui pendekatan yang etis, kolaboratif, dan berorientasi pada dampak nyata di industri dan masyarakat.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
  </div>

  <div class="tp" id="tp-sikap">
    <div class="cr ds"><div class="cnb">1</div><div class="cb"><h4>Sikap &amp; Nilai Kebangsaan</h4><p>Bertakwa kepada Tuhan YME, menjunjung nilai kemanusiaan, berkontribusi pada kemajuan bangsa berdasarkan Pancasila, cinta tanah air, menghargai keberagaman, taat hukum, menginternalisasi etika akademik, etika profesi, bertanggung jawab atas pekerjaannya, serta memiliki semangat kemandirian dan kewirausahaan.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p1">PEO 1</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr ds"><div class="cnb">2</div><div class="cb"><h4>Nilai IDEAL &amp; Berpikir Kritis</h4><p>Memiliki karakter dengan pemahaman kuat pada nilai-nilai IDEAL (Integrity, Dignity, Excellence, Agility, dan Loyalty), mencerminkan sikap anti korupsi dan selaras dengan nilai budaya melayu, serta berperilaku sebagai pembelajar mandiri, kreatif dan mampu berpikir kritis.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
  </div>

  <div class="tp" id="tp-umum">
    <div class="cr du"><div class="cnb">3</div><div class="cb"><h4>Komunikasi Efektif &amp; Kerja Tim Multidisiplin</h4><p>Kemampuan berkomunikasi tertulis, lisan, dan grafis secara efektif dan inklusif, mempertimbangkan perbedaan budaya, bahasa, dan pembelajaran, sebagai individu, anggota atau pemimpin dalam tim yang beragam, inklusif, dan multidisiplin dengan berbagai lingkungan kerja.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span></div></div>
    <div class="cr du"><div class="cnb">10</div><div class="cb"><h4>Profesionalisme &amp; Kepemimpinan Engineer Profesional</h4><p>Mampu menjalankan peran sebagai Engineer Profesional dengan menjunjung tinggi integritas, tanggung jawab profesional, kerja sama tim, dan jiwa kepemimpinan yang efektif, serta mendorong inovasi teknis melalui pendekatan etis, kolaboratif, dan berorientasi dampak nyata di industri dan masyarakat.</p></div><div class="ccs"><span class="ch c-p2">PEO 2</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
  </div>

  <div class="tp" id="tp-penget">
    <div class="cr dp"><div class="cnb">4</div><div class="cb"><h4>Perancangan Sistem &amp; Pembangunan Berkelanjutan</h4><p>Kemampuan merancang sistem, komponen, atau proses sesuai kebutuhan, mempertimbangkan aspek K3 publik, lingkungan, dan menerapkan prinsip pembangunan yang berkelanjutan.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span></div></div>
    <div class="cr dp"><div class="cnb">5</div><div class="cb"><h4>Ilmu Dasar &amp; Rekayasa Terapan</h4><p>Mampu mengidentifikasi dan menerapkan pengetahuan matematika, IPA, komputasi, dasar-dasar rekayasa, dan ilmu rekayasa khusus terhadap prosedur, proses, sistem, atau metodologi rekayasa terapan yang telah dikenal.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dp"><div class="cnb">6</div><div class="cb"><h4>Analisis &amp; Pemodelan Sistem Tenaga Listrik</h4><p>Mampu menerapkan ilmu dasar rekayasa ketenagalistrikan untuk menganalisis, memodelkan, dan memecahkan permasalahan teknis pada sistem tenaga listrik secara sistematis, terstandar, sesuai prosedur rekayasa terapan industri.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
  </div>

  <div class="tp" id="tp-khusus">
    <div class="cr dk"><div class="cnb">7</div><div class="cb"><h4>Rancang, Instalasi, Proteksi, Otomasi &amp; Operasi Sistem</h4><p>Mampu merancang, menginstalasi, memproteksi, mengotomasi, dan mengoperasikan sistem tenaga listrik secara komprehensif, serta menganalisis dan mengoptimalkan kinerja sistem untuk menghasilkan solusi teknik inovatif, aman, dan berdaya saing global.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dk"><div class="cnb">8</div><div class="cb"><h4>Troubleshooting, Pemeliharaan &amp; Optimalisasi Industri</h4><p>Mampu melakukan troubleshooting, pemeliharaan, dan optimalisasi sistem tenaga listrik di lingkungan industri secara sistematis, efektif, efisien, guna menjamin keandalan, keselamatan, dan keberlanjutan operasi, serta menerapkan solusi teknis berdasarkan hasil diagnosis permasalahan nyata.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
    <div class="cr dk"><div class="cnb">9</div><div class="cb"><h4>Adopsi &amp; Implementasi Teknologi Terkini</h4><p>Mampu mengadopsi, mengevaluasi, dan mengimplementasikan teknologi ketenagalistrikan terkini, menilai kelayakan dan kesesuaian teknologi, serta mengintegrasikan inovasi teknologi ke dalam solusi operasional yang berkelanjutan dan berdaya saing nasional maupun global.</p></div><div class="ccs"><span class="ch c-p1">PEO 1</span><span class="ch c-p3">PEO 3</span><span class="ch c-r1">Profil 1</span><span class="ch c-r2">Profil 2</span></div></div>
  </div>
</section>

<!-- DOMAIN -->
<section class="sec" id="domain">
  <div class="sh rv">
    <div class="sn">04</div>
    <div><div class="sk">Klasifikasi Kompetensi</div><div class="st">Domain <span>CPL</span></div></div>
  </div>
  <div class="dg">
    <div class="db rv"><div class="dstr dst"></div><div class="dh dht">⬤ &nbsp;Sikap &amp; Tata Nilai</div><div class="di"><span class="dtag dtt">CPL 1</span><div class="dtxt">Ketakwaan, Pancasila, etika akademik &amp; profesi, tanggung jawab, kewirausahaan</div></div><div class="di"><span class="dtag dtt">CPL 2</span><div class="dtxt">Nilai IDEAL, anti korupsi, budaya Melayu, kreatif &amp; berpikir kritis</div></div></div>
    <div class="db rv"><div class="dstr dss"></div><div class="dh dhs">⬤ &nbsp;Keterampilan Umum</div><div class="di"><span class="dtag dts">CPL 3</span><div class="dtxt">Komunikasi efektif tertulis/lisan/grafis, kerja tim inklusif &amp; multidisiplin</div></div><div class="di"><span class="dtag dts">CPL 10</span><div class="dtxt">Profesionalisme, kepemimpinan, kolaborasi etis, inovasi berkelanjutan</div></div></div>
    <div class="db rv"><div class="dstr dsg"></div><div class="dh dhg">⬤ &nbsp;Pengetahuan Rekayasa</div><div class="di"><span class="dtag dtg">CPL 4</span><div class="dtxt">Perancangan sistem, K3 publik, prinsip pembangunan berkelanjutan</div></div><div class="di"><span class="dtag dtg">CPL 5</span><div class="dtxt">Matematika, IPA, komputasi, dasar &amp; ilmu rekayasa terapan</div></div><div class="di"><span class="dtag dtg">CPL 6</span><div class="dtxt">Analisis, pemodelan, dan pemecahan masalah teknis sistem tenaga</div></div></div>
    <div class="db rv"><div class="dstr dsr"></div><div class="dh dhr">⬤ &nbsp;Keterampilan Khusus</div><div class="di"><span class="dtag dtr">CPL 7</span><div class="dtxt">Rancang, instalasi, proteksi, otomasi, operasi sistem tenaga listrik</div></div><div class="di"><span class="dtag dtr">CPL 8</span><div class="dtxt">Troubleshooting, pemeliharaan, optimalisasi di lingkungan industri</div></div><div class="di"><span class="dtag dtr">CPL 9</span><div class="dtxt">Adopsi, evaluasi, implementasi teknologi ketenagalistrikan terkini</div></div></div>
  </div>
</section>

<!-- MATRIX -->
<section class="sec" id="matriks">
  <div class="sh rv">
    <div class="sn">05</div>
    <div><div class="sk">Curriculum Mapping</div><div class="st">Matriks <span>Keterkaitan</span></div></div>
  </div>
  <p style="font-size:12.5px;color:var(--muted);margin-bottom:18px" class="rv">● = hubungan kuat &nbsp;|&nbsp; ○ = hubungan parsial &nbsp;|&nbsp; Hover pada simbol untuk keterangan detail</p>
  <div class="mwrap rv">
  <table>
    <thead>
      <tr>
        <th class="tlbl">Capaian Pembelajaran Lulusan</th>
        <th class="th1">PEO 1<br><span style="font-weight:300;font-size:9px">Kompetensi Teknik</span></th>
        <th class="th2">PEO 2<br><span style="font-weight:300;font-size:9px">Karakter &amp; Etika</span></th>
        <th class="th3">PEO 3<br><span style="font-weight:300;font-size:9px">Daya Saing Global</span></th>
        <th class="th4">Profil 1<br><span style="font-weight:300;font-size:9px">Designer &amp; Ops</span></th>
        <th class="th1">Profil 2<br><span style="font-weight:300;font-size:9px">Install &amp; Maint</span></th>
      </tr>
    </thead>
    <tbody>
      <tr><td class="tdlbl"><span class="cn2">CPL 1</span><span class="ctxt">Sikap &amp; Nilai Kebangsaan</span><span class="csh">Pancasila, etika, kewirausahaan</span></td><td data-tip="Landasan karakter profesional seorang engineer yang bertanggung jawab."><span class="mk mkw mgw">○</span></td><td data-tip="CPL 1 inti PEO 2: nilai Pancasila, etika akademik & profesi, tanggung jawab."><span class="mk mks mt2">●</span></td><td data-tip="Integritas dari CPL 1 menjadi syarat bersaing di level global."><span class="mk mkw mrw">○</span></td><td data-tip="Profil 1 mensyaratkan integritas, etika, profesionalisme dari CPL 1."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 mensyaratkan karakter unggul yang berakar dari CPL 1."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 2</span><span class="ctxt">Nilai IDEAL &amp; Berpikir Kritis</span><span class="csh">Integrity, Dignity, Excellence, Agility, Loyalty</span></td><td data-tip="Excellence & Agility dalam CPL 2 mendukung inovasi teknis PEO 1."><span class="mk mkw mgw">○</span></td><td data-tip="CPL 2 langsung mendukung PEO 2 melalui nilai IDEAL dan anti korupsi."><span class="mk mks mt2">●</span></td><td data-tip="Agility & Excellence mendukung adaptasi teknologi dan daya saing global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 memerlukan inovasi & kepemimpinan yang dilandasi nilai IDEAL."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 memerlukan karakter inovatif & adaptif dari CPL 2."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 3</span><span class="ctxt">Komunikasi &amp; Kerja Tim</span><span class="csh">Multidisiplin, inklusif</span></td><td data-tip="Komunikasi dibutuhkan untuk menyampaikan solusi teknis kepada stakeholder."><span class="mk mkw mgw">○</span></td><td data-tip="CPL 3 inti PEO 2: komunikasi efektif dan kerja sama tim."><span class="mk mks mt2">●</span></td><td data-tip="Komunikasi lintas budaya penting untuk bersaing di level global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 mensyaratkan komunikasi efektif untuk kepemimpinan dan koordinasi."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 memerlukan komunikasi lintas tim dalam operasi lapangan."><span class="mk mkw mvw">○</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 4</span><span class="ctxt">Perancangan Sistem</span><span class="csh">K3, berkelanjutan</span></td><td data-tip="CPL 4 inti PEO 1: perancangan sistem sesuai standar K3 dan prinsip berkelanjutan."><span class="mk mks mg">●</span></td><td data-tip="Aspek K3 dan tanggung jawab lingkungan beririsan dengan profesionalisme PEO 2."><span class="mk mkw mtw">○</span></td><td data-tip="Perancangan sistem berkelanjutan mendukung daya saing dan reputasi global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 langsung membutuhkan kompetensi perancangan sistem dari CPL 4."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 memerlukan pemahaman K3 dalam instalasi & pemeliharaan."><span class="mk mkw mvw">○</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 5</span><span class="ctxt">Ilmu Dasar &amp; Rekayasa</span><span class="csh">Matematika, IPA, komputasi</span></td><td data-tip="CPL 5 fondasi ilmu dasar yang mendukung seluruh kompetensi teknis PEO 1."><span class="mk mks mg">●</span></td><td><span class="mk mkn">–</span></td><td data-tip="Penguasaan rekayasa terapan mendukung adopsi teknologi terkini (PEO 3)."><span class="mk mkw mrw">○</span></td><td data-tip="Profil 1 membutuhkan fondasi rekayasa kuat dari CPL 5 untuk merancang sistem."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 membutuhkan ilmu dasar rekayasa untuk troubleshooting dan instalasi."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 6</span><span class="ctxt">Analisis Sistem Tenaga</span><span class="csh">Pemodelan, pemecahan masalah</span></td><td data-tip="CPL 6 inti PEO 1: analisis, pemodelan, pemecahan permasalahan teknis terstandar."><span class="mk mks mg">●</span></td><td><span class="mk mkn">–</span></td><td data-tip="Kemampuan analisis mendalam diperlukan untuk troubleshooting & optimalisasi global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 membutuhkan analisis dan optimalisasi kinerja sistem dari CPL 6."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 membutuhkan analisis untuk troubleshooting di lapangan."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 7</span><span class="ctxt">Rancang–Instalasi–Otomasi–Ops</span><span class="csh">Proteksi, K3, keandalan</span></td><td data-tip="CPL 7 puncak kompetensi teknis PEO 1: rancang, instalasi, proteksi, otomasi, operasi."><span class="mk mks mg">●</span></td><td data-tip="Aspek keselamatan kerja dalam CPL 7 beririsan dengan profesionalisme PEO 2."><span class="mk mkw mtw">○</span></td><td data-tip="CPL 7 inti PEO 3: solusi inovatif berdaya saing nasional-global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 secara penuh mengandalkan seluruh kompetensi teknis CPL 7."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 mengandalkan kompetensi instalasi, otomasi, dan operasi dari CPL 7."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 8</span><span class="ctxt">Troubleshooting &amp; Maintenance</span><span class="csh">Optimalisasi industri</span></td><td data-tip="CPL 8 mendukung PEO 1 dalam aspek pemeliharaan dan optimalisasi sistem."><span class="mk mks mg">●</span></td><td data-tip="Tanggung jawab profesional dalam pemeliharaan beririsan dengan etika PEO 2."><span class="mk mkw mtw">○</span></td><td data-tip="CPL 8 inti PEO 3: troubleshooting & pemeliharaan sistem kompetitif di industri."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 memerlukan kemampuan diagnosis dan optimalisasi kinerja dari CPL 8."><span class="mk mks mb2">●</span></td><td data-tip="CPL 8 adalah inti Profil 2: troubleshooting dan pemeliharaan di lapangan industri."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 9</span><span class="ctxt">Adopsi Teknologi Terkini</span><span class="csh">Evaluasi, integrasi inovasi</span></td><td data-tip="CPL 9 mendukung PEO 1 melalui implementasi teknologi terkini dalam sistem."><span class="mk mks mg">●</span></td><td data-tip="Inovasi dalam CPL 9 selaras dengan semangat inovatif dan adaptif PEO 2."><span class="mk mkw mtw">○</span></td><td data-tip="CPL 9 inti PEO 3: adopsi & implementasi teknologi terkini untuk daya saing global."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 memerlukan kemampuan integrasi teknologi inovatif dari CPL 9."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 memerlukan implementasi teknologi terkini di lapangan dari CPL 9."><span class="mk mks mv2">●</span></td></tr>
      <tr><td class="tdlbl"><span class="cn2">CPL 10</span><span class="ctxt">Profesionalisme &amp; Kepemimpinan</span><span class="csh">Integritas, kolaborasi, dampak</span></td><td data-tip="Kepemimpinan teknis dan inovasi CPL 10 mendukung solusi rekayasa PEO 1."><span class="mk mkw mgw">○</span></td><td data-tip="CPL 10 inti PEO 2: integritas, tanggung jawab profesional, kepemimpinan tim."><span class="mk mks mt2">●</span></td><td data-tip="Orientasi dampak nyata dan inovasi berkelanjutan CPL 10 mendukung PEO 3."><span class="mk mks mr2">●</span></td><td data-tip="Profil 1 mensyaratkan kepemimpinan efektif dan inovasi teknis dari CPL 10."><span class="mk mks mb2">●</span></td><td data-tip="Profil 2 memerlukan profesionalisme dan tanggung jawab dari CPL 10."><span class="mk mks mv2">●</span></td></tr>
    </tbody>
  </table>
  </div>
</section>

</div><!-- /wrap -->

<!-- FOOTER -->
<footer>
  <div class="ft">
    <div class="fb">
      <div class="fb-logo">
        <div class="fb-icon">PCR</div>
        <div class="fb-name">Politeknik Caltex Riau</div>
      </div>
      <p>Program Studi Sarjana Terapan D4 Teknik Listrik. Menghasilkan Engineer Profesional Ketenagalistrikan yang kompeten, berkarakter, dan berdaya saing global melalui pendekatan Outcome-Based Education.</p>
    </div>
    <div class="fdiv"></div>
    <div class="fobe" style="text-align:right">
      <span class="fobl">Kurikulum Berbasis</span>
      <div class="fobt">Outcome-Based<br>Education</div>
      <p>PEO &middot; Profil Lulusan &middot; CPL<br>3 PEO &nbsp;&middot;&nbsp; 2 Profil &nbsp;&middot;&nbsp; 10 CPL</p>
    </div>
  </div>
  <div class="fbot">
    <div class="fcp">&copy; D4 Teknik Listrik &mdash; Politeknik Caltex Riau &nbsp;&middot;&nbsp; Peta Kurikulum OBE</div>
    <div class="fn">
      <a href="#peo">PEO</a>
      <a href="#profil">Profil Lulusan</a>
      <a href="#cpl">CPL</a>
      <a href="#domain">Domain</a>
      <a href="#matriks">Matriks</a>
    </div>
  </div>
</footer>

<script>
function showTab(id,el){
  document.querySelectorAll('.tb').forEach(b=>b.classList.remove('a'));
  document.querySelectorAll('.tp').forEach(p=>p.classList.remove('a'));
  el.classList.add('a');
  document.getElementById('tp-'+id).classList.add('a');
}
const rvEls=document.querySelectorAll('.rv');
const obs=new IntersectionObserver((entries)=>{
  entries.forEach((e,i)=>{
    if(e.isIntersecting){setTimeout(()=>e.target.classList.add('vi'),i*55);obs.unobserve(e.target)}
  });
},{threshold:.08});
rvEls.forEach(el=>obs.observe(el));
</script>
</body>
</html>
