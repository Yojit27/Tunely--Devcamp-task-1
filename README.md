# Tunely - Multi-Page Static Website

DevCamp 2.0 - Web Development, Task 1.

A static, multi-page music website built with **HTML5 and CSS3 only** (no JavaScript, no frameworks). It is a practice clone of a music streaming site's layout, using a fictional brand name.

## Live Demo

<!-- Replace with your GitHub Pages link -->
https://your-username.github.io/your-repo-name/

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Navbar, hero section with "Sign up free" button, featured playlist cards, footer |
| Browse | `browse.html` | "Browse all" heading and genre cards (Pop, Hip-Hop, Chill, Workout) |
| Playlist Details | `playlist.html` | Cover image, title, description, Play button and a track table |
| Sign up (optional) | `signup.html` | Sign-up form with required inputs |

## Concepts Used

**HTML**
- Semantic tags: `<header>`, `<nav>`, `<main>`, `<footer>`
- `<form>` with `<input>` fields and the `required` attribute
- `<img>` with descriptive `alt` text
- `<a href="">` links connecting all pages
- `<table>` for the track list

**CSS**
- External stylesheet (`style.css`), with no inline or internal styles
- Class selectors reused across pages (`.navbar`, `.card`, `.btn`)
- ID selector for one unique element (`#hero`)
- Flexbox for the navbar, card rows, playlist header and footer
- Box model: padding, margin and border-radius
- Colour palette: green `#1DB954` and black `#191414`
- Hover effects on buttons, cards and links

## Project Structure

```
├── index.html
├── browse.html
├── playlist.html
├── signup.html
├── style.css
├── README.md
└── images/
    ├── cover1.svg
    ├── cover2.svg
    ├── cover3.svg
    └── cover4.svg
```

## How to Run

No setup needed. Download or clone the repository and open `index.html` in any browser.

## Author

Your Name - DevCamp 2.0
