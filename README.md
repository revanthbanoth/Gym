# IronPeak Fitness Website

A complete, modern, and professional gym website designed as a single HTML file. This project is built to provide a premium digital experience with dynamic animations, sleek typography, and a dark, energetic aesthetic.

## 🚀 Features

- **Single File Architecture:** All HTML, CSS, and Javascript are bundled into a single `index.html` file for simplicity and lightning-fast loading.
- **Fully Responsive:** Adapts seamlessly to all devices (Mobile, Tablet, Desktop) using modern CSS flexbox and grid layouts.
- **Scroll Animations:** Integrated `IntersectionObserver` to trigger smooth fade-in animations as elements enter the viewport.
- **Interactive UI Elements:** Hover effects on cards, a sticky navigation bar with a glassmorphism effect, and a dismissible promotional top banner.
- **Dynamic Stats Counter:** An animated numeric counter for displaying gym statistics.
- **Contact Form Simulation:** A fully styled front-end contact form with interactive loading and success states.

## 🎨 Design & Technology Stack

- **Core:** HTML5, CSS3, Vanilla JavaScript
- **Typography:** [Google Fonts](https://fonts.google.com/) (`Rajdhani` for impactful headings, `Inter` for clean body text)
- **Icons:** [Font Awesome 6](https://fontawesome.com/) & Emojis
- **Color Palette:** 
  - Primary: `#ff6b35` (Orange-Red)
  - Secondary: `#1a1a2e` (Dark Navy)
  - Accent: `#e94560` (Red)
  - Background: `#0f0f0f` (Near Black)

## 📁 File Structure

```text
Gym/
│
├── index.html    # The entire website (HTML, styling, and logic)
└── README.md     # Project documentation
```

## ⚙️ How to Run the Code

Since this project consists of a standard, static HTML file with no external frameworks or backend logic needed, running it is extremely simple:

### Option 1: Direct Browser Access (Simplest)
1. Navigate to the `Gym` folder on your computer.
2. Locate the `index.html` file.
3. Double-click the file to open it in your default web browser (Chrome, Edge, Safari, Firefox, etc.).

### Option 2: Live Server (Recommended for Editing)
If you plan to modify the code and want to see changes automatically:
1. Open the project folder in an IDE like **VS Code**.
2. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
3. Right-click the `index.html` file in your editor and select **"Open with Live Server"**.
4. The site will open in your browser at a local address (e.g., `http://127.0.0.1:5500/index.html`) and refresh automatically whenever you save changes.

## ✏️ Customizing the Code

- **Images:** The background uses a high-quality Unsplash image. You can replace the URL in the `.hero` CSS class to change the banner image.
- **Styling:** Colors and fonts can be easily modified by changing the CSS variables located inside the `:root` pseudo-class at the top of the `<style>` block.
- **Content:** Update the text, prices, or links directly inside the HTML markup. No complex build tools or compilers are required.

---
*Demo Site created by EasyWeb | [myeasyweb.in](https://myeasyweb.in)*
