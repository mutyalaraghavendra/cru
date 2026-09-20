# Krousty Korner – SEO checklist

## 1. Before uploading (find & replace)
Replace `https://YOUR-DOMAIN.fr` with the real domain in:
- `index.html` (canonical, hreflang, og:url, og:image, twitter:image, JSON-LD)
- `robots.txt`
- `sitemap.xml`

Add to the JSON-LD in `index.html` once known:
- `"telephone": "+33 ..."` (the business phone)
- `"geo": {"@type":"GeoCoordinates","latitude":..., "longitude":...}`
- `"sameAs": ["Instagram URL", "TikTok URL", "Google Maps URL"]`

## 2. Upload
Upload the whole folder to the hosting root (Hostinger: `public_html/`). Enable HTTPS.

## 3. Google Search Console
1. Add the property (Domain or URL prefix) and verify it.
2. Sitemaps > submit `sitemap.xml`.
3. URL Inspection > paste the homepage > Request indexing.

## 4. Local SEO (biggest impact for a restaurant)
- Claim/create the Google Business Profile: category "Fast-food restaurant" (add "Restaurant halal" as secondary), hours 18:00–02:00 every day, website link, photos, menu.
- Also create Bing Places and Apple Business Connect listings.
- Keep NAP identical everywhere (Name, Address, Phone): "Krousty Korner, 41 boulevard Poniatowski, 75012 Paris".
- Ask happy customers for Google reviews and reply to each one.
- List on TripAdvisor, Yelp, Uber Eats / Deliveroo / Just Eat if applicable, and link back to the site.
- Post photos and offers regularly on Google Business Profile.

## 5. Target searches
burger halal Paris 12, tenders poulet halal Paris 12, fast food halal Paris 12e, poulet croustillant halal Paris, restaurant halal boulevard Poniatowski, Krousty Korner.

## 6. After launch
- Test the page with Google's Rich Results Test (Restaurant + FAQ markup) and PageSpeed Insights.
- Check Search Console > Pages after 1–2 weeks.
- Update prices and hours in both the HTML and the JSON-LD when they change.
- Replace flyer-cropped photos with original high-resolution photos (keep descriptive file names and alt text).
