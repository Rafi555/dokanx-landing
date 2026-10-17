DokanX Static HTML Landing Page
===============================

1. Upload the entire folder to cPanel public_html or drag the folder/ZIP to any static host.
2. No npm, Node.js, database or build command is required.
3. Open index.html.

Image replacement
-----------------
Replace files in /assets while keeping the same filenames.
Recommended ratios:
- Hero/product visual: 16:9
- Large bento module images: 16:9
- Medium/smaller module images: 4:3
- Social platform logo strip: wide transparent PNG/SVG, roughly 4:1 to 6:1
- DokanX logo: transparent horizontal wordmark

Pricing
-------
Open index.html and find:
  const MODULES = [
Change any monthly BDT price there. The calculator updates automatically.
Annual billing automatically applies 10% discount.

Business type
-------------
Searchable English + Bangla SME list is included in plain JavaScript.
Find BUSINESS_TYPES in index.html to add or remove categories.

Contact form
------------
The form currently demonstrates the UI only. Connect the submit handler at the bottom of index.html to WhatsApp, Formspree, email, Google Apps Script, PHP or your backend when ready.
