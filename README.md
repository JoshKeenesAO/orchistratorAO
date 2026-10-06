# AO Trust Bridge Prototypes

Two clickable HTML prototypes exploring a persistent "trust bridge" that carries a
customer from a completed phone purchase through the data plan and insurance checkout
journeys. Both are faithful to the AO design language.

## Prototypes

- **Prototype A — Progress & Completion** (`prototype-a/index.html`)
  Trust bridge leads with reassurance, a visible progress bar and a step tracker.
- **Prototype B — Benefits & Value** (`prototype-b/index.html`)
  Trust bridge leads with value/savings copy; progress tracking is secondary.

Open `index.html` (the landing page) to launch either prototype.

## Journey

Phone Payment → Handset Confirmation → Data Plan Details → Data Plan Checkout →
Data Plan Confirmation → Insurance Setup → Final Combined Confirmation.

The trust bridge appears after phone payment and persists across every subsequent
screen, updating progress as the customer advances.

## Running locally

It's a static site (HTML/CSS/JS, no backend). Serve it from the project root, e.g.:

```bash
python3 -m http.server
```

then visit http://localhost:8000

## Hosting

Any static host works (Netlify, GitHub Pages, Vercel). Keep the folder structure
intact so the relative links between the landing page and the two prototype folders
resolve correctly.
