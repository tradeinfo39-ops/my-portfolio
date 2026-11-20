# Muhammad Rohaib — Premium Creative Portfolio

Responsive light-theme multi-page portfolio built with HTML, CSS and vanilla JavaScript. No build step or package install is required. Existing design, typography, logo artwork, colour system and motion are retained.

## Pages
- `index.html` — Home page; the “VIEW ALL SERVICES” link in “Ideas made visible” opens Services on desktop and mobile.
- `about.html` — About
- `services.html` — 12-service catalogue with a dedicated View Work / View Logos button for every service
- `logo-portfolio.html` — Dedicated logo gallery (existing page preserved)
- `photo-editing-portfolio.html`
- `brochures-flyers-posters-portfolio.html`
- `business-cards-stationery-portfolio.html`
- `tshirt-merchandise-portfolio.html`
- `youtube-social-graphics-portfolio.html`
- `product-packaging-labels-portfolio.html`
- `photo-retouching-portfolio.html`
- `photo-enhancement-portfolio.html`
- `document-editing-data-insertion-portfolio.html`
- `animation-video-portfolio.html` — playable MP4 samples with controls
- `web-design-portfolio.html` — interactive website demos embedded in live previews
- `work.html` — filterable selected work gallery
- `contact.html` — Formspree enquiry form
- `project-*.html` — individual project concept pages

## Run locally
Open `index.html` in a browser, or use VS Code Live Server. Keep the folder structure intact. The iframe website demos and video files are stored locally and work when the full folder is uploaded.

## Formspree is connected
The form endpoint supplied by you is now set in `assets/js/config.js`:
`https://formspree.io/f/mljbweav`

This is a public Formspree form endpoint, not a secret API key. Submit a test enquiry from the deployed site to confirm the Formspree account is accepting submissions.

## Replace showcase artwork
Keep the same image filename and replace the current asset with your own JPG, PNG, WebP or SVG, or update the image `src` in the related page. Service sample artwork remains in `assets/images/`. The per-service showcase pages use the same replaceable service image as their first sample; the second tile is an intentional “your next project” placeholder. Duplicate a project card in the page HTML when you want to add more examples.

## Replace video previews
The playable sample videos are in `assets/videos/animation-video-editing/`:
- `motion-study-01.mp4`
- `social-promo-01.mp4`

Replace these with your own H.264 MP4 files and keep the same names to update the players automatically. The poster images are in `assets/images/video/animation-video-editing/`.

## Replace interactive website previews
The web portfolio page embeds three local interactive demo websites in `assets/previews/web/`:
- `cafe-website.html`
- `creative-studio-website.html`
- `product-landing-website.html`

Edit these demo HTML files to show your own website projects, or change the iframe `src` values in `web-design-portfolio.html` to your hosted project URLs. The embedded demos include clickable menu options, project navigation, and product selection / add-to-bag interactions.

## Current services
Photo editing, logo design, brochures/flyers/posters, business cards/stationery, T-shirt/merchandise, YouTube/social graphics, product packaging/labels, photo retouching, photo enhancement, document editing/data insertion, animation/video editing, and web design/digital experiences. Data extraction, AI-assisted visual concepts, photo manipulation, and children’s book illustration remain removed from the Services page as previously requested.

## Notes
The newly added videos and web demos are original sample concepts to demonstrate playback and interaction. They are not client commissions. Replace them with your own work before presenting them as completed client projects.
