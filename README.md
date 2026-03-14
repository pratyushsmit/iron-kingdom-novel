<div align="center">
  
  
  # ⚔️ The Iron Kingdom
  <h3>An Immersive Digital Novel Experience</h3>

  [Live Demo](https://pratyushsmit.github.io/iron-kingdom-novel/) • [Presentation Slides (Link)](#)
</div>

---

## 📖 The Pitch
**The Iron Kingdom** is a premium digital publishing experiment that redefines how stories are told on the web. Set against the gritty backdrop of a brutal fantasy siege, it follows Kaelen, a grizzled veteran, as he holds the line against the relentless Iron Legion. 

We transformed passive reading into an interactive, visceral journey through the geometry of war. It blends high-stakes storytelling with cinematic web design, scroll-triggered animations, interactive 3D elements, and atmospheric particle effects.

---

## ✨ Key Features
- **Cinematic Pacing**: Story elements reveal themselves naturally as the user scrolls, creating a rhythm and suspense akin to turning a page.
- **Proximity Glow & 3D Tilt**: Text containers react mathematically to the user's cursor, tilting in 3D space with a reactive radial glow tracking the physical mouse position.
- **Canvas Particle Engine**: "Theme showers" render 150 individual ember and ash particles using HTML5 Canvas. The particles use physics vectors to actively dodge the user's cursor.
- **Scroll-Triggered FX**: Reading about an earth-shattering blow triggers an actual randomized CSS screen shake, blurring the line between text and sensation.
- **Magnetic UI**: Premium "magnetic" cursor wrapping on interactive elements (buttons, images, navigation hooks).

---

## 🛠️ Technical Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)

### Why Vanilla JS?
This project actively chooses **Vanilla Web Technologies** over heavy frameworks like React. 
By compiling to bare metal DOM manipulation, we ensure maximum performance. Complex animation libraries like GSAP and custom HTML5 Canvas particle engines operate significantly faster when not fighting a Virtual DOM for state reconciliation.

---

## 🏛️ Architecture
A clean, modularized structure separates concerns for readability and scalability:

```text
iron-kingdom-novel/
├── index.html       # The main DOM structure and semantic storytelling.
├── css/
│   └── styles.css   # Custom CSS keyframes, 3D visual shifts, and pulse animations.
└── js/
    └── main.js      # Core animation engine (GSAP timelines, math tracking, Canvas Engine).
```

---

## 🚀 Running Locally

Because this project utilizes browser-native rendering, there are zero build steps required.

1. Download or clone the repository:
   ```bash
   git clone https://github.com/pratyushsmit/iron-kingdom-novel.git
   ```
2. Open `index.html` in your favorite modern browser. That's it. 
*(Alternatively, use right-click -> "Open with Live Server" in VS Code for hot-reloading).*

---
<div align="center">
  <i>"I’m terrified every second. But a warrior isn't someone who lacks fear. A warrior is just someone who’s decided that what they’re standing in front of is more important than what’s coming at them."</i><br><br>
  <b>© MMXXIV THE IRON KINGDOM</b>
</div>
