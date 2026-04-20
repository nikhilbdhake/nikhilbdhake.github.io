# Nikhil Dhake — Personal Site

Personal static website. Intro page today; more pages (projects, blog, etc.) to come.

## Structure

```
Blog/
├── index.html          Intro page
├── css/style.css       Styles (design tokens at top)
├── js/main.js          Small JS
└── assets/             Images, icons, PDFs (add as needed)
```

## Running locally

Just open `index.html` in a browser. Or serve with any static server, e.g.:

```
python -m http.server 8000
```

Then visit http://localhost:8000

## Adding new pages

1. Copy `index.html` to e.g. `projects.html`.
2. Replace the `<main>` content.
3. Add the page to the `.nav-menu` in every HTML file.
4. Reuse classes in `css/style.css` — or add page-specific styles below the existing ones.
