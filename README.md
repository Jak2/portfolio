# Jaya Arun Kumar Tulluri - Personal Portfolio

A sleek, animated, and minimalist personal portfolio leveraging modern web design principles like Neo-Brutalism, Glassmorphism, and Neumorphism. This portfolio showcases professional experience, core competencies, and personal projects in a highly performant, single-file HTML architecture.

## Architecture

This project originally started as an Astro + Tailwind documentation site but has been refactored entirely into a **single, dependency-free HTML file (`index.html`)** for maximum portability, simplicity, and performance. 

- **Zero-Build Pipeline:** No Node.js build steps or complex bundlers required for production.
- **Embedded CSS & Scripts:** All Tailwind directives, custom CSS (glassmorphism/neumorphism), and lightweight scroll animations are contained directly within the file.
- **Offline Capable:** Drop the file into any browser and it works immediately.

## Design Highlights

- **Glassmorphism:** Elegant frosted glass layers (`.glass-card`, `.glass-nav`) with subtle ambient blur over an animated, deep-space gradient background.
- **Neumorphism:** Tactical use of inset and drop shadows (`.neu-tag`) for skill pills, complementing the dark aesthetic.
- **Responsive Layout:** A fixed navigation bar on desktop that transitions to a sleek, glassmorphism off-canvas menu for mobile viewing.
- **Micro-interactions:** Custom hover effects, CSS keyframe gradient text animations, and automated scroll reveal states (`IntersectionObserver`).

## Tech Stack

- **HTML5:** Semantic architecture
- **CSS3 / Tailwind CSS (CDN):** Core styling engine with custom variants
- **JavaScript (Vanilla):** Scroll observers and mobile menu toggles

## Getting Started

Because the project has been simplified to its purest form, there are no dependencies to install.

### Running Locally

**Method 1: Direct File Access**
Double-click `index.html` to open it in any modern browser.

**Method 2: Live Server (Recommended for development)**
If you are using VS Code, use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension to serve the file and get hot-reloading on save.

**Method 3: npm serve**
If you have Node installed, you can still use:
```bash
npm install -g serve
serve .
```

### Deployment

To deploy, simply upload the `index.html` wrapper to any static hosting provider.
- **Netlify Drop:** Drag and drop the folder into Netlify.
- **GitHub Pages:** Select your main branch root for deployment.
- **Vercel / Cloudflare Pages:** Connect repository and deploy instantly with no build command.

## Customization

To edit the portfolio, simply open `index.html`. 
- **Personal Details:** Search for standard IDs like `#hero`, `#about`, `#experience` to modify text.
- **Styling:** Top `<style>` block contains all custom CSS classes and animations.

## Author

**Jaya Arun Kumar Tulluri**
- **Role**: Senior Systems Engineer
- **Email**: jayaarunkumartulluri2@gmail.com
- **LinkedIn**: [Jaya Arun Kumar Tulluri](https://linkedin.com/in/jayaarunkumar-tulluri)
