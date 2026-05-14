# ❌ No-as-a-Service

<p align="center">
  <img src="https://raw.githubusercontent.com/hotheadhacker/no-as-a-service/main/assets/imgs/naas-with-no-logo-bunny.png" width="800" alt="No-as-a-Service Banner" width="70%"/>
</p>


Perlukan cara ynag baik untuk berkata tidak? 
API yang kecil molek ini mengembalikan alasan yang rawak, generik, kreatif dan kadangkala melucukan. - sesuai untuk apa-apa senario: peribadi, profesional, kehidupan pelajar atau pembangun.

Dibina untuk manusia, alasan dan humor.

---

## 🚀 Cara penggunaan API

**Base URL**
```
https://naas.isalman.dev/no
```

**Method:** `GET`  
**Rate Limit:** `120 requests per minute per IP`

### 🔄 Example Request
```http
GET /no
```

### ✅ Contoh Balasan
```json
{
  "reason": "This feels like something Future Me would yell at Present Me for agreeing to."
}
```

Use it in apps, bots, landing pages, Slack integrations, rejection letters, or wherever you need a polite (or witty) no.

---

## 🛠️ Penghosan Sendiri

Mahu menjalankannya sendiri? Ia ringan dan ringkas.

### 1. Klon repositori ini
```bash
git clone https://github.com/Syhfz78960/no-as-a-service-bahasa-melayu.git
cd no-as-a-service-bahasa-melayu
```

### 2. Pasang kebergantungan (dependency)
```bash
npm install
```

### 3. Mulakan pelayan
```bash
npm start
```

API boleh dicapai di:
```
http://localhost:3000/no
```

Anda juga boleh menukar port menggunakan pembolehubah persekitaran (environment variable):
```bash
PORT=5000 npm start
```
---

## 📁 Project Structure

```
no-as-service/
├── index.js            # Express API
├── reasons.json        # 1000+ alasan penolakan universal
├── package.json
├── .devcontainer.json  # VS Code / Github devcontainer setup
└── README.md
```

---

## 📦 package.json

Untuk rujukan, ini adalah konfigurasi pakej:

```json
{
  "name": "no-as-service",
  "version": "1.0.0",
  "description": "A lightweight API that returns random rejection or no reasons.",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "author": "hotheadhacker",
  "license": "MIT",
  "dependencies": {
    "express": "^4.18.2",
    "express-rate-limit": "^7.0.0"
  }
}
```

---

## ⚓ Devcontainer

Jika anda membuka repo ini dalam Github Codespaces, ia akan menggunakan `.devcontainer.json` secara automatik untuk menyediakan persekitaran anda.  Jika anda membukanya dalam VSCode, ia akan bertanya sama ada anda mahu membukanya semula dalam bekas.

---

## 👤 Author

Created with creative stubbornness by [hotheadhacker](https://github.com/hotheadhacker)
DIterjemahkan oleh [Syhfz78960](https://github.com/Syhfz78960)
---

## 📄 Lesen

MIT — buatlah apa=apa sahaj, cuma jangan berkata ya bila anda perlu berkata tidak.

---

## 🐧 Testimoni

> "I tried to integrate No-as-a-Service into the Linux kernel to reject bad patches automatically, but it started rejecting my own commits. 10/10, absolutely ruthless."
> 
> — **Linus Torvalds** (probably)
