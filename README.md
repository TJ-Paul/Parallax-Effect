# 🌄 Parallax Scrolling Website

A visually immersive, multi-layered parallax scrolling website built using **HTML5**, **CSS3**, and vanilla **JavaScript**. This project demonstrates how scroll-driven events can animate layered imagery and text dynamically to create a sense of true 3D depth.

---

## 🔗 Live Demo

Check out the live interactive website here:  
👉 **[Parallax Effect Live Link](https://tj-paul.github.io/Parallax-Effect/)**

---

## ✨ Features

- **Multi-layered Parallax Effects:** Smooth scrolling translations mapping 9 distinct graphical and text layers.
- **Pure JavaScript Implementation:** Uses standard `window.scrollY` event listeners without relying on heavy third-party animation libraries.
- **Responsive Layer Architecture:** Uses modern CSS with `object-fit: cover` to manage background asset proportions seamlessly across standard screens.
- **Sleek Navigation Bar:** A clean, fixed-style header providing responsive interactive hover states.

---

## 📂 Project Structure

```text
├── index.html       # Structural markup containing the navigation header and parallax layers
├── style.css        # Core layout, reset rules, Google Font integration, and layer depth configurations
├── script.js        # Scroll offset calculation engine mapping styles dynamically
└── images/          # Assets folder housing transparent parallax graphics (hills, leaves, trees, plants)
    ├── hill1.png
    ├── hill2.png
    ├── hill3.png
    ├── hill4.png
    ├── hill5.png
    ├── leaf.png
    ├── plant.png
    └── tree.png
