# Open Libra Website

This is a static website for Open Libra - The Future, Secured. It's built with modern web technologies including Tailwind CSS and Alpine.js.

## Project Structure

```
├── index.html          # Main landing page
├── faq.html            # FAQ page
├── data/
│   ├── text-content.json   # Website content data
│   └── manifesto.txt       # The Core Pledge document
├── assets/
│   └── logo.svg           # Open Libra logo
└── README.md              # This file
```

## Features

- Responsive design using Tailwind CSS
- Interactive components with Alpine.js
- Dynamic content loading from JSON
- Modern typography with Google Fonts (Poppins & Roboto)
- Clean, professional design with custom brand colors

## How to Run

Since this is a static website, you can run it in several ways:

### Option 1: Simple HTTP Server (Python)
```bash
python -m http.server 8000
```
Then visit: http://localhost:8000

### Option 2: Simple HTTP Server (Node.js)
```bash
npx http-server
```

### Option 3: VS Code Live Server Extension
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Alpine.js** - Lightweight JavaScript framework for interactivity
- **Google Fonts** - Poppins and Roboto font families

## Content Management

All text content is stored in `data/text-content.json` for easy editing without touching the HTML structure. The website dynamically loads this content using Alpine.js.

## Brand Colors

- **Brand Red**: #E75A5C
- **Brand Cream**: #FAF3E7  
- **Brand Charcoal**: #4A3B3C

## Original Source

Downloaded from: http://0o-de-lally.github.io/static-new/index.html
