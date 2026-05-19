# PromptEdit Landing Page

A static sales page concept for PromptEdit / ContentCreator.com, built from the guidance in `Agents.md`.

## What This Builds

- A premium creator-marketplace landing page
- Clear CTA around joining the marketplace
- Mobile-first responsive sections
- Product/workflow UI mockups for video creation
- Marketplace category cards and a simple conversion path
- Subtle transitions, scroll reveals, and hover states

## Design Direction

The page is aimed at video editors, short-form creators, agencies, YouTubers, and creators selling workflow products. The copy avoids vague technology language and focuses on concrete creator outcomes: faster starts, reusable workflows, production-ready assets, and fewer scattered tools.

The visual system uses high-contrast editorial spacing, warm creator-focused accents, and product UI mockups instead of generic SaaS screenshots.

## Technical Notes

- Plain HTML for a lightweight standalone deliverable
- Tailwind CDN for fast iteration and utility-driven styling
- Minimal custom CSS for texture, hero media, focus states, timeline details, and motion
- Small vanilla JavaScript layer for the intro popup and scroll reveal effects
- Semantic HTML, visible focus states, readable mobile typography, and no horizontal layout dependencies

## Run Locally

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

## Assumptions

- The final public deployment target was not provided, so this repo is prepared as a static site that can be deployed to Netlify, Vercel, GitHub Pages, Cloudflare Pages, or any static host.
- Generation tools are presented as part of a broader creator workflow, not as the entire product.
- The final CTA uses a mail link placeholder because no production signup URL was supplied.

## Next Improvements

- Replace concept UI panels with real product screenshots when available
- Wire the CTA to a real application or creator onboarding flow
- Add a production Tailwind build for deployment instead of the CDN
- Add lightweight analytics for CTA and section engagement
