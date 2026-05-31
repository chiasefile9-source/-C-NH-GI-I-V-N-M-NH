<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kawaii Photobooth 🌸</title>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
:root {
  --pink: #ff6eb4;
  --pink2: #ff9dd2;
  --peach: #ffd4e8;
  --cream: #fff8f8;
  --lavender: #c9a0f5;
  --mint: #7de8c8;
  --yellow: #ffe066;
  --blue: #89d4f7;
  --red: #ff6b6b;
  --text: #4a2040;
  --shadow: rgba(255,110,180,0.25);
}

* { margin:0; padding:0; box-sizing:border-box; }

body {
  background: linear-gradient(135deg, #ffe0f0 0%, #f0e8ff 50%, #e0f4ff 100%);
  min-height: 100vh;
  font-family: 'Nunito', sans-serif;
  color: var(--text);
  overflow-x: hidden;
}

/* Floating deco */
.bg-deco {
  position: fixed; inset: 0; pointer-events: none; z-index: 0; overflow: hidden;
}
.bg-deco span {
  position: absolute;
  font-size: 1.8rem;
  animation: floatUp linear infinite;
  opacity: 0.18;
}
@keyframes floatUp {
  0% { transform: translateY(110vh) rotate(0deg); opacity: 0; }
  10% { opacity: 0.18; }
  90% { opacity: 0.18; }
  100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
}

header {
  position: relative; z-index: 1;
  text-align: center;
  padding: 24px 16px 8px;
}
header h1 {
  font-family: 'Pacifico', cursive;
  font-size: 2.6rem;
  color: var(--pink);
  text-shadow: 3px 3px 0 #fff, 5px 5px 0 rgba(255,110,180,0.2);
  letter-spacing: 2px;
}
header p {
  font-size: 0.9rem;
  color: #c07aaa;
  font-weight: 600;
  margin-top: 4px;
  letter-spacing: 1px;
}

.main-layout {
  position: relative; z-index: 1;
  max-width: 1100px;
  margin: 0 auto;
  padding: 12px 16px 40px;
  display: grid;
  grid-template-columns: 1fr 320px;
  gap: 20px;
  align-items: start;
}

/* ─── Left column ─── */
.left-col { display: flex; flex-direction: column; gap: 16px; }

/* Viewfinder */
.viewfinder-wrap {
  background: #fff;
  border-radius: 24px;
  padding: 14px;
  box-shadow: 0 8px 32px var(--shadow), 0 2px 0 #fff inset;
  border: 3px solid #ffb3d9;
  position: relative;
}

.viewfinder {
  position: relative;
  border-radius: 16px;
  overflow: hidden;
  background: #1a0a14;
  aspect-ratio: 4/3;
}

#video {
  width: 100%; height: 100%;
  object-fit: cover;
  display: block;
  transform: scaleX(-1);
}

/* Frame overlay on live video */
#frameOverlay {
  position: absolute;
  inset: 0;
  pointer-events: none;
  z-index: 5;
}

/* Stickers on live preview */
#stickerLayer {
  position: absolute;
  inset: 0;
  pointer-events: none;
  z-index: 6;
}
.preview-sticker {
  position: absolute;
  font-size: 2.2rem;
  line-height: 1;
  cursor: move;
  pointer-events: all;
  user-select: none;
  filter: drop-shadow(1px 2px 3px rgba(0,0,0,0.25));
  transition: transform 0.1s;
}
.preview-sticker:hover { transform: scale(1.15); }

/* Countdown */
#countdown {
  position: absolute; inset: 0;
  display: none;
  align-items: center; justify-content: center;
  background: rgba(255,182,220,0.35);
  backdrop-filter: blur(2px);
  z-index: 20;
}
#countNum {
  font-family: 'Pacifico', cursive;
  font-size: 9rem;
  color: #fff;
  text-shadow: 0 0 30px var(--pink), 4px 4px 0 var(--pink);
  animation: bounce 1s ease infinite;
}
@keyframes bounce { 0%,100%{transform:scale(1)} 50%{transform:scale(1.12)} }

.flash-overlay {
  position: absolute; inset: 0;
  background: #fff;
  opacity: 0;
  pointer-events: none;
  z-index: 25;
  transition: opacity 0.05s;
}
.flash-overlay.pop { opacity: 1; }

.cam-error {
  position: absolute; inset: 0;
  display: none;
  flex-direction: column;
  align-items: center; justify-content: center;
  gap: 10px;
  background: #fff5fb;
  font-size: 0.9rem;
  color: #c07aaa;
  text-align: center;
  padding: 20px;
}

/* Strip preview (the film strip result) */
.strip-wrap {
  background: #fff;
  border-radius: 20px;
  padding: 12px;
  box-shadow: 0 6px 24px var(--shadow);
  border: 3px solid #ffb3d9;
  display: none;
}
.strip-wrap h3 {
  font-family: 'Pacifico', cursive;
  color: var(--pink);
  font-size: 1rem;
  text-align: center;
  margin-bottom: 10px;
}

#stripCanvas {
  width: 100%;
  border-radius: 10px;
  display: block;
}

.strip-actions {
  display: flex; gap: 10px; margin-top: 10px;
}
.strip-btn {
  flex: 1;
  padding: 10px;
  border-radius: 50px;
  border: none;
  font-family: 'Nunito', sans-serif;
  font-weight: 800;
  font-size: 0.85rem;
  cursor: pointer;
  transition: transform 0.15s, box-shadow 0.15s;
  letter-spacing: 0.5px;
}
.strip-btn:hover { transform: translateY(-2px); }
.strip-btn.save {
  background: linear-gradient(135deg, var(--pink), var(--lavender));
  color: #fff;
  box-shadow: 0 4px 16px rgba(255,110,180,0.4);
}
.strip-btn.retake {
  background: #fff;
  color: var(--pink);
  border: 2px solid var(--pink2);
}

/* Controls */
.controls-bar {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 14px;
}

.shutter-btn {
  width: 76px; height: 76px;
  border-radius: 50%;
  background: linear-gradient(145deg, #ff8ec6, var(--pink));
  border: 4px solid #fff;
  box-shadow: 0 6px 20px rgba(255,110,180,0.45), 0 0 0 3px rgba(255,110,180,0.2);
  cursor: pointer;
  font-size: 1.8rem;
  transition: transform 0.12s, box-shadow 0.2s;
  display: flex; align-items: center; justify-content: center;
}
.shutter-btn:hover {
  transform: scale(1.07);
  box-shadow: 0 8px 28px rgba(255,110,180,0.55), 0 0 0 6px rgba(255,110,180,0.15);
}
.shutter-btn:active { transform: scale(0.95); }

.ctrl-btn {
  width: 48px; height: 48px;
  border-radius: 50%;
  border: 2px solid #ffb3d9;
  background: #fff;
  font-size: 1.3rem;
  cursor: pointer;
  transition: all 0.2s;
  display: flex; align-items: center; justify-content: center;
  box-shadow: 0 3px 10px var(--shadow);
}
.ctrl-btn:hover { background: var(--peach); transform: scale(1.08); }

/* Timer row */
.timer-row {
  display: flex; gap: 8px; justify-content: center;
}
.timer-chip {
  padding: 5px 16px;
  border-radius: 50px;
  border: 2px solid #ffb3d9;
  background: #fff;
  font-family: 'Nunito', sans-serif;
  font-weight: 700;
  font-size: 0.8rem;
  cursor: pointer;
  color: #c07aaa;
  transition: all 0.2s;
}
.timer-chip.active, .timer-chip:hover {
  background: linear-gradient(135deg, var(--pink), var(--pink2));
  border-color: var(--pink);
  color: #fff;
}

/* ─── Right column ─── */
.right-col { display: flex; flex-direction: column; gap: 16px; }

.panel {
  background: #fff;
  border-radius: 20px;
  padding: 16px;
  box-shadow: 0 6px 24px var(--shadow);
  border: 3px solid #ffb3d9;
}
.panel-title {
  font-family: 'Pacifico', cursive;
  font-size: 1rem;
  color: var(--pink);
  margin-bottom: 12px;
  display: flex; align-items: center; gap: 6px;
}

/* Frames */
.frame-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 8px;
}
.frame-opt {
  aspect-ratio: 3/4;
  border-radius: 10px;
  border: 3px solid transparent;
  cursor: pointer;
  overflow: hidden;
  position: relative;
  background: #fff5fb;
  transition: border-color 0.2s, transform 0.15s;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.5rem;
}
.frame-opt canvas {
  width: 100%; height: 100%;
  position: absolute; inset: 0;
}
.frame-opt .frame-label {
  position: absolute; bottom: 3px; left: 0; right: 0;
  text-align: center; font-size: 0.55rem; font-weight: 800;
  color: #c07aaa; letter-spacing: 0.5px; text-transform: uppercase;
  background: rgba(255,255,255,0.75);
  padding: 2px 0;
}
.frame-opt.active { border-color: var(--pink); transform: scale(1.06); }
.frame-opt:hover { transform: scale(1.06); }

/* Stickers */
.sticker-grid {
  display: flex; flex-wrap: wrap; gap: 6px;
}
.sticker-item {
  width: 40px; height: 40px;
  border-radius: 10px;
  background: var(--cream);
  border: 2px solid #ffb3d9;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.5rem;
  cursor: pointer;
  transition: transform 0.15s, background 0.15s;
  user-select: none;
}
.sticker-item:hover { transform: scale(1.2); background: var(--peach); }

/* Filters */
.filter-scroll {
  display: flex; gap: 8px; overflow-x: auto; padding-bottom: 4px;
}
.filter-scroll::-webkit-scrollbar { height: 4px; }
.filter-scroll::-webkit-scrollbar-thumb { background: var(--pink2); border-radius: 2px; }
.filter-chip {
  flex-shrink: 0;
  padding: 5px 14px;
  border-radius: 50px;
  border: 2px solid #ffb3d9;
  background: #fff;
  font-size: 0.78rem;
  font-weight: 700;
  color: #c07aaa;
  cursor: pointer;
  white-space: nowrap;
  transition: all 0.2s;
}
.filter-chip.active, .filter-chip:hover {
  background: linear-gradient(135deg, var(--pink), var(--pink2));
  border-color: var(--pink);
  color: #fff;
}

/* Gallery */
.gallery-grid {
  display: grid; grid-template-columns: repeat(3, 1fr); gap: 6px;
  max-height: 180px; overflow-y: auto;
}
.gallery-grid::-webkit-scrollbar { width: 4px; }
.gallery-grid::-webkit-scrollbar-thumb { background: var(--pink2); border-radius: 2px; }
.gal-thumb {
  aspect-ratio: 3/4; border-radius: 8px; overflow: hidden;
  cursor: pointer; border: 2px solid #ffb3d9;
  transition: transform 0.15s;
}
.gal-thumb img { width:100%; height:100%; object-fit:cover; display:block; }
.gal-thumb:hover { transform: scale(1.05); }
.gal-empty { grid-column:1/-1; text-align:center; color:#c07aaa; font-size:0.8rem; padding:16px 0; }

/* Toast */
#toast {
  position: fixed; bottom: 28px; left: 50%; transform: translateX(-50%) translateY(20px);
  background: linear-gradient(135deg, var(--pink), var(--lavender));
  color: #fff; padding: 10px 28px; border-radius: 50px;
  font-weight: 700; font-size: 0.88rem;
  opacity: 0; transition: opacity 0.3s, transform 0.3s; pointer-events: none; z-index: 9999;
  box-shadow: 0 6px 20px rgba(255,110,180,0.4);
}
#toast.show { opacity:1; transform: translateX(-50%) translateY(0); }

/* Mode chips */
.mode-row { display: flex; gap: 8px; justify-content: center; }
.mode-chip {
  padding: 6px 16px; border-radius: 50px;
  border: 2px solid #ffb3d9; background: #fff;
  font-family: 'Nunito', sans-serif; font-weight: 700; font-size: 0.78rem;
  cursor: pointer; color: #c07aaa; transition: all 0.2s;
}
.mode-chip.active, .mode-chip:hover {
  background: linear-gradient(135deg, var(--lavender), #a78bfa);
  border-color: var(--lavender); color: #fff;
}

@media(max-width:720px){
  .main-layout { grid-template-columns:1fr; }
  .right-col { order: -1; }
  header h1 { font-size: 2rem; }
}
</style>
</head>
<body>

<!-- Floating bg deco -->
<div class="bg-deco" id="bgDeco"></div>

<header>
  <h1>✨ Kawaii Photobooth ✨</h1>
  <p>🌸 chụp ảnh cute cùng bạn bè 🌸</p>
</header>

<div class="main-layout">

  <!-- LEFT -->
  <div class="left-col">

    <div class="viewfinder-wrap">
      <div class="viewfinder">
        <video id="video" autoplay playsinline muted></video>
        <canvas id="frameOverlay"></canvas>
        <div id="stickerLayer"></div>
        <div id="countdown"><span id="countNum">3</span></div>
        <div class="flash-overlay" id="flash"></div>
        <div class="cam-error" id="camErr">
          <span style="font-size:3rem">📷</span>
          <div>Không thể truy cập camera</div>
          <small>Vui lòng cho phép quyền truy cập camera</small>
        </div>
      </div>
    </div>

    <!-- Mode + timer -->
    <div class="mode-row">
      <button class="mode-chip active" data-shots="1">1 Ảnh</button>
      <button class="mode-chip" data-shots="3">3 Ảnh</button>
      <button class="mode-chip" data-shots="4">4 Ảnh</button>
    </div>
    <div class="timer-row">
      <button class="timer-chip active" data-val="0">Tắt hẹn giờ</button>
      <button class="timer-chip" data-val="3">3s ⏱</button>
      <button class="timer-chip" data-val="5">5s ⏱</button>
    </div>

    <!-- Controls -->
    <div class="controls-bar">
      <button class="ctrl-btn" id="flipBtn" title="Đổi camera">🔄</button>
      <button class="shutter-btn" id="shutterBtn">📸</button>
      <button class="ctrl-btn" id="clearStickersBtn" title="Xóa stickers">🧹</button>
    </div>

    <!-- Strip result -->
    <div class="strip-wrap" id="stripWrap">
      <h3>🎞 Ảnh của bạn!</h3>
      <canvas id="stripCanvas"></canvas>
      <div class="strip-actions">
        <button class="strip-btn retake" id="retakeBtn">↩ Chụp lại</button>
        <button class="strip-btn save" id="saveBtn">💾 Lưu ảnh</button>
      </div>
    </div>

  </div>

  <!-- RIGHT -->
  <div class="right-col">

    <!-- Frames -->
    <div class="panel">
      <div class="panel-title">🖼 Khung viền</div>
      <div class="frame-grid" id="frameGrid"></div>
    </div>

    <!-- Filters -->
    <div class="panel">
      <div class="panel-title">🎨 Bộ lọc màu</div>
      <div class="filter-scroll" id="filterRow"></div>
    </div>

    <!-- Stickers -->
    <div class="panel">
      <div class="panel-title">🌟 Nhãn dán</div>
      <div class="sticker-grid" id="stickerGrid"></div>
    </div>

    <!-- Gallery -->
    <div class="panel">
      <div class="panel-title">🗂 Album</div>
      <div class="gallery-grid" id="gallery">
        <div class="gal-empty">Chưa có ảnh nào~ 🌸</div>
      </div>
    </div>

  </div>
</div>

<div id="toast"></div>

<script>
/* ─── DATA ─── */
const STICKERS = [
  '🌸','🌺','🌼','🌻','🌹','🌷',
  '⭐','✨','💫','🌟','💥','🎀',
  '🦋','🐱','🐰','🐻','🐼','🐨',
  '🍓','🍒','🍰','🧁','🍭','🍬',
  '💖','💗','💓','💝','💘','💞',
  '🌈','☁️','⛅','🌙','☀️','❄️',
  '👑','🎪','🎠','🎡','🎢','🎭',
  '💄','👛','🕶','🎀','🎁','🧸',
];

const FILTERS = [
  { name:'Normal',    css:'none' },
  { name:'Vivid',     css:'saturate(1.8) contrast(1.1)' },
  { name:'Soft',      css:'brightness(1.1) contrast(0.9) saturate(0.85)' },
  { name:'Warm',      css:'sepia(0.3) saturate(1.4) brightness(1.05)' },
  { name:'Cool',      css:'hue-rotate(190deg) saturate(1.3)' },
  { name:'Mono',      css:'grayscale(1) contrast(1.15)' },
  { name:'Pastel',    css:'saturate(0.7) brightness(1.15) contrast(0.9)' },
  { name:'Dreamy',    css:'brightness(1.1) saturate(1.2) blur(0.4px)' },
  { name:'Vintage',   css:'sepia(0.55) contrast(1.1) brightness(0.95)' },
  { name:'Glam',      css:'contrast(1.3) saturate(1.5) brightness(1.05)' },
];

const FRAMES = [
  { name:'None',    draw: null },
  { name:'Blossom', draw: drawBlossom },
  { name:'Stars',   draw: drawStars },
  { name:'Hearts',  draw: drawHearts },
  { name:'Rainbow', draw: drawRainbow },
  { name:'Clouds',  draw: drawClouds },
  { name:'Polkadot',draw: drawPolkadot },
  { name:'Retro',   draw: drawRetro },
  { name:'Neon',    draw: drawNeon },
];

/* ─── STATE ─── */
let currentFrame = 0;
let currentFilter = 0;
let timerVal = 0;
let shotMode = 1;
let shots = [];
let placedStickers = [];
let stream = null;
let facingMode = 'user';
let isBusy = false;
let dragSticker = null, dragOffX = 0, dragOffY = 0;

/* ─── ELEMENTS ─── */
const video       = document.getElementById('video');
const frameOvC    = document.getElementById('frameOverlay');
const frameOvCtx  = frameOvC.getContext('2d');
const stickerLayer= document.getElementById('stickerLayer');
const cdEl        = document.getElementById('countdown');
const cdNum       = document.getElementById('countNum');
const flashEl     = document.getElementById('flash');
const stripWrap   = document.getElementById('stripWrap');
const stripCanvas = document.getElementById('stripCanvas');
const stripCtx    = stripCanvas.getContext('2d');
const gallery     = document.getElementById('gallery');

/* ─── BG DECO ─── */
const BG_EMOJIS = ['🌸','⭐','🌺','💖','✨','🦋','🌟','🍀','🌈'];
const bgDeco = document.getElementById('bgDeco');
for (let i = 0; i < 18; i++) {
  const s = document.createElement('span');
  s.textContent = BG_EMOJIS[i % BG_EMOJIS.length];
  s.style.left = Math.random()*100 + 'vw';
  s.style.animationDuration = (12 + Math.random()*14) + 's';
  s.style.animationDelay = (Math.random()*12) + 's';
  s.style.fontSize = (1.2 + Math.random()*1.5) + 'rem';
  bgDeco.appendChild(s);
}

/* ─── CAMERA ─── */
async function startCamera(mode='user') {
  if (stream) stream.getTracks().forEach(t=>t.stop());
  try {
    stream = await navigator.mediaDevices.getUserMedia({
      video: { facingMode: mode, width:{ideal:1280}, height:{ideal:960} }, audio:false
    });
    video.srcObject = stream;
    document.getElementById('camErr').style.display = 'none';
    video.style.filter = FILTERS[currentFilter].css;
    video.addEventListener('play', resizeOverlay, {once:true});
  } catch(e) {
    document.getElementById('camErr').style.display = 'flex';
  }
}

function resizeOverlay() {
  frameOvC.width = video.videoWidth;
  frameOvC.height = video.videoHeight;
  drawFrameOverlay();
}

document.getElementById('flipBtn').addEventListener('click', () => {
  facingMode = facingMode === 'user' ? 'environment' : 'user';
  video.style.transform = facingMode === 'user' ? 'scaleX(-1)' : 'scaleX(1)';
  startCamera(facingMode);
});

/* ─── FRAME OVERLAY (live preview) ─── */
function drawFrameOverlay() {
  const w = frameOvC.width, h = frameOvC.height;
  frameOvCtx.clearRect(0,0,w,h);
  if (FRAMES[currentFrame].draw) {
    FRAMES[currentFrame].draw(frameOvCtx, w, h, false);
  }
}

setInterval(() => {
  if (video.videoWidth && !isBusy) {
    if (!frameOvC.width) resizeOverlay();
    else drawFrameOverlay();
  }
}, 80);

/* ─── FRAME DRAW FUNCTIONS ─── */
function drawBlossom(ctx, w, h) {
  ctx.save();
  // Pink gradient border
  const bw = Math.max(w,h)*0.04;
  const grad = ctx.createLinearGradient(0,0,w,h);
  grad.addColorStop(0,'#ff9dd2'); grad.addColorStop(0.5,'#ffb3d9'); grad.addColorStop(1,'#ff6eb4');
  ctx.strokeStyle = grad; ctx.lineWidth = bw;
  ctx.strokeRect(bw/2, bw/2, w-bw, h-bw);
  // Sakura petals in corners
  const petals = [
    [0,0],[w,0],[0,h],[w,h],
    [w/2,0],[w/2,h],[0,h/2],[w,h/2]
  ];
  petals.forEach(([px,py]) => {
    drawSakura(ctx, px, py, Math.max(w,h)*0.07, Math.atan2(py-h/2, px-w/2));
  });
  ctx.restore();
}

function drawSakura(ctx, x, y, r, angle) {
  ctx.save();
  ctx.translate(x, y);
  ctx.rotate(angle);
  for (let i=0;i<5;i++) {
    ctx.save();
    ctx.rotate((Math.PI*2/5)*i);
    ctx.beginPath();
    ctx.ellipse(0, -r*0.5, r*0.25, r*0.45, 0, 0, Math.PI*2);
    ctx.fillStyle = 'rgba(255,182,218,0.88)';
    ctx.fill();
    ctx.restore();
  }
  ctx.beginPath();
  ctx.arc(0,0,r*0.18,0,Math.PI*2);
  ctx.fillStyle = '#ffe066';
  ctx.fill();
  ctx.restore();
}

function drawStars(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.04;
  const grad = ctx.createLinearGradient(0,0,w,h);
  grad.addColorStop(0,'#ffe066'); grad.addColorStop(1,'#ffb347');
  ctx.strokeStyle = grad; ctx.lineWidth = bw;
  ctx.strokeRect(bw/2, bw/2, w-bw, h-bw);
  const positions = [];
  const margin = bw*2;
  // Top/bottom edges
  for (let x = margin; x < w-margin; x += w*0.12) positions.push([x, bw*0.5]);
  for (let x = margin; x < w-margin; x += w*0.12) positions.push([x, h-bw*0.5]);
  // Left/right edges
  for (let y = margin*2; y < h-margin*2; y += h*0.14) positions.push([bw*0.5, y]);
  for (let y = margin*2; y < h-margin*2; y += h*0.14) positions.push([w-bw*0.5, y]);
  positions.forEach(([x,y]) => drawStar(ctx, x, y, bw*0.6, bw*0.25, '#ffe066'));
  ctx.restore();
}

function drawStar(ctx, cx, cy, r, ir, color) {
  ctx.save();
  ctx.translate(cx, cy);
  ctx.beginPath();
  for (let i=0;i<10;i++) {
    const angle = (Math.PI/5)*i - Math.PI/2;
    const rad = i%2===0 ? r : ir;
    ctx.lineTo(Math.cos(angle)*rad, Math.sin(angle)*rad);
  }
  ctx.closePath();
  ctx.fillStyle = color;
  ctx.fill();
  ctx.restore();
}

function drawHearts(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.04;
  const grad = ctx.createLinearGradient(0,0,w,h);
  grad.addColorStop(0,'#ff6b6b'); grad.addColorStop(1,'#ff6eb4');
  ctx.strokeStyle = grad; ctx.lineWidth = bw;
  ctx.strokeRect(bw/2, bw/2, w-bw, h-bw);
  const positions = [];
  const m = bw*0.5;
  for (let x = m; x < w; x += w*0.1) { positions.push([x,m]); positions.push([x,h-m]); }
  for (let y = m*3; y < h-m*3; y += h*0.12) { positions.push([m,y]); positions.push([w-m,y]); }
  positions.forEach(([x,y]) => drawHeart(ctx, x, y, bw*0.7));
  ctx.restore();
}

function drawHeart(ctx, x, y, s) {
  ctx.save();
  ctx.translate(x, y);
  ctx.scale(s,s);
  ctx.beginPath();
  ctx.moveTo(0, 0.3);
  ctx.bezierCurveTo(-1.2, -0.8, -2, 0.6, 0, 1.5);
  ctx.bezierCurveTo(2, 0.6, 1.2, -0.8, 0, 0.3);
  ctx.fillStyle = 'rgba(255,107,107,0.85)';
  ctx.fill();
  ctx.restore();
}

function drawRainbow(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.05;
  const colors = ['#ff6b6b','#ff9f43','#ffe066','#7de8c8','#89d4f7','#c9a0f5'];
  colors.forEach((c,i) => {
    ctx.strokeStyle = c;
    ctx.lineWidth = bw / colors.length * 1.4;
    const off = (bw / colors.length * 1.4) * i + (bw / colors.length * 0.7);
    ctx.strokeRect(off, off, w-off*2, h-off*2);
  });
  ctx.restore();
}

function drawClouds(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.045;
  ctx.strokeStyle = '#89d4f7'; ctx.lineWidth = bw;
  ctx.strokeRect(bw/2, bw/2, w-bw, h-bw);
  const cloud_positions = [];
  const m = bw*0.5;
  for (let x = m; x < w; x += w*0.15) { cloud_positions.push([x,m]); cloud_positions.push([x,h-m]); }
  for (let y = m*3; y < h-m*3; y += h*0.15) { cloud_positions.push([m,y]); cloud_positions.push([w-m,y]); }
  cloud_positions.forEach(([x,y]) => drawCloud(ctx, x, y, bw*1.2));
  ctx.restore();
}

function drawCloud(ctx, x, y, s) {
  ctx.save();
  ctx.translate(x, y);
  ctx.fillStyle = 'rgba(137,212,247,0.85)';
  ctx.beginPath();
  ctx.arc(0, 0, s*0.5, 0, Math.PI*2);
  ctx.arc(s*0.45, -s*0.1, s*0.38, 0, Math.PI*2);
  ctx.arc(-s*0.4, -s*0.05, s*0.33, 0, Math.PI*2);
  ctx.fill();
  ctx.restore();
}

function drawPolkadot(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.06;
  ctx.fillStyle = 'rgba(255,110,180,0.8)';
  ctx.fillRect(0, 0, w, bw);
  ctx.fillRect(0, h-bw, w, bw);
  ctx.fillRect(0, bw, bw, h-bw*2);
  ctx.fillRect(w-bw, bw, bw, h-bw*2);
  const r = bw*0.25;
  const colors = ['#fff','#ffe066','#fff','#89d4f7'];
  for (let x = r*2; x < w; x += r*3.2) {
    for (let y = r*2; y < bw*0.9; y += r*3) {
      ctx.fillStyle = colors[Math.floor(x/r)%colors.length];
      ctx.beginPath(); ctx.arc(x,y,r,0,Math.PI*2); ctx.fill();
      ctx.beginPath(); ctx.arc(x,h-y,r,0,Math.PI*2); ctx.fill();
    }
  }
  for (let y = bw+r*2; y < h-bw; y += r*3.2) {
    for (let x = r*2; x < bw*0.9; x += r*3) {
      ctx.fillStyle = colors[Math.floor(y/r)%colors.length];
      ctx.beginPath(); ctx.arc(x,y,r,0,Math.PI*2); ctx.fill();
      ctx.beginPath(); ctx.arc(w-x,y,r,0,Math.PI*2); ctx.fill();
    }
  }
  ctx.restore();
}

function drawRetro(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.04;
  // Outer dark
  ctx.fillStyle = '#2d1b33';
  ctx.fillRect(0,0,w,bw*1.5); ctx.fillRect(0,h-bw*1.5,w,bw*1.5);
  ctx.fillRect(0,bw*1.5,bw*1.5,h-bw*3); ctx.fillRect(w-bw*1.5,bw*1.5,bw*1.5,h-bw*3);
  // Inner stripe
  ctx.fillStyle = '#c9a0f5';
  ctx.fillRect(bw*1.5,0,w-bw*3,bw*0.5); ctx.fillRect(bw*1.5,h-bw*0.5,w-bw*3,bw*0.5);
  ctx.fillRect(0,bw*1.5,bw*0.5,h-bw*3); ctx.fillRect(w-bw*0.5,bw*1.5,bw*0.5,h-bw*3);
  // Dots at corners
  [[bw*0.75,bw*0.75],[w-bw*0.75,bw*0.75],[bw*0.75,h-bw*0.75],[w-bw*0.75,h-bw*0.75]].forEach(([x,y])=>{
    ctx.beginPath(); ctx.arc(x,y,bw*0.45,0,Math.PI*2);
    ctx.fillStyle='#ffe066'; ctx.fill();
  });
  ctx.restore();
}

function drawNeon(ctx, w, h) {
  ctx.save();
  const bw = Math.max(w,h)*0.03;
  ctx.shadowBlur = 18;
  ['#ff6eb4','#c9a0f5','#7de8c8'].forEach((c,i)=>{
    ctx.strokeStyle = c;
    ctx.shadowColor = c;
    ctx.lineWidth = bw * 0.9;
    const off = bw * i * 1.1 + bw*0.5;
    ctx.strokeRect(off, off, w-off*2, h-off*2);
  });
  ctx.restore();
}

/* ─── BUILD FRAME THUMBNAILS ─── */
function buildFrameThumbs() {
  const grid = document.getElementById('frameGrid');
  FRAMES.forEach((f,i) => {
    const btn = document.createElement('button');
    btn.className = 'frame-opt' + (i===0?' active':'');
    const tc = document.createElement('canvas');
    tc.width = 60; tc.height = 80;
    const tctx = tc.getContext('2d');
    tctx.fillStyle = '#fff5fb'; tctx.fillRect(0,0,60,80);
    if (f.draw) f.draw(tctx, 60, 80);
    btn.appendChild(tc);
    const lbl = document.createElement('div');
    lbl.className='frame-label'; lbl.textContent=f.name;
    btn.appendChild(lbl);
    btn.addEventListener('click', ()=>{
      document.querySelectorAll('.frame-opt').forEach(b=>b.classList.remove('active'));
      btn.classList.add('active');
      currentFrame = i;
    });
    grid.appendChild(btn);
  });
}

/* ─── FILTERS ─── */
function buildFilters() {
  const row = document.getElementById('filterRow');
  FILTERS.forEach((f,i) => {
    const btn = document.createElement('button');
    btn.className = 'filter-chip' + (i===0?' active':'');
    btn.textContent = f.name;
    btn.addEventListener('click', ()=>{
      document.querySelectorAll('.filter-chip').forEach(b=>b.classList.remove('active'));
      btn.classList.add('active');
      currentFilter = i;
      video.style.filter = f.css;
    });
    row.appendChild(btn);
  });
}

/* ─── STICKERS ─── */
function buildStickers() {
  const grid = document.getElementById('stickerGrid');
  STICKERS.forEach(emoji => {
    const btn = document.createElement('button');
    btn.className = 'sticker-item';
    btn.textContent = emoji;
    btn.addEventListener('click', () => addSticker(emoji));
    grid.appendChild(btn);
  });
}

function addSticker(emoji) {
  const vf = video.parentElement;
  const rect = vf.getBoundingClientRect();
  const el = document.createElement('div');
  el.className = 'preview-sticker';
  el.textContent = emoji;
  const x = (Math.random()*0.6+0.2) * 100;
  const y = (Math.random()*0.6+0.2) * 100;
  el.style.left = x+'%';
  el.style.top = y+'%';
  el.style.transform = 'translate(-50%,-50%)';

  // Drag
  el.addEventListener('mousedown', e => startDrag(e, el));
  el.addEventListener('touchstart', e => startDrag(e, el), {passive:true});

  stickerLayer.appendChild(el);
  placedStickers.push({ emoji, x, y, el });
}

function startDrag(e, el) {
  dragSticker = el;
  const isTouch = e.type === 'touchstart';
  const clientX = isTouch ? e.touches[0].clientX : e.clientX;
  const clientY = isTouch ? e.touches[0].clientY : e.clientY;
  const rect = el.getBoundingClientRect();
  dragOffX = clientX - rect.left - rect.width/2;
  dragOffY = clientY - rect.top - rect.height/2;
}

document.addEventListener('mousemove', moveDrag);
document.addEventListener('touchmove', moveDrag, {passive:true});
document.addEventListener('mouseup', ()=>{ dragSticker=null; });
document.addEventListener('touchend', ()=>{ dragSticker=null; });

function moveDrag(e) {
  if (!dragSticker) return;
  const isTouch = e.type === 'touchmove';
  const clientX = isTouch ? e.touches[0].clientX : e.clientX;
  const clientY = isTouch ? e.touches[0].clientY : e.clientY;
  const parent = stickerLayer.getBoundingClientRect();
  const x = ((clientX - parent.left - dragOffX) / parent.width) * 100;
  const y = ((clientY - parent.top - dragOffY) / parent.height) * 100;
  dragSticker.style.left = Math.max(0,Math.min(100,x)) + '%';
  dragSticker.style.top = Math.max(0,Math.min(100,y)) + '%';
}

document.getElementById('clearStickersBtn').addEventListener('click', ()=>{
  stickerLayer.innerHTML = '';
  placedStickers = [];
});

/* ─── TIMER CHIPS ─── */
document.querySelectorAll('.timer-chip').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('.timer-chip').forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    timerVal = parseInt(btn.dataset.val);
  });
});

/* ─── MODE CHIPS ─── */
document.querySelectorAll('.mode-chip').forEach(btn=>{
  btn.addEventListener('click',()=>{
    document.querySelectorAll('.mode-chip').forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    shotMode = parseInt(btn.dataset.shots);
  });
});

/* ─── SHUTTER ─── */
document.getElementById('shutterBtn').addEventListener('click', ()=>{
  if (isBusy) return;
  stripWrap.style.display = 'none';
  shots = [];
  if (timerVal > 0) runTimer(timerVal, () => runSession());
  else runSession();
});

function runTimer(sec, cb) {
  isBusy = true;
  let rem = sec;
  cdEl.style.display = 'flex';
  cdNum.textContent = rem;
  const iv = setInterval(()=>{
    rem--;
    if (rem <= 0) {
      clearInterval(iv);
      cdEl.style.display = 'none';
      isBusy = false;
      cb();
    } else {
      cdNum.textContent = rem;
    }
  }, 1000);
}

async function runSession() {
  isBusy = true;
  for (let i=0; i<shotMode; i++) {
    if (i > 0) {
      // brief pause between shots
      await new Promise(r => setTimeout(r, 800));
    }
    await captureOne();
  }
  buildStrip();
  isBusy = false;
}

function captureOne() {
  return new Promise(resolve => {
    // Flash
    flashEl.classList.add('pop');
    setTimeout(() => flashEl.classList.remove('pop'), 120);

    const w = video.videoWidth || 640;
    const h = video.videoHeight || 480;
    const tmp = document.createElement('canvas');
    tmp.width = w; tmp.height = h;
    const tc = tmp.getContext('2d');

    // Mirror for selfie
    if (facingMode === 'user') { tc.translate(w,0); tc.scale(-1,1); }
    tc.filter = FILTERS[currentFilter].css;
    tc.drawImage(video, 0, 0);
    tc.filter = 'none';
    if (facingMode === 'user') { tc.setTransform(1,0,0,1,0,0); }

    // Draw frame
    if (FRAMES[currentFrame].draw) {
      FRAMES[currentFrame].draw(tc, w, h);
    }

    // Draw stickers
    const stickers = stickerLayer.querySelectorAll('.preview-sticker');
    stickers.forEach(s => {
      const px = parseFloat(s.style.left)/100 * w;
      const py = parseFloat(s.style.top)/100 * h;
      tc.font = `${w*0.07}px serif`;
      tc.textAlign = 'center';
      tc.textBaseline = 'middle';
      tc.fillText(s.textContent, px, py);
    });

    shots.push(tmp.toDataURL('image/jpeg', 0.92));
    setTimeout(resolve, 100);
  });
}

/* ─── BUILD STRIP ─── */
function buildStrip() {
  const PHOTO_W = 320;
  const PHOTO_H = 240;
  const PAD = 16;
  const TOP = 40;
  const BOTTOM = 60;
  const STRIP_W = PHOTO_W + PAD*2;
  const STRIP_H = TOP + (PHOTO_H + PAD) * shots.length + BOTTOM;

  stripCanvas.width = STRIP_W;
  stripCanvas.height = STRIP_H;

  // Background
  const bg = stripCtx.createLinearGradient(0,0,STRIP_W,STRIP_H);
  bg.addColorStop(0,'#fff0f8'); bg.addColorStop(1,'#f0e8ff');
  stripCtx.fillStyle = bg;
  stripCtx.fillRect(0,0,STRIP_W,STRIP_H);

  // Sprocket holes (film look)
  stripCtx.fillStyle = 'rgba(200,150,200,0.25)';
  for (let y = TOP; y < STRIP_H - BOTTOM; y += 28) {
    stripCtx.beginPath(); stripCtx.arc(6, y, 4, 0, Math.PI*2); stripCtx.fill();
    stripCtx.beginPath(); stripCtx.arc(STRIP_W-6, y, 4, 0, Math.PI*2); stripCtx.fill();
  }

  // Header
  stripCtx.fillStyle = '#ff6eb4';
  stripCtx.fillRect(0,0,STRIP_W,TOP);
  stripCtx.font = 'bold 14px Pacifico, cursive';
  stripCtx.fillStyle = '#fff';
  stripCtx.textAlign = 'center';
  stripCtx.textBaseline = 'middle';
  stripCtx.fillText('✨ Kawaii Photobooth ✨', STRIP_W/2, TOP/2);

  // Photos
  const promises = shots.map((src, i) => {
    return new Promise(res => {
      const img = new Image();
      img.onload = () => {
        const y = TOP + i*(PHOTO_H+PAD);
        // Shadow
        stripCtx.save();
        stripCtx.shadowColor = 'rgba(255,110,180,0.3)';
        stripCtx.shadowBlur = 10;
        stripCtx.fillStyle = '#fff';
        stripCtx.fillRect(PAD-2, y-2, PHOTO_W+4, PHOTO_H+4);
        stripCtx.restore();
        stripCtx.drawImage(img, PAD, y, PHOTO_W, PHOTO_H);
        res();
      };
      img.src = src;
    });
  });

  Promise.all(promises).then(() => {
    // Footer
    const fy = STRIP_H - BOTTOM;
    stripCtx.fillStyle = '#ff6eb4';
    stripCtx.fillRect(0, fy, STRIP_W, BOTTOM);
    const now = new Date();
    const dateStr = `${now.getDate()}/${now.getMonth()+1}/${now.getFullYear()}`;
    stripCtx.font = '700 11px Nunito, sans-serif';
    stripCtx.fillStyle = '#fff';
    stripCtx.textAlign = 'center';
    stripCtx.textBaseline = 'middle';
    stripCtx.fillText('🌸 ' + dateStr + ' 🌸', STRIP_W/2, fy + BOTTOM/2);

    // Show strip
    stripWrap.style.display = 'block';
    stripWrap.scrollIntoView({ behavior: 'smooth', block: 'nearest' });

    // Add to gallery
    addToGallery(stripCanvas.toDataURL('image/jpeg', 0.92));

    // Auto save
    autoSave(stripCanvas.toDataURL('image/jpeg', 0.92));
  });
}

function addToGallery(dataURL) {
  const empty = gallery.querySelector('.gal-empty');
  if (empty) empty.remove();
  const thumb = document.createElement('div');
  thumb.className = 'gal-thumb';
  const img = document.createElement('img');
  img.src = dataURL;
  thumb.appendChild(img);
  thumb.addEventListener('click', ()=>{
    const a = document.createElement('a');
    a.download = `photobooth-${Date.now()}.jpg`;
    a.href = dataURL; a.click();
  });
  gallery.prepend(thumb);
}

function autoSave(dataURL) {
  const a = document.createElement('a');
  a.download = `kawaii-photobooth-${Date.now()}.jpg`;
  a.href = dataURL; a.click();
  showToast('🌸 Ảnh đã được lưu vào máy!');
}

document.getElementById('saveBtn').addEventListener('click', ()=>{
  autoSave(stripCanvas.toDataURL('image/jpeg',0.92));
});

document.getElementById('retakeBtn').addEventListener('click', ()=>{
  stripWrap.style.display = 'none';
  shots = [];
});

/* ─── TOAST ─── */
let toastTimer;
function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(()=>t.classList.remove('show'), 2600);
}

/* ─── INIT ─── */
buildFrameThumbs();
buildFilters();
buildStickers();
startCamera();
</script>
</body>
</html>
