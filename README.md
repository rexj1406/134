# PixelPulse — Fetch & Render

A beginner-friendly image search project built with plain HTML, CSS, and JavaScript. It uses the Wikimedia Commons API and requires no API key.

## Files

- `index.html` — page structure and search form
- `style.css` — responsive dark theme and image-card grid
- `script.js` — form handling, API fetching, JSON parsing, and rendering

## Run the project

1. Extract the ZIP file.
2. Open the extracted folder in VS Code.
3. Open `index.html` in a browser. If you have VS Code Live Server installed, you can use **Open with Live Server**.
4. Search for a topic such as `cats`, `ocean`, or `new york`.

An internet connection is required to retrieve real images.

## Assignment concepts demonstrated

- `addEventListener("submit", ...)`
- `event.preventDefault()`
- `input.value.trim()`
- `encodeURIComponent(query)`
- `fetch()`, `await`, `response.ok`, and `response.json()`
- `document.createElement()` and `appendChild()`
- Clearing old results before rendering
- Ignoring blank searches
- Enhancement: result count and friendly empty/error messages

## GitHub submission reminder

Use your existing public repository from Part 1. Create a feature branch, commit and push your changes, open a pull request into `main`, and submit your own pull request URL in Kalvium.
