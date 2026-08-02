# ⚡ Speed Reader

A desktop speed-reading application that leverages the science of **Rapid Serial Visual Presentation (RSVP)** — displaying one word at a time so your eyes never have to move across a line, allowing you to read significantly faster without losing comprehension.

---

## 💡 The Idea

Traditional reading forces your eyes to scan left to right across a page, burning time on physical eye movement rather than actual comprehension. Speed Reader eliminates this by flashing one word at a time in a fixed position on screen.

To push this even further, the app highlights the **optimal recognition point (ORP)** of each word — roughly the middle letter — in a bright accent color, aligned to a fixed vertical guide. This gives your brain an anchor point to lock onto instantly, reducing the cognitive load of finding where to focus and letting you process words faster and more naturally.

---

## ⚙️ How It Works

The application is made up of five core components:

### 1. GUI
The main interface. Displays the current word in large, readable text with the ORP letter highlighted and aligned to a fixed vertical guide line. Clean, distraction-free, and optimised for focus.

### 2. PDF Parser
Upload any PDF and the parser extracts the raw text, stripping formatting and layout so it can be fed cleanly into the reader word by word.

### 3. Middle Letter Calculator
The brain of the highlighting system. For each word, this algorithm calculates the optimal recognition point — the approximate middle letter — and flags it for colour highlighting in the display. Handles edge cases like very short words, punctuation, and hyphenated compounds.

### 4. Settings
Customisable reading experience including:
- **WPM (Words Per Minute)** — set your target reading speed
- Font size, highlight colour, and other display preferences

### 5. Output Controls
Real-time playback controls while reading:
- **Pause / Resume**
- **2× speed toggle** for on-the-fly acceleration
- Skip forward/back by sentence or paragraph

---

## 👥 Project Authorship & Division of Work

This project is a collaboration between a human developer and Claude (Anthropic's AI assistant), with a clear division of responsibilities:

| Task Type | Who Does It |
|---|---|
| Core coding & algorithms | **Me** — all implementation, logic, and architecture |
| Middle letter calculation algorithm | **Me** |
| PDF parsing implementation | **Me** |
| GUI development | **Me** |
| README & documentation | **Claude** |
| Tutorials & usage guides | **Claude** |
| Miscellaneous written materials | **Claude** |

In short: **I write the code, Claude writes the words around it.**

---

## 🚀 Getting Started

*(Documentation coming soon.)*

---

## 📖 Usage Guide

*(Tutorial coming soon.)*

---

## 📄 License

*(To be added.)*
