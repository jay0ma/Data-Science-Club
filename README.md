# Data Science Club — Website

This repo contains a simple informational website for the Data Science Club. It uses plain HTML and CSS with placeholder content (Lorem ipsum).

The design has been updated to a more professional layout with improved typography, a responsive navigation, refined hero section, and polished cards.

How to view
- Open `index.html` in your browser (double-click in a file manager).

Optional: serve with a simple HTTP server (Python 3) from the repo root (fish shell):

```fish
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

Files in this repo:
- `index.html` — main page with placeholder sections (About, Goals, Leaders, Events, Contact)
- `styles.css` — polished site styles
- `README.md` — this file

Next steps you might want to do:
- Replace placeholder text with real club details and leader bios
- Add real images for leaders (currently inline SVG placeholders)
- Add automated event data (JSON) and a small script to render events

If you'd like, I can add any of those next. (For example: wire a simple JSON-driven events list or prepare the site for GitHub Pages.)

This repository now includes an interactive monthly calendar under the "Upcoming Events" section. The calendar shows placeholder events and supports month navigation. Click a day to see events for that date.

How to view locally (quick):

```fish
python -m http.server 8000
```

Open http://localhost:8000 and navigate to the Events section.
