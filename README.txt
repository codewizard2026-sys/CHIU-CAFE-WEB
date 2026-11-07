CHIU CAFE WEBSITE
=================

Files:
- index.html: complete responsive cafe website
- assets/chiu-cafe-hero.png: generated hero visual used in the homepage

Preview:
Open index.html in a modern browser. Keep the assets folder beside index.html.

Before publishing:
1. Confirm the exact spelling of the address, especially "Daag".
2. Replace the sample gallery photos with real Chiu Cafe food/interior photos when available.
3. Add the cafe's actual Google Maps pin/review link if one exists.
4. Add verified customer reviews only after receiving permission.
5. Upload the folder to a web host (for example, GitHub Pages, Netlify, or your hosting provider).

Note: This is a website package, not a live published website.


CUSTOMER REVIEWS DATABASE SETUP (REQUIRED BEFORE REVIEWS WORK)
1. Create a free project at https://supabase.com/ and open its SQL Editor.
2. Open supabase_reviews_setup.sql from this website folder, copy all SQL, paste it into SQL Editor and click Run.
3. In Supabase Project Settings → API (or Data API), copy the Project URL and the publishable key (or legacy anon public key).
4. Open index.html in a text editor. Find YOUR_SUPABASE_PROJECT_URL and YOUR_SUPABASE_PUBLISHABLE_OR_ANON_KEY and replace those two placeholder values.
5. Save index.html and upload the whole chiu_cafe_website folder to your website host again.
IMPORTANT: Use only the publishable/anon public key in the website. NEVER put a service_role key or secret key in index.html.
Reviews are immediately public after submission, as requested. Because public anonymous submissions can attract spam, add CAPTCHA/rate limiting before promoting the site widely.
