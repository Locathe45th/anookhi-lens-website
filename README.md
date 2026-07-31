# Anookhi Lens — International Online Photography Contest 2025

A single-page, static site. No build step, no dependencies — plain HTML/CSS/JS.

## Structure
```
index.html
style.css
script.js
assets/
  poster.jpg                 -> hero background (your uploaded poster)
  logo-placeholder.svg        -> temporary logo, swap with the real one
  founder-placeholder.svg     -> back-of-flip-card founder photo placeholder
  rulebook-placeholder.pdf    -> placeholder rulebook, replace with the real PDF
```

## Before you go live — replace these placeholders
1. **Logo** — swap `assets/logo-placeholder.svg` for your real logo (keep the filename, or update the `src` in `index.html`).
2. **Founder photo** — swap `assets/founder-placeholder.svg` (used in the "About Anookhi Lens" flip card).
3. **Rulebook PDF** — replace `assets/rulebook-placeholder.pdf` with the real rulebook.
4. **Registration link** — every `Join Here` / `#register` button currently scrolls to the final CTA section as a placeholder. Search `index.html` for `#register` and point it to your real registration form/link (e.g. Google Form, Typeform).
5. **Winner photos** — the 5 slides in "Meet the Winners" currently use royalty-free Unsplash stand-ins. Swap the `background-image` URLs in the `.slide-image` divs for the real winning photographs, and update the `[Sample description]` text.
6. **About Anookhi Lens copy** — the founder bio text is placeholder copy marked `[Placeholder copy]`. Replace with the real bio.
7. **Competition images** — the "About the Competition" section image is also an Unsplash stand-in.

## Run locally
Just open `index.html` in a browser, or serve it:
```bash
npx serve .
```

## Deploy on Vercel
1. Push this folder to a new GitHub repo.
2. In Vercel: **New Project** → import the repo.
3. Framework preset: **Other** (it's static — no build command, no output directory needed).
4. Deploy.

That's it — no environment variables, no build step.
