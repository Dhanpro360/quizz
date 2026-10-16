# 🔬 Ergonomics MCQ Practice Web App

A self-contained, responsive, zero-dependency practice and quiz website modeled after [mcq-practice](https://davis-rowan.github.io/mcq-practice/), pre-loaded with **120 questions across all 12 weeks** from the NPTEL **Ergonomics Research Techniques (ERT)** course (IIT Guwahati).

---

## 🚀 Quick Start

1. **Direct Browser Launch**:
   - Double-click [`start_quiz.bat`](file:///c:/Users/Dhanpro360/Downloads/ergo/start_quiz.bat) or open [`index.html`](file:///c:/Users/Dhanpro360/Downloads/ergo/index.html) in any web browser (Edge, Chrome, Firefox, Safari).
   - No internet connection, server, or installation required!
2. **Deploy to GitHub Pages**:
   - Push this directory (or just `index.html`) to a GitHub repository.
   - Go to **Settings > Pages** and set source to `main` branch.
   - Your quiz website will be live online immediately just like `davis-rowan.github.io/mcq-practice/`.

---

## 🎯 Features

- **120 Questions Pre-Loaded**: 10 questions per week covering all 12 assignments with verified answers, options, and lecture references.
- **Multiple Practice Modes**:
  - **⚡ Smart Mix**: Smart spaced learning that prioritizes questions you struggled with, then unseen questions, then review.
  - **🎲 All Questions**: Randomized practice across selected modules.
  - **⚠️ Weak Only**: Directly focuses on questions you have missed or have low accuracy on.
  - **✨ New Only**: Focuses only on unattempted questions.
  - **⭐ Starred Only**: Custom revision playlist of questions you bookmarked.
- **Module / Week Selector**:
  - Filter questions by specific weeks (Weeks 1 to 12) or practice the entire curriculum.
  - Select quick session sizes (5, 10, 20 questions, or all available).
- **Interactive Quiz Interface**:
  - Keyboard navigation: press `A`, `B`, `C`, `D` (or `1`, `2`, `3`, `4`) to select answers.
  - Advance questions with `Enter` or `Space`.
  - Press `S` or `B` to star/bookmark questions for quick revision.
  - Instant visual feedback: green checkmark on correct answer, red highlight on wrong answer.
  - Detailed explanation / lecture citation box.
- **Weak List Tracker**:
  - Dedicated page tracking questions you struggled with, sorted from worst to best.
  - One-click "Practice Weak Questions Now" button.
- **Add / Manage Questions**:
  - Paste additional questions using standard text syntax.
  - Export & Import JSON backups to sync progress across devices.
  - One-click "Restore Default 120 Questions" button.
- **Theme Support**:
  - One-click Dark Mode / Light Mode toggle with automatic system preference detection.

---

## 📚 Curriculum Breakdown (12 Weeks • 120 Questions)

| Module | Topic / Focus | Questions |
|---|---|:---:|
| **Week 01** | Systems Ergonomics & Musculoskeletal Tools | 10 |
| **Week 02** | Job Strain Index (JSI) & REBA Analysis | 10 |
| **Week 03** | Manual Handling Assessment Charts (MAC Tool) | 10 |
| **Week 04** | Postural Assessment (RULA & Neutral Posture) | 10 |
| **Week 05** | Snook Tables & Manual Material Handling | 10 |
| **Week 06** | Assessment of Repetitive Tasks (ART Tool) | 10 |
| **Week 07** | Introduction & General Analysis Methods | 10 |
| **Week 08** | Cognitive Task Analysis Methods (HTA) | 10 |
| **Week 09** | Error Analysis Methods (SHERPA & TAFEI) | 10 |
| **Week 10** | Workload & Situation Awareness (NASA-TLX & SAGAT) | 10 |
| **Week 11** | Mental Workload Measurement; Indirect Methods (EEG / ERP) | 10 |
| **Week 12** | Human Reliability (CREAM) & Environmental Factors | 10 |

---

## 💾 Files Included

- [`index.html`](file:///c:/Users/Dhanpro360/Downloads/ergo/index.html): Complete, standalone, zero-dependency quiz website.
- [`questions.json`](file:///c:/Users/Dhanpro360/Downloads/ergo/questions.json): Clean JSON export of all 120 questions.
- [`start_quiz.bat`](file:///c:/Users/Dhanpro360/Downloads/ergo/start_quiz.bat): Windows one-click launcher.
- [`build_site.py`](file:///c:/Users/Dhanpro360/UnoTest/ergo-quiz/build_site.py): Python script used to parse PDFs and compile the site.
