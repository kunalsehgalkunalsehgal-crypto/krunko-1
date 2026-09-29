KRUNKO HOMEPAGE

Open index.html directly in a modern browser. No build, framework, server or installation is required.

FILES
index.html: editable sections and product cards
style.css: section-by-section styles and responsive rules
script.js: cart, product search, packet flip, mobile menu and newsletter demo
assets/: supplied branding, mascot and product imagery

EDITING
Change product names, price text, weights and image paths directly in index.html.
When changing a price, update the matching Add to Cart data-price attribute too.
Duplicate a product-card article to add a product.
For packet cards, replace both front and back image paths.

IMPORTANT CONTENT NOTES
Jar prices and weights, and pack prices, are explicitly marked as samples.
The pink packet artwork shows 250 GM. Packet weight text uses 250 g.
Only green and pink have complete supplied front/back pairs. The red pack appears in campaign imagery; no red back image has been invented.
Supplied packet and mascot artwork retains its original The Farm Project branding.
The four featured jars are Cheese, Himalayan Salt, Peri Peri and Tangy Tomato, matching supplied images.
Contact email and address were transcribed from supplied packaging. A telephone number was not included because it was not legible enough to verify.
The newsletter displays a success state but does not save or send an email.
The cart runs in memory and resets on refresh. No checkout, account authentication, payment processing or backend is included.
Social, legal and account controls open clear informational dialogs because live links, approved policies and account infrastructure were not provided.

VALIDATION
JavaScript syntax passed node --check.
All 22 image references exist and their image files decode correctly.
Four jar cards and two complete front/back packet cards confirmed.
Anchor targets and unique element IDs verified.
Responsive breakpoints cover desktop, tablet and small mobile layouts.
Browser-based visual and interaction testing could not run in this environment: Chromium was absent and both full-browser and headless-browser downloads returned invalid archives. Layouts at the requested widths and live interactions therefore still need a browser review before production launch.
