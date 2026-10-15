NEXORADEVS — NO-LOGIN WEBSITE PACKAGE
====================================

This is a NEW, self-contained static replacement website, NOT a patch of your old React/Vite source.
It uses plain HTML, CSS and a small JavaScript file; no Firebase, npm, Node/Express server, accounts or database are needed.

PAGES
- index.html            Home
- services.html         Full service list, packages, add-ons, care plans
- contact.html          Founders, phone, WhatsApp and email
- privacy.html          Privacy Policy (review with legal adviser)
- terms.html            Terms & Conditions (review with legal adviser)
- assets/styles.css     Blue/violet theme
- assets/main.js        Responsive mobile menu
- assets/nexoradevs-logo.png    Your supplied original logo
- robots.txt, sitemap.xml       Search engine crawling
- .htaccess             Optional Apache headers; confirm Hostinger compatibility

PREVIEW ON WINDOWS / VS CODE
1. Extract this ZIP to a NEW folder, e.g. C:\Users\Lenovo\Desktop\nexora-public.
2. Open that folder in VS Code.
3. Install the 'Live Server' extension if necessary, then right-click index.html and select Open with Live Server.
   No npm install, Firebase setup or login testing is necessary.
4. Click Services, Contact, Privacy, Terms and check mobile view.

DEPLOY TO HOSTINGER (STATIC HTML HOSTING)
1. Back up anything already in the target website's public_html before making changes.
2. In Hostinger hPanel, open Websites > your domain > Dashboard > Files > File Manager.
3. Open public_html for nexoradevs.digital.
4. Upload the contents of this package (not the outer folder) so index.html is directly in public_html.
5. If using ZIP upload, extract and move files out of any nested folder into public_html.
6. Activate/verify SSL HTTPS and connect domain using hPanel's domain instructions.
7. Visit https://nexoradevs.digital/ and each page; check https://nexoradevs.digital/sitemap.xml.
8. Set up Google Search Console and add the sitemap URL once the site is live.

BEFORE LAUNCH
- Check package prices against current policy, clients, time estimates, and tax treatment.
- Check personal contacts, founder names and all links.
- The Privacy and Terms pages are starter drafts, NOT legal guarantees. Obtain lawyer review.
- They currently say NO analytics or contact database exists. If you add forms, analytics, cookies, payment handling,
  CRM, or server logs beyond normal hosting, you must update disclosures and compliance measures first.
- No Google Analytics or tracking code is included by design. Set it up only after appropriate disclosure/consent.
- No sign-in button appears. Firebase and Express are completely absent.
- Keep backups and do not put .env files, Firebase keys or other secrets in public_html.
- Check your browser devtools console; fix any hosting-specific errors.

NOTE ABOUT EXISTING REACT WEBSITE
If you want to keep the exact old 3D design and remove authentication from THAT codebase instead,
please upload its complete project ZIP (excluding node_modules, .env and secret files).
A README alone does not include the React source needed for safe direct edits.
