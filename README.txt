SANJAY SPEED PACKERS AND MOVERS WEBSITE

PROJECT STRUCTURE
- public/index.html             Main website
- public/assets/business-poster.jpg  Original poster extracted from your uploaded HTML
- public/robots.txt             Basic crawler instructions
- firebase.json                 Firebase Hosting configuration

RUN LOCALLY
1. Install Node.js (LTS) if it is not already installed.
2. Open PowerShell in this folder.
3. Run: npm install -g firebase-tools
4. Run: firebase emulators:start --only hosting
   If prompted to initialize Hosting first, run: firebase init hosting
5. Open the local URL printed in the terminal.

PUBLISH
1. Run: firebase login
2. Run: firebase init hosting
3. Select your Firebase project.
4. Public directory: public
5. Configure as a single-page app: No
6. If asked to overwrite public/index.html, choose No.
7. Run: firebase deploy --only hosting
8. Open the URL printed by Firebase (usually https://PROJECT_ID.web.app).

IMPORTANT
- The enquiry form does not save data to a database or send email. It opens WhatsApp with the enquiry text so the visitor can review and send it.
- Verify all phone numbers, email, address, business name and poster before publishing.
- The original poster was retained as an image asset. Replace it with a clean high-resolution logo/brand photo if you have one.
- Add your final Firebase URL to the JSON-LD url field and create a sitemap.xml using that exact domain after deployment.
- Do not add customer reviews, registrations, insurance claims, prices or service promises unless the business can substantiate them.
