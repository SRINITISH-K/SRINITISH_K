<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>SRINITISH_K :: DATA_ENGINEER</title>
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,100..800;1,100..800&family=Bebas+Neue&family=Oxanium:wght@200..800&display=swap" rel="stylesheet" />
<style>
  :root {
    --bg:        #080c0a;
    --bg2:       #0d1210;
    --bg3:       #111a15;
    --surface:   #0f1a12;
    --border:    #1a2e1f;
    --green:     #00ff6a;
    --green-dim: #00b84a;
    --green-muted:#004d20;
    --cyan:      #00e5ff;
    --cyan-dim:  #0099bb;
    --amber:     #ffb300;
    --amber-dim: #996a00;
    --red:       #ff3b3b;
    --text:      #c8e6c9;
    --text-dim:  #5a7a60;
    --text-faint:#2a3f2d;
    --mono:      'JetBrains Mono', monospace;
    --display:   'Bebas Neue', sans-serif;
    --ui:        'Oxanium', sans-serif;
    --scanline: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,0,0,0.15) 2px, rgba(0,0,0,0.15) 4px);
  }
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--mono);
    font-size: 14px;
    line-height: 1.6;
    overflow-x: hidden;
    cursor: crosshair;
  }

  ::-webkit-scrollbar { width: 6px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--green-muted); border-radius: 3px; }
  ::-webkit-scrollbar-thumb:hover { background: var(--green); }

  /* ── SCANLINE OVERLAY ── */
  body::after {
    content: '';
    position: fixed;
    inset: 0;
    background: var(--scanline);
    pointer-events: none;
    z-index: 9999;
    opacity: 0.4;
  }

  /* ── BIOS SCREEN ── */
  #bios {
    position: fixed;
    inset: 0;
    background: #000;
    z-index: 10000;
    font-family: var(--mono);
    font-size: 13px;
    padding: 32px 40px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    gap: 2px;
  }
  .bios-line { color: #aaa; white-space: pre; opacity: 0; }
  .bios-line.green { color: var(--green); }
  .bios-line.cyan  { color: var(--cyan); }
  .bios-line.amber { color: var(--amber); }
  .bios-line.white { color: #fff; }
  .bios-bar {
    display: inline-block;
    height: 10px;
    background: var(--green);
    width: 0%;
    transition: width 1.2s linear;
    vertical-align: middle;
    box-shadow: 0 0 8px var(--green);
  }
  #bios-progress-line { color: var(--green); font-family: var(--mono); }

  /* ── NAVBAR ── */
  #navbar {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 1000;
    background: rgba(8,12,10,0.95);
    border-bottom: 1px solid var(--border);
    backdrop-filter: blur(8px);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 28px;
    height: 48px;
    font-family: var(--mono);
  }
  .nav-logo {
    font-family: var(--display);
    font-size: 22px;
    color: var(--green);
    letter-spacing: 3px;
    text-shadow: 0 0 12px var(--green);
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .nav-logo-tag { font-family: var(--mono); font-size: 10px; color: var(--text-dim); letter-spacing: 1px; }
  .nav-links {
    display: flex;
    gap: 4px;
    list-style: none;
  }
  .nav-links a {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text-dim);
    text-decoration: none;
    padding: 4px 10px;
    border: 1px solid transparent;
    transition: all 0.2s;
    letter-spacing: 1px;
  }
  .nav-links a:hover {
    color: var(--green);
    border-color: var(--green-muted);
    background: rgba(0,255,106,0.05);
    text-shadow: 0 0 8px var(--green);
  }
  .nav-clock {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--cyan);
    letter-spacing: 2px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 1px;
  }
  .nav-clock-date { font-size: 9px; color: var(--text-dim); }
  .nav-status {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 10px;
    color: var(--green-dim);
  }
  .status-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--green);
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0%,100% { opacity: 1; box-shadow: 0 0 4px var(--green); }
    50%      { opacity: 0.4; box-shadow: none; }
  }

  /* ── HERO ── */
  #hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 80px 40px 60px;
    position: relative;
    overflow: hidden;
  }
  .hero-grid-bg {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,255,106,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,255,106,0.03) 1px, transparent 1px);
    background-size: 40px 40px;
  }
  .hero-glow {
    position: absolute;
    top: 20%;
    left: 50%;
    transform: translateX(-50%);
    width: 600px;
    height: 300px;
    background: radial-gradient(ellipse, rgba(0,255,106,0.06) 0%, transparent 70%);
    pointer-events: none;
  }
  .hero-inner {
    position: relative;
    max-width: 900px;
    width: 100%;
  }
  .hero-eyebrow {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--cyan);
    letter-spacing: 4px;
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .hero-eyebrow::before {
    content: '';
    display: block;
    width: 32px;
    height: 1px;
    background: var(--cyan);
    box-shadow: 0 0 6px var(--cyan);
  }
  .hero-name {
    font-family: var(--display);
    font-size: clamp(60px, 10vw, 120px);
    line-height: 0.9;
    letter-spacing: 6px;
    color: var(--green);
    text-shadow: 0 0 40px rgba(0,255,106,0.4);
    position: relative;
    margin-bottom: 4px;
  }
  .hero-name-glitch {
    position: relative;
    display: inline-block;
    animation: glitch-main 5s infinite;
  }
  .hero-name-glitch::before,
  .hero-name-glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0; left: 0;
    width: 100%;
  }
  .hero-name-glitch::before {
    color: var(--cyan);
    animation: glitch-a 5s infinite;
    clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    opacity: 0;
  }
  .hero-name-glitch::after {
    color: var(--amber);
    animation: glitch-b 5s infinite;
    clip-path: polygon(0 55%, 100% 55%, 100% 100%, 0 100%);
    opacity: 0;
  }
  @keyframes glitch-main {
    0%,89%,100% { transform: none; }
    90% { transform: skewX(-1deg); }
    91% { transform: none; }
    92% { transform: skewX(1deg) skewY(0.3deg); }
    93% { transform: none; }
  }
  @keyframes glitch-a {
    0%,89%,100% { opacity:0; transform:none; }
    90% { opacity:0.7; transform:translate(-3px,0); }
    91% { opacity:0; }
    92% { opacity:0.5; transform:translate(3px,0); }
    93% { opacity:0; }
  }
  @keyframes glitch-b {
    0%,89%,100% { opacity:0; transform:none; }
    90% { opacity:0.6; transform:translate(3px,0); }
    91% { opacity:0; }
    92% { opacity:0.4; transform:translate(-3px,0); }
    93% { opacity:0; }
  }
  .hero-title-line {
    font-family: var(--ui);
    font-size: clamp(14px,2.5vw,22px);
    font-weight: 300;
    color: var(--text-dim);
    letter-spacing: 6px;
    text-transform: uppercase;
    margin-bottom: 32px;
  }
  .hero-title-accent { color: var(--amber); font-weight: 600; }

  .hero-terminal {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    max-width: 680px;
    box-shadow: 0 0 30px rgba(0,0,0,0.5), inset 0 0 30px rgba(0,255,106,0.02);
  }
  .term-titlebar {
    background: var(--bg3);
    padding: 8px 14px;
    display: flex;
    align-items: center;
    gap: 8px;
    border-bottom: 1px solid var(--border);
  }
  .term-dot { width: 10px; height: 10px; border-radius: 50%; }
  .term-dot.r { background: #ff5f56; }
  .term-dot.y { background: #ffbd2e; }
  .term-dot.g { background: #27c93f; }
  .term-title {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--text-dim);
    margin-left: 8px;
    letter-spacing: 1px;
  }
  .term-body {
    padding: 20px 24px;
    min-height: 160px;
    font-family: var(--mono);
    font-size: 13px;
    line-height: 1.8;
  }
  .term-prompt { color: var(--green-dim); }
  .term-cmd { color: var(--green); }
  .term-out { color: var(--text); }
  .term-key { color: var(--cyan); }
  .term-val { color: var(--amber); }
  .term-cursor {
    display: inline-block;
    width: 8px; height: 15px;
    background: var(--green);
    vertical-align: middle;
    animation: blink 1s step-end infinite;
  }
  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

  .hero-badges {
    margin-top: 28px;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
  }
  .badge {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 1px;
    padding: 4px 12px;
    border: 1px solid;
    border-radius: 2px;
    text-transform: uppercase;
  }
  .badge-g { color: var(--green); border-color: var(--green-muted); background: rgba(0,255,106,0.04); }
  .badge-c { color: var(--cyan); border-color: var(--cyan-dim); background: rgba(0,229,255,0.04); }
  .badge-a { color: var(--amber); border-color: var(--amber-dim); background: rgba(255,179,0,0.04); }

  /* ── SECTIONS ── */
  section {
    padding: 80px 40px;
    max-width: 1100px;
    margin: 0 auto;
    position: relative;
  }
  .section-header {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 52px;
  }
  .section-num {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--green);
    letter-spacing: 2px;
  }
  .section-title {
    font-family: var(--display);
    font-size: 38px;
    letter-spacing: 4px;
    color: var(--text);
  }
  .section-line {
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, var(--border), transparent);
  }

  /* ── SKILLS GRID ── */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 16px;
  }
  .skill-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    padding: 20px;
    border-radius: 3px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.3s, transform 0.2s;
  }
  .skill-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0;
    width: 3px; height: 100%;
    background: var(--accent-color, var(--green));
    box-shadow: 0 0 10px var(--accent-color, var(--green));
  }
  .skill-card:hover {
    border-color: var(--accent-color, var(--green));
    transform: translateX(3px);
  }
  .skill-cat {
    font-family: var(--ui);
    font-size: 10px;
    font-weight: 700;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--accent-color, var(--green));
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .skill-cat::after { content: ''; flex:1; height: 1px; background: var(--text-faint); }
  .skill-tags { display: flex; flex-wrap: wrap; gap: 6px; }
  .skill-tag {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--text-dim);
    background: rgba(255,255,255,0.03);
    border: 1px solid var(--text-faint);
    padding: 3px 8px;
    border-radius: 2px;
    transition: all 0.2s;
  }
  .skill-tag:hover {
    color: var(--text);
    border-color: var(--text-dim);
    background: rgba(255,255,255,0.06);
  }

  /* ── TIMELINE ── */
  .timeline { position: relative; padding-left: 32px; }
  .timeline::before {
    content: '';
    position: absolute;
    left: 7px; top: 0; bottom: 0;
    width: 1px;
    background: linear-gradient(to bottom, var(--green), var(--cyan-dim), var(--border));
  }
  .tl-item {
    position: relative;
    margin-bottom: 48px;
  }
  .tl-item::before {
    content: '';
    position: absolute;
    left: -29px; top: 6px;
    width: 12px; height: 12px;
    border: 2px solid var(--green);
    border-radius: 50%;
    background: var(--bg);
    box-shadow: 0 0 10px var(--green);
  }
  .tl-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 6px;
  }
  .tl-role {
    font-family: var(--ui);
    font-size: 16px;
    font-weight: 700;
    color: var(--text);
    letter-spacing: 1px;
  }
  .tl-company {
    font-family: var(--mono);
    font-size: 12px;
    color: var(--green);
  }
  .tl-date {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--amber);
    background: rgba(255,179,0,0.07);
    border: 1px solid var(--amber-dim);
    padding: 2px 10px;
    border-radius: 2px;
    white-space: nowrap;
  }
  .tl-sub {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--cyan);
    margin-bottom: 12px;
    letter-spacing: 1px;
  }
  .tl-bullets { list-style: none; }
  .tl-bullets li {
    font-family: var(--mono);
    font-size: 12px;
    color: var(--text-dim);
    padding: 3px 0 3px 18px;
    position: relative;
    line-height: 1.6;
  }
  .tl-bullets li::before {
    content: '▸';
    position: absolute;
    left: 0;
    color: var(--green-dim);
  }
  .tl-bullets li strong { color: var(--green); font-weight: 600; }

  /* ── PROJECTS GRID ── */
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 20px;
  }
  .proj-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 3px;
    overflow: hidden;
    position: relative;
    transition: border-color 0.3s, box-shadow 0.3s;
  }
  .proj-card:hover {
    border-color: var(--green-dim);
    box-shadow: 0 0 20px rgba(0,255,106,0.07), 0 0 40px rgba(0,0,0,0.3);
  }
  .proj-top {
    background: var(--bg3);
    border-bottom: 1px solid var(--border);
    padding: 14px 18px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .proj-icon {
    font-size: 18px;
    line-height: 1;
  }
  .proj-name {
    font-family: var(--ui);
    font-size: 14px;
    font-weight: 700;
    color: var(--text);
    letter-spacing: 1px;
  }
  .proj-tag {
    margin-left: auto;
    font-family: var(--mono);
    font-size: 9px;
    color: var(--cyan);
    border: 1px solid var(--cyan-dim);
    padding: 2px 8px;
    border-radius: 2px;
    letter-spacing: 1px;
  }
  .proj-body { padding: 18px; }
  .proj-desc {
    font-family: var(--mono);
    font-size: 12px;
    color: var(--text-dim);
    line-height: 1.7;
    margin-bottom: 14px;
  }
  .proj-stack { display: flex; flex-wrap: wrap; gap: 6px; }
  .proj-pill {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--amber);
    background: rgba(255,179,0,0.06);
    border: 1px solid var(--amber-dim);
    padding: 2px 8px;
    border-radius: 2px;
  }

  /* ── CERTS ── */
  .certs-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 14px;
  }
  .cert-card {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 3px;
    padding: 16px 18px;
    display: flex;
    align-items: flex-start;
    gap: 14px;
    transition: border-color 0.2s, transform 0.2s;
  }
  .cert-card:hover { border-color: var(--amber-dim); transform: translateY(-2px); }
  .cert-icon {
    font-size: 22px;
    line-height: 1;
    flex-shrink: 0;
  }
  .cert-name {
    font-family: var(--ui);
    font-size: 12px;
    font-weight: 600;
    color: var(--text);
    line-height: 1.4;
  }
  .cert-issuer {
    font-family: var(--mono);
    font-size: 10px;
    color: var(--amber-dim);
    margin-top: 4px;
    letter-spacing: 1px;
  }

  /* ── CONTACT / TERMINAL ── */
  #contact-wrap {
    max-width: 800px;
    margin: 0 auto;
  }
  .contact-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-bottom: 30px;
  }
  .contact-item {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 3px;
    padding: 16px 20px;
    display: flex;
    align-items: center;
    gap: 14px;
  }
  .contact-item-icon { font-size: 20px; }
  .contact-label {
    font-family: var(--mono);
    font-size: 9px;
    color: var(--text-dim);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 4px;
  }
  .contact-val {
    font-family: var(--mono);
    font-size: 13px;
    color: var(--green);
  }
  .contact-val a { color: var(--cyan); text-decoration: none; }
  .contact-val a:hover { text-decoration: underline; }

  /* ── INTERACTIVE TERMINAL ── */
  #iterm {
    background: var(--bg2);
    border: 1px solid var(--border);
    border-radius: 3px;
    overflow: hidden;
  }
  #iterm-output {
    padding: 20px 22px;
    min-height: 200px;
    max-height: 320px;
    overflow-y: auto;
    font-family: var(--mono);
    font-size: 12px;
    line-height: 1.8;
  }
  .iterm-row { display: flex; gap: 0; }
  .iterm-p { color: var(--green-dim); flex-shrink: 0; }
  .iterm-c { color: var(--text); }
  .iterm-resp { color: var(--cyan); margin-left: 2px; }
  .iterm-err { color: var(--red); }
  .iterm-info { color: var(--amber); }
  #iterm-inputline {
    border-top: 1px solid var(--border);
    background: var(--bg3);
    display: flex;
    align-items: center;
    padding: 10px 22px;
    gap: 10px;
  }
  #iterm-inputline span { color: var(--green-dim); font-family: var(--mono); font-size: 12px; flex-shrink:0; }
  #iterm-input {
    flex: 1;
    background: transparent;
    border: none;
    outline: none;
    color: var(--green);
    font-family: var(--mono);
    font-size: 12px;
    caret-color: var(--green);
  }

  /* ── FOOTER ── */
  #footer {
    border-top: 1px solid var(--border);
    padding: 24px 40px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-family: var(--mono);
    font-size: 10px;
    color: var(--text-dim);
  }
  .footer-sig { color: var(--green-dim); letter-spacing: 1px; }

  /* ── SCROLL REVEAL ── */
  .reveal {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease, transform 0.6s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: none;
  }

  /* ── RESPONSIVE ── */
  @media (max-width: 768px) {
    section { padding: 60px 20px; }
    #hero { padding: 80px 20px 40px; }
    .hero-name { font-size: 64px; }
    .contact-grid { grid-template-columns: 1fr; }
    .nav-links { display: none; }
    #footer { flex-direction: column; gap: 8px; text-align: center; }
  }
</style>
</head>
<body>

<!-- ══════════════════════════════════════════════════
     BIOS BOOT SCREEN
══════════════════════════════════════════════════ -->
<div id="bios">
  <div class="bios-line white" id="b0">SK_OS v2.4.1 — ENGINEER EDITION</div>
  <div class="bios-line" id="b1">Copyright (C) 2024-2025 SRINITISH_K Systems. All rights reserved.</div>
  <div class="bios-line" id="b2"> </div>
  <div class="bios-line cyan" id="b3">CPU: Data Engineering Core v3.0 @ 99th Percentile</div>
  <div class="bios-line cyan" id="b4">RAM: 100+ TB Enterprise Data Processed</div>
  <div class="bios-line cyan" id="b5">Storage: Delta Lake · Snowflake · PostgreSQL · MySQL</div>
  <div class="bios-line" id="b6"> </div>
  <div class="bios-line amber" id="b7">Checking certifications...</div>
  <div class="bios-line green" id="b8">  ✓ Databricks Certified Data Engineer Professional</div>
  <div class="bios-line green" id="b9">  ✓ AWS Certified Data Engineer — Associate</div>
  <div class="bios-line green" id="b10">  ✓ Snowflake SnowPro Core</div>
  <div class="bios-line green" id="b11">  ✓ AWS Certified AI Practitioner</div>
  <div class="bios-line" id="b12"> </div>
  <div class="bios-line amber" id="b13">Loading modules: PySpark · Kafka · Airflow · Databricks · AWS...</div>
  <div class="bios-line" id="b14"> </div>
  <div id="bios-progress-line">
    <span>Boot progress: [</span><span class="bios-bar" id="bios-bar"></span><span>] </span><span id="bios-pct">0%</span>
  </div>
  <div class="bios-line" id="b15"> </div>
  <div class="bios-line green" id="b16">System ready. Loading SRINITISH_K portfolio...</div>
</div>

<!-- ══════════════════════════════════════════════════
     NAVBAR
══════════════════════════════════════════════════ -->
<nav id="navbar" style="display:none;">
  <div class="nav-logo">
    SK<span class="nav-logo-tag">&nbsp;// DATA ENGINEER</span>
  </div>
  <ul class="nav-links">
    <li><a href="#skills">SKILLS</a></li>
    <li><a href="#experience">EXPERIENCE</a></li>
    <li><a href="#projects">PROJECTS</a></li>
    <li><a href="#certifications">CERTS</a></li>
    <li><a href="#contact">CONTACT</a></li>
  </ul>
  <div style="display:flex;align-items:center;gap:16px;">
    <div class="nav-status"><span class="status-dot"></span>ONLINE</div>
    <div class="nav-clock">
      <span id="clock-time">00:00:00</span>
      <span class="nav-clock-date" id="clock-date">--/--/----</span>
    </div>
  </div>
</nav>

<!-- ══════════════════════════════════════════════════
     HERO
══════════════════════════════════════════════════ -->
<section id="hero">
  <div class="hero-grid-bg"></div>
  <div class="hero-glow"></div>
  <div class="hero-inner">
    <div class="hero-eyebrow">root@sk-os:~# whoami</div>
    <div class="hero-name">
      <span class="hero-name-glitch" data-text="SRINITISH K">SRINITISH K</span>
    </div>
    <div class="hero-title-line">
      <span class="hero-title-accent">Databricks Certified</span> Data Engineer &amp; GenAI Developer
    </div>

    <div class="hero-terminal">
      <div class="term-titlebar">
        <span class="term-dot r"></span>
        <span class="term-dot y"></span>
        <span class="term-dot g"></span>
        <span class="term-title">bash — sk@bangalore:~ — 80×24</span>
      </div>
      <div class="term-body" id="hero-term-body">
        <div><span class="term-prompt">sk@bangalore:~$</span> <span class="term-cmd" id="hero-type-cmd"></span><span id="hero-cursor" class="term-cursor"></span></div>
        <div id="hero-output" style="margin-top:8px;"></div>
      </div>
    </div>

    <div class="hero-badges" style="margin-top:28px;">
      <span class="badge badge-g">Databricks Professional</span>
      <span class="badge badge-c">AWS Data Engineer</span>
      <span class="badge badge-a">Snowflake SnowPro</span>
      <span class="badge badge-g">PySpark · Delta Lake</span>
      <span class="badge badge-c">Kafka Streaming</span>
      <span class="badge badge-a">GenAI · NLP · LLMs</span>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════════════
     SKILLS
══════════════════════════════════════════════════ -->
<section id="skills">
  <div class="section-header reveal">
    <span class="section-num">01 /</span>
    <h2 class="section-title">TECH STACK</h2>
    <div class="section-line"></div>
  </div>
  <div class="skills-grid">
    <div class="skill-card reveal" style="--accent-color: var(--green);">
      <div class="skill-cat">Programming</div>
      <div class="skill-tags">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">SQL</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">PySpark</span>
        <span class="skill-tag">Spark SQL</span>
      </div>
    </div>
    <div class="skill-card reveal" style="--accent-color: var(--cyan);">
      <div class="skill-cat">Data Engineering</div>
      <div class="skill-tags">
        <span class="skill-tag">Databricks</span>
        <span class="skill-tag">ETL/ELT Pipelines</span>
        <span class="skill-tag">Delta Lake</span>
        <span class="skill-tag">Data Modeling</span>
        <span class="skill-tag">Data Validation</span>
        <span class="skill-tag">Feature Engineering</span>
      </div>
    </div>
    <div class="skill-card reveal" style="--accent-color: var(--amber);">
      <div class="skill-cat">Streaming</div>
      <div class="skill-tags">
        <span class="skill-tag">Apache Kafka</span>
        <span class="skill-tag">Spark Streaming</span>
        <span class="skill-tag">Real-Time Pipelines</span>
        <span class="skill-tag">Fault-Tolerant Arch.</span>
      </div>
    </div>
    <div class="skill-card reveal" style="--accent-color: var(--green);">
      <div class="skill-cat">Cloud &amp; Orchestration</div>
      <div class="skill-tags">
        <span class="skill-tag">AWS S3</span>
        <span class="skill-tag">AWS EC2</span>
        <span class="skill-tag">Apache Airflow</span>
        <span class="skill-tag">CI/CD</span>
      </div>
    </div>
    <div class="skill-card reveal" style="--accent-color: var(--cyan);">
      <div class="skill-cat">ML &amp; Generative AI</div>
      <div class="skill-tags">
        <span class="skill-tag">LLMs</span>
        <span class="skill-tag">NLP</span>
        <span class="skill-tag">Embeddings</span>
        <span class="skill-tag">TF-IDF</span>
        <span class="skill-tag">Prompt Engineering</span>
        <span class="skill-tag">Information Retrieval</span>
        <span class="skill-tag">Semantic Search</span>
      </div>
    </div>
    <div class="skill-card reveal" style="--accent-color: var(--amber);">
      <div class="skill-cat">Databases &amp; Viz</div>
      <div class="skill-tags">
        <span class="skill-tag">Snowflake</span>
        <span class="skill-tag">PostgreSQL</span>
        <span class="skill-tag">MySQL</span>
        <span class="skill-tag">Power BI</span>
        <span class="skill-tag">Tableau</span>
        <span class="skill-tag">Git</span>
      </div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════════════
     EXPERIENCE
══════════════════════════════════════════════════ -->
<section id="experience">
  <div class="section-header reveal">
    <span class="section-num">02 /</span>
    <h2 class="section-title">EXPERIENCE</h2>
    <div class="section-line"></div>
  </div>
  <div class="timeline">

    <div class="tl-item reveal">
      <div class="tl-header">
        <div>
          <div class="tl-role">Software Engineer — Data Engineering</div>
          <div class="tl-company">⬡ GENPACT</div>
        </div>
        <div class="tl-date">OCT 2024 — PRESENT</div>
      </div>
      <div class="tl-sub">// Bangalore, India · Enterprise Data Platform</div>
      <ul class="tl-bullets">
        <li>Architected migration of <strong>100+ TB-scale</strong> enterprise datasets to Databricks with zero downtime, enabling scalable distributed data processing with high reliability.</li>
        <li>Built and optimized <strong>PySpark-based ETL pipelines</strong> for enterprise-scale data transformation, ingestion, and model-ready dataset generation.</li>
        <li>Improved pipeline performance by <strong>~30%</strong> through query optimization, partitioning strategies, and caching mechanisms.</li>
        <li>Implemented data validation and debugging frameworks achieving <strong>99%+ data accuracy</strong> across production workflows.</li>
        <li>Automated enterprise workflows using <strong>Airflow</strong> and supported CI/CD deployment for large-scale production systems.</li>
        <li>Built optimized SQL datasets and KPI reporting pipelines supporting operational decision-making and business analytics.</li>
        <li>Collaborated cross-functionally with engineering, QA, and deployment teams to deliver scalable enterprise-grade data solutions.</li>
      </ul>
    </div>

    <div class="tl-item reveal">
      <div class="tl-header">
        <div>
          <div class="tl-role">GE Vernova — Supplier 360 Platform</div>
          <div class="tl-company">⬡ GENPACT (Client Engagement)</div>
        </div>
      </div>
      <div class="tl-sub">// Centralized Enterprise Data Platform</div>
      <ul class="tl-bullets">
        <li>Developed centralized enterprise data platform integrating multiple source systems using <strong>PySpark and SQL</strong>.</li>
        <li>Built scalable data pipelines and transformation logic supporting analytics and operational reporting systems.</li>
        <li>Reduced analytics latency for downstream consumers through optimized Spark transformations and efficient data engineering workflows.</li>
      </ul>
    </div>

    <div class="tl-item reveal">
      <div class="tl-header">
        <div>
          <div class="tl-role">GenAI Intern</div>
          <div class="tl-company">⬡ GENPACT</div>
        </div>
        <div class="tl-date">FEB 2024 — JUL 2024</div>
      </div>
      <div class="tl-sub">// India · Natural Language Processing</div>
      <ul class="tl-bullets">
        <li>Developed an <strong>NLP-based document deduplication system</strong> leveraging TF-IDF, embeddings, and similarity matching to improve data quality.</li>
        <li>Built pipelines handling structured and unstructured datasets for intelligent document processing.</li>
        <li>Applied NLP techniques to improve system efficiency, semantic relevance, and pipeline throughput through automation.</li>
      </ul>
    </div>

  </div>
</section>

<!-- ══════════════════════════════════════════════════
     PROJECTS
══════════════════════════════════════════════════ -->
<section id="projects">
  <div class="section-header reveal">
    <span class="section-num">03 /</span>
    <h2 class="section-title">PROJECTS</h2>
    <div class="section-line"></div>
  </div>
  <div class="projects-grid">

    <div class="proj-card reveal">
      <div class="proj-top">
        <span class="proj-icon">⚡</span>
        <span class="proj-name">Real-Time Streaming Pipeline</span>
        <span class="proj-tag">STREAMING</span>
      </div>
      <div class="proj-body">
        <p class="proj-desc">Designed and developed a fault-tolerant Kafka + Spark Streaming pipeline for near real-time ingestion and distributed processing of high-throughput streaming data workloads with low-latency guarantees.</p>
        <div class="proj-stack">
          <span class="proj-pill">Apache Kafka</span>
          <span class="proj-pill">Spark Streaming</span>
          <span class="proj-pill">PySpark</span>
          <span class="proj-pill">Delta Lake</span>
          <span class="proj-pill">Databricks</span>
        </div>
      </div>
    </div>

    <div class="proj-card reveal">
      <div class="proj-top">
        <span class="proj-icon">🧠</span>
        <span class="proj-name">GenAI Document Deduplication</span>
        <span class="proj-tag">NLP · AI</span>
      </div>
      <div class="proj-body">
        <p class="proj-desc">Built an NLP-powered document deduplication pipeline using TF-IDF, dense embeddings, and semantic similarity scoring to detect duplicate records and significantly improve data quality across enterprise datasets.</p>
        <div class="proj-stack">
          <span class="proj-pill">TF-IDF</span>
          <span class="proj-pill">Embeddings</span>
          <span class="proj-pill">NLP</span>
          <span class="proj-pill">Python</span>
          <span class="proj-pill">Semantic Similarity</span>
        </div>
      </div>
    </div>

    <div class="proj-card reveal">
      <div class="proj-top">
        <span class="proj-icon">📊</span>
        <span class="proj-name">Social Media Sentiment Analysis</span>
        <span class="proj-tag">ANALYTICS</span>
      </div>
      <div class="proj-body">
        <p class="proj-desc">Analyzed large-scale social media datasets to surface sentiment trends, engagement behavior, and customer insights. Applied NLP-based analytics to support data-driven decision making and business intelligence reporting.</p>
        <div class="proj-stack">
          <span class="proj-pill">NLP</span>
          <span class="proj-pill">Python</span>
          <span class="proj-pill">PySpark</span>
          <span class="proj-pill">Sentiment Analysis</span>
          <span class="proj-pill">Data Analytics</span>
        </div>
      </div>
    </div>

    <div class="proj-card reveal">
      <div class="proj-top">
        <span class="proj-icon">🏭</span>
        <span class="proj-name">GE Vernova Supplier 360</span>
        <span class="proj-tag">ENTERPRISE</span>
      </div>
      <div class="proj-body">
        <p class="proj-desc">Delivered a centralized enterprise data platform integrating multiple business systems into a unified Supplier 360 view. Built scalable ETL pipelines and data models, reducing analytics latency and improving reporting fidelity.</p>
        <div class="proj-stack">
          <span class="proj-pill">PySpark</span>
          <span class="proj-pill">Databricks</span>
          <span class="proj-pill">SQL</span>
          <span class="proj-pill">Delta Lake</span>
          <span class="proj-pill">Power BI</span>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- ══════════════════════════════════════════════════
     CERTIFICATIONS
══════════════════════════════════════════════════ -->
<section id="certifications">
  <div class="section-header reveal">
    <span class="section-num">04 /</span>
    <h2 class="section-title">CERTIFICATIONS</h2>
    <div class="section-line"></div>
  </div>
  <div class="certs-grid">
    <div class="cert-card reveal">
      <span class="cert-icon">🏆</span>
      <div>
        <div class="cert-name">Databricks Certified Data Engineer Professional</div>
        <div class="cert-issuer">DATABRICKS</div>
      </div>
    </div>
    <div class="cert-card reveal">
      <span class="cert-icon">✦</span>
      <div>
        <div class="cert-name">Databricks Certified Data Engineer Associate</div>
        <div class="cert-issuer">DATABRICKS</div>
      </div>
    </div>
    <div class="cert-card reveal">
      <span class="cert-icon">❄</span>
      <div>
        <div class="cert-name">Snowflake SnowPro Core Certification</div>
        <div class="cert-issuer">SNOWFLAKE</div>
      </div>
    </div>
    <div class="cert-card reveal">
      <span class="cert-icon">☁</span>
      <div>
        <div class="cert-name">AWS Certified Data Engineer — Associate</div>
        <div class="cert-issuer">AMAZON WEB SERVICES</div>
      </div>
    </div>
    <div class="cert-card reveal">
      <span class="cert-icon">🤖</span>
      <div>
        <div class="cert-name">AWS Certified AI Practitioner</div>
        <div class="cert-issuer">AMAZON WEB SERVICES</div>
      </div>
    </div>
  </div>

  <!-- Achievements -->
  <div style="margin-top:40px;">
    <div class="section-header reveal" style="margin-bottom:24px;">
      <span class="section-num" style="font-size:10px;">ACHIEVEMENTS /</span>
      <div class="section-line"></div>
    </div>
    <div class="certs-grid">
      <div class="cert-card reveal" style="border-color:rgba(255,179,0,0.25);">
        <span class="cert-icon">🥇</span>
        <div>
          <div class="cert-name">Generative AI Champions League — Pioneer Award</div>
          <div class="cert-issuer">GENPACT INTERNAL</div>
        </div>
      </div>
      <div class="cert-card reveal" style="border-color:rgba(255,179,0,0.25);">
        <span class="cert-icon">🏅</span>
        <div>
          <div class="cert-name">SUPER 20 Award — Enterprise Data Migration Excellence</div>
          <div class="cert-issuer">GENPACT INTERNAL</div>
        </div>
      </div>
      <div class="cert-card reveal" style="border-color:rgba(255,179,0,0.25);">
        <span class="cert-icon">🎓</span>
        <div>
          <div class="cert-name">Gold Medalist — Dept. of Electrical &amp; Electronics Engineering</div>
          <div class="cert-issuer">KARE · B.TECH 2020–2024</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════════════
     CONTACT
══════════════════════════════════════════════════ -->
<section id="contact">
  <div class="section-header reveal">
    <span class="section-num">05 /</span>
    <h2 class="section-title">CONTACT</h2>
    <div class="section-line"></div>
  </div>
  <div id="contact-wrap">
    <div class="contact-grid reveal">
      <div class="contact-item">
        <span class="contact-item-icon">📧</span>
        <div>
          <div class="contact-label">Email</div>
          <div class="contact-val"><a href="mailto:ksrinitish@gmail.com">ksrinitish@gmail.com</a></div>
        </div>
      </div>
      <div class="contact-item">
        <span class="contact-item-icon">📱</span>
        <div>
          <div class="contact-label">Phone</div>
          <div class="contact-val"><a href="tel:+919865679988">+91 9865679988</a></div>
        </div>
      </div>
      <div class="contact-item">
        <span class="contact-item-icon">🔗</span>
        <div>
          <div class="contact-label">LinkedIn</div>
          <div class="contact-val"><a href="https://linkedin.com/in/srinitish-k-46a53020b" target="_blank">srinitish-k-46a53020b</a></div>
        </div>
      </div>
      <div class="contact-item">
        <span class="contact-item-icon">📍</span>
        <div>
          <div class="contact-label">Location</div>
          <div class="contact-val" style="color:var(--text);">Bangalore, India</div>
        </div>
      </div>
    </div>

    <!-- Interactive Terminal -->
    <div class="reveal">
      <div style="font-family:var(--mono);font-size:10px;color:var(--text-dim);letter-spacing:2px;margin-bottom:10px;">// INTERACTIVE TERMINAL — type 'help' to begin</div>
      <div id="iterm">
        <div class="term-titlebar">
          <span class="term-dot r"></span>
          <span class="term-dot y"></span>
          <span class="term-dot g"></span>
          <span class="term-title">contact@sk-os:~ — interactive shell</span>
        </div>
        <div id="iterm-output">
          <div class="iterm-resp">Welcome to SK-OS Contact Terminal v2.4.1</div>
          <div class="iterm-info">Type 'help' for available commands.</div>
          <div style="height:8px;"></div>
        </div>
        <div id="iterm-inputline">
          <span>visitor@sk-os:~$</span>
          <input id="iterm-input" type="text" placeholder="enter command..." autocomplete="off" spellcheck="false" />
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════════════════════════════════════════════
     FOOTER
══════════════════════════════════════════════════ -->
<footer id="footer">
  <span class="footer-sig">SRINITISH K :: DATA_ENGINEER :: BANGALORE</span>
  <span>Built with ❤ · <span style="color:var(--green);">PySpark</span> · <span style="color:var(--cyan);">Databricks</span> · <span style="color:var(--amber);">AWS</span></span>
  <span id="footer-uptime" style="color:var(--green-dim);">Uptime: 00:00:00</span>
</footer>

<!-- ══════════════════════════════════════════════════
     JAVASCRIPT
══════════════════════════════════════════════════ -->
<script>
/* ─── BIOS BOOT ─── */
(function() {
  const lines = document.querySelectorAll('.bios-line');
  const bar   = document.getElementById('bios-bar');
  const pct   = document.getElementById('bios-pct');

  let delay = 100;
  lines.forEach((el, i) => {
    setTimeout(() => { el.style.opacity = '1'; }, delay);
    delay += i < 7 ? 120 : 80;
  });

  setTimeout(() => {
    bar.style.width = '100%';
    let p = 0;
    const iv = setInterval(() => {
      p++;
      pct.textContent = p + '%';
      if (p >= 100) clearInterval(iv);
    }, 12);
  }, delay);

  setTimeout(() => {
    document.getElementById('bios').style.transition = 'opacity 0.5s';
    document.getElementById('bios').style.opacity = '0';
    setTimeout(() => {
      document.getElementById('bios').style.display = 'none';
      document.getElementById('navbar').style.display = 'flex';
      startHeroTyping();
    }, 500);
  }, delay + 1400);
})();

/* ─── CLOCK ─── */
function updateClock() {
  const now = new Date();
  const t = now.toTimeString().slice(0,8);
  const d = now.toLocaleDateString('en-GB');
  document.getElementById('clock-time').textContent = t;
  document.getElementById('clock-date').textContent = d;
}
updateClock();
setInterval(updateClock, 1000);

/* ─── UPTIME ─── */
const startTime = Date.now();
setInterval(() => {
  const s = Math.floor((Date.now() - startTime) / 1000);
  const h = String(Math.floor(s/3600)).padStart(2,'0');
  const m = String(Math.floor((s%3600)/60)).padStart(2,'0');
  const sc= String(s % 60).padStart(2,'0');
  const el = document.getElementById('footer-uptime');
  if (el) el.textContent = `Uptime: ${h}:${m}:${sc}`;
}, 1000);

/* ─── HERO TYPING ─── */
function startHeroTyping() {
  const cmd = 'cat profile.json';
  const output = `{
  <span class="term-key">"name"</span>:         <span class="term-val">"Srinitish K"</span>,
  <span class="term-key">"role"</span>:         <span class="term-val">"Data Engineer"</span>,
  <span class="term-key">"location"</span>:     <span class="term-val">"Bangalore, India"</span>,
  <span class="term-key">"company"</span>:      <span class="term-val">"Genpact"</span>,
  <span class="term-key">"experience"</span>:   <span class="term-val">"1+ years"</span>,
  <span class="term-key">"data_migrated"</span>: <span class="term-val">"100+ TB"</span>,
  <span class="term-key">"perf_gain"</span>:    <span class="term-val">"~30% pipeline improvement"</span>,
  <span class="term-key">"accuracy"</span>:     <span class="term-val">"99%+ data accuracy"</span>,
  <span class="term-key">"certs"</span>: [<span class="term-val">"Databricks Pro"</span>, <span class="term-val">"AWS DE"</span>, <span class="term-val">"Snowflake"</span>],
  <span class="term-key">"status"</span>:       <span class="term-val">"OPEN TO OPPORTUNITIES"</span>
}`;

  const cmdEl = document.getElementById('hero-type-cmd');
  const outEl = document.getElementById('hero-output');
  const cursor = document.getElementById('hero-cursor');

  let i = 0;
  function typeCmd() {
    if (i < cmd.length) {
      cmdEl.textContent += cmd[i++];
      setTimeout(typeCmd, 60);
    } else {
      cursor.style.display = 'none';
      setTimeout(() => {
        outEl.innerHTML = output;
      }, 200);
    }
  }
  typeCmd();
}

/* ─── SCROLL REVEAL ─── */
const revealEls = document.querySelectorAll('.reveal');
const observer = new IntersectionObserver((entries) => {
  entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold: 0.1 });
revealEls.forEach(el => observer.observe(el));

/* ─── INTERACTIVE TERMINAL ─── */
const termData = {
  help: () => `<div class="iterm-info">Available commands:</div>
<div class="iterm-resp">  skills      — view technical skills</div>
<div class="iterm-resp">  experience  — work history</div>
<div class="iterm-resp">  certs       — certifications</div>
<div class="iterm-resp">  contact     — get in touch</div>
<div class="iterm-resp">  email       — send email</div>
<div class="iterm-resp">  linkedin    — open LinkedIn</div>
<div class="iterm-resp">  summary     — professional summary</div>
<div class="iterm-resp">  clear       — clear terminal</div>`,

  skills: () => `<div class="iterm-resp">── TECHNICAL SKILLS ──────────────────────</div>
<div class="iterm-resp">  Programming:      Python · SQL · PySpark</div>
<div class="iterm-resp">  Data Eng:         Databricks · Delta Lake · ETL/ELT</div>
<div class="iterm-resp">  Streaming:        Apache Kafka · Spark Streaming</div>
<div class="iterm-resp">  Cloud:            AWS S3 · EC2 · Airflow</div>
<div class="iterm-resp">  AI/ML:            LLMs · NLP · TF-IDF · Embeddings</div>
<div class="iterm-resp">  Databases:        Snowflake · PostgreSQL · MySQL</div>
<div class="iterm-resp">  Viz:              Power BI · Tableau</div>`,

  experience: () => `<div class="iterm-resp">── EXPERIENCE ────────────────────────────</div>
<div class="iterm-resp">  <span class="iterm-info">Genpact</span> · Software Engineer (Data Eng)</div>
<div class="iterm-resp">  Oct 2024 – Present · Bangalore, India</div>
<div class="iterm-resp">  → 100+ TB enterprise migration to Databricks</div>
<div class="iterm-resp">  → 30% pipeline performance improvement</div>
<div class="iterm-resp">  → 99%+ data accuracy in production</div>
<div style="height:6px;"></div>
<div class="iterm-resp">  <span class="iterm-info">Genpact</span> · GenAI Intern</div>
<div class="iterm-resp">  Feb 2024 – Jul 2024 · India</div>
<div class="iterm-resp">  → NLP document deduplication system</div>
<div class="iterm-resp">  → TF-IDF + embeddings + similarity scoring</div>`,

  certs: () => `<div class="iterm-resp">── CERTIFICATIONS ────────────────────────</div>
<div class="iterm-resp">  ✓ Databricks Certified Data Engineer Professional</div>
<div class="iterm-resp">  ✓ Databricks Certified Data Engineer Associate</div>
<div class="iterm-resp">  ✓ Snowflake SnowPro Core</div>
<div class="iterm-resp">  ✓ AWS Certified Data Engineer — Associate</div>
<div class="iterm-resp">  ✓ AWS Certified AI Practitioner</div>`,

  contact: () => `<div class="iterm-resp">── CONTACT INFO ──────────────────────────</div>
<div class="iterm-resp">  Email:    ksrinitish@gmail.com</div>
<div class="iterm-resp">  Phone:    +91 9865679988</div>
<div class="iterm-resp">  LinkedIn: linkedin.com/in/srinitish-k-46a53020b</div>
<div class="iterm-resp">  Location: Bangalore, India</div>`,

  email: () => {
    window.location.href = 'mailto:ksrinitish@gmail.com';
    return `<div class="iterm-resp">Opening email client... → ksrinitish@gmail.com</div>`;
  },
  linkedin: () => {
    window.open('https://linkedin.com/in/srinitish-k-46a53020b', '_blank');
    return `<div class="iterm-resp">Opening LinkedIn profile in new tab...</div>`;
  },
  summary: () => `<div class="iterm-resp">── PROFESSIONAL SUMMARY ──────────────────</div>
<div class="iterm-resp">  Databricks Certified Data Engineer with hands-on</div>
<div class="iterm-resp">  experience building scalable ETL/ELT pipelines,</div>
<div class="iterm-resp">  distributed data processing, and enterprise-scale</div>
<div class="iterm-resp">  data migration using Python, PySpark, Databricks,</div>
<div class="iterm-resp">  and AWS. Strong foundation in GenAI, NLP, and LLMs</div>
<div class="iterm-resp">  with practical experience developing intelligent</div>
<div class="iterm-resp">  document processing and recommendation systems.</div>`,

  clear: () => '__clear__',
};

const itermOutput = document.getElementById('iterm-output');
const itermInput  = document.getElementById('iterm-input');

function itermPrint(cmd, response) {
  const row = document.createElement('div');
  row.innerHTML = `<div class="iterm-row"><span class="iterm-p">visitor@sk-os:~$ </span><span class="iterm-c">${cmd}</span></div>`;
  itermOutput.appendChild(row);
  if (response !== '__clear__') {
    const resp = document.createElement('div');
    resp.style.marginBottom = '8px';
    resp.innerHTML = response;
    itermOutput.appendChild(resp);
  } else {
    itermOutput.innerHTML = '';
  }
  itermOutput.scrollTop = itermOutput.scrollHeight;
}

itermInput.addEventListener('keydown', (e) => {
  if (e.key !== 'Enter') return;
  const val = itermInput.value.trim().toLowerCase();
  itermInput.value = '';
  if (!val) return;
  const fn = termData[val];
  if (fn) {
    itermPrint(val, fn());
  } else {
    itermPrint(val, `<div class="iterm-err">command not found: ${val}. Type 'help' for commands.</div>`);
  }
});

itermInput.addEventListener('click', () => itermInput.focus());
</script>
</body>
</html>
