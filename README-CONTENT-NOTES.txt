Content migration notes — things still marked as placeholders
================================================================

1. CV PDF
   cv.html links/embeds "assets/cv.pdf", which doesn't exist yet.
   Add your real CV as a PDF at: big-picture/assets/cv.pdf
   (both the inline viewer and the "Download CV" buttons will then work automatically)

2. Images (index.html, #work section)
   The "Selected Visuals" gallery currently uses the template's stock
   placeholder photos (images/thumbs/01-03.jpg + images/fulls/01-03.jpg).
   Replace these with your real figures (e.g. Crab Nebula composite,
   X-ray ejecta map, SNR image) — keep the same filenames/paths, or update
   the <a>/<img> src attributes in index.html to match new filenames.

   Your original site also referenced a profile photo
   (images/ElviraCruz-Cruz.JPG) which wasn't included in the upload —
   add it to big-picture/images/ if you'd like a portrait somewhere on
   the new site (there's no dedicated headshot slot in Big Picture's
   layout, so let me know if you want one added).

3. Publications (index.html, #publications section)
   Still has one placeholder entry ("[Add publication title]").
   Swap in your real publications, or duplicate the "box" markup for
   more entries.

4. Social links
   Twitter/GitHub/LinkedIn/Instagram icons in the footer (both pages)
   still point to "#". Update the href attributes with your real profile URLs.

5. Contact form
   The contact form (#contact section) posts to "#" — it needs a real
   backend (e.g. Formspree, like your old contact.html referenced) to
   actually deliver messages.
