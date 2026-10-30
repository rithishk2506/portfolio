# Rithish K — Personal Portfolio (Enhanced)

## Run locally
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Run `index.html` with Live Server, or open it directly in a browser.

## Portrait
The hero uses `assets/rithish-profile.jpg` as the atom nucleus, surrounded by three animated electron orbits. Replace this file to update the photo.

## Certificates
All certificate cards show JPEG/PNG previews. Click a card (or focus it and press Enter/Space) to open a large full-size image preview. PDF originals are retained in `assets/` for reference.

## Reviewed project reports included
- `assets/reports/smart-hostel-complaint-system.pdf`
- `assets/reports/wildlife-monitoring-hwc-system.pdf`
- `assets/reports/vaultx-secure-password-manager.pdf`

Project details in the website are grounded in the submitted report abstracts and implementation descriptions. Wildlife monitoring is described as a controlled-replay/simulation prototype, not field-validated detection. VaultX is an academic prototype and its report identifies production hardening still required.

## Live project
CourseIQ — Learning Insights by Mining Minds:
https://courseiq-learning-insights-by-mining-minds.streamlit.app/

## Profiles
- GitHub: https://github.com/rithishk2506
- LinkedIn: https://www.linkedin.com/in/rithish-k-551248319

## Contact links
- GitHub: https://github.com/rithishk2506
- Instagram: https://www.instagram.com/soulhacker.rithu?cplk=MXBiMGg5bmNxcjBmdw==
- LinkedIn: https://www.linkedin.com/in/rithish-k-551248319
- WhatsApp: https://wa.me/919940581851

## Latest portfolio update
- Replaced the SIPD appreciation, SIPD completion and RINEX Campus Ambassador certificate previews with JPEG versions of the supplied certificates.
- Added a mailto-based contact form and displayed Rithish K's email and phone details.
- Updated the top-left wordmark, STARS description, footer and neon hover states.
- Added Devicon-based technology logos where available, with compact monogram fallbacks.
- The profile portrait uses a transparent foreground cutout over a blurred original-photo backdrop.

## Latest update — profile photo and Thirukkural
- Replaced the profile image with the latest user-supplied portrait, retaining its softly blurred background.
- Added Thirukkural 619 as the final content section, with Tamil typography and a restrained red/blue accent treatment.


## Version 13 — Project WEB and image reliability
- Added a full-screen pull-to-enter opening experience. Drag the spider handle downward to reveal the portfolio; Skip intro and keyboard activation are also available.
- Embedded the profile photograph and all certificate preview images directly into `index.html` to prevent broken previews when the separate assets folder is not deployed.
- Kept the `assets/` directory in this package for reports, PDFs and other supporting files.
- For deployment, extract the ZIP and publish the contents of this folder so `index.html` is at the site root and `assets/` remains alongside it.

## v17 — Cinematic spider pull-down intro
Only the opening intro was redesigned; all portfolio content, projects, certificates, links and reports are unchanged.
- `assets/spider-transparent.png` — your supplied spider, background removed (true transparent PNG, no square/border/glow box), with a thin neon rim so the black artwork reads on the dark intro. Loaded via a relative path.
- Drag the spider (mouse, touch or pen — Pointer Events). A verlet-rope thread bends and stretches, side web strands tighten, and the spider swings along the thread. Releasing early springs it back.
- Reaching the pull threshold drops the spider, draws red/blue web strands across the screen and opens a radial mask reveal of the portfolio, followed by staggered entrance animations.
- Fallbacks: `TAP TO ENTER` button (touch-friendly), `Skip intro`, Enter/Space/↓ on the focused spider, and `prefers-reduced-motion` (no particles/blink/web; quick crossfade).
- Tuning: pull distance `T`, thread length `L0` and spider size are set in `layout()` inside the intro script in `index.html`.

### Thread realism update (still V17)
The hanging thread is now a hair-thin silk strand (pale blue-white core, a faint twisting micro-filament, slow glints and an occasional light running down it) instead of a thick glowing line. The spider swings gently like a pendulum, the thread has air-drag lag, slight elasticity and recoil when dragged or released, and stays anchored above the top edge. Pull threshold, reveal sequence, tap-to-enter, skip and reduced-motion behaviour are unchanged.
