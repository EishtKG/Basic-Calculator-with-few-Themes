# 🧮 Basic Calculator with Themes

> **This project was built as a learning exercise to understand DOM manipulation and the JavaScript frontend workflow.** Every feature was coded step by step — from scratch — without using any frameworks or libraries beyond Tailwind CSS for styling.

🔗 **Live Demo:** [eishtkg.github.io/Basic-Calculator-with-few-Themes](https://eishtkg.github.io/Basic-Calculator-with-few-Themes/)

---

## 📸 Themes Preview

| Deep Ocean | Blood Moon | Nebula |
|---|---|---|
| ![Deep Ocean](screenshots/deep-ocean.png) | ![Blood Moon](screenshots/blood-moon.png) | ![Nebula](screenshots/nebula.png) |

| Midnight Aurora | Volcanic | Venetian Gold |
|---|---|---|
| ![Midnight Aurora](screenshots/midnight-aurora.png) | ![Volcanic](screenshots/volcanic.png) | ![Venetian Gold](screenshots/venetian-gold.png) |

---

## ✨ Features

**Calculator**
- All 4 basic operations — addition, subtraction, multiplication, division
- Percentage (`%`) and sign toggle (`+/-`)
- Decimal input with duplicate decimal prevention
- `C` acts as backspace, `AC` clears everything
- Smart operator handling — no duplicate operators
- Handles edge cases like pressing `=` on incomplete expressions
- Fresh start after result, or continue with an operator

**Keyboard Support**
- Type numbers and operators directly from keyboard
- `Enter` → calculate
- `Backspace` → delete last character
- `Escape` → clear all

**Themes**
- 6 gradient themes that i liked while searching over internet
- Animated dot indicators below the calculator
- Theme name appears with a blur-in animation on switch
- Remembers active theme dot with a colored indicator

---

## 🎨 Themes

| Name |
|---|
| **Deep Ocean** | 
| **Blood Moon** | 
| **Nebula** | 
| **Midnight Aurora** | 
| **Volcanic** | 
| **Venetian Gold** | 
---

## 🛠️ Built With

- **HTML** — structure
- **Tailwind CSS** — styling via CDN (no build step)
- **Vanilla JavaScript** — all logic, DOM manipulation, theme switching
- **CSS** — custom styles for glass effect, gradients, animations

---

## 🍎 Mac Calculator Reference

The resemblance to Apple's macOS calculator app was **intentional** — it was used as the visual reference point for this project. The round buttons, dark theme, orange operators, and display layout were all inspired by it. The goal was to get as close as possible using only HTML, Tailwind, and CSS.

---

## 📚 What I Learned

Building this from scratch taught me:

- **DOM selection** — `getElementById`, `querySelectorAll`
- **Event listeners** — `addEventListener` for clicks and keyboard (`keydown`)
- **NodeList iteration** — `forEach` on query results
- **String manipulation** — `slice`, `includes`, template literals
- **Boolean flags** — tracking state like `justCalculated`
- **`eval()`** — evaluating math expressions from strings
- **`parseFloat()` and `String()`** — converting between types
- **CSS transitions** — `opacity`, `filter: blur()`, `transform: scale()`
- **`setTimeout` and `clearTimeout`** — timing animations
- **Tailwind CSS** — utility-first styling without writing raw CSS
- **`backdrop-filter`** — frosted glass effect
- **CSS gradients** — linear, radial, and conic gradients for backgrounds
- **Debugging** — reading console errors, fixing type bugs, bracket mistakes

---

## 🚀 Run Locally

No installation needed — just open `index.html` in your browser!

```bash
git clone https://github.com/EishtKG/Basic-Calculator-with-few-Themes.git
cd Basic-Calculator-with-few-Themes
open index.html
```

---

## 📁 Project Structure

```
├── index.html      # structure + Tailwind classes
├── style.css       # glass effect, gradients, dot styles, animations
├── script.js       # all calculator logic + theme switching
└── README.md
└── screenshots
    └── blood-moon.png
    └── deep-ocean.png
    └── midnight-aurora.png
    └── nebula.png
    └── venetian-gold.png
    └── volcanic.png

```

---

*Made with curiosity and a lot of console.log 🙃*
