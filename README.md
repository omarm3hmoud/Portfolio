# Omar Mahmoud - Portfolio

A premium, fully responsive portfolio website for Omar Mahmoud, building a strong professional brand as a Software Engineer specialized in Frontend and UI/UX design.

## Features
- **Modern UI**: Clean design with the `Plus Jakarta Sans` typography. 
- **Warm Neutral Color Palette**: Extracted from Omar's portrait (Camel, Beige, Charcoal hues).
- **Dark Mode**: Fully implemented with `localStorage` persistence. CSS variables based on hsl logic to preserve tones.
- **Micro-interactions**: Smooth scaling hover effects, smooth scrolling, and scroll-triggered fade-in animations.
- **Responsive Navigation**: Mobile-first Hamburger menu that scales to standard navbar on Desktop devices. 

## Files
- `index.html`: Contains all structures, using semantic tags (`header`, `main`, `section`, `article`, `footer`).
- `css/styles.css`: Uses BEM logic (`.block__element--modifier`), custom properties (variables), media queries, animations.
- `js/script.js`: Handles logic for nav toggling, dark mode activation and IntersectionObserver for fading animations.

## Deployment Instructions

### Option 1: GitHub Pages (Recommended)
1. Initialize a git repository in the root directory: `git init`
2. Add files: `git add .`
3. Commit changes: `git commit -m "Initial commit"`
4. Push to a repository named `Portfolio` or `omarm3hmoud.github.io`.
5. Go to Repo Settings > Pages > Select `main` branch. 

### Option 2: Netlify
1. Create a free account on [Netlify](https://www.netlify.com/).
2. Drag and drop the `portifolio` folder into the Netlify "Sites" dashboard, OR connect your GitHub repository and import the project.

## Note to Developer
- Please save the portrait image provided in the chat into the folder `assets/images` and name it `profile.jpg`.
