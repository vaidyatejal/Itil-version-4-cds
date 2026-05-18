# ITIL 4 Specialist: Create, Deliver and Support (CDS) — Master Study Portal

Welcome to the **ITIL 4 Specialist CDS Master Study Portal**! This is a feature-rich, high-performance, single-page application (SPA) optimized for mobile, desktop, and tablet. It is designed to help professionals master the ITIL 4 CDS syllabus and pass their certification exam on the first attempt.

## 🌟 Key Application Features

* 📖 **Master Study Guide:** Structurally organized into 6 core syllabus units containing exam-critical summaries, comparison tables, and real-world analogies.
* 🧠 **Tactile 3D Flashcards:** Interactive review deck with automatic mastering and tracking.
* 🎮 **Concept Matcher Game:** Dynamic interactive matching engine to verify core definitions against scenarios under time tracking.
* 📝 **Scenario Mock Exam:** Comprehensive, Bloom's Level 2 & 3 scenario-based practice questions complete with detailed explanations and rationales for every option.
* 🔍 **Global Interactive Search:** Instant search functionality filtering study content and glossary terms in real-time.
* 📊 **Checklist & Progress Tracker:** Auto-saving persistent progress indicator showing your unit completion rate.
* 🌗 **Tactical Dark Mode:** Curated HSL-tailored theme toggle preserving eye comfort during late-night study sessions.

---

## 🛠️ Technology Stack & Architecture

* **Core:** Semantic HTML5, Vanilla JavaScript (ES6+), HSL CSS custom variables.
* **Hosting:** Hosted 100% Free Forever on **GitHub Pages**.
* **Automation (CI/CD):** Equipped with a custom GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically deploys your latest commits to the live CDN within seconds.

---

## 🚀 Getting Started & Local Development

### Running the App Locally
Since the portal is built using pure static technologies, it is exceptionally lightweight and requires zero installations or dependencies:
1. Double-click [index.html](./index.html) to open the study portal in your default web browser.
2. Click the **"Creative Mode"** button to jump into the flashcards and game-based [creative.html](./creative.html) page.

---

## ⚙️ CI/CD & Deployment Instructions

The repository is fully integrated with a **GitHub Actions Pipeline**.

### Deploying Changes
Whenever you update content inside `index.html` or `creative.html`, publish them to the web with:

```bash
# 1. Add all modifications
git add .

# 2. Commit your progress
git commit -m "Add custom analogies and clarify SIAM concepts"

# 3. Push to make it live instantly
git push origin main
```

Your live, production-grade application will update automatically at:  
**`https://vaidyatejal.github.io/Itil-version-4-cds/`**
