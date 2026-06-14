# first-tailwind-project

A simple dashboard UI built with **Vite** and **Tailwind CSS**. The main page is `index.html`, which contains a student list layout (header, sidebar, summary cards, search/filter controls, and a table-like list).

## Tech Stack
- **Vite** (dev server + build tooling)
- **Tailwind CSS**
- **TypeScript** (via `src/main.ts`)

## Project Structure
- `index.html` - Main UI markup (header/sidebar/cards/table)
- `src/style.css` - Tailwind entry stylesheet
- `src/main.ts` - App entry (imports `style.css`)
- `src/assets/` - Images used in the UI
- `vite.config.ts` - Tailwind plugin configuration

## Getting Started
### 1) Install dependencies
```bash
npm install
```

### 2) Run the dev server
```bash
npm run dev
```
Then open the shown local URL in your browser.

## Build
```bash
npm run build
```

## Preview production build
```bash
npm run preview
```

## Notes
- Tailwind styles are applied via class names in `index.html`.
- Assets referenced in the markup are stored under `src/assets/`.

