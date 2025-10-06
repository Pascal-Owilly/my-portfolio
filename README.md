# Pascal Ouma - Django & React Developer Portfolio

A stunning, professionally designed portfolio website showcasing **Pascal Ouma's** expertise as a full-stack developer specializing in **Django** and **React** applications. This portfolio features advanced animations, parallax effects, and a modern UI/UX design that creates a memorable experience for visitors.

---

## 💻 Live Demo & Screenshots

**Live Demo (Self-Host):** [Open `index.html` in your browser]

**Featured Image (Code/Design Inspiration):**



---

## 🌟 Features

### ✨ Visual & Interactive Elements
* **Advanced CSS Animations:** Smooth entrance animations, hover effects, and transitions.
* **Parallax Scrolling:** Dynamic background elements that create depth.
* **Glassmorphism Design:** Modern `backdrop-filter` effects for the header.
* **Scroll-Triggered Animations:** Elements animate as you scroll through the page using lightweight JavaScript.
* **Custom Scrollbars:** Styled scrollbars matching the color scheme.

### 🎨 Design Excellence
* **Professional Color Palette:** Deep purple, dark grey, and accent green colors.
* **Responsive Layout:** Fully responsive design for all device sizes.
* **Card-Based Design:** Modern card layouts for services and projects.

### ⚡ Technical Features
* **Pure CSS Solution:** No heavy external frameworks required.
* **Optimized Performance:** Efficient animations using `will-change` and minimal JavaScript.
* **SEO Optimized:** Proper meta tags and semantic HTML.

---

## 🛠️ Technologies Used
| Category | Technology | Description |
| :--- | :--- | :--- |
| **Markup** | HTML5 | Semantic markup structure. |
| **Styling** | CSS3 & Custom Properties | Advanced styling, **CSS Grid**, **Flexbox**, and consistent theming. |
| **Interactivity** | Vanilla JavaScript | Lightweight scroll animations and minor DOM manipulation. |
| **Advanced CSS** | `backdrop-filter`, `scroll-snap-type`, `clip-path` | Unique UI/UX effects. |

---

## 📱 Sections

1.  **Hero Section:** Professional introduction, key value proposition ("make mediocre systems look brilliant"), and primary CTAs. Features a unique `clip-path` profile image.
2.  **Services Section:** Horizontal scrolling service cards with **scroll-snapping**. Services include: Urgent Bug Fixes, Small Business Websites, POS & Inventory Systems, HRM Systems, Clinical EMR Systems, and more.
3.  **Projects Section:** Project showcase with technology tags and subtle card hover effects.
4.  **Contact Section:** Direct links to WhatsApp, Email, and GitHub with animated contact items.

---

## 🎯 Unique CSS Features

This portfolio utilizes several rare and advanced CSS techniques for maximum visual impact:

| Feature | CSS Property/Value | Purpose |
| :--- | :--- | :--- |
| **Glassmorphism Header** | `backdrop-filter: blur(12px);` | Frosted glass effect for the sticky navigation. |
| **Horizontal Scrolling** | `scroll-snap-type: x mandatory;` | Ensures service cards snap perfectly into view. |
| **Performance Hint** | `will-change: scroll-position, transform;` | Optimizes browser rendering for smooth animations. |
| **Custom Shape** | `clip-path: polygon(...);` | Used on the profile image for a distinctive, non-rectangular shape. |
| **Custom Scrollbar** | `scrollbar-width: thin;` (Firefox) & `::-webkit-scrollbar` (Chrome/Safari) | Branded scrollbars for the services section. |

---

## 🚀 Installation & Setup

### Option 1: Direct Use (Simplest)
1.  Copy the entire code block below.
2.  Paste it into a file named `index.html`.
3.  Open `index.html` in any modern web browser. **No server required.**

### Option 2: Customization
1.  Clone or download the repository.
2.  Open `index.html` in a code editor.
3.  Customize your personal details (see guide below).

### Personalization Guide

| Element | HTML Location | Instruction |
| :--- | :--- | :--- |
| **Profile Image** | `<div class="profile-image">` | Replace the `img src="..."` with your photo URL. |
| **Contact Info** | `<section id="contact">` | Update the `href` and text for WhatsApp, Email, and GitHub. |
| **Color Scheme** | CSS `:root` block | Modify CSS custom properties (`--primary`, `--accent`, etc.) for instant theming. |
| **Services/Prices** | `<div class="service-card">` | Update text and price ranges to match your current offerings. |

---
