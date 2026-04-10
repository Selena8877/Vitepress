# Vitepress

Lab 14 — PaperBeam VitePress Site

This lab uses VitePress to build a documentation-style website for the fictional web technology PaperBeam.


Directory Hierarchy
```text
L07-08/
├─ README.md
├─ package.json
├─ package-lock.json
├─ docs/
│  ├─ index.md
│  ├─ products.md
│  ├─ api.md
│  ├─ contact.md
│  ├─ learning/
│  │  ├─ docs.md
│  │  ├─ tutorials.md
│  │  └─ examples.md
│  ├─ .vitepress/
│  │  ├─ config.mjs
│  │  └─ theme/
│  │     └─ custom.css
│  └─ public/
│     ├─ logo.png
└─      └─ pb-hero.png
```

How to Run

Install dependencies:

npm install

Start the VitePress development server:

npm run docs:dev

Then open:

http://localhost:5173/
PaperBeam Site Description

Lab Requirements
Part 1 — Basic VitePress Site

The site must include:

A working homepage with the provided logo
Customized hero text including title, text, and tagline
At least two action buttons on the homepage that link to pages
Three fictional features, each with a different icon
Six total working pages filled with original writing:
Three pages at the root level
Three subpages inside /learning

Example page layout:

Root pages:
products.md
api.md
contact.md
Learning pages:
learning/docs.md
learning/tutorials.md
learning/examples.md

Across the six pages, include at least two examples each of:

Markdown tables
Emojis or icons
Custom containers
Different heading levels
Lists
Code snippets
At least one JavaScript example
At least one HTML example
Part 2 — Extending the Default Theme

The site must also include:

A top nav bar with a site title and icon on the left
Four nav bar items total
One nav item called Learning with a dropdown menu containing at least three pages
A sidebar on every page except the homepage
A sidebar with at least two grouped sections such as:
Overview
Learning
Custom CSS Requirements

The homepage action buttons must be styled as follows:

The main action button should be green: #13b38e
The secondary action button should use the standard grey style
On hover, the secondary action button should turn pink: #ee9bdd
Key Features
Multi-page VitePress site for the fictional PaperBeam platform
Homepage with logo, hero section, and action buttons
Feature section with custom icons
Root pages and learning subpages
Navbar with dropdown menu
Sidebar navigation for internal pages
Markdown formatting examples across the site
Custom CSS styling for button colours and hover effects
