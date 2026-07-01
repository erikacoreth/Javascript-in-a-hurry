# JavaScript Flash Course

A small vanilla JavaScript project that combines several interactive UI features into one page:

- Live greeting based on the time of day
- Local clock display
- Geolocation-based weather lookup with Celsius/Fahrenheit toggle
- Image gallery with selectable thumbnails
- Product listing with paid/free filtering
- Responsive navigation menu
- FAQ section and footer year update

## Getting Started

This project does not require a build step or package install. Open `index.html` directly in a browser, or use a local server such as Live Server in VS Code.

### Recommended

1. Open the folder in VS Code.
2. Install and start Live Server, or open `index.html` in your browser.
3. Allow location access if you want the weather section to load.

## Project Structure

- `index.html` - main page markup
- `main.css` - styling and responsive layout
- `main.js` - all page interactions and dynamic content
- `assets/gallery/` - gallery images
- `assets/products/` - product images
- `assets/socials/` - social media icons
- `assets/json/` - sample JSON data files

## Notes

- The weather feature depends on browser geolocation and an internet connection.
- If location access is blocked, the weather section will show an error message.
- The gallery and product sections are populated from arrays inside `main.js`.

## Browser Support

This project is intended for modern browsers that support ES6 JavaScript, `fetch`, and geolocation APIs.
