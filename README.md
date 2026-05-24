# 🔥 Resume Roaster

> Brutal AI CV critique that actually helps you get hired

Paste resume kamu, dapat skor + kritik jujur + saran perbaikan dari AI. Powered by Xiaomi MiMo.

## ✨ Features

- 🎯 Skor CV 1-100 + breakdown lengkap
- 🔥 3 mode roast: Gentle / Brutal / Savage
- 🚩 Identifikasi red flags & ATS issues
- 🛠️ Fix list konkret & actionable
- 🌐 Bilingual: Indonesia / English
- 💾 Export hasil ke Markdown
- 🔑 BYOK MiMo API atau pakai demo gratis (Pollinations fallback)

## 🚀 Quick Deploy

### Option 1: Vercel (paling cepat)
1. Fork/clone repo ini
2. Connect ke [Vercel](https://vercel.com/new)
3. Deploy — done. URL hidup dalam 30 detik.

### Option 2: Drag & Drop
1. Download `index.html`
2. Drag ke [vercel.com/new](https://vercel.com/new) atau Netlify Drop
3. Live URL siap

### Option 3: Local
```bash
cd resume-roaster
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Pakai MiMo API Key (recommended)

1. Klik tombol **⚙ Settings** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Pilih model — `mimo-v2.5-reasoning` lebih akurat, `mimo-v2.5` lebih cepat
4. **Test Connection** → **Save**

Tanpa API key, app fallback ke Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- **Frontend:** Single-file HTML, vanilla JS, zero dependencies
- **AI:** Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- **Storage:** localStorage (settings only, no server)
- **Deploy:** Static file, kompatibel Vercel / Netlify / GitHub Pages / IPFS

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com) — Xiaomi's developer incentive untuk app yang pakai MiMo AI.

## 📄 License

MIT — bebas fork, modify, gunakan komersial.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
