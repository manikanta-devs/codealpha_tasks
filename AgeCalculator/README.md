# 🎂 Age Calculator Pro — Discover Your Story

A beautifully designed, **single-file** Age Calculator Web Application built with pure **HTML, internal CSS, and internal JavaScript**. Enter your date of birth and instantly unlock your exact age along with a rich set of personal insights — from your generation and zodiac signs to numerology and life milestones.

---

## 🚀 Live Demo

Open `index.html` directly in any modern browser — no server or build step required.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📅 **Exact Age** | Calculates precise age in years, months, and days |
| ⏱️ **Live Ticker** | Real-time counter that ticks every second |
| 📊 **Time Stats** | Total days lived, total weeks, and the weekday you were born on |
| 🌍 **Generation** | Identifies your generational cohort (Gen Z, Millennial, Gen X, Boomer, etc.) with cultural traits and famous people |
| ♈ **Western Zodiac** | Star sign, ruling planet, element, personality traits, and compatibility |
| 🐉 **Chinese Zodiac** | Animal sign, element, year type, traits, and compatibility |
| 🔢 **Numerology** | Life Path Number, Destiny Number, and Soul Urge Number with interpretations |
| 💎 **Birthstone & Birth Flower** | Traditional birthstone and birth flower for your birth month |
| 🏆 **Life Milestones** | Upcoming and past age milestones (100 days, 1 000 days, 10 000 days, 18 years, etc.) |
| ✅ **Input Validation** | Prevents future dates and invalid inputs with friendly error messages |
| 📱 **Fully Responsive** | Mobile-first layout that works on all screen sizes |

---

## 🛠️ Technologies Used

- **HTML5** — Semantic markup and structure  
- **Internal CSS** — All styling lives inside `<style>` within the single file  
  - CSS custom properties (variables) for theming  
  - CSS Grid & Flexbox for layout  
  - Smooth animations & transitions  
  - Backdrop blur glass-morphism effects  
- **Internal JavaScript** — All logic lives inside `<script>` within the single file  

---

## 🧠 Concepts & Techniques

- **DOM Manipulation** — Dynamic rendering of results without page reloads  
- **JavaScript `Date` Object** — Precise date arithmetic for age, days, weeks, and countdowns  
- **Event Handling** — Real-time `input` event listeners with debouncing  
- **`setInterval`** — Live ticker that updates every second  
- **Data-Driven UI** — Zodiac, generation, numerology, and milestone data encoded as JS objects  
- **Intersection Observer API** — Staggered section reveal animations on scroll  
- **CSS `clamp()`** — Fluid typography that scales between viewport sizes  

---

## 📂 Project Structure

```
AgeCalculator/
├── index.html      # Complete app — HTML + CSS + JS in a single file
└── README.md       # Project documentation (this file)
```

---

## 🖥️ Getting Started

1. **Clone or download** this repository  
   ```bash
   git clone https://github.com/manikanta-devs/codealpha_tasks.git
   ```
2. **Navigate** to the `AgeCalculator` folder  
   ```bash
   cd codealpha_tasks/AgeCalculator
   ```
3. **Open** `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)  
   ```bash
   # macOS
   open index.html
   # Linux
   xdg-open index.html
   # Windows
   start index.html
   ```

No dependencies, no `npm install`, no build step. It just works. ✅

---

## 🎯 How to Use

1. Enter your **Day**, **Month**, and **Year** of birth in the three input fields.  
2. Results appear **instantly** as you type — no button press needed.  
3. The **live ticker** updates every second showing your age to the nearest second.  
4. Scroll down to explore your **Generation**, **Zodiac**, **Numerology**, **Life Stats**, and **Milestones** panels.

---

## 📸 UI Highlights

- **Dark luxury theme** with a deep navy/charcoal background and gold accent color (`#d4af64`)  
- **Grain texture overlay** for a premium feel  
- **Radial gradient mesh** background glows  
- **Glass-morphism** navigation bar with `backdrop-filter: blur`  
- **Fraunces** serif display font paired with **DM Sans** body font  
- **Staggered scroll animations** powered by `IntersectionObserver`  

---

## 📋 Sections at a Glance

```
┌─────────────────────────────────────┐
│  🏠  Navbar — Age Calculator Pro    │
├─────────────────────────────────────┤
│  🎉  Hero — Title + Date Input      │
├─────────────────────────────────────┤
│  ⏱️  Live Age Ticker                │
├─────────────────────────────────────┤
│  📊  Time Stats (Days · Weeks · Day │
│       of Week)                      │
├─────────────────────────────────────┤
│  🌍  Your Generation                │
├─────────────────────────────────────┤
│  ♈🐉  Zodiac (Western + Chinese)   │
├─────────────────────────────────────┤
│  🔢  Numerology                     │
├─────────────────────────────────────┤
│  💎  Birthstone & Birth Flower      │
├─────────────────────────────────────┤
│  🏆  Life Milestones                │
└─────────────────────────────────────┘
```

---

## 🌐 Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Edge 90+ | ✅ |
| Safari 14+ | ✅ |
| Opera 76+ | ✅ |

---

## 📜 License

This project is open source and available under the [MIT License](../LICENSE).

---

## 👤 Author

**Manikanta**  
[GitHub — manikanta-devs](https://github.com/manikanta-devs)

> *Built as part of the CodeAlpha Internship Task — Project 2*