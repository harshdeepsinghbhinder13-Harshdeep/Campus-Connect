# Campus Connect

A student portal website for a college: events, announcements, study resources and clubs.
It's plain HTML and CSS, so there's no build step and nothing to install.

## Open it
Double-click `index.html`.

## Pages
- index.html: landing page
- dashboard.html, events.html, announcements.html, resources.html, clubs.html, profile.html: the student portal

## Notes
- Bootstrap (CSS only) and Bootstrap Icons are in the `css` folder, so it works offline.
  The fonts (Inter, Source Serif 4) load from Google Fonts. Without internet it falls back to system fonts.
- There is no JavaScript. Event and notice details open as pop-ups using the URL hash, the category filters are radio buttons, and the Register / Join buttons are checkboxes, so they reset when the page is reloaded.
- All names, dates and notices are made-up sample data.
