# Portfolio Website Frontend Clone



## Overview
A sleek, modern portfolio website built with **HTML**, **CSS**, and **JavaScript**. This project demonstrates front-end development skills through clean design, interactive elements, and smooth animations. It's a clone inspired by professional portfolios, featuring sections for hero/intro, skills/projects/certifications, about me, subscribe, and footer. Perfect for showcasing as a personal site or resume piece.

## Features
- **Custom Mouse Cursor**: A small white circle that follows the mouse with subtle scaling effects for a dynamic feel.
- **Page Load Animations**: Elements like the nav, headings, and footer fade in and slide into place on load.
- **Interactive Hover Effects**: Hover over skills/projects/certifications to reveal and animate images with fade, movement, and rotation.
- **Responsive Menu**: Click "MENU" to toggle a dropdown navigation with smooth transitions.
- **Minimalist Design**: Dark theme with uppercase typography, no scrollbars, and full-width sections for a immersive experience.

## Technologies Used
- **HTML5**: Semantic structure for accessibility and SEO.
- **CSS3**: Custom styling, flexbox layouts, transforms, and transitions for responsiveness and visuals (e.g., hidden scrollbar, absolute positioning).
- **JavaScript**: Handles events like mouse movement, hovers, and menu toggling. Uses **GSAP** (a lightweight animation library via CDN) for enhanced smoothness in animations, but core logic is vanilla JS.
- **External Resources**:
  - GSAP CDN for animations (keeps it simple—no heavy setup).
  - Remix Icon for arrows and icons.
  - Custom font: "General Sans".

## Setup Instructions
1. Clone or download the repo.
2. Open `index.html` in a browser—no build tools needed!
3. Internet required for GSAP CDN and external images (e.g., GitHub avatar).
   
Files:
- `index.html`: Structure.
- `style.css`: All styling.
- `script.js`: Interactivity and animations.

## How It Works
- **Cursor Effect**: JS tracks mouse position and updates the circle's transform.
- **Animations**: On load, elements animate in sequence. Hovers use event listeners to update image styles.
- **Menu**: Simple class toggle on click for dropdown visibility.

Test by hovering sections or moving the mouse—keeps it engaging without complexity.

## Future Ideas
- Add mobile touch support for cursor fallback.
- Integrate more JS for scroll effects.


## About Me
Full-stack dev based in India, passionate about clean code and user-friendly sites. Built this to practice front-end basics. Connect on LinkedIn or check my other work!

