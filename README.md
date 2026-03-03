A highly interactive, portfolio designed for an Engineer. Built entirely with Vanilla HTML, CSS, and JavaScript.

## ✨ Features
- **Scroll-Linked Animation**: 240-frame image sequence rendered smoothly on an HTML5 `<canvas>` that physically opens a laptop as the user scrolls down the page.
- **Immersive Laptop Interface**: The actual portfolio content lives *inside* the 3D laptop screen, scaling and tracking flawlessly with the animation.
- **Light & Dark Mode**: Seamless toggle mapped to a custom button. Flips the ambient orbs, fonts, and UI surfaces to matching inverse colors. (Defaults to Light Mode).
- **Glassmorphism UI**: Sticky top navigation bar and frosted glass overlay effects.
- **Premium Micro-Interactions**:
  - Custom laggy cursor using `requestAnimationFrame`.
  - 3D tilting project cards based on continuous mouse-position calculations.
  - Dynamic typing terminal animation for hero job titles.
  - Intersection Observer scroll reveals for smooth, staggered fade-ins.
  - Ambient breathing background orbs.
- **Zero Dependencies**: An ultra-fast, entirely vanilla codebase. No React, no Tailwind, no bloat.

## 🚀 How to Run Locally
1. Clone this repository to your local machine.
2. Because it only uses standard web technologies, there are no build steps or dependencies to install!
3. Simply open the `index.html` file in your favorite browser. *(Tip: If you are using VS Code, use the "Live Server" extension for the best local viewing experience).*

## 🌐 Deployment (GitHub Pages)
This project is perfectly structured for free deployment on GitHub Pages:
1. Commit and push all files (including the `index.html` and the `ezgif-frame-...png` files) to a new GitHub repository.
2. Go to your repository's **Settings** tab.
3. Click on **Pages** in the left sidebar.
4. Under "Build and deployment", set the Source to `Deploy from a branch`.
5. Select the `main` branch (and `/root` folder) and click **Save**.
6. Wait about 3-5 minutes, and GitHub will provide you with a live URL to share with recruiters!

## 🛠️ Built With
* **HTML5 Canvas** (for frame-scrubbing)
* **Vanilla JavaScript** (for 3D math & cursor logic)
* **CSS Container Queries** (`cqw` units for perfect laptop-screen scaling)
* **IntersectionObserver API** (for performance-friendly scroll animations)
* **CSS Variables** (for dynamic theme toggling)

---
*Developed by [Harshvardhan Singh](https://github.com/harshvardhansingh903)*