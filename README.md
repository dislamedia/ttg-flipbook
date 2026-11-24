# To The Good flipbook

Page-turning web version of the To The Good prospectus, embedded on tothegood.net.
Built by Disla Media. Page-turn engine: StPageFlip 2.0.7 (MIT license, see THIRD_PARTY_LICENSE_StPageFlip.txt).

To update the book: replace the images in `pages/` (leaf-01.jpg ... one per booklet page) and the PDF, then push.

- `page-flip.browser.js` carries one local patch (11/24/2026): with showCover the cover is no longer forced to a hard page, so every page curls soft.
