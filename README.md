# 📚 GATE 2026 Interactive Study Planner

An interactive, single-page web application designed to help students prepare for the **GATE 2026 Computer Science & IT** examination in a **structured and motivational way**.

This planner transforms a **23-week static study plan** into a **dynamic progress tracker** with real-time updates, persistent progress, and an exam countdown.
It runs entirely in the browser – **no backend required**.

---

## 🚀 Features

✅ **Interactive Weekly Cards** – Study plan is divided into 23 weeks. Mark weeks as *complete* when done.\
✅ **Dynamic Progress Tracking** – Progress bar + percentage counter updates in real time.\
✅ **Live Exam Countdown** – Always shows remaining time until **February 8, 2026**.\
✅ **Phase-Based Navigation** – Jump to preparation phases: *Foundational Learning*, *Intensive Revision*, *Full-Length Mocks*.\
✅ **Persistent State** – Progress is stored in **localStorage** (auto-saved).\
✅ **Fully Responsive** – Works seamlessly on **desktop, tablet, and mobile**.\
✅ **Customizable** – Edit the `studyPlan` array in the HTML file to adjust subjects, weeks, or goals.\

---

## 🛠️ Tech Stack

* **HTML5** – Base structure
* **Tailwind CSS** – Modern, utility-first styling
* **Vanilla JavaScript** – Handles interactivity, DOM updates, and localStorage

---

## 📥 Installation & Usage

1. **Download** the file: `gate_2026_planner.html`
2. **Open in browser** – Just double-click the file (works offline too).
3. **Track progress** – Mark weeks as complete, view countdown, and check overall progress.

---

## 📝 Customization

* Open `gate_2026_planner.html` in a text editor.
* Locate the `studyPlan` object (JavaScript array).
* Modify subjects, weeks, or goals to match your personal study strategy.

Example:

```js
const studyPlan = [
  { week: 1, goal: "TOC – Regular Languages, DFA/NFA + Maths – Sets" },
  { week: 2, goal: "COA – Number Systems + Discrete – Logic" },
  ...
];
```

---

## 📷 Preview

*(Optional: Add screenshots/gifs of the planner here if you’d like)*

---

## 📆 Timeline

* **Sep – Oct 2025**: Foundational Learning (TOC, COA, Maths, Discrete, Aptitude)
* **Nov – Dec 2025**: Full Syllabus Coverage (OS, CN, DBMS, Algo, Compiler, DL)
* **Jan – Feb 2026**: Intensive Revision + Full-Length Mock Tests

---

## 🙌 Contributing

Want to add features (dark mode, export progress, subject-wise filters)?

* Fork the repo
* Make changes
* Submit a pull request

---

## 📄 License

This project is **open-source** under the MIT License.

---
