# 23D Studio — Landing page (Next.js)

## Run it
1. Install Node.js 20 or newer from https://nodejs.org (LTS version).
2. Open this folder in a terminal (or VS Code → Terminal → New Terminal).
3. Run:
   npm install
   npm run dev
4. Open http://localhost:3000

## Production
   npm run build
   npm start
Or push the folder to GitHub and import it on https://vercel.com (zero config).

## Where things are
- app/page.js              → page made of the sections below
- components/Hero.js       → nav, hero, mobile menu, back-to-top button
- components/Stats.js      → 2022 / 30+ / 6+
- components/Services.js   → the three services (text + images in one list at the top)
- components/Process.js    → 5-step timeline
- components/Footer.js     → footer links, CTA
- components/ChatButton.js → floating chat bubble
- app/globals.css          → all styling
- public/images, public/fonts → assets from the design PDF

## Before going live (search for "TODO")
- Social links in Footer.js
- Email in Footer.js ("Start the Project")
- WhatsApp link in ChatButton.js
