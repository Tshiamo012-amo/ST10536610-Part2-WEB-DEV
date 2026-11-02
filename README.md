# Golden Crust Bakery - WEDE5020 Part 3 Finale
**Student:** ST10536610 | **Location:** Bloemfontein, Free State (051) | **Theme:** Luxury Burgundy & Gold

## Project Overview
Golden Crust Bakery is a luxury bakery website based in Bloemfontein. All images are 100% real work from own kitchen (cake_1_CLEAN.jpg to cake_9_CLEAN.jpg). Built with HTML, CSS, and JavaScript for Part 3. Deployed on Netlify.

Live Link: https://enchanting-pika-9d31e5.netlify.app
Repository: https://github.com/Tshiamo012-amo/ST10536610-Part2-WEB-DEV

## Part 3 Updates (New in Part 3 - Finale)
### 2.1 Interactive Elements & Visual Effects
- Added Lightbox Gallery on services.html - click any of 9 cakes to enlarge (custom JS lightbox)
- Added Modal Popup on index.html - Today's Special offer
- Added Accordion FAQ on about.html - Our Story, Ingredients, Delivery
- Added Interactive Map using Leaflet.js + OpenStreetMap on contact.html - Pin at Bloemfontein [-29.0852, 26.1596]
- Added CSS Animations & Transitions: hover scale, fade-in on scroll using Intersection Observer, smooth scroll
- Added Advanced DOM Manipulation: dynamic rendering, event delegation

### 2.2 Dynamic Content & Search
- Converted services.html 9 cakes from static HTML to dynamic JS array loading (products array in JS)
- Implemented Live Search: search by name/flavor (Chocolate, Vanilla etc.)
- Implemented Filter: filter by flavor type (All, Chocolate, Vanilla, Red Velvet, Caramel, Lemon)
- Implemented Sort: sort by price Low to High / High to Low
- Implemented Dynamic Testimonials on index.html - loaded from JS array
- Implemented Price Estimator on enquiry.html - calculates R x quantity live

### 3.1 & 3.2 SEO Optimization
- On-Page: Added title tags, meta descriptions, keywords, canonical, viewport, alt text on all 9 images with keywords
- On-Page: Proper H1, H2, H3 hierarchy, image lazy loading, internal linking
- On-Page: Created robots.txt and sitemap.xml in root
- Off-Page: Added Open Graph tags for Facebook/Instagram, footer social links
- Local SEO: Added JSON-LD structured data for Bakery in Bloemfontein, keywords "Bakery Bloemfontein 051"
- Performance: Preconnect Google Fonts, optimized images, blurred background with overlay for readability

### 4. Form Functionality & Validation
- **contact.html purpose:** General enquiries, feedback, complaints - Fields: Name, Email, Message Type select, Message
- **enquiry.html purpose:** Specific cake quotes/bookings - Fields: Name, Email, Phone, Cake Type select, Event Date, Quantity, Details + live price estimate
- Client-Side JS Validation: Name min 2 chars, email must contain @ and ., phone 10 digits, date must be future, message 10+ chars, error messages shown inline
- Error Handling: Shows red error text, prevents submit if invalid
- AJAX Submission: Uses fetch() to https://httpbin.org/post to simulate email sending, shows success message, resets form
- Security: novalidate + custom JS validation, no inline passwords, form reset after submit

## Changelog
- **Part 3:** Added JS enhancements - lightbox, modal, accordion, Leaflet map, animations
- **Part 3:** Added dynamic product loading + search/filter/sort functionality
- **Part 3:** Added SEO files - robots.txt, sitemap.xml, meta tags, JSON-LD
- **Part 3:** Created enquiry.html separate from contact.html with different purpose + validation + AJAX
- **Part 3:** Updated contact.html with Leaflet map and full validation + AJAX
- **Part 2:** Added background image blur effect (1px) with white overlay 0.85 for readability
- **Part 2:** Split Flavors and Fillings into two columns (flex display)
- **Part 2:** Added luxury burgundy (#800020, #4a0a0a) and gold (#D4AF37, #ffd700) theme
- **Feedback from Part 1 Fixed:** Removed stock photos, replaced with own cake images (cake_1 to cake_9)
- **Feedback from Part 1 Fixed:** Fixed layout alignment on About page, centered content
- **Feedback from Part 1 Fixed:** Added alt text and proper headings

## Part 2 Updates (Kept)
- Luxury burgundy and gold theme across all pages
- Blurred background image using own cake photo on all pages
- Real cake gallery from own images
- Improved responsiveness and sticky navigation

## References
- Google Fonts - Playfair Display and Poppins - https://fonts.google.com/
- W3Schools - CSS flexbox, blur filter, form validation - https://www.w3schools.com/
- MDN Web Docs - Intersection Observer, Fetch API, form validation - https://developer.mozilla.org/
- Leaflet.js - Interactive Maps - https://leafletjs.com/ + OpenStreetMap tiles
- httpbin.org - For testing AJAX form submission
- Own cake photography - Golden Crust Bakery Bloemfontein - 9 images

## How to Run
1. Clone repo
2. Open index.html in browser
3. All pages linked via nav: index, services, about, enquiry, contact

## Repository & Deployment
- GitHub: https://github.com/Tshiamo012-amo/ST10536610-Part2-WEB-DEV
- Netlify Deploy: Import from GitHub, publish directory is root
- Files included: index.html, services.html, about.html, enquiry.html, contact.html, robots.txt, sitemap.xml, README.md, cake_1_CLEAN.jpg to cake_9_CLEAN.jpg

## Screenshots (Add for submission)
- Home page with modal
- Services with lightbox open + search filter
- Contact with Leaflet map
- Forms with validation errors