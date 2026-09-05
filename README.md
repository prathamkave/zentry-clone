# Zentry Website Clone

A modern, immersive website clone inspired by the original **Zentry** website, built to practice advanced frontend development, animations, responsive layouts, and interactive UI using **React, GSAP, and Tailwind CSS**.

This project focuses heavily on creating a smooth, cinematic user experience with scroll-based animations, dynamic transitions, clip-path effects, interactive cards, and responsive design.

> **Note:** This is a personal educational clone created for learning and practice purposes. It is not affiliated with or endorsed by Zentry.

---

## Live Demo

**Live Website:**

**GitHub Repository:** https://github.com/prathamkave/zentry-clone

---

## About The Project

The goal of this project was to recreate the visual experience and interactive behavior of the Zentry website while understanding how modern frontend animation techniques work in a real-world project.

Instead of building a simple static landing page, I focused on reproducing the experience through:

- Smooth scroll-based animations
- GSAP-powered transitions
- Interactive hover effects
- Clip-path based shapes and transitions
- Video-based sections
- Animated typography
- Bento-style layouts
- Responsive design
- Reusable React components

The project helped me understand how animation, layout, typography, and interaction can work together to create a premium web experience.

---

## Tech Stack

### Frontend

- **React.js** — Component-based UI development
- **Tailwind CSS** — Utility-first styling and responsive layouts
- **GSAP** — Advanced animations and scroll interactions
- **JavaScript (ES6+)** — Application logic and interactions
- **HTML5** — Semantic structure
- **CSS3** — Custom animations, clip-paths, and styling

### Development Tools

- **Vite** — Fast development environment
- **Git** — Version control
- **GitHub** — Repository management
- **VS Code** — Development environment

---

## Features

### Smooth Scroll Animations

Animations are triggered based on the user's scroll position to create a dynamic and engaging browsing experience.

### GSAP Animations

GSAP is used for creating complex animations and controlling the timing and sequence of multiple UI elements.

### Clip-Path Animations

Custom CSS `clip-path` shapes are used to create unique transitions and geometric visual effects.

### 3D Hover Effects

Interactive elements respond to mouse movement with 3D transformations, giving the interface more depth.

### Animated Typography

Large headings and text elements are animated using transforms, opacity, rotation, and custom typography.

### Video Transitions

Video elements are integrated into different sections to create a more cinematic storytelling experience.

### Bento Grid

The project contains an interactive bento-style section with different card sizes and hover interactions.

### Responsive Design

The website adapts to different screen sizes including:

- Desktop
- Laptop
- Tablet
- Mobile

### Reusable Components

The UI is divided into reusable React components to keep the codebase organized and maintainable.

---

## Project Structure

```text
zentry-clone/
│
├── public/
│   ├── assets/
│   ├── fonts/
│   └── videos/
│
├── src/
│   ├── components/
│   │   ├── About.jsx
│   │   ├── AnimatedTitle.jsx
│   │   ├── BentoTilt.jsx
│   │   ├── Button.jsx
│   │   ├── Contact.jsx
│   │   ├── FloatingImage.jsx
│   │   ├── Footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   ├── RoundedCorners.jsx
│   │   └── Story.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

> Your exact folder structure may differ depending on how you organized the project.

---

## Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- Git

You can verify your installations with:

```bash
node -v
npm -v
git --version
```

---

## Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate into the project

```bash
cd zentry-clone
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open the project

Visit:

```text
http://localhost:5173
```

---

## Available Scripts

### Development

```bash
npm run dev
```

Starts the Vite development server.

### Production Build

```bash
npm run build
```

Creates an optimized production build.

### Preview Production Build

```bash
npm run preview
```

Runs the production build locally for testing.

---

## Animation Concepts Used

One of the main purposes of this project was learning how modern web animations are structured.

### GSAP

Used for:

- Timeline animations
- Scroll-triggered animations
- Element transformations
- Opacity transitions
- Rotation
- Scaling
- 3D transforms

### ScrollTrigger

Used to synchronize animations with the user's scroll position.

Example:

```js
gsap.to(element, {
	scrollTrigger: {
		trigger: element,
		start: "top center",
		end: "bottom center",
		scrub: true,
	},
	scale: 1.2,
	rotation: 5,
});
```

### CSS Clip-Path

Used to create custom shapes and transitions:

```css
clip-path: polygon(4% 0, 83% 21%, 100% 73%, 0% 100%);
```

### 3D Transformations

Interactive elements use transformations such as:

```css
transform: translate3d(...) rotateX(...) rotateY(...) scale(...);
```

---

## What I Learned

Building this clone helped me strengthen my understanding of:

- React component architecture
- GSAP animation timelines
- ScrollTrigger
- DOM-based animations
- CSS clip-path
- 3D transformations
- Responsive design
- Tailwind CSS
- Custom fonts
- Reusable components
- Interactive UI development
- Animation performance
- Structuring a modern React project

The biggest takeaway was understanding that a high-quality website is not only about the design. The **timing, movement, transitions, spacing, and interaction** are equally important.

---

## Challenges Faced

Some of the challenging parts of this project included:

- Creating smooth scroll-based animations
- Synchronizing multiple animations
- Recreating complex clip-path transitions
- Handling responsive animations
- Managing video transitions
- Creating interactive 3D hover effects
- Keeping animations smooth across different devices
- Maintaining reusable React components while working with animation-heavy sections

---

## Future Improvements

Some improvements I can make in the future:

- Add more micro-interactions
- Improve mobile-specific animations
- Optimize video and image assets
- Improve accessibility
- Add reduced-motion support
- Improve animation performance
- Add more interactive sections
- Optimize the project for production

---

## Credits & Inspiration

This project is inspired by the design and interaction patterns of the **Zentry** website.

All original design, branding, assets, and intellectual property belong to their respective owners.

This clone was created strictly for:

- Learning
- Practice
- Frontend development experimentation
- Understanding modern animation techniques

This project is **not intended for commercial use**.

---

## Disclaimer

This is an independent educational project created as a frontend development practice exercise.

**Zentry** and its associated branding/design belong to their respective owners. This project is not affiliated with, sponsored by, or officially connected to Zentry.

If this project is ever used publicly or commercially, original assets and branding should be replaced with content that I own or have permission to use.

---

## Author

### Pratham Kave

Frontend Developer | React Developer | Full Stack Developer

**GitHub:** https://github.com/prathamkave
**LinkedIn:** https://www.linkedin.com/in/pratham-kave/

---

## ⭐ If You Like The Project

If you found this project interesting, consider giving the repository a **star** on GitHub.
