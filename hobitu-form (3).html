<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Hobitu Eksik Stok</title>
<style>
* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #0f1117; color: #e8e9ed; min-height: 100vh; padding-bottom: 40px; }
.header { background: #1a1d27; padding: 16px 20px; border-bottom: 1px solid #2a2d3a; display: flex; align-items: center; gap: 10px; position: sticky; top: 0; z-index: 100; }
.logo { width: 34px; height: 34px; background: #ff6b35; border-radius: 9px; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
.logo svg { width: 20px; height: 20px; fill: white; }
.header-text h1 { font-size: 16px; font-weight: 700; color: #fff; }
.header-text p { font-size: 11px; color: #666; margin-top: 1px; }
.form-body { padding: 18px 16px; display: flex; flex-direction: column; gap: 14px; }
.field { display: flex; flex-direction: column; gap: 5px; }
label { font-size: 11px; font-weight: 700; letter-spacing: 0.07em; text-transform: uppercase; color: #777; }
label .req { color: #ff6b35; }
.scan-row { display: flex; gap: 8px; align-items: stretch; }
.scan-row input { flex: 1; }
input, textarea { background: #1a1d27; border: 1.5px solid #2a2d3a; border-radius: 11px; padding: 13px 14px; font-size: 16px; color: #e8e9ed; width: 100%; outline: none; transition: border-color 0.15s; -webkit-appearance: none; }
input:focus, textarea:focus { border-color: #ff6b35; background: #1d2030; }
input::placeholder, textarea::placeholder { color: #444; }
textarea { resize: none; min-height: 76px; font-family: inherit; font-size: 15px; }
.scan-btn { background: #ff6b35; border: none; border-radius: 11px; padding: 0 16px; color: white; font-size: 13px; font-weight: 700; cursor: pointer; display: flex; align-items: center; gap: 6px; white-space: nowrap; flex-shrink: 0; min-height: 50px; font-family: inherit; }
.scan-btn:active { opacity: 0.8; }
.scan-btn svg { width: 20px; height: 20px; flex-shrink: 0; }
.photo-preview { display: none; background: #1a1d27; border: 1.5px solid #2a2d3a; border-radius: 12px; padding: 12px; align-items: center; gap: 12px; }
.photo-preview.show { display: flex; }
.photo-preview img { width: 60px; height: 60px; border-radius: 8px; object-fit: cover; flex-shrink: 0; }
.photo-preview-text { flex: 1; }
.photo-preview-text p { font-size: 13px; color: #aaa; margin-bottom: 4px; }
.photo-preview-text strong { font-size: 15px; color: #fff; }
.retry-btn { background: transparent; border: 1px solid #555; border-radius: 8px; color: #aaa; font-size: 12px; padding: 6px 10px; cursor: pointer; font-family: inherit; white-space: nowrap; flex-shrink: 0; }
.scan-status { background: #1a1d27; border: 1.5px solid #2a2d3a; border-radius: 11px; padding: 12px 14px; font-size: 13px; color: #888; display: none; text-align: center; }
.scan-status.show { display: block; }
.scan-status.ok { color: #4ade80; border-color: #4ade80; }
.scan-status.err { color: #f87171; border-color: #f87171; }
.row2 { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
.divider { height: 1px; background: #2a2d3a; margin: 2px 0; }
.submit-btn { background: #ff6b35; border: none; border-radius: 13px; padding: 17px; color: white; font-size: 17px; font-weight: 700; width: 100%; cursor: pointer; font-family: inherit; margin-top: 4px; transition: opacity 0.15s, transform 0.1s; }
.submit-btn:active { transform: scale(0.98); opacity: 0.9; }
.submit-btn:disabled { opacity: 0.5; }
.err { font-size: 11px; color: #f87171; display: none; margin-top: 2px; }
.success { display: none; flex-direction: column; align-items: center; justify-content: center; min-height: 80vh; padding: 40px 20px; text-align: center; gap: 14px; }
.success.show { display: flex; }
.check-circle { width: 80px; height: 80px; background: #0f2e0f; border: 2px solid #4ade80; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin-bottom: 6px; }
.success h2 { font-size: 22px; color: #4ade80; font-weight: 700; }
.success p { font-size: 14px; color: #777; max-width: 260px; line-height: 1.6; }
.detail-card { background: #1a1d27; border: 1px solid #2a2d3a; border-radius: 12px; padding: 14px 16px; width: 100%; max-width: 340px; text-align: left; }
.detail-card .lbl { font-size: 11px; color: #555; text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 3px; }
.detail-card .val { font-size: 15px; color: #e8e9ed; font-weight: 600; margin-bottom: 10px; }
.detail-card .val:last-child { margin-bottom: 0; }
.new-btn { background: transparent; border: 1.5px solid #ff6b35; border-radius: 12px; padding: 14px 36px; color: #ff6b35; font-size: 16px; font-weight: 700; cursor: pointer; margin-top: 6px; font-family: inherit; }
.new-btn:active { background: #1a0d00; }
.toast { position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%); background: #222; border: 1px solid #333; border-radius: 10px; padding: 10px 20px; font-size: 13px; color: #fff; z-index: 999; opacity: 0; transition: opacity 0.3s; pointer-events: none; white-space: nowrap; }
.toast.show { opacity: 1; }
</style>
</head>
<body>

<div class="header">
  <div class="logo">
    <svg viewBox="0 0 24 24"><path d="M20 7H4c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2zm-9 8H9v2H7v-2H5v-2h2v-2h2v2h2v2zm4.5 1c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm3-3c-.83 0-1.5-.67-1.5-1.5S17.67 10 18.5 10s1.5.67 1.5 1.5S19.33 13 18.5 13zM4 6h16V4H4v2z"/></svg>
  </div>
  <div class="header-text">
    <h1>Eksik Stok Bildirimi</h1>
    <p>Hobitu Depo Takip Sistemi</p>
  </div>
</div>

<input type="file" id="iosInput" accept="image/*" capture="environment" style="display:none" onchange="handlePhoto(this)">
<canvas id="snapCanvas" style="display:none"></canvas>

<form id="mainForm" class="form-body" onsubmit="submitForm(event)">
  <div class="field">
    <label>Sipariş No <span class="req">*</span></label>
    <div class="scan-row">
      <input type="text" id="siparisNo" placeholder="TS2804394243" autocomplete="off" autocorrect="off" autocapitalize="characters" />
      <button type="button" class="scan-btn" onclick="document.getElementById('iosInput').click()">
        <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round">
          <path d="M3 7V5a2 2 0 0 1 2-2h2"/><path d="M17 3h2a2 2 0 0 1 2 2v2"/>
          <path d="M21 17v2a2 2 0 0 1-2 2h-2"/><path d="M7 21H5a2 2 0 0 1-2-2v-2"/>
          <line x1="8" y1="12" x2="16" y2="12"/><line x1="8" y1="15" x2="16" y2="15"/><line x1="8" y1="9" x2="11" y2="9"/>
        </svg>
        Tara
      </button>
    </div>
    <div class="err" id="err-siparis">Sipariş numarası gerekli</div>
  </div>

  <div class="scan-status" id="scanStatus"></div>

  <div class="photo-preview" id="photoPreview">
    <img id="previewImg" src="" alt="">
    <div class="photo-preview-text">
      <p>Okunan kod:</p>
      <strong id="previewCode"></strong>
    </div>
    <button type="button" class="retry-btn" onclick="retryPhoto()">Tekrar</button>
  </div>

  <div class="divider"></div>

  <div class="field">
    <label>Eksik Ürün Adı <span class="req">*</span></label>
    <input type="text" id="eksikUrun" placeholder="Ürün adını yazın..." />
    <div class="err" id="err-urun">Ürün adı gerekli</div>
  </div>

  <div class="row2">
    <div class="field">
      <label>Eksik Miktar <span class="req">*</span></label>
      <input type="number" id="eksikMiktar" placeholder="0" min="1" inputmode="numeric" />
      <div class="err" id="err-eksik">Gerekli</div>
    </div>
    <div class="field">
      <label>Mevcut Miktar</label>
      <input type="number" id="mevcutMiktar" placeholder="0" min="0" inputmode="numeric" />
    </div>
  </div>

  <div class="field">
    <label>Not / Açıklama</label>
    <textarea id="notAlani" placeholder="Ek bilgi varsa buraya yazın..."></textarea>
  </div>

  <button type="submit" class="submit-btn" id="submitBtn">Gönder</button>
</form>

<div class="success" id="successScreen">
  <div class="check-circle">
    <svg viewBox="0 0 24 24" fill="none" stroke="#4ade80" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" width="40" height="40">
      <polyline points="20 6 9 17 4 12"/>
    </svg>
  </div>
  <h2>Bildirim Gönderildi!</h2>
  <p>T-Soft güncellendi, sipariş notu eklendi ve süreç değiştirildi.</p>
  <div class="detail-card" id="detailCard"></div>
  <button class="new-btn" onclick="resetForm()">+ Yeni Bildirim</button>
</div>

<div class="toast" id="toast"></div>

<script src="https://cdn.jsdelivr.net/npm/jsqr@1.4.0/dist/jsQR.min.js"></script>
<script>
const WEBHOOK = 'https://tuzwzs6k.rpcld.app/webhook/eksik-stok';

function showToast(msg, dur) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), dur || 2500);
}

function setStatus(msg, type) {
  const s = document.getElementById('scanStatus');
  s.textContent = msg;
  s.className = 'scan-status show ' + (type || '');
}

function handlePhoto(input) {
  const file = input.files[0];
  if (!file) return;
  setStatus('Barkod aranıyor...', '');

  const url = URL.createObjectURL(file);
  const img = new Image();
  img.onload = () => {
    const canvas = document.getElementById('snapCanvas');
    const ctx = canvas.getContext('2d');

    // Orijinal boyutta dene
    tryDecode(img, canvas, ctx, 1, url, () => {
      // Daha büyük boyutta dene
      tryDecode(img, canvas, ctx, 2, url, () => {
        // Crop edilmiş orta bölgeyi dene
        tryDecodeCrop(img, canvas, ctx, url, () => {
          setStatus('Barkod okunamadı — daha yakın ve düz çekin.', 'err');
          input.value = '';
          URL.revokeObjectURL(url);
        });
      });
    });
  };
  img.src = url;
}

function tryDecode(img, canvas, ctx, scale, url, onFail) {
  canvas.width = img.width * scale;
  canvas.height = img.height * scale;
  ctx.drawImage(img, 0, 0, canvas.width, canvas.height);
  const imageData = ctx.getImageData(0, 0, canvas.width, canvas.height);

  // jsQR
  const qr = jsQR(imageData.data, imageData.width, imageData.height, { inversionAttempts: 'attemptBoth' });
  if (qr && qr.data) { onFound(qr.data, url); return; }

  onFail();
}

function tryDecodeCrop(img, canvas, ctx, url, onFail) {
  // Ortayı crop et
  const cw = img.width * 0.8;
  const ch = img.height * 0.5;
  const cx = (img.width - cw) / 2;
  const cy = (img.height - ch) / 2;
  canvas.width = cw * 2;
  canvas.height = ch * 2;
  ctx.drawImage(img, cx, cy, cw, ch, 0, 0, canvas.width, canvas.height);
  const imageData = ctx.getImageData(0, 0, canvas.width, canvas.height);
  const qr = jsQR(imageData.data, imageData.width, imageData.height, { inversionAttempts: 'attemptBoth' });
  if (qr && qr.data) { onFound(qr.data, url); return; }
  onFail();
}

function onFound(value, imgUrl) {
  document.getElementById('siparisNo').value = value;
  setStatus('✓ Barkod okundu: ' + value, 'ok');
  if (imgUrl) {
    document.getElementById('previewImg').src = imgUrl;
    document.getElementById('previewCode').textContent = value;
    document.getElementById('photoPreview').classList.add('show');
  }
  navigator.vibrate && navigator.vibrate([80, 30, 80]);
  setTimeout(() => document.getElementById('eksikUrun').focus(), 300);
}

function retryPhoto() {
  document.getElementById('photoPreview').classList.remove('show');
  document.getElementById('scanStatus').className = 'scan-status';
  document.getElementById('iosInput').value = '';
  document.getElementById('siparisNo').value = '';
  document.getElementById('iosInput').click();
}

async function submitForm(e) {
  e.preventDefault();
  const btn = document.getElementById('submitBtn');

  const siparisNo = document.getElementById('siparisNo').value.trim();
  const eksikUrun = document.getElementById('eksikUrun').value.trim();
  const eksikMiktar = document.getElementById('eksikMiktar').value.trim();
  const mevcutMiktar = document.getElementById('mevcutMiktar').value.trim();
  const not = document.getElementById('notAlani').value.trim();

  document.querySelectorAll('.err').forEach(el => el.style.display = 'none');
  let valid = true;
  if (!siparisNo) { document.getElementById('err-siparis').style.display = 'block'; valid = false; }
  if (!eksikUrun) { document.getElementById('err-urun').style.display = 'block'; valid = false; }
  if (!eksikMiktar) { document.getElementById('err-eksik').style.display = 'block'; valid = false; }
  if (!valid) return;

  btn.disabled = true;
  btn.textContent = 'Gönderiliyor...';

  try {
    await fetch(WEBHOOK, {
      method: 'POST',
      mode: 'no-cors',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        'Sipariş No': siparisNo,
        'Eksik Ürün': eksikUrun,
        'Eksik Miktar': eksikMiktar,
        'Mevcut Miktar': mevcutMiktar || '0',
        'Not': not
      })
    });

    document.getElementById('detailCard').innerHTML =
      '<div class="lbl">Sipariş No</div><div class="val">' + siparisNo + '</div>' +
      '<div class="lbl">Eksik Ürün</div><div class="val">' + eksikUrun + ' — ' + eksikMiktar + ' adet</div>' +
      (mevcutMiktar ? '<div class="lbl">Raftaki</div><div class="val">' + mevcutMiktar + ' adet</div>' : '') +
      (not ? '<div class="lbl">Not</div><div class="val">' + not + '</div>' : '');

    document.getElementById('mainForm').style.display = 'none';
    document.getElementById('successScreen').classList.add('show');
    navigator.vibrate && navigator.vibrate([100, 50, 100]);
  } catch(err) {
    showToast('Bağlantı hatası. Tekrar deneyin.');
  } finally {
    btn.disabled = false;
    btn.textContent = 'Gönder';
  }
}

function resetForm() {
  // Formu tamamen sıfırla
  document.getElementById('siparisNo').value = '';
  document.getElementById('eksikUrun').value = '';
  document.getElementById('eksikMiktar').value = '';
  document.getElementById('mevcutMiktar').value = '';
  document.getElementById('notAlani').value = '';
  document.getElementById('iosInput').value = '';
  document.getElementById('photoPreview').classList.remove('show');
  document.getElementById('scanStatus').className = 'scan-status';
  document.querySelectorAll('.err').forEach(el => el.style.display = 'none');
  
  const btn = document.getElementById('submitBtn');
  btn.disabled = false;
  btn.textContent = 'Gönder';
  
  document.getElementById('mainForm').style.display = 'flex';
  document.getElementById('successScreen').classList.remove('show');
}
</script>
</body>
</html>
