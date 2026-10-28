# Paw & Care — Veterinary Clinic (business card website)

Responsive one-page website for a veterinary clinic. It introduces the services,
the doctors and lets visitors send an online appointment request.

Live version: GitHub Pages (Settings -> Pages -> branch `main`, folder `/ (root)`).

## Components

1. **Header / Nav** — flex bar on desktop, burger menu on phones (checkbox + CSS, no JavaScript), button "Call Doctor 24/7".
2. **Hero** — media background, heading "Professional Care for Your Pets", call to action "Make an Appointment".
3. **Grid** — Therapy, Surgery, Vaccination cards (3 columns on desktop, 1 column on phones).
4. **Feedback form** — Pet's Name, Pet Species, Owner's Phone, Owner's Email, date, validation with HTML attributes and CSS (`:user-valid` / `:user-invalid`).
5. **Footer** — emergency phone, address, messengers, legal block, Night mode switch (pure CSS).

## Technologies

- HTML5 semantic tags: `header`, `nav`, `main`, `section`, `article`, `footer`
- CSS3: Grid, Flexbox, custom properties, `light-dark()`, relative units only (`rem`, `%`, `vh`)
- Mobile-first: one `@media (min-width: 1024px)` query for the desktop layout
- Light / Dark themes, contrast according to WCAG AA
- Images: SVG (logo, icons, illustration) and WebP (hero picture)

## Project structure

```
index.html
style.css
images/
```

Open `index.html` in a browser to see the site; no build step is needed.
