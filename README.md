# Game Complex

Game Complex is a dark-themed game marketplace prototype built with plain HTML, CSS, and JavaScript.

The current version focuses on the frontend experience and includes:
- A login screen with client-side password validation
- A game browsing interface with featured games, new releases, top sellers, and on-sale sections
- Search and featured-genre filtering
- Scrollable game carousels and responsive game grids
- A game details modal
- Mock game data generated in the browser

## Project Structure

- `index.html` - Main application layout and UI sections
- `styles.css` - Custom styling for layout, cards, forms, navigation, and modal components
- `app.js` - Client-side logic for login flow, mock data generation, filtering, rendering, and interactions

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)

## How To Run

1. Clone this repository.
2. Open `index.html` in your browser.

No build step or package installation is required for the current version.

## Notes

- This repository currently works as a frontend prototype.
- Game listings are generated from mock data in `app.js`.
- Authentication is simulated using `localStorage`.
- A real backend, database, and API integration are not included yet.

## Future Improvements

- Add real user authentication
- Connect the app to a backend service and database
- Replace mock game data with API-driven content
- Add cart, checkout, and account management features
- Improve accessibility and mobile responsiveness
