# AI Usage Report: Ali Alhashem Portfolio

## 1. Tools Used & Use Cases
* **Gemini (Google):** Primary AI collaborator used for generating the initial HTML5 boilerplate, designing the responsive CSS Flexbox layout, and drafting the theme-switching logic in JavaScript.
* **VS Code:** Utilized for writing code, debugging file path errors, and previewing Markdown documentation.

---

## 2. Benefits & Challenges

### **Benefits**
AI significantly accelerated the development of the responsive grid logic. It provided clear explanations of modern CSS properties like `flex-basis` and `calc()`, which helped me build a lightweight site without needing heavy external frameworks like Bootstrap.

### **Challenges**
One major challenge was a "white page" error where the CSS failed to load. I used AI to troubleshoot this and discovered it was a directory path issue. I learned that the browser's relationship with folders is literal and case-sensitive.

---

## 3. Learning Outcomes
Through this AI-assisted workflow, I gained a deeper understanding of:
* **Persistent State:** Using `localStorage` to ensure the user's "Dark Mode" choice remains active even after a page refresh.
* **Event Handling:** Learning how `e.preventDefault()` stops the default browser "jump" to allow for smooth scrolling animations.
* **The Box Model:** Understanding how `box-sizing: border-box` prevents padding from breaking the layout width.

---

## 4. Responsible Use & Modifications
I actively reviewed and refined all AI-generated content to ensure it followed the assignment's "Mobile-First" and "Clean Code" requirements:

* **Code Refactoring:** I identified and manually removed duplicate HTML sections that were accidentally created during the coding process. 
* **Semantic Correction:** I reorganized the AI's initial section structure to ensure proper nesting (e.g., ensuring `<article>` tags were inside the correct `<section>`).
* **Verification:** I did not treat the AI as a "black box." I requested technical breakdowns of commands like `document.querySelectorAll` to ensure I could explain the logic during a code review.
* **Styling Customization:** I adjusted the generated CSS hex codes and spacing values to match my personal design preference and to ensure high contrast for accessibility.

---

## 5. Ethical Reflection
Using AI allowed me to focus on the "Architecture" of the site rather than getting stuck on syntax. By verifying every line of code provided by the AI, I ensured that the final project is a true reflection of my own learning and technical decisions.