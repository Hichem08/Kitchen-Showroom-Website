# Hichem Cuisine — React website

A responsive English-language kitchen showroom and custom-order website for Hichem Cuisine in Blida, Algeria.

## View it immediately (no installation)
Open `preview/index.html` in Chrome, Safari, Edge or Firefox. Keep the `preview/images` folder beside it. This is a local preview and does not need a server. Internet is only used for optional Google Fonts; the site works without them too.

## Run the React app
Requires Node.js 20+.

```bash
npm install
npm run dev
```
Open the local address printed by Vite. To create a production build, run `npm run build`; the output will be in `dist/`.

## Features
- Responsive layouts for phones, tablets and desktop
- Hero section using the supplied horizontal cappuccino kitchen image
- Six kitchen designs with starting prices, indicative dimensions, materials and three finish options each
- Custom kitchen form with layout, dimensions, style, color and budget fields
- Product enquiries and custom-order requests composed for WhatsApp
- Home / Services / Location / Contact navigation with smooth scrolling
- Email, WhatsApp, Instagram and Blida map links

## Important notes
- Prices and dimensions are sample starting estimates for presentation and should be confirmed/updated by Hichem Cuisine before publishing.
- The shop location is shown as Blida, Algeria; a street address was not supplied, so the map link opens a search rather than a pinned storefront.
- The WhatsApp order flow opens a pre-filled message. The customer reviews and sends it from WhatsApp; the website does not automatically send messages or collect payments.
