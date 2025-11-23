# 🎹 Piano Virtuoso 18  
**Ultra-Fast Piano Reflex Trainer — by DIMProductions**

Piano Virtuoso 18 (PV18) is a browser-based speed & precision trainer  
designed to measure and improve rapid repeated-note performance.  
Built for pianists, keyboardists, and performers aiming for extreme finger agility.

---

## 🚀 Features
- 10-second rapid-note performance test  
- Real-time MIDI input analysis (Web MIDI API)  
- Repetition speed counter  
- Timing-stability evaluation  
- Training modes:
  - **Erlkönig Mode** — C4 rapid taps  
  - **Trill Mode** — C4 ↔ D4 alternation  
- Lightweight browser implementation — no installation needed

---

## 🕹 Modes

### ⭐ Erlkönig Mode
- MIDI Note: **60 (C4)**
- Tap as fast as possible for 10 seconds

### ⭐ Trill Mode
- MIDI Notes: **60 ↔ 62 (C4 ↔ D4)**
- Measures alternation speed & stability

### ⭐ Custom Mode *(Coming Soon)*
- User-selectable keys  
- Scale endurance patterns

---

## 📁 Project Structure
```

pv18/
├── index.html
├── pv18.js
├── midi.js
├── styles/
├── assets/
└── README.md

````

---

## 🔧 Development (Local Testing)

PV18 must be served over **http://localhost/** for Web MIDI API to work.  
Browsers block Web MIDI on `file://`.

Start a local server:

```sh
python3 -m http.server 8080
````

Open:

```
http://localhost:8080
```

---

## 🌐 Online Demo

(Coming Soon)

```
https://pv18.dim.productions
```

PV18 will be deployed via GitHub Pages inside the DIMProductions organization.

---

## 📜 License / IP Notice

© 2025 **DIMProductions**
Authored by **Davinci Leonhard**.

Piano Virtuoso 18 is proprietary software of DIMProductions.
Unauthorized reproduction, distribution, or modification is prohibited.

---

## 🗺 Roadmap

* Custom key mode
* Scale training mode
* Cloud score leaderboard
* AI-based finger-stroke quality evaluation (DivinasVision Core)
* Mobile optimization

---

## 🙌 Contributing

Internal use only.
External contributions are not accepted.

````

---

# 📄 **LICENSE（完全版）**

```text
Copyright (c) 2025 DIMProductions  
All Rights Reserved.

Piano Virtuoso 18 (PV18) is proprietary software owned by DIMProductions.

Permission is NOT granted to copy, redistribute, modify, merge, publish,
sell, sublicense, or create derivative works from this software, in whole
or in part, without prior written permission from DIMProductions.

This software is provided "as is" without warranty of any kind.
DIMProductions assumes no liability for use, misuse, or damages arising
from this product.

Author: Davinci Leonhard  
Organization: DIMProductions (DIMP)
