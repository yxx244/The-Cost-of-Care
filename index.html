<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<title>The Cost of Care</title>
<style>
  :root{
    --bg:#f5f1e8; --ink:#292722; --muted:#777168; --card:#fffdf8;
    --line:#ddd5c7; --accent:#6d765c; --danger:#a65d52; --gold:#b68b4c;
  }
  *{box-sizing:border-box}
  body{margin:0;background:var(--bg);color:var(--ink);font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif}
  button{font:inherit}
  .screen{min-height:100vh;display:none;align-items:center;justify-content:center;padding:24px}
  .screen.active{display:flex}
  .tutorial-card{max-width:720px;width:100%;background:var(--card);border:1px solid var(--line);border-radius:26px;padding:30px;box-shadow:0 14px 40px #4c433015}.tutorial-card h2{font-family:Georgia,serif;font-size:42px;font-weight:500;margin:4px 0 8px}.rules{list-style:none;padding:0;margin:22px 0;text-align:left}.rules li{padding:11px 0 11px 34px;border-bottom:1px solid #eee8df;position:relative;color:#625b52;line-height:1.45}.rules li::before{content:"✓";position:absolute;left:5px;color:var(--accent);font-weight:900}.tutorial-pet{font-size:60px}.start-btn{border:0;border-radius:14px;background:#657053;color:#fff;padding:13px 34px;font-weight:800;cursor:pointer;font-size:16px}.intro{max-width:920px;width:100%;text-align:center}
  .eyebrow{font-size:12px;letter-spacing:.18em;text-transform:uppercase;color:var(--muted);margin-bottom:12px}
  h1{font-family:Georgia,serif;font-size:clamp(44px,9vw,82px);line-height:.95;margin:0 0 18px;font-weight:500}
  .subtitle{max-width:610px;margin:0 auto 30px;color:#655f56;line-height:1.65;font-size:16px}
  .cover{height:210px;border:1px solid var(--line);border-radius:26px;background:#eee7d9;position:relative;overflow:hidden;margin:0 auto 30px;max-width:700px;box-shadow:0 14px 40px #4c433015}
  .door{position:absolute;right:10%;bottom:0;width:34%;height:86%;background:#8a755e;border-radius:10px 10px 0 0}
  .door::after{content:"";position:absolute;left:12%;right:12%;top:17%;bottom:0;background:#20242b;border-radius:4px}
  .screenGlow{position:absolute;right:14%;top:34%;width:20%;height:28%;background:#d8c995;border-radius:3px;z-index:2;box-shadow:0 0 24px #d8c99566}
  .catCover{position:absolute;left:14%;bottom:20px;font-size:92px;z-index:3}
  .bowl{position:absolute;left:27%;bottom:20px;font-size:45px}
  .note{position:absolute;left:45%;top:24px;background:#d8c45e;padding:13px 18px;transform:rotate(-4deg);font-family:cursive;font-size:16px;box-shadow:0 6px 10px #00000018;z-index:4}
  .pet-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;max-width:760px;margin:auto}
  .pet-choice{border:1px solid var(--line);background:var(--card);border-radius:20px;padding:22px 16px;cursor:pointer;transition:.18s;box-shadow:0 8px 24px #4c43300d}
  .pet-choice:hover{transform:translateY(-3px);border-color:#b8ad9a}
  .pet-choice .emoji{font-size:55px;display:block;margin-bottom:8px}
  .pet-choice strong{display:block;font-size:20px}
  .pet-choice small{display:block;color:var(--muted);margin-top:6px;line-height:1.4}
  .game-wrap{width:100%;max-width:1180px;margin:auto}
  .topbar{display:flex;justify-content:space-between;align-items:center;gap:14px;margin-bottom:14px}
.diary-banner{display:none;margin:-4px 0 12px;padding:10px 14px;border:1px solid #d9cfbe;background:#f7f0df;border-radius:14px;color:#5f574d;font-family:Georgia,serif;font-size:14px;box-shadow:0 5px 14px #4c43300d}
.diary-banner.show{display:block}
.diary-banner strong{font-family:Inter,ui-sans-serif,system-ui,sans-serif;font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:#8a806f;margin-right:7px}
  .brand{font-family:Georgia,serif;font-size:25px}
  .round-info{text-align:center;flex:1}
  .round-label{font-size:12px;letter-spacing:.16em;text-transform:uppercase;color:var(--muted)}
  .round-number{font-size:19px;font-weight:700}
  .pet-badge{font-size:28px}
  .layout{display:grid;grid-template-columns:minmax(0,1fr) 270px;gap:18px}
  .board-card,.side-card{background:var(--card);border:1px solid var(--line);border-radius:24px;box-shadow:0 12px 35px #4c433012}
  .board-card{padding:16px}
  .board{height:min(68vh,650px);min-height:450px;position:relative;overflow:hidden;border-radius:18px;background:#e9e2d6;border:1px solid #d8cfbf}
  .tile{position:absolute;width:clamp(66px,8.2vw,92px);height:clamp(66px,8.2vw,92px);border-radius:18px;border:1px solid #d5cec1;background:#fff;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;box-shadow:0 7px 15px #40382d1c;cursor:pointer;user-select:none;touch-action:manipulation;transition:transform .15s,filter .15s,box-shadow .15s}
  .tile:hover{transform:translateY(-2px);box-shadow:0 10px 18px #40382d2a}
  .tile.blocked{filter:grayscale(.72) brightness(.93);box-shadow:0 4px 10px #40382d12}
  .tile .icon{font-size:30px;line-height:1}
  .tile .label{font-size:10px;font-weight:700;max-width:90%;text-align:center;line-height:1.05}
  .emoji-only .tile .icon{font-size:37px}
  .emoji-only .tile .label{display:none}
  .board-hint{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);color:#8d8579;text-align:center;pointer-events:none;opacity:.7}
  .side-card{padding:18px;height:max-content}
  .idea{font-size:13px;line-height:1.5;color:#6f675d;border-bottom:1px solid var(--line);padding-bottom:14px;margin-bottom:14px}
  .idea strong{color:var(--ink)}
  .side-title{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--muted);margin-bottom:9px}
  .sacrifice-list{min-height:110px}
  .sac{display:flex;justify-content:space-between;gap:10px;padding:7px 0;border-bottom:1px solid #eee8df;font-size:13px}
  .sac span:last-child{font-weight:700}
  .shuffle{width:100%;margin-top:16px;border:0;border-radius:14px;background:#657053;color:white;padding:13px 14px;font-weight:800;cursor:pointer}
  .shuffle:disabled{background:#c9c3b8;cursor:not-allowed}
  .restart{width:100%;margin-top:9px;border:1px solid var(--line);border-radius:14px;background:white;padding:11px;cursor:pointer}
  .slots-wrap{padding:14px 4px 2px}
  .slots-title{font-size:12px;text-transform:uppercase;letter-spacing:.12em;color:var(--muted);margin-bottom:9px}
  .slots{display:grid;grid-template-columns:repeat(7,1fr);gap:7px}
  .slot{height:67px;border:1px dashed #c9c0b2;border-radius:14px;background:#f9f6ef;display:flex;align-items:center;justify-content:center}
  .slot.filled{border-style:solid;background:white;box-shadow:0 4px 9px #40382d12}
  .slot .icon{font-size:26px}
  .slot .label{display:none}
  .progress{height:5px;background:#ddd6ca;border-radius:99px;overflow:hidden;margin-top:10px}
  .progress > div{height:100%;background:var(--accent);width:0%;transition:.2s}
  .modal{position:fixed;inset:0;background:#28251fcc;display:none;align-items:center;justify-content:center;padding:20px;z-index:5000}
  .modal.show{display:flex}
  .modal-card{width:min(560px,100%);background:#fffdf8;border-radius:26px;padding:28px;text-align:center;box-shadow:0 30px 80px #0004}
  .modal-card h2{font-family:Georgia,serif;font-size:38px;font-weight:500;margin:0 0 8px}
  .modal-card p{color:#696157;line-height:1.55}
  .state-visual{height:180px;background:#eee7da;border-radius:20px;margin:18px 0;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden}
  .state-main{font-size:92px}
  .state-extra{position:absolute;font-size:42px}
  .state-extra.a{left:18%;bottom:25px}.state-extra.b{right:18%;bottom:30px}
  .summary{background:#f3eee5;border-radius:15px;padding:13px;text-align:left;font-size:13px}
  .modal-actions{display:flex;gap:10px;margin-top:16px}
  .modal-actions button{flex:1;border-radius:14px;padding:13px;border:1px solid var(--line);cursor:pointer;background:white;font-weight:800}
  .modal-actions .primary{background:#657053;color:white;border-color:#657053}
  .toast{position:fixed;left:50%;bottom:24px;transform:translate(-50%,20px);background:#2d2b27;color:white;padding:12px 17px;border-radius:999px;font-size:13px;opacity:0;pointer-events:none;transition:.25s;z-index:6000}
  .toast.show{opacity:1;transform:translate(-50%,0)}
  @media(max-width:800px){
    .layout{grid-template-columns:1fr}
    .side-card{order:2}
    .board{height:58vh;min-height:410px}
    .pet-grid{grid-template-columns:1fr}
    .cover{height:175px}
    .topbar .brand{font-size:19px}
  }
  @media(max-width:520px){
    .screen{padding:16px}
    .board-card{padding:10px}
    .board{min-height:390px}
    .tile{width:68px;height:68px;border-radius:15px}
    .tile .icon{font-size:27px}
    .emoji-only .tile .icon{font-size:34px}
    .slots{gap:5px}
    .slot{height:57px}
    .slot .icon{font-size:22px}
  }
</style>
</head>
<body>

<section id="intro" class="screen active">
  <div class="intro">
    <div class="eyebrow">An economics game about scarcity & tradeoffs</div>
    <h1>The Cost of Care</h1>
    <p class="subtitle">You have limited time. Your pet has needs. Work, rest, care, and scrolling all compete for the same seven slots.</p>
    <div class="cover">
      <div class="door"></div><div class="screenGlow"></div>
      <div class="catCover">🐱</div><div class="bowl">🥣</div>
      <div class="note">I'll play with you tomorrow.</div>
    </div>
    <p style="margin:0 0 15px;font-weight:800">Who are you caring for?</p>
    <div class="pet-grid">
      <button class="pet-choice" data-pet="cat"><span class="emoji">🐱</span><strong>Cat</strong><small>Independent, but picky</small></button>
      <button class="pet-choice" data-pet="dog"><span class="emoji">🐶</span><strong>Dog</strong><small>High interaction, high energy</small></button>
      <button class="pet-choice" data-pet="bird"><span class="emoji">🐦</span><strong>Bird</strong><small>Smart, social, easily understimulated</small></button>
    </div>
  </div>
</section>

<section id="tutorial" class="screen">
  <div class="tutorial-card">
    <div class="tutorial-pet" id="tutorialPet">🐱</div>
    <div class="eyebrow">Before you begin</div>
    <h2>How to Play</h2>
    <ul class="rules">
      <li>Tap a tile to place it in one of the 7 slots below.</li>
      <li>Match 3 identical tiles to clear them.</li>
      <li>If all 7 slots are full and no matches can be made, the game ends.</li>
      <li>Every tile you place represents a choice — and every choice costs you something.</li>
      <li>At the end of each round, you'll see what your pet gave up.</li>
      <li>You can use the Shuffle button once per round.</li>
    </ul>
    <button id="startBtn" class="start-btn">Start</button>
  </div>
</section>

<section id="game" class="screen">
  <div class="game-wrap">
    <div class="topbar">
      <div class="brand">The Cost of Care</div>
      <div class="round-info"><div class="round-label" id="roundLabel">Round</div><div class="round-number" id="roundNumber">1</div></div>
      <div class="pet-badge" id="petBadge">🐱</div>
    </div>
    <div id="diaryBanner" class="diary-banner"><strong>Yesterday, your pet wrote:</strong><span id="diaryText"></span></div>
    <div class="layout">
      <div class="board-card">
        <div id="board" class="board"></div>
        <div class="slots-wrap">
          <div class="slots-title">Your seven time slots</div>
          <div id="slots" class="slots"></div>
          <div class="progress"><div id="slotProgress"></div></div>
        </div>
      </div>
      <aside class="side-card">
        <div class="idea"><strong>The idea:</strong> You cannot do everything. Every choice uses scarce time, so choosing one thing means giving up another.</div>
        <div class="side-title">Opportunity cost</div>
        <div id="sacrificeList" class="sacrifice-list"></div>
        <button id="shuffleBtn" class="shuffle">Shuffle · 1 left</button>
        <button id="restartBtn" class="restart">Try Again</button>
      </aside>
    </div>
  </div>
</section>

<div id="modal" class="modal">
  <div class="modal-card">
    <div class="eyebrow" id="modalEyebrow">Day Complete</div>
    <h2 id="modalTitle">Day Complete</h2>
    <div id="stateVisual" class="state-visual"></div>
    <p id="modalText"></p>
    <div id="modalSummary" class="summary" style="display:none"></div>
    <div id="modalDiary" class="summary" style="display:none;margin-top:10px"><strong>Pet's diary:</strong> <span id="modalDiaryText"></span></div>
    <div id="modalScore" class="summary" style="display:none;margin-top:10px"></div>
    <div class="modal-actions" id="modalActions" style="display:none">
      <button id="modalRestart">Try Again</button>
      <button id="modalNext" class="primary">Next Day?</button>
    </div>
  </div>
</div>
<div id="toast" class="toast"></div>

<script>
const PETS = {
  cat: {
    name:"Cat", emoji:"🐱",
    activities:[
      ["feed","🍽️","Feed"],["litter","🧹","Scoop Litter"],["play","🎾","Play"],["alone","🛋️","Leave Alone"],
      ["sleep","💤","My Sleep"],["work","💼","Work"],["phone","📱","Scroll Phone"],["vet","🏥","Vet"]
    ],
    weights:["feed","litter","play","alone","sleep","work","phone","vet"]
  },
  dog: {
    name:"Dog", emoji:"🐶",
    activities:[
      ["walk","🚶","Walk"],["feed","🍖","Feed"],["play","🎾","Play"],["bath","🛁","Bath"],
      ["sleep","💤","My Sleep"],["work","💼","Work"],["phone","📱","Scroll Phone"],["vet","🏥","Vet"]
    ],
    weights:["walk","feed","play","bath","sleep","work","phone","vet"]
  },
  bird: {
    name:"Bird", emoji:"🐦",
    activities:[
      ["feed","🍎","Feed"],["talk","🗣️","Talk"],["toys","🧸","Toys"],["cage","🧹","Clean Cage"],
      ["sleep","💤","My Sleep"],["work","💼","Work"],["phone","📱","Scroll Phone"],["vet","🏥","Vet"]
    ],
    weights:["feed","talk","toys","cage","sleep","work","phone","vet"]
  }
};

let petKey=null, round=1, tiles=[], slots=[], sacrifices={}, choicesMade={}, shuffleLeft=1, gameOver=false, inTutorial=true, totalScore=0, roundMatches=0, roundShuffles=0, lastDiary="";

const $=id=>document.getElementById(id);
const rand=(a,b)=>Math.random()*(b-a)+a;
const shuffle=a=>{for(let i=a.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[a[i],a[j]]=[a[j],a[i]]}return a};

function choosePet(key){
  petKey=key; round=1; inTutorial=true; totalScore=0; lastDiary=""; choicesMade={}; sacrifices={};
  $('intro').classList.remove('active'); $('game').classList.remove('active'); $('tutorial').classList.add('active');
  $('tutorialPet').textContent=PETS[key].emoji;
}

document.querySelectorAll('.pet-choice').forEach(b=>b.addEventListener('click',()=>choosePet(b.dataset.pet)));
$('startBtn').onclick=()=>{inTutorial=false; $('tutorial').classList.remove('active'); $('game').classList.add('active'); startRound()};
$('restartBtn').onclick=()=>startRound();
$('shuffleBtn').onclick=doShuffle;
$('modalRestart').onclick=()=>{closeModal();startRound()};
$('modalNext').onclick=()=>{const diary=diaryFor(topSacrifice()); lastDiary=diary; closeModal(); round++; startRound(); showDiary(diary)};

function activityMap(){
  const m={}; PETS[petKey].activities.forEach(a=>m[a[0]]={id:a[0],icon:a[1],name:a[2]}); return m;
}

function tileCount(){
  if(round===1)return 18;
  return Math.min(96, 42+(round-2)*8);
}

/* A triple-first sequence guarantees that a valid removal order exists:
   each group can be cleared together, so the slot count never needs to
   exceed two unmatched pieces. Physical board placement is randomized
   independently. */
function buildTiles(){
  const acts=PETS[petKey].activities.map(a=>a[0]);
  const count=tileCount(), groups=Math.floor(count/3), ids=[];
  for(let g=0;g<groups;g++){
    const id=acts[g%acts.length];
    ids.push(id,id,id);
  }
  shuffle(ids);
  const map=activityMap();
  tiles=ids.map((id,i)=>({uid:i,id,...map[id],x:0,y:0,order:i,removed:false}));
  placeTiles();
}

function placeTiles(){
  const board=$('board'), rect=board.getBoundingClientRect();
  const w=Math.max(320,rect.width), h=Math.max(390,rect.height);
  const n=tiles.length;
  const cols=Math.max(4,Math.min(9,Math.ceil(Math.sqrt(n*1.35))));
  const rows=Math.ceil(n/cols);
  const cellW=w/cols, cellH=h/rows;
  const clusterStrength=Math.min(.48,.14+round*.025);
  tiles.forEach((t,i)=>{
    const r=Math.floor(i/cols), c=i%cols;
    let x=(c+.5)*cellW, y=(r+.5)*cellH;
    // Dense clusters and occasional deep overlap.
    const clusterX = Math.sin(i*2.17)*cellW*clusterStrength;
    const clusterY = Math.cos(i*1.71)*cellH*clusterStrength;
    x+=clusterX+rand(-cellW*.22,cellW*.22);
    y+=clusterY+rand(-cellH*.22,cellH*.22);
    if(i%11===0){x+=cellW*.25;y+=cellH*.2}
    t.x=Math.max(2,Math.min(w-72,x-40));
    t.y=Math.max(2,Math.min(h-72,y-40));
    t.order=i;
  });
}

function startRound(){
  gameOver=false; shuffleLeft=1; slots=[]; sacrifices={}; choicesMade={}; roundMatches=0; roundShuffles=0;
  $('diaryBanner').classList.remove('show');
  $('shuffleBtn').disabled=false; $('shuffleBtn').textContent='Shuffle · 1 left';
  $('roundNumber').textContent=round;
  $('roundLabel').textContent=round<=6?'Challenge Round':'Hard Mode';
  $('petBadge').textContent=PETS[petKey].emoji;
  buildTiles(); renderAll();
}

function renderAll(){
  const board=$('board');
  board.innerHTML='';
  board.classList.toggle('emoji-only',round>=7);
  const active=tiles.filter(t=>!t.removed);
  active.forEach(t=>{
    const el=document.createElement('button');
    el.className='tile';
    el.dataset.uid=t.uid;
    el.style.left=t.x+'px'; el.style.top=t.y+'px'; el.style.zIndex=1000-t.order;
    el.innerHTML=`<span class="icon">${t.icon}</span><span class="label">${t.name}</span>`;
    if(isBlocked(t))el.classList.add('blocked');
    el.onclick=()=>clickTile(t.uid);
    board.appendChild(el);
  });
  const hint=active.length?null:document.createElement('div');
  if(hint){hint.className='board-hint';hint.textContent='';board.appendChild(hint)}
  renderSlots(); renderSacrifices();
}

function rectForTile(t){
  const board=$('board').getBoundingClientRect();
  const tileW=parseFloat(getComputedStyle(document.querySelector('.tile')||document.body).width)||80;
  const tileH=tileW;
  return {left:board.left+t.x,top:board.top+t.y,right:board.left+t.x+tileW,bottom:board.top+t.y+tileH};
}
function overlaps(a,b){
  return a.left < b.right && a.right > b.left && a.top < b.bottom && a.bottom > b.top;
}
function isBlocked(t){
  const r=rectForTile(t);
  return tiles.some(o=>!o.removed && o.uid!==t.uid && o.order<t.order && overlaps(r,rectForTile(o)));
}

function clickTile(uid){
  if(gameOver)return;
  const t=tiles.find(x=>x.uid===uid); if(!t||t.removed)return;
  if(isBlocked(t)){showToast('That piece is blocked.');return}
  if(slots.length>=7){loseRound();return}
  t.removed=true;
  slots.push(t);
  choicesMade[t.id]=(choicesMade[t.id]||0)+1;
  recordSacrifice(t.id);
  const same=slots.filter(s=>s.id===t.id);
  if(same.length===3){
    roundMatches++;
    totalScore += 10;
    const keep=[]; let removedThree=0;
    for(const s of slots){
      if(s.id===t.id && removedThree<3){removedThree++} else keep.push(s);
    }
    slots=keep;
    showToast(`${t.icon} ${t.name} completed.`);
  }
  renderAll();
  if(tiles.every(t=>t.removed) && slots.length===0){winRound();return}
  if(slots.length>=7 && !canClearTriple()){loseRound();}
}

function canClearTriple(){
  const counts={};slots.forEach(s=>counts[s.id]=(counts[s.id]||0)+1);
  return Object.values(counts).some(n=>n>=3);
}
function recordSacrifice(chosen){
  // Opportunity cost is a choice among activities that remain available.
  const options=PETS[petKey].activities.map(a=>a[0]).filter(id=>id!==chosen);
  if(!options.length)return;
  const weights={};
  options.forEach(id=>weights[id]=1);
  // Give meaningful activities slightly more visibility in the summary.
  const pick=options[Math.floor(Math.random()*options.length)];
  sacrifices[pick]=(sacrifices[pick]||0)+1;
}

function renderSlots(){
  const s=$('slots');s.innerHTML='';
  for(let i=0;i<7;i++){
    const d=document.createElement('div');d.className='slot'+(slots[i]?' filled':'');
    if(slots[i])d.innerHTML=`<span class="icon">${slots[i].icon}</span>`;
    s.appendChild(d);
  }
  $('slotProgress').style.width=(slots.length/7*100)+'%';
}
function renderSacrifices(){
  const box=$('sacrificeList');box.innerHTML='';
  const entries=Object.entries(sacrifices).sort((a,b)=>b[1]-a[1]);
  if(!entries.length){box.innerHTML='<div style="color:#8b8379;font-size:13px;padding:8px 0">Your tradeoffs will appear here.</div>';return}
  const map=activityMap();
  entries.slice(0,5).forEach(([id,n])=>{
    const d=document.createElement('div');d.className='sac';
    d.innerHTML=`<span>${map[id].icon} ${map[id].name}</span><span>${n}×</span>`;box.appendChild(d);
  });
}
function doShuffle(){
  if(!shuffleLeft||gameOver)return;
  shuffleLeft=0;
  roundShuffles++;
  totalScore -= 5;
  const active=tiles.filter(t=>!t.removed);
  shuffle(active);
  active.forEach((t,i)=>t.order=i);
  placeTiles();
  $('shuffleBtn').disabled=true;$('shuffleBtn').textContent='Shuffle · 0 left';
  renderAll();
  showToast('The remaining board was shuffled.');
}

function topSacrifice(){
  const entries=Object.entries(sacrifices).sort((a,b)=>b[1]-a[1]);
  return entries[0]?.[0]||null;
}

function stateFor(id){
  const scenes={
    cat:{
      feed:{main:'🐱',extra:['🥣','👀'],text:'The bowl is empty. Your cat sits beside it and looks up, waiting.'},
      litter:{main:'🐱',extra:['🧹','💩'],text:'The litter box was ignored. Your cat starts scratching outside it.'},
      play:{main:'🐱',extra:['🎾','👣'],text:'Your cat brings you a toy and waits at your feet. Its tail flicks slowly.'},
      alone:{main:'🐱',extra:['🛋️','👀'],text:'You gave up the quiet time your cat wanted. It disappears under the sofa.'},
      sleep:{main:'😴',extra:['🐱','💤'],text:'You gave up your own sleep. Your cat is awake while you are running on empty.'},
      work:{main:'🐱',extra:['🚪','💼'],text:'You chose work. Your cat watches from the door as you leave with your bag.'},
      phone:{main:'🐱',extra:['📱','👀'],text:'Your cat is on your lap, but your attention is on the phone.'},
      vet:{main:'🐱',extra:['🏥','🧺'],text:'Health was pushed aside. Your cat curls up quietly in the corner.'}
    },
    dog:{
      walk:{main:'🐶',extra:['🚪','🦮'],text:'The leash stays by the door. Your dog sits there, waiting for a walk.'},
      feed:{main:'🐶',extra:['🥣','👅'],text:'The bowl is empty. Your dog lies beside it, still hoping for food.'},
      play:{main:'🐶',extra:['🎾','🐾'],text:'Your dog brings you a ball and waits. The tail that was wagging slows down.'},
      bath:{main:'🐶',extra:['🛁','😖'],text:'Bath time kept getting postponed. Your dog is visibly dirty, and you keep your distance.'},
      sleep:{main:'😴',extra:['🐶','☀️'],text:'You gave up your own sleep. Your dog is ready for the day before you are.'},
      work:{main:'🐶',extra:['🚪','💼'],text:'You chose work. Your dog watches from the door as you leave with your bag.'},
      phone:{main:'🐶',extra:['🎾','📱'],text:'Your dog puts a ball at your feet while your attention stays on your phone.'},
      vet:{main:'🐶',extra:['🏥','🧺'],text:'Health was pushed aside. Your dog curls up quietly with its ears lowered.'}
    },
    bird:{
      feed:{main:'🐦',extra:['🥣','👀'],text:'The food dish is empty. Your bird tilts its head beside it.'},
      talk:{main:'🐦',extra:['🗣️','🙉'],text:'Your bird becomes loud in the cage because the attention it wanted never came.'},
      toys:{main:'🐦',extra:['🧸','🪶'],text:'There are no toys in the cage. Your bird pecks at the bars instead.'},
      cage:{main:'🐦',extra:['🧹','🪶'],text:'The cage was left uncleaned. Your bird stays on the highest perch.'},
      sleep:{main:'😴',extra:['🐦','☀️'],text:'Your bird starts the morning before you are ready. Your lost sleep catches up with you.'},
      work:{main:'🐦',extra:['🚪','💼'],text:'You chose work. Your bird watches you leave while the cage stays closed and quiet.'},
      phone:{main:'🐦',extra:['📱','↩️'],text:'Your bird watches you scroll, then turns its head away.'},
      vet:{main:'🐦',extra:['🏥','🪶'],text:'Health was pushed aside. Your bird stays quietly in the corner of its cage.'}
    }
  };
  return scenes[petKey][id] || {main:PETS[petKey].emoji,extra:['⏰','🐾'],text:'Another need had to wait because your time was limited.'};
}

let revealTimer=null;
function revealResult(){
  clearTimeout(revealTimer);
  $('modalSummary').style.display='block';
  $('modalActions').style.display='flex';
}
function prepareModal(){
  clearTimeout(revealTimer);
  $('modalSummary').style.display='none';
  $('modalActions').style.display='none';
  revealTimer=setTimeout(revealResult,2500);
}


function diaryFor(id){
  const p=petKey;
  const lines={
    walk:"I waited by the door for a long time today.",
    play:"I put my ball at your feet, but you didn't see it.",
    feed:"The bowl is empty.",
    sleep:"You look really tired.",
    work:"You left again.",
    vet:"I don't feel very good.",
    litter:"I didn't like the litter box today.",
    alone:"I hid because I wanted some quiet.",
    bath:"I really needed that bath.",
    talk:"I called for you, but the room was quiet.",
    toys:"I looked for my toys, but they weren't there.",
    cage:"My cage needed cleaning today.",
    phone:"I watched you look at your phone instead of me."
  };
  return lines[id] || "I noticed you had to choose."
}
function showDiary(text){
  if(!text)return;
  $('diaryText').textContent='“'+text+'”';
  $('diaryBanner').classList.add('show');
}
function listChoices(obj){
  const map=activityMap();
  const entries=Object.entries(obj).sort((a,b)=>b[1]-a[1]);
  if(!entries.length)return 'None';
  return entries.slice(0,5).map(([k,v])=>`${map[k].icon} ${map[k].name} ${v}×`).join(' · ');
}
function scoreBreakdown(){
  const matchPts=roundMatches*10, completionPts=20, shufflePts=roundShuffles*5;
  return `<strong>Score: ${totalScore}</strong><br><span style="color:#6f675d">Matches: ${roundMatches} × 10 = ${matchPts} &nbsp;|&nbsp; Completion: +20 &nbsp;|&nbsp; Shuffles: −${shufflePts}</span>`;
}
function showReward(){
  const id=topSacrifice(), st=stateFor(id), diary=diaryFor(id);
  totalScore += 20;
  $('modalEyebrow').textContent=`${PETS[petKey].name} · Day ${round}`;
  $('modalTitle').textContent='Day Complete';
  $('stateVisual').innerHTML=`<div class="state-main">${st.main}</div><div class="state-extra a">${st.extra[0]}</div><div class="state-extra b">${st.extra[1]}</div>`;
  $('modalText').textContent='Your time was limited. Here is what your choices added up to today.';
  $('modalSummary').innerHTML=`<strong>What you did:</strong><br>${listChoices(choicesMade)}<br><br><strong>What you gave up:</strong><br>${listChoices(sacrifices)}`;
  $('modalDiaryText').textContent=diary;
  $('modalScore').innerHTML=scoreBreakdown();
  $('modalRestart').textContent='Try Again';
  $('modalNext').textContent='Next Day?';
  $('modalNext').style.display='block';
  $('modal').classList.add('show');
  prepareModal();
}
function winRound(){
  gameOver=true;
  showReward();
}
function loseRound(){
  if(gameOver)return;
  gameOver=true;
  $('modalEyebrow').textContent='Out of time';
  $('modalTitle').textContent='The seven slots are full.';
  $('stateVisual').innerHTML=`<div class="state-main">${PETS[petKey].emoji}</div><div class="state-extra a">⏰</div><div class="state-extra b">🧺</div>`;
  $('modalText').textContent='Scarcity means some choices have to wait. This round ran out of room before everything could be done.';
  $('modalSummary').innerHTML=`<strong>What you did:</strong><br>${listChoices(choicesMade)}<br><br><strong>What you gave up:</strong><br>${listChoices(sacrifices)}`;
  $('modalDiary').style.display='none';
  $('modalScore').innerHTML=scoreBreakdown();
  $('modalRestart').textContent='Try Again';
  $('modalNext').style.display='none';
  $('modal').classList.add('show');
  prepareModal();
}
function prepareModal(){
  clearTimeout(revealTimer);
  $('modalSummary').style.display='none';
  $('modalDiary').style.display='none';
  $('modalScore').style.display='none';
  $('modalActions').style.display='none';
  revealTimer=setTimeout(()=>{
    $('modalSummary').style.display='block';
    $('modalDiary').style.display=gameOver && $('modalTitle').textContent==='Day Complete'?'block':'none';
    $('modalScore').style.display='block';
    $('modalActions').style.display='flex';
  },2500);
}
function closeModal(){
  clearTimeout(revealTimer);
  $('modal').classList.remove('show');
  $('modalSummary').style.display='none';
  $('modalDiary').style.display='none';
  $('modalScore').style.display='none';
  $('modalActions').style.display='none';
  $('modalNext').style.display='block';
}
let toastTimer;
function showToast(msg){
  const t=$('toast');t.textContent=msg;t.classList.add('show');
  clearTimeout(toastTimer);toastTimer=setTimeout(()=>t.classList.remove('show'),1400);
}
window.addEventListener('resize',()=>{if($('game').classList.contains('active')&&!gameOver){placeTiles();renderAll()}});

</script>
</body>
</html>