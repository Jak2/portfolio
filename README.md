# Jaya Arun Kumar Tulluri - Personal Portfolio

A fast, responsive, and minimalist personal portfolio website built with Astro and Tailwind CSS. The portfolio showcases professional experience, core competencies, and personal projects, driven entirely by Markdown content for easy maintenance.

## Features

- **Markdown-Driven Content**: Easily update work experience, skills, and projects by editing a single markdown file (`src/data/portfolio.md`).
- **Dynamic Theming**: Supports multiple color themes (Amber, Sage, Slate, Rose) and a built-in Dark/Light mode toggle for personalized viewing.
- **Responsive Layout**: Mobile-friendly design featuring an off-canvas sidebar navigation and smooth scrolling for a seamless user experience.
- **High Performance**: Built with Astro for optimized asset delivery and zero-JS-by-default architecture.

## Tech Stack

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Language**: TypeScript / HTML

## System Requirements

- Node.js (v18.0.0 or higher recommended)
- npm (or any preferred Node package manager)

## Getting Started

Follow these steps to set up and run the project locally.

### 1. Installation

Clone the repository and install the dependencies:

```bash
# Install dependencies
npm install
```

### 2. Development

Start the local development server:

```bash
# Start the development server
npm run dev
```

The application will be available at `http://localhost:4321`.

### 3. Build for Production

To create a production-ready build:

```bash
# Build the project
npm run build
```

This will generate the static files in the `dist/` directory, ready to be deployed to your preferred hosting provider.

## Project Structure

```text
portfolio/
├── src/
│   ├── data/
│   │   └── portfolio.md     # Main portfolio content
│   ├── layouts/
│   │   └── Layout.astro     # Global HTML shell and layout
│   ├── pages/
│   │   └── index.astro      # Homepage layout and UI logic
│   └── styles/
│       └── global.css       # Global styles and Tailwind base
├── public/                  # Static assets (images, fonts)
├── astro.config.mjs         # Astro configuration
└── tailwind.config.mjs      # Tailwind CSS configuration
```

## Usage & Customization

- **Update Content**: Edit `src/data/portfolio.md` to update your resume, skills, and projects.
- **Adjust Styling**: Modify `src/styles/global.css` for custom CSS variables or tweak Tailwind utility classes throughout the `.astro` components.
- **Change Themes**: The theme switching logic is handled in `src/pages/index.astro`. You can add or modify themes by updating the data attributes and CSS variables.

## Author

**Jaya Arun Kumar Tulluri**
- **Role**: Senior Systems Engineer
- **Email**: jayaarunkumartulluri2@gmail.com
- **LinkedIn**: [Jaya Arun Kumar Tulluri](https://linkedin.com/in/jayaarunkumar-tulluri)
