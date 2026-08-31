# The Tech Agency — Website (Phase 1)

5 pages: Home, Services, Portfolio, Contact, Thumbnail Review Tool. No backend code — everything runs on free/no-code services.

## To go live (no coding needed)

1. **Hosting:** Create a free account at [Netlify](https://netlify.com) or [Vercel](https://vercel.com), drag this whole folder into their upload area. You'll get a live URL in under a minute. (Both have a free tier that's enough for this.)
2. **Forms (Contact page + Thumbnail Review page):** Create a free account at [Formspree](https://formspree.io), create a form, and copy the form ID it gives you. In `contact.html` and `thumbnail-review.html`, find `YOUR_FORM_ID` and replace it with your real one.
3. **Payments (Priority Review, $5):** In your Razorpay dashboard, create a Payment Link for $5. Add it as a button on `thumbnail-review.html` near the "Chose Priority?" line — I've left a comment there marking where.
4. **Custom domain (optional):** Once live on Netlify/Vercel, you can point a custom domain (like thetechagency.com) to it from their dashboard if you buy one later.

## To edit content later

Every page is plain HTML — open any `.html` file, find the text you want to change between tags, edit it, save. `style.css` controls colours/fonts/spacing for all pages at once — change a colour there and it updates everywhere.

## What's still placeholder

- Portfolio page shows 12 "coming soon" cards (one per category) — swap these for real images as they're finished in the Notion Portfolio Tracker.
- Once there's a first real client, add their result to the "First client testimonial" slot planned in the Content Calendar, and consider adding a testimonials section here too.
