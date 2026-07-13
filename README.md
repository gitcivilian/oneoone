# Metaversus

> This was my first GitHub repository.

A visually rich, single-page **Metaverse** landing page that presents a futuristic virtual-world concept. The site combines full-screen artwork, animated content sections, interactive world cards, feature highlights, community imagery, and metaverse-themed editorial content.

## Overview

Metaversus is a front-end showcase website focused on an immersive user experience. Visitors can explore a set of fictional virtual worlds, learn how the platform works, view new-feature highlights, discover community-focused content, and read metaverse insights.

The repository contains the exported production files for the site, including the generated HTML, JavaScript bundles, stylesheets, icons, and image assets.

## Features

- Responsive single-page layout for desktop and mobile screens
- Animated hero section and scroll-based content transitions
- Interactive **Explore Worlds** cards that expand when selected
- Metaverse introduction and guided “Get Started” steps
- Feature and update sections with VR-inspired visuals
- Community map section for discovering and inviting people
- Insight/article cards and a testimonial-style section
- Navigation, footer, social-media icons, and branded graphics

## Technology

The compiled site indicates use of:

- **Next.js** for the application and static export
- **React** for UI components and state management
- **Tailwind CSS** for responsive styling and layout utilities
- **Framer Motion** for animations and viewport transitions

## Project Structure

```text
index.html                 Main exported page
404.html                   Custom exported 404 page
_next/                     Generated Next.js JavaScript and CSS assets
*.png                      Page imagery and visual assets
*.svg                      Icons and interface graphics
favicon.ico                Browser favicon
```

## Running the Site Locally

This repository contains a static export rather than the original development source files. You can preview it by serving the project folder with any static web server.

For example, using Node.js:

```bash
npx serve .
```

Then open the local address shown in your terminal.

## Notes

- The original source files and package configuration are not included in this repository.
- To make component-level changes or rebuild the project, the original Next.js source project would be required.
- All visual assets used by the exported website are stored in the root of this repository.
