# ⚔️ LinguaFlow — Mandarin & Japanese Writing Studio *(Attack on Titan Edition)*

[![Live Demo](https://img.shields.io/badge/Live_App-GitHub_Pages-d4a348?style=for-the-badge&logo=github)](https://celinele5.github.io/linguaflow/)
![Languages](https://img.shields.io/badge/Languages-Mandarin_中文_%7C_Japanese_日本語-2d4a3e?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Architecture-Single_File_HTML-38bdf8?style=for-the-badge)

> **「心臓を捧げよ！」 / 「献出心脏吧！」**  
> *"Dedicate your heart! Every sentence you write pushes humanity past the walls."* — Commander Erwin Smith

**LinguaFlow** is a distraction-free, zero-setup daily writing web app designed specifically for **Mandarin Chinese (`中文`)** and **Japanese (`日本語`)** learners. Styled after the *Attack on Titan* Survey Corps (*調査兵団*), it combines a smartphone-grade zero-space IME, interactive character meaning lookup, blind-bag topic prompts, and streak-unlocked regiment themes inside a single self-contained HTML application.

---

## ✨ Key Features

### 🧧 1. Pre-Writing Lucky Blind Bag Draw
* Kick off each writing session by tearing open one of **3 sealed Scout Blind Bags** to reveal a randomized writing mission in Mandarin or Japanese.
* Includes a **Starter Frame**, clickable **Useful Vocabulary** chips with English glosses, or a **Free Write** toggle whenever you want to write about anything on your mind.

### ⌨️ 2. Zero-Space Smart Composition Engine (`Instant Script IME`)
Type naturally with your standard Latin keyboard—no OS input-method switching or manual spacebars required:
* **Mandarin Chinese (`中文`)**: Powered by a dynamic-programming syllable segmenter and multi-word beam-search decoder. Type full multi-syllable words or phrases continuously (e.g., `jinnian` → `今年`, `woxihuanhekafei` → `我喜欢喝咖啡`) without premature splitting.
* **Japanese (`日本語`)**: Live Romaji-to-Hiragana mora conversion (`kyou` → `きょう`, `konnichiha` → `こんにちは`) with double-consonant `っ` handling and instant Kanji candidate conversion (`今日`, `今日は`).
* **Auto-Switching Virtual Keyboard**: Dynamically adapts between Mandarin Pinyin/punctuation and Japanese Hiragana/Katakana (`⇧ Shift`), highlighting keys live as you type.

### 🔍 3. Interactive Character & Word Meaning Inspector
* **Highlight to Inspect**: Select any unknown Hanzi, Kanji, or Kana inside the writing canvas to open a floating card displaying its reading (Pinyin or Hiragana/Romaji) and English definition.
* **Tap-to-Inspect Reader Strip**: Every unique character in your draft appears in a quick-inspect bar below the editor, and dotted-underlined characters in prompts and coach feedback can be clicked anytime.

### 🎯 4. Native Coach & Colloquial Suggestions
* **Grammar & Flow Polishing**: Refines sentence endings, particles, and natural phrasing—with one-click replacement into your draft.
* **How Natives Say It Nowadays**: Suggests modern, casual expressions (*e.g.*, `氛围感直接拉满！`, `めっちゃ癒された！`) that you can insert directly into your writing.
* **Next Writing Directions**: Provides follow-up prompt starters to keep your momentum going, plus an optional **Live** mode that analyzes pauses automatically.

### 🔥 5. Daily Streaks, Reminders & Regiment Themes
* **Local Journal Archive**: Save dated entries in your browser (`localStorage`) to review past writing.
* **Daily Reminder Scheduler**: Set a custom daily writing nudge with browser notifications.
* **Unlockable Regiment Themes**:
  * **Default**: Survey Corps (*Wings of Freedom*)
  * **3-Day Streak (`🛡️ Cadet`)**: Wall Maria Parchment
  * **7-Day Streak (`⚔️ Scout`)**: Garrison Crimson
  * **14-Day Streak (`🎖️ Squad Leader`)**: Military Police Gold
  * **30-Day Streak (`🌌 Commander`)**: Coordinate Paths

---

## 🚀 Getting Started

### Option A: Use Online
Open the live web app directly in your browser:  
👉 **[https://celinele5.github.io/linguaflow/](https://celinele5.github.io/linguaflow/)**

### Option B: Run Locally
1. Clone or download this repository:
   ```bash
   git clone https://github.com/celinele5/linguaflow.git
   ```
2. Double-click `index.html` to open it in any modern browser (Chrome, Edge, Safari, or Firefox)—no build tools, servers, or installations required.

---

## ⌨️ IME Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| **`1` – `9`** | Select a specific Hanzi / Kanji candidate from the bar |
| **`Space` / `Enter`** | Commit the `#1` top candidate |
| **`Backspace`** | Remove the last letter in the active composition buffer |
| **`Esc`** | Commit the raw Latin letters directly without conversion |

---

## 🛠️ Tech Stack
* **HTML5 & Vanilla JavaScript (ES6+)** — Single-file architecture with zero external runtime dependencies.
* **Tailwind CSS (CDN)** — Responsive grid layout and custom theme tokens.
* **Google Fonts** — `Jost`, `Inter`, `Noto Sans SC`, and `Noto Sans JP` for crisp multilingual typography.
