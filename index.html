<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Laukik Parashare · Portfolio Tree</title>
<style>
:root{color-scheme:dark;--bg:#0b1020;--panel:#111833;--line:#334155;--ink:#e2e8f0;--mute:#94a3b8;--acc:#7dd3fc;--n0:#1e3a5f;--n1:#1e293b;--n2:#0f172a}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Segoe UI",system-ui,-apple-system,sans-serif;min-height:100vh}
header{text-align:center;padding:36px 16px 8px}
h1{margin:0;font-size:clamp(28px,5vw,44px);letter-spacing:.5px;font-weight:700}
.sub{color:var(--mute);font-family:"JetBrains Mono",Consolas,monospace;font-size:14px;margin-top:8px;min-height:20px}
.hint{text-align:center;color:var(--mute);font-size:13px;margin:6px 0 0}
#wrap{overflow-x:auto;padding:12px 16px 4px}
svg{display:block;margin:0 auto}
.edge{fill:none;stroke:var(--line);stroke-width:1.6}
.node{cursor:pointer;animation:pop .35s ease both}
.node ellipse{stroke-width:1.6;transition:fill .2s,stroke .2s}
.node:hover ellipse{stroke:var(--acc)}
.node text{fill:var(--ink);font-size:13px;text-anchor:middle;dominant-baseline:central;pointer-events:none}
.node.sel ellipse{stroke:var(--acc);stroke-width:2.5}
.tog circle{fill:var(--bg);stroke:var(--acc);stroke-width:1.4}
.tog text{fill:var(--acc);font-size:12px;font-weight:700}
@keyframes pop{from{opacity:0;transform:translateY(-8px)}to{opacity:1;transform:none}}
#panel{max-width:760px;margin:10px auto 40px;padding:20px 24px;background:var(--panel);border:1px solid var(--line);border-radius:14px;min-height:120px}
#panel h2{margin:0 0 4px;font-size:20px}
#panel .path{color:var(--mute);font-family:Consolas,monospace;font-size:12px;margin-bottom:12px}
#panel p{line-height:1.65;margin:0 0 12px;color:#cbd5e1}
.tags span{display:inline-block;background:var(--n1);border:1px solid var(--line);border-radius:999px;padding:3px 11px;font-size:12px;margin:0 6px 6px 0;color:var(--acc)}
.links a{display:inline-block;margin:4px 10px 0 0;padding:8px 16px;border-radius:8px;background:var(--acc);color:#0b1020;font-weight:600;font-size:13px;text-decoration:none}
.links a.alt{background:transparent;border:1px solid var(--acc);color:var(--acc)}
footer{text-align:center;padding:0 0 36px}
footer a{color:var(--acc);margin:0 10px;font-size:14px;text-decoration:none}
</style>
</head>
<body>
<header>
  <h1>Laukik Parashare</h1>
  <div class="sub" id="typed"></div>
</header>
<p class="hint">Click a node to expand or collapse it. Click any node to read its details.</p>
<div id="wrap"><svg id="svg"></svg></div>
<div id="panel"></div>
<footer>
  <a href="mailto:laukikparashare@gmail.com">Email</a>
  <a href="https://www.linkedin.com/in/laukik-parashare-7373a326b/">LinkedIn</a>
  <a href="https://github.com/Rockyyy2312">GitHub</a>
</footer>

<script>
const T = {n:"about", d:"Software engineer building AI-powered applications, backend systems and cloud-ready infrastructure. I take messy real-world problems, break them into engineering problems and turn them into systems that work.", c:[
 {n:"skills", d:"The tools I work with, grouped by area. Expand a group to see what is inside.", c:[
  {n:"languages", d:"Languages I use for software, data and systems work.", tags:["Python","C++","Java","JavaScript","SQL"], c:[
   {n:"Python", d:"Primary language for ML, data processing and backend services."},
   {n:"C++", d:"Used for data structures, algorithms and performance-minded code."},
   {n:"Java", d:"Object-oriented programming and core application development."},
   {n:"JavaScript", d:"Powers the Node.js and React parts of my full-stack work."},
   {n:"SQL", d:"Querying and modelling relational data in MySQL and PostgreSQL."}]},
  {n:"ai-ml", d:"Machine learning and LLM-based application work, from classical models to retrieval pipelines.", tags:["Machine Learning","LLM Apps","RAG","Embeddings"], c:[
   {n:"Machine Learning", d:"Supervised, unsupervised and reinforcement learning, backed by the Machine Learning Specialization."},
   {n:"LLM Applications", d:"Applications built around large language models."},
   {n:"RAG Pipelines", d:"Retrieval-augmented generation that grounds answers in your own data."},
   {n:"Embeddings", d:"Vector embeddings for semantic search and retrieval."},
   {n:"Prompt Engineering", d:"Designing prompts that give reliable, structured output."},
   {n:"PyTorch", d:"Deep learning framework."},
   {n:"TensorFlow", d:"Deep learning framework."},
   {n:"Scikit-Learn", d:"Classical ML models and evaluation, including anomaly detection."}]},
  {n:"backend", d:"APIs and services: authentication, access control and clean module structure.", tags:["REST","JWT","RBAC"], c:[
   {n:"FastAPI", d:"Fast Python APIs."},
   {n:"Django REST", d:"Used for the health data platform's APIs."},
   {n:"Node + Express", d:"Used for the log platform's services."},
   {n:"REST APIs", d:"Resource-oriented API design with validation."},
   {n:"JWT + RBAC", d:"Token authentication with role-based access control."}]},
  {n:"frontend", d:"Interfaces for dashboards and apps.", tags:["React","Next.js"], c:[
   {n:"React", d:"Dashboards and interactive UIs."},
   {n:"Next.js", d:"Used for the health platform's front end."}]},
  {n:"databases", d:"Relational and document stores.", tags:["MongoDB","MySQL","PostgreSQL"], c:[
   {n:"MongoDB", d:"Document store for logs and records."},
   {n:"MySQL", d:"Relational database."},
   {n:"PostgreSQL", d:"Relational database for the health platform."}]},
  {n:"cloud-devops", d:"Deploying and running services on AWS.", tags:["AWS","Docker"], c:[
   {n:"EC2", d:"Hosts the application server."},
   {n:"S3", d:"Object storage."},
   {n:"RDS", d:"Managed relational database."},
   {n:"IAM", d:"Access and permissions."},
   {n:"Docker", d:"Containerised, reproducible services."},
   {n:"Git + GitHub", d:"Version control and collaboration."}]}
 ]},
 {n:"projects", d:"Two systems I am building. Expand one to see its overview, architecture, features and stack.", c:[
  {n:"AI Log Intelligence", d:"An AI-powered observability platform for real-time log ingestion, analysis, anomaly detection and debugging.", links:[["Live demo","https://ai-log-intelligence-frontend.vercel.app/"],["Source code","https://github.com/Rockyyy2312/AI-log-Intelligence-system"]], c:[
   {n:"Architecture", d:"Logs flow left to right through five stages: ingest, process, analyse, visualise.", c:[
    {n:"1 Logs", d:"Application logs are the input to the pipeline."},
    {n:"2 Ingestion", d:"Real-time log ingestion, with live streaming over Socket.IO."},
    {n:"3 Processing", d:"Log filtering and metadata processing."},
    {n:"4 ML Analysis", d:"Automated pattern detection and ML-based anomaly detection."},
    {n:"5 Dashboard", d:"Interactive monitoring dashboards for debugging."}]},
   {n:"Features", d:"What the platform does.", c:[
    {n:"Live streaming", d:"Logs appear in the dashboard as they arrive."},
    {n:"Pattern detection", d:"Finds recurring patterns automatically."},
    {n:"Anomaly detection", d:"ML flags unusual log behaviour."},
    {n:"REST APIs", d:"Programmatic access to logs and results."},
    {n:"Filtering", d:"Filter by metadata to narrow down an issue."}]},
   {n:"Stack", d:"Technologies used.", tags:["Python","React","Node.js","MongoDB","Docker","AWS","Socket.IO"]}]},
  {n:"Health Data Platform", d:"A secure healthcare platform focused on patient-controlled medical records, authentication, access control and data integrity.", c:[
   {n:"Architecture", d:"Every request passes authentication and access control before it reaches stored data.", c:[
    {n:"1 Patient", d:"The patient owns and controls their records."},
    {n:"2 JWT Auth", d:"Authenticates every request."},
    {n:"3 Access Control", d:"Role-based permissions decide who sees what."},
    {n:"4 REST API", d:"Django REST Framework endpoints."},
    {n:"5 Medical Data", d:"Stored records, protected by integrity checks."}]},
   {n:"Features", d:"What the platform does.", c:[
    {n:"Record ownership", d:"Patient-controlled record management."},
    {n:"SHA-256", d:"Integrity verification on stored data."},
    {n:"Verification", d:"Blockchain-inspired verification of records."},
    {n:"Modular", d:"Dockerised, modular backend."}]},
   {n:"Stack", d:"Technologies used.", tags:["Next.js","Django","Python","Docker","PostgreSQL"]}]}
 ]},
 {n:"education", d:"Bachelor of Engineering in Information Technology, Savitribai Phule Pune University, 2022 to 2026.", c:[
  {n:"B.E. IT", d:"Savitribai Phule Pune University, 2022 to 2026."},
  {n:"ML Specialization", d:"Supervised, unsupervised and reinforcement learning, plus ML projects."},
  {n:"AWS with Python", d:"EC2, S3, RDS and IAM with Python-based cloud apps."}]}
]};

const open = new Set(), H = 96, svg = document.getElementById("svg"), panel = document.getElementById("panel");
let sel = T, id = 0;
(function tag(n, p){ n.id = id++; n.p = p; (n.c||[]).forEach(c => tag(c, n)); })(T, null);
const W = n => Math.max(78, n.n.length * 7.6 + 30);
function size(n){ const kids = open.has(n.id) && n.c ? n.c : []; kids.forEach(size);
  n.w = Math.max(W(n) + 22, kids.reduce((s, k) => s + k.w, 0)); }
function place(n, x, d, out){ n.x = x + n.w / 2; n.y = 34 + d * H; out.push(n);
  if (open.has(n.id) && n.c){ let cx = x; n.c.forEach(k => { place(k, cx, d + 1, out); cx += k.w; }); } }
function path(n){ const a = []; for (let q = n; q; q = q.p) a.unshift(q.n); return a.join(" / "); }

function draw(){
  size(T); const ns = []; place(T, 0, 0, ns);
  const maxD = Math.max(...ns.map(n => Math.round((n.y - 34) / H))), vw = T.w + 20, vh = 34 + maxD * H + 40;
  svg.setAttribute("viewBox", `-10 0 ${vw} ${vh}`); svg.setAttribute("width", vw); svg.setAttribute("height", vh);
  let h = "";
  ns.forEach(n => { if (open.has(n.id) && n.c) n.c.forEach(k => {
    const y1 = n.y + 19, y2 = k.y - 19, m = (y1 + y2) / 2;
    h += `<path class="edge" d="M${n.x} ${y1} C${n.x} ${m},${k.x} ${m},${k.x} ${y2}"/>`; }); });
  ns.forEach(n => { const depth = Math.round((n.y - 34) / H), fill = depth === 0 ? "var(--n0)" : depth === 1 ? "var(--n1)" : "var(--n2)",
    stroke = depth === 0 ? "#7dd3fc" : "var(--line)", rx = W(n) / 2;
    h += `<g class="node${n === sel ? " sel" : ""}" data-id="${n.id}"><ellipse cx="${n.x}" cy="${n.y}" rx="${rx}" ry="19" fill="${fill}" stroke="${stroke}"/><text x="${n.x}" y="${n.y}">${n.n}</text>`;
    if (n.c) h += `<g class="tog"><circle cx="${n.x}" cy="${n.y + 19}" r="8"/><text x="${n.x}" y="${n.y + 19}">${open.has(n.id) ? "−" : "+"}</text></g>`;
    h += `</g>`; });
  svg.innerHTML = h;
  document.getElementById("wrap").scrollLeft = (document.getElementById("wrap").scrollWidth - document.getElementById("wrap").clientWidth) / 2;
}
function show(n){
  let h = `<h2>${n.n}</h2><div class="path">${path(n)}</div><p>${n.d || ""}</p>`;
  if (n.tags) h += `<div class="tags">${n.tags.map(t => `<span>${t}</span>`).join("")}</div>`;
  if (n.links) h += `<div class="links">${n.links.map((l, i) => `<a class="${i ? "alt" : ""}" href="${l[1]}" target="_blank" rel="noopener">${l[0]}</a>`).join("")}</div>`;
  panel.innerHTML = h;
}
const find = (n, i) => n.id === i ? n : (n.c || []).map(c => find(c, i)).find(Boolean);
svg.addEventListener("click", e => {
  const g = e.target.closest(".node"); if (!g) return;
  const n = find(T, +g.dataset.id); sel = n;
  if (n.c){ if (open.has(n.id)){ (function close(x){ open.delete(x.id); (x.c || []).forEach(close); })(n); }
    else { if (n.p) n.p.c.forEach(s => { if (s !== n) (function close(x){ open.delete(x.id); (x.c || []).forEach(close); })(s); }); open.add(n.id); } }
  draw(); show(n);
});
open.add(T.id); draw(); show(T);

const lines = ["AI & Machine Learning Engineer", "Backend & Cloud Developer", "Building systems that make difficult things easier"];
let li = 0, ci = 0, del = false; const el = document.getElementById("typed");
(function tick(){ const s = lines[li]; ci += del ? -1 : 1; el.textContent = s.slice(0, ci);
  let t = del ? 25 : 55; if (!del && ci === s.length){ del = true; t = 1500; } else if (del && ci === 0){ del = false; li = (li + 1) % lines.length; t = 300; }
  setTimeout(tick, t); })();
</script>
</body>
</html>
