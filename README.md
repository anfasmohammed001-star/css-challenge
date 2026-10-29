# CSS Lab — Week 1, Task 3

A small, standalone practice project for the Week 1 CSS challenge at WeIntern Pvt Ltd. It demonstrates three layout and interaction exercises without a framework or JavaScript.

## Exercises

### 1. Flexbox layout

The testimonial section uses a flexible three-card row on larger screens. At the mobile breakpoint, the cards stack vertically. It demonstrates `display: flex`, `flex`, `gap`, alignment, and a hover lift effect.

### 2. CSS Grid layout

The “A week in little moments” section uses six cards in a responsive grid. The Monday card spans two columns and two rows on desktop, then the layout simplifies to two columns on smaller screens.

### 3. Animation

The final call-to-action includes a subtle orbit animation using `@keyframes`. The button uses a transition to move its arrow on hover. A reduced-motion media query is included for accessibility.

## Tech used

- Semantic HTML5
- CSS3
- Flexbox
- CSS Grid
- CSS transitions and keyframes
- Responsive media queries
- Google Fonts (DM Sans and Space Grotesk)

## Run locally

Open `index.html` in a browser. For the most reliable local preview, use VS Code Live Server or any simple static file server.

## Folder structure

```text
css-challenge/
├── index.html
├── css/
│   └── style.css
├── screenshots/
└── README.md
```

## Screenshot checklist

Capture and save these files in `screenshots/` before submission:

- `flex-desktop.png` — the testimonial cards at desktop width
- `flex-mobile.png` — the stacked testimonial cards at mobile width
- `grid-layout.png` — the complete grid section
- `animation-demo.png` — the motion section with the button visible

## Author

WeIntern Week 1 submission
