# Copilot Instructions (50projects50days)

## Repository context
This repo is a collection of small, mostly standalone HTML/CSS/vanilla-JS mini projects ("50 Projects in 50 Days").
Changes should usually be scoped to a **single project folder**.

---

## Project structure
- Each project lives in its own directory (see README project table).
- Expect plain `index.html`, `style.css`, `script.js` patterns per project.

---

## When generating or editing code
- Keep solutions **framework-free** unless the target project already uses a framework.
- Prefer **vanilla JavaScript** and modern DOM APIs.
- Avoid introducing build steps, bundlers, or additional dependencies.
- Keep code readable for beginners: short functions, clear variable names, and inline comments only where helpful.

---

## Styling conventions
- Prefer simple, scoped CSS for the project folder you are editing.
- Avoid global CSS that could affect other project folders.

---

## Bug fixes / enhancements
- Make changes only within the relevant project directory.
- Do not refactor unrelated projects.
- If adding a new feature, include a brief note in the project’s README (if present) or comments.

---

## Security & safety
- Never add secrets or tokens.
- If a project fetches external APIs, include basic error handling and user-friendly fallback UI.

---

## Testing / validation
- There is no central test runner; validate by running the project in the browser.
- Ensure the page loads without console errors and works on mobile widths where relevant.
