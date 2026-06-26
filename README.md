# Next Cut Barbershop — Website

Premium single-page site for Next Cut Barbershop (Waterloo, ON). Self-contained HTML — no build step.

## Deploy (GitHub Pages)
1. Create a public repo named `nextcut`
2. Upload `index.html`, `README.md`, `.nojekyll`
3. Settings → Pages → Branch: `main` / root → Save
4. Live at `https://<username>.github.io/nextcut/`

## Replace placeholders with real content
- **Photos:** every `<div class="ph">…</div>` is an image slot — swap for `<img src="your-photo.jpg" alt="">` (hero collage, team, gallery, before/after).
- **Phone / WhatsApp:** search the file for `5190000000` and `(519) 000-0000` and replace with the real number.
- **Booking link:** already wired to the Fresha page via the `BOOKING` constant in the script.

Crafted by Vector Studio.
