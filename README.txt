REFRACTORBOT MOBILE - IPHONE SETUP

This is Option B: eBay saved-search notifications + manual candidate entry + AI review. It does NOT scrape eBay or auto-purchase.

A) FAST TEST ON A COMPUTER
Open index.html in a desktop browser. Searches, scoring, tracking, and export should work. iPhone Files previews may block storage or JavaScript; for iPhone use the hosted route below.

B) HOST AS AN IPHONE HOME SCREEN APP (FREE OPTION)
1. Make a GitHub account if needed.
2. Create a PUBLIC repository named refractorbot-mobile. Note: public hosting means the app source and search URLs are public, but your browser-local candidate records are not uploaded by this code.
3. Upload all five files in this folder to the repository root: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
4. In repository Settings -> Pages, set Deploy from a branch, main and / (root). Save.
5. Open https://YOUR-USERNAME.github.io/refractorbot-mobile/ in iPhone Safari. Publishing may require a moment; use the actual URL shown under GitHub Pages settings.
6. Tap Share -> Add to Home Screen -> Add.
7. Open the new Home Screen icon and set up eBay saved-search notifications.

C) DAILY WORKFLOW
1. Tap Searches and open matching eBay searches. Save those searches in eBay and turn on notifications.
2. Add suspicious listings in Leads and copy the exact eBay URL, title, all-in purchase costs, and photo evidence.
3. Tools -> Copy AI prompt, paste into ChatGPT with seller photos and ask for an evidence-based review.
4. Use eBay Product Research for verified sold comps. Enter base and refractor values when known.
5. Reserve $100 as the total buying limit. It blocks marking a purchase as bought if cumulative committed spending exceeds $100.
6. Export JSON backups regularly from Tools. Data is only stored locally in that browser and does not synchronize across devices. If Safari or iOS deletes site storage, an old backup is the recovery path.

NOTE: Service worker allows the local app shell to open offline after the first hosted visit. eBay and ChatGPT links need connectivity. eBay queries are NOT live-scanned automatically.

Security: No API keys are needed. No photos are uploaded by the app. Do not upload sensitive data into candidate notes. For fully private hosting/source, choose a private hosting provider and verify its access controls.
