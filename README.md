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

## You might also like

<p><a href="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/0"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/0-dark.svg"><img src="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/0-light.svg" width="50%" align="top" alt="More apps by p32929 on OpenStore (1)"></picture></a><a href="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/1"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/1-dark.svg"><img src="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/1-light.svg" width="50%" align="top" alt="More apps by p32929 on OpenStore (2)"></picture></a><br><a href="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/2"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/2-dark.svg"><img src="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/2-light.svg" width="50%" align="top" alt="More apps by p32929 on OpenStore (3)"></picture></a><a href="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/3"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/3-dark.svg"><img src="https://openstore.pfay.workers.dev/more/p32929/glowbot-landing/personal/3-light.svg" width="50%" align="top" alt="More apps by p32929 on OpenStore (4)"></picture></a></p>

<p><a href="https://p32929.github.io/share/?repo=glowbot-landing"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
