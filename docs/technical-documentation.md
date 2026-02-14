# Technical Documentation: Ali Alhashem Portfolio

## 1. Project Overview
This project is a responsive, single-page personal portfolio designed to showcase projects and provide a contact method. The application is built using a **"Mobile-First"** approach to ensure usability across all devices.

---

## 2. Architecture & Design Choices

### **HTML5 (Semantic Structure)**
I chose to use **Semantic HTML5** tags (e.g., `<header>`, `<main>`, `<section>`, `<article>`).
* **Why:** This improves SEO and accessibility for screen readers. It also makes the code easier to maintain by creating a clear hierarchy.

### **CSS Flexbox (Layout & Responsiveness)**
For the project grid and navigation, I implemented **CSS Flexbox**.
* **Why:** Flexbox allows for a fluid layout without the need for heavy frameworks. It is ideal for "stacking" elements (like project cards) on mobile devices while allowing them to sit side-by-side on desktops.
* **Benefit:** It keeps the CSS file small and lightweight, ensuring fast page load speeds.

### **Vanilla JavaScript (Interactivity)**
I opted for **Vanilla JavaScript** rather than a library like jQuery.
* **Why:** This ensures zero external dependencies. For a simple portfolio, native JS provides the fastest execution and keeps the project lightweight.

**Features implemented:**
* **Smooth Scrolling:** Uses the `scrollIntoView` API for a polished navigation experience.
* **Dark Mode Toggle:** Uses `localStorage` to remember user preferences across sessions.

---

## 3. Implementation Details

### **Responsive Grid Logic**
The projects section uses a combination of `flex-wrap: wrap` and a media query to adjust column counts based on screen width:

```css
/* Stacks on mobile, splits on desktop (768px+) */
.project-card {
    flex: 1 1 100%;
}

@media (min-width: 768px) {
    .project-card {
        flex: 1 1 calc(50% - 2rem);
    }
}