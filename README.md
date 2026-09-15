# MMEink Corporate & Seasonal Event Agency Website

Multi-page web application featuring full-service event planning, marketing, production, hospitality, and exclusive venue properties. Built with semantic HTML5 and CSS3

## Deployment
* **Vercel**: https://mmeink-website.vercel.app/

##  Key Features
* **Alternating Zigzag Layout**: Uses `.row-container` with flexbox directional swapping (`flex-direction: row-reverse`) for high-impact visual storytelling between text and media columns.
* **Responsive Breakpoint Behavior**: Gracefully collapses multi-column media/text rows into a single vertical stack on mobile viewports (`max-width: 768px`).
* **Multi-Column Corporate Footer**: CSS Grid layout (`repeat(auto-fit, minmax(180px, 1fr))`) structuring navigation directories, service offerings, and headquarters contact credentials.
* **Modern CTA Architecture**: Full-width high-contrast feature banners and responsive action buttons.

## Tech Stack
* **Markup**: HTML5 (Semantic elements: `<main>`, `<section>`, `<footer class="footer-container">`)
* **Styling**: CSS3 (Flexbox, CSS Grid, custom relative spacing)
* **Version Control**: Git / GitHub
* **Deployment**: Vercel

## Project Structure
```text
├── index.html        # Main landing and service showcase page
├── style.css         # Global stylesheet, layout grid, and responsive rule


