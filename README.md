# 🤖 Quantex AI — Preventive Maintenance Chatbot

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with CSS](https://img.shields.io/badge/Made%20with-CSS-blue?style=for-the-badge&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **Repository Link:** https://github.com/Mathur0100/Bot_Busters.git

---

## 🧩 Problem Statement

College laboratories (Physics, Chemistry, Computer, Electrical/Mechanical) face:
- Frequent equipment issues (e.g., “projector no power”, “microscope blurry”, “PC overheating”).
- Lack of quick, standardized troubleshooting guidance.
- Preventive maintenance tasks are often missed, leading to downtime, safety risks, and delayed practical sessions.

**Goal:** Build a single-page AI assistant that provides **instant, concise, step-by-step** preventive maintenance and troubleshooting guidance for common lab equipment — without needing any API keys or backend.

---

## ✅ Current Progress Status

**What’s done (prototype-ready):**
- ✔️ High-end futuristic UI (mascot, neon QUANTEX logo, particle background).
- ✔️ Eye-tracking mascot + typing animation.
- ✔️ **Large local knowledge base** (multi-lab: PC/AV/Microscope/Electronics/Chemistry Safety/etc.).
- ✔️ Query analyzer (equipment + issue intent; fuzzy matching; synonyms).
- ✔️ **Teach mode** to add custom fixes on the fly (saved locally in browser `localStorage`).
- ✔️ Optional web fallback (Wikipedia/Jina proxy) for quick references (no API keys).

**What’s pending (post-submission roadmap):**
- ⏳ Add dedicated backend with persistent DB (store custom learnings per lab).
- ⏳ Rich web sources beyond Wikipedia (manufacturer manuals, safety SOP PDFs).
- ⏳ Admin dashboard to track recurring issues and schedule maintenance.
- ⏳ Offline bundle for labs with limited internet.
- ⏳ Voice I/O and multi-language support.

---

## 🛠️ How the Prototype Solves the Problem

1. **Immediate Answers:** Typed issues like “projector no power” trigger targeted, to-the-point resolutions from a curated knowledge base.
2. **Consistency:** Guidance is standardized across labs; step-by-step flows reduce guesswork.
3. **Learning on the Fly:** Staff can **teach** Quantex custom fixes (`teach: key | steps`), which are remembered locally.
4. **Web-Enhanced Context:** When local knowledge is insufficient, Quantex pulls a concise reference snippet from the web (no keys).
5. **Futuristic, Engaging UI:** Improves adoption by students/lab assistants, reinforcing routine preventive maintenance.

---

## 🧪 Demo & Screenshots

> Replace the placeholders below with your own images.

| Home (Futuristic UI) | Typing + Mascot | Example Fix |
|---|---|---|
|![home](https://github.com/user-attachments/assets/f894f638-889e-4082-a154-129b003051bd)
| ![mascot](https://github.com/user-attachments/assets/51b5b3f9-c79d-4dac-baa8-88a257df6a90)
| ![fix](https://github.com/user-attachments/assets/d13cdd53-072b-47b2-877a-2c8845f00b81)
|

Additional:
- `screenshots/mobile.png` (Mobile responsive view)
- `screenshots/teach-mode.png` (Teach flow)

---

## 🚀 Quick Start (Front-End Only)

This prototype runs **entirely in the browser**.

1. Download/clone this repo.
2. Open `index.html` in Chrome/Edge/Firefox.
3. Start chatting with Quantex (e.g., “microscope blurry”, “projector no power”, “pc overheating”).
4. To add your own fix:
teach: projector:color issue | Check cable → set input source → reset display mode → test with spare HDMI.

> Optional: Use VS Code “Live Server” for auto-reload.

---

## 🧠 What You Can Ask (Examples)

- “projector no power”, “projector overheat”
- “microscope blurry”, “microscope not focusing”
- “pc overheating”, “usb device not detected”
- “multimeter wrong reading”, “oscilloscope no signal”
- “chemical spill”, “fume hood low airflow”
- “printer paper jam”, “camera no feed”

---

## 🧰 Tech/Tools Used

- **HTML + CSS + Vanilla JavaScript** (single-page app)
- **Custom Query Analyzer** (equipment/issue detection, synonyms, fuzzy matching)
- **Local Knowledge Base** (expandable)
- **Local Learning** via `localStorage`
- **Optional Web Fallback** using public endpoints (no API keys)

---

## 📦 Project Structure

Quantex/
│── index.html # All UI + logic in one file (for easy judging)
│── README.md # This file
└── screenshots/ # Your images for the README

---

## 🧭 Submission Checklist (for me)

- [ ] Repo link pasted into the form.
- [ ] README includes problem statement, progress, solution, tech stack, screenshots.
- [ ] Screenshots added to `/screenshots` and paths updated.
- [ ] Opened `index.html` to verify everything works end-to-end.

---

## 📜 License

MIT — free to use and modify with attribution.

---

## 🙌 Credits

Designed & built by **Rhythm Mathur** and **Sombit Mitra** — Quantex AI: Preventive Maintenance Assistant for College Labs.
