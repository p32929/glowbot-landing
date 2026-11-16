# GlowBot landing page

The landing page for GlowBot, a WhatsApp booking bot for ladies' salons in Dubai and the UAE. Salon clients message on WhatsApp at all hours, and a salon that replies late loses the booking. GlowBot replies straight away, shows prices and books the appointment in the chat, 24/7, in English and Arabic.

Live page: [p32929.github.io/glowbot-landing](https://p32929.github.io/glowbot-landing/)

## What is on the page

1. **The pitch:** what GlowBot does for a salon and why it helps (no missed messages, booking in the chat, English and Arabic, one-time setup).
2. **A demo chat** ([demo.html](https://p32929.github.io/glowbot-landing/demo.html)): a small chat that acts like a salon assistant. It shows prices and opening hours, gives the location and walks through booking a slot. It switches between English and Arabic, with right-to-left layout for Arabic. It runs entirely in the browser with sample salon data.
3. **A sign-up form** where a salon owner leaves their salon name, WhatsApp number, services, prices, hours and area. It is sent through Formspree.
4. **A WhatsApp button** to message directly.

The page's "Try the Live Demo" button opens a hosted demo on Netlify.

## Run it

It is two static HTML files with no build step.

1. Clone the repo and open `index.html` in a browser, or serve the folder with any static server, for example `npx serve .`.
2. Open `demo.html` to try the chat on its own.

Pushing to `main` deploys the site to GitHub Pages with the workflow in `.github/workflows/deploy.yml`.

## Good to know

1. The page loads Tailwind CSS and Google Fonts from their CDNs.
2. The form posts to a Formspree endpoint, and the WhatsApp and Instagram links are placeholders. Change them to your own before using the page.

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make GlowBot better.

## Share

<a href="https://p32929.github.io/share/?repo=glowbot-landing"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/share-dark.svg"><img src="https://p32929.github.io/readme/share-light.svg" alt="Share this with your friends in just a click" width="420"></picture></a>

## Support

<a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/support-dark.svg"><img src="https://p32929.github.io/readme/support-light.svg" alt="If you like my works and want to support me, feel free to support" width="420"></picture></a>
