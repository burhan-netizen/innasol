INNASOL WEBSITE - SETUP NOTES

Upload everything to the root of your hosting / GitHub repo (index.html at the top level).

BEFORE GOING LIVE, open index.html and change:
1. PHONE and EMAIL  (search: EDIT YOUR CONTACT DETAILS HERE)
2. WA = WhatsApp number, country code first, no + or spaces, e.g. 447123456789
3. YOURDOMAIN.co.uk (two og:image / twitter:image tags near the top) -> real domain
4. Gallery: replace each <div class="ph"> block (search: Replace each .ph block)
5. Irina's portrait: search 'Replace the contents of .pr-frame' and put <img src="irina.jpg" alt="Irina, owner of Innasol"> inside .pr-frame; upload irina.jpg next to index.html

NEW: REVIEWS + QUOTE BUILDER
6. Reviews: the 6 reviews are EXAMPLES. Replace each <article class="rc"> with a real review (search: REVIEWS), update the 5.0 rating, then DELETE the data-demo attribute on <section id="reviews"> - that removes the EXAMPLE tags and the yellow note.
7. Google reviews button: set GOOGLE_REVIEWS_URL in the script (leave "" to hide the button).
8. Quote builder (#estimate): shows no prices. It sends the customer's choices to WhatsApp (and email) using the WA, EMAIL values above. Edit services/sizes in the script (search: Quote builder).
