# GitHub CI/CD Example by Let’s Tech

A minimal, responsive landing page with a dark background, high contrast UI, and Sora typography.

## Preview

Open `index.html` in your browser. No installation or build step is required.

## Features

- Responsive layout for desktop and mobile.
- Interactive, simulated CI/CD pipeline with replay controls.
- Copyable GitHub Actions workflow example.
- Keyboard focus indicators and reduced motion support.
- Staggered entrance and scroll reveals, gentle pipeline tilt, button sheen, and animated pipeline progress.
- All page styles and scripts included in one HTML file.

Sora loads from Google Fonts and requires an internet connection. A sans-serif fallback is used when unavailable. Clipboard access depends on the browser; when copying is unavailable, the example code is selected for manual copying.

## Customize

Edit `index.html` to update the content, links, and workflow snippet. The dark palette is defined in the final CSS block, with color variables under `:root`.

## CI/CD demonstration

The pipeline animation is illustrative and does not connect to GitHub or perform deployments. The displayed YAML is a starter CI example for a Node.js project with a committed lockfile and a `build` script. Adapt the Node version and commands to your project, and add your own test and deployment steps.

To use the example in a suitable Node.js repository, save the YAML as `.github/workflows/ci.yml`. This landing page itself is buildless and does not require npm.

## Hosting

Serve `index.html` with any static host. For GitHub Pages, configure the repository’s Pages publishing source to the branch and root folder containing the file.
