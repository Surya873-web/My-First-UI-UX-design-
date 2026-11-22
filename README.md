# Wandervista

A responsive, interactive travel experience for discovering slow journeys, local food trails, and relaxed weekend escapes.

## About

Wandervista presents travel inspiration through a polished multi-screen interface. It combines destination discovery, curated recommendations, trip saving, and a simple favorites flow in a single static web page.

## Features

- Responsive layout for desktop and mobile
- Multi-screen travel and onboarding experience
- Destination and attraction discovery
- Curated food and travel recommendations
- Interactive saved places
- Accessible keyboard focus styles
- GitHub Pages deployment workflow

## Project Structure

```text
.
|-- index.html
|-- .github/
|   `-- workflows/
|       `-- pages.yml
`-- README.md
```

## Run Locally

No build tools or dependencies are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/Surya873-web/My-First-UI-UX-design-.git
   cd My-First-UI-UX-design-
   ```

2. Open `index.html` directly in a browser.

   Alternatively, serve the project locally:

   ```bash
   python -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

## Deployment

The repository includes a GitHub Actions workflow that publishes the site to GitHub Pages whenever changes are pushed to `main`.
