# 🌟 EduHex - Interactive Indian Educational Quiz Website

> **Created with 💖 by Hacker Bhau**
>
> A vibrant, gamified quiz web application inspired by **Duolingo's delightful learning mechanics**, specifically built for **India's Education System (Grades 1st to 10th)** with **Science**, **Mathematics**, and **Indian General Studies & Current Affairs**, featuring **Multi-Language Translation (Hindi, Marathi, Gujarati, Tamil, Telugu, Bengali)**.

---

## 🎮 Key Features

### 1. 🐅 Duolingo-Style Animated Avatars & Mascots
- **Veer the Royal Bengal Tiger**: Energetic science & nature explorer.
- **Arya the Wise Peacock**: Graceful, sharp math & logic mentor.
- **Tara the ISRO Space Star**: Space cadet celebrating India's astronomical breakthroughs.
- **Gajju the Gentle Baby Elephant**: Patient memory master & Indian heritage guide.
- **Dynamic Reactions**: Mascots cheer, jump with confetti, celebrate streaks, and offer encouraging tips on tricky questions via speech bubbles.

### 2. 📚 Complete Grades 1 to 10 Curriculum (NCERT / CBSE / State Board)
- **Grade Switcher Bar**: Switch between **Class 1 to Class 10** with a single click.
- **Curated Subject Tracks**:
  - 🔬 **Science Explorer**: Living vs non-living, plant/human biology, electricity, optics, genetics, Newton's laws, chemical reactions.
  - 📐 **Math Prodigy**: Number sense, shapes, fractions, algebra, geometry, trigonometry, quadratic equations, probability, arithmetic progressions.
  - 🇮🇳 **India GK & Current Affairs**: ISRO Chandrayaan-3 south pole landing, Aditya-L1, Gaganyaan, Constitution & Dr. Ambedkar, UPI/Digital India, G20 Summit, national symbols, rivers, mountains, and sports champions like Neeraj Chopra.
  - 🏆 **Mega Olympiad Challenge**: Speed test combining all tracks for the selected grade.

### 3. 🎯 Engaging Gamification
- **Tactile 3D Buttons**: Satisfying Duolingo-style push buttons and option cards.
- **Web Audio Engine**: Pure procedural audio synthesizer (offline chord chimes, gentle tone on wrong answers, streak whoosh, victory fanfare).
- **Daily Streak Tracker 🔥**: Daily streak counter with glowing animated flame.
- **XP & Levels ⚡**: Earn +10 XP per correct answer with combo streak multipliers.
- **Lifelines & Hints 💡**: 50:50 Lifeline to eliminate 2 incorrect choices, plus Mascot hints.
- **Practice Mode (Zen)**: Toggle unlimited hearts for stress-free revision or challenge mode with 5 hearts.
- **Confetti Engine 🎊**: 60fps canvas particle celebration bursts on high scores and streaks.
- **Mistake Mastery & Review 🔄**: Review all answers at the end with NCERT explanations and run a "Retry Mistakes" session.

---

## 📁 Project Structure

```
gyan-quest/
├── index.html          # Main responsive single-page application
├── server.py           # Python local server with auto-browser launch
├── css/
│   └── styles.css      # Duolingo 3D button system, animations & layout
├── js/
│   ├── audio.js        # Procedural Web Audio API sound effects engine
│   ├── mascots.js      # Animated SVG characters & dynamic quotes
│   ├── questions.js    # Comprehensive NCERT question bank (Grades 1-10)
│   ├── confetti.js     # Full-screen canvas celebration particles
│   └── app.js          # Main game state, scoring, lifelines, local storage
└── README.md           # Documentation and guide
```
