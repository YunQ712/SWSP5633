# Trauma-Informed Social Work Practice Learning Tool

A beginner-friendly, static learning website for social work students and early-career social workers. It introduces trauma-informed practice (TIP) and provides interactive scenarios for applying TIP in social work settings.

## Website modules

- **Module 01 · Understanding Trauma** — introductory learning materials about trauma, its sources, impacts, loss and grief, and individual differences, culture and resilience.
- **Module 02 · Understanding Trauma-Informed Practice** — key TIP concepts, principles and frameworks.
- **Module 03 · Applying TIP in Social Work** — practical topics for communication, safety, trust, assessment, responding to disclosure, professional power and reflection.
- **Module 04 · Interactive Simulations** — three branching practice scenarios:
  - **Jack** — school setting and rapport building.
  - **Alex** — NDIS assessment.
  - **Marko** — youth work and care planning.

## Files

- `index.html` — the homepage and learning modules. The simulation card illustrations are embedded in this file.
- `jack.html` — Jack's interactive school scenario.
- `alex.html` — Alex's interactive NDIS assessment scenario.
- `marko.html` — Marko's interactive youth care-planning scenario.

Keep all four HTML files in the same directory. The homepage links to each simulation using relative file paths.

## Deployment

This is a static website. It does not require a backend, database, API key, package installation or build step.

To deploy with Vercel:

1. Upload all website files to the root of a GitHub repository.
2. Import that repository into Vercel.
3. Deploy it as a static site without a build command.

The root `index.html` file serves as the homepage. Keep the three simulation files alongside it so the links continue to work.
