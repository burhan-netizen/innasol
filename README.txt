INNASOL WEBSITE - SETUP NOTES

This is a CONCEPT version prepared by Mago Labs. Before going live:

1. Contact details: open index.html, search "EDIT YOUR CONTACT DETAILS HERE"
   - PHONE, EMAIL, WA (WhatsApp: country code + number, no + or spaces, e.g. 447123456789)
   - GOOGLE_REVIEWS_URL (leave "" to hide the link)
2. Remove the concept banner: delete the <div class="demo" ...> line near the top of <body>.
3. Remove all EXAMPLE tags and yellow placeholder notes: delete data-demo from <body data-demo>.
4. Remove <meta name="robots" content="noindex"> so Google can index the live site.
5. Replace YOURDOMAIN.co.uk in the og:image and twitter:image tags with the real domain.
6. Photos in /img are Unsplash stock placeholders. Replace with Irina's real photos (same file names, WebP):
   - hero.webp (hero), irina.webp (portrait in About)
   - home / office / deep / tenancy / builders .webp (service cards)
   - kitchen-before.webp + kitchen-after.webp (before/after slider, same room, same angle)
   - kitchen2 / bathroom / wipe / office2 .webp (Recent work gallery)
7. Reviews: replace each <article class="rc"> with a real review and update the 5.0 rating (search: REVIEWS).
8. Quote builder (#estimate) shows no prices. It sends the customer's choices to WhatsApp or email.
