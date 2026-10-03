<div align="center">

  <!-- YouTube Logo -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube Logo" width="220"/>

  # 🎥 YouTube Web UI Clone

  **A pixel-perfect, modern, fully responsive YouTube Front-End UI clone crafted strictly with pure HTML5 & CSS3.**

  [![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=netlify)](https://zippy-daifuku-e896fa.netlify.app/)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![No JS](https://img.shields.io/badge/JavaScript-0%25-yellow?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

  <br />

  <a href="#-overview"><b>Overview</b></a> •
  <a href="#-key-features"><b>Key Features</b></a> •
  <a href="#-css-highlights--techniques"><b>CSS Highlights</b></a> •
  <a href="#-folder-structure"><b>Folder Structure</b></a> •
  <a href="#-getting-started"><b>Getting Started</b></a> •
  <a href="#-live-preview"><b>Live Preview</b></a>

  <br />
  <br />

  <!-- Preview Banner -->
  <img src="https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?auto=format&fit=crop&w=1200&q=80" alt="YouTube Clone Banner" width="100%" style="border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.6);">

</div>

---

## 🌟 Overview

Welcome to the **YouTube Web UI Clone** repository! This project is a pixel-perfect recreation of YouTube's official web application interface, engineered using **only pure HTML5 and CSS3**. 

No JavaScript frameworks, layout libraries (such as Bootstrap or Tailwind), or preprocessors were used. It demonstrates clean DOM structuring, complex CSS Grid & Flexbox alignment, CSS custom properties (variables), media queries, and smooth micro-interactions.

🚀 **[View Live Demo](https://zippy-daifuku-e896fa.netlify.app/)**

---

## ✨ Key Features

| Section | Feature & Functionality Description |
| :--- | :--- |
| **🔍 Top Header Bar** | YouTube logo, responsive centered search input with search & mic icons, right action buttons, and profile avatar. |
| **📁 Navigation Sidebar** | Left navigation bar with Home, Explore, Subscriptions, Originals, YouTube Music, and Library tabs with hover states. |
| **🏷️ Category Filter Bar** | Horizontal scrolling pill navigation (`All`, `Gaming`, `Coding`, `Music`, `Live`, `Tech`, etc.). |
| **🎬 Video Grid Layout** | Multi-column responsive video layout using CSS Grid (`repeat(auto-fit, minmax(...))`). |
| **👤 Channel & Meta Info** | Displays video thumbnails, duration overlays, channel avatar, title, channel name, views count, and upload timestamp. |
| **🌙 YouTube Dark Theme** | Official pitch-dark background styling with custom dark scrollbars. |
| **📱 Full Responsiveness** | Custom `@media` query breakpoints adapting smooth UI transitions from Desktop to Mobile screens. |

---

## 🎨 Interface Preview

<div align="center">

| Desktop View | Mobile Responsive View |
| :---: | :---: |
| <img src="https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?auto=format&fit=crop&w=600&q=80" width="400" alt="Desktop View"/> | <img src="https://images.unsplash.com/photo-1526738549149-8e07eca6c147?auto=format&fit=crop&w=300&q=200" width="200" alt="Mobile View"/> |

</div>

---

## 💡 CSS Highlights & Techniques

### 1. Dynamic Responsive Video Grid System
```css
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px 16px;
  padding: 20px;
}
