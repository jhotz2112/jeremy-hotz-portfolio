# Jeremy Hotz: Portfolio

Personal portfolio and interactive resume, built as a single self-contained HTML file (no build step, no dependencies).

**Live site:** https://jhotz2112.github.io/jeremy-hotz-portfolio/

## What's on it

- Product/experience overview framed around Digital Product Management, with a supporting background in web development
- Animated stat counters, an interactive experience accordion, and a "Selected Work" section with case-study modals
- A draggable impact-vs-effort prioritization matrix (keyboard-operable)
- A command palette (`⌘K` or the search button) for jumping to any section
- Dark/light mode toggle (persisted, defaults to light)
- Testimonials
- A downloadable PDF version of the resume that mirrors the page content
- Open Graph/Twitter card metadata and a custom favicon for link previews

## Stack

Plain HTML, CSS, and vanilla JavaScript in [index.html](index.html). No frameworks, no bundler. The PDF (`resume.pdf`) and social preview image (`og-image.png`) are generated assets checked into the repo rather than built at request time.

## Updating

1. Edit `index.html` directly.
2. Commit and push to `main`.
3. GitHub Pages rebuilds automatically within a minute or two.

If resume content changes, regenerate `resume.pdf` so it stays in sync with the page (the generation script is not part of this repo; ask for it to be rebuilt if needed).
