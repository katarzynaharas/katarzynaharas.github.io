# Katarzyna Haras — Portfolio

Personal portfolio website for Katarzyna Haras, Civil Engineer & Business Transformation Specialist.

**Live at:** *(your GitHub Pages URL here)*

## Stack

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no build steps, no dependencies. Just one file.

## Features

- Responsive single-page layout (mobile + desktop)
- Smooth scroll navigation with fixed nav bar
- Animated section fade-ins on scroll
- Contact modal
- Sections: Hero · About · Education · Experience · Projects · Skills

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `katarzynaharas.github.io` or `portfolio`)
2. Upload `index.html` (and your `photo.jpg` if you add one) to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your site will be live at `https://<yourusername>.github.io/<reponame>`

## To add your photo

1. Add your photo file (e.g. `photo.jpg`) to the repo root
2. In `index.html`, find the hero section and add an `<img>` tag, or replace the stats panel with a photo+stats layout

## Customisation

All colours are CSS variables at the top of the `<style>` block:

```css
:root {
  --bg: #F7F5F0;
  --accent: #2D5A3D;       /* green — change to your preferred accent */
  --accent-warm: #C4622D;  /* warm orange for dots */
  ...
}
```

## License

Personal use only.
