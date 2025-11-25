# Community Corner – Local Community Events Website

A clean, accessible, fully responsive community events website built with plain HTML, CSS, and vanilla JavaScript.  
No build tools, frameworks, or backend required — everything runs 100% client-side using **localStorage** for persistence.

Live Demo: https://harlynp.github.io/Community-Corner-Project/ 

## Features

- Home page with hero slider and featured events
- Full events listing with search & category filters
- Individual event detail pages with registration form
- Volunteer sign-up form
- Contact form
- Simple admin dashboard (demo login) to manage events, view registrations, volunteers, and newsletter subscribers
- Newsletter subscription
- Accessibility controls:
  - Text size adjustment (100% → 125% → 150% → 200%)
  - High-contrast mode toggle
- Fully responsive (mobile-first)
- All data persisted in the browser via `localStorage`
- No external dependencies except Google Fonts

## Project Structure
community-corner/
├── index.html          # Home page
├── community.html      # Events & Initiatives page
├── contact.html        # Contact page
├── event.html          # Single event detail page
├── admin.html          # Admin dashboard (demo login)
├── styles.css          # All styles
├── script.js           # All JavaScript logic
├── assets/
│   ├── hero1.jpg
│   ├── hero2.jpg
│   ├── hero3.jpg
│   ├── event1.jpg
│   ├── event2.jpg
│   ├── event3.jpg
│   └── default-event.jpg
└── README.md           # This file


## Quick Start (Run Locally)

1. **Clone or download** the repository
   ```bash
   git clone https://github.com/Harlynp/Community-Corner-Project.git
   cd community-corner

2. Open index.html in your browser (double-click the file or drag into Chrome/Firefox).That’s it — the site works instantly!

## Admin Access (Demo Only)

URL: admin.html
Email: admin@community.com
Password: password123

## Warning: This is a demo-only credential. Never use plain-text credentials like this in production.
## Admin Features

Add / edit / delete events
View all event registrations, volunteers, and newsletter subscribers
Export volunteers & subscribers as CSV
Clear all volunteer data (useful for testing)

## Accessibility
The site includes:

Proper ARIA labels and roles
Keyboard-navigable menus and forms
High-contrast mode (WCAG AA/AAA compliant when enabled)
Scalable text up to 200%
Clear focus indicators

## Security Note
This project is intentionally client-side only and uses demo credentials for the admin area.
Never use this exact authentication method on a public production site that handles real personal data.
For real-world use, replace the admin section with proper server-side authentication (e.g., Firebase, Supabase, Node.js + database, etc.).
Contributing
Feel free to fork, open issues, or submit pull requests!
Improvements to accessibility, performance, or new features are very welcome.

## License
MIT License — feel free to use, modify, and redistribute for personal or commercial projects.
