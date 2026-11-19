# TechNova 2026 — College Event & Tech Fest Portal

A responsive, multi-file web application built using **HTML5, CSS3, and Vanilla JavaScript** for managing and registering in annual college tech and cultural fest events.

## Folder Structure
```text
TechNova_2026_Event_Portal/
├── index.html       # Main semantic HTML5 structure & registration modal
├── css/
│   └── style.css    # Responsive Flexbox/Grid styling & Dark Mode theme
├── js/
│   ├── data.js      # Structured JSON-like event dataset (8 events)
│   └── app.js       # Filtering, live search, LocalStorage persistence & pass generation
└── README.md        # Project overview & setup guide
```

## Key Features
1. **Dynamic Event Rendering:** Events are loaded dynamically from `js/data.js` rather than hardcoded in HTML.
2. **Real-Time Category Filter & Search:** Filter by Technical, Cultural, Gaming, or Workshop, and search simultaneously by keyword or venue.
3. **Interactive Registration & Pass Generator:** Validates student inputs and generates a unique `PASS-XXXX` ID.
4. **Browser Persistence (`localStorage`):** Registered events and Dark/Light mode preferences remain saved even after refreshing the page.
5. **3-Day Master Schedule:** Auto-populated tabular timetable for quick reference.

## How to Run
1. Extract the ZIP file.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox). No server or internet connection required.
