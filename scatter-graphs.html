<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Scatter Graphs</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}


  .rep-top{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;margin-top:8px;}
  .rep-legend{flex:1;min-width:220px;display:flex;flex-direction:column;gap:8px;}
  .rep-cap{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);text-transform:uppercase;letter-spacing:.05em;}
  .rep-li{display:flex;align-items:center;gap:6px;font-size:15px;}
  .rep-n{margin-left:auto;white-space:nowrap;padding-left:8px;font-family:'IBM Plex Mono',monospace;font-weight:600;}
  .sw{display:inline-block;width:12px;height:12px;border-radius:3px;flex:none;}
  .rep-grid{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .rep-grid{grid-template-columns:1fr 1fr;} }
  .rep-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:14px;display:flex;flex-direction:column;gap:10px;}
  .rep-h{display:flex;align-items:center;gap:8px;font:700 16px 'Source Sans 3',sans-serif;}
  .crit{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;color:var(--card);font:700 15px Fraunces,serif;flex:none;}
  .rep-row{display:flex;gap:14px;align-items:center;}
  .rep-stats{display:flex;flex-direction:column;gap:5px;font-size:14.5px;}
  .rep-stats div{display:flex;align-items:center;gap:6px;}
  .rep-lvl{margin-top:4px;color:var(--accent-text);} .rep-lvl span{color:var(--ink-soft);font-size:13px;}
  .rep-note{font-size:13px;color:var(--ink-soft);}


  .skip-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;}
  .skip-chips .chip{min-width:48px;min-height:40px;cursor:pointer;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--retry-text);border-radius:10px;font:600 14px 'IBM Plex Mono',monospace;}
  .skip-btns{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:12px;}


  .kb-toggle{border:none;background:transparent;font-size:15px;cursor:pointer;padding:0 2px;vertical-align:middle;opacity:.7;}
  .vkb{position:fixed;left:0;right:0;bottom:0;z-index:80;background:var(--paper-2);border-top:1px solid var(--rule);box-shadow:0 -6px 20px rgba(0,0,0,.12);padding:6px 6px 8px;display:none;}
  .vkb.show{display:block;}
  .vkb-top{display:flex;justify-content:space-between;align-items:center;max-width:640px;margin:0 auto 4px;font:600 12px 'Source Sans 3',sans-serif;color:var(--ink-soft);}
  .vkb-link{border:none;background:none;color:var(--accent-text);font:600 12px 'Source Sans 3',sans-serif;cursor:pointer;text-decoration:underline;}
  .vkb-row{display:flex;gap:5px;max-width:640px;margin:0 auto 5px;}
  .vkb-k{flex:1;min-height:42px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 17px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .vkb-k.fn{font:600 13px 'Source Sans 3',sans-serif;background:var(--gold-soft);}
  .vkb-k.done{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .vkb-k:active{transform:scale(.96);}
  body.kb-open .wrap{padding-bottom:360px;}
  body.kb-open .fab{display:none;}
  .tool-bar{display:flex;gap:8px;flex-wrap:wrap;margin:-4px 0 10px;}
  .tool-btn{min-height:36px;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--ink);border-radius:18px;padding:4px 12px;font:600 13.5px 'Source Sans 3',sans-serif;cursor:pointer;}
  .tool-panel{position:fixed;z-index:85;background:var(--card);border:1px solid var(--rule);border-radius:14px;box-shadow:0 10px 30px rgba(0,0,0,.25);display:none;}
  .tool-panel.show{display:block;}
  .tp-head{display:flex;align-items:center;gap:8px;padding:8px 10px;border-bottom:1px solid var(--rule);font:600 14px 'Source Sans 3',sans-serif;}
  .tp-note{font-size:12px;color:var(--ink-soft);font-weight:500;}
  .tp-x{margin-left:auto;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:8px;min-height:32px;padding:2px 10px;cursor:pointer;font:600 13px 'Source Sans 3',sans-serif;}
  .tp-x + .tp-x{margin-left:0;}
  .calc{right:12px;bottom:84px;width:min(330px,calc(100vw - 24px));}
  body.calc-open .wrap{padding-bottom:440px;}
  body.calc-open .fab{display:none;}
  @media (max-width:640px){ .calc{left:6px;right:6px;width:auto;} .calc-keys button{min-height:36px;} }
  .calc-disp{padding:8px 12px;text-align:right;background:var(--paper-2);}
  .calc-expr{font:500 13px 'IBM Plex Mono',monospace;color:var(--ink-soft);min-height:18px;word-break:break-all;}
  .calc-res{font:600 24px 'IBM Plex Mono',monospace;color:var(--ink);word-break:break-all;}
  .calc-keys{display:grid;grid-template-columns:repeat(6,1fr);gap:5px;padding:8px;}
  .calc-keys button{min-height:40px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 14px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .calc-keys button.fn{background:var(--gold-soft);font-family:'Source Sans 3',sans-serif;font-size:13px;}
  .calc-keys button.eq{grid-column:span 2;background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .desmos{left:50%;top:50%;transform:translate(-50%,-50%);width:min(760px,calc(100vw - 16px));height:min(560px,calc(100vh - 90px));flex-direction:column;}
  .desmos.show{display:flex;}
  #desmosBox{flex:1;min-height:0;border-radius:0 0 14px 14px;overflow:hidden;}
  .desmos-msg{padding:24px;text-align:center;color:var(--ink-soft);}
  .chip[data-status="skipped"]{cursor:pointer;}
  .chip[data-status="answered"]{border-color:var(--accent-text);color:var(--accent-text);}


  button.crest-home{border:none;padding:0;position:relative;cursor:pointer;transition:transform .15s ease;}
  button.crest-home:hover,button.crest-home:focus-visible{transform:scale(1.06);outline:2px solid var(--gold);outline-offset:2px;}
  .crest-h{position:absolute;right:-7px;bottom:-7px;width:18px;height:18px;border-radius:50%;background:#F4EFDF;color:var(--navy);font:700 12px/18px 'Source Sans 3',sans-serif;text-align:center;box-shadow:0 1px 3px rgba(0,0,0,.3);}
  .brand .brand-row{position:relative;}
  .bmasw{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);display:flex;flex-shrink:0;white-space:nowrap;align-items:center;gap:6px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.25);border-radius:99px;padding:5px 14px;color:#F4EFDF;}
  .bmasw-ic{font-size:16px;} .bmasw-t{font:600 20px 'IBM Plex Mono',monospace;letter-spacing:.02em;min-width:62px;text-align:center;}
  .bmasw-b{border:none;background:rgba(255,255,255,.18);color:#F4EFDF;border-radius:50%;width:30px;height:30px;cursor:pointer;font-size:13px;}
  .bmasw.off{display:none;}
  @media (max-width:560px){ .bmasw{position:static;transform:none;margin-left:auto;padding:4px 5px 4px 8px;gap:4px;} .bmasw-ic{display:none;} .bmasw-t{font-size:16px;min-width:48px;} .bmasw-b{width:26px;height:26px;} .brand .series-name{font-size:15px;} .brand .brand-name{font-size:10.5px;} .brand .brand-row>div:not(.bmasw){min-width:0;} }
  .bmasw-done{font:600 15px 'IBM Plex Mono',monospace;color:var(--accent-text);margin:4px 0 8px;}
  .sp-fab{position:fixed;left:14px;bottom:84px;z-index:60;border:1.5px solid var(--navy-2);background:var(--card);color:var(--ink);border-radius:99px;padding:9px 14px;font:700 14px 'Source Sans 3',sans-serif;box-shadow:0 4px 14px rgba(0,0,0,.15);cursor:pointer;}
  .sp-fab.on{background:var(--navy);color:#F4EFDF;}
  body.kb-open .sp-fab{display:none;}
  .sp-canvas{position:absolute;z-index:55;display:none;touch-action:none;cursor:crosshair;}
  .sp-canvas.passive{pointer-events:none;cursor:default;}
  .sp-bar{position:fixed;top:8px;left:8px;right:8px;margin:0 auto;width:max-content;z-index:90;display:none;align-items:center;gap:6px;background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:6px 8px;box-shadow:0 6px 20px rgba(0,0,0,.2);max-width:calc(100vw - 16px);flex-wrap:wrap;justify-content:center;}
  .sp-lbl{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);margin-right:2px;}
  .sp-pen,.sp-tool{width:38px;height:38px;border-radius:10px;border:1.5px solid var(--rule);background:var(--paper);cursor:pointer;display:inline-flex;align-items:center;justify-content:center;font-size:17px;padding:0;color:var(--ink);}
  .sp-pen i{width:20px;height:20px;border-radius:50%;display:block;}
  .sp-pen.on,.sp-tool.on{border-color:var(--navy-2);box-shadow:0 0 0 3px var(--gold-soft);}
  @media (max-width:560px){ .sp-lbl{display:none;} .sp-pen,.sp-tool{width:34px;height:34px;} .sp-fab span{display:none;} }

  /* larger reading sizes */
  .chapter-eyebrow{font-size:13.5px;}
  .chapter-title{font-size:36px;line-height:1.15;}
  .chapter-sub{font-size:16.5px;}
  .tab-btn{font-size:15.5px;}
  .sec-sub{font-size:15px;}
  .qtext{font-size:19px;line-height:1.55;}
  .qnum{width:36px;height:36px;font-size:16px;}
  .opt{font-size:17.5px;padding:12px 14px;}
  .step-line{font-size:17.5px;line-height:2;}
  .blank-input{font-size:16px;}
  .sol-line{font-size:16.5px;}
  .feedback{font-size:15px;}
  .note h2{font-size:28px;}
  .note h4{font-size:19px;}
  .note p,.note li{font-size:17.5px;line-height:1.65;}
  .note .lt{font-size:15.5px;}
  .ex .exh{font-size:18px;} .ex .exl{font-size:16.5px;}
  .keybox{font-size:16.5px;}
  .ttab{font-size:15.5px;}
  .hub-card h3{font-size:21px;} .hub-card p{font-size:15.5px;} .hub-btn{font-size:15px;}
  @media (max-width:480px){ .chapter-title{font-size:30px;} .qtext{font-size:18px;} .opt,.step-line{font-size:16.5px;} .note h2{font-size:24px;} .note p,.note li{font-size:16.5px;} }

  /* v4 celebration */
  .v4conf{position:fixed;inset:0;width:100vw;height:100vh;pointer-events:none;z-index:9999;}
  .v4ban{background:linear-gradient(135deg,var(--gold-soft),var(--card));border:2px solid var(--gold);border-radius:18px;padding:18px 14px 16px;margin:-4px 0 18px;text-align:center;animation:v4pop .55s cubic-bezier(.2,1.6,.4,1);}
  @keyframes v4pop{0%{transform:scale(.6);opacity:0}100%{transform:scale(1);opacity:1}}
  .v4trophy{font-size:54px;line-height:1;animation:v4bob 1.4s ease-in-out infinite;}
  @keyframes v4bob{0%,100%{transform:translateY(0) rotate(-6deg)}50%{transform:translateY(-6px) rotate(6deg)}}
  .v4h{font-size:28px;font-weight:800;color:var(--accent-text);margin-top:6px;}
  .v4m{font-size:19px;color:var(--ink);margin-top:4px;}
  .v4pills{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:12px;}
  .v4p{font-size:16px;font-weight:700;border-radius:999px;padding:6px 12px;}
  .v4p.g{background:var(--success-soft);color:var(--success);} .v4p.o{background:var(--gold-soft);color:var(--retry-text);}
  .v4p.r{background:var(--danger-soft);color:var(--danger);} .v4p.s{background:var(--rule);color:var(--ink);}
  .v4next{margin-top:14px;} .v4go{font-size:18px !important;padding:13px 20px !important;}
  .v4rec td.v4g{color:var(--success);font-weight:700;} .v4rec td.v4o{color:var(--retry-text);font-weight:700;} .v4rec td.v4r{color:var(--danger);font-weight:700;}
  .v4rec tr.v4tot td{font-weight:800;border-top:2px solid var(--rule);}
  .v4rec th{font-size:12.5px;padding:6px 3px !important;white-space:nowrap;} .v4rec td{font-size:15px;padding:7px 3px !important;text-align:center;}
  .v4rec td:first-child,.v4rec th:first-child{text-align:left;white-space:normal;min-width:92px;max-width:150px;font-size:14.5px;}
  @media(max-width:460px){ .v4left{display:none;} }
  .v4leg{font-size:14.5px;color:var(--ink-soft);margin:2px 0 8px;line-height:1.5;}
  body.v4done .fab-q,body.v4done #qFab{display:none;}
  .v4sum{font-size:16px;margin-top:10px;}
  /* v4 larger reading sizes */
  body{font-size:18px;}
  .chapter-title{font-size:38px !important;line-height:1.15;}
  .chapter-sub{font-size:17px !important;}
  .tab-btn{font-size:16.5px !important;}
  .sec-sub{font-size:16.5px !important;}
  .qtext{font-size:21px !important;line-height:1.6 !important;}
  .qnum{width:38px !important;height:38px !important;font-size:17px !important;}
  .opt{font-size:19.5px !important;padding:13px 15px !important;}
  .step-line{font-size:19.5px !important;line-height:2.1 !important;}
  .blank-input{font-size:18px !important;min-height:40px;}
  .sol-line{font-size:18px !important;line-height:1.6;}
  .feedback{font-size:16.5px !important;}
  .note h2{font-size:29px !important;}
  .note h3{font-size:22px !important;}
  .note h4{font-size:20px !important;}
  .note p,.note li,.note td,.note th{font-size:18.5px !important;line-height:1.7 !important;}
  .ex .exh{font-size:19px !important;} .ex .exl{font-size:18px !important;}
  .keybox{font-size:18px !important;}
  .hub-card p{font-size:17.5px !important;} .hub-btn{font-size:16.5px !important;}
  .review-q,.review-ans{font-size:17.5px !important;}
  .rec-table td{font-size:16px;}
  .vkb-k{font-size:19px !important;}
  .fq{font-size:0.95em;}

  /* v5 plotters */
  .plotw{background:var(--card);border:1px solid var(--rule);border-radius:12px;padding:10px;margin:6px 0 4px;}
  .plotw svg{display:block;margin:0 auto;cursor:crosshair;}
  .plw-msg{font-size:15px;color:var(--ink-soft);margin:6px 2px;}
  .plw-tools{display:flex;gap:8px;flex-wrap:wrap;margin-top:6px;}
  .plw-tools button,.plw-row button{font:600 14px 'Source Sans 3',sans-serif;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:8px;padding:7px 10px;cursor:pointer;min-height:36px;}
  .plw-row{display:flex;align-items:center;gap:6px;flex-wrap:wrap;padding:6px;border-radius:8px;margin-top:6px;border:1px solid transparent;}
  .plw-row.sel{border-color:var(--gold);background:var(--gold-soft);}
  .plw-sw{width:14px;height:14px;border-radius:4px;display:inline-block;}
  .plw-eq{font:600 16px 'IBM Plex Mono',monospace;margin-right:4px;}
  .plw-sum{font-size:16px;margin-top:8px;} .plw-key{font-size:15px;margin-top:6px;color:var(--ink);}

  /* v6 accuracy meter */
  .accm{max-width:900px;margin:6px auto 0;padding:6px 16px;display:flex;align-items:center;gap:10px;}
  .accg{width:64px;height:38px;flex:0 0 auto;}
  .acct{display:flex;flex-direction:column;line-height:1.25;font-size:14.5px;color:var(--ink-soft);}
  .acct b{font-size:16px;color:var(--ink);} .accp{font:700 18px 'IBM Plex Mono',monospace;margin-left:4px;}
  .accp.g{color:var(--success);} .accp.o{color:var(--retry-text);} .accp.r{color:var(--danger);}
  /* v6 observations */
  .v6obs{text-align:left;background:var(--card);border:1px solid var(--rule);border-left:5px solid var(--accent-text);border-radius:14px;padding:14px 16px;margin:0 0 16px;}
  .v6h{font:700 21px 'Fraunces',Georgia,serif;color:var(--accent-text);margin-bottom:6px;}
  .v6lvl{font-size:17px;font-weight:700;padding:8px 10px;border-radius:10px;margin-bottom:8px;}
  .v6lvl.g{background:var(--success-soft);color:var(--success);} .v6lvl.o{background:var(--gold-soft);color:var(--retry-text);} .v6lvl.r{background:var(--danger-soft);color:var(--danger);}
  .v6sub{font-weight:800;font-size:15px;text-transform:uppercase;letter-spacing:.04em;color:var(--ink-soft);margin:10px 0 4px;}
  .v6ul{margin:0;padding-left:20px;} .v6ul li{font-size:17px;line-height:1.55;margin:3px 0;} .v6p{font-size:17px;margin:2px 0;}
  .v6q{font:700 14px 'IBM Plex Mono',monospace;border:1px solid var(--danger);color:var(--danger);background:var(--danger-soft);border-radius:8px;padding:3px 8px;cursor:pointer;margin:2px 2px;}
  .v6btns{display:flex;flex-direction:column;gap:6px;} .v6btns button{text-align:left;font:600 16px 'Source Sans 3',sans-serif;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:9px 12px;cursor:pointer;}
  /* v6 whiteboard */
  .wb-fab{position:fixed;left:14px;bottom:calc(140px + env(safe-area-inset-bottom,0px));z-index:40;border:1px solid var(--rule);background:var(--card);color:var(--ink);border-radius:999px;padding:9px 14px;font:700 15px 'Source Sans 3',sans-serif;box-shadow:0 2px 8px rgba(0,0,0,.15);cursor:pointer;}
  @media(max-width:520px){ .wb-fab span{display:none;} .wb-fab{padding:9px 11px;} }
  .wbov{position:fixed;inset:0;z-index:9000;background:#f3f4f6;display:none;flex-direction:column;}
  .wbov.show{display:flex;} body.wb-open{overflow:hidden;}
  .wbbar{display:flex;flex-wrap:nowrap;overflow-x:auto;-webkit-overflow-scrolling:touch;align-items:center;gap:4px;padding:6px 8px;background:#fff;border-bottom:1px solid #e5e7eb;box-shadow:0 1px 4px rgba(0,0,0,.06);}
  .wbbar button{flex:0 0 auto;min-width:38px;height:38px;border:1px solid #e5e7eb;background:#fff;border-radius:9px;font:600 17px sans-serif;color:#111;cursor:pointer;}
  .wbbar button.on{border-color:#2563eb;background:#dbeafe;} .wbc{min-width:26px!important;width:26px;height:26px!important;border-radius:50%!important;border:2px solid #d1d5db!important;}
  .wbc.on{outline:3px solid #2563eb;outline-offset:1px;} .wbsep{flex:0 0 auto;width:1px;height:26px;background:#e5e7eb;margin:0 3px;}
  .wbsz{width:90px;flex:0 0 auto;} .wbpg{font:600 14px sans-serif;color:#374151;min-width:44px;text-align:center;} .wbx{padding:0 10px;font-size:15px!important;}
  .wbcv{flex:1;width:100%;min-width:0;min-height:0;touch-action:none;cursor:crosshair;display:block;background:#fff;}
  .wbbody{flex:1;display:flex;flex-direction:column;min-height:0;}
  .wbq{background:var(--paper);color:var(--ink);border-bottom:3px solid var(--gold);max-height:40vh;overflow:auto;padding:8px 12px 10px;flex:0 0 auto;}
  .wbqh{display:flex;align-items:center;justify-content:space-between;gap:8px;font-size:15px;color:var(--accent-text);margin-bottom:6px;position:sticky;top:-8px;background:var(--paper);padding:4px 0;z-index:1;}
  .wbqt{font:600 14px 'Source Sans 3',sans-serif;border:1px solid var(--rule);background:var(--card);color:var(--ink);border-radius:8px;padding:5px 10px;cursor:pointer;}
  .wbq.min{max-height:none;} .wbq.min .wbqc{display:none;}
  .wbqc .qcard{margin:0;box-shadow:none;} .wbqc .qtext{font-size:19px !important;} .wbqc input{pointer-events:none;}
  @media(min-width:860px){ .wbbody{flex-direction:row;} .wbq{width:40%;max-width:520px;max-height:none;border-bottom:0;border-right:3px solid var(--gold);} .wbq.min{width:auto;} }
  .wbin{position:fixed;z-index:9001;font:20px 'Source Sans 3',sans-serif;border:1px dashed #2563eb;background:rgba(255,255,255,.9);padding:2px 6px;min-width:140px;}

  .scatw{background:var(--card);border:1px solid var(--rule);border-radius:12px;padding:8px;margin:6px 0 4px;}
  .scatw svg{display:block;margin:0 auto;cursor:crosshair;}
  .scw-sum{font-size:15.5px;margin-top:6px;}

  .gp-hidden{position:absolute !important;width:2px !important;height:2px !important;padding:0 !important;border:0 !important;opacity:0 !important;overflow:hidden;}
  .gp-box{margin:8px 0 4px;padding:10px;border:1px solid var(--rule);border-radius:12px;background:var(--card);}
  .gp-help{font-size:15px;color:var(--ink-soft);margin-bottom:6px;line-height:1.4;}
  .gp-svg{display:block;margin:0 auto;width:100%;max-width:380px;user-select:none;-webkit-user-select:none;cursor:crosshair;}
  .gp-tools{display:flex;flex-wrap:wrap;gap:6px;align-items:center;margin-top:8px;}
  .gp-tools.gp-n{display:block;line-height:2.6;}
  .gp-b{font:600 15px 'Source Sans 3',sans-serif;border:1.5px solid var(--rule);background:var(--paper);color:var(--ink);border-radius:999px;padding:6px 12px;cursor:pointer;margin:0 3px 0 0;}
  .gp-b.on{border-color:var(--accent-text);background:var(--gold-soft);color:var(--accent-text);}
  .gp-lab{font-weight:700;margin-right:6px;}
  .gp-in{font:16px 'IBM Plex Mono',monospace;width:90px;border:1.5px solid var(--rule);border-radius:6px;padding:4px 6px;margin-right:6px;background:var(--card);color:var(--ink);}
  .gp-stat{font-size:15px;margin-top:6px;color:var(--accent-text);font-weight:600;}
  .ineq-grapher{border:2px solid var(--gold);border-radius:14px;padding:12px;margin:14px 0;background:var(--card);}
  .gr-head{font:700 19px 'Fraunces',serif;color:var(--accent-text);margin-bottom:6px;}
  .gr-row{display:flex;gap:8px;} .gr-in{flex:1;min-width:0;font:16px 'IBM Plex Mono',monospace;border:1.5px solid var(--rule);border-radius:8px;padding:8px;background:var(--paper);color:var(--ink);}
  .gr-hint{font-size:14.5px;color:var(--ink-soft);margin:6px 0;}
  .gr-cv{width:100%;max-width:420px;display:block;margin:6px auto;border:1px solid var(--rule);border-radius:8px;}
  .gr-msg{font-size:15px;color:var(--accent-text);font-weight:600;}

  header.brand{background:linear-gradient(180deg,rgba(20,20,20,.55),rgba(20,20,20,.78)),url('data:image/jpeg;base64,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') center/cover no-repeat, #2b2b2b !important;}
  .crest,button.crest-home{width:58px !important;height:54px !important;background:transparent !important;border-radius:12px !important;}
  .crest img{width:58px;height:53px;display:block;filter:drop-shadow(0 1px 2px rgba(0,0,0,.5));}
  button.crest-home .crest-h{right:-4px;bottom:-4px;}
  .brand-name{color:#F4EFDF !important;font-family:'Fraunces',Georgia,serif;font-size:13px !important;letter-spacing:.06em;}
  .series-name{color:#E8D9A8;}
  .chapter-eyebrow{color:#D9D4C7 !important;}
  .chapter-sub{color:#F1D58A !important;}
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest"><img src="data:image/png;base64,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" alt="Brain and Mind"></div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Mathematics · Statistics · Topic sheet</div>
  <div class="chapter-title">Scatter Graphs</div>
  <div class="chapter-sub">Theory Notes · Plot-it Practice · Test</div><div class="chapter-credit">Theory · Step-by-step practice · Learning assessment</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series<br>Includes NYS Regents exam questions (S.ID.B.6) shared by JMAP (jmap.org). Other questions, theory notes and worked solutions written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^[a-z]=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(-?)(\d+)(?: |\+)(\d+)\/(\d+)$/))){ if(+m[4]===0) return null; var sg=m[1]?-1:1; return {v:sg*(+m[2]+m[3]/m[4]),form:'mixed',w:sg*m[2],n:+m[3],d:+m[4]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).replace(/[−–—]/g,'-').match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Short notes for every part of the topic: example graphs, the six kinds of correlation, how to draw a line of best fit, common mistakes and worked examples.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n1\">1 · Plotting scatter graphs</button><button class=\"hub-btn\" data-jump=\"n2\">2 · Correlation and relationships</button><button class=\"hub-btn\" data-jump=\"n3\">3 · Lines of best fit</button><button class=\"hub-btn\" data-jump=\"n4\">4 · Equation of a line of best fit</button></div></div><div class=\"hub-card\"><h3>🎯 Plot-it practice</h3><p>Six practice sheets. Tap the grid to plot points or draw your own line of best fit; the sheet checks it. Multiple-choice questions alternate with fill-in and plotting questions.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">1 · Plotting scatter graphs</button><button class=\"hub-btn\" data-go=\"s2\">2 · Correlation and relationships</button><button class=\"hub-btn\" data-go=\"s3\">3 · Lines of best fit</button><button class=\"hub-btn\" data-go=\"s4\">4 · Equation of a line of best fit</button><button class=\"hub-btn\" data-go=\"s5\">5 · Exam practice</button><button class=\"hub-btn\" data-go=\"s6\">6 · Regents questions</button></div></div><div class=\"hub-card\"><h3>📝 Test</h3><p>Four short assessments mixing the whole topic, one per skill area. Take them in Quiz mode and open the report to see your results.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s7\">A · Knowing and understanding</button><button class=\"hub-btn\" data-go=\"s8\">B · Investigating patterns</button><button class=\"hub-btn\" data-go=\"s9\">C · Communicating</button><button class=\"hub-btn\" data-go=\"s10\">D · Applying mathematics in real-life contexts</button><button class=\"hub-btn primary\" data-go=\"report\">📊 View my report</button></div></div></div><section class=\"note\" id=\"nintro\"><h2>What is a scatter graph?</h2><p>A <b>scatter graph</b> (scatter plot, scatter diagram) shows <b>pairs of values</b> measured on the same people or things, for example the height <i>and</i> the arm span of each student. Each pair is one cross: across for the first value (x), up for the second (y). Looking at the whole cloud of crosses tells us whether the two quantities are related.</p><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"66.7\" y1=\"256.0\" x2=\"66.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"96.1\" y1=\"256.0\" x2=\"96.1\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"154.9\" y1=\"256.0\" x2=\"154.9\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"184.3\" y1=\"256.0\" x2=\"184.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"213.7\" y1=\"256.0\" x2=\"213.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"243.1\" y1=\"256.0\" x2=\"243.1\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"301.9\" y1=\"256.0\" x2=\"301.9\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"331.3\" y1=\"256.0\" x2=\"331.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"243.9\" x2=\"346.0\" y2=\"243.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"219.7\" x2=\"346.0\" y2=\"219.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"171.3\" x2=\"346.0\" y2=\"171.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"147.1\" x2=\"346.0\" y2=\"147.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"122.9\" x2=\"346.0\" y2=\"122.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"98.7\" x2=\"346.0\" y2=\"98.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"50.3\" x2=\"346.0\" y2=\"50.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"26.1\" x2=\"346.0\" y2=\"26.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">140</text><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"125.5\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">150</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">160</text><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"272.5\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">170</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">180</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">140</text><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"199.5\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">150</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">160</text><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"78.5\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">170</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">180</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Height (cm)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Arm span (cm)</text><clipPath id=\"c628730593\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c628730593)\"></g><line x1=\"62.2\" y1=\"251.5\" x2=\"71.2\" y2=\"260.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"62.2\" y1=\"260.5\" x2=\"71.2\" y2=\"251.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"191.0\" x2=\"115.3\" y2=\"200.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"200.0\" x2=\"115.3\" y2=\"191.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"191.0\" x2=\"144.7\" y2=\"200.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"200.0\" x2=\"144.7\" y2=\"191.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"142.6\" x2=\"174.1\" y2=\"151.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"151.6\" x2=\"174.1\" y2=\"142.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"154.7\" x2=\"203.5\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"163.7\" x2=\"203.5\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"94.2\" x2=\"232.9\" y2=\"103.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"103.2\" x2=\"232.9\" y2=\"94.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"268.0\" y1=\"82.1\" x2=\"277.0\" y2=\"91.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"268.0\" y1=\"91.1\" x2=\"277.0\" y2=\"82.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"45.8\" x2=\"321.1\" y2=\"54.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"54.8\" x2=\"321.1\" y2=\"45.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Height and arm span of 8 students: each cross is one student.</figcaption></figure><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Sheet</th><th>Part</th><th>Learning target</th></tr><tr><td>1</td><td>Plotting scatter graphs</td><td>I can plot pairs of data as crosses, choose and read scales, and read values and counts from a scatter graph.</td></tr><tr><td>2</td><td>Correlation and relationships</td><td>I can describe correlation (positive, negative, none; strong or weak), spot outliers and explain why correlation does not prove causation.</td></tr><tr><td>3</td><td>Lines of best fit</td><td>I can draw a line of best fit, use it to estimate values, and say when an estimate is interpolation (reliable) or extrapolation (risky).</td></tr><tr><td>4</td><td>Equation of a line of best fit</td><td>I can find the gradient and intercept of a line of best fit, explain them in context and use the equation to predict.</td></tr><tr><td>5</td><td>Exam practice</td><td>I can answer multi-part exam questions that mix plotting, describing, estimating and explaining.</td></tr><tr><td>6</td><td>Regents questions</td><td>I can answer NYS Regents exam questions on scatter plots and lines of best fit.</td></tr></table></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Assessment</th><th>Skill area</th><th>What it checks</th></tr><tr><td>A</td><td>Knowing and understanding</td><td>Plotting, reading, naming the correlation, drawing a line of best fit.</td></tr><tr><td>B</td><td>Investigating patterns</td><td>How outliers and new points change a pattern; gradients and trends.</td></tr><tr><td>C</td><td>Communicating</td><td>Correct vocabulary, describing relationships, correlation and causation.</td></tr><tr><td>D</td><td>Applying mathematics in real-life contexts</td><td>Shop, travel, energy and money problems, and checking whether a prediction is reasonable.</td></tr></table></div><p><b>How the plotting questions work:</b> tap the grid to plot a cross (tap it again to remove it). For a line of best fit, tap two points on your line; tap again to start over. Crosses snap to the nearest small grid line. Type numbers like <span class=\"mono\">22.5</span> and words like <span class=\"mono\">positive</span>.</p></section><section class=\"note\" id=\"n1\"><h2>1 · Plotting scatter graphs</h2><p class=\"lt\"><b>Learning target:</b> I can plot pairs of data as crosses, choose and read scales, and read values and counts from a scatter graph.</p><h4>Plotting a point</h4><ol><li>Read the pair from the table: (x, y) = (first value, second value).</li><li>Go <b>across</b> the horizontal axis to x, then <b>up</b> to y.</li><li>Mark a small, neat cross <b>×</b>. Do not join the crosses.</li></ol><h4>Reading the scale</h4><p>Work out what one small square is worth: <b>value of one big square ÷ number of small squares in it</b>. On a y-axis going up in 20s with 5 small squares per big square, one small square is 20 ÷ 5 = 4.</p><div class=\"ex\"><div class=\"exh\">Worked example · Plot the age and value of a car</div><div class=\"exl\">A 4-year-old car is worth ₹340 thousand. On the axes below, one small square across is 1 year and one small square up is ₹20 thousand.<br>Across to 4, then up to 340: 340 is 300 + 40, which is 2 small squares above the 300 line.<br>Mark the cross at (4, 340).</div></div><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"247.9\" x2=\"346.0\" y2=\"247.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"239.9\" x2=\"346.0\" y2=\"239.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"223.7\" x2=\"346.0\" y2=\"223.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"215.7\" x2=\"346.0\" y2=\"215.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"199.5\" x2=\"346.0\" y2=\"199.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"191.5\" x2=\"346.0\" y2=\"191.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"175.3\" x2=\"346.0\" y2=\"175.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"167.3\" x2=\"346.0\" y2=\"167.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"151.1\" x2=\"346.0\" y2=\"151.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"143.1\" x2=\"346.0\" y2=\"143.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"126.9\" x2=\"346.0\" y2=\"126.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"118.9\" x2=\"346.0\" y2=\"118.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"102.7\" x2=\"346.0\" y2=\"102.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"94.7\" x2=\"346.0\" y2=\"94.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"78.5\" x2=\"346.0\" y2=\"78.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"70.5\" x2=\"346.0\" y2=\"70.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"54.3\" x2=\"346.0\" y2=\"54.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"46.3\" x2=\"346.0\" y2=\"46.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"30.1\" x2=\"346.0\" y2=\"30.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"22.1\" x2=\"346.0\" y2=\"22.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"81.4\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">1</text><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"110.8\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">2</text><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"140.2\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">3</text><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"169.6\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">4</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">5</text><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"228.4\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">6</text><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"257.8\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">7</text><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"287.2\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">8</text><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"316.6\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">9</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"52.0\" y1=\"215.7\" x2=\"346.0\" y2=\"215.7\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"219.7\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">100</text><line x1=\"52.0\" y1=\"175.3\" x2=\"346.0\" y2=\"175.3\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"179.3\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">200</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">300</text><line x1=\"52.0\" y1=\"94.7\" x2=\"346.0\" y2=\"94.7\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"98.7\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">400</text><line x1=\"52.0\" y1=\"54.3\" x2=\"346.0\" y2=\"54.3\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"58.3\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">500</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">600</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Age of car (years)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Value (₹ thousand)</text><clipPath id=\"c269958028\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c269958028)\"></g><line x1=\"76.9\" y1=\"41.8\" x2=\"85.9\" y2=\"50.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"76.9\" y1=\"50.8\" x2=\"85.9\" y2=\"41.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"66.0\" x2=\"115.3\" y2=\"75.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"75.0\" x2=\"115.3\" y2=\"66.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"82.1\" x2=\"144.7\" y2=\"91.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"91.1\" x2=\"144.7\" y2=\"82.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"122.4\" x2=\"203.5\" y2=\"131.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"131.4\" x2=\"203.5\" y2=\"122.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"146.6\" x2=\"232.9\" y2=\"155.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"155.6\" x2=\"232.9\" y2=\"146.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"282.7\" y1=\"187.0\" x2=\"291.7\" y2=\"196.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"282.7\" y1=\"196.0\" x2=\"291.7\" y2=\"187.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"203.1\" x2=\"321.1\" y2=\"212.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"212.1\" x2=\"321.1\" y2=\"203.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"114.4\" x2=\"174.1\" y2=\"123.4\" style=\"stroke:var(--danger);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"123.4\" x2=\"174.1\" y2=\"114.4\" style=\"stroke:var(--danger);stroke-width:2.4\"/><circle cx=\"169.6\" cy=\"118.9\" r=\"11\" style=\"fill:none;stroke:var(--danger);stroke-width:2\"/><line x1=\"253.3\" y1=\"170.8\" x2=\"262.3\" y2=\"179.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"253.3\" y1=\"179.8\" x2=\"262.3\" y2=\"170.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Age and value of 9 cars: the circled cross is (4, 340).</figcaption></figure><h4>Questions you can answer straight from the graph</h4><ul><li><b>Largest / smallest value:</b> find the highest (or lowest, right-most, left-most) cross and read its value.</li><li><b>How many…?</b> draw a line across at the boundary value and count the crosses above or below it. Read the question carefully: “more than 30” does not include 30.</li><li><b>What percentage…?</b> count, then (count ÷ total) × 100.</li></ul><div class=\"keybox\"><b>Common mistakes.</b> Plotting (y, x) instead of (x, y): always go <b>across first</b>. Misreading the scale: check the value of one small square before plotting. Joining the crosses with lines: a scatter graph shows separate pairs, not a journey.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise 1 →</button></div></section><section class=\"note\" id=\"n2\"><h2>2 · Correlation and relationships</h2><p class=\"lt\"><b>Learning target:</b> I can describe correlation (positive, negative, none; strong or weak), spot outliers and explain why correlation does not prove causation.</p><p><b>Correlation</b> describes how two quantities change together. Look at the overall direction of the crosses, then at how tightly they hug a straight line.</p><div style=\"display:flex;flex-wrap:wrap;gap:6px;justify-content:center;margin:8px 0\"><div style=\"flex:1 1 140px;max-width:200px\"><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:200px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"288\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">x</text><text transform=\"translate(26,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">y</text><clipPath id=\"c99045681\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c99045681)\"></g><line x1=\"74.9\" y1=\"191.4\" x2=\"87.9\" y2=\"204.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"74.9\" y1=\"204.4\" x2=\"87.9\" y2=\"191.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"176.9\" x2=\"117.3\" y2=\"189.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"189.9\" x2=\"117.3\" y2=\"176.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"152.7\" x2=\"146.7\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"165.7\" x2=\"146.7\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"143.0\" x2=\"176.1\" y2=\"156.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"156.0\" x2=\"176.1\" y2=\"143.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"118.8\" x2=\"205.5\" y2=\"131.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"131.8\" x2=\"205.5\" y2=\"118.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"104.3\" x2=\"234.9\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"117.3\" x2=\"234.9\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"89.8\" x2=\"264.3\" y2=\"102.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"102.8\" x2=\"264.3\" y2=\"89.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"65.6\" x2=\"293.7\" y2=\"78.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"78.6\" x2=\"293.7\" y2=\"65.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"55.9\" x2=\"323.1\" y2=\"68.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"68.9\" x2=\"323.1\" y2=\"55.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\"><b>strong positive</b><br>close to a rising line</figcaption></figure></div><div style=\"flex:1 1 140px;max-width:200px\"><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:200px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"288\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">x</text><text transform=\"translate(26,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">y</text><clipPath id=\"c415188239\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c415188239)\"></g><line x1=\"74.9\" y1=\"201.1\" x2=\"87.9\" y2=\"214.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"74.9\" y1=\"214.1\" x2=\"87.9\" y2=\"201.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"128.5\" x2=\"117.3\" y2=\"141.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"141.5\" x2=\"117.3\" y2=\"128.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"176.9\" x2=\"146.7\" y2=\"189.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"189.9\" x2=\"146.7\" y2=\"176.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"104.3\" x2=\"176.1\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"117.3\" x2=\"176.1\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"152.7\" x2=\"205.5\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"165.7\" x2=\"205.5\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"65.6\" x2=\"234.9\" y2=\"78.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"78.6\" x2=\"234.9\" y2=\"65.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"128.5\" x2=\"264.3\" y2=\"141.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"141.5\" x2=\"264.3\" y2=\"128.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"55.9\" x2=\"293.7\" y2=\"68.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"68.9\" x2=\"293.7\" y2=\"55.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"104.3\" x2=\"323.1\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"117.3\" x2=\"323.1\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"104.3\" x2=\"146.7\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"117.3\" x2=\"146.7\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"46.2\" x2=\"264.3\" y2=\"59.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"59.2\" x2=\"264.3\" y2=\"46.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"191.4\" x2=\"205.5\" y2=\"204.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"204.4\" x2=\"205.5\" y2=\"191.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\"><b>weak positive</b><br>rising, but spread out</figcaption></figure></div><div style=\"flex:1 1 140px;max-width:200px\"><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:200px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"288\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">x</text><text transform=\"translate(26,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">y</text><clipPath id=\"c605710265\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c605710265)\"></g><line x1=\"74.9\" y1=\"104.3\" x2=\"87.9\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"74.9\" y1=\"117.3\" x2=\"87.9\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"191.4\" x2=\"117.3\" y2=\"204.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"204.4\" x2=\"117.3\" y2=\"191.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"55.9\" x2=\"146.7\" y2=\"68.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"68.9\" x2=\"146.7\" y2=\"55.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"143.0\" x2=\"176.1\" y2=\"156.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"156.0\" x2=\"176.1\" y2=\"143.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"80.1\" x2=\"205.5\" y2=\"93.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"93.1\" x2=\"205.5\" y2=\"80.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"176.9\" x2=\"234.9\" y2=\"189.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"189.9\" x2=\"234.9\" y2=\"176.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"114.0\" x2=\"264.3\" y2=\"127.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"127.0\" x2=\"264.3\" y2=\"114.0\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"46.2\" x2=\"293.7\" y2=\"59.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"59.2\" x2=\"293.7\" y2=\"46.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"152.7\" x2=\"323.1\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"165.7\" x2=\"323.1\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"80.1\" x2=\"117.3\" y2=\"93.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"93.1\" x2=\"117.3\" y2=\"80.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"65.6\" x2=\"234.9\" y2=\"78.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"78.6\" x2=\"234.9\" y2=\"65.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"181.7\" x2=\"293.7\" y2=\"194.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"194.7\" x2=\"293.7\" y2=\"181.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\"><b>no correlation</b><br>no pattern</figcaption></figure></div><div style=\"flex:1 1 140px;max-width:200px\"><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:200px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"288\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">x</text><text transform=\"translate(26,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">y</text><clipPath id=\"c321218717\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c321218717)\"></g><line x1=\"74.9\" y1=\"31.7\" x2=\"87.9\" y2=\"44.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"74.9\" y1=\"44.7\" x2=\"87.9\" y2=\"31.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"46.2\" x2=\"117.3\" y2=\"59.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"59.2\" x2=\"117.3\" y2=\"46.2\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"75.3\" x2=\"146.7\" y2=\"88.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"88.3\" x2=\"146.7\" y2=\"75.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"89.8\" x2=\"176.1\" y2=\"102.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"102.8\" x2=\"176.1\" y2=\"89.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"104.3\" x2=\"205.5\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"117.3\" x2=\"205.5\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"133.3\" x2=\"234.9\" y2=\"146.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"146.3\" x2=\"234.9\" y2=\"133.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"147.9\" x2=\"264.3\" y2=\"160.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"160.9\" x2=\"264.3\" y2=\"147.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"176.9\" x2=\"293.7\" y2=\"189.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"189.9\" x2=\"293.7\" y2=\"176.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"191.4\" x2=\"323.1\" y2=\"204.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"204.4\" x2=\"323.1\" y2=\"191.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\"><b>strong negative</b><br>close to a falling line</figcaption></figure></div><div style=\"flex:1 1 140px;max-width:200px\"><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:200px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"288\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">x</text><text transform=\"translate(26,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 22px sans-serif;fill:var(--ink)\">y</text><clipPath id=\"c988415421\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c988415421)\"></g><line x1=\"74.9\" y1=\"55.9\" x2=\"87.9\" y2=\"68.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"74.9\" y1=\"68.9\" x2=\"87.9\" y2=\"55.9\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"128.5\" x2=\"117.3\" y2=\"141.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"104.3\" y1=\"141.5\" x2=\"117.3\" y2=\"128.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"80.1\" x2=\"146.7\" y2=\"93.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"93.1\" x2=\"146.7\" y2=\"80.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"152.7\" x2=\"176.1\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"163.1\" y1=\"165.7\" x2=\"176.1\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"104.3\" x2=\"205.5\" y2=\"117.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"117.3\" x2=\"205.5\" y2=\"104.3\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"191.4\" x2=\"234.9\" y2=\"204.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"221.9\" y1=\"204.4\" x2=\"234.9\" y2=\"191.4\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"128.5\" x2=\"264.3\" y2=\"141.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"141.5\" x2=\"264.3\" y2=\"128.5\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"201.1\" x2=\"293.7\" y2=\"214.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"280.7\" y1=\"214.1\" x2=\"293.7\" y2=\"201.1\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"152.7\" x2=\"323.1\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"310.1\" y1=\"165.7\" x2=\"323.1\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"152.7\" x2=\"146.7\" y2=\"165.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"133.7\" y1=\"165.7\" x2=\"146.7\" y2=\"152.7\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"210.8\" x2=\"264.3\" y2=\"223.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"251.3\" y1=\"223.8\" x2=\"264.3\" y2=\"210.8\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"65.6\" x2=\"205.5\" y2=\"78.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/><line x1=\"192.5\" y1=\"78.6\" x2=\"205.5\" y2=\"65.6\" style=\"stroke:var(--ink);stroke-width:3.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\"><b>weak negative</b><br>falling, but spread out</figcaption></figure></div></div><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Type</th><th>What the crosses do</th><th>Relationship in words</th></tr><tr><td>Positive</td><td>go up from left to right</td><td>as x increases, y increases</td></tr><tr><td>Negative</td><td>go down from left to right</td><td>as x increases, y decreases</td></tr><tr><td>None (zero)</td><td>no pattern, spread all over</td><td>no relationship between x and y</td></tr><tr><td>Strong / weak</td><td>close to a line / spread out round a line</td><td>how reliable the pattern is</td></tr></table></div><h4>Describe the correlation vs describe the relationship</h4><p>“Describe the correlation” wants the type: <i>positive</i>, <i>negative</i> or <i>no correlation</i> (add strong or weak if clear). “Describe the relationship” wants a sentence <b>in context</b>, e.g. “As the temperature increases, the number of hot drinks sold decreases.”</p><h4>Outliers</h4><p>An <b>outlier</b> is a point that does not fit the pattern of the rest. It may be a recording mistake or an unusual case. Leave it out when you draw a line of best fit.</p><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"66.7\" y1=\"256.0\" x2=\"66.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"96.1\" y1=\"256.0\" x2=\"96.1\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"154.9\" y1=\"256.0\" x2=\"154.9\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"184.3\" y1=\"256.0\" x2=\"184.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"213.7\" y1=\"256.0\" x2=\"213.7\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"243.1\" y1=\"256.0\" x2=\"243.1\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"301.9\" y1=\"256.0\" x2=\"301.9\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"331.3\" y1=\"256.0\" x2=\"331.3\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"246.3\" x2=\"346.0\" y2=\"246.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"236.6\" x2=\"346.0\" y2=\"236.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"227.0\" x2=\"346.0\" y2=\"227.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"217.3\" x2=\"346.0\" y2=\"217.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"197.9\" x2=\"346.0\" y2=\"197.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"188.2\" x2=\"346.0\" y2=\"188.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"178.6\" x2=\"346.0\" y2=\"178.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"168.9\" x2=\"346.0\" y2=\"168.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"149.5\" x2=\"346.0\" y2=\"149.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"139.8\" x2=\"346.0\" y2=\"139.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"130.2\" x2=\"346.0\" y2=\"130.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"120.5\" x2=\"346.0\" y2=\"120.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"101.1\" x2=\"346.0\" y2=\"101.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"91.4\" x2=\"346.0\" y2=\"91.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"81.8\" x2=\"346.0\" y2=\"81.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"72.1\" x2=\"346.0\" y2=\"72.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"52.7\" x2=\"346.0\" y2=\"52.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"43.0\" x2=\"346.0\" y2=\"43.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"33.4\" x2=\"346.0\" y2=\"33.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"23.7\" x2=\"346.0\" y2=\"23.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">150</text><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"125.5\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">160</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">170</text><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"272.5\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">180</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">190</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">40</text><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"211.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">50</text><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"163.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">60</text><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"114.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">70</text><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"66.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">80</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">90</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Height (cm)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Mass (kg)</text><clipPath id=\"c129106836\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c129106836)\"></g><line x1=\"62.2\" y1=\"212.8\" x2=\"71.2\" y2=\"221.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"62.2\" y1=\"221.8\" x2=\"71.2\" y2=\"212.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"91.6\" y1=\"193.4\" x2=\"100.6\" y2=\"202.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"91.6\" y1=\"202.4\" x2=\"100.6\" y2=\"193.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"183.7\" x2=\"130.0\" y2=\"192.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"192.7\" x2=\"130.0\" y2=\"183.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"150.4\" y1=\"154.7\" x2=\"159.4\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"150.4\" y1=\"163.7\" x2=\"159.4\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"179.8\" y1=\"145.0\" x2=\"188.8\" y2=\"154.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"179.8\" y1=\"154.0\" x2=\"188.8\" y2=\"145.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"209.2\" y1=\"125.7\" x2=\"218.2\" y2=\"134.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"209.2\" y1=\"134.7\" x2=\"218.2\" y2=\"125.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"238.6\" y1=\"106.3\" x2=\"247.6\" y2=\"115.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"238.6\" y1=\"115.3\" x2=\"247.6\" y2=\"106.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"268.0\" y1=\"86.9\" x2=\"277.0\" y2=\"95.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"268.0\" y1=\"95.9\" x2=\"277.0\" y2=\"86.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"297.4\" y1=\"67.6\" x2=\"306.4\" y2=\"76.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"297.4\" y1=\"76.6\" x2=\"306.4\" y2=\"67.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"38.5\" x2=\"174.1\" y2=\"47.5\" style=\"stroke:var(--danger);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"47.5\" x2=\"174.1\" y2=\"38.5\" style=\"stroke:var(--danger);stroke-width:2.4\"/><circle cx=\"169.6\" cy=\"43.0\" r=\"11\" style=\"fill:none;stroke:var(--danger);stroke-width:2\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Height and mass of 10 adults: (166, 84) is an outlier.</figcaption></figure><h4>Correlation is not causation</h4><p>Two quantities can be correlated because a <b>third factor</b> drives both. Ice cream sales and sunburn cases rise together, but ice cream does not cause sunburn: hot sunny weather causes both.</p><div class=\"ex\"><div class=\"exh\">Worked example · Describe the graph</div><div class=\"exl\">Temperature and hot drinks sold (graph in Practice 2).<br>The crosses fall from left to right and lie close to a line → <b>strong negative correlation</b>.<br>Relationship: as the temperature increases, the number of hot drinks sold <b>decreases</b>.</div></div><div class=\"keybox\"><b>Common mistakes.</b> Saying “negative correlation means no relationship”: negative is a real relationship. Using “correlation” words when asked for the relationship in context. Claiming one thing <i>causes</i> the other just because they are correlated.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise 2 →</button></div></section><section class=\"note\" id=\"n3\"><h2>3 · Lines of best fit</h2><p class=\"lt\"><b>Learning target:</b> I can draw a line of best fit, use it to estimate values, and say when an estimate is interpolation (reliable) or extrapolation (risky).</p><p>A <b>line of best fit</b> is a single straight line that follows the trend of the crosses. Draw it only when there is correlation.</p><div class=\"keybox\"><b>How to draw a line of best fit</b><br>1. Use a ruler: one straight line, not a zig-zag.<br>2. Follow the direction of the crosses.<br>3. Have roughly the same number of crosses on each side.<br>4. Pass through (or very close to) the <b>mean point</b> (mean of x, mean of y).<br>5. Ignore outliers. It does not have to pass through the origin or through any cross.</div><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"76.5\" y1=\"256.0\" x2=\"76.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"174.5\" y1=\"256.0\" x2=\"174.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"223.5\" y1=\"256.0\" x2=\"223.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"321.5\" y1=\"256.0\" x2=\"321.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"243.9\" x2=\"346.0\" y2=\"243.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"219.7\" x2=\"346.0\" y2=\"219.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"171.3\" x2=\"346.0\" y2=\"171.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"147.1\" x2=\"346.0\" y2=\"147.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"122.9\" x2=\"346.0\" y2=\"122.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"98.7\" x2=\"346.0\" y2=\"98.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"50.3\" x2=\"346.0\" y2=\"50.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"26.1\" x2=\"346.0\" y2=\"26.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"101.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">1</text><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"150.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">2</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">3</text><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"248.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">4</text><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"297.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">5</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">6</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"235.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"211.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">20</text><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"187.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">30</text><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"163.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">40</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">50</text><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"114.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">60</text><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"90.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">70</text><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"66.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">80</text><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"42.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">90</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">100</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Time spent revising (hours)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Test score (%)</text><clipPath id=\"c144435518\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c144435518)\"><line x1=\"52.0\" y1=\"201.8\" x2=\"346.0\" y2=\"33.1\" style=\"stroke:var(--success);stroke-width:2.4\"/></g><line x1=\"72.0\" y1=\"191.0\" x2=\"81.0\" y2=\"200.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"72.0\" y1=\"200.0\" x2=\"81.0\" y2=\"191.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"166.8\" x2=\"105.5\" y2=\"175.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"175.8\" x2=\"105.5\" y2=\"166.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"154.7\" x2=\"130.0\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"163.7\" x2=\"130.0\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"130.5\" x2=\"154.5\" y2=\"139.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"139.5\" x2=\"154.5\" y2=\"130.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"142.6\" x2=\"179.0\" y2=\"151.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"151.6\" x2=\"179.0\" y2=\"142.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"106.3\" x2=\"203.5\" y2=\"115.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"115.3\" x2=\"203.5\" y2=\"106.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"94.2\" x2=\"228.0\" y2=\"103.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"103.2\" x2=\"228.0\" y2=\"94.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"82.1\" x2=\"252.5\" y2=\"91.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"91.1\" x2=\"252.5\" y2=\"82.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"45.8\" x2=\"301.5\" y2=\"54.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"54.8\" x2=\"301.5\" y2=\"45.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"57.9\" x2=\"326.0\" y2=\"66.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"66.9\" x2=\"326.0\" y2=\"57.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Good: a ruled line through the middle of the crosses.</figcaption></figure><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"76.5\" y1=\"256.0\" x2=\"76.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"174.5\" y1=\"256.0\" x2=\"174.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"223.5\" y1=\"256.0\" x2=\"223.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"321.5\" y1=\"256.0\" x2=\"321.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"243.9\" x2=\"346.0\" y2=\"243.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"219.7\" x2=\"346.0\" y2=\"219.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"171.3\" x2=\"346.0\" y2=\"171.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"147.1\" x2=\"346.0\" y2=\"147.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"122.9\" x2=\"346.0\" y2=\"122.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"98.7\" x2=\"346.0\" y2=\"98.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"50.3\" x2=\"346.0\" y2=\"50.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"26.1\" x2=\"346.0\" y2=\"26.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"101.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">1</text><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"150.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">2</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">3</text><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"248.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">4</text><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"297.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">5</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">6</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"235.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"211.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">20</text><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"187.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">30</text><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"163.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">40</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">50</text><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"114.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">60</text><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"90.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">70</text><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"66.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">80</text><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"42.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">90</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">100</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Time spent revising (hours)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Test score (%)</text><clipPath id=\"c101085672\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c101085672)\"><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--danger);stroke-width:2.4;stroke-dasharray:7 5\"/></g><line x1=\"72.0\" y1=\"191.0\" x2=\"81.0\" y2=\"200.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"72.0\" y1=\"200.0\" x2=\"81.0\" y2=\"191.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"166.8\" x2=\"105.5\" y2=\"175.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"175.8\" x2=\"105.5\" y2=\"166.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"154.7\" x2=\"130.0\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"163.7\" x2=\"130.0\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"130.5\" x2=\"154.5\" y2=\"139.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"139.5\" x2=\"154.5\" y2=\"130.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"142.6\" x2=\"179.0\" y2=\"151.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"151.6\" x2=\"179.0\" y2=\"142.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"106.3\" x2=\"203.5\" y2=\"115.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"115.3\" x2=\"203.5\" y2=\"106.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"94.2\" x2=\"228.0\" y2=\"103.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"103.2\" x2=\"228.0\" y2=\"94.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"82.1\" x2=\"252.5\" y2=\"91.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"91.1\" x2=\"252.5\" y2=\"82.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"45.8\" x2=\"301.5\" y2=\"54.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"54.8\" x2=\"301.5\" y2=\"45.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"57.9\" x2=\"326.0\" y2=\"66.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"66.9\" x2=\"326.0\" y2=\"57.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Poor (red dashed): forced through the origin, so most crosses are below it.</figcaption></figure><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"76.5\" y1=\"256.0\" x2=\"76.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"125.5\" y1=\"256.0\" x2=\"125.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"174.5\" y1=\"256.0\" x2=\"174.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"223.5\" y1=\"256.0\" x2=\"223.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"272.5\" y1=\"256.0\" x2=\"272.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"321.5\" y1=\"256.0\" x2=\"321.5\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"243.9\" x2=\"346.0\" y2=\"243.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"219.7\" x2=\"346.0\" y2=\"219.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"171.3\" x2=\"346.0\" y2=\"171.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"147.1\" x2=\"346.0\" y2=\"147.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"122.9\" x2=\"346.0\" y2=\"122.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"98.7\" x2=\"346.0\" y2=\"98.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"50.3\" x2=\"346.0\" y2=\"50.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"26.1\" x2=\"346.0\" y2=\"26.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"101.0\" y1=\"256.0\" x2=\"101.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"101.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">1</text><line x1=\"150.0\" y1=\"256.0\" x2=\"150.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"150.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">2</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">3</text><line x1=\"248.0\" y1=\"256.0\" x2=\"248.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"248.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">4</text><line x1=\"297.0\" y1=\"256.0\" x2=\"297.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"297.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">5</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">6</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"235.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"211.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">20</text><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"187.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">30</text><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"163.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">40</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">50</text><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"114.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">60</text><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"90.6\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">70</text><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"66.4\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">80</text><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"42.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">90</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">100</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Time spent revising (hours)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Test score (%)</text><clipPath id=\"c506401628\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c506401628)\"><polyline points=\"76.5,195.5 101.0,171.3 125.5,159.2 150.0,135.0 174.5,147.1 199.0,110.8 223.5,98.7 248.0,86.6 297.0,50.3 321.5,62.4\" style=\"fill:none;stroke:var(--danger);stroke-width:2\"/></g><line x1=\"72.0\" y1=\"191.0\" x2=\"81.0\" y2=\"200.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"72.0\" y1=\"200.0\" x2=\"81.0\" y2=\"191.0\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"166.8\" x2=\"105.5\" y2=\"175.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"96.5\" y1=\"175.8\" x2=\"105.5\" y2=\"166.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"154.7\" x2=\"130.0\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"121.0\" y1=\"163.7\" x2=\"130.0\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"130.5\" x2=\"154.5\" y2=\"139.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"145.5\" y1=\"139.5\" x2=\"154.5\" y2=\"130.5\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"142.6\" x2=\"179.0\" y2=\"151.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"170.0\" y1=\"151.6\" x2=\"179.0\" y2=\"142.6\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"106.3\" x2=\"203.5\" y2=\"115.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"115.3\" x2=\"203.5\" y2=\"106.3\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"94.2\" x2=\"228.0\" y2=\"103.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"219.0\" y1=\"103.2\" x2=\"228.0\" y2=\"94.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"82.1\" x2=\"252.5\" y2=\"91.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"243.5\" y1=\"91.1\" x2=\"252.5\" y2=\"82.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"45.8\" x2=\"301.5\" y2=\"54.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"292.5\" y1=\"54.8\" x2=\"301.5\" y2=\"45.8\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"57.9\" x2=\"326.0\" y2=\"66.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"317.0\" y1=\"66.9\" x2=\"326.0\" y2=\"57.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">Wrong: joining the dots is not a line of best fit.</figcaption></figure><h4>Using the line to estimate</h4><p>To estimate y for a given x: go up from x to the line, then across to the y-axis. To estimate x for a given y: go across from y to the line, then down.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Interpolation</th><th>Extrapolation</th></tr><tr><td>estimating <b>inside</b> the range of the data</td><td>estimating <b>outside</b> the range of the data</td></tr><tr><td>usually reliable</td><td>risky: the pattern may not continue (scores cannot pass 100%, values cannot be negative, growth levels off)</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example · Mean point</div><div class=\"exl\">Data: (2, 14), (4, 18), (5, 25), (7, 27), (7, 31).<br>Mean x = (2 + 4 + 5 + 7 + 7) ÷ 5 = 25 ÷ 5 = 5<br>Mean y = (14 + 18 + 25 + 27 + 31) ÷ 5 = 115 ÷ 5 = 23<br>A good line of best fit passes close to (5, 23).</div></div><div class=\"keybox\"><b>Common mistakes.</b> Joining the dots. Forcing the line through the origin (0, 0). Letting an outlier pull the line. Trusting an estimate far outside the data (extrapolating).</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise 3 →</button></div></section><section class=\"note\" id=\"n4\"><h2>4 · Equation of a line of best fit</h2><p class=\"lt\"><b>Learning target:</b> I can find the gradient and intercept of a line of best fit, explain them in context and use the equation to predict.</p><p>A line of best fit is a straight line, so it has an equation <b>y = mx + c</b>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Part</th><th>How to find it</th><th>Meaning in context</th></tr><tr><td><b>m</b> (gradient)</td><td>pick two points far apart <b>on the line</b>: m = (change in y) ÷ (change in x)</td><td>how much y changes for each 1 unit increase in x</td></tr><tr><td><b>c</b> (intercept)</td><td>where the line crosses the y-axis (x = 0), or c = y − mx for a point on the line</td><td>the value of y when x = 0 (only meaningful if x = 0 makes sense)</td></tr></table></div><figure style=\"margin:8px 0\"><svg viewBox=\"0 0 360 300\" class=\"figsvg\" style=\"width:100%;max-width:440px\"><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"249.9\" x2=\"346.0\" y2=\"249.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"243.9\" x2=\"346.0\" y2=\"243.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"237.8\" x2=\"346.0\" y2=\"237.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"231.8\" x2=\"346.0\" y2=\"231.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"225.8\" x2=\"346.0\" y2=\"225.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"219.7\" x2=\"346.0\" y2=\"219.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"213.7\" x2=\"346.0\" y2=\"213.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"207.6\" x2=\"346.0\" y2=\"207.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"201.6\" x2=\"346.0\" y2=\"201.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"189.4\" x2=\"346.0\" y2=\"189.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"183.4\" x2=\"346.0\" y2=\"183.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"177.3\" x2=\"346.0\" y2=\"177.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"171.3\" x2=\"346.0\" y2=\"171.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"165.2\" x2=\"346.0\" y2=\"165.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"159.2\" x2=\"346.0\" y2=\"159.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"153.2\" x2=\"346.0\" y2=\"153.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"147.1\" x2=\"346.0\" y2=\"147.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"141.1\" x2=\"346.0\" y2=\"141.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"128.9\" x2=\"346.0\" y2=\"128.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"122.9\" x2=\"346.0\" y2=\"122.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"116.9\" x2=\"346.0\" y2=\"116.9\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"110.8\" x2=\"346.0\" y2=\"110.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"104.8\" x2=\"346.0\" y2=\"104.8\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"98.7\" x2=\"346.0\" y2=\"98.7\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"92.6\" x2=\"346.0\" y2=\"92.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"86.6\" x2=\"346.0\" y2=\"86.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"80.6\" x2=\"346.0\" y2=\"80.6\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"68.4\" x2=\"346.0\" y2=\"68.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"62.4\" x2=\"346.0\" y2=\"62.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"56.4\" x2=\"346.0\" y2=\"56.4\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"50.3\" x2=\"346.0\" y2=\"50.3\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"44.2\" x2=\"346.0\" y2=\"44.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"38.2\" x2=\"346.0\" y2=\"38.2\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"32.1\" x2=\"346.0\" y2=\"32.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"26.1\" x2=\"346.0\" y2=\"26.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"20.1\" x2=\"346.0\" y2=\"20.1\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"52.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"81.4\" y1=\"256.0\" x2=\"81.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"81.4\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">1</text><line x1=\"110.8\" y1=\"256.0\" x2=\"110.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"110.8\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">2</text><line x1=\"140.2\" y1=\"256.0\" x2=\"140.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"140.2\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">3</text><line x1=\"169.6\" y1=\"256.0\" x2=\"169.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"169.6\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">4</text><line x1=\"199.0\" y1=\"256.0\" x2=\"199.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"199.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">5</text><line x1=\"228.4\" y1=\"256.0\" x2=\"228.4\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"228.4\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">6</text><line x1=\"257.8\" y1=\"256.0\" x2=\"257.8\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"257.8\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">7</text><line x1=\"287.2\" y1=\"256.0\" x2=\"287.2\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"287.2\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">8</text><line x1=\"316.6\" y1=\"256.0\" x2=\"316.6\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"316.6\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">9</text><line x1=\"346.0\" y1=\"256.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"346.0\" y=\"271\" text-anchor=\"middle\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"260.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">0</text><line x1=\"52.0\" y1=\"225.8\" x2=\"346.0\" y2=\"225.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"229.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">10</text><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"195.5\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"199.5\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">20</text><line x1=\"52.0\" y1=\"165.2\" x2=\"346.0\" y2=\"165.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"169.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">30</text><line x1=\"52.0\" y1=\"135.0\" x2=\"346.0\" y2=\"135.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"139.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">40</text><line x1=\"52.0\" y1=\"104.8\" x2=\"346.0\" y2=\"104.8\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"108.8\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">50</text><line x1=\"52.0\" y1=\"74.5\" x2=\"346.0\" y2=\"74.5\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"78.5\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">60</text><line x1=\"52.0\" y1=\"44.2\" x2=\"346.0\" y2=\"44.2\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"48.2\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">70</text><line x1=\"52.0\" y1=\"14.0\" x2=\"346.0\" y2=\"14.0\" style=\"stroke:var(--rule);stroke-width:1.2\"/><text x=\"47\" y=\"18.0\" text-anchor=\"end\" style=\"font:11px sans-serif;fill:var(--ink-soft)\">80</text><line x1=\"52.0\" y1=\"256.0\" x2=\"346.0\" y2=\"256.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><line x1=\"52.0\" y1=\"256.0\" x2=\"52.0\" y2=\"14.0\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text x=\"199.0\" y=\"294\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Practice (hours)</text><text transform=\"translate(13,135.0) rotate(-90)\" text-anchor=\"middle\" style=\"font:600 12.5px sans-serif;fill:var(--ink)\">Score</text><clipPath id=\"c588328348\"><rect x=\"52\" y=\"14\" width=\"294\" height=\"242\"/></clipPath><g clip-path=\"url(#c588328348)\"><line x1=\"52.0\" y1=\"195.5\" x2=\"346.0\" y2=\"44.2\" style=\"stroke:var(--accent-text);stroke-width:2.4\"/></g><line x1=\"76.9\" y1=\"178.9\" x2=\"85.9\" y2=\"187.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"76.9\" y1=\"187.9\" x2=\"85.9\" y2=\"178.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"154.7\" x2=\"115.3\" y2=\"163.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"106.3\" y1=\"163.7\" x2=\"115.3\" y2=\"154.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"148.7\" x2=\"144.7\" y2=\"157.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"135.7\" y1=\"157.7\" x2=\"144.7\" y2=\"148.7\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"124.4\" x2=\"174.1\" y2=\"133.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"165.1\" y1=\"133.4\" x2=\"174.1\" y2=\"124.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"118.4\" x2=\"203.5\" y2=\"127.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"194.5\" y1=\"127.4\" x2=\"203.5\" y2=\"118.4\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"94.2\" x2=\"232.9\" y2=\"103.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"223.9\" y1=\"103.2\" x2=\"232.9\" y2=\"94.2\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"253.3\" y1=\"88.1\" x2=\"262.3\" y2=\"97.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"253.3\" y1=\"97.1\" x2=\"262.3\" y2=\"88.1\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"282.7\" y1=\"63.9\" x2=\"291.7\" y2=\"72.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"282.7\" y1=\"72.9\" x2=\"291.7\" y2=\"63.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"57.9\" x2=\"321.1\" y2=\"66.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/><line x1=\"312.1\" y1=\"66.9\" x2=\"321.1\" y2=\"57.9\" style=\"stroke:var(--ink);stroke-width:2.4\"/></svg><figcaption style=\"text-align:center;font-size:13.5px;color:var(--ink-soft)\">The line passes through (0, 20) and (8, 60).</figcaption></figure><div class=\"ex\"><div class=\"exh\">Worked example · Equation from the graph</div><div class=\"exl\">Two points on the line: (0, 20) and (8, 60).<br>m = (60 − 20) ÷ (8 − 0) = 40 ÷ 8 = 5<br>c = 20 (where the line meets the y-axis)<br>Equation: <b>y = 5x + 20</b>. Each extra hour of practice adds about 5 marks.</div></div><div class=\"ex\"><div class=\"exh\">Worked example · Predict with the equation</div><div class=\"exl\">The line of best fit for a scooter’s value is y = −5x + 60 (y in ₹ thousand, x = age in years).<br>Age 7: y = −5 × 7 + 60 = −35 + 60 = <b>25</b>, so about ₹25 thousand.<br>Value ₹35 thousand: 35 = −5x + 60 → 5x = 25 → x = <b>5</b> years.</div></div><div class=\"ex\"><div class=\"exh\">Worked example · Using the mean point</div><div class=\"exl\">A line of best fit has gradient 4 and passes through the mean point (6, 50).<br>c = y − mx = 50 − 4 × 6 = 50 − 24 = 26<br>Equation: y = 4x + 26.</div></div><div class=\"keybox\"><b>Common mistakes.</b> Using two data crosses that are not on the line. Writing run ÷ rise instead of rise ÷ run. Forgetting the minus sign when the line goes down. Reading the intercept from an axis that does not start at 0.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise 4 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Topic checklist</h2><ul><li>I can plot pairs of data as crosses, choose and read scales, and read values and counts from a scatter graph.</li><li>I can describe correlation (positive, negative, none; strong or weak), spot outliers and explain why correlation does not prove causation.</li><li>I can draw a line of best fit, use it to estimate values, and say when an estimate is interpolation (reliable) or extrapolation (risky).</li><li>I can find the gradient and intercept of a line of best fit, explain them in context and use the equation to predict.</li><li>I can answer multi-part exam questions that mix plotting, describing, estimating and explaining.</li><li>I never join the dots, never force a line through the origin, and I say “extrapolation” when I estimate outside the data.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn\" data-go=\"s7\">Assessment A</button><button class=\"hub-btn\" data-go=\"s8\">Assessment B</button><button class=\"hub-btn\" data-go=\"s9\">Assessment C</button><button class=\"hub-btn\" data-go=\"s10\">Assessment D</button><button class=\"hub-btn primary\" data-go=\"report\">📊 Report</button></div></section>";
var REPORT = [["s7", "A", "Knowing and understanding"], ["s8", "B", "Investigating patterns"], ["s9", "C", "Communicating"], ["s10", "D", "Applying mathematics in real-life contexts"]];
var SECTIONS = [{"id": "s1", "label": "1 · Plotting scatter graphs", "sub": "I can plot pairs of data as crosses, choose and read scales, and read values and counts from a scatter graph.", "slides": [{"kind": "mcq", "text": "What does a scatter graph show?", "opts": ["Pairs of values, to see if two quantities are linked", "The parts of a whole, shown as slices of a circle", "How a single quantity changes over time, joined by lines", "How often each value occurs in a single list of data"], "correct": 0, "tag": "", "sol": "A scatter graph plots pairs of values (x, y), one cross per pair, so you can see whether the two quantities are related. A line graph shows change over time, a pie chart shows parts of a whole and a bar chart shows frequencies."}, {"kind": "blank", "p": "The scatter graph shows the heights and arm spans of 8 students. Read the graph.", "tag": "", "marks": "", "flat": [{"t": "a) The tallest student is __B1__ cm tall.", "a": {"B1": "176"}}, {"t": "b) The tallest student’s arm span is __B1__ cm.", "a": {"B1": "174"}}, {"t": "c) The number of students with an arm span of more than 155 cm is __B1__.", "a": {"B1": "5"}}], "sol": "The right-most cross is at 176 cm (one small square is 2 cm).\nGo up from 176 to the cross, then across: 174 cm.\nCrosses above the 155 line: 158, 156, 166, 168 and 174 → 5 students.", "fig": "<div class=\"scatw\" data-xlo=\"140\" data-xhi=\"180\" data-xstep=\"10\" data-ylo=\"140\" data-yhi=\"180\" data-ystep=\"10\" data-xlab=\"Height (cm)\" data-ylab=\"Arm span (cm)\" data-xminor=\"2\" data-yminor=\"2\" data-pts=\"142,140; 148,150; 152,150; 156,158; 160,156; 164,166; 170,168; 176,174\"></div>"}, {"kind": "mcq", "text": "Asha records the hours each student revised and their test score. Which axis should each go on?", "opts": ["Test score across (x), hours revised up (y)", "Hours revised across (x), test score up (y)", "Both on the y-axis, as two colours", "It does not matter, so use the same scale for both"], "correct": 1, "tag": "", "sol": "Put the quantity that may affect the other (hours revised) on the horizontal x-axis and the quantity it may affect (the score) on the vertical y-axis."}, {"kind": "blank", "p": "A used-car website lists nine cars. Seven are on the graph. The other two are a 4-year-old car worth ₹340 thousand and a 7-year-old car worth ₹200 thousand.", "tag": "", "marks": "", "flat": [{"t": "Plot both cars on the scatter graph. __B1__", "a": {"B1": "4,340; 7,200"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Age of car (years)\" data-ylab=\"Value (₹ thousand)\" data-xminor=\"1\" data-yminor=\"20\" data-pts=\"1,520; 2,460; 3,420; 5,320; 6,260; 8,160; 9,120\" data-key=\"4,340; 7,200\" data-meta=\"tol:0.5,10.0\"></div>", "expr": "spts", "accept": ["tol:0.5,10.0"]}], "sol": "Across to 4, up to 340 (2 small squares above 300); across to 7, up to 200. One small square up is ₹20 thousand."}, {"kind": "mcq", "text": "On a y-axis, the labels go 0, 10, 20, 30, … and each big square is split into 5 small squares. What is one small square worth?", "opts": ["5", "1", "10", "2"], "correct": 3, "tag": "", "sol": "One big square is 10, split into 5 small squares: 10 ÷ 5 = 2."}, {"kind": "blank", "p": "An electrician records the length of some jobs and the charge.<br>Hours: 1, 2, 3, 4.5, 6, 7<br>Charge (₹): 600, 900, 1100, 1600, 1900, 2300", "tag": "", "marks": "", "flat": [{"t": "Plot all six jobs on the scatter graph. __B1__", "a": {"B1": "1,600; 2,900; 3,1100; 4.5,1600; 6,1900; 7,2300"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"8\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"3000\" data-ystep=\"500\" data-xlab=\"Length of job (hours)\" data-ylab=\"Charge (₹)\" data-xminor=\"0.5\" data-yminor=\"100\" data-pts=\"\" data-key=\"1,600; 2,900; 3,1100; 4.5,1600; 6,1900; 7,2300\" data-meta=\"tol:0.25,50.0\"></div>", "expr": "spts", "accept": ["tol:0.25,50.0"]}], "sol": "Each small square is 0.5 hour across and ₹100 up. Plot (1, 600), (2, 900), (3, 1100), (4.5, 1600), (6, 1900) and (7, 2300)."}, {"kind": "mcq", "text": "Hours of sunshine and visitors (hundreds) to a park:<br>(2, 30), (4, 45), (6, 50), (8, 70), (10, 75).<br>Which pair has been plotted <b>wrongly</b> on the graph?", "opts": ["(2, 30)", "(8, 70)", "(6, 50)", "(10, 75)"], "correct": 2, "tag": "", "sol": "The cross above 6 is at 55, one small square (5) too high. It should be at 50. The other crosses match the table.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"12\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"80\" data-ystep=\"10\" data-xlab=\"Hours of sunshine\" data-ylab=\"Visitors (hundreds)\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"2,30; 4,45; 6,55; 8,70; 10,75\"></div>"}, {"kind": "blank", "p": "Ten students recorded their revision time and test score. Six have been plotted. The other four are (3.5, 65), (4, 70), (5, 85) and (5.5, 80).", "tag": "", "marks": "", "flat": [{"t": "Complete the scatter graph. __B1__", "a": {"B1": "3.5,65; 4,70; 5,85; 5.5,80"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time spent revising (hours)\" data-ylab=\"Test score (%)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"0.5,25; 1,35; 1.5,40; 2,50; 2.5,45; 3,60\" data-key=\"3.5,65; 4,70; 5,85; 5.5,80\" data-meta=\"tol:0.25,2.5\"></div>", "expr": "spts", "accept": ["tol:0.25,2.5"]}], "sol": "One small square is 0.5 hour across and 5% up. Plot (3.5, 65), (4, 70), (5, 85) and (5.5, 80)."}, {"kind": "mcq", "text": "<b>Error analysis.</b> To plot (3, 40), Ravi went up to 3 and across to 40. What went wrong?", "opts": ["He should have gone across to 40 first and then down to 3", "He should also plot (40, 3) as a second point, to be safe", "Nothing: going up first or across first gives the same point", "He swapped the coordinates: go across to 3 first, then up to 40"], "correct": 3, "tag": "", "sol": "In (x, y) the first number is across and the second is up. Ravi plotted (40, 3) by mistake: go across to 3, then up to 40."}, {"kind": "blank", "p": "The graph shows the temperature and the number of ice creams sold on 13 days in May.", "tag": "", "marks": "", "flat": [{"t": "a) On another day it was 21 °C and 88 ice creams were sold. Plot this point. __B1__", "a": {"B1": "21,88"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"10\" data-xhi=\"35\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"160\" data-ystep=\"20\" data-xlab=\"Temperature (°C)\" data-ylab=\"Ice creams sold\" data-xminor=\"1\" data-yminor=\"4\" data-pts=\"12,24; 14,36; 16,40; 17,52; 19,60; 22,84; 23,96; 25,100; 26,112; 27,144; 29,128; 31,136; 15,132\" data-key=\"21,88\" data-meta=\"tol:0.5,2.0\"></div>", "expr": "spts", "accept": ["tol:0.5,2.0"]}, {"t": "b) On the hottest day, __B1__ ice creams were sold.", "a": {"B1": "136"}}, {"t": "c) The most ice creams were sold on a day when the temperature was __B1__ °C.", "a": {"B1": "27"}}], "sol": "Across to 21 (1 small square = 1 °C), up to 88 (one small square up is 4, so 88 is two small squares above 80).\nThe right-most cross is at 31 °C; across to the y-axis: 136.\nThe highest cross is at 144 ice creams; down to the x-axis: 27 °C."}, {"kind": "mcq", "text": "All ten revision points are now plotted. What percentage of the students scored 60% or more?", "opts": ["60%", "5%", "50%", "40%"], "correct": 2, "tag": "", "sol": "Scores of 60 or more: 60, 65, 70, 85, 80 → 5 students. 5 ÷ 10 × 100 = 50%. (5% is the count, not a percentage.)", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time spent revising (hours)\" data-ylab=\"Test score (%)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"0.5,25; 1,35; 1.5,40; 2,50; 2.5,45; 3,60; 3.5,65; 4,70; 5,85; 5.5,80\"></div>"}, {"kind": "blank", "p": "Use the completed revision graph.", "tag": "", "marks": "", "flat": [{"t": "a) The number of students who revised for more than 3 hours is __B1__.", "a": {"B1": "4"}}, {"t": "b) The number of students who scored less than 45% is __B1__.", "a": {"B1": "3"}}], "sol": "Crosses to the right of 3 hours: 3.5, 4, 5 and 5.5 → 4 (the cross at exactly 3 does not count).\nCrosses below 45: 25, 35 and 40 → 3 (45 itself is not less than 45).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time spent revising (hours)\" data-ylab=\"Test score (%)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"0.5,25; 1,35; 1.5,40; 2,50; 2.5,45; 3,60; 3.5,65; 4,70; 5,85; 5.5,80\"></div>"}, {"kind": "mcq", "text": "On the height and arm span graph, what does each cross stand for?", "opts": ["A height that appears twice in the class list", "The total arm span of all the students", "One student’s height and arm span together", "The mean height and mean arm span of the class"], "correct": 2, "tag": "", "sol": "Each cross is one pair of values: the height (across) and arm span (up) of the same student.", "fig": "<div class=\"scatw\" data-xlo=\"140\" data-xhi=\"180\" data-xstep=\"10\" data-ylo=\"140\" data-yhi=\"180\" data-ystep=\"10\" data-xlab=\"Height (cm)\" data-ylab=\"Arm span (cm)\" data-xminor=\"2\" data-yminor=\"2\" data-pts=\"142,140; 148,150; 152,150; 156,158; 160,156; 164,166; 170,168; 176,174\"></div>"}]}, {"id": "s2", "label": "2 · Correlation and relationships", "sub": "I can describe correlation (positive, negative, none; strong or weak), spot outliers and explain why correlation does not prove causation.", "slides": [{"kind": "mcq", "text": "What does <b>positive correlation</b> mean?", "opts": ["The two quantities are always equal", "As one quantity increases, the other tends to decrease", "As one quantity increases, the other tends to increase", "There is no link between the two quantities"], "correct": 2, "tag": "", "sol": "Positive correlation: the crosses go up from left to right, so as x increases, y tends to increase. Going down is negative correlation."}, {"kind": "blank", "p": "Describe the correlation shown by each graph. Type positive, negative or none.", "tag": "", "marks": "", "flat": [{"t": "a) __B1__", "a": {"B1": "positive"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,12; 2,15; 3,20; 4,22; 5,27; 6,30; 7,33; 8,38; 9,40\"></div>", "expr": "words", "accept": ["positive correlation", "strong positive", "strong positive correlation"]}, {"t": "b) __B1__", "a": {"B1": "negative"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,45; 2,42; 3,36; 4,33; 5,30; 6,24; 7,21; 8,15; 9,12\"></div>", "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}, {"t": "c) __B1__", "a": {"B1": "none"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,30; 2,12; 3,40; 4,22; 5,35; 6,15; 7,28; 8,42; 9,20; 2,35; 6,38; 8,14\"></div>", "expr": "words", "accept": ["no correlation", "no", "zero", "zero correlation"]}], "sol": "The crosses rise from left to right: positive correlation.\nThe crosses fall from left to right: negative correlation.\nThe crosses show no pattern: no correlation."}, {"kind": "mcq", "text": "Which description fits this scatter graph best?", "opts": ["No correlation", "Weak positive correlation", "Strong positive correlation", "Weak negative correlation"], "correct": 1, "tag": "", "sol": "The crosses go up from left to right, so the correlation is positive, but they are spread out a long way from a line, so it is weak.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,10; 2,25; 3,15; 4,30; 5,20; 6,38; 7,25; 8,40; 9,30; 3,30; 7,42; 5,12\"></div>"}, {"kind": "blank", "p": "The graph shows the heights and masses of 10 adults. One point is an outlier.", "tag": "", "marks": "", "flat": [{"t": "The outlier is at (__B1__ cm, __B2__ kg).", "a": {"B1": "166", "B2": "84"}}], "sol": "Every other cross is close to a rising line; (166, 84) is far above it (an adult of 166 cm would be expected to weigh about 61 kg).", "fig": "<div class=\"scatw\" data-xlo=\"150\" data-xhi=\"190\" data-xstep=\"10\" data-ylo=\"40\" data-yhi=\"90\" data-ystep=\"10\" data-xlab=\"Height (cm)\" data-ylab=\"Mass (kg)\" data-xminor=\"2\" data-yminor=\"2\" data-pts=\"152,48; 156,52; 160,54; 164,60; 168,62; 172,66; 176,70; 180,74; 184,78; 166,84\"></div>"}, {"kind": "mcq", "text": "A graph of distance from an airport (x) against the noise level measured at a house (y) shows strong negative correlation. Which sentence describes the <b>relationship</b>?", "opts": ["Distance from the airport has no effect on the noise level", "Houses with lower noise levels are closer to the airport", "The further a house is from the airport, the lower the noise level", "The further a house is from the airport, the higher the noise level"], "correct": 2, "tag": "", "sol": "Negative correlation: as one quantity increases, the other decreases. In context: as the distance increases, the noise level decreases."}, {"kind": "blank", "p": "The graph shows the temperature and the number of hot drinks sold at a café.", "tag": "", "marks": "", "flat": [{"t": "As the temperature increases, the number of hot drinks sold __B1__.", "a": {"B1": "decreases"}, "expr": "words", "accept": ["decrease", "goes down", "falls", "gets smaller", "drops", "reduces"]}], "sol": "The crosses fall from left to right (negative correlation), so the number of hot drinks sold decreases as it gets warmer.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"30\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"20\" data-xlab=\"Temperature (°C)\" data-ylab=\"Hot drinks sold\" data-xminor=\"1\" data-yminor=\"4\" data-pts=\"2,88; 5,80; 8,76; 11,64; 14,60; 17,48; 20,40; 23,36; 26,24; 29,20\"></div>"}, {"kind": "mcq", "text": "Over a summer, a town’s ice cream sales and the number of people treated for sunburn show strong positive correlation. Which statement is correct?", "opts": ["A correlation this strong proves that one causes the other", "Sunburn makes people buy more ice cream to cool down", "Eating ice cream causes sunburn, so sales predict sunburn cases", "Both rise in hot sunny weather; ice cream does not cause sunburn"], "correct": 3, "tag": "", "sol": "Correlation is not causation. A third factor, hot sunny weather, increases both. Banning ice cream would not reduce sunburn."}, {"kind": "blank", "p": "Describe the <b>strength</b> of the correlation in each graph. Type strong or weak.", "tag": "", "marks": "", "flat": [{"t": "a) __B1__", "a": {"B1": "strong"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,12; 2,15; 3,20; 4,22; 5,27; 6,30; 7,33; 8,38; 9,40\"></div>", "expr": "words", "accept": ["strong positive", "strong positive correlation"]}, {"t": "b) __B1__", "a": {"B1": "weak"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,40; 2,25; 3,35; 4,20; 5,30; 6,12; 7,25; 8,10; 9,20; 3,20; 7,8; 5,38\"></div>", "expr": "words", "accept": ["weak negative", "weak negative correlation"]}], "sol": "The crosses lie very close to a straight line: strong.\nThe crosses go down overall but are widely spread: weak."}, {"kind": "mcq", "text": "Which pair of quantities would you expect to show <b>negative</b> correlation?", "opts": ["Hours of revision and test score", "The age of a car and its value", "Temperature and ice creams sold", "A person’s height and their shoe size"], "correct": 1, "tag": "", "sol": "Older cars are usually worth less: as age increases, value decreases. The other three pairs would be expected to show positive correlation."}, {"kind": "blank", "p": "The graph shows the ages and heights of 9 children. One child’s height was recorded wrongly.", "tag": "", "marks": "", "flat": [{"t": "Tap the outlier to mark it. __B1__", "a": {"B1": "6,140"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"4\" data-xhi=\"12\" data-xstep=\"1\" data-ylo=\"90\" data-yhi=\"160\" data-ystep=\"10\" data-xlab=\"Age (years)\" data-ylab=\"Height (cm)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"4,102; 5,108; 6,114; 7,120; 8,126; 9,132; 10,138; 11,144; 6,140\" data-key=\"6,140\" data-meta=\"tol:0.5,1.0\"></div>", "expr": "spts", "accept": ["tol:0.5,1.0"]}], "sol": "The crosses rise steadily by about 6 cm a year; (6, 140) is far above that line (a 6-year-old would be about 114 cm), so it is the outlier."}, {"kind": "mcq", "text": "<b>Error analysis.</b> In a primary school, shoe size and reading score show positive correlation. Aarav says: “So bigger feet make you a better reader.” What is wrong?", "opts": ["Nothing: a positive correlation proves that bigger feet help reading", "The correlation must really be negative, as reading falls with age", "Shoe size and reading score cannot be plotted on one scatter graph", "Age is a third factor: older children have bigger feet and read better"], "correct": 3, "tag": "", "sol": "Correlation does not show cause. Older children tend to have both bigger feet and better reading, so age links the two quantities."}, {"kind": "blank", "p": "A class took tests in Maths, Music and Science. Describe each correlation. Type positive, negative or none.", "tag": "", "marks": "", "flat": [{"t": "a) Maths and Music: __B1__", "a": {"B1": "none"}, "fig": "<div class=\"scatw\" data-xlo=\"20\" data-xhi=\"100\" data-xstep=\"20\" data-ylo=\"20\" data-yhi=\"100\" data-ystep=\"20\" data-xlab=\"Maths score\" data-ylab=\"Music score\" data-xminor=\"10\" data-yminor=\"10\" data-pts=\"30,70; 38,40; 45,85; 50,55; 56,30; 62,75; 68,45; 72,90; 78,50; 85,35; 92,65\"></div>", "expr": "words", "accept": ["no correlation", "no", "zero", "zero correlation"]}, {"t": "b) Maths and Science: __B1__", "a": {"B1": "positive"}, "fig": "<div class=\"scatw\" data-xlo=\"20\" data-xhi=\"100\" data-xstep=\"20\" data-ylo=\"20\" data-yhi=\"100\" data-ystep=\"20\" data-xlab=\"Maths score\" data-ylab=\"Science score\" data-xminor=\"10\" data-yminor=\"10\" data-pts=\"30,34; 38,36; 45,52; 50,46; 56,60; 62,58; 68,74; 72,70; 78,84; 85,80; 92,94\"></div>", "expr": "words", "accept": ["positive correlation", "strong positive", "strong positive correlation"]}], "sol": "The Music scores are scattered with no pattern as the Maths score increases: no correlation.\nStudents with higher Maths scores also have higher Science scores: positive correlation."}, {"kind": "mcq", "text": "A data point turns out to be a recording mistake. What should you do with it when you draw a line of best fit?", "opts": ["Delete all the other points and keep only this one", "Make the line pass through it, since it is real data", "Ignore it, because it does not fit the pattern", "Move the whole line part of the way towards it"], "correct": 2, "tag": "", "sol": "An outlier, especially a mistake, would pull the line away from the trend of the other points, so leave it out when drawing the line."}]}, {"id": "s3", "label": "3 · Lines of best fit", "sub": "I can draw a line of best fit, use it to estimate values, and say when an estimate is interpolation (reliable) or extrapolation (risky).", "slides": [{"kind": "mcq", "text": "Which of these describes a good line of best fit?", "opts": ["A smooth curve passing through the highest points on the graph", "A ruled straight line with about equal numbers of points on each side", "A ruled line from the origin (0, 0) to the last point plotted", "A line joining every point in order from left to right"], "correct": 1, "tag": "", "sol": "A line of best fit is one straight ruled line following the trend, with about as many crosses above it as below it. It need not pass through the origin or any cross."}, {"kind": "blank", "p": "The graph shows revision time and test score for 10 students.", "tag": "", "marks": "", "flat": [{"t": "Draw a line of best fit. __B1__", "a": {"B1": "11.6184,22.3876,12,0.5,5.5"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time spent revising (hours)\" data-ylab=\"Test score (%)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"0.5,25; 1,35; 1.5,40; 2,50; 2.5,45; 3,60; 3.5,65; 4,70; 5,85; 5.5,80\" data-key=\"11.6184,22.3876,12,0.5,5.5\"></div>", "expr": "slbf"}], "sol": "A good line passes close to the mean point (2.85, 55.5) with about half the crosses on each side, e.g. from about (0.5, 28) to (5.5, 86)."}, {"kind": "mcq", "text": "Is the line on this graph a good line of best fit?", "opts": ["Yes: it starts at the origin", "No: every point is below the line", "No: it should join all the points", "Yes: it is a straight ruled line"], "correct": 1, "tag": "", "sol": "All the crosses lie below the line, so it does not go through the middle of the data. A line of best fit needs roughly equal numbers of crosses on each side.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time spent revising (hours)\" data-ylab=\"Test score (%)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"0.5,25; 1,35; 1.5,40; 2,50; 2.5,45; 3,60; 3.5,65; 4,70; 5,85; 5.5,80\" data-line=\"10,55\"></div>"}, {"kind": "blank", "p": "The graph shows the ages and values of 9 cars.", "tag": "", "marks": "", "flat": [{"t": "Draw a line of best fit. __B1__", "a": {"B1": "-50.3333,562.778,72,1,9"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Age of car (years)\" data-ylab=\"Value (₹ thousand)\" data-xminor=\"1\" data-yminor=\"20\" data-pts=\"1,520; 2,460; 3,420; 5,320; 6,260; 8,160; 9,120; 4,340; 7,200\" data-key=\"-50.3333,562.778,72,1,9\"></div>", "expr": "slbf"}], "sol": "The correlation is negative, so the line slopes down: e.g. from about (1, 512) to (9, 110), passing near the mean point (5, 311)."}, {"kind": "mcq", "text": "For a set of data the mean of x is 6 and the mean of y is 40. Which point should a line of best fit pass through (or very close to)?", "opts": ["(6, 40)", "(0, 0)", "(6, 0)", "(40, 6)"], "correct": 0, "tag": "", "sol": "A line of best fit passes through (or close to) the mean point (mean of x, mean of y) = (6, 40)."}, {"kind": "blank", "p": "Data: (2, 14), (4, 18), (5, 25), (7, 27), (7, 31). Find the mean point.", "tag": "", "marks": "", "flat": [{"t": "Mean of x = __B1__", "a": {"B1": "5"}}, {"t": "Mean of y = __B1__", "a": {"B1": "23"}}], "sol": "(2 + 4 + 5 + 7 + 7) ÷ 5 = 25 ÷ 5 = 5.\n(14 + 18 + 25 + 27 + 31) ÷ 5 = 115 ÷ 5 = 23."}, {"kind": "mcq", "text": "A job cost ₹1400. Use the line of best fit to estimate how long it lasted.", "opts": ["3 hours", "4 hours", "6 hours", "5 hours"], "correct": 1, "tag": "", "sol": "Go across from ₹1400 to the line, then down: 4 hours (check: 250 × 4 + 400 = 1400).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"8\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"3000\" data-ystep=\"500\" data-xlab=\"Length of job (hours)\" data-ylab=\"Charge (₹)\" data-xminor=\"0.5\" data-yminor=\"100\" data-pts=\"1,600; 2,900; 3,1100; 4.5,1600; 6,1900; 7,2300\" data-line=\"250,400\"></div>"}, {"kind": "blank", "p": "Use the line of best fit drawn on the hot drinks graph.", "tag": "", "marks": "", "flat": [{"t": "a) At 10 °C, about __B1__ hot drinks are sold.", "a": {"B1": "68"}}, {"t": "b) When 32 hot drinks are sold, the temperature is about __B1__ °C.", "a": {"B1": "25"}}], "sol": "Up from 10 to the line, then across: 68 (one small square up is 4).\nAcross from 32 to the line, then down: 25 °C.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"30\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"20\" data-xlab=\"Temperature (°C)\" data-ylab=\"Hot drinks sold\" data-xminor=\"1\" data-yminor=\"4\" data-pts=\"2,88; 5,80; 8,76; 11,64; 14,60; 17,48; 20,40; 23,36; 26,24; 29,20\" data-line=\"-2.4,92\"></div>"}, {"kind": "mcq", "text": "What is <b>extrapolation</b>?", "opts": ["Removing an outlier from the data", "Estimating a value outside the range of the data", "Drawing a line through the origin", "Estimating a value inside the range of the data"], "correct": 1, "tag": "", "sol": "Extrapolation means using the line beyond the data you have; interpolation means estimating within the data. Extrapolation is less reliable."}, {"kind": "blank", "p": "The electrician’s data cover jobs from 1 to 7 hours. Is each estimate interpolation or extrapolation?", "tag": "", "marks": "", "flat": [{"t": "a) The charge for a 5-hour job: __B1__", "a": {"B1": "interpolation"}, "expr": "words", "accept": ["interpolate"]}, {"t": "b) The charge for a 15-hour job: __B1__", "a": {"B1": "extrapolation"}, "expr": "words", "accept": ["extrapolate"]}], "sol": "5 hours is between 1 and 7 hours: interpolation.\n15 hours is beyond 7 hours: extrapolation.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"8\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"3000\" data-ystep=\"500\" data-xlab=\"Length of job (hours)\" data-ylab=\"Charge (₹)\" data-xminor=\"0.5\" data-yminor=\"100\" data-pts=\"1,600; 2,900; 3,1100; 4.5,1600; 6,1900; 7,2300\" data-line=\"250,400\"></div>"}, {"kind": "mcq", "text": "Why might it not be sensible to use this line to estimate the charge for a 15-hour job?", "opts": ["15 hours is not a whole number of working days", "The line does not pass through the origin, so it cannot be used", "15 hours is outside the data, so the pattern may not continue", "There are too many points lying close to the line"], "correct": 2, "tag": "", "sol": "The longest job in the data is 7 hours. Beyond that the electrician might charge a day rate or a discount, so the line may not apply (extrapolation)."}, {"kind": "blank", "p": "The graph shows the temperature and hot drinks sold.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "-2.60202,93.9313,12,2,29"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"30\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"20\" data-xlab=\"Temperature (°C)\" data-ylab=\"Hot drinks sold\" data-xminor=\"1\" data-yminor=\"4\" data-pts=\"2,88; 5,80; 8,76; 11,64; 14,60; 17,48; 20,40; 23,36; 26,24; 29,20\" data-key=\"-2.60202,93.9313,12,2,29\"></div>", "expr": "slbf"}, {"t": "b) Using your line to estimate sales at 15 °C is called __B1__.", "a": {"B1": "interpolation"}, "expr": "words", "accept": ["interpolate"]}], "sol": "Negative correlation, so slope down: e.g. from about (2, 89) to (29, 18).\n15 °C is inside the data (2 °C to 29 °C): interpolation."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Meena draws her line of best fit by joining each cross to the next one. What is wrong?", "opts": ["She should only join the highest crosses, not all of them", "A line of best fit is one straight line through the middle of the data", "Nothing: joining the crosses in order is the correct method", "She should join the crosses, but start the line from the origin"], "correct": 1, "tag": "", "sol": "Joining the dots gives a zig-zag that shows every wobble in the data. A line of best fit is a single straight line showing the trend."}, {"kind": "blank", "p": "Use the line of best fit drawn on the car graph.", "tag": "", "marks": "", "flat": [{"t": "a) A 4-year-old car is worth about ₹__B1__ thousand.", "a": {"B1": "360"}}, {"t": "b) A car worth ₹260 thousand is about __B1__ years old.", "a": {"B1": "6"}}], "sol": "Up from 4 to the line, then across: 360 (one small square up is ₹20 thousand). Use the line, not the cross at (4, 340).\nAcross from 260 to the line, then down: 6 years.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Age of car (years)\" data-ylab=\"Value (₹ thousand)\" data-xminor=\"1\" data-yminor=\"20\" data-pts=\"1,520; 2,460; 3,420; 5,320; 6,260; 8,160; 9,120; 4,340; 7,200\" data-line=\"-50,560\"></div>"}]}, {"id": "s4", "label": "4 · Equation of a line of best fit", "sub": "I can find the gradient and intercept of a line of best fit, explain them in context and use the equation to predict.", "slides": [{"kind": "mcq", "text": "A line of best fit has equation y = mx + c. What do m and c tell you?", "opts": ["m is the gradient, c is where the line crosses the y-axis", "m and c are the coordinates of the first point", "m is the mean of x, c is the mean of y", "m is where the line crosses the y-axis, c is the gradient"], "correct": 0, "tag": "", "sol": "In y = mx + c, m is the gradient (change in y for each 1 unit of x) and c is the y-intercept (the value of y when x = 0)."}, {"kind": "blank", "p": "The line of best fit passes through (0, 20) and (8, 60).", "tag": "", "marks": "", "flat": [{"t": "Gradient m = __B1__", "a": {"B1": "5"}}, {"t": "Intercept c = __B1__", "a": {"B1": "20"}}], "sol": "m = (60 − 20) ÷ (8 − 0) = 40 ÷ 8 = 5.\nThe line crosses the y-axis at 20, so c = 20. Equation: y = 5x + 20.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"80\" data-ystep=\"10\" data-xlab=\"Practice (hours)\" data-ylab=\"Score\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,24; 2,32; 3,34; 4,42; 5,44; 6,52; 7,54; 8,62; 9,64\" data-line=\"5,20\"></div>"}, {"kind": "mcq", "text": "Which equation most closely represents a line of best fit for this plant data?", "opts": ["y = 2x + 20", "y = 10x + 2", "y = 2x + 10", "y = −2x + 10"], "correct": 2, "tag": "", "sol": "The line rises about 2 cm a week and would meet the y-axis near 10 cm: y = 2x + 10 (least-squares line y ≈ 1.97x + 10.2). 10x + 2 is far too steep, 2x + 20 lies above every cross and −2x + 10 slopes down.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"40\" data-ystep=\"10\" data-xlab=\"Time (weeks)\" data-ylab=\"Plant height (cm)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,14; 3,16; 4,18; 5,22; 6,20; 7,24; 8,26; 9,28\"></div>"}, {"kind": "blank", "p": "A line of best fit for marks (y) against hours of practice (x) is y = 2.5x + 40.", "tag": "", "marks": "", "flat": [{"t": "a) Predicted mark for 8 hours: __B1__", "a": {"B1": "60"}}, {"t": "b) Hours of practice for a mark of 75: __B1__", "a": {"B1": "14"}}], "sol": "y = 2.5 × 8 + 40 = 20 + 40 = 60.\n75 = 2.5x + 40 → 2.5x = 35 → x = 14."}, {"kind": "mcq", "text": "For the practice data the line of best fit is y = 5x + 20. What does the gradient 5 mean?", "opts": ["Each extra hour of practice adds about 5 marks", "The score with no practice is about 5", "Every student practised for 5 hours", "The score goes down by 5 marks per hour"], "correct": 0, "tag": "", "sol": "The gradient is the change in y for each 1 unit increase in x: about 5 more marks for each extra hour. The intercept 20 is the score with no practice."}, {"kind": "blank", "p": "The line of best fit for a scooter’s value passes through (0, 60) and (10, 10).", "tag": "", "marks": "", "flat": [{"t": "Gradient m = __B1__", "a": {"B1": "-5"}}, {"t": "Intercept c = __B1__", "a": {"B1": "60"}}], "sol": "m = (10 − 60) ÷ (10 − 0) = −50 ÷ 10 = −5 (negative: the line goes down).\nThe line crosses the y-axis at 60, so c = 60. Equation: y = −5x + 60.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"70\" data-ystep=\"10\" data-xlab=\"Age of scooter (years)\" data-ylab=\"Value (₹ thousand)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,56; 2,50; 3,44; 4,42; 5,34; 6,30; 7,26; 8,20; 9,14\" data-line=\"-5,60\"></div>"}, {"kind": "mcq", "text": "For the scooters, y = −5x + 60 (y in ₹ thousand, x in years). What does the intercept 60 mean?", "opts": ["The oldest scooter is 60 years old", "A scooter loses ₹60 thousand a year", "A new scooter (age 0) is worth about ₹60 thousand", "A scooter is worth nothing after 60 years"], "correct": 2, "tag": "", "sol": "c is the value of y when x = 0: a brand-new scooter is worth about ₹60 thousand. The gradient −5 means it loses about ₹5 thousand a year."}, {"kind": "blank", "p": "Use y = −5x + 60 for the scooters.", "tag": "", "marks": "", "flat": [{"t": "a) Value of a 7-year-old scooter: ₹__B1__ thousand", "a": {"B1": "25"}}, {"t": "b) Age of a scooter worth ₹35 thousand: __B1__ years", "a": {"B1": "5"}}], "sol": "y = −5 × 7 + 60 = −35 + 60 = 25.\n35 = −5x + 60 → 5x = 25 → x = 5."}, {"kind": "mcq", "text": "The scooter data cover ages 1 to 9 years. Which prediction from y = −5x + 60 is the most reliable?", "opts": ["The age when the value is ₹0", "The value at 15 years", "The value at 13 years", "The value at 5 years"], "correct": 3, "tag": "", "sol": "5 years is inside the data (interpolation). 13 and 15 years are outside it, and the line gives −₹5 thousand and −₹15 thousand, which are impossible; the age for ₹0 (12 years) is also beyond the data."}, {"kind": "blank", "p": "A line of best fit has gradient 4 and passes through the mean point (6, 50).", "tag": "", "marks": "", "flat": [{"t": "Intercept c = __B1__", "a": {"B1": "26"}}, {"t": "Prediction for x = 9: y = __B1__", "a": {"B1": "62"}}], "sol": "c = y − mx = 50 − 4 × 6 = 50 − 24 = 26.\ny = 4 × 9 + 26 = 36 + 26 = 62."}, {"kind": "mcq", "text": "A phone’s battery level (y %) after x hours of use is modelled by y = −8x + 100. What does −8 mean?", "opts": ["The battery lasts 8 hours", "The battery level falls by about 8% each hour", "The battery starts at 8%", "The battery level rises by about 8% each hour"], "correct": 1, "tag": "", "sol": "The gradient is −8: for each extra hour, the battery level goes down by about 8 percentage points. It starts at 100% (the intercept)."}, {"kind": "blank", "p": "Use y = −8x + 100 for the battery.", "tag": "", "marks": "", "flat": [{"t": "a) Battery level after 5 hours: __B1__%", "a": {"B1": "60"}}, {"t": "b) Hours until the battery reaches 20%: __B1__", "a": {"B1": "10"}}], "sol": "y = −8 × 5 + 100 = −40 + 100 = 60.\n20 = −8x + 100 → 8x = 80 → x = 10."}, {"kind": "mcq", "text": "<b>Error analysis.</b> A line passes through (2, 30) and (10, 70). Kabir writes gradient = (10 − 2) ÷ (70 − 30) = 0.2. What went wrong?", "opts": ["He should have used (0, 0) as one of the two points", "He should add the coordinates instead: 12 ÷ 100 = 0.12", "He divided change in x by change in y; it should be 40 ÷ 8 = 5", "Nothing: the gradient of this line really is 0.2"], "correct": 2, "tag": "", "sol": "Gradient = change in y ÷ change in x = (70 − 30) ÷ (10 − 2) = 40 ÷ 8 = 5. Kabir worked out run ÷ rise."}, {"kind": "blank", "p": "The graph shows hours of training and fitness scores for 11 people.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "3.94545,21.6,8,1,11"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"12\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"90\" data-ystep=\"10\" data-xlab=\"Hours of training\" data-ylab=\"Fitness score\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,26; 2,28; 3,36; 4,36; 5,42; 6,44; 7,48; 8,54; 9,58; 10,62; 11,64\" data-key=\"3.94545,21.6,8,1,11\"></div>", "expr": "slbf"}, {"t": "b) A reasonable line passes through (2, 30) and (10, 62). Its gradient is __B1__", "a": {"B1": "4"}}, {"t": "c) Its intercept is c = __B1__", "a": {"B1": "22"}}], "sol": "Positive correlation: e.g. from about (1, 26) to (11, 65).\nm = (62 − 30) ÷ (10 − 2) = 32 ÷ 8 = 4.\nc = 30 − 4 × 2 = 22, so y = 4x + 22."}]}, {"id": "s5", "label": "5 · Exam practice", "sub": "I can answer multi-part exam questions that mix plotting, describing, estimating and explaining.", "slides": [{"kind": "blank", "p": "The table shows how many hours 10 students worked in part-time jobs last month and what they earned.", "tag": "", "marks": "", "flat": [{"t": "a) Plot the data on the scatter graph. __B1__", "a": {"B1": "24,20; 27,26; 30,28; 33,34; 35,30; 38,40; 41,42; 44,46; 47,48; 29,34"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"20\" data-xhi=\"50\" data-xstep=\"5\" data-ylo=\"10\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Hours worked last month\" data-ylab=\"Earnings (₹ hundred)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"\" data-key=\"24,20; 27,26; 30,28; 33,34; 35,30; 38,40; 41,42; 44,46; 47,48; 29,34\" data-meta=\"tol:0.5,1.0\"></div>", "expr": "spts", "accept": ["tol:0.5,1.0"]}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation", "strong positive", "strong positive correlation"]}], "sol": "One small square is 1 hour across and ₹2 hundred up. Plot all 10 pairs from the table.\nThe crosses rise from left to right: positive correlation.", "fig": "<div class=\"tscroll\"><table class=\"ttab\" style=\"width:auto;min-width:0\"><tr><th>Hours worked</th><td>24</td><td>27</td><td>30</td><td>33</td><td>35</td><td>38</td><td>41</td><td>44</td><td>47</td><td>29</td></tr><tr><th>Earnings (₹ hundred)</th><td>20</td><td>26</td><td>28</td><td>34</td><td>30</td><td>40</td><td>42</td><td>46</td><td>48</td><td>34</td></tr></table></div>"}, {"kind": "mcq", "text": "Describe the <b>relationship</b> between hours worked and earnings for these 10 students.", "opts": ["Working more hours always means earning more", "As hours worked increase, earnings tend to increase", "There is no relationship between hours and earnings", "As hours worked increase, earnings tend to decrease"], "correct": 1, "tag": "", "sol": "Positive correlation, written in context: students who worked more hours tend to earn more. “Always” is too strong: the student who worked 29 hours earned ₹3400, more than the one who worked 35 hours (₹3000).", "fig": "<div class=\"scatw\" data-xlo=\"20\" data-xhi=\"50\" data-xstep=\"5\" data-ylo=\"10\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Hours worked last month\" data-ylab=\"Earnings (₹ hundred)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"24,20; 27,26; 30,28; 33,34; 35,30; 38,40; 41,42; 44,46; 47,48; 29,34\"></div>"}, {"kind": "blank", "p": "A stall records the temperature and the number of bottles of water sold on 11 days.", "tag": "", "marks": "", "flat": [{"t": "a) On another day it was 25 °C and 112 bottles were sold. Plot this point. __B1__", "a": {"B1": "25,112"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"10\" data-xhi=\"40\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"200\" data-ystep=\"40\" data-xlab=\"Temperature (°C)\" data-ylab=\"Bottles of water sold\" data-xminor=\"1\" data-yminor=\"8\" data-pts=\"14,40; 16,48; 18,64; 20,72; 22,80; 24,96; 26,104; 28,120; 30,40; 32,144; 34,152\" data-key=\"25,112\" data-meta=\"tol:0.5,4.0\"></div>", "expr": "spts", "accept": ["tol:0.5,4.0"]}, {"t": "b) The outlier is at (__B1__ °C, __B2__ bottles).", "a": {"B1": "30", "B2": "40"}}, {"t": "c) The most bottles were sold on a day when the temperature was __B1__ °C.", "a": {"B1": "34"}}, {"t": "d) Describe the correlation: __B1__", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation", "strong positive", "strong positive correlation"]}], "sol": "Across to 25, up to 112 (one small square up is 8 bottles: 112 = 104 + 8).\n(30, 40) is far below the rising pattern (about 130 bottles would be expected); maybe it rained that day.\nThe highest cross is 152 bottles, at 34 °C.\nApart from the outlier the crosses rise steeply and closely: positive correlation."}, {"kind": "mcq", "text": "Why would it be unreliable to use this graph to estimate sales on a 45 °C day?", "opts": ["Hot days always produce outliers, so no estimate is possible", "45 °C is outside the data, so the trend may not continue", "The graph shows negative correlation, so sales would fall", "45 °C does not lie on one of the labelled grid lines"], "correct": 1, "tag": "", "sol": "The data go up to 34 °C (and the axis to 40 °C). Estimating at 45 °C is extrapolation: on extreme days the stall could sell out or people might stay indoors."}, {"kind": "blank", "p": "Mira ran 15 races of 5 km. The graph shows the temperature at the start of each race and her time.", "tag": "", "marks": "", "flat": [{"t": "a) In another race it was 19 °C and she took 27 minutes. Plot this point. __B1__", "a": {"B1": "19,27"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"10\" data-xhi=\"40\" data-xstep=\"5\" data-ylo=\"15\" data-yhi=\"45\" data-ystep=\"5\" data-xlab=\"Temperature at the start (°C)\" data-ylab=\"Time for 5 km (minutes)\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"12,20; 14,22; 15,21; 17,24; 18,26; 20,25; 21,28; 23,29; 25,31; 26,30; 28,33; 30,34; 33,37; 35,38; 16,36\" data-key=\"19,27\" data-meta=\"tol:0.5,0.5\"></div>", "expr": "spts", "accept": ["tol:0.5,0.5"]}, {"t": "b) Her quickest time in the 15 races was __B1__ minutes.", "a": {"B1": "20"}}, {"t": "c) The number of the 15 races in which she took less than half an hour is __B1__.", "a": {"B1": "8"}}, {"t": "d) Describe the correlation: __B1__", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation", "strong positive", "strong positive correlation"]}], "sol": "Across to 19, up to 27 (one small square = 1 in both directions).\nThe lowest cross is at 20 minutes.\nHalf an hour = 30 minutes. Crosses below 30: 20, 22, 21, 24, 26, 25, 28, 29 → 8 (the cross at exactly 30 is not less than 30).\nHotter races go with slower (larger) times: positive correlation."}, {"kind": "mcq", "text": "Mira runs another race at 32 °C. Use a line of best fit (ignore the outlier) to estimate her time.", "opts": ["About 22 minutes", "About 36 minutes", "About 30 minutes", "About 42 minutes"], "correct": 1, "tag": "", "sol": "A line of best fit through the other 14 races gives about 35.9 minutes at 32 °C (between the crosses at 30 °C → 34 min and 33 °C → 37 min), so about 36 minutes.", "fig": "<div class=\"scatw\" data-xlo=\"10\" data-xhi=\"40\" data-xstep=\"5\" data-ylo=\"15\" data-yhi=\"45\" data-ystep=\"5\" data-xlab=\"Temperature at the start (°C)\" data-ylab=\"Time for 5 km (minutes)\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"12,20; 14,22; 15,21; 17,24; 18,26; 20,25; 21,28; 23,29; 25,31; 26,30; 28,33; 30,34; 33,37; 35,38; 16,36\"></div>"}, {"kind": "blank", "p": "The graph shows the distance driven and the value of 11 used cars, with a line of best fit.", "tag": "", "marks": "", "flat": [{"t": "a) Estimate the value of a car that has been driven 40 thousand km: ₹__B1__ thousand", "a": {"B1": "460"}}, {"t": "b) Estimate the distance driven by a car worth ₹220 thousand: __B1__ thousand km", "a": {"B1": "80"}}, {"t": "c) Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}], "sol": "Up from 40 to the line, then across: 460 (one small square up is ₹20 thousand).\nAcross from 220 to the line, then down: 80 thousand km (one small square across is 5).\nThe more a car has been driven, the lower its value: negative correlation.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"100\" data-xstep=\"20\" data-ylo=\"0\" data-yhi=\"800\" data-ystep=\"100\" data-xlab=\"Distance driven (thousand km)\" data-ylab=\"Value (₹ thousand)\" data-xminor=\"5\" data-yminor=\"20\" data-pts=\"10,640; 20,600; 30,500; 35,520; 45,420; 50,380; 60,360; 70,260; 75,280; 85,180; 90,160\" data-line=\"-6,700\"></div>"}, {"kind": "mcq", "text": "Why might the line not be appropriate for a car that has been driven 150 thousand km?", "opts": ["Cars are never driven as far as 150 thousand km", "It is outside the data, and the line would give a negative value", "The line would give a value above ₹700 thousand", "The correlation would become positive after 100 thousand km"], "correct": 1, "tag": "", "sol": "150 is far beyond the data (10 to 90 thousand km). The line gives −6 × 150 + 700 = −200, a negative value, which is impossible. Extrapolation is unreliable."}, {"kind": "blank", "p": "The graph shows the distance of 15 villages from a city and the price of a building plot in each village, with a line of best fit.", "tag": "", "marks": "", "flat": [{"t": "a) The number of villages where a plot costs less than ₹15 lakh is __B1__.", "a": {"B1": "5"}}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}, {"t": "c) Use the line to estimate the price of a plot in a village 6.5 km from the city: ₹__B1__ lakh", "a": {"B1": "13"}}], "sol": "Crosses below 15: 14, 12, 10, 11, 8 → 5 (the village at exactly 15 does not count).\nPrices fall as the distance increases: negative correlation.\nUp from 6.5 to the line, then across: 13.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"30\" data-ystep=\"5\" data-xlab=\"Distance from the city (km)\" data-ylab=\"Price of a plot (₹ lakh)\" data-xminor=\"0.5\" data-yminor=\"1\" data-pts=\"0.5,27; 1,25; 1.5,22; 2,24; 2.5,20; 3,21; 3.5,18; 4,19; 5,15; 5.5,16; 6,14; 7,12; 7.5,10; 8,11; 9,8\" data-line=\"-2,26\"></div>"}, {"kind": "mcq", "text": "A village is 2500 m from the city. Which x-value should you use on the plot-price graph?", "opts": ["2500", "250", "2.5", "25"], "correct": 2, "tag": "", "sol": "The axis is in kilometres: 2500 m ÷ 1000 = 2.5 km. Always check the units on the axis before reading."}, {"kind": "blank", "p": "20 learners took a driving theory test marked out of 80. The graph shows their marks and revision time. The pass mark was 40.", "tag": "", "marks": "", "flat": [{"t": "a) The number of learners who failed is __B1__.", "a": {"B1": "8"}}, {"t": "b) The percentage of learners who failed is __B1__%.", "a": {"B1": "40"}}, {"t": "c) Draw a line of best fit. __B1__", "a": {"B1": "4.37883,11.9156,9.6,1,14"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"16\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"80\" data-ystep=\"10\" data-xlab=\"Hours spent revising\" data-ylab=\"Theory test mark (out of 80)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,18; 2,26; 3,22; 4,28; 4,34; 5,30; 6,38; 6,44; 7,40; 8,48; 8,52; 9,50; 10,58; 10,54; 11,62; 12,60; 12,68; 13,66; 14,72\" data-key=\"4.37883,11.9156,9.6,1,14\"></div>", "expr": "slbf"}], "sol": "Marks below 40: 12, 18, 26, 22, 28, 34, 30, 38 → 8 learners (40 itself is a pass).\n8 ÷ 20 × 100 = 40%.\nPositive correlation: e.g. from about (1, 16) to (14, 73)."}, {"kind": "mcq", "text": "Why might it not be appropriate to use the line to estimate the mark of a learner who revised for 18 hours?", "opts": ["It is outside the data, and the line would give more than 80 marks", "18 hours is less than a whole day, so it does not count", "The line of best fit is straight, so it cannot be used at all", "Nobody revises for 18 hours, so the data must be wrong"], "correct": 0, "tag": "", "sol": "The data stop at 14 hours. The line would give about 91 marks, which is more than the maximum of 80. Extrapolation is unreliable here."}, {"kind": "blank", "p": "The graph shows the ages of 13 mango trees and the number of mangoes picked from each, with a line of best fit.", "tag": "", "marks": "", "flat": [{"t": "a) The range of the number of mangoes picked is __B1__.", "a": {"B1": "72"}}, {"t": "b) Another tree gave 68 mangoes. Use the line to estimate its age: __B1__ years", "a": {"B1": "6"}}], "sol": "Range = largest − smallest = 92 − 20 = 72.\nAcross from 68 to the line, then down: 6 years.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"120\" data-ystep=\"20\" data-xlab=\"Age of tree (years)\" data-ylab=\"Mangoes picked\" data-xminor=\"0.5\" data-yminor=\"4\" data-pts=\"2,20; 2.5,28; 3,32; 3.5,40; 4,44; 4.5,48; 5,60; 5.5,60; 6,68; 6.5,72; 7,80; 7.5,88; 8,92\" data-line=\"12,-4\"></div>"}, {"kind": "mcq", "text": "Which description best matches this scatter graph?", "opts": ["No correlation", "Strong negative correlation", "Weak positive correlation", "Weak negative correlation"], "correct": 3, "tag": "", "sol": "The crosses drift down from left to right (negative), but are widely spread round any line (weak).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,44; 2,30; 3,40; 4,22; 5,34; 6,18; 7,30; 8,12; 9,26; 3,26; 7,16; 5,42\"></div>"}]}, {"id": "s6", "label": "6 · Regents questions", "sub": "I can answer NYS Regents exam questions on scatter plots and lines of best fit.", "slides": [{"kind": "mcq", "text": "<b>Regents Q1</b> · The scatter plot below shows the profit, by month, for a new company for the first year of operation. Kate drew a line of best fit, as shown in the diagram. Using this line, what is the best estimate for profit in the 18th month?", "opts": ["$35,000", "$37,750", "$42,500", "$45,000"], "correct": 2, "tag": "", "sol": "Kate’s line passes through (1, 0) and (9, 20), so it rises 2.5 (thousand dollars) per month: y = 2.5x − 2.5. At month 18: 2.5 × 18 − 2.5 = 42.5, i.e. $42,500 (choice 3).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"20\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"Month\" data-ylab=\"Profit (in thousands of dollars)\" data-xminor=\"1\" data-yminor=\"2.5\" data-pts=\"1,0; 2,2.5; 3,5; 4,12.5; 5,7.5; 6,15; 7,10; 8,15; 9,20; 10,20; 11,27.5; 12,25\" data-line=\"2.5,-2.5\"></div>"}, {"kind": "blank", "p": "<b>Regents Q1</b> · Follow-up on Kate’s line (it passes through (1, 0) and (9, 20)).", "tag": "", "marks": "", "flat": [{"t": "a) The gradient of Kate’s line is __B1__ (thousand dollars per month).", "a": {"B1": "2.5"}}, {"t": "b) Using the line, the profit in month 10 is __B1__ thousand dollars.", "a": {"B1": "22.5"}}], "sol": "m = (20 − 0) ÷ (9 − 1) = 20 ÷ 8 = 2.5.\ny = 2.5 × 10 − 2.5 = 22.5 (thousand dollars).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"20\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"Month\" data-ylab=\"Profit (in thousands of dollars)\" data-xminor=\"1\" data-yminor=\"2.5\" data-pts=\"1,0; 2,2.5; 3,5; 4,12.5; 5,7.5; 6,15; 7,10; 8,15; 9,20; 10,20; 11,27.5; 12,25\" data-line=\"2.5,-2.5\"></div>"}, {"kind": "mcq", "text": "<b>Regents Q2</b> · Based on the line of best fit drawn below, which value could be expected for the data in June 2015?", "opts": ["230", "310", "480", "540"], "correct": 2, "tag": "", "sol": "Go up from June 2015 to the line, then across: about 480 (choice 3). The line starts near 235 in 1995 and rises about 12.5 a year: 235 + 20 × 12.5 = 485 ≈ 480.", "fig": "<div class=\"scatw\" data-xlo=\"1995\" data-xhi=\"2020\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Year (June)\" data-ylab=\"Value\" data-pts=\"1998,240; 1998.5,390; 2001,235; 2003,385; 2003.5,280; 2005,445; 2005.5,275; 2007,525; 2008,440; 2009,310; 2010.5,470; 2010.75,250; 2012.25,570; 2012.75,360\" data-line=\"12.5,-24702.5\"></div>"}, {"kind": "blank", "p": "<b>Regents Q2</b> · Follow-up on the same graph.", "tag": "", "marks": "", "flat": [{"t": "a) The data show weak __B1__ correlation.", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation"]}, {"t": "b) The data end in about 2013, so estimating for June 2015 is __B1__.", "a": {"B1": "extrapolation"}, "expr": "words", "accept": ["extrapolate"]}], "sol": "The points rise from left to right but are widely spread: weak positive correlation.\nJune 2015 is beyond the data: extrapolation, so treat the estimate with care.", "fig": "<div class=\"scatw\" data-xlo=\"1995\" data-xhi=\"2020\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Year (June)\" data-ylab=\"Value\" data-pts=\"1998,240; 1998.5,390; 2001,235; 2003,385; 2003.5,280; 2005,445; 2005.5,275; 2007,525; 2008,440; 2009,310; 2010.5,470; 2010.75,250; 2012.25,570; 2012.75,360\" data-line=\"12.5,-24702.5\"></div>"}, {"kind": "mcq", "text": "<b>Regents Q3</b> · The number of hours spent on math homework each week and the final exam grades for twelve students in Mr. Dylan's algebra class are plotted below. Based on a line of best fit, which exam grade is the best prediction for a student who spends about 4 hours on math homework each week?", "opts": ["62", "72", "82", "92"], "correct": 1, "tag": "", "sol": "A line of best fit through the middle of the points gives about 72 at 4 hours, so 72 (choice 2). 62 is below nearly all the points; 82 and 92 are above the trend at 4 hours.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time Spent on Math Homework (hours)\" data-ylab=\"Exam Grade (percent)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"1,50; 1.5,70; 2,63; 3,72; 3.5,80; 5,85; 5.5,70; 6,75; 7,91; 7,80; 8,81; 8.5,87\"></div>"}, {"kind": "blank", "p": "<b>Regents Q3</b> · Follow-up: Mr. Dylan’s class.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "3.42308,58.7885,7.5,1,8.5"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Time Spent on Math Homework (hours)\" data-ylab=\"Exam Grade (percent)\" data-xminor=\"0.5\" data-yminor=\"5\" data-pts=\"1,50; 1.5,70; 2,63; 3,72; 3.5,80; 5,85; 5.5,70; 6,75; 7,91; 7,80; 8,81; 8.5,87\" data-key=\"3.42308,58.7885,7.5,1,8.5\"></div>", "expr": "slbf"}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation", "weak positive", "weak positive correlation", "moderate positive"]}], "sol": "Rising line through the middle of the data, e.g. from about (1, 62) to (8.5, 88), passing near the mean point.\nMore homework time goes with higher grades: positive correlation."}, {"kind": "mcq", "text": "<b>Regents Q4</b> · The scatter plot below shows the relationship between the number of members in a family and the amount of the family's weekly grocery bill. The most appropriate prediction of the grocery bill for a family that consists of six members is", "opts": ["$100", "$300", "$400", "$500"], "correct": 1, "tag": "", "sol": "The trend rises from about $150 for small families to about $350 for 8–9 members. A line of best fit gives about $276 at 6 members, so $300 (choice 2).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Number of Family Members\" data-ylab=\"Grocery Bill (Dollars)\" data-pts=\"2,115; 3,300; 3,165; 3,115; 4,300; 4,250; 4,165; 4,115; 5,300; 5,145; 7,430; 7,375; 7,290; 7,200; 8,355; 9,400; 9,310\"></div>"}, {"kind": "blank", "p": "<b>Regents Q4</b> · Follow-up: grocery bills.", "tag": "", "marks": "", "flat": [{"t": "a) The number of families shown is __B1__.", "a": {"B1": "17"}}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "positive"}, "expr": "words", "accept": ["positive correlation", "weak positive", "weak positive correlation"]}], "sol": "Count the points: 1 + 3 + 4 + 2 + 4 + 1 + 2 = 17.\nBigger families tend to have bigger bills: positive correlation.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"600\" data-ystep=\"100\" data-xlab=\"Number of Family Members\" data-ylab=\"Grocery Bill (Dollars)\" data-pts=\"2,115; 3,300; 3,165; 3,115; 4,300; 4,250; 4,165; 4,115; 5,300; 5,145; 7,430; 7,375; 7,290; 7,200; 8,355; 9,400; 9,310\"></div>"}, {"kind": "mcq", "text": "<b>Regents Q5</b> · The scatter plot below shows the relationship between the number of internet-connected devices and the number of members in a household. For a household that has six members, what would be the best estimate for the number of internet-connected devices?", "opts": ["6", "10", "14", "18"], "correct": 1, "tag": "", "sol": "Halfway between the 5-member households (6 to 13) and the 7-member households (7 to 13), a line of best fit gives about 9.8, so 10 (choice 2).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"20\" data-ystep=\"4\" data-xlab=\"Members of Household\" data-ylab=\"Internet-Connected Devices\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"2,6; 2,4; 2,3; 2,2; 3,8; 3,7; 3,6; 3,4; 3,3; 4,9; 4,8; 4,6; 4,5; 4,4; 5,13; 5,12; 5,10; 5,7; 5,6; 7,13; 7,12; 7,11; 7,9; 7,7; 8,14; 8,13; 9,16; 9,14; 9,13; 10,15\"></div>"}, {"kind": "blank", "p": "<b>Regents Q5</b> · Follow-up: devices.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "1.44614,1.14676,2.4,2,10"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"20\" data-ystep=\"4\" data-xlab=\"Members of Household\" data-ylab=\"Internet-Connected Devices\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"2,6; 2,4; 2,3; 2,2; 3,8; 3,7; 3,6; 3,4; 3,3; 4,9; 4,8; 4,6; 4,5; 4,4; 5,13; 5,12; 5,10; 5,7; 5,6; 7,13; 7,12; 7,11; 7,9; 7,7; 8,14; 8,13; 9,16; 9,14; 9,13; 10,15\" data-key=\"1.44614,1.14676,2.4,2,10\"></div>", "expr": "slbf"}, {"t": "b) The number of households with 5 members is __B1__.", "a": {"B1": "5"}}], "sol": "Rising line, e.g. from about (2, 4) to (10, 16).\nAbove x = 5 there are points at 6, 7, 10, 12 and 13 devices: 5 households."}, {"kind": "mcq", "text": "<b>Regents Q6</b> · The graph below illustrates the number of acres used for farming in Smalltown, New York, over several years. Using a line of best fit, approximately how many acres will be used for farming in the 5th year?", "opts": ["0", "200", "300", "400"], "correct": 1, "tag": "", "sol": "The points fall by about 1 (hundred acres) a year. A line of best fit gives about 2.0 hundred acres in year 5, i.e. about 200 acres (choice 2). Remember the axis is in hundreds.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"8\" data-ystep=\"1\" data-xlab=\"Year\" data-ylab=\"Acres (in hundreds)\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"1,7; 2,5; 3,5; 4,3; 4.6,2.5\"></div>"}, {"kind": "blank", "p": "<b>Regents Q6</b> · Follow-up: farm land.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit for the first four years. __B1__", "a": {"B1": "-1.2,8,0.96,1,4"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"8\" data-ystep=\"1\" data-xlab=\"Year\" data-ylab=\"Acres (in hundreds)\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"1,7; 2,5; 3,5; 4,3\" data-key=\"-1.2,8,0.96,1,4\"></div>", "expr": "slbf"}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}], "sol": "Falling line, e.g. from about (1, 7) to (4, 3).\nAs the years go by, fewer acres are farmed: negative correlation."}, {"kind": "mcq", "text": "<b>Regents Q7</b> · A scatter plot was constructed on the graph below and a line of best fit was drawn. What is the equation of this line of best fit?", "opts": ["y = x + 5", "y = x + 25", "y = 5x + 5", "y = 5x + 25"], "correct": 3, "tag": "", "sol": "The line crosses the y-axis at 25 and passes through (1, 30) and (7, 60): m = (60 − 30) ÷ (7 − 1) = 5. So y = 5x + 25 (choice 4).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"15\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"75\" data-ystep=\"5\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,30; 2,35; 5,55; 7,60; 10,70\" data-line=\"5,25\"></div>"}, {"kind": "mcq", "text": "<b>Regents Q8</b> · Which equation most closely represents the line of best fit for the scatter plot below?", "opts": ["y = x", "y = {2/3}x + 1", "y = {3/2}x + 4", "y = {3/2}x + 1"], "correct": 3, "tag": "", "sol": "Test each option against the points. y = {3/2}x + 1 passes through (0, 1), (2, 4), (4, 7) and (6, 10), which are all plotted points, and has about as many points above it as below it (7 above, 7 below), so it is the best fit (choice 4). y = {3/2}x + 4 lies above 17 of the 18 points; y = x and y = {2/3}x + 1 are too shallow and lie below most points on the right.", "fig": "<div style=\"width:100%\"><div style=\"font-weight:700;text-align:center\">Money Earned from Babysitting</div><div class=\"scatw\" data-xlo=\"0\" data-xhi=\"12\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"12\" data-ystep=\"1\" data-xlab=\"Babysitting Time (hours)\" data-ylab=\"Money (dollars)\" data-xminor=\"1\" data-yminor=\"1\" data-pts=\"0,1; 1,1; 1,3; 1,5; 2,3; 2,4; 3,6; 3,8; 4,4; 4,7; 4,12; 5,7; 5,10; 6,5; 6,8; 6,10; 6,11; 8,11\"></div></div>"}, {"kind": "blank", "p": "<b>Regents Q9</b> · The table below shows the number of prom tickets sold over a ten-day period. Plot these data points on the coordinate grid below. Use a consistent and appropriate scale. Draw a reasonable line of best fit and write its equation.", "tag": "", "marks": "", "flat": [{"t": "a) Plot the data points. __B1__", "a": {"B1": "1,30; 2,35; 5,55; 7,60; 10,70"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"12\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"80\" data-ystep=\"10\" data-xlab=\"Day\" data-ylab=\"Number of Prom Tickets Sold\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"\" data-key=\"1,30; 2,35; 5,55; 7,60; 10,70\" data-meta=\"tol:0.5,2.5\"></div>", "expr": "spts", "accept": ["tol:0.5,2.5"]}, {"t": "b) Draw a reasonable line of best fit. __B1__", "a": {"B1": "4.53704,27.3148,9.6,1,10"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"12\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"80\" data-ystep=\"10\" data-xlab=\"Day\" data-ylab=\"Number of Prom Tickets Sold\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,30; 2,35; 5,55; 7,60; 10,70\" data-key=\"4.53704,27.3148,9.6,1,10\"></div>", "expr": "slbf"}, {"t": "c) The line through (1, 30) and (7, 60) is y = __B1__x + __B2__", "a": {"B1": "5", "B2": "25"}}], "sol": "Scale: 1 day across and 5 tickets up per small square. Plot (1, 30), (2, 35), (5, 55), (7, 60), (10, 70).\nA ruled line close to all five points, e.g. from (1, 30) to (10, 73).\nm = (60 − 30) ÷ (7 − 1) = 5; c = 30 − 5 × 1 = 25, so y = 5x + 25 (the JMAP answer).", "fig": "<div class=\"tscroll\"><table class=\"ttab\" style=\"width:auto;min-width:0\"><caption style=\"text-align:left;font-weight:700;padding:2px 0 6px\">Prom Ticket Sales</caption><tr><th>Day (x)</th><td>1</td><td>2</td><td>5</td><td>7</td><td>10</td></tr><tr><th>Number of Prom Tickets Sold (y)</th><td>30</td><td>35</td><td>55</td><td>60</td><td>70</td></tr></table></div>"}, {"kind": "blank", "p": "<b>Regents Q10</b> · Megan and Bryce opened a new store called the Donut Pit. Their goal is to reach a profit of $20,000 in their 18th month of business. The table and scatter plot below represent the profit, P, in thousands of dollars, that they made during the first 12 months. Draw a reasonable line of best fit. Using the line of best fit, predict whether Megan and Bryce will reach their goal in the 18th month of their business. Justify your answer.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a reasonable line of best fit. __B1__", "a": {"B1": "0.571678,2.32576,1.5,1,12"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"20\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"20\" data-ystep=\"2\" data-xlab=\"Number of Months\" data-ylab=\"Profit (in thousands of dollars)\" data-xminor=\"1\" data-yminor=\"0.5\" data-pts=\"1,3; 2,2.5; 3,4; 4,5; 5,6.5; 6,5.5; 7,7; 8,6; 9,7.5; 10,7; 11,9; 12,9.5\" data-key=\"0.571678,2.32576,1.5,1,12\"></div>", "expr": "slbf"}, {"t": "b) Will they reach their goal of $20,000 in month 18? (yes or no) __B1__", "a": {"B1": "no"}, "expr": "words", "accept": ["no they will not", "they will not", "no will not reach"]}], "sol": "A rising line through the middle of the points, e.g. from (1, 3) to (12, 9).\nExtending the line to t = 18 gives about P = 13 (thousand dollars), about $13,000, which is less than $20,000. They will not reach their goal.", "fig": "<div class=\"tscroll\"><table class=\"ttab\" style=\"width:auto;min-width:0\"><tr><th>t (months)</th><td>1</td><td>2</td><td>3</td><td>4</td><td>5</td><td>6</td><td>7</td><td>8</td><td>9</td><td>10</td><td>11</td><td>12</td></tr><tr><th>P (profit, in thousands of dollars)</th><td>3.0</td><td>2.5</td><td>4.0</td><td>5.0</td><td>6.5</td><td>5.5</td><td>7.0</td><td>6.0</td><td>7.5</td><td>7.0</td><td>9.0</td><td>9.5</td></tr></table></div>"}]}, {"id": "s7", "label": "Assessment A", "sub": "Knowing and understanding", "slides": [{"kind": "mcq", "text": "What type of correlation does this graph show?", "opts": ["Strong negative", "No correlation", "Strong positive", "Weak negative"], "correct": 0, "tag": "", "sol": "The crosses fall steadily from left to right and lie close to a line: strong negative correlation. More screen time goes with less sleep.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Hours of screen time per day\" data-ylab=\"Hours of sleep per week\" data-xminor=\"0.5\" data-yminor=\"2\" data-pts=\"1,58; 2,56; 3,52; 4,50; 5,46; 6,44; 7,40; 8,36; 9,34\"></div>"}, {"kind": "blank", "p": "Three more people: (2.5 hours, 54), (5.5 hours, 44) and (7.5 hours, 38).", "tag": "", "marks": "", "flat": [{"t": "Plot the three points. __B1__", "a": {"B1": "2.5,54; 5.5,44; 7.5,38"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Hours of screen time per day\" data-ylab=\"Hours of sleep per week\" data-xminor=\"0.5\" data-yminor=\"2\" data-pts=\"1,58; 2,56; 3,52; 4,50; 5,46; 6,44; 7,40; 8,36; 9,34\" data-key=\"2.5,54; 5.5,44; 7.5,38\" data-meta=\"tol:0.25,1.0\"></div>", "expr": "spts", "accept": ["tol:0.25,1.0"]}], "sol": "One small square is 0.5 hour across and 2 hours up. Plot (2.5, 54), (5.5, 44) and (7.5, 38)."}, {"kind": "mcq", "text": "Which point is the outlier?", "opts": ["(9, 36)", "(1, 12)", "(8, 10)", "(5, 24)"], "correct": 2, "tag": "", "sol": "All the other points lie close to a rising line; at x = 8 the pattern gives about 34, but (8, 10) is far below.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"40\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,16; 3,18; 4,22; 5,24; 6,28; 7,30; 8,34; 9,36; 8,10\"></div>"}, {"kind": "blank", "p": "The graph shows the screen time and sleep of 9 people.", "tag": "", "marks": "", "flat": [{"t": "Draw a line of best fit. __B1__", "a": {"B1": "-3.1,61.7222,5,1,9"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Hours of screen time per day\" data-ylab=\"Hours of sleep per week\" data-xminor=\"0.5\" data-yminor=\"2\" data-pts=\"1,58; 2,56; 3,52; 4,50; 5,46; 6,44; 7,40; 8,36; 9,34\" data-key=\"-3.1,61.7222,5,1,9\"></div>", "expr": "slbf"}], "sol": "Falling line through the middle, e.g. from (1, 58) to (9, 34)."}, {"kind": "mcq", "text": "Which of these is a rule for drawing a line of best fit?", "opts": ["Make sure that the line passes through any outlier", "Join the first point plotted to the last point plotted", "Have about the same number of points above and below the line", "Always start the line at the origin (0, 0) of the graph"], "correct": 2, "tag": "", "sol": "A line of best fit follows the trend with roughly equal numbers of points on each side. It need not pass through the origin, the end points or an outlier."}, {"kind": "blank", "p": "Use the line of best fit on the gas graph.", "tag": "", "marks": "", "flat": [{"t": "a) At 5 °C, gas used ≈ __B1__ units per day.", "a": {"B1": "40"}}, {"t": "b) When 36 units are used, the temperature is about __B1__ °C.", "a": {"B1": "8"}}], "sol": "Up from 5 to the line, then across: 40.\nAcross from 36 to the line, then down: 8 °C.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"30\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"Outside temperature (°C)\" data-ylab=\"Gas used (units per day)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"2,44; 5,40; 8,36; 10,32; 13,28; 16,24; 19,22; 22,16; 25,12; 28,10\" data-line=\"-1.3333333333333333,46.666666666666664\"></div>"}, {"kind": "mcq", "text": "Estimating a value <b>inside</b> the range of the data is called…", "opts": ["an outlier", "extrapolation", "correlation", "interpolation"], "correct": 3, "tag": "", "sol": "Inside the data range: interpolation. Outside: extrapolation."}, {"kind": "blank", "p": "Describe each graph.", "tag": "", "marks": "", "flat": [{"t": "a) The correlation is __B1__.", "a": {"B1": "none"}, "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,30; 2,12; 3,40; 4,22; 5,35; 6,15; 7,28; 8,42; 9,20; 2,35; 6,38; 8,14\"></div>", "expr": "words", "accept": ["no correlation", "no", "zero", "zero correlation"]}, {"t": "b) For the gas graph: as the temperature increases, the gas used __B1__.", "a": {"B1": "decreases"}, "expr": "words", "accept": ["decrease", "goes down", "falls", "drops", "reduces", "gets smaller"]}], "sol": "No pattern: no correlation.\nThe crosses fall from left to right: gas use decreases as it gets warmer."}]}, {"id": "s8", "label": "Assessment B", "sub": "Investigating patterns", "slides": [{"kind": "mcq", "text": "The outlier (8, 10) is removed from this data. What happens to the correlation?", "opts": ["It disappears", "It changes from positive to negative", "It becomes stronger", "It becomes weaker"], "correct": 2, "tag": "", "sol": "Without the outlier the remaining points lie very close to a rising line, so the positive correlation becomes stronger (r rises from 0.63 to 1.00).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"40\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,16; 3,18; 4,22; 5,24; 6,28; 7,30; 8,34; 9,36; 8,10\"></div>"}, {"kind": "blank", "p": "Use the 9 points without the outlier: (1, 12), (2, 16), (3, 18), (4, 22), (5, 24), (6, 28), (7, 30), (8, 34), (9, 36).", "tag": "", "marks": "", "flat": [{"t": "a) Mean of x = __B1__", "a": {"B1": "5"}}, {"t": "b) Total of the y-values = __B1__", "a": {"B1": "220"}}, {"t": "c) Draw a line of best fit through (or close to) the mean point. __B1__", "a": {"B1": "3,9.44444,4.8,1,9"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"40\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,16; 3,18; 4,22; 5,24; 6,28; 7,30; 8,34; 9,36\" data-key=\"3,9.44444,4.8,1,9\"></div>", "expr": "slbf"}], "sol": "(1 + 2 + … + 9) ÷ 9 = 45 ÷ 9 = 5.\n12 + 16 + 18 + 22 + 24 + 28 + 30 + 34 + 36 = 220, so the mean of y = 220 ÷ 9 ≈ 24.4.\nThe line should pass near (5, 24.4), e.g. from (1, 12) to (9, 36)."}, {"kind": "mcq", "text": "Which graph shows the <b>stronger</b> correlation?", "opts": ["Graph P", "Graph Q", "Both are equally strong", "Neither shows correlation"], "correct": 0, "tag": "", "sol": "Both are positive, but in P the crosses lie much closer to a straight line, so P is stronger.", "fig": "<div style=\"display:flex;flex-wrap:wrap;gap:8px;width:100%\"><div style=\"flex:1 1 150px;min-width:0\"><div style=\"font-weight:700;text-align:center;margin-bottom:2px\">Graph P</div><div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,12; 2,15; 3,20; 4,22; 5,27; 6,30; 7,33; 8,38; 9,40\"></div></div><div style=\"flex:1 1 150px;min-width:0\"><div style=\"font-weight:700;text-align:center;margin-bottom:2px\">Graph Q</div><div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"1,10; 2,25; 3,15; 4,30; 5,20; 6,38; 7,25; 8,40; 9,30; 3,30; 7,42; 5,12\"></div></div></div>"}, {"kind": "blank", "p": "A line of best fit is y = 3x + 12.", "tag": "", "marks": "", "flat": [{"t": "a) When x increases by 5, y increases by __B1__.", "a": {"B1": "15"}}, {"t": "b) Predict y when x = 8: __B1__", "a": {"B1": "36"}}], "sol": "The gradient 3 means y goes up 3 for each 1 in x, so 5 × 3 = 15.\ny = 3 × 8 + 12 = 24 + 12 = 36."}, {"kind": "mcq", "text": "If the outlier (8, 10) were included when drawing the line of best fit, how would the line change?", "opts": ["It would be moved so that it passes through the origin", "It would be pulled down at the right, so it would be less steep", "It would be pulled up at the right, so it would be steeper", "It would not change at all, as one point makes no difference"], "correct": 1, "tag": "", "sol": "The outlier is far below the trend at x = 8, so it drags the right-hand end of the line down: gradient 2.07 with it, 3.00 without it.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"40\" data-ystep=\"10\" data-xlab=\"x\" data-ylab=\"y\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"1,12; 2,16; 3,18; 4,22; 5,24; 6,28; 7,30; 8,34; 9,36; 8,10\"></div>"}, {"kind": "blank", "p": "The graph shows the age and resale value of 9 phones.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "-8.7871,55.1226,7.2,0.5,5"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Age of phone (years)\" data-ylab=\"Resale value (₹ thousand)\" data-xminor=\"0.5\" data-yminor=\"2\" data-pts=\"0.5,52; 1,46; 1.5,42; 2,36; 2.5,34; 3,28; 3.5,24; 4,20; 5,12\" data-key=\"-8.7871,55.1226,7.2,0.5,5\"></div>", "expr": "slbf"}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}], "sol": "Falling line, e.g. from (0.5, 50) to (5, 12).\nOlder phones are worth less: negative correlation."}, {"kind": "mcq", "text": "A plant grew 2 cm a week for its first 8 weeks. Why might y = 2x + 10 give a poor estimate of its height after 2 years?", "opts": ["2 years is inside the data, so the line cannot be used", "The equation does not say what type of plant it is", "Growth slows down, so the pattern will not continue that far", "The gradient of the line would become negative after a year"], "correct": 2, "tag": "", "sol": "2 years (104 weeks) is far outside the data. The model would give 218 cm, but plants slow down or stop growing: extrapolating a straight line so far is unreliable."}, {"kind": "blank", "p": "The line of best fit for fuel left (y litres) after driving x km is y = −0.08x + 45.", "tag": "", "marks": "", "flat": [{"t": "a) Fuel left after 250 km: __B1__ litres", "a": {"B1": "25"}}, {"t": "b) Distance driven when 13 litres are left: __B1__ km", "a": {"B1": "400"}}, {"t": "c) The data were for 0 to 300 km. Part (b) is __B1__.", "a": {"B1": "extrapolation"}, "expr": "words", "accept": ["extrapolate"]}], "sol": "y = −0.08 × 250 + 45 = −20 + 45 = 25.\n13 = −0.08x + 45 → 0.08x = 32 → x = 400.\n400 km is beyond 300 km: extrapolation."}]}, {"id": "s9", "label": "Assessment C", "sub": "Communicating", "slides": [{"kind": "mcq", "text": "Which sentence describes <b>negative correlation</b> correctly?", "opts": ["As one variable increases, the other tends to decrease", "The values are below zero", "There is no relationship between the variables", "Both variables decrease at exactly the same rate"], "correct": 0, "tag": "", "sol": "Negative correlation means as one quantity increases, the other tends to decrease. It is a real relationship and has nothing to do with negative numbers."}, {"kind": "blank", "p": "Complete the sentences.", "tag": "", "marks": "", "flat": [{"t": "a) A point that does not fit the pattern of the rest is called an __B1__.", "a": {"B1": "outlier"}, "expr": "words", "accept": ["outliers", "anomaly"]}, {"t": "b) Estimating a value inside the range of the data is called __B1__.", "a": {"B1": "interpolation"}, "expr": "words", "accept": ["interpolate"]}], "sol": "Outlier (also called an anomaly).\nInterpolation (inside the data); outside is extrapolation."}, {"kind": "mcq", "text": "<b>Error analysis.</b> Meera says: “Strong negative correlation means there is no relationship.” Which reply is correct?", "opts": ["Right: only a positive correlation shows a relationship", "Wrong: it means that both of the variables increase together", "Right: negative correlation means that there is no relationship", "Wrong: it is a strong relationship; as one goes up, the other goes down"], "correct": 3, "tag": "", "sol": "Strong negative correlation is a clear relationship: the crosses fall close to a straight line. “No correlation” is when there is no pattern."}, {"kind": "blank", "p": "The table shows absences and exam marks for 9 students. Seven are plotted. Plot the other two: (4, 65) and (7, 50).", "tag": "", "marks": "", "flat": [{"t": "Plot the two points. __B1__", "a": {"B1": "4,65; 7,50"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Number of absences\" data-ylab=\"Exam mark (%)\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"0,85; 1,80; 2,75; 3,75; 5,60; 6,55; 8,40\" data-key=\"4,65; 7,50\" data-meta=\"tol:0.5,2.5\"></div>", "expr": "spts", "accept": ["tol:0.5,2.5"]}, {"t": "Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}], "sol": "Across to 4, up to 65; across to 7, up to 50 (one small square up is 5%).\nMore absences go with lower marks: negative correlation."}, {"kind": "mcq", "text": "A study finds that towns with more fire engines have more fires. Which conclusion is best?", "opts": ["Bigger towns have more of both; fire engines do not cause fires", "Removing some fire engines would reduce the number of fires", "Every fire makes a town go out and buy another fire engine", "Fire engines cause fires, since the two are correlated"], "correct": 0, "tag": "", "sol": "Correlation is not causation: town size (a third factor) increases both the number of fires and the number of fire engines."}, {"kind": "blank", "p": "Data: (1, 3), (3, 7), (4, 8), (6, 12), (6, 15).", "tag": "", "marks": "", "flat": [{"t": "The mean point is (__B1__, __B2__).", "a": {"B1": "4", "B2": "9"}}, {"t": "A line of best fit should pass __B1__ the mean point.", "a": {"B1": "through"}, "expr": "words", "accept": ["near", "close to", "through or near"]}], "sol": "Mean x = (1 + 3 + 4 + 6 + 6) ÷ 5 = 20 ÷ 5 = 4; mean y = (3 + 7 + 8 + 12 + 15) ÷ 5 = 45 ÷ 5 = 9.\nA good line of best fit passes through (or very close to) (4, 9)."}, {"kind": "mcq", "text": "The line of best fit for monthly electricity bill (₹) against number of people in a home is y = 250x + 400. Which sentence interprets 250 correctly?", "opts": ["Each extra person adds about ₹250 to the monthly bill", "The bill for an empty home (0 people) is about ₹250", "Each person pays about ₹400 of the monthly bill", "Each home in the data has 250 people living in it"], "correct": 0, "tag": "", "sol": "250 is the gradient: about ₹250 more for each extra person. 400 is the intercept: the bill when x = 0 (the fixed part)."}, {"kind": "blank", "p": "The graph shows absences and exam marks for all 9 students.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "-5.41667,86.6667,9,0,8"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"10\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"100\" data-ystep=\"10\" data-xlab=\"Number of absences\" data-ylab=\"Exam mark (%)\" data-xminor=\"1\" data-yminor=\"5\" data-pts=\"0,85; 1,80; 2,75; 3,75; 5,60; 6,55; 8,40; 4,65; 7,50\" data-key=\"-5.41667,86.6667,9,0,8\"></div>", "expr": "slbf"}, {"t": "b) As the number of absences increases, the exam mark __B1__.", "a": {"B1": "decreases"}, "expr": "words", "accept": ["decrease", "goes down", "falls", "drops", "gets lower", "reduces"]}], "sol": "Falling line, e.g. from (0, 85) to (8, 45).\nNegative correlation in context: more absences, lower marks."}]}, {"id": "s10", "label": "Assessment D", "sub": "Applying mathematics in real-life contexts", "slides": [{"kind": "mcq", "text": "A market stall records the weekly rainfall and the number of raincoats sold. In how many weeks did the stall sell at least 120 raincoats?", "opts": ["7", "5", "14", "3"], "correct": 1, "tag": "", "sol": "Draw across at 120 and count the crosses on or above it: 120, 128, 144, 152 and the second 120 → 5 weeks (“at least 120” includes 120).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"40\" data-xstep=\"10\" data-ylo=\"0\" data-yhi=\"200\" data-ystep=\"40\" data-xlab=\"Rainfall in the week (mm)\" data-ylab=\"Raincoats sold\" data-xminor=\"2\" data-yminor=\"8\" data-pts=\"2,40; 4,48; 6,64; 8,72; 10,80; 12,88; 14,104; 16,112; 18,120; 20,128; 22,144; 24,152; 10,120; 16,96\"></div>"}, {"kind": "blank", "p": "Raincoat stall (continued).", "tag": "", "marks": "", "flat": [{"t": "a) In another week there were 26 mm of rain and 160 raincoats were sold. Plot this point. __B1__", "a": {"B1": "26,160"}, "fig": "<div class=\"scatw\" data-mode=\"spts\" data-xlo=\"0\" data-xhi=\"40\" data-xstep=\"10\" data-ylo=\"0\" data-yhi=\"200\" data-ystep=\"40\" data-xlab=\"Rainfall in the week (mm)\" data-ylab=\"Raincoats sold\" data-xminor=\"2\" data-yminor=\"8\" data-pts=\"2,40; 4,48; 6,64; 8,72; 10,80; 12,88; 14,104; 16,112; 18,120; 20,128; 22,144; 24,152; 10,120; 16,96\" data-key=\"26,160\" data-meta=\"tol:1.0,4.0\"></div>", "expr": "spts", "accept": ["tol:1.0,4.0"]}, {"t": "b) In the week with 14 mm of rain, __B1__ raincoats were sold.", "a": {"B1": "104"}}], "sol": "Across to 26 (one small square = 2 mm), up to 160 (one small square = 8).\nUp from 14 mm to the cross, then across: 104 (13 small squares of 8)."}, {"kind": "mcq", "text": "<b>Is this reasonable?</b> A line of best fit for test score (%) against revision hours (data from 0 to 10 hours) is y = 4x + 30. Dev uses it to predict a score of 130% for 25 hours. Is this reasonable?", "opts": ["No: 25 hours is far outside the data and a score cannot exceed 100%", "No: he should not add the 30, so it should be 4 × 25 = 100%", "Yes: more revision always means a higher score, without limit", "Yes: the working 4 × 25 + 30 = 130 is correct, so it is fine"], "correct": 0, "tag": "", "sol": "The arithmetic is right (4 × 25 + 30 = 130) but the answer is impossible: scores cannot exceed 100%. 25 hours is extrapolation far beyond the data, so the model does not apply."}, {"kind": "blank", "p": "A home records the outside temperature and the gas used each day. Use the line of best fit.", "tag": "", "marks": "", "flat": [{"t": "a) At 20 °C, the gas used is about __B1__ units.", "a": {"B1": "20"}}, {"t": "b) Describe the correlation: __B1__", "a": {"B1": "negative"}, "expr": "words", "accept": ["negative correlation", "strong negative", "strong negative correlation"]}], "sol": "Up from 20 to the line, then across: 20.\nWarmer days need less heating: negative correlation.", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"30\" data-xstep=\"5\" data-ylo=\"0\" data-yhi=\"50\" data-ystep=\"10\" data-xlab=\"Outside temperature (°C)\" data-ylab=\"Gas used (units per day)\" data-xminor=\"1\" data-yminor=\"2\" data-pts=\"2,44; 5,40; 8,36; 10,32; 13,28; 16,24; 19,22; 22,16; 25,12; 28,10\" data-line=\"-1.3333333333333333,46.666666666666664\"></div>"}, {"kind": "mcq", "text": "A line of best fit for taxi fares is y = 22x + 50 (x in km, y in ₹). What does the 50 represent?", "opts": ["A charge of about ₹50 for every kilometre", "The fare for a journey of exactly 50 km", "The longest journey in the data is 50 km", "A fixed charge of about ₹50 before any distance"], "correct": 3, "tag": "", "sol": "50 is the intercept: the fare when the distance is 0, i.e. a fixed starting charge. 22 is the charge per km."}, {"kind": "blank", "p": "The graph shows distances and fares for 10 taxi journeys.", "tag": "", "marks": "", "flat": [{"t": "a) Draw a line of best fit. __B1__", "a": {"B1": "22.137,50.2715,60,2,18"}, "fig": "<div class=\"scatw\" data-mode=\"slbf\" data-xlo=\"0\" data-xhi=\"20\" data-xstep=\"2\" data-ylo=\"0\" data-yhi=\"500\" data-ystep=\"100\" data-xlab=\"Distance (km)\" data-ylab=\"Fare (₹)\" data-xminor=\"1\" data-yminor=\"10\" data-pts=\"2,90; 4,140; 5,160; 7,210; 9,240; 10,280; 12,320; 14,360; 16,410; 18,440\" data-key=\"22.137,50.2715,60,2,18\"></div>", "expr": "slbf"}, {"t": "b) A reasonable line is y = 22x + 50. Predict the fare for 15 km: ₹__B1__", "a": {"B1": "380"}}], "sol": "Rising line, e.g. from (2, 90) to (18, 450).\ny = 22 × 15 + 50 = 330 + 50 = ₹380."}, {"kind": "mcq", "text": "Estimate the resale value of a 4.5-year-old phone.", "opts": ["About ₹6 thousand", "About ₹40 thousand", "About ₹16 thousand", "About ₹28 thousand"], "correct": 2, "tag": "", "sol": "A line of best fit gives about ₹16 thousand at 4.5 years (between the phones at 4 years → ₹20 thousand and 5 years → ₹12 thousand).", "fig": "<div class=\"scatw\" data-xlo=\"0\" data-xhi=\"6\" data-xstep=\"1\" data-ylo=\"0\" data-yhi=\"60\" data-ystep=\"10\" data-xlab=\"Age of phone (years)\" data-ylab=\"Resale value (₹ thousand)\" data-xminor=\"0.5\" data-yminor=\"2\" data-pts=\"0.5,52; 1,46; 1.5,42; 2,36; 2.5,34; 3,28; 3.5,24; 4,20; 5,12\"></div>"}, {"kind": "blank", "p": "A car’s fuel tank: y = −0.08x + 45 gives the fuel left (litres) after x km.", "tag": "", "marks": "", "flat": [{"t": "a) Fuel left after 100 km: __B1__ litres", "a": {"B1": "37"}}, {"t": "b) The car warns when 5 litres are left. This happens after __B1__ km.", "a": {"B1": "500"}}], "sol": "y = −0.08 × 100 + 45 = −8 + 45 = 37.\n5 = −0.08x + 45 → 0.08x = 40 → x = 500."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-scatter';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Scatter Graphs</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('') + '<button class="tab-btn'+(activeTab==='report'?' active':'')+'" data-tab="report">📊 Report<span class="tab-count">pie</span></button>';
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — you can answer it now and press <b>Check</b>, or come back later from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+((item.status!=='unanswered'&&item.status!=='skipped')?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  if(item.status==='skipped') item.status='unanswered';
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+fr(THEORY)+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};


/* ================= MYP criterion report ================= */
var CRIT_COL={A:'var(--accent-text)',B:'var(--gold)',C:'#8A6FC4',D:'#2F9AA0'};
function critStats(){
  return REPORT.map(function(r){
    var tabId=r[0], slides=SLIDES[tabId], ts=state&&state.tabs[tabId];
    var c=0,w=0,n=0;
    slides.forEach(function(sl,i){
      if(!ts||!ts.items[i]){ n++; return; }
      var it=ts.items[i];
      if(MODE==='learning'){
        if(it.status==='correct') c++; else if(it.status==='revealed') w++; else n++;
      } else {
        if(isSlideCorrect(tabId,i)) c++; else if(isSlideAttempted(tabId,i)) w++; else n++;
      }
    });
    var tot=slides.length, pct=tot?Math.round(c/tot*100):0;
    var lvl=Math.round(c/Math.max(tot,1)*8);
    return {tab:tabId,letter:r[1],name:r[2],c:c,w:w,n:n,tot:tot,pct:pct,lvl:lvl};
  });
}
function arcPath(cx,cy,r,a0,a1){
  if(a1-a0>=Math.PI*2-1e-6){ return 'M'+(cx-r)+','+cy+' a'+r+','+r+' 0 1,0 '+(2*r)+',0 a'+r+','+r+' 0 1,0 '+(-2*r)+',0 Z'; }
  var x0=cx+r*Math.sin(a0), y0=cy-r*Math.cos(a0), x1=cx+r*Math.sin(a1), y1=cy-r*Math.cos(a1);
  return 'M'+cx+','+cy+' L'+x0.toFixed(2)+','+y0.toFixed(2)+' A'+r+','+r+' 0 '+((a1-a0)>Math.PI?1:0)+',1 '+x1.toFixed(2)+','+y1.toFixed(2)+' Z';
}
function pieSVG(parts,size,hole,center,sub){
  var tot=parts.reduce(function(s,p){return s+p.v;},0), cx=size/2, cy=size/2, r=size/2-4, a=0, h='';
  if(!tot){ h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+r+'" style="fill:var(--paper-2);stroke:var(--rule)"/>'; }
  parts.forEach(function(p){ if(!p.v) return; var b=a+p.v/tot*Math.PI*2; h+='<path d="'+arcPath(cx,cy,r,a,b)+'" style="fill:'+p.col+';stroke:var(--card);stroke-width:2"><title>'+esc(p.label)+': '+p.v+'</title></path>'; a=b; });
  if(hole) h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+(r*hole)+'" style="fill:var(--card)"/>';
  if(center) h+='<text x="'+cx+'" y="'+(cy-(sub?4:0))+'" text-anchor="middle" dominant-baseline="middle" style="fill:var(--ink);font:700 '+(size>150?22:15)+'px Fraunces,serif">'+center+'</text>';
  if(sub) h+='<text x="'+cx+'" y="'+(cy+16)+'" text-anchor="middle" style="fill:var(--ink-soft);font:600 11px \'Source Sans 3\',sans-serif">'+sub+'</text>';
  return '<svg viewBox="0 0 '+size+' '+size+'" width="'+size+'" height="'+size+'" role="img">'+h+'</svg>';
}
function band(l){ return l===0?'0':(l<=2?'1–2':(l<=4?'3–4':(l<=6?'5–6':'7–8'))); }
function renderReport(){
  var st=critStats(), totC=0, totQ=0;
  st.forEach(function(s){ totC+=s.c; totQ+=s.tot; });
  var h='<div class="theory">';
  h+='<section class="note"><h2>Chapter test report</h2><p class="lt">'+(MODE==='quiz'?'<b>Quiz mode</b> results: answers are marked when you finish each test tab.':'<b>Learning mode</b> results: a question counts as correct only if you got it without the answer being revealed. Switch to Quiz mode for an exam-style score.')+'</p>';
  h+='<div class="rep-top"><div class="rep-pie">'+pieSVG(st.map(function(s){return {v:s.c,col:CRIT_COL[s.letter],label:'Criterion '+s.letter};}),200,0.55,totC+'/'+totQ,'correct')+'</div>';
  h+='<div class="rep-legend"><div class="rep-cap">Marks earned, by criterion</div>'+st.map(function(s){ return '<div class="rep-li"><span class="sw" style="background:'+CRIT_COL[s.letter]+'"></span><b>'+s.letter+'</b>&nbsp;'+esc(s.name)+'<span class="rep-n">'+s.c+' / '+s.tot+'</span></div>'; }).join('')+'</div></div></section>';
  h+='<div class="rep-grid">'+st.map(function(s){
    return '<div class="rep-card"><div class="rep-h"><span class="crit" style="background:'+CRIT_COL[s.letter]+'">'+s.letter+'</span>'+esc(s.name)+'</div>'+
      '<div class="rep-row">'+pieSVG([{v:s.c,col:'var(--success)',label:'Correct'},{v:s.w,col:'var(--danger)',label:'Incorrect'},{v:s.n,col:'var(--locked)',label:'Not attempted'}],120,0.5,s.pct+'%')+
      '<div class="rep-stats"><div><span class="sw" style="background:var(--success)"></span>Correct <b>'+s.c+'</b></div><div><span class="sw" style="background:var(--danger)"></span>Incorrect <b>'+s.w+'</b></div><div><span class="sw" style="background:var(--locked)"></span>Not attempted <b>'+s.n+'</b></div>'+
      '<div class="rep-lvl">Indicative level <b>'+s.lvl+'</b> / 8 <span>(band '+band(s.lvl)+')</span></div></div></div>'+
      '<button class="hub-btn" data-go="'+s.tab+'">Open Test '+s.letter+' →</button></div>';
  }).join('')+'</div>';
  h+='<p class="rep-note">Indicative level = fraction of questions correct × 8, rounded. It is a practice guide only; your teacher awards the real MYP criterion levels.</p></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Report — chapter test results by MYP criterion';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
}
var _rsReport = renderSlide;
renderSlide = function(){
  if(activeTab==='report'){ renderReport(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  _rsReport();
};


/* ================= skipped-question return ================= */
function firstSkippedIdx(ts){
  for(var i=0;i<ts.items.length;i++){
    var it=ts.items[i];
    if(MODE==='quiz'){ if(!isSlideAttempted(activeTab,i)) return i; }
    else if(it.status==='skipped'||it.status==='unanswered') return i;
  }
  return -1;
}
function skippedList(ts){
  var out=[]; for(var i=0;i<ts.items.length;i++){ var it=ts.items[i];
    if(MODE==='quiz' ? !isSlideAttempted(activeTab,i) : (it.status==='skipped'||it.status==='unanswered')) out.push(i); }
  return out;
}
function renderSkipGate(ts){
  var list=skippedList(ts);
  var h='<div class="qcard done-card"><div class="big">⏭️</div><h2>You skipped '+list.length+' question'+(list.length>1?'s':'')+'</h2>'+
    '<p style="color:var(--ink-soft);font-size:14px;">Answer them now, or submit the tab as it is. Answers are marked only when you submit.</p>'+
    '<div class="skip-chips">'+list.map(function(i){ return '<button class="chip skip-go" data-i="'+i+'">Q'+(i+1)+'</button>'; }).join('')+'</div>'+
    '<div class="skip-btns"><button class="btn btn-primary" id="btnGoSkipped">Answer skipped questions</button><button class="btn" id="btnSubmitAnyway">Submit anyway</button></div></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  var go=function(i){ ts.idx=i; ts.maxReached=Math.max(ts.maxReached,i); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); };
  document.getElementById('btnGoSkipped').addEventListener('click',function(){ go(list[0]); });
  document.querySelectorAll('.skip-go').forEach(function(b){ b.addEventListener('click',function(){ go(parseInt(b.dataset.i,10)); }); });
  document.getElementById('btnSubmitAnyway').addEventListener('click',function(){ ts.submitOK=true; renderFinished(); ts.submitOK=false; });
  saveState();
}
var _rfSkip = renderFinished;
renderFinished = function(){
  var ts=state.tabs[activeTab];
  if(MODE==='quiz' && !ts.submitOK && skippedList(ts).length){ renderSkipGate(ts); return; }
  _rfSkip();
  if(MODE==='learning'){
    var list=skippedList(ts);
    if(list.length){
      var card=document.querySelector('.done-card');
      if(card){ var d=document.createElement('div'); d.className='skip-btns';
        d.innerHTML='<button class="btn btn-primary" id="btnGoSkipped">Attempt skipped questions ('+list.length+')</button>';
        card.appendChild(d);
        document.getElementById('btnGoSkipped').addEventListener('click',function(){ ts.idx=list[0]; ts.recorded=false; renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); }
    }
  }
};


/* ================= approx answers (physics: within 1%) ================= */
var _amTools = answerMatches;
answerMatches = function(input,answer,accept,expr){
  if(expr==='approx'){
    var n1=parseNum(input); if(n1===null) return false;
    return [answer].concat(accept||[]).some(function(a){ var n2=parseNum(a); if(n2===null) return false; return Math.abs(n1-n2) <= Math.max(0.011*Math.abs(n2), 1e-9); });
  }
  return _amTools(input,answer,accept,expr);
};

/* ================= palette: every question already reached can be opened ================= */
statusOf = function(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  var s=ts.items[i].status;
  if(s==='unanswered') return 'skipped';
  return s;
};

/* ================= on-screen keyboard ================= */
var KB={on:true, page:'num', target:null};
try{ var kbp=localStorage.getItem('sopaan-kb-pref'); if(kbp==='off') KB.on=false; }catch(e){}
function kbSave(){ try{ localStorage.setItem('sopaan-kb-pref', KB.on?'on':'off'); }catch(e){} }
var KEYS_NUM=[['7','8','9','(',')'],['4','5','6','−','/'],['1','2','3','.',','],['0',':','%','°','⌫'],['abc','←','→','Clear','Done']];
var KEYS_FRAC=[['7','8','9','/'],['4','5','6','−'],['1','2','3','space'],['0',',','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ALG=[['7','8','9','x','y','n'],['4','5','6','+','−','a'],['1','2','3','×','÷','b'],['0','.','(',')','^','²'],['/','π','|','t','⌫','Clear'],['abc','←','→','Done']];
function kbLayoutFor(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; var m=stp.expr, key=String(stp.a[inp.dataset.bkey]||'');
  if(m==='words'||m==='glist'||m==='angle') return 'abc'; if(m===true||m==='pow'||m==='primes') return 'alg';
  if(['fv','fe','fl','fm','fi','flist'].indexOf(m)>=0) return 'frac'; if(m==='dec'||m==='approx'||m==='dlist'||m==='set'||m==='coord'||m==='list'||m==='time') return 'num';
  if(/^[\-−]?\d+ \d+\/\d+$/.test(key)||/^[\-−]?\d+\/\d+$/.test(key)) return 'frac'; if(/[a-df-z]/i.test(key.replace(/pi/gi,''))) return /\d/.test(key)?'alg':'abc'; return 'num'; }catch(e){ return 'num'; } }
var KEYS_CALC=[['7','8','9','x','(',')'],['4','5','6','+','−','^'],['1','2','3','×','/','²'],['0','.','e','eˣ','√','ln'],['sin','cos','tan','t','⌫','Clear'],['sec','csc','cot','π','θ','∛'],['abc','←','→','Done']];
var KEYS_ABC=[['q','w','e','r','t','y','u','i','o','p'],['a','s','d','f','g','h','j','k','l','-'],['z','x','c','v','b','n','m',',',':','/'],['123','space','←','→','⌫','Done']];
function kbBuild(){
  var el=document.getElementById('vkb'); if(!el){ el=document.createElement('div'); el.id='vkb'; el.className='vkb'; document.body.appendChild(el);
    el.addEventListener('pointerdown',function(e){ var b=e.target.closest('button[data-k]'); e.preventDefault(); if(b) kbPress(b.dataset.k); });
    el.addEventListener('mousedown',function(e){ e.preventDefault(); }); }
  var rows={num:KEYS_NUM,frac:KEYS_FRAC,alg:KEYS_ALG,abc:KEYS_ABC,calc:KEYS_CALC}[KB.page]||KEYS_NUM;
  el.innerHTML='<div class="vkb-top"><span>⌨️ Keyboard</span><button data-k="device" class="vkb-link">Use device keyboard</button></div>'+
    rows.map(function(r){ return '<div class="vkb-row">'+r.map(function(k){
      var cls='vkb-k'+(/^(abc|123|Done|Clear|⌫|←|→|space)$/.test(k)?' fn':'')+(k==='Done'?' done':'');
      return '<button type="button" class="'+cls+'" data-k="'+k+'">'+(k==='space'?'space':k)+'</button>'; }).join('')+'</div>'; }).join('');
  return el;
}
function kbShow(inp){ KB.target=inp; KB.home=kbLayoutFor(inp); KB.page=KB.home; if(!KB.on) return; var cp=document.getElementById('calcPanel'); if(cp&&cp.classList.contains('show')) return; var el=kbBuild(); var nb=document.querySelector('.navbar'); el.style.bottom=(nb?nb.getBoundingClientRect().height:0)+'px'; el.classList.add('show'); document.body.classList.add('kb-open'); setTimeout(function(){ var r=inp.getBoundingClientRect(), top=el.getBoundingClientRect().top; if(r.bottom>top-12) window.scrollBy({top:r.bottom-top+60,behavior:'smooth'}); else if(r.top<60) window.scrollBy({top:r.top-80,behavior:'smooth'}); },30); }
function kbHide(){ var el=document.getElementById('vkb'); if(el) el.classList.remove('show'); document.body.classList.remove('kb-open'); }
function kbInsert(s){
  var t=KB.target; if(!t||t.disabled) return;
  var a=t.selectionStart==null?t.value.length:t.selectionStart, b=t.selectionEnd==null?a:t.selectionEnd;
  t.value=t.value.slice(0,a)+s+t.value.slice(b); var p=a+s.length; try{ t.setSelectionRange(p,p); }catch(e){}
  t.dispatchEvent(new Event('input',{bubbles:true}));
}
function kbPress(k){
  var t=KB.target; if(k==='device'){ KB.on=false; kbSave(); kbHide(); document.querySelectorAll('.blank-input').forEach(function(i){ i.removeAttribute('inputmode'); }); if(t){ t.blur(); setTimeout(function(){ t.focus(); },50); } showToast('Device keyboard on. Tap ⌨️ on any blank to bring the on-screen keyboard back.'); return; }
  if(k==='Done'){ kbHide(); if(t) t.blur(); return; }
  if(k==='abc'||k==='123'){ KB.page=(k==='abc')?'abc':(KB.home&&KB.home!=='abc'?KB.home:'num'); kbBuild(); return; }
  if(!t) return;
  if(k==='⌫'){ var a=t.selectionStart, b=t.selectionEnd; if(a===b&&a>0){ t.value=t.value.slice(0,a-1)+t.value.slice(b); try{t.setSelectionRange(a-1,a-1);}catch(e){} } else { t.value=t.value.slice(0,a)+t.value.slice(b); try{t.setSelectionRange(a,a);}catch(e){} } t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='Clear'){ t.value=''; t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='←'||k==='→'){ var p=(t.selectionStart||0)+(k==='←'?-1:1); p=Math.max(0,Math.min(t.value.length,p)); try{t.setSelectionRange(p,p);}catch(e){} return; }
  var map={'−':'-','space':' '}; kbInsert(map[k]!==undefined?map[k]:k);
}
function kbWire(){
  document.querySelectorAll('.blank-input').forEach(function(inp){
    if(inp.dataset.kb) return; inp.dataset.kb='1';
    if(KB.on) inp.setAttribute('inputmode','none');
    inp.addEventListener('focus',function(){ kbShow(inp); });
    var btn=document.createElement('button'); btn.type='button'; btn.className='kb-toggle'; btn.title='On-screen keyboard'; btn.textContent='⌨️'; btn.tabIndex=-1;
    btn.addEventListener('mousedown',function(e){ e.preventDefault(); });
    btn.addEventListener('click',function(){ KB.on=true; kbSave(); document.querySelectorAll('.blank-input').forEach(function(i){ i.setAttribute('inputmode','none'); }); inp.focus(); kbShow(inp); });
    if(!inp.disabled) inp.insertAdjacentElement('afterend',btn);
  });
}
document.addEventListener('focusout',function(e){ setTimeout(function(){ var a=document.activeElement; if(!a||!a.classList||!a.classList.contains('blank-input')){ if(!document.querySelector('#vkb:hover')) kbHide(); } },120); });

/* ================= calculator ================= */
var CALC={expr:'', ans:0};
function calcEval(src){
  var s=String(src).replace(/×/g,'*').replace(/÷/g,'/').replace(/−/g,'-').replace(/π/g,'(PI)').replace(/Ans/g,'('+CALC.ans+')').replace(/\^/g,'**').replace(/√\(/g,'sqrt(').replace(/²/g,'**2').replace(/E/g,'*10**');
  s=s.replace(/(^|[(*\/+\-,])-/g,'$1(-1)*');
  if(/[^0-9+\-*/().,a-z A-Z]/.test(s)) throw 0;
  var ok=s.replace(/sin|cos|tan|asin|acos|atan|sqrt|log|ln|PI|abs/g,''); if(/[a-zA-Z]/.test(ok)) throw 0;
  var f=new Function('sin','cos','tan','asin','acos','atan','sqrt','log','ln','PI','abs','return ('+s+');');
  var d=Math.PI/180;
  var v=f(function(x){return Math.sin(x*d);},function(x){return Math.cos(x*d);},function(x){return Math.tan(x*d);},
    function(x){return Math.asin(x)/d;},function(x){return Math.acos(x)/d;},function(x){return Math.atan(x)/d;},Math.sqrt,Math.log10,Math.log,Math.PI,Math.abs);
  if(typeof v!=='number'||!isFinite(v)) throw 0; return v;
}
function fmtNum(v){ if(Math.abs(v)>=1e10||(Math.abs(v)<1e-6&&v!==0)) return v.toExponential(6).replace(/\.?0+e/,'e'); return String(parseFloat(v.toPrecision(10))); }
var CKEYS=[['sin(','cos(','tan(','√(','^','²'],['asin(','acos(','atan(','(',')','π'],['7','8','9','÷','⌫','AC'],['4','5','6','×','E','Ans'],['1','2','3','−','(−)','Insert'],['0','.','=','+']];
function openCalc(){
  var p=document.getElementById('calcPanel');
  if(!p){ p=document.createElement('div'); p.id='calcPanel'; p.className='tool-panel calc';
    p.innerHTML='<div class="tp-head"><b>🧮 Calculator</b><span class="tp-note">degrees · tap a blank, then Insert</span><button class="tp-x" data-c="close">✕</button></div>'+
      '<div class="calc-disp"><div class="calc-expr" id="calcExpr"></div><div class="calc-res" id="calcRes">0</div></div>'+
      '<div class="calc-keys">'+CKEYS.map(function(r){ return r.map(function(k){ return '<button type="button" data-c="'+k+'" class="'+(k==='='?'eq':(/^(AC|⌫|Insert)$/.test(k)?'fn':''))+'">'+({'sin(':'sin','cos(':'cos','tan(':'tan','asin(':'sin⁻¹','acos(':'cos⁻¹','atan(':'tan⁻¹','√(':'√'}[k]||k)+'</button>'; }).join(''); }).join('')+'</div>';
    document.body.appendChild(p);
    p.addEventListener('mousedown',function(e){ if(e.target.closest('button')) e.preventDefault(); });
    p.addEventListener('click',function(e){ var b=e.target.closest('button[data-c]'); if(!b) return; calcKey(b.dataset.c); });
  }
  kbHide(); var nb=document.querySelector('.navbar'); p.style.bottom=((nb?nb.getBoundingClientRect().height:0)+8)+'px'; p.classList.add('show'); document.body.classList.add('calc-open'); calcShow();
}
function calcShow(res){ document.getElementById('calcExpr').textContent=CALC.expr||' '; if(res!==undefined) document.getElementById('calcRes').textContent=res; }
function calcKey(k){
  if(k==='close'){ document.getElementById('calcPanel').classList.remove('show'); document.body.classList.remove('calc-open'); return; }
  if(k==='AC'){ CALC.expr=''; calcShow('0'); return; }
  if(k==='⌫'){ CALC.expr=CALC.expr.replace(/(asin\(|acos\(|atan\(|sin\(|cos\(|tan\(|√\(|Ans|.)$/,''); calcShow(); return; }
  if(k==='='){ try{ var v=calcEval(CALC.expr); CALC.ans=v; calcShow(fmtNum(v)); }catch(e){ calcShow('Error'); } return; }
  if(k==='(−)'){ CALC.expr+='−'; calcShow(); return; }
  if(k==='Insert'){ var r=document.getElementById('calcRes').textContent; if(KB.target && !KB.target.disabled && r!=='Error'){ KB.target.value=r; KB.target.dispatchEvent(new Event('input',{bubbles:true})); showToast('Inserted '+r+' into the blank.'); } else showToast('Tap a blank first, then press Insert.'); return; }
  CALC.expr+=k; calcShow();
}

/* ================= Desmos ================= */
var DESMOS_KEY='dcb31709b452b1cf9dc26972add0fda6', desmosCalc=null, desmosLoading=false;
function openDesmos(exprs){
  var p=document.getElementById('desmosPanel');
  if(!p){ p=document.createElement('div'); p.id='desmosPanel'; p.className='tool-panel desmos';
    p.innerHTML='<div class="tp-head"><b>📈 Desmos graphing calculator</b><button class="tp-x" id="desmosReset">Reset graph</button><button class="tp-x" id="desmosClose">✕</button></div><div id="desmosBox"><div class="desmos-msg">Loading Desmos…</div></div>';
    document.body.appendChild(p);
    document.getElementById('desmosClose').addEventListener('click',function(){ p.classList.remove('show'); });
    document.getElementById('desmosReset').addEventListener('click',function(){ if(desmosCalc) desmosSet(p._exprs||[]); });
  }
  p._exprs=exprs||[]; p.classList.add('show');
  if(window.Desmos){ desmosInit(); desmosSet(p._exprs); return; }
  if(desmosLoading) return; desmosLoading=true;
  var sc=document.createElement('script'); sc.src='https://www.desmos.com/api/v1.9/calculator.js?apiKey='+DESMOS_KEY;
  sc.onload=function(){ desmosInit(); desmosSet(p._exprs); };
  sc.onerror=function(){ desmosLoading=false; document.getElementById('desmosBox').innerHTML='<div class="desmos-msg">Desmos needs an internet connection. <a href="https://www.desmos.com/calculator" target="_blank" rel="noopener">Open Desmos in a new tab</a>.</div>'; };
  document.head.appendChild(sc);
}
function desmosInit(){ if(desmosCalc) return; var box=document.getElementById('desmosBox'); box.innerHTML=''; desmosCalc=Desmos.GraphingCalculator(box,{expressionsCollapsed:false,settingsMenu:false,border:false,degreeMode:true}); }
function desmosSet(exprs){ if(!desmosCalc) return; desmosCalc.setBlank(); (exprs||[]).forEach(function(e,i){ if(typeof e==='string') desmosCalc.setExpression({id:'e'+i,latex:e}); else desmosCalc.setExpression(Object.assign({id:'e'+i},e)); }); }

/* ================= toolbar on each question ================= */
var _rsTools = renderSlide;
renderSlide = function(){
  _rsTools();
  kbHide();
  if(activeTab==='theory'||activeTab==='report') return;
  var ts=state.tabs[activeTab]; if(!ts) return;
  var slide=SLIDES[activeTab][ts.idx], card=document.querySelector('#wrap .qcard');
  if(card && slide && slide.tools && slide.tools.length && !card.querySelector('.tool-bar')){
    var bar=document.createElement('div'); bar.className='tool-bar';
    bar.innerHTML=(slide.tools.indexOf('calc')>=0?'<button type="button" class="tool-btn" data-t="calc">🧮 Calculator</button>':'')+
                  (slide.tools.indexOf('desmos')>=0?'<button type="button" class="tool-btn" data-t="desmos">📈 Desmos graph</button>':'');
    card.insertBefore(bar, card.firstChild);
    bar.addEventListener('click',function(e){ var b=e.target.closest('[data-t]'); if(!b) return; if(b.dataset.t==='calc') openCalc(); else openDesmos(slide.desmos||[]); });
  }
  kbWire();
};



/* ================= signed fractions in text: {−3/4}, {3/−4}, {−2 1/3}, {p/q} ================= */
fr = function(s){ return String(s).replace(/&lt;(\/?)(b|sup|sub|i)>/g,'<$1$2>')
  .replace(/\{([−-]?\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>')
  .replace(/\{([−-]?[A-Za-z0-9]+)\/([−-]?[A-Za-z0-9]+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); };
/* ================= BMA badge → main page of this sheet (theory hub) ================= */
(function(){
  var c=document.querySelector('.brand .crest'); if(!c) return;
  var a=document.createElement('button'); a.type='button'; a.className='crest crest-home'; a.title='Back to the main page (theory notes)'; a.setAttribute('aria-label','Main page');
  a.innerHTML='<img src="data:image/png;base64,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" alt="Brain and Mind"><span class="crest-h">⌂</span>'; c.parentNode.replaceChild(a,c);
  a.addEventListener('click',function(){
    if(!student||!MODE){ window.scrollTo({top:0,behavior:'smooth'}); return; }
    if(typeof kbHide==='function') kbHide(); if(typeof SP!=='undefined'&&SP.on) spToggle(false);
    var cp=document.getElementById('calcPanel'); if(cp) cp.classList.remove('show'); document.body.classList.remove('calc-open');
    activeTab = (typeof THEORY!=='undefined') ? 'theory' : TAB_DEFS[0].id;
    buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'});
  });
})();

/* ================= session clock: starts at sign-in and keeps running ================= */
var CLK={t0:null};
(function(){
  var row=document.querySelector('.brand .brand-row'); if(!row) return;
  var d=document.createElement('div'); d.className='bmasw off'; d.id='swBox'; d.title='Time since you signed in';
  d.innerHTML='<span class="bmasw-ic">⏱</span><span class="bmasw-t" id="swT">00:00</span>';
  row.appendChild(d); setInterval(swTick,1000);
})();
function swFmt(s){ s=Math.floor(s||0); var h=Math.floor(s/3600), m=Math.floor(s%3600/60), x=s%60; return (h?h+':'+String(m).padStart(2,'0'):String(m).padStart(2,'0'))+':'+String(x).padStart(2,'0'); }
function swTick(){
  var box=document.getElementById('swBox'); if(!box) return;
  if(student && !CLK.t0) CLK.t0=Date.now();
  if(!student) CLK.t0=null;
  box.classList.toggle('off',!CLK.t0);
  document.getElementById('swT').textContent = CLK.t0 ? swFmt((Date.now()-CLK.t0)/1000) : '00:00';
}
function swTab(){ try{ if(!state||!state.tabs||activeTab==='theory'||activeTab==='report') return null; return state.tabs[activeTab]||null; }catch(e){ return null; } }
var _rsSW = renderSlide;
renderSlide = function(){ _rsSW(); swTick(); };
var _rfSW = renderFinished;
renderFinished = function(){ _rfSW(); var done=document.querySelector('#wrap .done-card'); if(CLK.t0 && done && !done.querySelector('.bmasw-done')){ var p=document.createElement('p'); p.className='bmasw-done'; p.textContent='⏱ Time since sign-in: '+swFmt((Date.now()-CLK.t0)/1000); var h2=done.querySelector('h2'); if(h2) h2.insertAdjacentElement('afterend',p); else done.appendChild(p); } };

/* ================= scratchpad (Khan-style, 4 pens) ================= */
var SP={on:false, draw:true, color:'ink', size:3, erase:false, store:{}, key:null, cv:null, ctx:null, down:false, last:null};
var SP_COL={ink:null, blue:'#2563EB', red:'#DC2626', green:'#16A34A'};
function spInk(){ return getComputedStyle(document.documentElement).getPropertyValue('--ink').trim()||'#211E1A'; }
function spKey(){ var ts=swTab(); return ts ? (MODE+'|'+activeTab+'|'+ts.idx) : null; }
function spBuild(){
  if(SP.cv) return;
  var cv=document.createElement('canvas'); cv.id='spCanvas'; cv.className='sp-canvas'; document.body.appendChild(cv);
  var bar=document.createElement('div'); bar.id='spBar'; bar.className='sp-bar';
  bar.innerHTML='<span class="sp-lbl">✏️ Scratchpad</span>'+
    ['ink','blue','red','green'].map(function(c){ return '<button type="button" class="sp-pen" data-c="'+c+'" title="'+(c==='ink'?'black':c)+' pen"><i style="background:'+(c==='ink'?'var(--ink)':SP_COL[c])+'"></i></button>'; }).join('')+
    '<button type="button" class="sp-tool" data-t="erase" title="Eraser">🧽</button><button type="button" class="sp-tool" data-t="size" title="Pen size">●</button><button type="button" class="sp-tool" data-t="scroll" title="Pause drawing to scroll or answer">✋</button>'+
    '<button type="button" class="sp-tool" data-t="clear" title="Clear page">🗑</button><button type="button" class="sp-tool" data-t="close" title="Close scratchpad">✕</button>';
  document.body.appendChild(bar);
  bar.addEventListener('click',function(e){ var b=e.target.closest('button'); if(!b) return;
    if(b.dataset.c){ SP.color=b.dataset.c; SP.erase=false; SP.draw=true; }
    else if(b.dataset.t==='erase'){ SP.erase=true; SP.draw=true; }
    else if(b.dataset.t==='size'){ SP.size = SP.size===3?6:(SP.size===6?1.5:3); b.textContent = SP.size===6?'⬤':(SP.size===1.5?'·':'●'); }
    else if(b.dataset.t==='scroll'){ SP.draw=!SP.draw; }
    else if(b.dataset.t==='clear'){ spClear(); }
    else if(b.dataset.t==='close'){ spToggle(false); return; }
    spUI(); });
  SP.cv=cv; SP.ctx=cv.getContext('2d');
  cv.addEventListener('pointerdown',function(e){ if(!SP.draw) return; e.preventDefault(); cv.setPointerCapture(e.pointerId); SP.down=true; SP.last=spPt(e); spDot(SP.last); });
  cv.addEventListener('pointermove',function(e){ if(!SP.down) return; e.preventDefault(); var p=spPt(e); spLine(SP.last,p); SP.last=p; });
  var up=function(){ if(SP.down){ SP.down=false; spSave(); } };
  cv.addEventListener('pointerup',up); cv.addEventListener('pointercancel',up); cv.addEventListener('pointerleave',up);
  window.addEventListener('resize',function(){ if(SP.on) spFit(true); });
}
function spPt(e){ var r=SP.cv.getBoundingClientRect(); return {x:e.clientX-r.left, y:e.clientY-r.top}; }
function spStyle(){ var c=SP.ctx; c.lineCap='round'; c.lineJoin='round'; c.globalCompositeOperation=SP.erase?'destination-out':'source-over'; c.strokeStyle=c.fillStyle=(SP.color==='ink'?spInk():SP_COL[SP.color]); c.lineWidth=SP.erase?22:SP.size; }
function spDot(p){ spStyle(); var c=SP.ctx; c.beginPath(); c.arc(p.x,p.y,(SP.erase?11:SP.size/2),0,Math.PI*2); c.fill(); }
function spLine(a,b){ spStyle(); var c=SP.ctx; c.beginPath(); c.moveTo(a.x,a.y); c.lineTo(b.x,b.y); c.stroke(); }
function spSave(){ if(SP.key&&SP.cv){ try{ SP.store[SP.key]=SP.cv.toDataURL(); }catch(e){} } }
function spClear(){ if(!SP.ctx) return; SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.clearRect(0,0,SP.cv.width,SP.cv.height); SP.ctx.restore(); if(SP.key) delete SP.store[SP.key]; }
function spFit(keep){
  var wrap=document.getElementById('wrap'); if(!wrap||!SP.cv) return;
  var r=wrap.getBoundingClientRect(), top=r.top+window.scrollY, h=Math.max(wrap.scrollHeight, window.innerHeight-r.top)+40, w=document.documentElement.clientWidth;
  var old=keep&&SP.key?SP.store[SP.key]:null, dpr=window.devicePixelRatio||1;
  SP.cv.style.top=top+'px'; SP.cv.style.left='0px'; SP.cv.style.width=w+'px'; SP.cv.style.height=h+'px';
  SP.cv.width=Math.round(w*dpr); SP.cv.height=Math.round(h*dpr); SP.ctx.setTransform(dpr,0,0,dpr,0,0);
  if(old){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=old; }
}
function spLoad(){ spSave(); SP.key=spKey(); spFit(false); var d=SP.key&&SP.store[SP.key]; if(d){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=d; } }
function spUI(){
  var bar=document.getElementById('spBar'); if(!bar) return;
  bar.querySelectorAll('.sp-pen').forEach(function(b){ b.classList.toggle('on', !SP.erase && SP.draw && b.dataset.c===SP.color); });
  bar.querySelector('[data-t=erase]').classList.toggle('on', SP.erase && SP.draw);
  bar.querySelector('[data-t=scroll]').classList.toggle('on', !SP.draw);
  SP.cv.classList.toggle('passive', !SP.draw);
  var fb=document.getElementById('spFab'); if(fb) fb.classList.toggle('on',SP.on);
}
function spToggle(on){
  spBuild(); SP.on=(on===undefined)?!SP.on:on;
  document.body.classList.toggle('sp-open',SP.on); SP.cv.style.display=SP.on?'block':'none'; document.getElementById('spBar').style.display=SP.on?'flex':'none';
  if(SP.on){ SP.draw=true; SP.erase=false; spLoad(); if(typeof kbHide==='function') kbHide(); } else { spSave(); }
  spUI();
}
(function(){ var f=document.createElement('button'); f.type='button'; f.id='spFab'; f.className='sp-fab'; f.innerHTML='✏️ <span>Scratchpad</span>'; f.title='Open a scratchpad to write your working'; f.addEventListener('click',function(){ spToggle(); }); document.body.appendChild(f); })();
var _rsSP = renderSlide;
renderSlide = function(){ _rsSP(); var fab=document.getElementById('spFab'); var q=!!swTab(); if(fab) fab.style.display=q?'':'none'; if(!q && SP.on) spToggle(false); if(SP.on) setTimeout(spLoad,30); };


/* ================= v4: attempt classification ================= */
function v4Class(item){
  if(!item) return 'un';
  if(item.status==='skipped') return 'sk';
  if(item.status==='unanswered') return 'un';
  if(item.stepStates){ // step question
    if(item.status!=='correct' && item.status!=='revealed') return 'un';
    if(item.status==='revealed' || item.stepStates.some(function(s){return s.status==='revealed';})) return 'w';
    return item.stepStates.some(function(s){return (s.attempts||0)>0;}) ? 'c2' : 'c1';
  }
  if(item.status==='revealed') return 'w';
  if(item.status==='correct') return (item.attempts||0)>0 ? 'c2' : 'c1';
  if(item.status==='wrong'||item.status==='incorrect') return 'w';
  return 'un';
}
function v4Counts(items){ var c={n:items.length,c1:0,c2:0,w:0,sk:0,un:0}; items.forEach(function(it){ c[v4Class(it)]++; }); return c; }

/* ================= v4: My record with attempt columns ================= */
renderRecord = function(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var title=(document.querySelector('.chapter-title')||{}).textContent||'';
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+(title?' · '+esc(title):'')+'</p>';
  var st=appState.learning;
  h+='<h3>📘 Learning Sheet — attempts</h3><p class="v4leg"><b>1st ✓</b> correct on the first attempt · <b>2nd ✓</b> correct on the second attempt · <b>Wrong</b> still wrong after two attempts (answer revealed) · <b>Skip</b> skipped<span class="v4left"> · <b>Left</b> not done yet</span></p>';
  if(!st){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    var T={n:0,c1:0,c2:0,w:0,sk:0,un:0};
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th><th>Skip</th><th class="v4left">Left</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=st.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var c=v4Counts(tt.items);
      ['n','c1','c2','w','sk','un'].forEach(function(k){ T[k]+=c[k]; });
      h+='<tr><td>'+td.label+'</td><td>'+c.n+'</td><td class="v4g">'+c.c1+'</td><td class="v4o">'+c.c2+'</td><td class="v4r">'+c.w+'</td><td>'+c.sk+'</td><td class="v4left">'+c.un+'</td></tr>'; });
    h+='<tr class="v4tot"><td>Total</td><td>'+T.n+'</td><td class="v4g">'+T.c1+'</td><td class="v4o">'+T.c2+'</td><td class="v4r">'+T.w+'</td><td>'+T.sk+'</td><td class="v4left">'+T.un+'</td></tr>';
    h+='</tbody></table></div>';
    var doneN=T.c1+T.c2+T.w; if(doneN){ h+='<p class="v4sum">Of '+doneN+' questions answered: <b>'+Math.round(T.c1/doneN*100)+'%</b> right first time, <b>'+Math.round(T.c2/doneN*100)+'%</b> right on the second try, <b>'+Math.round(T.w/doneN*100)+'%</b> still wrong after two tries.</p>'; }
  }
  var q=appState.quiz;
  h+='<h3>📝 Quiz Mode</h3>';
  if(!q){ h+='<p class="rec-empty">Not started yet.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>Sheet</th><th>Qs</th><th>Status</th><th>Correct</th><th>Wrong</th></tr></thead><tbody>';
    TAB_DEFS.forEach(function(td){ var tt=q.tabs[td.id]; if(!tt||!tt.items||!tt.items.length) return; var n=tt.items.length, cor=0, att=0;
      tt.items.forEach(function(it){ if(it.status!=='unanswered'||it.choice!==undefined) att++; });
      var rec=records.filter(function(r){ return r.mode==='quiz'&&r.tab===td.id; })[0];
      if(rec){ cor=rec.correct; att=Math.max(att,rec.total); }
      h+='<tr><td>'+td.label+'</td><td>'+n+'</td><td>'+(rec?'Finished':att+' / '+n)+'</td><td class="v4g">'+(rec?cor:'—')+'</td><td class="v4r">'+(rec?(rec.total-cor):'—')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><div class="rec-card"><h3>Finished sheets (latest first)</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sheets finished yet. Each time you finish a sheet, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table v4rec"><thead><tr><th>When</th><th>Mode</th><th>Sheet</th><th>Score</th><th>1st ✓</th><th>2nd ✓</th><th>Wrong</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+'</td><td>'+(r.c1!=null?r.c1:'—')+'</td><td>'+(r.c2!=null?r.c2:'—')+'</td><td>'+(r.w!=null?r.w:(r.mode==='quiz'?r.total-r.correct:'—'))+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){ if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker(); });
  window.scrollTo({top:0});
};
var _v4add = addRecord;
addRecord = function(mode, tabId, correct, revealed, skipped, total){
  _v4add(mode, tabId, correct, revealed, skipped, total);
  try{ if(mode==='learning'&&records[0]){ var c=v4Counts(state.tabs[tabId].items); records[0].c1=c.c1; records[0].c2=c.c2; records[0].w=c.w; saveState(); } }catch(e){}
};

/* ================= v4: celebration ================= */
function v4Cracker(){
  var ctx=ensureAudio(); if(!ctx) return; try{ if(ctx.state==='suspended') ctx.resume(); }catch(e){}
  var now=ctx.currentTime;
  function pop(t, vol, dur, hp){
    var len=Math.floor(ctx.sampleRate*dur), buf=ctx.createBuffer(1,len,ctx.sampleRate), d=buf.getChannelData(0);
    for(var i=0;i<len;i++){ d[i]=(Math.random()*2-1)*Math.pow(1-i/len,3); }
    var src=ctx.createBufferSource(); src.buffer=buf;
    var f=ctx.createBiquadFilter(); f.type='highpass'; f.frequency.value=hp;
    var g=ctx.createGain(); g.gain.setValueAtTime(vol,t); g.gain.exponentialRampToValueAtTime(0.001,t+dur);
    src.connect(f); f.connect(g); g.connect(ctx.destination); src.start(t); src.stop(t+dur+0.02);
  }
  pop(now,0.9,0.35,300);                                   // big bang
  for(var k=0;k<14;k++){ pop(now+0.35+Math.random()*1.3, 0.25+Math.random()*0.35, 0.05+Math.random()*0.08, 1500+Math.random()*2500); } // crackles
  [523.25,659.25,783.99,1046.5].forEach(function(fq,i){ var o=ctx.createOscillator(), g=ctx.createGain(); o.type='triangle'; o.frequency.value=fq;
    var t=now+0.15+i*0.12; g.gain.setValueAtTime(0.0001,t); g.gain.exponentialRampToValueAtTime(0.18,t+0.03); g.gain.exponentialRampToValueAtTime(0.001,t+0.5);
    o.connect(g); g.connect(ctx.destination); o.start(t); o.stop(t+0.55); });
}
function v4Confetti(){
  var cv=document.createElement('canvas'); cv.className='v4conf'; document.body.appendChild(cv);
  var W=cv.width=window.innerWidth*(window.devicePixelRatio||1), H=cv.height=window.innerHeight*(window.devicePixelRatio||1), s=(window.devicePixelRatio||1);
  var ctx=cv.getContext('2d'), cols=['#e8b13a','#d9534f','#2e86de','#27ae60','#9b59b6','#f39c12','#1abc9c','#ff6b9a'], P=[];
  function burst(x,y,n){ for(var i=0;i<n;i++){ var a=Math.random()*Math.PI*2, v=(4+Math.random()*9)*s;
    P.push({x:x,y:y,vx:Math.cos(a)*v,vy:Math.sin(a)*v-6*s,w:(6+Math.random()*7)*s,h:(4+Math.random()*5)*s,r:Math.random()*6,vr:(Math.random()-.5)*.4,c:cols[i%cols.length],life:0,flyer:Math.random()<.25}); } }
  burst(W*0.2,H*0.35,90); burst(W*0.8,H*0.35,90); setTimeout(function(){ burst(W*0.5,H*0.25,120); },380); setTimeout(function(){ burst(W*0.35,H*0.3,70); burst(W*0.65,H*0.3,70); },800);
  var t0=performance.now();
  (function frame(t){
    ctx.clearRect(0,0,W,H);
    P.forEach(function(p){ p.vy+=0.22*s; p.vx*=0.985; p.vy*=0.985; p.x+=p.vx; p.y+=p.vy; p.r+=p.vr; p.life++;
      ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.r); ctx.fillStyle=p.c;
      if(p.flyer){ ctx.fillRect(-p.w*1.4,-1.5*s,p.w*2.8,3*s); } else { ctx.fillRect(-p.w/2,-p.h/2,p.w,p.h*Math.abs(Math.cos(p.life/6))); }
      ctx.restore(); });
    if(t-t0<4200) requestAnimationFrame(frame); else cv.remove();
  })(t0);
}
function v4NextTab(){
  var i=TAB_DEFS.findIndex(function(t){return t.id===activeTab;});
  for(var j=i+1;j<TAB_DEFS.length;j++){ var id=TAB_DEFS[j].id; if(id!=='theory' && SLIDES[id] && SLIDES[id].length) return TAB_DEFS[j]; }
  return null;
}
function v4Celebrate(){
  var done=document.querySelector('#wrap .done-card'); if(!done || done.dataset.v4) return; done.dataset.v4='1';
  var ts=state.tabs[activeTab], c=v4Counts(ts.items), n=ts.items.length;
  var first=(student&&student.name)?String(student.name).split(' ')[0]:'';
  var pct=MODE==='quiz'?null:Math.round((c.c1+c.c2)/Math.max(n,1)*100);
  var msg = pct===null ? 'You finished this sheet!' : (pct>=90?'Outstanding work!':pct>=75?'Excellent effort!':pct>=50?'Well done — keep going!':'Great persistence — every try makes you stronger!');
  var banner=document.createElement('div'); banner.className='v4ban';
  banner.innerHTML='<div class="v4trophy">🏆</div><div class="v4h">Congratulations'+(first?', '+esc(first):'')+'!</div><div class="v4m">'+msg+'</div>'+
    (MODE==='quiz'?'':'<div class="v4pills"><span class="v4p g">✅ '+c.c1+' first attempt</span><span class="v4p o">🔁 '+c.c2+' second attempt</span><span class="v4p r">❌ '+c.w+' finally wrong</span>'+(c.sk?'<span class="v4p s">⏭ '+c.sk+' skipped</span>':'')+'</div>');
  done.insertBefore(banner, done.firstChild);
  var nx=v4NextTab(), wrapB=document.createElement('div'); wrapB.className='v4next';
  if(nx){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">Next sheet: '+nx.label+' →</button>'; }
  else if(SLIDES.report!==undefined || TAB_DEFS.some(function(t){return t.id==='report';})){ wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">📊 View my report →</button>'; }
  else { wrapB.innerHTML='<button class="btn btn-primary v4go" id="v4Next">⌂ Back to the home page</button>'; }
  banner.appendChild(wrapB);
  document.getElementById('v4Next').addEventListener('click',function(){
    var t=nx?nx.id:(TAB_DEFS.some(function(x){return x.id==='report';})?'report':(TAB_DEFS[0]&&TAB_DEFS[0].id));
    activeTab=t; showChrome(true); buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  setTimeout(function(){ var r=banner.getBoundingClientRect(); window.scrollBy({top:r.top-110,behavior:'smooth'}); },60);
  v4Confetti(); v4Cracker();
}
var _v4rf = renderFinished;
renderFinished = function(){ _v4rf.apply(this,arguments); try{ v4Celebrate(); }catch(e){ console.log('v4',e); } };


/* ================= v5: inequality plotters ================= */
var PLT={};
function pFrac(s){ s=String(s).trim().replace(/−/g,'-'); if(/^[-+]?∞$|^[-+]?inf$/i.test(s)) return s.charAt(0)==='-'?-Infinity:Infinity;
  var m=s.match(/^([-+]?\d*\.?\d+)\s*\/\s*(\d*\.?\d+)$/); if(m) return parseFloat(m[1])/parseFloat(m[2]); var v=parseFloat(s); return isNaN(v)?null:v; }
function fmtN(v){ if(v===Infinity) return '∞'; if(v===-Infinity) return '−∞'; var r=Math.round(v*1000)/1000; var s=String(r); for(var d=2;d<=12;d++){ var n=Math.round(v*d); if(Math.abs(n/d-v)<1e-9 && Math.abs(n)%d!==0){ s=n+'/'+d; break; } } return s.replace('-','−'); }
/* ---- intervals ---- */
function ivParse(s){ s=String(s||'').trim(); if(!s) return null; if(/^(∅|\{\s*\}|none|empty)$/i.test(s)) return [];
  if(/^(ℝ|R|all real( numbers)?)$/i.test(s)) return [{a:-Infinity,ai:false,b:Infinity,bi:false}];
  var parts=s.split(/\s*(?:∪|U|u|or)\s*/), out=[];
  for(var i=0;i<parts.length;i++){ var m=parts[i].match(/^([\[(])\s*([^,]+?)\s*,\s*([^\])]+?)\s*([\])])$/); if(!m) return null;
    var a=pFrac(m[2]), b=pFrac(m[3]); if(a===null||b===null) return null; out.push({a:a,ai:m[1]==='['&&isFinite(a),b:b,bi:m[4]===']'&&isFinite(b)}); }
  return ivNorm(out); }
function ivNorm(L){ L=L.filter(function(t){ return t.a<t.b||(t.a===t.b&&t.ai&&t.bi); }).sort(function(p,q){ return p.a-q.a||((q.ai?1:0)-(p.ai?1:0)); });
  var o=[]; L.forEach(function(t){ var l=o[o.length-1];
    if(l && (t.a<l.b || (Math.abs(t.a-l.b)<1e-9 && (l.bi||t.ai)))){ if(t.b>l.b||(Math.abs(t.b-l.b)<1e-9&&t.bi)){ l.b=t.b; l.bi=t.bi; } }
    else o.push({a:t.a,ai:t.ai,b:t.b,bi:t.bi}); }); return o; }
function ivEq(x,y){ var A=ivParse(x),B=ivParse(y); if(!A||!B||A.length!==B.length) return false;
  for(var i=0;i<A.length;i++){ var p=A[i],q=B[i]; if(Math.abs(p.a-q.a)>1e-6&&!(p.a===q.a)) return false; if(Math.abs(p.b-q.b)>1e-6&&!(p.b===q.b)) return false; if(p.ai!==q.ai||p.bi!==q.bi) return false; } return true; }
function ivFmt(L){ if(!L.length) return '∅'; return L.map(function(t){ return (t.ai?'[':'(')+fmtN(t.a)+', '+fmtN(t.b)+(t.bi?']':')'); }).join(' ∪ '); }
/* ---- half-planes ---- */
function linParse(side){ side=String(side).replace(/\s+/g,'').replace(/−/g,'-').replace(/\*/g,''); if(!side) side='0';
  if(!/^[-+]/.test(side)) side='+'+side; var re=/([-+])(\(?\d*\.?\d*(?:\/\d*\.?\d+)?\)?)([xy]?)/g, m, r={x:0,y:0,c:0}, used=0;
  while((m=re.exec(side))!==null){ if(m[0]==='') { re.lastIndex++; continue; } used+=m[0].length; var co=m[2].replace(/[()]/g,''); var v=co===''?1:pFrac(co); if(v===null) return null; if(m[1]==='-') v=-v; if(m[3]) r[m[3]]+=v; else { if(co==='') return null; r.c+=v; } }
  if(used!==side.length) return null; return r; }
function hpParse(s){ s=String(s).replace(/<=/g,'≤').replace(/>=/g,'≥'); var m=s.match(/^(.*?)(≤|≥|<|>)(.*)$/); if(!m) return null;
  var L=linParse(m[1]), R=linParse(m[3]); if(!L||!R) return null; var a=L.x-R.x, b=L.y-R.y, c=R.c-L.c, op=m[2];
  if(Math.abs(a)<1e-12&&Math.abs(b)<1e-12) return null; var n=Math.sqrt(a*a+b*b), sg=(Math.abs(a)>1e-12? (a>0?1:-1):(b>0?1:-1));
  a=a/n*sg; b=b/n*sg; c=c/n*sg; if(sg<0) op={'≤':'≥','≥':'≤','<':'>','>':'<'}[op]; return {a:a,b:b,c:c,op:op}; }
function hpList(s){ s=String(s||'').trim(); if(!s) return null; var parts=s.split(/\s*(?:;|,|\band\b)\s*/).filter(Boolean), o=[]; for(var i=0;i<parts.length;i++){ var h=hpParse(parts[i]); if(!h) return null; o.push(h);} return o; }
function hpEq(x,y){ var A=hpList(x),B=hpList(y); if(!A||!B||A.length!==B.length) return false; var used=B.map(function(){return false;});
  return A.every(function(p){ for(var j=0;j<B.length;j++){ var q=B[j]; if(!used[j]&&p.op===q.op&&Math.abs(p.a-q.a)<1e-6&&Math.abs(p.b-q.b)<1e-6&&Math.abs(p.c-q.c)<1e-6){ used[j]=true; return true; } } return false; }); }
function gcd(a,b){ a=Math.abs(a);b=Math.abs(b); while(b){ var t=a%b;a=b;b=t;} return a; }
function hpFmtInt(a,b,c,op){ var g=gcd(gcd(a,b),c)||1; a/=g;b/=g;c/=g; if(a<0||(a===0&&b<0)){ a=-a;b=-b;c=-c; op=({'≤':'≥','≥':'≤','<':'>','>':'<'}[op]||op); }
  function term(k,v,first){ if(!k) return ''; var s=(k<0?(first?'−':' − '):(first?'':' + ')); var m=Math.abs(k); return s+(m===1?'':m)+v; }
  var lhs=term(a,'x',true); lhs+=term(b,'y',lhs===''); return lhs+' '+op+' '+String(c).replace('-','−'); }
/* ---- answer checking ---- */
(function(){ var _am=answerMatches; answerMatches=function(input,answer,accept,expr){
  if(expr==='plot1'||expr==='plot2'){ if(input===undefined||input===null||String(input).trim()==='') return false; var f=expr==='plot1'?ivEq:hpEq;
    return [answer].concat(accept||[]).some(function(a){ return f(input,a); }); }
  return _am.apply(this,arguments); }; })();
/* ---- SVG helpers ---- */
function sv(tag,attrs){ return '<'+tag+' '+Object.keys(attrs).map(function(k){return k+'="'+attrs[k]+'"';}).join(' ')+'/>'; }
/* ---- number-line widget ---- */
function nlEncode(st){ var P=st.pts.slice().sort(function(p,q){return p.v-q.v;}), n=P.length, R=[];
  for(var i=0;i<=n;i++){ R.push({a:i===0?-Infinity:P[i-1].v, b:i===n?Infinity:P[i].v, on:!!st.sh[i]}); }
  var L=[]; R.forEach(function(r,i){ if(r.on) L.push({a:r.a,ai:i>0&&P[i-1].closed,b:r.b,bi:i<n&&P[i].closed}); });
  P.forEach(function(p,i){ if(p.closed && !st.sh[i] && !st.sh[i+1]) L.push({a:p.v,ai:true,b:p.v,bi:true}); });
  var out=[]; L.forEach(function(t){ out.push(t); }); return ivFmt(ivNorm(out)); }
function nlDraw(w){ var st=w._st, lo=st.lo, hi=st.hi, W=340, H=78, x0=22, x1=W-22, y=40, X=function(v){ return x0+(v-lo)/(hi-lo)*(x1-x0); };
  var P=st.pts.slice().sort(function(p,q){return p.v-q.v;}), n=P.length, h='';
  var col='var(--accent-text)';
  for(var i=0;i<=n;i++){ if(!st.sh[i]) continue; var a=i===0?x0-14:X(P[i-1].v), b=i===n?x1+14:X(P[i].v);
    h+=sv('line',{x1:a,y1:y,x2:b,y2:y,style:'stroke:'+col+';stroke-width:7;stroke-linecap:round;opacity:.85'});
    if(i===0) h+='<polygon points="'+(x0-18)+','+y+' '+(x0-6)+','+(y-8)+' '+(x0-6)+','+(y+8)+'" style="fill:'+col+'"/>';
    if(i===n) h+='<polygon points="'+(x1+18)+','+y+' '+(x1+6)+','+(y-8)+' '+(x1+6)+','+(y+8)+'" style="fill:'+col+'"/>'; }
  h=sv('line',{x1:x0-16,y1:y,x2:x1+16,y2:y,style:'stroke:var(--ink);stroke-width:1.6'})+h;
  var every=Math.max(1,Math.ceil((hi-lo)/14));
  for(var v=Math.ceil(lo/st.step)*st.step; v<=hi+1e-9; v+=st.step){ var big=Math.abs(v-Math.round(v))<1e-9; var xx=X(v);
    h+=sv('line',{x1:xx,y1:y-(big?8:4),x2:xx,y2:y+(big?8:4),style:'stroke:var(--ink);stroke-width:'+(big?1.4:1)});
    if(big && Math.round(v)%every===0) h+='<text x="'+xx+'" y="'+(y+24)+'" text-anchor="middle" style="font:13px sans-serif;fill:var(--ink)">'+String(Math.round(v)).replace('-','−')+'</text>'; }
  P.forEach(function(p){ h+=sv('circle',{cx:X(p.v),cy:y,r:7,style:'stroke:'+col+';stroke-width:2.5;fill:'+(p.closed?col:'var(--card)')}); });
  if(st.key){ var K=ivParse(st.key)||[]; K.forEach(function(t){ var a=isFinite(t.a)?X(t.a):x0-14, b=isFinite(t.b)?X(t.b):x1+14;
      h+=sv('line',{x1:a,y1:y-17,x2:b,y2:y-17,style:'stroke:var(--success);stroke-width:5;stroke-linecap:round'});
      if(isFinite(t.a)) h+=sv('circle',{cx:a,cy:y-17,r:5,style:'stroke:var(--success);stroke-width:2;fill:'+(t.ai?'var(--success)':'var(--card)')});
      if(isFinite(t.b)) h+=sv('circle',{cx:b,cy:y-17,r:5,style:'stroke:var(--success);stroke-width:2;fill:'+(t.bi?'var(--success)':'var(--card)')}); }); }
  w.querySelector('.plw-svg').innerHTML='<svg viewBox="0 0 '+W+' '+H+'" style="width:100%;max-width:520px;touch-action:manipulation">'+h+'</svg>';
  w._X=X; w._x0=x0; w._x1=x1; w._W=W; }
function nlTap(w,ev){ var st=w._st; if(st.ro) return; var svg=w.querySelector('svg'), r=svg.getBoundingClientRect(), px=(ev.clientX-r.left)*w._W/r.width;
  var v=st.lo+(px-w._x0)/(w._x1-w._x0)*(st.hi-st.lo), sv_=Math.round(v/st.step)*st.step;
  var near=Math.abs(sv_-v)<st.step*0.28 && sv_>=st.lo-1e-9 && sv_<=st.hi+1e-9;
  if(near){ var idx=-1; st.pts.forEach(function(p,i){ if(Math.abs(p.v-sv_)<1e-9) idx=i; });
    if(idx<0){ st.pts.push({v:Math.round(sv_*1e6)/1e6,closed:true}); st.sh={}; } else if(st.pts[idx].closed){ st.pts[idx].closed=false; } else { st.pts.splice(idx,1); st.sh={}; } }
  else { var P=st.pts.slice().sort(function(p,q){return p.v-q.v;}), i=0; while(i<P.length && P[i].v<v) i++; st.sh[i]=!st.sh[i]; }
  plwSave(w); }
/* ---- grid widget ---- */
function clipPoly(poly,a,b,c,ge){ var out=[], f=function(p){ var s=a*p[0]+b*p[1]-c; return ge? s>=-1e-9 : s<=1e-9; };
  for(var i=0;i<poly.length;i++){ var P=poly[i], Q=poly[(i+1)%poly.length], fp=f(P), fq=f(Q);
    if(fp) out.push(P); if(fp!==fq){ var sp=a*P[0]+b*P[1]-c, sq=a*Q[0]+b*Q[1]-c, t=sp/(sp-sq); out.push([P[0]+t*(Q[0]-P[0]),P[1]+t*(Q[1]-P[1])]); } } return out; }
function grLines(st){ return st.lines.map(function(L){ var a=L.p2[1]-L.p1[1], b=L.p1[0]-L.p2[0], c=a*L.p1[0]+b*L.p1[1]; return {a:a,b:b,c:c,L:L}; }); }
function grEncode(st){ var o=[]; var bad=false; grLines(st).forEach(function(q){ if(!q.L.side){ bad=true; return; } var s=q.a*q.L.side[0]+q.b*q.L.side[1]-q.c; if(Math.abs(s)<1e-9){ bad=true; return; }
    var op=s<0?(q.L.solid?'≤':'<'):(q.L.solid?'≥':'>'); o.push(hpFmtInt(q.a,q.b,q.c,op)); }); return (bad||!o.length)?'':o.join('; '); }
function grDraw(w){ var st=w._st, lo=st.lo, hi=st.hi, W=340, pad=18, S=(W-2*pad)/(hi-lo), X=function(x){return pad+(x-lo)*S;}, Y=function(y){return W-pad-(y-lo)*S;}, h='';
  var box=[[lo,lo],[hi,lo],[hi,hi],[lo,hi]], every=Math.max(1,Math.ceil((hi-lo)/12));
  for(var g=lo; g<=hi; g++){ var ax=(g===0); h+=sv('line',{x1:X(g),y1:Y(lo),x2:X(g),y2:Y(hi),style:'stroke:'+(ax?'var(--ink)':'var(--rule)')+';stroke-width:'+(ax?1.6:1)});
    h+=sv('line',{x1:X(lo),y1:Y(g),x2:X(hi),y2:Y(g),style:'stroke:'+(ax?'var(--ink)':'var(--rule)')+';stroke-width:'+(ax?1.6:1)});
    if(g!==0 && g%every===0 && lo<=0 && hi>=0){ h+='<text x="'+X(g)+'" y="'+(Y(0)+13)+'" text-anchor="middle" style="font:10px sans-serif;fill:var(--ink-soft)">'+String(g).replace('-','−')+'</text>';
      h+='<text x="'+(X(0)-4)+'" y="'+(Y(g)+3)+'" text-anchor="end" style="font:10px sans-serif;fill:var(--ink-soft)">'+String(g).replace('-','−')+'</text>'; } }
  if(lo<=0&&hi>=0){ h+='<text x="'+(X(hi)-2)+'" y="'+(Y(0)-5)+'" text-anchor="end" style="font:italic 13px serif;fill:var(--ink)">x</text><text x="'+(X(0)+6)+'" y="'+(Y(hi)+12)+'" style="font:italic 13px serif;fill:var(--ink)">y</text>'; }
  var Ls=grLines(st), inter=box.slice(), anySide=false, cols=['#2e86de','#e67e22','#8e44ad','#16a085','#c0392b'];
  Ls.forEach(function(q,i){ if(!q.L.side) return; anySide=true; var s=q.a*q.L.side[0]+q.b*q.L.side[1]-q.c, ge=s>0; var pl=clipPoly(box,q.a,q.b,q.c,ge); inter=clipPoly(inter,q.a,q.b,q.c,ge);
    if(pl.length>2) h+='<polygon points="'+pl.map(function(p){return X(p[0])+','+Y(p[1]);}).join(' ')+'" style="fill:'+cols[i%5]+';opacity:.13"/>'; });
  if(anySide && Ls.length>1 && inter.length>2) h+='<polygon points="'+inter.map(function(p){return X(p[0])+','+Y(p[1]);}).join(' ')+'" style="fill:var(--accent-text);opacity:.28"/>';
  if(st.key){ var K=hpList(st.key)||[], kin=box.slice(); K.forEach(function(k){ var ge=(k.op==='≥'||k.op==='>'); kin=clipPoly(kin,k.a,k.b,k.c,ge); });
    if(kin.length>2) h+='<polygon points="'+kin.map(function(p){return X(p[0])+','+Y(p[1]);}).join(' ')+'" style="fill:none;stroke:var(--success);stroke-width:3;stroke-dasharray:2 3"/>'; }
  Ls.forEach(function(q,i){ var seg=clipLine(q.a,q.b,q.c,lo,hi); if(!seg) return;
    h+=sv('line',{x1:X(seg[0][0]),y1:Y(seg[0][1]),x2:X(seg[1][0]),y2:Y(seg[1][1]),style:'stroke:'+cols[i%5]+';stroke-width:'+(i===st.sel?3.4:2.6)+(q.L.solid?'':';stroke-dasharray:8 6')});
    [q.L.p1,q.L.p2].forEach(function(p){ h+=sv('circle',{cx:X(p[0]),cy:Y(p[1]),r:4.5,style:'fill:'+cols[i%5]}); });
    if(q.L.side) h+='<text x="'+X(q.L.side[0])+'" y="'+(Y(q.L.side[1])+5)+'" text-anchor="middle" style="font:bold 15px sans-serif;fill:'+cols[i%5]+'">✓</text>'; });
  if(st.pend) h+=sv('circle',{cx:X(st.pend[0]),cy:Y(st.pend[1]),r:6,style:'fill:none;stroke:var(--danger);stroke-width:2.5'});
  w.querySelector('.plw-svg').innerHTML='<svg viewBox="0 0 '+W+' '+W+'" style="width:100%;max-width:460px;touch-action:manipulation">'+h+'</svg>';
  w._inv=function(px,py){ return [lo+(px-pad)/S, lo+(W-pad-py)/S]; }; w._W=W;
  var list=w.querySelector('.plw-list'); list.innerHTML=st.lines.map(function(L,i){ var q=Ls[i]; var eq=hpFmtInt(q.a,q.b,q.c,'=').replace(' = ',' = ');
    return '<div class="plw-row'+(i===st.sel?' sel':'')+'" data-i="'+i+'"><span class="plw-sw" style="background:'+cols[i%5]+'"></span><span class="plw-eq">'+eq+'</span>'+
      (st.ro?'':'<button type="button" data-a="style">'+(L.solid?'━ solid (≤, ≥)':'┅ dashed (<, >)')+'</button><button type="button" data-a="side">'+(L.side?'🎨 change side':'🎨 shade a side')+'</button><button type="button" data-a="del" aria-label="Delete line">✕</button>')+'</div>'; }).join('');
  var msg=w.querySelector('.plw-msg'); msg.textContent= st.ro?'':(st.pend?'Tap a second grid point on the line.':(st.mode==='side'?'Tap a point in the region you want to keep (not on the line).':(st.lines.length?'Tap two grid points to draw another boundary line, or adjust a line below.':'Tap two grid points to draw the boundary line.'))); }
function clipLine(a,b,c,lo,hi){ var P=[]; if(Math.abs(b)>1e-12){ [lo,hi].forEach(function(x){ var y=(c-a*x)/b; if(y>=lo-1e-9&&y<=hi+1e-9) P.push([x,y]); }); }
  if(Math.abs(a)>1e-12){ [lo,hi].forEach(function(y){ var x=(c-b*y)/a; if(x>=lo-1e-9&&x<=hi+1e-9) P.push([x,y]); }); }
  if(P.length<2) return null; var best=[P[0],P[1]], d=0; for(var i=0;i<P.length;i++) for(var j=i+1;j<P.length;j++){ var dd=Math.hypot(P[i][0]-P[j][0],P[i][1]-P[j][1]); if(dd>d){ d=dd; best=[P[i],P[j]]; } } return best; }
function grTap(w,ev){ var st=w._st; if(st.ro) return; var svg=w.querySelector('svg'), r=svg.getBoundingClientRect(); var p=w._inv((ev.clientX-r.left)*w._W/r.width,(ev.clientY-r.top)*w._W/r.width);
  if(st.mode==='side' && st.sel>=0 && st.lines[st.sel]){ var L=st.lines[st.sel]; var a=L.p2[1]-L.p1[1], b=L.p1[0]-L.p2[0], c=a*L.p1[0]+b*L.p1[1]; if(Math.abs(a*p[0]+b*p[1]-c)/Math.hypot(a,b)<0.15){ return; } L.side=[Math.round(p[0]*100)/100,Math.round(p[1]*100)/100]; st.mode='draw'; plwSave(w); return; }
  var g=[Math.round(p[0]),Math.round(p[1])]; if(g[0]<st.lo||g[0]>st.hi||g[1]<st.lo||g[1]>st.hi) return;
  if(!st.pend){ st.pend=g; grDraw(w); return; } if(g[0]===st.pend[0]&&g[1]===st.pend[1]){ st.pend=null; grDraw(w); return; }
  st.lines.push({p1:st.pend,p2:g,solid:true,side:null}); st.pend=null; st.sel=st.lines.length-1; st.mode='side'; plwSave(w); }
/* ---- wiring ---- */
function plwSave(w){ var st=w._st, enc; if(st.kind==='1d'){ enc=nlEncode(st); nlDraw(w); } else { enc=grEncode(st); grDraw(w); }
  var inp=w._inp; if(inp && !inp.disabled){ inp.value=enc; inp.dispatchEvent(new Event('input',{bubbles:true})); }
  try{ PLT[w._key]=JSON.stringify({pts:st.pts,sh:st.sh,lines:st.lines}); }catch(e){}
  var sm=w.querySelector('.plw-sum'); if(sm) sm.innerHTML= enc? 'Your graph shows: <b>'+esc(enc)+'</b>' : (st.kind==='2d'&&st.lines.length?'Shade a side for every line to finish.':''); }
function plwInit(){ document.querySelectorAll('.plotw').forEach(function(w){ if(w._st) return;
  var figd=w.closest('.fig'), line=figd&&figd.nextElementSibling, inp=line&&line.querySelector('.blank-input'); w._inp=inp||null;
  if(inp){ inp.setAttribute('tabindex','-1'); inp.setAttribute('inputmode','none'); inp.style.cssText='position:absolute;opacity:0;width:1px;height:1px;padding:0;border:0;pointer-events:none;'; }
  var kind=w.dataset.kind, st={kind:kind,lo:parseFloat(w.dataset.lo),hi:parseFloat(w.dataset.hi),step:parseFloat(w.dataset.step||'1'),pts:[],sh:{},lines:[],pend:null,sel:-1,mode:'draw',ro:!!(inp&&inp.disabled),key:null};
  w._st=st; w._key=MODE+'|'+activeTab+'|'+state.tabs[activeTab].idx+'|'+(inp?inp.dataset.step:'')+'|'+(w.dataset.id||'');
  var saved=PLT[w._key]; if(saved){ try{ var o=JSON.parse(saved); st.pts=o.pts||[]; st.sh=o.sh||{}; st.lines=o.lines||[]; }catch(e){} }
  else if(inp && inp.value){ if(kind==='1d'){ (ivParse(inp.value)||[]).forEach(function(t){ /* rebuild from value */ var i0=st.pts.length;
        if(isFinite(t.a)) st.pts.push({v:t.a,closed:t.ai}); if(isFinite(t.b)&&t.b!==t.a) st.pts.push({v:t.b,closed:t.bi}); });
      var P=st.pts.slice().sort(function(p,q){return p.v-q.v;}); st.pts=P; var L=ivParse(inp.value)||[]; for(var i=0;i<=P.length;i++){ var m=(i===0?(P.length?P[0].v-1:0):(i===P.length?P[i-1].v+1:(P[i-1].v+P[i].v)/2)); st.sh[i]=L.some(function(t){ return m>t.a&&m<t.b; }); } } }
  if(st.ro && inp && w.dataset.key){ var ok=(kind==='1d'?ivEq:hpEq)(inp.value,w.dataset.key); if(!ok) st.key=w.dataset.key; }
  if(MODE==='quiz') st.key=null;
  w.innerHTML='<div class="plw-svg"></div>'+(kind==='2d'?'<div class="plw-list"></div><div class="plw-msg"></div>':'<div class="plw-msg">'+(st.ro?'':'Tap a number to place an endpoint (tap again: ● closed → ○ open → remove). Tap a part of the line to shade it.')+'</div>')+
    (st.ro?'':'<div class="plw-tools"><button type="button" data-a="undo">↩ Undo</button><button type="button" data-a="clear">🗑 Clear</button></div>')+'<div class="plw-sum"></div>'+(st.key?'<div class="plw-key">Correct graph shown in <b style="color:var(--success)">green</b>: '+esc(w.dataset.key)+'</div>':'');
  w._hist=[];
  w.addEventListener('click',function(ev){ var b=ev.target.closest('button[data-a]'); if(!b) return; ev.preventDefault(); var a=b.dataset.a;
    if(a==='clear'){ st.pts=[]; st.sh={}; st.lines=[]; st.pend=null; st.sel=-1; st.mode='draw'; plwSave(w); return; }
    if(a==='undo'){ if(kind==='1d'){ st.pts.pop(); st.sh={}; } else { if(st.pend) st.pend=null; else st.lines.pop(); st.sel=st.lines.length-1; st.mode='draw'; } plwSave(w); return; }
    var row=b.closest('.plw-row'); if(!row) return; var i=parseInt(row.dataset.i,10); st.sel=i;
    if(a==='style'){ st.lines[i].solid=!st.lines[i].solid; plwSave(w); }
    if(a==='side'){ st.mode='side'; grDraw(w); }
    if(a==='del'){ st.lines.splice(i,1); st.sel=st.lines.length-1; st.mode='draw'; plwSave(w); } });
  w.querySelector('.plw-svg').addEventListener('click',function(ev){ if(kind==='1d') nlTap(w,ev); else grTap(w,ev); });
  if(kind==='1d') nlDraw(w); else grDraw(w); plwSave0(w); }); }
function plwSave0(w){ var st=w._st, enc=st.kind==='1d'?nlEncode(st):grEncode(st); var sm=w.querySelector('.plw-sum'); if(sm&&enc&&(st.pts.length||st.lines.length)) sm.innerHTML='Your graph shows: <b>'+esc(enc)+'</b>'; }
(function(){ var _rs=renderSlide; renderSlide=function(){ _rs.apply(this,arguments); try{ if(document.querySelector('#wrap .plotw')){ plwInit();
  var sl=SLIDES[activeTab][state.tabs[activeTab].idx]; if(sl&&sl.flat&&sl.flat.every(function(s){ return !s.expr||s.expr==='plot1'||s.expr==='plot2'; })) document.querySelectorAll('#wrap .quiz-hint').forEach(function(q){ if(/Type expressions/.test(q.textContent)) q.remove(); }); } }catch(e){ console.log('plot',e); } }; })();


/* ================= v6: helpers ================= */
function v6Correct(tab,i){ var it=state.tabs[tab].items[i]; if(MODE==='quiz'){ try{ return isSlideCorrect(tab,i); }catch(e){ return false; } } var c=v4Class(it); return c==='c1'||c==='c2'; }
function v6Stats(tab){ var ts=state.tabs[tab]; if(!ts||!ts.items) return null; var sl=SLIDES[tab]||[], o={n:ts.items.length,ans:0,ok:0,c1:0,c2:0,w:0,sk:0,wrong:[],byKind:{mcq:[0,0],step:[0,0],plot:[0,0]},stepFail:{first:0,mid:0,last:0}};
  ts.items.forEach(function(it,i){ var s=sl[i]||{}, kind=s.kind==='mcq'||s.kind==='ar'?'mcq':((s.flat||[]).some(function(f){return f.expr==='plot1'||f.expr==='plot2';})?'plot':'step');
    if(MODE==='quiz'){ var att=false; try{ att=isSlideAttempted(tab,i); }catch(e){} if(!att) return; o.ans++; var ok=v6Correct(tab,i); if(ok) o.ok++; else o.wrong.push(i); o.byKind[kind][0]++; if(ok) o.byKind[kind][1]++; return; }
    var c=v4Class(it); if(c==='un') return; if(c==='sk'){ o.sk++; return; } o.ans++; o.byKind[kind][0]++;
    if(c==='c1'){ o.c1++; o.ok++; o.byKind[kind][1]++; } else if(c==='c2'){ o.c2++; o.ok++; o.byKind[kind][1]++; } else { o.w++; o.wrong.push(i); }
    if(it.stepStates&&it.stepStates.length>1){ var L=it.stepStates.length; it.stepStates.forEach(function(ss,k){ if(ss.status==='revealed'||(ss.attempts||0)>0){ if(k===0) o.stepFail.first++; else if(k===L-1) o.stepFail.last++; else o.stepFail.mid++; } }); } });
  o.acc=o.ans?Math.round(o.ok/o.ans*100):null; o.first=o.ans?Math.round(o.c1/o.ans*100):null; return o; }
function v6Qtabs(){ return TAB_DEFS.filter(function(t){ return SLIDES[t.id]&&SLIDES[t.id].length; }); }

/* ================= v6: accuracy meter ================= */
(function(){ var sp=document.querySelector('.slide-progress'); if(!sp) return; var m=document.createElement('div'); m.id='accMeter'; m.className='accm'; sp.parentNode.insertBefore(m, sp.nextSibling); })();
function v6Gauge(p){ var r=26, cx=32, cy=32, a=Math.PI*(1-(p||0)/100), x=cx+r*Math.cos(a), y=cy-r*Math.sin(a), col=p===null?'var(--rule)':(p>=75?'var(--success)':p>=50?'var(--gold)':'var(--danger)');
  return '<svg viewBox="0 0 64 38" class="accg"><path d="M6 32 A26 26 0 0 1 58 32" style="fill:none;stroke:var(--rule);stroke-width:7;stroke-linecap:round"/>'+(p?'<path d="M6 32 A26 26 0 0 1 '+x.toFixed(1)+' '+y.toFixed(1)+'" style="fill:none;stroke:'+col+';stroke-width:7;stroke-linecap:round"/>':'')+
    '<line x1="32" y1="32" x2="'+(cx+20*Math.cos(a)).toFixed(1)+'" y2="'+(cy-20*Math.sin(a)).toFixed(1)+'" style="stroke:var(--ink);stroke-width:2.5;stroke-linecap:round"/><circle cx="32" cy="32" r="3.5" style="fill:var(--ink)"/></svg>'; }
function v6Meter(){ var m=document.getElementById('accMeter'); if(!m) return; var tab=activeTab, sl=SLIDES[tab];
  if(!MODE||!sl||!sl.length||!state.tabs[tab]){ m.style.display='none'; return; } m.style.display='';
  var o=v6Stats(tab); var all={ans:0,ok:0}; v6Qtabs().forEach(function(t){ var s=v6Stats(t.id); if(s){ all.ans+=s.ans; all.ok+=s.ok; } });
  var chap=all.ans?Math.round(all.ok/all.ans*100):null;
  if(MODE==='quiz'){ m.innerHTML=v6Gauge(null)+'<div class="acct"><b>🎯 Accuracy</b><span>Quiz mode: answered '+o.ans+' of '+o.n+' — your accuracy appears when you finish this sheet.</span></div>'; return; }
  var p=o.acc, lab=p===null?'—':p+'%', col=p===null?'':(p>=75?'g':p>=50?'o':'r');
  m.innerHTML=v6Gauge(p)+'<div class="acct"><b>🎯 Accuracy <span class="accp '+col+'">'+lab+'</span></b><span>'+(o.ans?o.ok+' of '+o.ans+' right · '+o.c1+' on the first try':'Answer a question to start the meter')+(chap!==null?' · Chapter '+chap+'%':'')+'</span></div>'; }
(function(){ var _rs=renderSlide; renderSlide=function(){ _rs.apply(this,arguments); try{ v6Meter(); }catch(e){} }; })();
(function(){ var _sc=showChrome; showChrome=function(show){ _sc(show); var m=document.getElementById('accMeter'); if(m&&!show) m.style.display='none'; }; })();

/* ================= v6: observations on the finished card ================= */
function v6NoteFor(tab){ var b=null, sec=null; try{ var tmp=document.createElement('div'); tmp.innerHTML=(typeof THEORY!=='undefined'?THEORY:''); b=tmp.querySelector('section [data-go="'+tab+'"]'); }catch(e){}
  if(b) sec=b.closest('section'); return sec&&sec.id?sec.id:null; }
function v6Observe(){ var done=document.querySelector('#wrap .done-card'); if(!done||done.dataset.v6) return; done.dataset.v6='1';
  var tab=activeTab, o=v6Stats(tab); if(!o||!o.ans) return; var first=(student&&student.name)?String(student.name).split(' ')[0]:'You';
  var tdef=TAB_DEFS.find(function(t){return t.id===tab;})||{label:''}, acc=o.acc, lvl, lvlc;
  if(acc>=90){ lvl='Excellent understanding — this topic is mastered'; lvlc='g'; } else if(acc>=75){ lvl='Strong understanding — just a few points to polish'; lvlc='g'; } else if(acc>=50){ lvl='Developing understanding — the basics are in place'; lvlc='o'; } else { lvl='Building understanding — a little more practice will make it click'; lvlc='r'; }
  var pos=[], grow=[], rev=[];
  // positive diagnostic remarks
  if(MODE!=='quiz' && o.first>=70) pos.push('Your first-try accuracy of <b>'+o.first+'%</b> shows you understood the method before checking.');
  if(MODE!=='quiz' && o.c2>0) pos.push('You corrected <b>'+o.c2+'</b> answer'+(o.c2>1?'s':'')+' on the second try — spotting and fixing your own mistakes is a great habit.');
  var K={mcq:'multiple-choice reasoning',step:'step-by-step working',plot:'plotting graphs'}, best=null, worst=null;
  Object.keys(o.byKind).forEach(function(k){ var v=o.byKind[k]; if(v[0]<2) return; var r=v[1]/v[0]; if(!best||r>best.r) best={k:k,r:r}; if(!worst||r<worst.r) worst={k:k,r:r}; });
  if(best && best.r>=0.6) pos.push('A real strength: <b>'+K[best.k]+'</b> ('+Math.round(best.r*100)+'% correct).');
  if(o.sk===0 && o.ans===o.n) pos.push('You attempted every question in the sheet — excellent persistence.');
  if(acc>=90) pos.push('You are ready to move on to the next sheet with confidence.');
  if(!pos.length) pos.push('You finished the whole sheet, '+esc(first)+' — finishing is the first step to mastering it. Every question you worked through added to your understanding.');
  // growth areas
  if(worst && best && worst.k!==best.k && worst.r<0.6) grow.push('Practise more <b>'+K[worst.k]+'</b> ('+Math.round(worst.r*100)+'% correct so far).');
  var sf=o.stepFail, tot=sf.first+sf.mid+sf.last; if(MODE!=='quiz' && tot>=2){ var mx=Math.max(sf.first,sf.mid,sf.last);
    if(mx===sf.first) grow.push('Most slips happened in the <b>first step</b> — re-read the question and set up the method carefully before calculating.');
    else if(mx===sf.last) grow.push('Most slips happened in the <b>final step</b> — the method was right; check the last simplification or rounding.');
    else grow.push('Most slips happened in the <b>middle steps</b> — write each line of working fully and check signs and arithmetic.'); }
  if(o.wrong.length) grow.push('Have another look at '+(o.wrong.length>1?'these questions':'this question')+': '+o.wrong.slice(0,10).map(function(i){ return '<button type="button" class="v6q" data-q="'+i+'">Q'+(i+1)+'</button>'; }).join(' ')+(o.wrong.length>10?' …':''));
  if(o.sk) grow.push('Come back to the <b>'+o.sk+'</b> skipped question'+(o.sk>1?'s':'')+' when you are ready.');
  // review suggestions
  var nid=v6NoteFor(tab); if(acc<75 && nid) rev.push('<button type="button" class="v6r" data-n="'+nid+'">📖 Re-read the notes for '+esc(tdef.label)+'</button>');
  var tabs=v6Qtabs(), ci=tabs.findIndex(function(t){return t.id===tab;}), weakPrev=[];
  for(var j=0;j<ci;j++){ var t=tabs[j]; if(/^Assessment|Test|Report/i.test(t.label)) continue; var s=v6Stats(t.id); if(s&&s.ans&&s.acc<60) weakPrev.push({t:t,a:s.acc}); else if(acc<60 && j===ci-1 && (!s||!s.ans)) weakPrev.push({t:t,a:null}); }
  weakPrev.slice(-3).forEach(function(w){ rev.push('<button type="button" class="v6t" data-t="'+w.t.id+'">🔁 Review '+esc(w.t.label)+(w.a!==null?' (you scored '+w.a+'%)':' (not attempted yet)')+'</button>'); });
  var revTxt = rev.length? '<div class="v6sub">Suggested review</div><div class="v6btns">'+rev.join('')+'</div>' : '<div class="v6sub">Suggested review</div><p class="v6p">'+(acc>=75?'No earlier topics need review — you are ready for the next sheet.':'Re-try the questions above, then move on.')+'</p>';
  var box=document.createElement('div'); box.className='v6obs';
  box.innerHTML='<div class="v6h">📝 Teacher’s observations</div><div class="v6lvl '+lvlc+'">'+lvl+' · <b>'+acc+'%</b> accuracy</div>'+
    '<div class="v6sub">What went well</div><ul class="v6ul">'+pos.map(function(x){return '<li>'+x+'</li>';}).join('')+'</ul>'+
    (grow.length?'<div class="v6sub">Next steps</div><ul class="v6ul">'+grow.map(function(x){return '<li>'+x+'</li>';}).join('')+'</ul>':'')+revTxt;
  var ban=done.querySelector('.v4ban'); if(ban&&ban.nextSibling) done.insertBefore(box, ban.nextSibling); else done.appendChild(box);
  box.addEventListener('click',function(ev){ var b=ev.target.closest('button'); if(!b) return;
    if(b.dataset.q!==undefined){ var ts=state.tabs[tab]; ts.idx=parseInt(b.dataset.q,10); ts.recorded=false; showChrome(true); buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }
    else if(b.dataset.t){ activeTab=b.dataset.t; showChrome(true); buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }
    else if(b.dataset.n){ var th=TAB_DEFS.find(function(t){return t.id==='theory';}); if(th){ activeTab='theory'; showChrome(true); buildTabbar(); renderSlide(); setTimeout(function(){ var el=document.getElementById(b.dataset.n); if(el) el.scrollIntoView({behavior:'smooth',block:'start'}); },80); } } });
  try{ if(records[0]&&records[0].tab===tab){ records[0].obs=lvl.split(' — ')[0]; saveState(); } }catch(e){}
}
(function(){ var _rf=renderFinished; renderFinished=function(){ _rf.apply(this,arguments); try{ v6Observe(); }catch(e){ console.log('v6',e); } }; })();

/* ================= v6: whiteboard ================= */
var WB={on:false,pages:[[]],pg:0,tool:'pen',color:'#1f2937',size:4,bg:'grid',redo:[],cur:null,cv:null,ctx:null,w0:0};
var WB_COLS=['#1f2937','#2563eb','#dc2626','#16a34a','#ea580c','#9333ea','#db2777','#ffffff'];
function wbKey(){ try{ return 'sopaan-wb::'+document.title+'::'+(student?student.name+'#'+student.roll:'')+'::'+MODE+'|'+activeTab+'|'+((state.tabs[activeTab]||{}).idx||0); }catch(e){ return 'sopaan-wb'; } }
function wbLoad(){ WB.pages=[[]]; WB.pg=0; WB.redo=[]; WB.w0=0; try{ var s=localStorage.getItem(wbKey()); if(s){ var o=JSON.parse(s); if(o&&o.pages){ WB.pages=o.pages; WB.pg=Math.min(o.pg||0,WB.pages.length-1); WB.bg=o.bg||'grid'; WB.w0=o.w0||0; } } }catch(e){} }
function wbStore(){ try{ localStorage.setItem(wbKey(), JSON.stringify({pages:WB.pages,pg:WB.pg,bg:WB.bg,w0:WB.w0})); }catch(e){} }
function wbBuild(){ if(document.getElementById('wbOv')) return; var d=document.createElement('div'); d.id='wbOv'; d.className='wbov';
  var tools=[['pen','✏️','Pen'],['hl','🖍️','Highlighter'],['er','🧽','Eraser'],['line','／','Line'],['arrow','➚','Arrow'],['rect','▭','Rectangle'],['ell','◯','Circle'],['text','T','Text']];
  d.innerHTML='<div class="wbbar"><button type="button" data-a="close" class="wbx" title="Close">✕ Close</button><span class="wbsep"></span>'+tools.map(function(t){ return '<button type="button" class="wbt" data-tool="'+t[0]+'" title="'+t[2]+'">'+t[1]+'</button>'; }).join('')+
    '<span class="wbsep"></span>'+WB_COLS.map(function(c){ return '<button type="button" class="wbc" data-col="'+c+'" style="background:'+c+'" title="Colour"></button>'; }).join('')+
    '<span class="wbsep"></span><input type="range" min="1" max="24" value="4" class="wbsz" title="Size"><span class="wbsep"></span>'+
    '<button type="button" data-a="undo" title="Undo">↶</button><button type="button" data-a="redo" title="Redo">↷</button><button type="button" data-a="bg" title="Background">▦</button><button type="button" data-a="clear" title="Clear page">🗑</button>'+
    '<span class="wbsep"></span><button type="button" data-a="prev" title="Previous page">◀</button><span class="wbpg"></span><button type="button" data-a="next" title="Next / new page">▶</button>'+
    '<span class="wbsep"></span><button type="button" data-a="save" title="Save as picture">💾</button></div><div class="wbbody"><div class="wbq"><div class="wbqh"><b>📌 Question</b><button type="button" class="wbqt">Hide question</button></div><div class="wbqc"></div></div><canvas class="wbcv"></canvas></div>';
  document.body.appendChild(d); d.querySelector('.wbqt').addEventListener('click',function(){ var q=d.querySelector('.wbq'); q.classList.toggle('min'); this.textContent=q.classList.contains('min')?'Show question':'Hide question'; setTimeout(function(){ wbSize(); wbDraw(); },20); });
  WB.cv=d.querySelector('canvas.wbcv'); WB.ctx=WB.cv.getContext('2d');
  d.querySelector('.wbbar').addEventListener('click',function(ev){ var b=ev.target.closest('button'); if(!b) return;
    if(b.dataset.tool){ WB.tool=b.dataset.tool; wbUI(); return; } if(b.dataset.col){ WB.color=b.dataset.col; wbUI(); return; }
    var a=b.dataset.a, P=WB.pages[WB.pg];
    if(a==='undo'&&P.length){ WB.redo.push(P.pop()); } else if(a==='redo'&&WB.redo.length){ P.push(WB.redo.pop()); } else if(a==='clear'&&P.length){ WB.pages[WB.pg]=[]; WB.redo=[]; }
    else if(a==='bg'){ WB.bg={grid:'lines',lines:'plain',plain:'grid'}[WB.bg]; } else if(a==='prev'&&WB.pg>0){ WB.pg--; WB.redo=[]; } else if(a==='next'){ WB.pg++; if(WB.pg>=WB.pages.length) WB.pages.push([]); WB.redo=[]; }
    else if(a==='save'){ try{ var l=document.createElement('a'); l.download='whiteboard-page-'+(WB.pg+1)+'.png'; l.href=wbExport(); l.click(); }catch(e){} }
    else if(a==='close'){ wbToggle(false); return; }
    wbStore(); wbDraw(); wbUI(); });
  d.querySelector('.wbsz').addEventListener('input',function(){ WB.size=parseInt(this.value,10); });
  var cv=WB.cv; cv.addEventListener('pointerdown',wbDown); cv.addEventListener('pointermove',wbMove); cv.addEventListener('pointerup',wbUp); cv.addEventListener('pointercancel',wbUp);
  window.addEventListener('resize',function(){ if(WB.on){ wbSize(); wbDraw(); } }); }
function wbUI(){ var d=document.getElementById('wbOv'); if(!d) return; d.querySelectorAll('.wbt').forEach(function(b){ b.classList.toggle('on',b.dataset.tool===WB.tool); }); d.querySelectorAll('.wbc').forEach(function(b){ b.classList.toggle('on',b.dataset.col===WB.color); }); d.querySelector('.wbpg').textContent=(WB.pg+1)+' / '+WB.pages.length; }
function wbSize(){ var cv=WB.cv, r=cv.getBoundingClientRect(), dpr=window.devicePixelRatio||1; cv.width=Math.round(r.width*dpr); cv.height=Math.round(r.height*dpr); WB.ctx.setTransform(dpr,0,0,dpr,0,0); if(!WB.w0) WB.w0=r.width; WB.sc=r.width/WB.w0; }
function wbP(e){ var r=WB.cv.getBoundingClientRect(); return [(e.clientX-r.left)/WB.sc,(e.clientY-r.top)/WB.sc]; }
function wbDown(e){ e.preventDefault(); var p=wbP(e);
  if(WB.tool==='text'){ wbText(p); return; } WB.cv.setPointerCapture(e.pointerId);
  WB.cur={t:WB.tool,c:WB.color,s:WB.tool==='hl'?Math.max(12,WB.size*3):(WB.tool==='er'?Math.max(18,WB.size*4):WB.size),pts:[p],a:p,b:p}; }
function wbMove(e){ if(!WB.cur) return; var p=wbP(e); if(WB.cur.t==='pen'||WB.cur.t==='hl'||WB.cur.t==='er') WB.cur.pts.push(p); else WB.cur.b=p; wbDraw(); }
function wbUp(){ if(!WB.cur) return; WB.pages[WB.pg].push(WB.cur); WB.cur=null; WB.redo=[]; wbStore(); wbDraw(); }
function wbText(p){ var d=document.getElementById('wbOv'), r=WB.cv.getBoundingClientRect(); var inp=document.createElement('input'); inp.className='wbin'; inp.placeholder='Type, then Enter';
  inp.style.left=(r.left+p[0]*WB.sc)+'px'; inp.style.top=(r.top+p[1]*WB.sc-14)+'px'; inp.style.color=WB.color; d.appendChild(inp); inp.focus(); setTimeout(function(){ inp.focus(); },60);
  var fin=function(){ if(inp._d) return; inp._d=1; var v=inp.value.trim(); inp.remove(); if(v){ WB.pages[WB.pg].push({t:'text',c:WB.color,s:Math.max(24,WB.size*5),a:p,str:v}); WB.redo=[]; wbStore(); wbDraw(); } };
  inp.addEventListener('keydown',function(ev){ if(ev.key==='Enter') fin(); if(ev.key==='Escape'){ inp.value=''; fin(); } }); setTimeout(function(){ inp.addEventListener('blur',fin); },300); }
function wbShape(c,o){ var k=WB.sc; c.save(); c.lineCap='round'; c.lineJoin='round'; c.strokeStyle=c.fillStyle=o.c; c.lineWidth=o.s*k; c.globalAlpha=o.t==='hl'?0.35:1; c.globalCompositeOperation=o.t==='er'?'destination-out':'source-over';
  if(o.t==='pen'||o.t==='hl'||o.t==='er'){ c.beginPath(); o.pts.forEach(function(p,i){ if(i) c.lineTo(p[0]*k,p[1]*k); else c.moveTo(p[0]*k,p[1]*k); }); if(o.pts.length===1) c.lineTo(o.pts[0][0]*k+0.1,o.pts[0][1]*k); c.stroke(); }
  else if(o.t==='line'||o.t==='arrow'){ c.beginPath(); c.moveTo(o.a[0]*k,o.a[1]*k); c.lineTo(o.b[0]*k,o.b[1]*k); c.stroke(); if(o.t==='arrow'){ var an=Math.atan2(o.b[1]-o.a[1],o.b[0]-o.a[0]), h=(10+o.s*2)*k; c.beginPath(); c.moveTo(o.b[0]*k,o.b[1]*k); c.lineTo(o.b[0]*k-h*Math.cos(an-0.45),o.b[1]*k-h*Math.sin(an-0.45)); c.lineTo(o.b[0]*k-h*Math.cos(an+0.45),o.b[1]*k-h*Math.sin(an+0.45)); c.closePath(); c.fill(); } }
  else if(o.t==='rect'){ c.strokeRect(o.a[0]*k,o.a[1]*k,(o.b[0]-o.a[0])*k,(o.b[1]-o.a[1])*k); }
  else if(o.t==='ell'){ c.beginPath(); c.ellipse((o.a[0]+o.b[0])/2*k,(o.a[1]+o.b[1])/2*k,Math.abs(o.b[0]-o.a[0])/2*k,Math.abs(o.b[1]-o.a[1])/2*k,0,0,Math.PI*2); c.stroke(); }
  else if(o.t==='text'){ c.font=(o.s*k)+'px "Source Sans 3",sans-serif'; c.textBaseline='middle'; c.fillText(o.str,o.a[0]*k,o.a[1]*k); }
  c.restore(); }
function wbBg(c,W,H,bg){ c.fillStyle='#ffffff'; c.fillRect(0,0,W,H); if(bg==='plain') return; c.strokeStyle=bg==='grid'?'#e5e7eb':'#dbeafe'; c.lineWidth=1; var g=28*WB.sc; c.beginPath(); for(var y=g;y<H;y+=g){ c.moveTo(0,y); c.lineTo(W,y); } if(bg==='grid') for(var x=g;x<W;x+=g){ c.moveTo(x,0); c.lineTo(x,H); } c.stroke(); }
function wbDraw(){ var c=WB.ctx, r=WB.cv.getBoundingClientRect(), W=r.width, H=r.height; c.clearRect(0,0,W,H);
  var ink=document.createElement('canvas'), dpr=window.devicePixelRatio||1; ink.width=WB.cv.width; ink.height=WB.cv.height; var ic=ink.getContext('2d'); ic.setTransform(dpr,0,0,dpr,0,0);
  WB.pages[WB.pg].concat(WB.cur?[WB.cur]:[]).forEach(function(o){ wbShape(ic,o); });
  wbBg(c,W,H,WB.bg); c.save(); c.setTransform(1,0,0,1,0,0); c.drawImage(ink,0,0); c.restore(); }
function wbExport(){ return WB.cv.toDataURL('image/png'); }
function wbFillQ(){ var d=document.getElementById('wbOv'); if(!d) return; var box=d.querySelector('.wbq'), c=d.querySelector('.wbqc'), q=document.querySelector('#wrap .qcard');
  if(!q){ box.style.display='none'; return; } box.style.display='';
  var cl=q.cloneNode(true); cl.removeAttribute('id'); cl.querySelectorAll('[id]').forEach(function(e){ e.removeAttribute('id'); });
  cl.querySelectorAll('input,button,select,textarea').forEach(function(e){ e.setAttribute('tabindex','-1'); e.disabled=true; });
  cl.querySelectorAll('.feedback,.step-badge,.quiz-hint,.plw-tools,.plw-msg').forEach(function(e){ e.remove(); });
  cl.querySelectorAll('canvas').forEach(function(e){ e.remove(); });
  c.innerHTML=''; c.appendChild(cl); var tdef=(TAB_DEFS.find(function(t){return t.id===activeTab;})||{}).label||''; var h=d.querySelector('.wbqh b'); if(h) h.textContent='📌 '+tdef+' · Question '+(((state.tabs[activeTab]||{}).idx||0)+1); }
function wbToggle(on){ WB.on=(on===undefined)?!WB.on:on; wbBuild(); var d=document.getElementById('wbOv'); d.classList.toggle('show',WB.on); document.body.classList.toggle('wb-open',WB.on);
  if(WB.on){ wbLoad(); wbFillQ(); setTimeout(function(){ wbSize(); wbDraw(); wbUI(); },30); } }
(function(){ var f=document.createElement('button'); f.type='button'; f.id='wbFab'; f.className='wb-fab'; f.innerHTML='🧑‍🏫 <span>Whiteboard</span>'; f.title='Open the whiteboard'; f.addEventListener('click',function(){ wbToggle(true); }); document.body.appendChild(f); })();
(function(){ var _rs=renderSlide; renderSlide=function(){ _rs.apply(this,arguments); var f=document.getElementById('wbFab'); if(f) f.style.display=MODE?'':'none'; }; })();


/* ================= v7: scatter-graph plotter ================= */
var SCT={};
function scPts(s){ s=String(s||'').trim(); if(!s) return []; return s.split(/\s*;\s*/).filter(Boolean).map(function(p){ var a=p.replace(/[()]/g,'').split(/\s*,\s*/); return [parseFloat(a[0]),parseFloat(a[1])]; }).filter(function(p){ return isFinite(p[0])&&isFinite(p[1]); }); }
function scEqPts(inp,key,tolx,toly){ var A=scPts(inp),B=scPts(key); if(!A.length||A.length!==B.length) return false; var used=B.map(function(){return false;});
  return A.every(function(p){ for(var j=0;j<B.length;j++){ if(!used[j]&&Math.abs(p[0]-B[j][0])<=tolx+1e-9&&Math.abs(p[1]-B[j][1])<=toly+1e-9){ used[j]=true; return true; } } return false; }); }
function scLine(s){ var m=String(s||'').match(/^line:\(([^,]+),([^)]+)\)-\(([^,]+),([^)]+)\)/); if(!m) return null; var x1=+m[1],y1=+m[2],x2=+m[3],y2=+m[4]; if(Math.abs(x2-x1)<1e-9) return null; var k=(y2-y1)/(x2-x1); return {m:k,c:y1-k*x1}; }
(function(){ var _am=answerMatches; answerMatches=function(input,answer,accept,expr){
  if(expr==='spts'||expr==='slbf'){ if(input===undefined||input===null||String(input).trim()==='') return false;
    var meta=String((accept&&accept[0])||''); var mm=meta.match(/tol:([\d.]+),([\d.]+)/), tx=mm?+mm[1]:0.5, ty=mm?+mm[2]:0.5;
    if(expr==='spts') return scEqPts(input,answer,tx,ty);
    if(String(input).trim()===String(answer).trim()) return true;
    var L=scLine(input), k=String(answer).split(','), m=+k[0], c=+k[1], tol=+k[2], xa=+k[3], xb=+k[4]; if(!L) return false;
    return [xa,xb].every(function(x){ return Math.abs((L.m*x+L.c)-(m*x+c))<=tol; }); }
  return _am.apply(this,arguments); }; })();
function scDraw(w){ var st=w._st, W=360, H=300, L=52, R=14, T=14, B=44, X=function(x){ return L+(x-st.xlo)/(st.xhi-st.xlo)*(W-L-R); }, Y=function(y){ return H-B-(y-st.ylo)/(st.yhi-st.ylo)*(H-T-B); }, h='';
  function line(x1,y1,x2,y2,sty){ return '<line x1="'+x1.toFixed(1)+'" y1="'+y1.toFixed(1)+'" x2="'+x2.toFixed(1)+'" y2="'+y2.toFixed(1)+'" style="'+sty+'"/>'; }
  var fmt=function(v){ var a=Math.abs(v); return (a>=10000? (v/1000)+'k' : String(Math.round(v*100)/100)).replace('-','−'); };
  if(st.xminor) for(var x=st.xlo;x<=st.xhi+1e-9;x+=st.xminor) h+=line(X(x),Y(st.ylo),X(x),Y(st.yhi),'stroke:var(--rule);stroke-width:.6');
  if(st.yminor) for(var y=st.ylo;y<=st.yhi+1e-9;y+=st.yminor) h+=line(X(st.xlo),Y(y),X(st.xhi),Y(y),'stroke:var(--rule);stroke-width:.6');
  for(var x2=st.xlo;x2<=st.xhi+1e-9;x2+=st.xstep){ h+=line(X(x2),Y(st.ylo),X(x2),Y(st.yhi),'stroke:var(--rule);stroke-width:1.2'); h+='<text x="'+X(x2).toFixed(1)+'" y="'+(H-B+15)+'" text-anchor="middle" style="font:11px sans-serif;fill:var(--ink-soft)">'+fmt(x2)+'</text>'; }
  for(var y2=st.ylo;y2<=st.yhi+1e-9;y2+=st.ystep){ h+=line(X(st.xlo),Y(y2),X(st.xhi),Y(y2),'stroke:var(--rule);stroke-width:1.2'); h+='<text x="'+(L-5)+'" y="'+(Y(y2)+4).toFixed(1)+'" text-anchor="end" style="font:11px sans-serif;fill:var(--ink-soft)">'+fmt(y2)+'</text>'; }
  h+=line(X(st.xlo),Y(st.ylo),X(st.xhi),Y(st.ylo),'stroke:var(--ink);stroke-width:1.6')+line(X(st.xlo),Y(st.ylo),X(st.xlo),Y(st.yhi),'stroke:var(--ink);stroke-width:1.6');
  h+='<text x="'+((L+W-R)/2)+'" y="'+(H-6)+'" text-anchor="middle" style="font:600 12.5px sans-serif;fill:var(--ink)">'+esc(st.xlab)+'</text>';
  h+='<text transform="translate(13,'+((T+H-B)/2)+') rotate(-90)" text-anchor="middle" style="font:600 12.5px sans-serif;fill:var(--ink)">'+esc(st.ylab)+'</text>';
  if(st.line){ var a=st.line, xs=[st.xlo,st.xhi].map(function(x){ return [x,a[0]*x+a[1]]; }); h+='<g clip-path="url(#scclip'+w._n+')">'+line(X(xs[0][0]),Y(xs[0][1]),X(xs[1][0]),Y(xs[1][1]),'stroke:var(--accent-text);stroke-width:2')+'</g>'; }
  function cross(px,py,col,sz){ return line(px-sz,py-sz,px+sz,py+sz,'stroke:'+col+';stroke-width:2.4')+line(px-sz,py+sz,px+sz,py-sz,'stroke:'+col+';stroke-width:2.4'); }
  st.fixed.forEach(function(p){ h+=cross(X(p[0]),Y(p[1]),'var(--ink)',4.5); });
  if(st.key){ if(st.mode==='spts') scPts(st.key).forEach(function(p){ h+='<circle cx="'+X(p[0]).toFixed(1)+'" cy="'+Y(p[1]).toFixed(1)+'" r="8" style="fill:none;stroke:var(--success);stroke-width:2.5"/>'; });
    else { var k=st.key.split(',').map(Number); h+='<g clip-path="url(#scclip'+w._n+')">'+line(X(k[3]),Y(k[0]*k[3]+k[1]),X(k[4]),Y(k[0]*k[4]+k[1]),'stroke:var(--success);stroke-width:3;stroke-dasharray:6 5')+'</g>'; } }
  st.pts.forEach(function(p){ h+=cross(X(p[0]),Y(p[1]),'var(--danger)',6); });
  if(st.mode==='slbf'){ if(st.lp.length===2){ var P=st.lp, k2=(P[1][1]-P[0][1])/(P[1][0]-P[0][0]||1e-9), c2=P[0][1]-k2*P[0][0];
      var ya=k2*st.xlo+c2, yb=k2*st.xhi+c2; h+='<g clip-path="url(#scclip'+w._n+')">'+line(X(st.xlo),Y(ya),X(st.xhi),Y(yb),'stroke:var(--danger);stroke-width:2.6')+'</g>'; }
    st.lp.forEach(function(p){ h+='<circle cx="'+X(p[0]).toFixed(1)+'" cy="'+Y(p[1]).toFixed(1)+'" r="5" style="fill:var(--danger)"/>'; }); }
  w.querySelector('.scw-svg').innerHTML='<svg viewBox="0 0 '+W+' '+H+'" style="width:100%;max-width:520px;touch-action:manipulation;overflow:hidden"><clipPath id="scclip'+w._n+'"><rect x="'+L+'" y="'+T+'" width="'+(W-L-R)+'" height="'+(H-T-B)+'"/></clipPath>'+h+'</svg>';
  w._inv=function(px,py){ return [st.xlo+(px-L)/(W-L-R)*(st.xhi-st.xlo), st.ylo+(H-B-py)/(H-T-B)*(st.yhi-st.ylo)]; }; w._W=W; w._H=H; }
function scEnc(st){ if(st.mode==='spts') return st.pts.map(function(p){ return p[0]+','+p[1]; }).join('; ');
  if(st.lp.length<2) return ''; return 'line:('+st.lp[0][0]+','+st.lp[0][1]+')-('+st.lp[1][0]+','+st.lp[1][1]+')'; }
function scSave(w){ var st=w._st, enc=scEnc(st); scDraw(w); var inp=w._inp; if(inp&&!inp.disabled){ inp.value=enc; inp.dispatchEvent(new Event('input',{bubbles:true})); }
  try{ SCT[w._key]=JSON.stringify({pts:st.pts,lp:st.lp}); }catch(e){}
  var sm=w.querySelector('.scw-sum'); if(sm) sm.innerHTML= st.mode==='spts' ? (st.pts.length?'Points plotted: <b>'+st.pts.length+'</b>':'') : (st.lp.length===2?'Line drawn — tap ↩ Undo to move it.':(st.lp.length?'Tap a second point on your line.':'')); }
function scTap(w,ev){ var st=w._st; if(st.ro) return; var svg=w.querySelector('svg'), r=svg.getBoundingClientRect(), p=w._inv((ev.clientX-r.left)*w._W/r.width,(ev.clientY-r.top)*w._H/r.height);
  if(p[0]<st.xlo||p[0]>st.xhi||p[1]<st.ylo||p[1]>st.yhi) return;
  var q=[Math.round(p[0]/st.xsnap)*st.xsnap, Math.round(p[1]/st.ysnap)*st.ysnap]; q=[+q[0].toFixed(6),+q[1].toFixed(6)];
  if(st.mode==='spts'){ var i=st.pts.findIndex(function(a){ return Math.abs(a[0]-q[0])<1e-9&&Math.abs(a[1]-q[1])<1e-9; }); if(i>=0) st.pts.splice(i,1); else st.pts.push(q); }
  else { if(st.lp.length>=2) st.lp=[]; if(!(st.lp.length===1&&Math.abs(st.lp[0][0]-q[0])<1e-9)) st.lp.push(q); }
  scSave(w); }
var SCN=0;
function scInit(){ document.querySelectorAll('.scatw').forEach(function(w){ if(w._st) return; w._n=++SCN;
  var figd=w.closest('.fig'), line=figd&&figd.nextElementSibling, inp=(w.dataset.mode&&line)?line.querySelector('.blank-input'):null; w._inp=inp||null;
  if(inp){ inp.setAttribute('tabindex','-1'); inp.setAttribute('inputmode','none'); inp.style.cssText='position:absolute;opacity:0;width:1px;height:1px;padding:0;border:0;pointer-events:none;'; }
  var D=w.dataset, num=function(k,d){ var v=parseFloat(D[k]); return isFinite(v)?v:d; };
  var st={mode:D.mode||'',xlo:num('xlo',0),xhi:num('xhi',10),xstep:num('xstep',1),xminor:num('xminor',0),ylo:num('ylo',0),yhi:num('yhi',10),ystep:num('ystep',1),yminor:num('yminor',0),
    xsnap:num('xsnap',num('xminor',0)||num('xstep',1)),ysnap:num('ysnap',num('yminor',0)||num('ystep',1)),xlab:D.xlab||'',ylab:D.ylab||'',fixed:scPts(D.pts),line:D.line?D.line.split(',').map(Number):null,pts:[],lp:[],ro:!!(inp&&inp.disabled),key:null};
  w._st=st; w._key=MODE+'|'+activeTab+'|'+state.tabs[activeTab].idx+'|'+(inp?inp.dataset.step:'')+'|'+(D.id||'');
  var sv=SCT[w._key]; if(sv){ try{ var o=JSON.parse(sv); st.pts=o.pts||[]; st.lp=o.lp||[]; }catch(e){} }
  else if(inp&&inp.value){ if(st.mode==='spts') st.pts=scPts(inp.value); else { var m=inp.value.match(/^line:\(([^,]+),([^)]+)\)-\(([^,]+),([^)]+)\)/); if(m) st.lp=[[+m[1],+m[2]],[+m[3],+m[4]]]; } }
  if(st.ro && inp && D.key && MODE!=='quiz'){ if(!answerMatches(inp.value,D.key,D.meta?[D.meta]:[],st.mode)) st.key=D.key; }
  var tip=st.mode==='spts'?'Tap the grid to plot each point (tap a point again to remove it).':(st.mode==='slbf'?'Tap two points to draw your line of best fit (tap again to start over).':'');
  w.innerHTML='<div class="scw-svg"></div>'+(st.mode&&!st.ro?'<div class="plw-msg">'+tip+'</div><div class="plw-tools"><button type="button" data-a="undo">↩ Undo</button><button type="button" data-a="clear">🗑 Clear</button></div>':'')+'<div class="scw-sum"></div>'+(st.key?'<div class="plw-key">Correct answer shown in <b style="color:var(--success)">green</b>.</div>':'');
  w.addEventListener('click',function(ev){ var b=ev.target.closest('button[data-a]'); if(!b) return; ev.preventDefault(); if(b.dataset.a==='clear'){ st.pts=[]; st.lp=[]; } else { if(st.mode==='spts') st.pts.pop(); else st.lp.pop(); } scSave(w); });
  if(st.mode) w.querySelector('.scw-svg').addEventListener('click',function(ev){ scTap(w,ev); });
  scDraw(w); var sm=w.querySelector('.scw-sum'); if(sm&&st.mode==='spts'&&st.pts.length) sm.innerHTML='Points plotted: <b>'+st.pts.length+'</b>'; }); }
(function(){ var _rs=renderSlide; renderSlide=function(){ _rs.apply(this,arguments); try{ if(document.querySelector('#wrap .scatw')){ scInit();
  var sl=SLIDES[activeTab][state.tabs[activeTab].idx]; if(sl&&sl.flat&&sl.flat.every(function(s){ return !s.expr||s.expr==='spts'||s.expr==='slbf'||s.expr==='plot1'||s.expr==='plot2'; })) document.querySelectorAll('#wrap .quiz-hint').forEach(function(q){ if(/Type expressions/.test(q.textContent)) q.remove(); }); } }catch(e){ console.log('scat',e); } }; })();


/* ================= calculus answer mode ================= */
function calcCompile(src){
  var s=String(src).replace(/\s+/g,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^(2)').replace(/³/g,'^(3)').replace(/π/g,'#').replace(/θ/g,'q').replace(/eˣ/g,'e^x');
  if(s.indexOf('=')>=0) s=s.slice(s.lastIndexOf('=')+1);
  var FN=['sqrt','cbrt','abs','ln','log','exp','sin','cos','tan','sec','csc','cot','pi'];
  var i=0,toks=[];
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length&&/[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(ch==='√'){ toks.push({k:'f',v:'sqrt'}); i++; continue; }
    if(ch==='∛'){ toks.push({k:'f',v:'cbrt'}); i++; continue; }
    if(/[a-zA-Z#]/.test(ch)){
      var hit=null; for(var q=0;q<FN.length;q++){ if(s.substr(i,FN[q].length).toLowerCase()===FN[q]){ hit=FN[q]; break; } }
      if(hit==='pi'){ toks.push({k:'v',v:'#'}); i+=2; continue; }
      if(hit){ toks.push({k:'f',v:hit}); i+=hit.length; continue; }
      toks.push({k:'v',v:ch}); i++; continue; }
    if('+-*/^()|'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  // absolute value bars -> abs( )
  var t2=[],open=false; for(var a=0;a<toks.length;a++){ var tk=toks[a]; if(tk.k==='|'){ if(!open){ t2.push({k:'f',v:'abs'}); t2.push({k:'('}); open=true; } else { t2.push({k:')'}); open=false; } } else t2.push(tk); }
  toks=t2;
  var out=[];
  for(var t=0;t<toks.length;t++){ var A=toks[t], B=out[out.length-1];
    if(B&&(B.k==='n'||B.k==='v'||B.k===')')&&(A.k==='n'||A.k==='v'||A.k==='('||A.k==='f')) out.push({k:'&'});
    out.push(A); }
  var p=0; function pk(){ return out[p]; }
  var F={sqrt:Math.sqrt,cbrt:Math.cbrt,ln:Math.log,log:function(x){return Math.log(x)/Math.LN10;},exp:Math.exp,sin:Math.sin,cos:Math.cos,tan:Math.tan,
    sec:function(x){return 1/Math.cos(x);},csc:function(x){return 1/Math.sin(x);},cot:function(x){return 1/Math.tan(x);},abs:Math.abs};
  function E(){ var n=T(); while(pk()&&(pk().k==='+'||pk().k==='-')){ var o=out[p++].k,r=T(); n=(function(l,r,o){return function(e){return o==='+'?l(e)+r(e):l(e)-r(e);};})(n,r,o);} return n; }
  function T(){ var n=I(); while(pk()&&(pk().k==='*'||pk().k==='/')){ var o=out[p++].k,r=I(); n=(function(l,r,o){return function(e){return o==='*'?l(e)*r(e):l(e)/r(e);};})(n,r,o);} return n; }
  function I(){ var n=U(); while(pk()&&pk().k==='&'){ p++; var r=P(); n=(function(l,r){return function(e){return l(e)*r(e);};})(n,r);} return n; }
  function U(){ if(pk()&&pk().k==='-'){ p++; var u=U(); return function(e){return -u(e);}; } if(pk()&&pk().k==='+'){ p++; return U(); } return P(); }
  function P(){ var b=Aa(); if(pk()&&pk().k==='^'){ p++; var x=U(); return function(e){return Math.pow(b(e),x(e));}; } return b; }
  function Aa(){ var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){return t.v;};
    if(t.k==='v'){ if(t.v==='#') return function(){return Math.PI;}; if(t.v==='e') return function(){return Math.E;}; return function(e){return e[t.v];}; }
    if(t.k==='('){ var n=E(); if(!pk()||pk().k!==')') throw 0; p++; return n; }
    if(t.k==='f'){ var fn=F[t.v]; var ex=null;
      if(pk()&&pk().k==='^'){ p++; ex=Aa(); if(pk()&&pk().k==='&') p++; }            // sin^2(x)
      var arg; if(pk()&&pk().k==='('){ p++; arg=E(); if(!pk()||pk().k!==')') throw 0; p++; } else { arg=P(); while(pk()&&pk().k==='&'&&out[p+1]&&(out[p+1].k==='n'||(out[p+1].k==='v'&&out[p+1].v!=='e'))){ p++; var nx=P(); arg=(function(l,r){return function(e){return l(e)*r(e);};})(arg,nx); } }
      return ex? function(e){ return Math.pow(fn(arg(e)),ex(e)); } : function(e){ return fn(arg(e)); }; }
    throw 0; }
  try{ var f=E(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function calcEqual(input,answer){
  var f=calcCompile(input), g=calcCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<14;trial++){
    var env={}; 'abcdfghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=0.35+Math.random()*2.3; });
    var x=f(env), y=g(env); if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-6*Math.max(1,Math.abs(x),Math.abs(y))) return false; hits++;
  }
  return hits>=4;
}
(function(){
  var _am=answerMatches;
  answerMatches=function(input,answer,accept,expr){
    if(expr==='expanded'){ if(input===undefined||input===null||String(input).trim()==='') return false; if(/[()\[\]]/.test(String(input))) return false; return _am.call(this,input,answer,accept,true); }
    if(expr==='calc'){ if(input===undefined||input===null||String(input).trim()==='') return false;
      if(calcEqual(input,answer)) return true; return (accept||[]).some(function(a){ return calcEqual(input,a); }); }
    return _am.apply(this,arguments); };
  var _kl=kbLayoutFor;
  kbLayoutFor=function(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; if(stp.expr==='calc') return 'calc'; }catch(e){} return _kl(inp); };
  var _kp=kbPress;
  kbPress=function(k){ var m={'eˣ':'e^(','√':'√(','ln':'ln(','sin':'sin(','cos':'cos(','tan':'tan(','sec':'sec(','csc':'csc(','cot':'cot(','∛':'∛('}; if(KB.page==='calc'&&m[k]){ kbInsert(m[k]); return; } return _kp(k); };
})();


/* ================= v5: interactive plotting ================= */
var GP={};
function gpNum(s){ s=String(s).trim().replace(/[−–]/g,'-'); var m=s.match(/^(-?\d+(?:\.\d+)?)\/(\d+(?:\.\d+)?)$/); if(m) return parseFloat(m[1])/parseFloat(m[2]); var m2=s.match(/^(-?)(\d+) (\d+)\/(\d+)$/); if(m2) return (m2[1]?-1:1)*(+m2[2]+m2[3]/m2[4]); var v=parseFloat(s); return isFinite(v)&&/^-?\d*\.?\d+$/.test(s)?v:NaN; }
function gpIneq(src){ // -> {f:function(x,y), op:'<'|'<='|'>'|'>=', a,b,c} with f = lhs-rhs
  var s=String(src).replace(/≤/g,'<=').replace(/≥/g,'>=').replace(/\s+/g,'').replace(/−/g,'-');
  var m=s.match(/^(.*?)(<=|>=|<|>)(.*)$/); if(!m) return null;
  var L=calcCompile(m[1]), R=calcCompile(m[3]); if(!L||!R) return null;
  var f=function(x,y){ return L({x:x,y:y})-R({x:x,y:y}); };
  var d=f(0,0), a=f(1,0)-d, b=f(0,1)-d; return {f:f,op:m[2],a:a,b:b,c:-d,src:src};
}
function gpOpTxt(op){ return {'<':'<','<=':'≤','>':'>','>=':'≥'}[op]; }
function gpSat(I,x,y){ var v=I.f(x,y); if(I.op==='<') return v<-1e-9; if(I.op==='<=') return v<=1e-9; if(I.op==='>') return v>1e-9; return v>=-1e-9; }
function gpParseG(v){ var m=String(v||'').match(/^G:(-?[\d.]+),(-?[\d.]+);(-?[\d.]+),(-?[\d.]+);([sd]);(-?[\d.]+),(-?[\d.]+)$/); if(!m) return null;
  return {p:[[+m[1],+m[2]],[+m[3],+m[4]]], solid:m[5]==='s', sh:[+m[6],+m[7]]}; }
function gpParseN(v){ var m=String(v||'').match(/^N:([^;]+);([^;]+);([LRBO])$/); if(!m) return null;
  var vs=m[1].split(',').map(gpNum), cs=m[2].split(','); if(vs.some(isNaN)) return null; return {v:vs, c:cs.map(function(c){return c==='c';}), mode:m[3]}; }
function gpOpt(accept,pre){ var r=null; (accept||[]).forEach(function(a){ if(String(a).indexOf(pre)===0) r=String(a).slice(pre.length); }); return r; }
function gpCheckG(input,answer,accept){
  var I=gpIneq(gpOpt(accept,'INEQ:')||''), S=gpParseG(input); if(!I||!S) return false;
  var p=S.p; if(Math.abs(p[0][0]-p[1][0])<1e-9&&Math.abs(p[0][1]-p[1][1])<1e-9) return false;
  var tol=1e-7*Math.max(1,Math.abs(I.a),Math.abs(I.b),Math.abs(I.c));
  if(Math.abs(I.f(p[0][0],p[0][1]))>tol||Math.abs(I.f(p[1][0],p[1][1]))>tol) return false;
  var strict=(I.op==='<'||I.op==='>'); if(S.solid===strict) return false;
  if(Math.abs(I.f(S.sh[0],S.sh[1]))<tol) return false;
  return gpSat(I,S.sh[0],S.sh[1]);
}
function gpCheckN(input,answer){
  var S=gpParseN(input), K=gpParseN(answer); if(!S||!K) return false;
  if(S.mode!==K.mode||S.v.length!==K.v.length) return false;
  var sv=S.v.slice(), sc=S.c.slice(); if(sv.length===2&&sv[0]>sv[1]){ sv.reverse(); sc.reverse(); }
  for(var i=0;i<sv.length;i++){ if(Math.abs(sv[i]-K.v[i])>1e-6||sc[i]!==K.c[i]) return false; }
  return true;
}
function gpHumanG(v){ var S=gpParseG(v); if(!S) return v||'—'; return 'boundary through ('+S.p[0]+') and ('+S.p[1]+'), '+(S.solid?'solid':'dashed')+', shaded on the side of ('+S.sh+')'; }
function gpHumanN(v){ var S=gpParseN(v); if(!S) return v||'—'; var d=function(i){ return (S.c[i]?'closed':'open')+' dot at '+S.v[i]; };
  if(S.mode==='L') return d(0)+', shaded to the left'; if(S.mode==='R') return d(0)+', shaded to the right';
  return d(0)+' and '+d(1)+', shaded '+(S.mode==='B'?'between them':'outside them'); }
(function(){
  var _am=answerMatches;
  answerMatches=function(input,answer,accept,expr){
    if(expr==='gplot') return gpCheckG(input,answer,accept);
    if(expr==='nplot') return gpCheckN(input,answer);
    return _am.apply(this,arguments); };
  var _sat=slideAnswerText;
  slideAnswerText=function(slide,item,correctSide){
    if(slide.kind!=='blank'||!slide.flat.some(function(s){return s.expr==='gplot'||s.expr==='nplot';})) return _sat.apply(this,arguments);
    return slide.flat.map(function(step,si){ var ss=item.stepStates[si];
      return Object.keys(step.a).map(function(k){
        if(step.expr==='gplot') return correctSide ? 'the graph of '+(gpOpt(step.accept,'INEQ:')||'').replace(/<=/g,'≤').replace(/>=/g,'≥') : gpHumanG(ss.inputs[k]);
        if(step.expr==='nplot') return correctSide ? gpHumanN(step.a[k])+((gpOpt(step.accept,'INEQ:'))?' ('+gpOpt(step.accept,'INEQ:').replace(/<=/g,'≤').replace(/>=/g,'≥')+')':'') : gpHumanN(ss.inputs[k]);
        return correctSide ? step.a[k] : (ss.inputs[k] || '—'); }).join(', '); }).join('  |  ');
  };
  var _rs=renderSlide;
  renderSlide=function(){ _rs.apply(this,arguments); try{ gpEnhance(); grInitAll(); }catch(e){ console.log('gp',e); } };
})();
function gpStep(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx]; return sl.flat[parseInt(inp.dataset.step,10)]; }catch(e){ return null; } }
function gpEnhance(){
  document.querySelectorAll('.blank-input').forEach(function(inp){
    var st=gpStep(inp); if(!st||(st.expr!=='gplot'&&st.expr!=='nplot')||inp.dataset.gp) return; inp.dataset.gp='1';
    inp.classList.add('gp-hidden'); inp.setAttribute('tabindex','-1'); inp.setAttribute('aria-hidden','true');
    var box=document.createElement('div'); box.className='gp-box';
    var line=inp.closest('.step-line'); (line||inp.parentNode).appendChild(box);
    var ts=state.tabs[activeTab], item=ts.items[ts.idx], ss=item.stepStates?item.stepStates[parseInt(inp.dataset.step,10)]:null;
    var done=inp.disabled, revealed=ss&&ss.status==='revealed';
    if(st.expr==='gplot') gpBuildG(box,inp,st,done,revealed); else gpBuildN(box,inp,st,done,revealed);
    var rn=line&&line.nextElementSibling; if(rn&&rn.classList.contains('reveal-note')){ var iq=gpOpt(st.accept,'INEQ:'); rn.textContent='Correct graph'+(iq?' of '+iq.replace(/<=/g,'≤').replace(/>=/g,'≥'):'')+' shown in green.'; }
  });
}
function gpKey(inp){ return (MODE||'')+'|'+activeTab+'|'+state.tabs[activeTab].idx+'|'+inp.dataset.step; }
function gpSet(inp,v){ inp.value=v; inp.dispatchEvent(new Event('input',{bubbles:true})); }
/* ---------- coordinate-plane widget ---------- */
function gpRange(st,def){ var r=gpOpt(st.accept,'R:'); if(!r) return def; var a=r.split(',').map(Number); return a.length>=2&&a.every(isFinite)?a:def; }
function gpClipHalf(poly,a,b,c,keepPos){ // keep points with s*(a x + b y - c) >= 0
  var s=keepPos?1:-1, out=[]; for(var i=0;i<poly.length;i++){ var P=poly[i], Q=poly[(i+1)%poly.length];
    var fp=s*(a*P[0]+b*P[1]-c), fq=s*(a*Q[0]+b*Q[1]-c);
    if(fp>=0) out.push(P); if((fp>=0)!==(fq>=0)){ var t=fp/(fp-fq); out.push([P[0]+t*(Q[0]-P[0]),P[1]+t*(Q[1]-P[1])]); } } return out; }
function gpBuildG(box,inp,st,done,revealed){
  var R=gpRange(st,[-8,8,-8,8]), x0=R[0],x1=R[1],y0=R[2],y1=R[3], W=320, H=Math.round(320*(y1-y0)/(x1-x0)), pad=0;
  var X=function(x){ return (x-x0)/(x1-x0)*W; }, Y=function(y){ return H-(y-y0)/(y1-y0)*H; };
  var S=gpParseG(inp.value)||{p:[],solid:true,sh:null}; if(!gpParseG(inp.value)){ if(GP[gpKey(inp)]) S=JSON.parse(JSON.stringify(GP[gpKey(inp)])); }
  var I=gpIneq(gpOpt(st.accept,'INEQ:')||'');
  box.innerHTML='<div class="gp-help">'+(done?'Your graph':'① Tap two grid points on the boundary line · ② choose Solid or Dashed · ③ tap the side to shade')+'</div>'+
    '<svg class="gp-svg" viewBox="-14 -14 '+(W+28)+' '+(H+28)+'" style="max-width:100%;touch-action:manipulation"></svg>'+
    (done?'':'<div class="gp-tools"><button type="button" data-k="s" class="gp-b">━ Solid (≤, ≥)</button><button type="button" data-k="d" class="gp-b">┅ Dashed (&lt;, &gt;)</button><button type="button" data-k="u" class="gp-b">↶ Undo</button><button type="button" data-k="c" class="gp-b">Clear</button></div>')+
    '<div class="gp-stat"></div>';
  var svg=box.querySelector('svg'), stat=box.querySelector('.gp-stat');
  function lineSeg(a,b,c){ // endpoints of a x + b y = c inside box
    var pts=[], add=function(x,y){ if(x>=x0-1e-9&&x<=x1+1e-9&&y>=y0-1e-9&&y<=y1+1e-9&&!pts.some(function(p){return Math.abs(p[0]-x)<1e-9&&Math.abs(p[1]-y)<1e-9;})) pts.push([x,y]); };
    if(Math.abs(b)>1e-12){ add(x0,(c-a*x0)/b); add(x1,(c-a*x1)/b); } if(Math.abs(a)>1e-12){ add((c-b*y0)/a,y0); add((c-b*y1)/a,y1); } return pts.slice(0,2); }
  function region(a,b,c,keepPos,fill){ var poly=gpClipHalf([[x0,y0],[x1,y0],[x1,y1],[x0,y1]],a,b,c,keepPos); if(poly.length<3) return '';
    return '<polygon points="'+poly.map(function(p){return X(p[0]).toFixed(1)+','+Y(p[1]).toFixed(1);}).join(' ')+'" style="fill:'+fill+';opacity:.28"/>'; }
  function draw(){
    var h='', i;
    for(i=Math.ceil(x0);i<=x1;i++) h+='<line x1="'+X(i)+'" y1="0" x2="'+X(i)+'" y2="'+H+'" style="stroke:var(--rule);stroke-width:'+(i===0?0:1)+'"/>';
    for(i=Math.ceil(y0);i<=y1;i++) h+='<line x1="0" y1="'+Y(i)+'" x2="'+W+'" y2="'+Y(i)+'" style="stroke:var(--rule);stroke-width:'+(i===0?0:1)+'"/>';
    if(x0<0&&x1>0) h+='<line x1="'+X(0)+'" y1="0" x2="'+X(0)+'" y2="'+H+'" style="stroke:var(--ink);stroke-width:1.6"/>';
    if(y0<0&&y1>0) h+='<line x1="0" y1="'+Y(0)+'" x2="'+W+'" y2="'+Y(0)+'" style="stroke:var(--ink);stroke-width:1.6"/>';
    var step=(x1-x0)>12?2:1; for(i=Math.ceil(x0);i<=x1;i++) if(i!==0&&i%step===0) h+='<text x="'+X(i)+'" y="'+(Y(0)+13)+'" text-anchor="middle" style="font:10px sans-serif;fill:var(--ink-soft)">'+String(i).replace('-','−')+'</text>';
    for(i=Math.ceil(y0);i<=y1;i++) if(i!==0&&i%step===0) h+='<text x="'+(X(0)-5)+'" y="'+(Y(i)+3.5)+'" text-anchor="end" style="font:10px sans-serif;fill:var(--ink-soft)">'+String(i).replace('-','−')+'</text>';
    h+='<text x="'+(W+4)+'" y="'+(Y(0)-4)+'" style="font:italic 12px serif;fill:var(--ink)">x</text><text x="'+(X(0)+5)+'" y="-3" style="font:italic 12px serif;fill:var(--ink)">y</text>';
    if(S.p.length===2){ var P=S.p, a=P[1][1]-P[0][1], b=P[0][0]-P[1][0], c=a*P[0][0]+b*P[0][1];
      if(Math.abs(a)>1e-12||Math.abs(b)>1e-12){
        if(S.sh){ var keep=(a*S.sh[0]+b*S.sh[1]-c)>0; h+=region(a,b,c,keep,'var(--accent-text)'); }
        var sg2=lineSeg(a,b,c); if(sg2.length===2) h+='<line x1="'+X(sg2[0][0])+'" y1="'+Y(sg2[0][1])+'" x2="'+X(sg2[1][0])+'" y2="'+Y(sg2[1][1])+'" style="stroke:var(--accent-text);stroke-width:2.6;'+(S.solid?'':'stroke-dasharray:8 6')+'"/>'; } }
    if((done||revealed)&&revealed&&I){ // correct answer in green
      var keepPos=I.op==='>'||I.op==='>='; h+=region(I.a,I.b,I.c,keepPos,'var(--success)'); var sg=lineSeg(I.a,I.b,I.c);
      if(sg.length===2) h+='<line x1="'+X(sg[0][0])+'" y1="'+Y(sg[0][1])+'" x2="'+X(sg[1][0])+'" y2="'+Y(sg[1][1])+'" style="stroke:var(--success);stroke-width:3;'+((I.op==='<'||I.op==='>')?'stroke-dasharray:8 6':'')+'"/>'; }
    S.p.forEach(function(p){ h+='<circle cx="'+X(p[0])+'" cy="'+Y(p[1])+'" r="5.5" style="fill:var(--danger)"/>'; });
    if(S.sh) h+='<text x="'+X(S.sh[0])+'" y="'+(Y(S.sh[1])+5)+'" text-anchor="middle" style="font:700 15px sans-serif;fill:var(--accent-text)">✚</text>';
    h+='<rect x="0" y="0" width="'+W+'" height="'+H+'" style="fill:transparent;stroke:var(--ink-soft);stroke-width:1" class="gp-hit"/>';
    svg.innerHTML=h;
    var msg = S.p.length<2 ? 'Point '+(S.p.length+1)+' of 2: tap a grid point on the boundary line.' : (!S.sh ? 'Line: '+(S.solid?'solid':'dashed')+'. Now tap a point on the side to shade.' : 'Boundary through ('+S.p[0]+') and ('+S.p[1]+'), '+(S.solid?'solid':'dashed')+', shaded side marked ✚. Press Check.');
    if(!done) stat.textContent=msg; else stat.textContent=S.p.length===2&&S.sh?gpHumanG(inp.value):'';
  }
  function save(){ GP[gpKey(inp)]=JSON.parse(JSON.stringify(S)); if(S.p.length===2&&S.sh) gpSet(inp,'G:'+S.p[0]+';'+S.p[1]+';'+(S.solid?'s':'d')+';'+S.sh); else gpSet(inp,''); }
  if(!done){
    svg.addEventListener('click',function(e){ var r=svg.getBoundingClientRect(), vb=svg.viewBox.baseVal, sx=(e.clientX-r.left)/r.width*vb.width+vb.x, sy=(e.clientY-r.top)/r.height*vb.height+vb.y;
      var x=x0+sx/W*(x1-x0), y=y0+(H-sy)/H*(y1-y0); if(x<x0-0.3||x>x1+0.3||y<y0-0.3||y>y1+0.3) return;
      if(S.p.length<2){ var gx=Math.round(x), gy=Math.round(y); if(S.p.length===1&&S.p[0][0]===gx&&S.p[0][1]===gy) return; S.p.push([gx,gy]); S.sh=null; }
      else { S.sh=[Math.round(x*2)/2,Math.round(y*2)/2]; var a=S.p[1][1]-S.p[0][1], b=S.p[0][0]-S.p[1][0], c=a*S.p[0][0]+b*S.p[0][1]; if(Math.abs(a*S.sh[0]+b*S.sh[1]-c)<1e-9){ S.sh=[Math.round(x*4)/4,Math.round(y*4)/4]; if(Math.abs(a*S.sh[0]+b*S.sh[1]-c)<1e-9) S.sh=null; } }
      save(); draw(); });
    box.querySelectorAll('.gp-b').forEach(function(b){ b.addEventListener('click',function(){ var k=b.dataset.k;
      if(k==='s') S.solid=true; else if(k==='d') S.solid=false; else if(k==='c'){ S={p:[],solid:S.solid,sh:null}; } else if(k==='u'){ if(S.sh) S.sh=null; else S.p.pop(); }
      box.querySelectorAll('.gp-b[data-k=s],.gp-b[data-k=d]').forEach(function(x){ x.classList.toggle('on',(x.dataset.k==='s')===S.solid); });
      save(); draw(); }); });
    box.querySelectorAll('.gp-b[data-k=s],.gp-b[data-k=d]').forEach(function(x){ x.classList.toggle('on',(x.dataset.k==='s')===S.solid); });
  }
  draw();
}
/* ---------- number-line widget ---------- */
function gpBuildN(box,inp,st,done,revealed){
  var R=gpRange(st,[-8,8]), lo=R[0], hi=R[1], W=320, H=70, X=function(v){ return 14+(v-lo)/(hi-lo)*(W-28); };
  var S=gpParseN(inp.value)||{v:[],c:[],mode:''}; var draft={v:['',''],c:['c','c'],n:1,mode:''};
  if(gpParseN(inp.value)){ var T=gpParseN(inp.value); draft.n=T.v.length; draft.v=[String(T.v[0]),T.v[1]!==undefined?String(T.v[1]):'']; draft.c=[T.c[0]?'c':'o',T.c[1]?'c':'o']; draft.mode=T.mode; }
  else { if(GP[gpKey(inp)]) draft=JSON.parse(JSON.stringify(GP[gpKey(inp)])); }
  var K=gpParseN(st.a[Object.keys(st.a)[0]]);
  box.innerHTML='<div class="gp-help">'+(done?'Your number line':'Choose 1 or 2 endpoints, type each value, pick open ○ / closed ● dots and the shading')+'</div>'+
    '<svg class="gp-svg" viewBox="0 0 '+W+' '+H+'" style="max-width:100%"></svg>'+
    (done?'':'<div class="gp-tools gp-n">'+
      '<span class="gp-lab">Endpoints:</span><button type="button" class="gp-b" data-n="1">1</button><button type="button" class="gp-b" data-n="2">2</button><br>'+
      '<span class="gp-lab">A =</span><input class="gp-in" data-i="0" inputmode="decimal" placeholder="value"><button type="button" class="gp-b" data-ci="0" data-c="o">○ open</button><button type="button" class="gp-b" data-ci="0" data-c="c">● closed</button><br>'+
      '<span class="gp-row2"><span class="gp-lab">B =</span><input class="gp-in" data-i="1" inputmode="decimal" placeholder="value"><button type="button" class="gp-b" data-ci="1" data-c="o">○ open</button><button type="button" class="gp-b" data-ci="1" data-c="c">● closed</button><br></span>'+
      '<span class="gp-lab">Shade:</span><span class="gp-sh1"><button type="button" class="gp-b" data-m="L">← left</button><button type="button" class="gp-b" data-m="R">right →</button></span><span class="gp-sh2"><button type="button" class="gp-b" data-m="B">between</button><button type="button" class="gp-b" data-m="O">outside</button></span></div>')+
    '<div class="gp-stat"></div>';
  var svg=box.querySelector('svg'), stat=box.querySelector('.gp-stat');
  function seg(a,b,col,y){ return '<line x1="'+X(a)+'" y1="'+y+'" x2="'+X(b)+'" y2="'+y+'" style="stroke:'+col+';stroke-width:5;stroke-linecap:round;opacity:.85"/>'; }
  function arrowTo(v,dir,col,y){ var e=dir<0?lo:hi; return seg(v,e,col,y)+'<path d="M'+X(e)+' '+y+' l'+(dir<0?8:-8)+' -6 v12 z" style="fill:'+col+'"/>'; }
  function dot(v,closed,col,y){ return '<circle cx="'+X(v)+'" cy="'+y+'" r="6" style="fill:'+(closed?col:'var(--card)')+';stroke:'+col+';stroke-width:2.4"/>'; }
  function paint(T,col,y){ if(!T) return ''; var h='', v=T.v.slice(), c=T.c.slice(); if(v.length===2&&v[0]>v[1]){ v.reverse(); c.reverse(); }
    if(T.mode==='L') h+=arrowTo(v[0],-1,col,y); else if(T.mode==='R') h+=arrowTo(v[0],1,col,y); else if(T.mode==='B') h+=seg(v[0],v[1],col,y); else if(T.mode==='O') h+=arrowTo(v[0],-1,col,y)+arrowTo(v[1],1,col,y);
    v.forEach(function(x,i){ h+=dot(x,c[i],col,y); }); return h; }
  function cur(){ var vs=draft.v.slice(0,draft.n).map(gpNum); if(vs.some(isNaN)||!draft.mode) return null; if(draft.n===1&&'LR'.indexOf(draft.mode)<0) return null; if(draft.n===2&&'BO'.indexOf(draft.mode)<0) return null;
    return {v:vs,c:draft.c.slice(0,draft.n).map(function(x){return x==='c';}),mode:draft.mode}; }
  function draw(){
    var h='<line x1="6" y1="40" x2="'+(W-6)+'" y2="40" style="stroke:var(--ink);stroke-width:1.6"/><path d="M'+(W-6)+' 40 l-8 -5 v10z M6 40 l8 -5 v10z" style="fill:var(--ink)"/>';
    var step=(hi-lo)>16?2:1; for(var i=Math.ceil(lo);i<=hi;i++){ h+='<line x1="'+X(i)+'" y1="35" x2="'+X(i)+'" y2="45" style="stroke:var(--ink);stroke-width:1"/>'; if(i%step===0) h+='<text x="'+X(i)+'" y="60" text-anchor="middle" style="font:11px sans-serif;fill:var(--ink-soft)">'+String(i).replace('-','−')+'</text>'; }
    if(revealed&&K) h+=paint(K,'var(--success)',22);
    var T=done?gpParseN(inp.value):cur(); h+=paint(T,'var(--accent-text)',40); svg.innerHTML=h;
    if(!done){ box.querySelectorAll('.gp-b[data-n]').forEach(function(b){ b.classList.toggle('on',+b.dataset.n===draft.n); });
      box.querySelector('.gp-row2').style.display=draft.n===2?'':'none'; box.querySelector('.gp-sh1').style.display=draft.n===1?'':'none'; box.querySelector('.gp-sh2').style.display=draft.n===2?'':'none';
      box.querySelectorAll('.gp-b[data-ci]').forEach(function(b){ b.classList.toggle('on',draft.c[+b.dataset.ci]===b.dataset.c); });
      box.querySelectorAll('.gp-b[data-m]').forEach(function(b){ b.classList.toggle('on',draft.mode===b.dataset.m); });
      stat.textContent = T ? gpHumanN('N:'+T.v.join(',')+';'+T.c.map(function(x){return x?'c':'o';}).join(',')+';'+T.mode)+'. Press Check.' : 'Fill in the endpoint value(s) and choose the shading.'; }
    else stat.textContent = T?gpHumanN(inp.value):'';
  }
  function save(){ GP[gpKey(inp)]=JSON.parse(JSON.stringify(draft)); var T=cur(); gpSet(inp, T? 'N:'+draft.v.slice(0,draft.n).map(function(s){return String(s).trim().replace(/[−–]/g,'-');}).join(',')+';'+draft.c.slice(0,draft.n).join(',')+';'+draft.mode : ''); }
  if(!done){
    box.querySelectorAll('.gp-in').forEach(function(f){ f.value=draft.v[+f.dataset.i]||''; f.addEventListener('input',function(){ draft.v[+f.dataset.i]=f.value; save(); draw(); }); });
    box.querySelectorAll('.gp-b').forEach(function(b){ b.addEventListener('click',function(){
      if(b.dataset.n){ draft.n=+b.dataset.n; draft.mode=''; } if(b.dataset.ci) draft.c[+b.dataset.ci]=b.dataset.c; if(b.dataset.m) draft.mode=b.dataset.m; save(); draw(); }); });
  }
  draw();
}
/* ---------- inequality grapher (explore tool) ---------- */
function grInitAll(root){ (root||document).querySelectorAll('.ineq-grapher:not([data-ok])').forEach(grInit); }
function grInit(el){
  el.dataset.ok='1'; var init=el.dataset.init||'y >= 2x - 1; x + y < 6';
  el.innerHTML='<div class="gr-head">📈 Inequality grapher</div><div class="gr-row"><input class="gr-in" value="'+esc(init)+'" aria-label="inequalities"><button type="button" class="gp-b gr-go">Plot</button></div>'+
    '<div class="gr-hint">Type one or more inequalities in x and y, separated by ; (e.g. 2x + 3y ≤ 6; x ≥ 0; y ≥ 0). The region that satisfies all of them is shaded; solid lines for ≤ ≥, dashed for &lt; &gt;.</div>'+
    '<canvas class="gr-cv" width="640" height="640"></canvas><div class="gr-msg"></div>';
  var cv=el.querySelector('canvas'), inp=el.querySelector('.gr-in'), msg=el.querySelector('.gr-msg');
  function plot(){
    var ctx=cv.getContext('2d'), W=cv.width, H=cv.height, x0=-10,x1=10,y0=-10,y1=10, cs=getComputedStyle(document.documentElement);
    var ink=cs.getPropertyValue('--ink').trim()||'#222', rule=cs.getPropertyValue('--rule').trim()||'#ddd', acc=cs.getPropertyValue('--accent-text').trim()||'#1F3B6B', card=cs.getPropertyValue('--card').trim()||'#fff';
    var parts=inp.value.split(/[;,]/).map(function(s){return s.trim();}).filter(Boolean), Is=[];
    for(var i=0;i<parts.length;i++){ var I=gpIneq(parts[i]); if(!I){ msg.textContent='Could not read “'+parts[i]+'”. Use x, y, numbers, + − × /, ^ and one of < > ≤ ≥ (or <= >=).'; return; } Is.push(I); }
    msg.textContent=Is.length?'Shaded: points satisfying '+parts.map(function(p){return p.replace(/<=/g,'≤').replace(/>=/g,'≥');}).join(' and ')+'.':'';
    var X=function(x){return (x-x0)/(x1-x0)*W;}, Y=function(y){return H-(y-y0)/(y1-y0)*H;};
    ctx.fillStyle=card; ctx.fillRect(0,0,W,H);
    var cell=4; ctx.fillStyle=acc; ctx.globalAlpha=0.28;
    for(var px=0;px<W;px+=cell) for(var py=0;py<H;py+=cell){ var x=x0+(px+cell/2)/W*(x1-x0), y=y1-(py+cell/2)/H*(y1-y0); if(Is.length&&Is.every(function(I){return gpSat(I,x,y);})) ctx.fillRect(px,py,cell,cell); }
    ctx.globalAlpha=1; ctx.strokeStyle=rule; ctx.lineWidth=1;
    for(var g=x0;g<=x1;g++){ ctx.beginPath(); ctx.moveTo(X(g),0); ctx.lineTo(X(g),H); ctx.stroke(); ctx.beginPath(); ctx.moveTo(0,Y(g)); ctx.lineTo(W,Y(g)); ctx.stroke(); }
    ctx.strokeStyle=ink; ctx.lineWidth=2; ctx.beginPath(); ctx.moveTo(X(0),0); ctx.lineTo(X(0),H); ctx.moveTo(0,Y(0)); ctx.lineTo(W,Y(0)); ctx.stroke();
    ctx.fillStyle=ink; ctx.font='20px sans-serif'; ctx.textAlign='center'; for(g=x0+2;g<=x1-1;g+=2){ if(g) { ctx.fillText(String(g),X(g),Y(0)+22); ctx.fillText(String(g),X(0)-16,Y(g)+7); } }
    Is.forEach(function(I){ // boundary f = 0 by sampling sign changes
      var strict=(I.op==='<'||I.op==='>'), n=320; ctx.fillStyle=acc;
      for(var i=0;i<n;i++) for(var j=0;j<n;j++){ var xa=x0+i/n*(x1-x0), ya=y0+j/n*(y1-y0), d=(x1-x0)/n;
        var f00=I.f(xa,ya), f10=I.f(xa+d,ya), f01=I.f(xa,ya+d);
        if((f00>0)!==(f10>0)||(f00>0)!==(f01>0)||Math.abs(f00)<1e-12){ if(strict&&((i+j)%14>6)) continue; ctx.fillRect(X(xa)-1.6,Y(ya)-1.6,3.2,3.2); } } });
  }
  el.querySelector('.gr-go').addEventListener('click',plot); inp.addEventListener('keydown',function(e){ if(e.key==='Enter') plot(); });
  plot();
}

renderLogin();
})();
</script>
</body>
</html>
