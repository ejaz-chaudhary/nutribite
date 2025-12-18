# MERN Stack — Frontend

This repository contains the frontend static assets for a MERN-stack application (HTML/CSS/JS). It's a simple, static frontend primarily consisting of an `index.html` file and supporting resources.

## Features
- Single-page static frontend
- Organized resources under `resources/` (CSS, images, JS)
- Vendor CSS in `vendors/`

## Prerequisites
- A modern web browser
- (Optional) `live-server` or another static file server for local dev

## Install / Run
1. Open `index.html` directly in your browser, or run a static server from the project root:

```bash
# using npm package 'live-server' (install globally if needed)
live-server .
```

2. Visit the served URL (usually `http://127.0.0.1:8080`).

## Project Structure
- `index.html` — main HTML file
- `resources/`
  - `css/` — main styles (e.g., `style.css`)
  - `img/` — images used by the frontend
  - `js/` — custom JavaScript
- `vendors/` — third-party CSS (e.g., `grid.css`, `normalize.css`)
- `fonts/` — font files

## Notes
- This frontend is static; connect it to your backend APIs (Express/MongoDB) as needed.
- Keep assets organized under `resources/` for clarity.

## Contributing
Feel free to open issues or submit pull requests to improve the frontend.

## License
Add a license file or specify a license here.
