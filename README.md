<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=arduino,css,html,github,py,vscode&perline=14" />
  </a>
</p>



<!--- stats & Trophy (start) src="https://github-readme-streak-stats.herokuapp.com/?user=1010nishant&theme=dark&hide_border=false" -->
<p align="center">
  <!--- stats (start) -->
<table align="center">
<tr border="none">
<td width="50%" align="center">
  
  <br></br>
  [![GitHub Streak](https://streak-stats.demolab.com?user=MORENOG-2&theme=dark&background=0D1117&ring=f97316&fire=f97316&currStreakLabel=f97316)](https://github.com/MORENOG-2)
</tr>
</table>
<!--- stats (end) -->

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Stats – MORENOG-2</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700;800&family=Syne:wght@400;700;800&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg: #0d1117; --card: #161b22; --border: #21262d;
    --orange: #f97316; --orange-glow: rgba(249,115,22,0.3);
    --text: #e6edf3; --muted: #8b949e;
  }
  body { background: var(--bg); font-family: 'Syne', sans-serif; display: flex; align-items: center; justify-content: center; min-height: 100vh; padding: 2rem; }
  .wrapper { width: 100%; max-width: 680px; display: flex; flex-direction: column; gap: 1.2rem; }

  .header { display: flex; align-items: center; gap: 1rem; opacity: 0; animation: fadeUp 0.6s ease forwards; }
  .avatar { width: 52px; height: 52px; border-radius: 50%; border: 2px solid var(--orange); box-shadow: 0 0 14px var(--orange-glow); }
  .username { font-size: 1.4rem; font-weight: 800; color: var(--text); letter-spacing: -0.02em; }
  .username span { color: var(--orange); }
  .sub { font-size: 0.78rem; color: var(--muted); font-family: 'JetBrains Mono', monospace; margin-top: 2px; }

  .card { background: var(--card); border: 1px solid var(--border); border-radius: 16px; position: relative; overflow: hidden; opacity: 0; }
  .card::before { content: ''; position: absolute; top: 0; left: 0; right: 0; height: 1px; background: linear-gradient(90deg, transparent, var(--orange), transparent); opacity: 0.6; }

  .stats-card { padding: 2rem; display: grid; grid-template-columns: 1fr auto 1fr; animation: fadeUp 0.6s ease 0.15s forwards; }
  .stat { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 1rem 1.5rem; gap: 0.4rem; }
  .stat-value { font-family: 'JetBrains Mono', monospace; font-size: 2.4rem; font-weight: 800; color: var(--text); letter-spacing: -0.03em; line-height: 1; }
  .stat-label { font-size: 0.8rem; font-weight: 700; color: var(--muted); text-transform: uppercase; letter-spacing: 0.08em; }
  .stat-date { font-size: 0.72rem; color: var(--muted); font-family: 'JetBrains Mono', monospace; margin-top: 2px; text-align: center; }
  .divider { width: 1px; background: var(--border); margin: 0.5rem 0; align-self: stretch; }

  .streak-center { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 1rem 2rem; gap: 0.5rem; }
  .ring-wrap { position: relative; width: 90px; height: 90px; }
  .ring-svg { width: 90px; height: 90px; transform: rotate(-90deg); }
  .ring-bg { fill: none; stroke: var(--border); stroke-width: 5; }
  .ring-fill { fill: none; stroke: var(--orange); stroke-width: 5; stroke-linecap: round; stroke-dasharray: 226; stroke-dashoffset: 226; filter: drop-shadow(0 0 6px var(--orange)); transition: stroke-dashoffset 1.2s cubic-bezier(0.4,0,0.2,1); }
  .ring-icon { position: absolute; top: 50%; left: 50%; transform: translate(-50%,-50%); font-size: 1.6rem; animation: flicker 2s ease-in-out infinite; }
  @keyframes flicker { 0%,100%{opacity:1} 50%{opacity:0.7} }
  .streak-value { font-family: 'JetBrains Mono', monospace; font-size: 1.8rem; font-weight: 800; color: var(--orange); text-shadow: 0 0 12px var(--orange-glow); line-height: 1; }
  .streak-label { font-size: 0.78rem; font-weight: 700; color: var(--orange); text-transform: uppercase; letter-spacing: 0.1em; }
  .streak-date { font-size: 0.7rem; color: var(--muted); font-family: 'JetBrains Mono', monospace; }

  .lang-card { padding: 1.8rem 2rem; animation: fadeUp 0.6s ease 0.3s forwards; }
  .section-title { font-size: 1rem; font-weight: 800; color: var(--text); letter-spacing: -0.01em; margin-bottom: 1.4rem; }
  .lang-list { display: flex; flex-direction: column; gap: 0.85rem; }
  .lang-row { display: grid; grid-template-columns: 140px 1fr 58px; align-items: center; gap: 0.75rem; opacity: 0; animation: fadeUp 0.4s ease forwards; }
  .lang-name { font-size: 0.82rem; font-weight: 700; color: var(--text); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; display: flex; align-items: center; gap: 6px; }
  .lang-dot { width: 8px; height: 8px; border-radius: 50%; flex-shrink: 0; }
  .bar-track { height: 6px; background: var(--border); border-radius: 99px; overflow: hidden; }
  .bar-fill { height: 100%; border-radius: 99px; width: 0%; transition: width 1s cubic-bezier(0.4,0,0.2,1); }
  .lang-pct { font-family: 'JetBrains Mono', monospace; font-size: 0.75rem; color: var(--muted); text-align: right; }
  .multibar-wrap { margin-top: 1.4rem; }
  .multibar { height: 8px; border-radius: 99px; overflow: hidden; display: flex; }
  .multibar-seg { height: 100%; width: 0%; transition: width 1s cubic-bezier(0.4,0,0.2,1); }

  .skeleton { background: linear-gradient(90deg, var(--border) 25%, #2d333b 50%, var(--border) 75%); background-size: 200% 100%; animation: shimmer 1.5s infinite; border-radius: 6px; color: transparent !important; }
  @keyframes shimmer { 0%{background-position:200% 0} 100%{background-position:-200% 0} }

  .status-bar { text-align: center; font-size: 0.72rem; color: var(--muted); font-family: 'JetBrains Mono', monospace; padding: 0.5rem; opacity: 0; animation: fadeUp 0.6s ease 0.4s forwards; }
  .status-bar.error { color: #f85149; }
  .status-bar.success { color: #3fb950; }

  .footer { text-align: center; font-size: 0.7rem; color: var(--muted); font-family: 'JetBrains Mono', monospace; opacity: 0; animation: fadeUp 0.6s ease 0.5s forwards; }
  .footer a { color: var(--orange); text-decoration: none; }

  @keyframes fadeUp { from{opacity:0;transform:translateY(16px)} to{opacity:1;transform:translateY(0)} }

  @media(max-width:480px){
    .stat-value{font-size:1.6rem} .streak-value{font-size:1.4rem}
    .stats-card{padding:1.2rem 0.5rem} .stat{padding:0.8rem 0.5rem}
    .streak-center{padding:0.8rem} .lang-row{grid-template-columns:100px 1fr 50px}
  }
</style>
</head>
<body>
<div class="wrapper">

  <div class="header">
    <img class="avatar" id="avatar" src="https://avatars.githubusercontent.com/MORENOG-2" alt="avatar">
    <div>
      <div class="username"><span>@</span>MORENOG-2</div>
      <div class="sub" id="bio">Cargando perfil…</div>
    </div>
  </div>

  <div class="card stats-card">
    <div class="stat">
      <div class="stat-value skeleton" id="total-val" style="min-width:80px;min-height:38px;"> </div>
      <div class="stat-label">Contribuciones</div>
      <div class="stat-date" id="total-date"> </div>
    </div>
    <div class="divider"></div>
    <div class="streak-center">
      <div class="ring-wrap">
        <svg class="ring-svg" viewBox="0 0 90 90">
          <circle class="ring-bg" cx="45" cy="45" r="36"/>
          <circle class="ring-fill" id="ring" cx="45" cy="45" r="36"/>
        </svg>
        <div class="ring-icon">🔥</div>
      </div>
      <div class="streak-value" id="streak-val">–</div>
      <div class="streak-label">Racha Actual</div>
      <div class="streak-date" id="streak-date"> </div>
    </div>
    <div class="divider"></div>
    <div class="stat">
      <div class="stat-value skeleton" id="longest-val" style="min-width:60px;min-height:38px;"> </div>
      <div class="stat-label">Racha Máxima</div>
      <div class="stat-date" id="longest-date"> </div>
    </div>
  </div>

  <div class="card lang-card">
    <div class="section-title">Most Used Languages</div>
    <div class="lang-list" id="lang-list">
      <div class="lang-row" style="animation-delay:0s"><div class="lang-name skeleton" style="height:14px;width:90px"> </div><div class="bar-track"><div class="bar-fill skeleton" style="width:100%"> </div></div><div class="lang-pct skeleton" style="height:14px;width:40px"> </div></div>
      <div class="lang-row" style="animation-delay:0.06s"><div class="lang-name skeleton" style="height:14px;width:70px"> </div><div class="bar-track"><div class="bar-fill skeleton" style="width:100%"> </div></div><div class="lang-pct skeleton" style="height:14px;width:40px"> </div></div>
      <div class="lang-row" style="animation-delay:0.12s"><div class="lang-name skeleton" style="height:14px;width:55px"> </div><div class="bar-track"><div class="bar-fill skeleton" style="width:100%"> </div></div><div class="lang-pct skeleton" style="height:14px;width:40px"> </div></div>
    </div>
    <div class="multibar-wrap"><div class="multibar" id="multibar"></div></div>
  </div>

  <div class="status-bar" id="status">⟳ Consultando API de GitHub…</div>
  <div class="footer">GitHub Stats · <a href="https://github.com/MORENOG-2" target="_blank">MORENOG-2</a> · Powered by Claude AI</div>
</div>

<script>
const USERNAME = 'MORENOG-2';

const LANG_COLORS = {
  JavaScript:'#f1e05a', TypeScript:'#3178c6', HTML:'#e34c26', CSS:'#563d7c',
  Python:'#3572A5', 'Jupyter Notebook':'#DA5B0B', Java:'#b07219', Kotlin:'#A97BFF',
  Swift:'#F05138', Go:'#00ADD8', Rust:'#dea584', Ruby:'#701516', PHP:'#4F5D95',
  'C#':'#178600', 'C++':'#f34b7d', C:'#555555', Shell:'#89e051', Vue:'#41b883',
  Pug:'#a86454', 'Objective-C':'#438eff', Dart:'#00B4AB', Scala:'#c22d40',
  R:'#198CE7', SCSS:'#c6538c', Svelte:'#ff3e00',
};
const getColor = l => LANG_COLORS[l] || '#' + Math.abs(Math.sin(l.charCodeAt(0)*999)*16777215|0).toString(16).padStart(6,'0');
const fmt = n => n >= 1000 ? (n/1000).toFixed(1).replace('.0','')+'k' : String(n);
const fmtDate = d => { if(!d) return ''; const m=['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'],dt=new Date(d+'T00:00:00'); return `${m[dt.getMonth()]} ${dt.getDate()}, ${dt.getFullYear()}`; };

function setStatus(msg, type='') {
  const el = document.getElementById('status');
  el.textContent = msg; el.className = 'status-bar ' + type;
}

function animateNum(el, target) {
  el.classList.remove('skeleton');
  let s=0;
  requestAnimationFrame(function step(ts){ if(!s)s=ts; const p=Math.min((ts-s)/1200,1),e=1-Math.pow(1-p,3); el.textContent=fmt(Math.round(e*target)); if(p<1)requestAnimationFrame(step); else el.textContent=fmt(target); });
}

function animateRing(cur,max){
  setTimeout(()=>{ document.getElementById('ring').style.strokeDashoffset=226-Math.min(cur/Math.max(max,1),1)*226; },400);
}

function applyStats(d) {
  animateNum(document.getElementById('total-val'), d.total||0);
  document.getElementById('total-date').textContent = d.firstDate ? `${fmtDate(d.firstDate)} – Hoy` : '';
  document.getElementById('streak-val').textContent = d.current||0;
  document.getElementById('streak-date').textContent = d.currentStart ? fmtDate(d.currentStart) : '';
  animateNum(document.getElementById('longest-val'), d.longest||0);
  document.getElementById('longest-date').textContent = (d.longestStart&&d.longestEnd) ? `${fmtDate(d.longestStart)} – ${fmtDate(d.longestEnd)}` : '';
  animateRing(d.current||0, d.longest||1);
}

function renderLangs(langs) {
  const list=document.getElementById('lang-list'), mb=document.getElementById('multibar');
  list.innerHTML=''; mb.innerHTML='';
  const maxP=langs[0].pct;
  langs.forEach((item,i)=>{
    const c=getColor(item.lang);
    const row=document.createElement('div'); row.className='lang-row'; row.style.animationDelay=(i*0.06)+'s';
    row.innerHTML=`<div class="lang-name"><span class="lang-dot" style="background:${c}"></span>${item.lang}</div><div class="bar-track"><div class="bar-fill" id="b${i}" style="background:${c}"></div></div><div class="lang-pct">${item.pct.toFixed(2)}%</div>`;
    list.appendChild(row);
    const seg=document.createElement('div'); seg.className='multibar-seg'; seg.id='s'+i; seg.style.background=c; mb.appendChild(seg);
    setTimeout(()=>{ document.getElementById('b'+i).style.width=(item.pct/maxP*100)+'%'; document.getElementById('s'+i).style.width=item.pct+'%'; },120+i*60);
  });
}

// --- Use Claude AI to fetch & calculate real GitHub stats ---
async function fetchWithClaude() {
  setStatus('⟳ Obteniendo datos reales de GitHub…');

  const prompt = `You are a GitHub data fetcher. Fetch real data for GitHub user "${USERNAME}" using the public GitHub API (no auth needed).

Do these steps:
1. GET https://api.github.com/users/${USERNAME} — get profile info (bio, name, created_at)
2. GET https://api.github.com/users/${USERNAME}/repos?per_page=100&type=owner — get repos list
3. For each repo (up to 30), GET https://api.github.com/repos/${USERNAME}/{repo_name}/languages — accumulate language bytes
4. To calculate contribution streak, use the GitHub contributions calendar: GET https://github.com/users/${USERNAME}/contributions — parse the SVG to count contribution days, then compute: total contributions (sum all), current streak (consecutive days ending today), longest streak ever.

Return ONLY valid JSON (no markdown, no explanation):
{
  "bio": "string",
  "total": number,
  "firstDate": "YYYY-MM-DD",
  "current": number,
  "currentStart": "YYYY-MM-DD",
  "longest": number,
  "longestStart": "YYYY-MM-DD",
  "longestEnd": "YYYY-MM-DD",
  "languages": [{"lang":"name","pct":number}, ...]
}

The languages array should be sorted descending by pct, max 10 items, percentages sum to 100.`;

  const response = await fetch("https://api.anthropic.com/v1/messages", {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify({
      model: "claude-sonnet-4-20250514",
      max_tokens: 1000,
      tools: [{ type: "web_search_20250305", name: "web_search" }],
      messages: [{ role: "user", content: prompt }]
    })
  });

  if (!response.ok) throw new Error('API error ' + response.status);
  const data = await response.json();

  // Extract text from all content blocks
  const text = data.content
    .filter(b => b.type === 'text')
    .map(b => b.text)
    .join('');

  // Parse JSON from response
  const clean = text.replace(/```json|```/g, '').trim();
  const start = clean.indexOf('{'), end = clean.lastIndexOf('}');
  if (start === -1) throw new Error('No JSON found');
  return JSON.parse(clean.slice(start, end+1));
}

async function main() {
  // Load avatar/bio from GitHub directly (no CORS issues)
  try {
    const p = await (await fetch(`https://api.github.com/users/${USERNAME}`)).json();
    document.getElementById('avatar').src = p.avatar_url;
    document.getElementById('bio').textContent = p.bio || p.name || 'GitHub Developer';
  } catch(e) {}

  // Load languages directly (GitHub API supports CORS for repos)
  try {
    let repos = [];
    const r = await fetch(`https://api.github.com/users/${USERNAME}/repos?per_page=100&type=owner`);
    if (r.ok) repos = await r.json();

    const lb = {};
    await Promise.all(repos.slice(0,40).map(async repo => {
      try {
        const d = await (await fetch(`https://api.github.com/repos/${USERNAME}/${repo.name}/languages`)).json();
        for (const [l,v] of Object.entries(d)) lb[l]=(lb[l]||0)+v;
      } catch(e) {}
    }));

    const total = Object.values(lb).reduce((a,b)=>a+b,0);
    if (total > 0) {
      const sorted = Object.entries(lb).sort((a,b)=>b[1]-a[1]).slice(0,10).map(([lang,bytes])=>({lang,pct:bytes/total*100}));
      renderLangs(sorted);
    }
  } catch(e) {}

  // Use Claude AI with web_search to get streak & contribution data
  try {
    const stats = await fetchWithClaude();
    applyStats(stats);
    if (stats.languages && stats.languages.length > 0) renderLangs(stats.languages);
    setStatus('✓ Datos actualizados en tiempo real', 'success');
  } catch(e) {
    // Final fallback: parse contributions from GitHub SVG directly
    try {
      await loadContributionsFromGitHub();
    } catch(e2) {
      applyStats({total:1595,firstDate:'2021-08-13',current:0,currentStart:'2026-03-04',longest:12,longestStart:'2023-06-06',longestEnd:'2023-06-17'});
      setStatus('⚠ Usando datos en caché', 'error');
    }
  }
}

async function loadContributionsFromGitHub() {
  // Fetch the contributions SVG via a CORS proxy
  const url = `https://corsproxy.io/?https://github.com/users/${USERNAME}/contributions`;
  const r = await fetch(url);
  if (!r.ok) throw new Error();
  const html = await r.text();

  // Parse contribution data-count attributes
  const matches = [...html.matchAll(/data-count="(\d+)" data-date="(\d{4}-\d{2}-\d{2})"/g)];
  if (!matches.length) throw new Error('no data');

  const days = matches.map(m => ({ count: parseInt(m[1]), date: m[2] })).sort((a,b)=>a.date.localeCompare(b.date));

  const total = days.reduce((s,d)=>s+d.count,0);
  const firstDate = days.find(d=>d.count>0)?.date;

  // Calculate streaks
  let curStreak=0, curStart=null, longestStreak=0, longestStart=null, longestEnd=null;
  let tempStreak=0, tempStart=null;
  const today = new Date().toISOString().slice(0,10);

  for (let i=0; i<days.length; i++) {
    const d=days[i];
    if (d.count>0) {
      if (tempStreak===0) tempStart=d.date;
      tempStreak++;
      if (tempStreak>longestStreak) { longestStreak=tempStreak; longestStart=tempStart; longestEnd=d.date; }
    } else {
      tempStreak=0; tempStart=null;
    }
  }

  // Current streak: count from today backwards
  for (let i=days.length-1; i>=0; i--) {
    if (days[i].count>0) { if(curStreak===0) curStart=days[i].date; curStreak++; }
    else break;
  }

  applyStats({ total, firstDate: firstDate||'2021-08-13', current: curStreak, currentStart: curStart||today, longest: longestStreak, longestStart, longestEnd });
  setStatus('✓ Datos reales de GitHub', 'success');
}

main();
</script>
</body>
</html>
