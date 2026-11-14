# TripForge — Tour Operator Platform

A responsive travel-planning web app built with **HTML, CSS, and vanilla JavaScript**. It stores user-created trips, itinerary activities, favorites, and preferences in the browser's `localStorage`.

## Features

- Dashboard with trip, destination, and budget summaries
- Create, edit, search, filter, share, and delete trips
- Destination discovery with search and region filter
- Favorite destinations
- Day-wise itinerary planner with add/remove activities
- Budget overview with currency selection
- Share trip details using the device share sheet or copy-to-clipboard fallback
- Export trips to CSV
- Responsive desktop and mobile layout
- Sample data included on first launch

## Run the project

### Option 1: Open directly
Open `index.html` in a modern browser. Most features work without a server.

### Option 2: Run with VS Code Live Server
1. Extract the ZIP.
2. Open the `tripforge` folder in VS Code.
3. Install the **Live Server** extension if needed.
4. Right-click `index.html` and choose **Open with Live Server**.

## Project structure

```text
tripforge/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
└── README.md
```

## Important notes

- This is a frontend recreation based on the visible TripForge feature set, not the original Netlify source repository.
- Data is saved in the current browser/device using `localStorage`. It does not sync across devices and clearing browser site data may remove it.
- Destination photos are loaded from Unsplash, and Google Fonts are loaded online. For offline use, replace those remote assets with local image/font files.
- CSV export is available from the **My Trips** page.
- This starter app does not include user accounts, a hosted database, live flight/hotel booking, or live maps.
