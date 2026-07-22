# University Event Management Website

A fully responsive University Event Management Website for UET Peshawar, built with pure HTML5 and CSS3.

## Academic Project

- **Course:** Web Technologies (CS 311 / CS 224)
- **Semester:** Summer 2026
- **Instructor:** Mr. Mohammad
- **Institution:** University of Engineering & Technology, Peshawar



## Pages
Home — index.html: Hero banner, featured events, statistics, and gallery sections
Events — events.html: Grid of 8 event cards with image, date, venue, and organizer details
Schedule — schedule.html: Full event timetable in a responsive table
Speakers — speakers.html: Profiles of 6 guest speakers with photo, designation, and bio
Registration — register.html: Multi-field event registration form with fieldsets and checkboxes
Contact — contact.html: Department contacts, FAQ accordion, campus map, and inquiry form

## Features

- Fully responsive layout (Desktop / Tablet / Mobile)
- Sticky, responsive navigation bar with CSS-only mobile menu toggle
- CSS Grid & Flexbox layouts throughout
- CSS custom properties (variables) for consistent theming
- Smooth scrolling and hover/transition effects
- Hero section with gradient overlay and CTA buttons
- Statistics section with styled counters
- Photo gallery grid with hover overlays
- FAQ accordion (CSS-only) on the Contact page
- Styled, accessible registration and contact forms
- Consistent footer with quick links and social icons across all pages
- 5 media query breakpoints for responsive behavior

## Technologies Used

- HTML5 (semantic markup)
- CSS3 (Grid, Flexbox, custom properties, animations)
- No JavaScript — all interactivity is CSS-only

## Responsive Breakpoints

The stylesheet defines 5 media query breakpoints to adapt layout, navigation, and grid columns across desktop, tablet, and mobile screen sizes.

## Color Theme

**Blue Professional Theme**, defined via CSS variables in `style.css`:

| Role | Color |
|---|---|
| Primary | `#1e3a8a` |
| Primary Light | `#3b82f6` |
| Primary Dark | `#1e40af` |
| Accent | `#60a5fa` |
| Secondary | `#6366f1` |

## Project Structure

```
University-Events/
├── index.html              # Home page
├── events.html              # Events listing page (8 event cards)
├── schedule.html             # Event schedule page (table)
├── speakers.html             # Speaker profiles page (6 speakers)
├── register.html             # Registration form page
├── contact.html              # Contact page (info, FAQ, form)
├── style.css                 # Single external stylesheet for all pages
├── images/                   # Image assets referenced by the pages
│   └── logo/
│       └── university-logo.png
├── IMPLEMENTATION_PLAN.md    # Detailed design & implementation plan
└── README.md                 # Project documentation (this file)
```

> **Note:** The `images/` folder (logos, event photos, speaker photos, hero banner, gallery, etc.) referenced by the HTML files must be added alongside these files before the site will render correctly — see `IMPLEMENTATION_PLAN.md` for the expected image structure.

## How to View

1. Clone or download this repository.
2. Add an `images/` folder with the required assets (see structure above).
3. Open `index.html` in any modern web browser — no build step or server required.

Or view it live via GitHub Pages once deployed (link above).

## Author

**[Muhammad Musanif]**
Registration No: [22pwbcs0927]
Section: [Summer2026]
