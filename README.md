# Zeke Pujols Website

A fully responsive, statically generated 8-page editorial web application designed with an early 2000s brutalist hip-hop & R&B magazine aesthetic. 

Built to serve as the official digital home for Zeke Pujols, highlighting his biography, discography, tour dates, and exclusive merch.

## Key Features
- **Brutalist Editorial Design:** Built with pure HTML/CSS leveraging CSS Grid, Flexbox, and fluid typography (`clamp()`) to recreate a tactile print magazine feel.
- **Cinematic Parallax Engine:** A custom, lightweight JS engine smoothly translates oversized background textures (`parallax-1.png` & `parallax-2.png`) opposite to the user's scroll.
- **Native Mobile Responsiveness:** Thoroughly optimized via `@media (max-width: 768px)` breakpoints to seamlessly stack complex multi-column layouts into readable vertical flows.
- **Embedded Media:** Intelligent lazy-loading facade scripts in `main.js` for YouTube and Spotify iframes to ensure blazing-fast initial page loads.
- **Mailing List Integration:** Fully functional, unstyled EmailOctopus form endpoint integrated directly into `contact.html` for list-building.

## File Structure

```text
/
├── index.html       # Cover Layout & Feature Highlights
├── music.html       # Complete Discography List & Visuals
├── videos.html      # Visual Contact Sheet (Music Videos & BTS)
├── tour.html        # Tour Matrix & Live Performance Gallery
├── merch.html       # Summer Collection Catalog Grid
├── about.html       # Biography Spread & Navigation to Featurettes
├── interview.html   # Dedicated Q&A Spread (Featurette)
├── influences.html  # Dedicated Formative Voices Spread (Featurette)
├── community.html   # Fan Club Portal (Discord, Subreddit, Patreon)
├── contact.html     # Mailing List Signup & Booking Information
├── css/
│   ├── styles.css     # Unified Global CSS & Responsiveness
│   ├── interview.css  # Specific overrides for Interview page
│   └── influences.css # Specific overrides for Influences page
├── js/
│   └── main.js      # Global Parallax Engine & Embed Logic
└── assets/
    └── images/      # Highly optimized .jpg & .png editorial assets
```

## Deployment

Since this is a pure static site (HTML/CSS/JS) with no build step, hosting is incredibly fast, simple, and completely free on platforms like Netlify, Vercel, or GitHub Pages.

1. Upload this entire folder to your GitHub repository.
2. Log into your hosting provider of choice (e.g., Netlify) and link the repository.
3. Select the repository. **Leave "Build Command" and "Publish Directory" blank.**
4. Deploy! The edge network will automatically serve and cache your static site globally.
