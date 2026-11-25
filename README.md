# Rebel Acres Farm LLC: sample website

A one-page sample site for **Rebel Acres Farm LLC**, a family livestock farm in Sumerco, Lincoln County, West Virginia. The farm sells its own WV-raised beef, pork and lamb from an on-farm shop and a refrigerated meat truck. Built by AiroxLab.

The lead said Ohio, but every source puts the business in **Sumerco, WV**. The Google listing and the Facebook page both show the lead's phone number.

## Contacts

- Phone (mobile, call or text): **(304) 962-5896**
- Email (public on Facebook): rebelacres15@gmail.com
- Address: 485 Laurel Fork Road, Sumerco, WV 25567 (plus code 63CV+3F)
- Farm shop: Mon–Thu 11 AM–7 PM. Closed the week of 23 Nov 2026 except by appointment.
- Meat truck pop-ups: Hamlin (by the "Welcome to Hamlin" sign) on Fridays and Julian (by the train tracks) on Sundays, noon till dark. Not every week.
- Payment: cash, credit/debit, EBT
- Facebook: https://www.facebook.com/p/Rebel-Acres-Farm-LLC-61575542373080/

## Sections

1. Sticky header: anchor nav, a **Text** button (sms:) and a **Call** button (tel:)
2. Hero: truck photo, what the farm sells, a verbatim "no growth hormones nor additives" quote, call CTA
3. Info strip: shop hours, truck days, payment, address (Maps link)
4. Thanksgiving-week notice (from the 19 Nov 2026 post; remove after the holiday)
5. The farm: cattle and horse photos, claims taken from the farm's own posts
6. Price list: beef, lamb and pork per-lb prices from the 16 Nov 2026 price sheets
7. Package deals and beef shares ($100–$1,000), and half/whole hanging-weight rates (15 Nov 2026)
8. Farm shop and meat truck: where to buy
9. From the farm kitchen: lard-and-beeswax candles $8, smoked salt $4, cobblers $15
10. Quarterly freezer giveaway (13 Nov 2026 post)
11. Reviews: "100% recommend (37 reviews)" and 9 verbatim Facebook recommendations
12. Call/text band and footer with data sources

## Data sources

- Facebook page, posts, About and reviews: https://www.facebook.com/p/Rebel-Acres-Farm-LLC-61575542373080/ and https://www.facebook.com/profile.php?id=61575542373080&sk=reviews
- Price, pork and package sheets posted 16 Nov 2026. Package graphics posted 15 and 20 Nov 2026. Half/whole graphic posted 15 Nov 2026.
- Google Maps listing (category "Butcher shop", hours, no reviews): https://www.google.com/maps/place/Rebel+Acres+Farm+LLC/@38.2201675,-81.906297,17z
- WV Dept of Agriculture vendor list: agriculture.wv.gov/farmers-market/farmers_market_results.php

All prices date from November 2026 and are labeled with their posted dates on the page.

## Excluded

- Instagram @rebel.acres.farm ("Kelley"): nothing links it to this farm.
- Midnight Farms (Sumerco sheep farm), Rebel's Ridgeview Acres, Rebel Hollow Farm (TN) and other Ohio "Acres" farms: different phones or businesses.
- An old, unavailable FB page "Rebel Acres Farm, 466 Laurel Fork" (goats, rabbits, chickens, labs): unverified, so those animals are not listed.
- "Mobile Auto Llc | Madison WV" FB page: unverified.
- The owner's surname (possibly Matt Smith) and any "fair cattle" or award claims are not used. "Matt" appears only inside one verbatim review.

## Photos (`img/`)

All photos belong to the business. No stock images are used.

| File | Source |
|---|---|
| meat-truck-roadside-setup.jpg | Facebook post, 20 Nov 2026 (Hamlin setup). License plate blurred, resized. |
| farm-shop-sign.jpg | Facebook post, 16 Nov 2026 |
| rebel-acres-logo-sign.jpg | Facebook post, 16 Nov 2026 (logo/truck graphic) |
| cattle-in-barn.jpg, cattle-at-feed-trough.jpg | Facebook posts, 15 Nov 2026 |
| horses-in-pasture.jpg | Facebook album, 23 Apr 2025 |
| ground-beef-and-steaks.jpg | Facebook post, 22 Nov 2026 |
| smoked-salt.jpg, lard-beeswax-candle.jpg | Facebook posts, 16 Nov 2026 |
| blueberry-cobbler.jpg | Facebook post, 10 Nov 2026 |
| beef-cooler-stocked.jpg, pork-cooler-stocked.jpg | Google Maps listing photos |

## Tracking and deploy

Sendra tracker before `</body>`. The page carries `data-section` and `data-track` labels (added by `sendra-track.py`). It is a static single file: deploy it to GitHub Pages (main / root) and send prospects the airoxlab subdomain.
