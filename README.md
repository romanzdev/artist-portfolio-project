# John Doe's Ceramics — Artist Portfolio

A simple, elegant single-page portfolio site for a fictional ceramics artist, "John Doe." Built with plain HTML and CSS.

> **Note:** This is a demo project created for learning purposes only, focused on practicing HTML, CSS, and the box model — it is not a real business or production site.

## Overview

The page presents a ceramics studio's work in a clean, gallery-style layout:

- **Header/Nav** — studio name and navigation links (Work, About, Contact)
- **Gallery** — an 8-piece image gallery, each with a title (e.g. *Joshua Vase*, *Larkin Plates*, *Astoria Collection*), laid out in a two-column grid with a subtle hover fade effect on images
- **Footer** — an about blurb, a call-to-action, and contact details (email and phone)

## Tech Stack

- **HTML5** — semantic markup, no JavaScript
- **CSS3** — custom styling with the [Cormorant](https://fonts.google.com/specimen/Cormorant) Google Font

## Project Structure

```
artist-portfolio-project/
├── index.html        # Single page markup
├── css/
│   └── style.css     # All styling
├── img/               # Gallery images (1.png – 8.png)
└── favicon.ico
```

## Getting the Code

Clone the repository with git:

```bash
git clone https://github.com/romanzdev/artist-portfolio-project.git
cd artist-portfolio-project
```

## Running Locally

No build step or dependencies required — just open `index.html` directly in your browser (e.g. double-click the file, or right-click → Open With → your browser).

Alternatively, serve the folder with any static file server, for example:

```bash
npx serve .
```

Then visit the local URL it prints (e.g. `http://localhost:3000`).

## Status

This is a learning/demo project and not intended for production use.
