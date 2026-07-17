# Media Company Landing Page

A simple landing page project built with Tailwind CSS.

## Project Structure

- `public/`
  - `index.html` – main HTML entry point
  - `style.css` – generated Tailwind output file
  - `Assets/` – static assets used by the site
- `src/`
  - `input.css` – Tailwind input file
- `tailwind.config.js` – Tailwind CSS configuration
- `package.json` – npm scripts and dependencies

## Setup

1. Install dependencies:

```bash
npm install
```

2. Build the Tailwind CSS output:

```bash
npm run build
```

This command watches the input file and regenerates `public/style.css` as you edit.

## Development

Open `public/index.html` in your browser to view the landing page. The project uses Tailwind CSS via `src/input.css` and the configuration defined in `tailwind.config.js`.

## Notes

- Tailwind CSS is configured to scan all HTML files under `public/`.
- Customize the design by editing `src/input.css` and `public/index.html`.
