# Thirdy E-Portfolio — Mikasa animated profile

## Included

- Original HTML pages, layout, navigation, Spotify widget and existing photos are preserved.
- The `home.html` profile uses the existing **450 × 550 oval frame**.
- After a few seconds it smoothly reveals Mikasa with a **circular wipe**, then returns to the original photo.
- Click/tap the oval (or focus it and press Enter/Space) to toggle at any time. Manual interaction turns off automatic switching on that page visit.
- The anime eyes make small independent gaze adjustments using specially prepared frame images; the rest of the portrait remains stationary.
- Gentle moving red particles, lighting and optional pointer parallax are contained within the oval.
- `prefers-reduced-motion` is honored by disabling automatic movement.

## Assets

- `images/image1.jpg` — your original profile photo, preserved.
- `images/mikasa-gaze-center.webp`, `...-left.webp`, `...-right.webp`, `...-down.webp` — matching HD art for the moving eyes.
- The other existing images remain untouched.

## Preview and GitHub

1. Open the folder in VS Code and launch `index.html` using Live Server.
2. Allow the profile to switch automatically, then click the oval to try manual switching.
3. In the terminal, run `git add .`, `git commit -m "Add animated Mikasa portrait"`, `git push origin main`.

The animation is purely HTML/CSS/JavaScript plus local `.webp` images. It does not require a JavaScript library, account, external animation service or paid plugin.
