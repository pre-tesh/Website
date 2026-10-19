# Pritesh Rodge — Personal Website

Source for my personal portfolio website, hosted with GitHub Pages.

The site introduces my interests in robotics, computer vision, embedded systems,
kernels, and machine learning. It also highlights completed projects, including
my Structure from Motion pipeline, and what I am currently exploring.

## Local preview

From the repository root, serve the `files` directory with any static web server:

```bash
cd files
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Project structure

```text
files/
├── index.html       # Website content
├── style.css        # Site styles
├── Resume_PriteshRodge.pdf
└── fonts/           # Local font assets
```

## Deployment

Push changes to the `main` branch. GitHub Pages is configured to publish the
contents of the `files` directory.
