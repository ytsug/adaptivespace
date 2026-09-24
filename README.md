# AdaptiveSpace 🦉

> **Equal content isn't equal access.**[cite: 1]  
> AdaptiveSpace is an accessible, low-friction academic dashboard built for students with ADHD, dyslexia, and executive dysfunction[cite: 1, 8]. It eliminates initiation paralysis, breaks down complex tasks, and converts dense study material into visual diagrams, audio summaries, and plain-language notes[cite: 1, 8].

---

## 🚀 Live Demo
🔗 **[Launch AdaptiveSpace Live]([https://ytsug.github.io/adaptivespace/](https://ytsug.github.io/adaptivespace/))**

---

## ✨ Features & Architecture

### 1. "Your One Next Thing" & Focus Engine
* **Cognitive Isolation:** Highlights a single priority task at the top of the workspace to prevent overwhelm and decision fatigue[cite: 8].
* **Micro-Step Breakdown (✂):** Deconstructs intimidating assignments into concrete, time-boxed milestones (under 15 minutes each) using built-in scaffolding or Claude AI[cite: 8].
* **Built-in Focus Timer:** Selectable intervals (5, 10, 15, or 25 minutes) directly attached to the active task[cite: 8].
* **Auditory Walkthrough (🔊):** Reads the current objective and its sub-steps aloud using the browser's speech synthesis engine[cite: 8].

### 2. Low-Friction Task Dump
* **Single-Field Quick Add:** Type an assignment, exam, or reading and hit `Enter` to dump it instantly without mandatory form fields[cite: 8].
* **Automatic Timeline Grouping:** Automatically categorizes tasks into **Today**, **Upcoming deadlines**, and **All tasks**[cite: 8].
* **Zero-Friction Editing & Completion:** Check off completed items (earning XP), edit names inline, or toggle "Hide done" for a cleaner view[cite: 8].

### 3. Study Material Converter
* **🗺 Diagram Mode:** Generates a visual node-and-link mind map directly from pasted text using an interactive SVG engine[cite: 8].
* **🔊 Listen & Read Mode:** Automatically extracts key sentences into a high-yield bulleted summary paired with an adjustable-speed (0.6× to 1.6×) text-to-speech player[cite: 8].
* **✨ Simplify Mode (AI):** Re-writes dense academic material into short, dyslexia-friendly lines (under 12 words) with inline bracket definitions[cite: 8].
* **Direct File Ingestion:** Supports pasting raw text or uploading `.txt`, `.md`, and `.pdf` documents directly via an integrated PDF.js reader[cite: 8].

### 4. Neuro-Inclusive Comfort Engine (⚙)
* **High-Legibility Typography:** Toggle between **Atkinson Hyperlegible** (designed for low-vision distinction) and **Lexend** (designed to reduce visual crowding)[cite: 8].
* **Visual Stress Reduction:** Uses an off-white canvas (`#FAF9F6`), high-contrast accessible controls (3:1+), and dark-mode adaptation to eliminate screen-glare distortion[cite: 8].
* **Text Scaling & Roomy Spacing:** Instant font-size scaling controls (`A-` / `A+`) and increased line/letter spacing (`--lh: 1.9`, `--ls: .04em`) to ease reading tracking[cite: 8].
* **Calm View:** Strips away secondary lists and converters, leaving only the active task and focus timer on screen[cite: 8].

### 5. Sensory-Balanced Gamification
* Low-arousal visual rewards with zero flashing lights or loud popups[cite: 8].
* XP progress bars, level-ups, milestone badges (*First step*, *5 tasks done*, *Level 3*, *3-day streak*), and an encouraging mascot toast[cite: 8].

---

## 🧠 Why It Works (Cognitive Ergonomics)

| Challenge | Why Existing Apps Fail | The AdaptiveSpace Fix |
| :--- | :--- | :--- |
| **Blank-Canvas Paralysis** | Big blank dashboards force planning decisions before starting[cite: 1]. | Quick dump bar + automated "One Next Thing" isolation[cite: 8]. |
| **Executive Time Blindness** | Tasks feel bottomless without clear, concrete bounds[cite: 1]. | Micro-step breakdowns with explicit minute allocations (`5m`, `10m`, `15m`)[cite: 8]. |
| **Decoding Fatigue (Dyslexia)** | Dense, jargon-filled text strains working memory[cite: 1]. | Diagram visualization, plain-language simplification, and synchronized TTS narration[cite: 8]. |
| **Visual Stress & Glare** | High-contrast pure white/black triggers visual distortions[cite: 1]. | Softened canvas tones, custom typography, and adjustable line tracking[cite: 8]. |

---

## 🛠 Tech Stack

* **Core:** Semantic HTML5, Custom Property CSS3, Vanilla ES6+ JavaScript[cite: 8]
* **Document Parsing:** [PDF.js](https://mozilla.github.io/pdf.js/) (in-browser worker parsing)[cite: 8]
* **Speech Synthesis:** HTML5 Web Speech API (`window.speechSynthesis`)[cite: 8]
* **AI Engine (Optional):** Anthropic API direct browser integration (`claude-sonnet-4-6`)[cite: 8]
* **Persistence & Privacy:** 100% Client-side `localStorage` (no account setup required, API keys never leave the browser)[cite: 8]

---

## 📦 Run Locally

1. Clone the repository[cite: 7]:
   ```bash
   git clone [https://github.com/ytsug/adaptivespace.git](https://github.com/ytsug/adaptivespace.git)
