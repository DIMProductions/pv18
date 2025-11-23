# 🎹 Piano Virtuoso 18  
**Ultra-Fast Piano Reflex Trainer — by DIMProductions**

Piano Virtuoso 18 (PV18) is a browser-based speed & precision trainer  
designed to measure and improve rapid repeated-note performance.  
It analyzes finger dexterity, repetition accuracy, and short-burst control  
through a clean 10-second challenge format.

---

## 🚀 Features
- 10-second rapid-note performance test  
- Real-time MIDI input analysis (Web MIDI API)  
- Repetition speed counter  
- Timing stability evaluation  
- Multiple training modes:
  - **Erlkönig Mode** — C4 repeated taps  
  - **Trill Mode** — C4 ↔ D4 alternation  
- Built as a lightweight browser app  
- Works on Windows / macOS with any MIDI keyboard

---

## 🕹 Modes

### ⭐ **Erlkönig Mode**
- MIDI note: **60 (C4)**
- Tap C repeatedly for 10 seconds  
- Designed for Romantic repeated-note technique (Liszt / Sturm etc.)

### ⭐ **Trill Mode**
- MIDI notes: **60 ↔ 62 (C4 ↔ D4)**
- Measures alternation speed & stability  
- Useful for trill development in classical repertoire

### ⭐ **Custom Mode** *(Coming soon)*  
User-selectable keys, scale patterns, and velocity tracking.

---

## 📱 Mobile Demo (Experimental)

A **separate, simplified mobile-only demo UI** exists at:

```text
/m/index.html
```

This mobile demo is *not* the main version of PV18.  
It is an experimental UI prototype for mobile layout testing.  
The **canonical implementation is the root `index.html`**.
```
---

## 📁 Project Structure

```text
pv18/
  ├── index.html                 # Main PC/mobile-responsive build
  ├── assets/
  │     └── fonts/PressStart2P.woff2
  ├── m/
  │     └── index.html           # Mobile-only demo (experimental)
  └── README.md
````

---

## 🔧 Local Development

PV18 requires a local server for Web MIDI API.
Use Python’s built-in server:

```sh
cd pv18
python3 -m http.server 8080
```

Then open:

```
http://localhost:8080
```

PV18 will load with full MIDI support.

---

## 🌐 Online Demo (Coming Soon)

PV18 will be deployed on:

```
https://pv18.dim.productions
```

GitHub Pages + Cloudflare will host the production build.

---

## 📜 License / IP Notice

© 2025 DIMProductions
Author: **Davinci Leonhard**

Piano Virtuoso 18 is proprietary and confidential software.
Unauthorized reproduction, redistribution, or modification is prohibited.

See the `LICENSE` file for full legal terms.

---

## 🗺 Roadmap

* Custom note mode
* Scale endurance mode
* Cloud leaderboard / ranking
* AI-based finger stroke quality evaluation (via DivinasVision Core)
* Responsive design refinements
* Performance analytics dashboard

---

## 🙌 Contributing

Internal use only — external contributions are not accepted.

```

Piano Virtuoso 18
Copyright (c) 2025 DIMProductions
All Rights Reserved.

This software is proprietary and confidential.
Unauthorized copying, distribution, modification, or use of this software,
in whole or in part, is strictly prohibited without written permission
from DIMProductions.

Author: Davinci Leonhard
Organization: DIMProductions (DIMP)

This license applies to all source code, assets, documentation,
and binary outputs included in this repository, unless otherwise noted.

