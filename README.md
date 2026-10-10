# Chinanda Timbers

Complete static website with 13 routes, supplied material photography, product filtering, galleries, a roofing reveal, responsive navigation and WhatsApp enquiry preparation.

## Local preview
Run `npm run dev` in this directory, then open http://127.0.0.1:4173.

## Production build
Run `npm run build`. Upload the contents of `dist` to a static host with directory index support. No dependencies or build installation are required. This project has not been publicly deployed.

## Enquiries
Forms validate and prepare a message. Visitors explicitly select Continue to WhatsApp to send it. There is no server submission, email service or stored enquiry database. Connect a backend in the form submission handler in `public/app.js` if required later.

## Assets and facts
All material images are cropped from supplied client images. The original logo is retained with a circular transparent mask. The white-named logo file preserves the original brand badge, rather than inventing a monochrome mark. Specifications, dimensions, prices, delivery fees and times require confirmation with Chinanda Timbers.

The roofing comparison depicts two separate supplied material/application examples; it does not claim a documented before-and-after project.

Fonts load from Google Fonts with local sans-serif fallbacks. The embedded Google map requires internet access. Map directions use the provided address and do not assert an independently verified exact pin.
