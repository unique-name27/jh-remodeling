JH REMODELING — WEBSITE FILES
=============================

What's here
-----------
index.html   The whole site (one page). All styling and scripts are inside it.
img/         The project photos the page uses (all real JH Remodeling jobs from Yelp).

How to put it online (no coding needed)
---------------------------------------
Option A — Netlify Drop (free, ~2 minutes):
  1. Go to https://app.netlify.com/drop
  2. Drag the whole "jh-remodeling-site" folder onto the page.
  3. It gives you a live link immediately. In Netlify's site settings you can
     attach the jhremodel.com domain so the new site replaces the old one.

Option B — Any web host (GoDaddy, Hostinger, Bluehost, etc.):
  Upload index.html and the img/ folder to the root (public_html) folder.

Things to know
--------------
* The "Request a free estimate" form opens a pre-filled email in the visitor's
  mail app (no server needed). If you'd rather have submissions land in an inbox
  automatically, a free form service like Formspree or Netlify Forms takes about
  five minutes to wire up — ask and it can be added.
* Phone, email, hours and the license number are typed in plain text in
  index.html — search for "609-1313", "jh13remodeling", "8 AM", or "1132818"
  to change them.
* To swap a photo, replace the file in img/ with a new one of the same name
  (JPEG, roughly 1000 px wide is plenty).
