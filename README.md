# TeddyPups U.A.E. — Website Recreation

A responsive React + Vite recreation for the technical assignment.

## Project links
- **Reference website:** https://puppy.instabizweb.com/
- **Production website:** https://teddypups-website-clone.vercel.app
- **Public source repository:** https://github.com/VeeraShivaKarthik/teddypups-website-clone
- **Hosting:** Vercel

## Run locally
1. Install Node.js 18 or newer.
2. Clone this repository and open the project folder in a terminal.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite.

## Production build
Run `npm run build`. Vite writes the production files to `dist/`.

## Vercel deployment
The project is deployed to Vercel using the Vite framework preset.
- Build command: `npm run build`
- Output directory: `dist`
- Production URL: https://teddypups-website-clone.vercel.app

## Project structure
- `index.html` — document shell and metadata
- `src/main.jsx` — page sections, data and interactive React components
- `src/styles.css` — responsive styling, layout and breakpoints
- `package.json` — dependencies and development/build scripts

## Implemented interactions
- Responsive navigation menu for desktop and mobile
- Puppy breed filters
- Puppy enquiry links and floating WhatsApp contact link
- Expand/collapse FAQ accordion
- In-page section navigation

## Technologies
- React 18
- Vite 5
- JavaScript (ES modules)
- CSS (responsive media queries)
- Lucide React icons
- Google Fonts and Unsplash-hosted imagery

## AI assistance disclosure
AI assistance was used to scaffold and refine the implementation. Example prompts used during development:
1. "Build a responsive React website inspired by the supplied TeddyPups reference. Include hero, puppy catalogue, how-it-works, trust, testimonials, FAQ and contact sections."
2. "Use a warm cream, muted sage and blush palette with editorial serif headings, responsive layouts and accessible interactions."
3. "Add functional navigation, puppy breed filters, accordion FAQ and WhatsApp enquiry links."
4. "Document local setup, production build and Vercel deployment."

The developer should be able to explain, review and maintain all generated code.

## Verification and known limitations
- Vercel production deployment reached the `READY` state and the production build completed successfully.
- Functional controls are implemented in React; perform a final manual desktop/mobile browser pass before submission.
- Puppy cards and imagery are demonstration content and are not a live inventory feed. Availability must be confirmed directly with TeddyPups.
- Photos are loaded from Unsplash rather than copied from the reference site. Replace them with authorized reference assets if exact visual matching is required.
- This is an independent assignment recreation, not the original TeddyPups website or an official business service.
- Confirm contact details, business claims, legal notices and image permissions before using the project beyond the assignment.

## Suggested final manual checks
1. Open the production URL on desktop and mobile widths.
2. Test the mobile navigation open/close behavior.
3. Select each puppy breed filter and confirm the cards update.
4. Expand and collapse FAQ questions.
5. Follow a WhatsApp enquiry link and verify the destination/message without sending an unintended message.
6. Check that all photos load and that there is no horizontal overflow.
