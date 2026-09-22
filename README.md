# 1Portfolio Umar

A React + Vite portfolio website for personal branding and project showcase.

## Project Overview

This project is a portfolio template built with:
- React
- Vite
- Bootstrap
- SCSS
- JSON-driven content sections

The site content is mostly controlled through JSON files in the `public/data` folder, which makes it easy to update your profile, education, experience, skills, and portfolio without changing React components.

## Folder Structure

```text
.
├── public/
│   ├── data/
│   │   ├── sections.json
│   │   ├── profile.json
│   │   ├── settings.json
│   │   ├── strings.json
│   │   └── sections/
│   │       ├── cover.json
│   │       ├── education.json
│   │       ├── experience.json
│   │       ├── portfolio.json
│   │       ├── skills.json
│   │       ├── achievements.json
│   │       ├── updates.json
│   │       └── contact.json
│   └── images/
├── src/
│   ├── components/
│   ├── hooks/
│   ├── providers/
│   ├── styles/
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
├── README.md
└── node_modules/
```

## Main Content Editing

The website pulls content from the JSON files in `public/data`.

The most important files to edit are:
- `public/data/profile.json` — name, status, roles, profile picture
- `public/data/settings.json` — app-wide behavior and theme settings
- `public/data/sections.json` — section list and JSON paths
- `public/data/sections/*.json` — actual section content for education, experience, skills, etc.

Example:
- Education content: `public/data/sections/education.json`
- About section: `public/data/sections/cover.json`
- Contact section: `public/data/sections/contact.json`

## Getting Started

Install dependencies:

```bash
npm install
```

Run the app in development mode:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Available Scripts

```bash
npm run dev
npm run build
npm run lint
npm run preview
npm run resume:make:article
npm run resume:clear
```

## Notes

- Do not edit files in the `dist/` folder; they are generated build files.
- Edit the source content in `public/data` instead.
- If the app does not reflect changes, make sure the Vite dev server is running and you are viewing the correct localhost URL.

## License

This project is intended for personal portfolio use. Check the project ownership and licensing details before publishing externally.

Anyway if you want the original repository template you can it from : https://github.com/ryanbalieiro/react-portfolio-template.git
