# 📝 EXTEND-X 2026 — Submission & Presentation Guidelines

This guide outlines the **submission requirements**, **pre-submission checklist**, and **presentation structure** for participating teams in **EXTEND-X 2026**.

---

## ✅ 1. Pre-Submission Checklist

Before presenting your Chrome Extension to the judges, ensure your solution meets the following criteria:

* [ ] **Chrome Extension Compatibility**: The extension loads cleanly in Google Chrome via `chrome://extensions` (Developer Mode -> *Load Unpacked*).
* [ ] **Problem Alignment**: The extension directly solves either **PS-01 (Too Much Information)** or **PS-02 (Think Before You Click)**.
* [ ] **Functional MVP**: Core features work reliably on live web pages during testing.
* [ ] **Clean User Interface**: The popup, side panel, or page overlay UI is easy to read and navigate.
* [ ] **Code Readiness**: Every team member is prepared to answer technical questions about the codebase.
* [ ] **Third-Party Disclosures**: All external APIs, libraries, and AI services used are documented for presentation.

---

## 🎤 2. Presentation & Demonstration Structure

Each team will have a dedicated time slot to present their solution to the judging panel. We recommend structuring your presentation into the following 7 core areas:

```text
┌─────────────────────────────────────────────────────────────────────────┐
│                      EXTEND-X DEMO FLOW (7 STEPS)                       │
├─────────────────────────────────────────────────────────────────────────┤
│ 1. Problem Understanding ──► Why does this problem matter to users?    │
│ 2. Proposed Solution   ──► Your high-level extension concept           │
│ 3. Key Features        ──► What can the user do with your extension?    │
│ 4. Technical Stack     ──► Chrome APIs, JS/TS, CSS, Frameworks used    │
│ 5. APIs & Disclosures  ──► External AI models, REST APIs, libraries    │
│ 6. LIVE DEMO           ──► Show the extension working live in Chrome   │
│ 7. Future Roadmap      ──► Potential enhancements & production scope   │
└─────────────────────────────────────────────────────────────────────────┘
```

### 1. Problem Understanding
Explain the specific user pain point your team chose to address and why current web browsing tools fall short.

### 2. Proposed Solution
Introduce your Chrome Extension by name, tag line, and overall value proposition.

### 3. Key Features
Highlight the 2–3 core features that make your extension unique and effective.

### 4. Technical Implementation
Detail your technical architecture:
* Extension components used (`manifest.json`, background service workers, content scripts, popup UI, side panels).
* Key Chrome APIs leveraged (`chrome.tabs`, `chrome.scripting`, `chrome.storage`, `chrome.contextMenus`, etc.).

### 5. Third-Party & AI Disclosures
List any external APIs (OpenAI, Gemini, custom REST APIs), open-source packages, or styling frameworks used.

### 6. Live Product Demonstration
Demonstrate your extension live in Google Chrome:
* Open a target web page.
* Trigger your extension action (popup click, context menu, hover, or automated content script).
* Show how the extension processes page data and renders results clearly.

### 7. Future Improvements
Briefly outline features you would add given more time (e.g., cross-browser support, additional AI models, sync across devices).

---

## 📦 3. Required Deliverables

When submitting your final project, prepare the following items:

1. **Working Chrome Extension Codebase**:
   * Must include a valid `manifest.json` file.
   * All source files (`background.js`, `content.js`, `popup.html`, `popup.js`, styles, assets).
2. **GitHub Repository**:
   * Clean repository containing source code and a descriptive `README.md`.
3. **Presentation Deck (Optional/Recommended)**:
   * A concise slide deck (PDF/PPTX) summarizing your project for evaluation.

---

## 🔗 Quick Links

* 🏠 [**Back to Event Homepage (README)**](./README.md)
* 🧠 [**Problem Statement 01**](./PS-01-Too-Much-Information.md)
* 🛡️ [**Problem Statement 02**](./PS-02-Think-Before-You-Click.md)
* 📘 [**Common Rules & Integrity Policy**](./COMMON-RULES.md)

---

<p align="center"><i>EXTEND-X 2026 — Submission Guidelines</i></p>
