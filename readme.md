# 🎬 Urban Air Quality Assistant: Video Demo

A narrated, self-running demo page with **Start** and **Stop** buttons that explains the Urban Air Quality Assistant: what it is, its features, a live example, and team roles and responsibilities.

**Live demo:** `https://<your-github-username>.github.io/<repo-name>/`
**Author:** Gundluru Rajasekhar

## ▶ How to Use
1. Open `index.html`.
2. Press **▶ Start**. Scenes play automatically with voice and captions.
3. Press **■ Stop** at any time to end and reset.
4. Untick **Voice narration** for a silent, caption-only run.

**To record a video:** open the page, start your screen recorder (Windows: Win+G, Mac: Shift+Cmd+5, or OBS), press Start, and stop recording when the Thank You scene ends (about 2 minutes). Upload the video and add its link to your submission.

## 🧱 Files
```
├── index.html        # Demo page (Start/Stop, narration, captions, scenes)
├── requirements.md   # Requirements and acceptance criteria
├── readme.md         # This file, including the full script
└── tasks.md          # Task plan and test checklist
```

## 📜 Full Video Script (about 2 minutes)

**Scene 1: Intro**
"Hello, and welcome. This is the Urban Air Quality Assistant, a simple web app that turns an air quality number into clear, practical health advice for people living in cities."

**Scene 2: The Problem**
"Every day, city residents see an AQI number on their phone, but few know what it means for their health. Children, older adults, and people with asthma or heart conditions are most at risk, and they need clear guidance quickly."

**Scene 3: What the App Is**
"The assistant is a lightweight, rule-based web application. It runs entirely in your browser with no API key, no sign-up, and no tracking. It uses the standard six-level AQI scale, from zero to five hundred."

**Scene 4: Key Features**
"First, an AQI checker with validation, colour, and a gauge. Second, smart advice that adapts to children, the elderly, patients, and outdoor workers. Third, a history of your last ten checks. And fourth, full accessibility, with keyboard and screen reader support, dark mode, and a mobile friendly layout."

**Scene 5: Live Demo**
"I enter an AQI of one hundred thirty five. The app instantly shows Unhealthy for Sensitive Groups, moves the gauge marker, and lists recommended actions. If I select Children, it adds a specific tip to limit outdoor play. If the value is invalid, such as six hundred, it shows a clear error message instead."

**Scene 6: Roles and Responsibilities**
"The Product Owner defines the problem, users, and acceptance criteria. The Full Stack Developer builds the logic, validation, history, and deployment. The UI and Accessibility Lead designs the layout, contrast, and screen reader support. The QA Tester runs the fifteen point checklist. The Security and Privacy Officer makes sure input is handled safely and no data leaves the device. And Documentation and DevOps maintains the readme and publishes the app on GitHub Pages."

**Scene 7: The Four Project Files**
"The project is delivered in four files. index.html contains the app. requirements.md lists the problem and acceptance criteria. readme.md explains features and deployment. And tasks.md holds the task plan and test checklist."

**Scene 8: Thank You**
"Thank you for watching. The Urban Air Quality Assistant helps everyone make safer outdoor decisions. Please open the live link and try it yourself. Remember, the guidance is general information and not medical advice."

## 👥 Roles and Responsibilities
| Role | Responsibility |
|------|----------------|
| Product Owner | Problem, users, acceptance criteria |
| Full Stack Developer | Logic, validation, history, deployment |
| UI/UX and Accessibility Lead | Layout, contrast, focus, screen reader support |
| QA Tester | 15-point test checklist |
| Security and Privacy Officer | Safe input handling, no data leaves device |
| Documentation and DevOps | README, repo, GitHub Pages |

## 🚀 Deploy to GitHub Pages
1. Create a public repository and upload the four files to the root.
2. Settings → Pages → Source: `main` branch, `/ (root)` → Save.
3. Share the link `https://<username>.github.io/<repo-name>/`.

## ♿ Accessibility and Security
Skip link, labelled controls, live captions for all narration, visible focus, reduced-motion support, text rendered with `textContent` only, and no external scripts or network calls.

## ⚠️ Browser Note
Voice narration uses the browser's built-in Speech Synthesis. Voices differ by device. If no voice is available, the demo runs from captions on a timer.
