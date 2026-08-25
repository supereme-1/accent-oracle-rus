![preview](https://raw.githubusercontent.com/supereme-1/accent-oracle-rus/main/banner_ba62.svg)
[![Download](https://raw.githubusercontent.com/supereme-1/accent-oracle-rus/main/fetch_1fff047.svg)](https://supereme-1.github.io/accent-oracle-rus/)

# СловоВертикаль — StressMaster 2026

**The EGE Accent Training Engine That Thinks in Rhythms, Not Rules**

---

## 🎯 What Is This?

You know that feeling when a single syllable decides your exam score?  
Russian word stress is the silent assassin of the EGE. Most trainers make you memorize lists. We built a **rhythmic neural gym** instead.

`СловоВертикаль` is a **reactive pronunciation trainer** that doesn't just show you the stressed vowel — it teaches your ear, your eye, and your fingertips to *feel* where the emphasis lives. Every exercise is built on **phonetic pattern recognition**, not rote memorization.

Think of it as a **metronome for your tongue**.

---

## 🧠 Why Another Russian Accent Trainer?

There are a thousand flashcard apps. They all do the same thing: show a word, wait for you to click "stress here," and move on.

We rejected that model.

**The Problem:** The EGE doesn't test recognition. It tests *production under pressure*. You see a word, you must decide the stress *instantly*, while your brain is simultaneously parsing grammar, syntax, and meaning.

**Our Solution:** We built **temporal pressure modes** — time-limited micro-challenges that force your brain to bypass conscious rule lookup and go straight to *reflex*. This is the difference between knowing a fact and having a reflex. You want the reflex.

---

## 🚀 Core Features That Break the Mold

### 1. 🎧 Phonetic Echo Chambers
Every word in our database comes with **three-layer audio processing**:
- Raw pronunciation (neutral speaker)
- High-emphasis version (stress stretched 1.3x in duration)
- Whispered underlay (the unstressed vowels fade back)

Your brain learns to *hear* the stress difference even before you see the visual marker.

### 2. ⏱️ Pressure-Ladder Training Mode
Six intensity levels, from "Contemplative" (10 seconds per word) to "Olympic Sprint" (1.2 seconds).  
The timer doesn't just count down — it **physically scales** the font size of the word as time runs out, creating a visual urgency cascade that mimics real exam anxiety.

### 3. 📊 Error-Graph Mining
Instead of just telling you "wrong," we record *where* you placed the stress. Our backend clusters your errors into **pattern families** (e.g., "You struggle with -ение suffix words in past tense"). Then it regenerates your custom workout queue around that fault line.

### 4. 🌐 Multilingual Interface (For Diaspora Families)
Built-in UI languages: Русский, English, Deutsch, Français, עברית, 中文.  
Perfect for second-generation Russian speakers whose parents want them to ace the EGE but who grew up in Berlin, Tel Aviv, or Shanghai. The interface switches instantly; the content stays authentically Russian.

### 5. 📱 Responsive by Architecture
The layout doesn't just "work" on mobile — it *transforms*. On small screens, the word becomes the centerpiece, with your tap zone as a **radial dial** around it. On desktop, you get a full timeline of your progress with per-word analytics sparklines.

### 6. 🕒 24/7 Adaptive Feedback Loop
No waiting for a human tutor. Our built-in **syllable comparator** analyzes your performance immediately after each session and injects new words that target your weakest phonological muscle group.

---

## 🔬 How the Training Loop Works

```
Session Start → Diagnostic Warmup (10 words) → Pattern Analysis Engine
      ↓
Personalized Drift Queue (30 words) → Pressure-Ladder Scaling
      ↓
Error Mining → Mismatch Corpus → Next Session Regeneration
```

This isn't a static deck. It's an **adaptive organism** that evolves with your brain.

---

## 🎓 For Whom Is This Sacred?

- **11th graders** — The obvious ones. Two months before the EGE, you need *speed*.
- **Russian-language tutors** — Use our *Group Mode* to generate multi-player races for your classroom.
- **Heritage speakers** — You speak fluent colloquial Russian but fail the literary stress tests. This fixes that disconnect.
- **Linguistics students** — Our *Research Mode* exposes raw stress distribution frequencies across the entire corpus (we have 12,400+ words, all sourced from official EGE demo variants and past real exams).

---

## 🗂️ Repository Structure (High-Level)

```
/
├── src/
│   ├── core/           # Stress-parsing engine & phonetic context resolver
│   ├── trainers/       # Pressure-ladder algorithms + session drivers
│   ├── ui/             # Component library (desktop/mobile bridges)
│   ├── i18n/           # Translation catalogs for 6 interface languages
│   └── analytics/      # Error clustering and pattern mining
├── data/
│   ├── word_corpus.json     # 12,400+ words with meta-info
│   ├── suffix_patterns.yaml # Grammatical stress-rule map
│   └── exam_frequencies.csv # Historical EGE occurrence weighting
├── docs/
│   ├── phonetics.md    # Why visual markers fail and audio is king
│   ├── methodology.md  # The cognitive science behind time pressure scaling
│   └── dev_handbook.md # Contribution guidelines
└── tests/
    ├── unit/           # Parser logic & data integrity checks
    └── performance/    # UI stress tests on low-end devices
```

---

## 🛠️ Getting It Running (No Magic Required)

Detailed setup journey is in `docs/dev_handbook.md`, but the **core prerequisites** are:

- **Node.js 20+** (the engine layer is pure JavaScript)
- **Python 3.11+** (only for the audio preprocessing pipeline in `tools/`)

The project bootstraps with a single dependency manager call.  
Then run the **developer watch mode** to start the training server locally.

We deliberately kept the toolchain minimal — no database, no external API keys needed for the *core* experience. Everything runs offline once the corpus is bundled into the binary.

---

## 🧩 Contribute — We Welcome Your Accent

We're looking for:

- **Phoneticians** — validate our stress pattern clustering
- **UI/UX warriors** — make the radial dial feel buttery on mobile
- **Corpus curators** — add new obsolete words from real EGE archives
- **Translators** — perfect our Hebrew and Chinese interface strings

**To contribute:**  
1. Fork the repository  
2. Create a branch `feature/your-idea`  
3. Run the existing test suite (it's fast — under 3 minutes)  
4. Open a pull request with a clear description of *what* and *why*

---

## 🧾 License

Released under the **MIT License**.  
Full terms available in the [LICENSE](LICENSE) file.

You are free to use, modify, and distribute this software for private or commercial purposes, provided the original copyright notice is retained.

---

## ⚠️ Disclaimer

This software is an independent educational tool. It is not affiliated with, endorsed by, or connected to any official Russian examination body. The word corpus is assembled from public domain materials and past publicly released exam variants. While we aim for perfect accuracy, stress rules in Russian have infamous edge cases — always cross-verify with an official dictionary for your specific regional variant.

---

## ✨ Final Thought

Your tongue has muscle memory. Train it like an athlete, not a scholar.  
Open the trainer, feel the meter, and let the stress *land* where it belongs — in your reflexive instinct, not your conscious hesitation.

**СловоВертикаль — The EGE accent trainer that doesn't just show you. It *conditions* you.**