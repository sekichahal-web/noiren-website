NOIREN ADMIN PANEL

This version includes Decap CMS at /admin/.
To make the Admin Panel actually save changes, the site must be deployed from a GitHub repository connected to Netlify.

ONE-TIME NETLIFY SETUP:
1. Put this website into a GitHub repository (main branch).
2. In Netlify, connect the site to that repository and set production branch to main.
3. In Netlify Site Configuration -> Identity, enable Identity.
4. Enable Git Gateway under Identity/Services (wording can vary in the current Netlify UI).
5. Invite/allow your own admin user.
6. Open https://YOUR-SITE.netlify.app/admin/

PRODUCT EDITING:
Products -> choose a product -> upload photo / edit name / type / price / rating -> Save/Publish.
The public site reads data/products.json.

IMPORTANT:
- Do not put secret API keys in this website.
- Online payments still need a payment gateway such as Razorpay configured separately.
