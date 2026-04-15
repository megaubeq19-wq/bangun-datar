<!doctype html>
<html lang="id" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Belajar Bangun Datar</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Fredoka', sans-serif; }
    html, body { height: 100%; margin: 0; }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
    }
    @keyframes popIn {
      0% { transform: scale(0); opacity: 0; }
      70% { transform: scale(1.1); }
      100% { transform: scale(1); opacity: 1; }
    }
    @keyframes sparkle {
      0%, 100% { opacity: 1; transform: scale(1); }
      50% { opacity: 0.5; transform: scale(1.3); }
    }
    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes bounce {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.15); }
    }
    @keyframes confetti {
      0% { transform: translateY(0) rotate(0deg); opacity: 1; }
      100% { transform: translateY(-120px) rotate(720deg); opacity: 0; }
    }
    .float { animation: float 3s ease-in-out infinite; }
    .pop-in { animation: popIn 0.5s ease-out forwards; }
    .slide-up { animation: slideUp 0.4s ease-out forwards; }
    .sparkle { animation: sparkle 1.5s ease-in-out infinite; }
    .card-hover { transition: all 0.3s ease; }
    .card-hover:hover { transform: translateY(-6px) scale(1.03); box-shadow: 0 12px 30px rgba(0,0,0,0.15); }
    .btn-bounce:active { animation: bounce 0.3s ease; }

    .shape-svg { filter: drop-shadow(2px 4px 6px rgba(0,0,0,0.15)); }

    .quiz-option { transition: all 0.2s ease; }
    .quiz-option:hover { transform: scale(1.05); }
    .quiz-option.correct { background: #22c55e !important; color: white !important; animation: bounce 0.4s ease; }
    .quiz-option.wrong { background: #ef4444 !important; color: white !important; }

    .tab-active { background: #6d28d9; color: white; box-shadow: 0 4px 15px rgba(109,40,217,0.4); }
    .tab-inactive { background: #ede9fe; color: #6d28d9; }

    .progress-fill { transition: width 0.5s ease; }
  </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full">
  <div id="app" class="w-full h-full overflow-auto" style="background: linear-gradient(135deg, #fef3c7 0%, #fce7f3 30%, #ddd6fe 60%, #ccfbf1 100%);"><!-- Header -->
   <header class="text-center pt-6 pb-4 px-4">
    <div class="flex items-center justify-center gap-2 mb-1"><span class="text-3xl sparkle">✨</span>
     <h1 id="mainTitle" class="text-3xl md:text-4xl font-bold text-purple-700 drop-shadow">Belajar Bangun Datar</h1><span class="text-3xl sparkle" style="animation-delay:0.5s">✨</span>
    </div>
    <p id="mainSubtitle" class="text-lg text-purple-500 font-medium">Kelas 3 SD</p>
    <div class="flex justify-center gap-1 mt-2 text-2xl"><span class="float" style="animation-delay:0s">📐</span> <span class="float" style="animation-delay:0.3s">📏</span> <span class="float" style="animation-delay:0.6s">🔺</span> <span class="float" style="animation-delay:0.9s">⬟</span> <span class="float" style="animation-delay:1.2s">⭐</span>
    </div>
   </header><!-- Tabs -->
   <nav class="flex justify-center gap-2 px-4 mb-6 flex-wrap" role="tablist"><button onclick="switchTab('belajar')" id="tab-belajar" class="tab-active px-5 py-2.5 rounded-full font-semibold text-sm btn-bounce" role="tab">📚 Belajar</button> <button onclick="switchTab('hitung')" id="tab-hitung" class="tab-inactive px-5 py-2.5 rounded-full font-semibold text-sm btn-bounce" role="tab">🧮 Hitung</button> <button onclick="switchTab('kuis')" id="tab-kuis" class="tab-inactive px-5 py-2.5 rounded-full font-semibold text-sm btn-bounce" role="tab">🎯 Kuis</button>
   </nav><!-- Tab Content -->
   <main class="px-4 pb-10 max-w-4xl mx-auto"><!-- BELAJAR TAB -->
    <section id="content-belajar">
     <div class="grid grid-cols-2 md:grid-cols-3 gap-4" id="shapeGrid"></div><!-- Shape Detail Modal -->
     <div id="shapeModal" class="hidden fixed inset-0 z-50 flex items-center justify-center p-4" style="background:rgba(0,0,0,0.4)">
      <div class="bg-white rounded-3xl p-6 max-w-md w-full max-h-[85%] overflow-auto slide-up shadow-2xl relative"><button onclick="closeModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">✕</button>
       <div id="modalContent"></div>
      </div>
     </div>
    </section><!-- HITUNG TAB -->
    <section id="content-hitung" class="hidden">
     <div class="bg-white/80 backdrop-blur rounded-3xl p-6 shadow-lg">
      <h2 class="text-xl font-bold text-purple-700 mb-4 text-center">🧮 Kalkulator Bangun Datar</h2><label class="block text-sm font-semibold text-purple-600 mb-2">Pilih Bangun:</label>
      <div class="grid grid-cols-3 gap-2 mb-5" id="calcShapeSelector"></div>
      <div id="calcInputs" class="space-y-3 mb-5"></div>
      <div id="calcResult" class="text-center p-4 rounded-2xl bg-purple-50 hidden">
       <p class="text-sm text-purple-500 font-medium">Hasil:</p>
       <p id="calcResultText" class="text-2xl font-bold text-purple-700"></p>
      </div>
     </div>
    </section><!-- KUIS TAB -->
    <section id="content-kuis" class="hidden">
     <div class="bg-white/80 backdrop-blur rounded-3xl p-6 shadow-lg">
      <div id="quizHeader" class="flex items-center justify-between mb-4">
       <h2 class="text-xl font-bold text-purple-700">🎯 Kuis</h2><span id="quizScore" class="text-sm font-bold bg-yellow-100 text-yellow-700 px-3 py-1 rounded-full">⭐ 0/0</span>
      </div>
      <div class="w-full bg-purple-100 rounded-full h-3 mb-5">
       <div id="quizProgress" class="progress-fill bg-gradient-to-r from-purple-500 to-pink-500 h-3 rounded-full" style="width:0%"></div>
      </div>
      <div id="quizArea"></div>
     </div>
    </section>
   </main>
  </div>
  <script>
const shapes = [
  {
    name: "Persegi", emoji: "🟦", color: "#3b82f6", bgColor: "#dbeafe",
    desc: "Bangun datar yang memiliki 4 sisi sama panjang dan 4 sudut siku-siku (90°).",
    rumusK: "K = 4 × s", rumusL: "L = s × s",
    contoh: "Ubin lantai, buku tulis, papan catur ♟️",
    sifat: ["4 sisi sama panjang", "4 sudut siku-siku (90°)", "2 diagonal sama panjang"],
    inputs: [{id:"s",label:"Sisi (s)",ph:"cm"}],
    calc: (v) => ({keliling: 4*v.s, luas: v.s*v.s}),
    svg: `<svg viewBox="0 0 100 100" class="shape-svg w-20 h-20"><rect x="10" y="10" width="80" height="80" rx="4" fill="#3b82f6" stroke="#1d4ed8" stroke-width="3"/><text x="50" y="55" text-anchor="middle" fill="white" font-size="14" font-weight="bold">s</text></svg>`
  },
  {
    name: "Persegi Panjang", emoji: "🟩", color: "#22c55e", bgColor: "#dcfce7",
    desc: "Bangun datar yang memiliki 2 pasang sisi sejajar sama panjang dan 4 sudut siku-siku.",
    rumusK: "K = 2 × (p + l)", rumusL: "L = p × l",
    contoh: "Pintu rumah 🚪, meja, layar HP 📱",
    sifat: ["2 pasang sisi sejajar", "4 sudut siku-siku", "Diagonal sama panjang"],
    inputs: [{id:"p",label:"Panjang (p)",ph:"cm"},{id:"l",label:"Lebar (l)",ph:"cm"}],
    calc: (v) => ({keliling: 2*(v.p+v.l), luas: v.p*v.l}),
    svg: `<svg viewBox="0 0 120 80" class="shape-svg w-24 h-16"><rect x="5" y="5" width="110" height="70" rx="4" fill="#22c55e" stroke="#15803d" stroke-width="3"/><text x="60" y="45" text-anchor="middle" fill="white" font-size="13" font-weight="bold">p × l</text></svg>`
  },
  {
    name: "Segitiga", emoji: "🔺", color: "#ef4444", bgColor: "#fee2e2",
    desc: "Bangun datar yang memiliki 3 sisi dan 3 sudut. Jumlah semua sudutnya 180°.",
    rumusK: "K = a + b + c", rumusL: "L = ½ × a × t",
    contoh: "Atap rumah 🏠, penggaris segitiga 📐, irisan pizza 🍕",
    sifat: ["3 sisi", "3 sudut", "Jumlah sudut = 180°"],
    inputs: [{id:"a",label:"Alas (a)",ph:"cm"},{id:"t",label:"Tinggi (t)",ph:"cm"}],
    calc: (v) => ({keliling: null, luas: 0.5*v.a*v.t}),
    svg: `<svg viewBox="0 0 100 100" class="shape-svg w-20 h-20"><polygon points="50,10 10,90 90,90" fill="#ef4444" stroke="#b91c1c" stroke-width="3"/><text x="50" y="70" text-anchor="middle" fill="white" font-size="12" font-weight="bold">½×a×t</text></svg>`
  },
  {
    name: "Lingkaran", emoji: "🔵", color: "#8b5cf6", bgColor: "#ede9fe",
    desc: "Bangun datar yang terdiri dari titik-titik yang berjarak sama dari pusat. Tidak memiliki sudut.",
    rumusK: "K = 2 × π × r", rumusL: "L = π × r × r",
    contoh: "Roda sepeda 🚲, koin 🪙, jam dinding 🕐",
    sifat: ["Tidak punya sudut", "1 sisi lengkung", "Diameter = 2 × jari-jari"],
    inputs: [{id:"r",label:"Jari-jari (r)",ph:"cm"}],
    calc: (v) => ({keliling: 2*Math.PI*v.r, luas: Math.PI*v.r*v.r}),
    svg: `<svg viewBox="0 0 100 100" class="shape-svg w-20 h-20"><circle cx="50" cy="50" r="42" fill="#8b5cf6" stroke="#6d28d9" stroke-width="3"/><text x="50" y="55" text-anchor="middle" fill="white" font-size="14" font-weight="bold">r</text></svg>`
  },
  {
    name: "Trapesium", emoji: "⏢", color: "#f59e0b", bgColor: "#fef3c7",
    desc: "Bangun datar segiempat yang memiliki tepat sepasang sisi sejajar.",
    rumusK: "K = jumlah semua sisi", rumusL: "L = ½ × (a + b) × t",
    contoh: "Tas tangan 👜, ember 🪣, atap joglo",
    sifat: ["4 sisi", "1 pasang sisi sejajar", "Sudut bervariasi"],
    inputs: [{id:"a",label:"Sisi sejajar a",ph:"cm"},{id:"b",label:"Sisi sejajar b",ph:"cm"},{id:"t",label:"Tinggi (t)",ph:"cm"}],
    calc: (v) => ({keliling: null, luas: 0.5*(v.a+v.b)*v.t}),
    svg: `<svg viewBox="0 0 120 80" class="shape-svg w-24 h-16"><polygon points="30,10 90,10 110,70 10,70" fill="#f59e0b" stroke="#b45309" stroke-width="3"/><text x="60" y="48" text-anchor="middle" fill="white" font-size="11" font-weight="bold">½(a+b)t</text></svg>`
  },
  {
    name: "Layang-layang", emoji: "🪁", color: "#ec4899", bgColor: "#fce7f3",
    desc: "Bangun datar yang memiliki 2 pasang sisi berdekatan yang sama panjang.",
    rumusK: "K = 2 × (s₁ + s₂)", rumusL: "L = ½ × d₁ × d₂",
    contoh: "Layang-layang 🪁, motif batik, permata 💎",
    sifat: ["2 pasang sisi sama panjang", "1 pasang sudut berhadapan sama", "Diagonal tegak lurus"],
    inputs: [{id:"d1",label:"Diagonal 1 (d₁)",ph:"cm"},{id:"d2",label:"Diagonal 2 (d₂)",ph:"cm"}],
    calc: (v) => ({keliling: null, luas: 0.5*v.d1*v.d2}),
    svg: `<svg viewBox="0 0 100 120" class="shape-svg w-20 h-24"><polygon points="50,5 85,40 50,115 15,40" fill="#ec4899" stroke="#be185d" stroke-width="3"/><text x="50" y="55" text-anchor="middle" fill="white" font-size="11" font-weight="bold">½d₁d₂</text></svg>`
  }
];

// Quiz questions
const quizQuestions = [
  {q:"Bangun datar yang memiliki 4 sisi sama panjang adalah...", opts:["Persegi Panjang","Segitiga","Persegi","Lingkaran"], ans:2, emoji:"🤔"},
  {q:"Berapa jumlah sudut pada segitiga?", opts:["2","3","4","5"], ans:1, emoji:"🔺"},
  {q:"Rumus luas persegi panjang adalah...", opts:["s × s","p × l","½ × a × t","π × r²"], ans:1, emoji:"📐"},
  {q:"Bangun datar yang tidak memiliki sudut adalah...", opts:["Persegi","Segitiga","Trapesium","Lingkaran"], ans:3, emoji:"🔵"},
  {q:"Rumus keliling persegi adalah...", opts:["4 × s","2 × (p+l)","π × d","s × s"], ans:0, emoji:"🟦"},
  {q:"Layang-layang memiliki berapa pasang sisi sama panjang?", opts:["1","2","3","4"], ans:1, emoji:"🪁"},
  {q:"Trapesium memiliki berapa pasang sisi sejajar?", opts:["0","1","2","4"], ans:1, emoji:"⏢"},
  {q:"Rumus luas segitiga adalah...", opts:["a × t","½ × a × t","a + b + c","2 × a × t"], ans:1, emoji:"🔺"},
  {q:"Contoh benda persegi panjang di rumah adalah...", opts:["Bola","Pintu","Roda","Koin"], ans:1, emoji:"🏠"},
  {q:"Jumlah sudut dalam segitiga adalah... derajat", opts:["90","180","270","360"], ans:1, emoji:"📏"},
];

let currentTab = 'belajar';
let quizIdx = 0, quizCorrect = 0, quizAnswered = false;
let selectedCalcShape = 0;

// Render shape cards
function renderShapeGrid() {
  const grid = document.getElementById('shapeGrid');
  grid.innerHTML = '';
  shapes.forEach((s, i) => {
    const card = document.createElement('div');
    card.className = 'card-hover rounded-3xl p-4 text-center cursor-pointer pop-in';
    card.style.cssText = `background:${s.bgColor};border:3px solid ${s.color};animation-delay:${i*0.1}s`;
    card.onclick = () => openModal(i);
    card.innerHTML = `
      <div class="text-4xl mb-2">${s.emoji}</div>
      <div class="mb-2">${s.svg}</div>
      <p class="font-bold text-sm" style="color:${s.color}">${s.name}</p>
    `;
    grid.appendChild(card);
  });
}

function openModal(i) {
  const s = shapes[i];
  document.getElementById('modalContent').innerHTML = `
    <div class="text-center mb-4">
      <span class="text-5xl">${s.emoji}</span>
      <h3 class="text-2xl font-bold mt-2" style="color:${s.color}">${s.name}</h3>
    </div>
    <div class="flex justify-center mb-4">${s.svg.replace('w-20 h-20','w-28 h-28').replace('w-24 h-16','w-32 h-20').replace('w-20 h-24','w-28 h-32')}</div>
    <p class="text-gray-600 mb-4 text-sm leading-relaxed">${s.desc}</p>
    <div class="space-y-2 mb-4">
      <p class="text-xs font-semibold text-purple-500 uppercase">Sifat-sifat:</p>
      ${s.sifat.map(x=>`<p class="text-sm text-gray-600 flex items-start gap-2"><span>✅</span>${x}</p>`).join('')}
    </div>
    <div class="grid grid-cols-2 gap-3 mb-4">
      <div class="rounded-2xl p-3 text-center" style="background:${s.bgColor}">
        <p class="text-xs text-gray-500 mb-1">Keliling</p>
        <p class="font-bold text-sm" style="color:${s.color}">${s.rumusK}</p>
      </div>
      <div class="rounded-2xl p-3 text-center" style="background:${s.bgColor}">
        <p class="text-xs text-gray-500 mb-1">Luas</p>
        <p class="font-bold text-sm" style="color:${s.color}">${s.rumusL}</p>
      </div>
    </div>
    <div class="rounded-2xl p-3" style="background:${s.bgColor}">
      <p class="text-xs font-semibold text-gray-500 mb-1">📦 Contoh benda:</p>
      <p class="text-sm" style="color:${s.color}">${s.contoh}</p>
    </div>
  `;
  document.getElementById('shapeModal').classList.remove('hidden');
}

function closeModal() {
  document.getElementById('shapeModal').classList.add('hidden');
}

// Tab switching
function switchTab(tab) {
  currentTab = tab;
  ['belajar','hitung','kuis'].forEach(t => {
    document.getElementById('content-'+t).classList.toggle('hidden', t !== tab);
    const btn = document.getElementById('tab-'+t);
    btn.className = btn.className.replace(/tab-active|tab-inactive/g, '') + (t === tab ? ' tab-active' : ' tab-inactive');
  });
  if (tab === 'kuis') resetQuiz();
}

// Calculator
function renderCalcSelector() {
  const el = document.getElementById('calcShapeSelector');
  el.innerHTML = '';
  shapes.forEach((s, i) => {
    const btn = document.createElement('button');
    btn.className = `p-2 rounded-xl text-center text-xs font-semibold btn-bounce border-2 transition-all ${i === selectedCalcShape ? 'border-purple-500 bg-purple-50' : 'border-gray-200 bg-white'}`;
    btn.onclick = () => { selectedCalcShape = i; renderCalcSelector(); renderCalcInputs(); };
    btn.innerHTML = `<span class="text-2xl block">${s.emoji}</span>${s.name}`;
    el.appendChild(btn);
  });
  renderCalcInputs();
}

function renderCalcInputs() {
  const s = shapes[selectedCalcShape];
  const el = document.getElementById('calcInputs');
  el.innerHTML = s.inputs.map(inp => `
    <div>
      <label class="text-sm font-medium text-gray-600 mb-1 block" for="calc-${inp.id}">${inp.label}</label>
      <input id="calc-${inp.id}" type="number" min="0" step="any" placeholder="${inp.ph}"
        class="w-full px-4 py-2.5 rounded-xl border-2 border-purple-200 focus:border-purple-500 focus:outline-none text-sm"
        oninput="calculate()">
    </div>
  `).join('');
  document.getElementById('calcResult').classList.add('hidden');
}

function calculate() {
  const s = shapes[selectedCalcShape];
  const vals = {};
  let allFilled = true;
  s.inputs.forEach(inp => {
    const v = parseFloat(document.getElementById('calc-'+inp.id).value);
    if (isNaN(v) || v <= 0) allFilled = false;
    vals[inp.id] = v;
  });
  if (!allFilled) { document.getElementById('calcResult').classList.add('hidden'); return; }
  const r = s.calc(vals);
  let txt = '';
  if (r.keliling !== null) txt += `📏 Keliling = <strong>${r.keliling.toFixed(2)}</strong> cm<br>`;
  txt += `📐 Luas = <strong>${r.luas.toFixed(2)}</strong> cm²`;
  document.getElementById('calcResultText').innerHTML = txt;
  document.getElementById('calcResult').classList.remove('hidden');
}

// Quiz
function resetQuiz() {
  quizIdx = 0; quizCorrect = 0; quizAnswered = false;
  renderQuiz();
}

function renderQuiz() {
  const area = document.getElementById('quizArea');
  if (quizIdx >= quizQuestions.length) {
    const pct = Math.round(quizCorrect/quizQuestions.length*100);
    const msg = pct >= 80 ? '🏆 Luar Biasa!' : pct >= 50 ? '👍 Bagus!' : '💪 Ayo Semangat!';
    area.innerHTML = `
      <div class="text-center py-6 slide-up">
        <span class="text-6xl block mb-4">${pct>=80?'🎉':'📚'}</span>
        <h3 class="text-2xl font-bold text-purple-700 mb-2">${msg}</h3>
        <p class="text-lg text-gray-600 mb-1">Skor: <strong>${quizCorrect}/${quizQuestions.length}</strong></p>
        <p class="text-3xl font-bold text-purple-600 mb-4">${pct}%</p>
        <button onclick="resetQuiz()" class="bg-purple-600 hover:bg-purple-700 text-white px-6 py-3 rounded-full font-semibold btn-bounce">🔄 Main Lagi</button>
      </div>`;
    return;
  }
  const q = quizQuestions[quizIdx];
  quizAnswered = false;
  document.getElementById('quizScore').textContent = `⭐ ${quizCorrect}/${quizIdx}`;
  document.getElementById('quizProgress').style.width = `${(quizIdx/quizQuestions.length)*100}%`;
  area.innerHTML = `
    <div class="slide-up">
      <div class="text-center mb-4">
        <span class="text-4xl">${q.emoji}</span>
        <p class="text-sm text-gray-400 mt-1">Soal ${quizIdx+1} dari ${quizQuestions.length}</p>
      </div>
      <p class="text-base font-semibold text-gray-700 mb-5 text-center leading-relaxed">${q.q}</p>
      <div class="grid grid-cols-1 gap-3" id="quizOpts">
        ${q.opts.map((o,j) => `
          <button onclick="answerQuiz(${j})" class="quiz-option w-full p-3 rounded-2xl text-left font-medium text-sm border-2 border-purple-200 bg-white hover:bg-purple-50">${['🅰️','🅱️','🅲','🅳'][j]} ${o}</button>
        `).join('')}
      </div>
    </div>`;
}

function answerQuiz(idx) {
  if (quizAnswered) return;
  quizAnswered = true;
  const q = quizQuestions[quizIdx];
  const btns = document.querySelectorAll('#quizOpts button');
  btns[q.ans].classList.add('correct');
  if (idx === q.ans) {
    quizCorrect++;
  } else {
    btns[idx].classList.add('wrong');
  }
  document.getElementById('quizScore').textContent = `⭐ ${quizCorrect}/${quizIdx+1}`;
  setTimeout(() => { quizIdx++; renderQuiz(); }, 1200);
}

// Init
const defaultConfig = {
  app_title: "Belajar Bangun Datar",
  subtitle: "Kelas 3 SD",
  background_color: "#fef3c7",
  surface_color: "#ffffff",
  text_color: "#6d28d9",
  primary_action_color: "#6d28d9",
  secondary_action_color: "#ec4899",
  font_family: "Fredoka",
  font_size: 16
};

function applyConfig(config) {
  const t = document.getElementById('mainTitle');
  const s = document.getElementById('mainSubtitle');
  if (t) t.textContent = config.app_title || defaultConfig.app_title;
  if (s) s.textContent = config.subtitle || defaultConfig.subtitle;

  const font = config.font_family || defaultConfig.font_family;
  document.body.style.fontFamily = `${font}, Fredoka, sans-serif`;

  const bg = config.background_color || defaultConfig.background_color;
  const txt = config.text_color || defaultConfig.text_color;
  const primary = config.primary_action_color || defaultConfig.primary_action_color;

  document.getElementById('app').style.background = `linear-gradient(135deg, ${bg} 0%, #fce7f3 30%, #ddd6fe 60%, #ccfbf1 100%)`;
  if (t) t.style.color = txt;
  if (s) s.style.color = primary;

  const base = config.font_size || defaultConfig.font_size;
  if (t) t.style.fontSize = `${base * 2}px`;
  if (s) s.style.fontSize = `${base * 1.1}px`;
}

window.elementSdk.init({
  defaultConfig,
  onConfigChange: async (config) => applyConfig(config),
  mapToCapabilities: (config) => ({
    recolorables: [
      { get: () => config.background_color || defaultConfig.background_color, set: (v) => { config.background_color = v; window.elementSdk.setConfig({background_color:v}); }},
      { get: () => config.surface_color || defaultConfig.surface_color, set: (v) => { config.surface_color = v; window.elementSdk.setConfig({surface_color:v}); }},
      { get: () => config.text_color || defaultConfig.text_color, set: (v) => { config.text_color = v; window.elementSdk.setConfig({text_color:v}); }},
      { get: () => config.primary_action_color || defaultConfig.primary_action_color, set: (v) => { config.primary_action_color = v; window.elementSdk.setConfig({primary_action_color:v}); }},
      { get: () => config.secondary_action_color || defaultConfig.secondary_action_color, set: (v) => { config.secondary_action_color = v; window.elementSdk.setConfig({secondary_action_color:v}); }}
    ],
    borderables: [],
    fontEditable: { get: () => config.font_family || defaultConfig.font_family, set: (v) => { config.font_family = v; window.elementSdk.setConfig({font_family:v}); }},
    fontSizeable: { get: () => config.font_size || defaultConfig.font_size, set: (v) => { config.font_size = v; window.elementSdk.setConfig({font_size:v}); }}
  }),
  mapToEditPanelValues: (config) => new Map([
    ["app_title", config.app_title || defaultConfig.app_title],
    ["subtitle", config.subtitle || defaultConfig.subtitle]
  ])
});

renderShapeGrid();
renderCalcSelector();
lucide.createIcons();
</script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9ec70762c066b5cc',t:'MTc3NjIxNDk4OS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
