# Anookhi Lens — International Online Photography Contest 2026

A single-page, static site. No build step, no dependencies — plain HTML/CSS/JS.

## Structure
```
index.html
style.css
script.js
assets/
  logo.png                        -> real Anookhi Lens logo (transparent PNG)
  hero-bg.jpg                     -> real hero background
  founder.jpg                     -> real founder photo
  winner-aryaman-dhiman.jpg       -> Nature & Wildlife winner
  winner-saumavo-kumar.jpg        -> Travel & Street winner
  winner-ramesh-prajapati.jpg     -> Open Monochrome winner
  runner-farbod-nature.jpg        -> Nature & Wildlife runner-up
  runner-karunakaran-ramlingam.jpg-> Travel & Street runner-up
  runner-farbod-monochrome.jpg    -> Open Monochrome runner-up
```

## Still placeholder — replace before going live
1. **About Anookhi Lens copy** — the founder bio text is placeholder copy marked `[Placeholder copy]`. Replace with the real bio.
2. **Competition section image** (the person photographing, 30% column) is still an Unsplash stand-in — swap if you have a real photo.

## Already wired up
- All 4 "Join Here" / "Join the Contest" buttons (header, mobile menu, hero, final CTA) link directly to the real registration form, opening in a new tab:
  `https://docs.google.com/forms/d/1n3nDMpVZnA553HiDknX1SRq-rnI-pyHDiIajD54v4po/viewform`
- Rulebook button has been removed from the "About the Competition" section.
- Winner slides no longer show description text — just image, name, place, and category tag.
- All "2025" references updated to "2026" (title, meta description, edition labels, footer copyright).

## Already real (from your uploads)
- Logo (header, hero, footer) — transparent PNG so it drops cleanly onto any background
- Hero background
- Founder photo (About Anookhi Lens, entrance-animated)
- All 6 winner/runner-up photos, correctly matched to name + category:
  - Nature & Wildlife: Aryaman Dhiman (Winner), Farbod Bahevie (Runner-up)
  - Travel & Street: Saumavo Kumar (Winner), Karunakaram Ramlingam (Runner-up)
  - Open Monochrome: Ramesh Kumar Prajapati (Winner), Farbod Bahevie (Runner-up)

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
