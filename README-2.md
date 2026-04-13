# 🌸 AISHAGUL DTM

**DTM imtihoniga tayyorgarlik uchun zamonaviy PWA platforma**

> Fan tanlash · Ball hisoblash · Natija tahlili · Offline ishlaydi

---

## 📱 Xususiyatlar

- **Fan tanlash** — Majburiy va ixtiyoriy fanlarni tanlash imkoniyati
- **Ball kalkulyatori** — DTM mezonlariga mos aniq hisoblash
- **Natija tahlili** — To'plangan ball va baholash tizimi
- **PWA** — Telefonga o'rnatiladi, internet bo'lmasa ham ishlaydi
- **Mobil dizayn** — To'liq moslashtirilgan mobil interfeys

---

## 🚀 GitHub Pages orqali ishlatish

### 1. Repozitoriyani tayyorlash

```
aishagul-dtm/
├── index.html        ← dtm-platform-6.html ni rename qiling
├── manifest.json
├── sw.js
├── icon-192.png      ← 192×192 px ikonka
├── icon-512.png      ← 512×512 px ikonka
└── README.md
```

### 2. GitHub Pages yoqish

1. Repo sahifasiga o'ting → **Settings**
2. Chap menuda **Pages** bo'limini toping
3. **Source** → `Deploy from a branch`
4. **Branch** → `main` / `(root)` → **Save**
5. Bir necha daqiqadan keyin sayt tayyor bo'ladi

### 3. Havola

```
https://<username>.github.io/aishagul-dtm/
```

---

## 🖼️ Ikonkalar yaratish

Ikonkalar bo'lmasa, quyidagi vositalardan birini ishlating:

- [favicon.io](https://favicon.io) — logotipdan PNG yaratish
- [Canva](https://canva.com) — 192×192 va 512×512 eksport
- [RealFaviconGenerator](https://realfavicongenerator.net) — barcha o'lchamlar

> Rang kodi: `#c026d3` (binafsha-pushti)

---

## 📦 Service Worker haqida

`sw.js` quyidagilarni ta'minlaydi:

| Xususiyat | Tavsif |
|-----------|--------|
| **Offline rejim** | Ilk yuklanishdan keyin internet siz ham ishlaydi |
| **Cache** | Sahifa va resurslar mahalliy saqlanadi |
| **Yangilanish** | Fon rejimida avtomatik yangilanadi |
| **Versiyalash** | `CACHE_NAME` ni o'zgartirish orqali cache tozalanadi |

---

## ⚙️ Mahalliy sinovdan o'tkazish

```bash
# Python bilan oddiy server
python -m http.server 8000

# Node.js bilan
npx serve .
```

Brauzerda: `http://localhost:8000`

---

## 🛠️ Texnologiyalar

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat&logo=pwa&logoColor=white)

- Vanilla JS (framework yo'q)
- CSS Custom Properties
- Web App Manifest
- Service Worker API

---

## 📄 Litsenziya

MIT © Aishagul DTM — 2025
