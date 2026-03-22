# 🏎️ Premium Accordion Car Slider

A high-performance, interactive car showcase built with **Vanilla JavaScript**, **CSS3 Flexbox**, and **HTML5**. This project features a sophisticated "accordion" expansion effect, grayscale-to-color transitions, and dynamic data reveals for vehicle specifications.

---

## 🔗 Live Demo
Check out the interactive demo here:  
**[View Live Demo](https://priyanshjain543.github.io/Apex-Canvas-TASK-24/
)** *(Replace with your actual link)*

---

## 🌟 Key Features

* **Accordion Flex Layout:** Uses dynamic `flex-grow` properties to expand slides smoothly on click.
* **Grayscale-to-Color Transition:** Inactive slides are aesthetically desaturated, popping into full color upon interaction.
* **Animated Data Reveal:** Car specifications and performance badges slide into view with staggered `cubic-bezier` animations.
* **Dual Navigation:**
    * **Interactive:** Click any slide to expand/collapse.
    * **Controls:** Dedicated Next/Prev buttons and Keyboard Arrow Key support.
* **Responsive Design:** Automatically switches from a horizontal layout to a vertical stack for mobile devices.

---

## 🛠️ Technical Breakdown

### 🎨 CSS Highlights
The slider utilizes a complex transition system to ensure the expansion feels premium:
* **Transition Timing:** `cubic-bezier(0.4, 0, 0.2, 1)` for a natural, snappy feel.
* **Glassmorphism:** Navigation arrows use `backdrop-filter: blur(10px)` for a modern UI look.
* **Overlay Gradients:** A bottom-heavy linear gradient ensures text readability against varied background images.

### 🧠 JavaScript Logic
The logic is encapsulated in an `AccordionSlider` class to maintain a clean global scope:
* **State Management:** Tracks the `currentIndex` to allow for "toggle" behavior (clicking an active slide collapses it).
* **Event Listeners:** Efficiently handles click events, button triggers, and `DOMContentLoaded` initialization.

---

## 📂 Project Structure

| File | Description |
| :--- | :--- |
| `index.html` | Contains the semantic structure and car data (Specs, Images, Brands). |
| `style.css` | Handles the layout, animations, and mobile-responsive media queries. |
| `script.js` | Contains the OOP logic for the slider's interactivity. |

---

## 🚀 Getting Started

1.  **Clone the files** into your project directory.
2.  Ensure your file structure matches the references in the HTML:
    * `<link rel="stylesheet" href="./style.css">`
    * `<script src="./script.js"></script>`
3.  **Open `index.html`** in any modern browser to view the slider.
