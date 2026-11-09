# The Ignite Academy — Website Starter

A responsive Bengali-first coaching academy website with a demo admin portal, designed for GitHub Pages.

## Files
- `index.html` — public academy website
- `admin.html` — admin login and demo dashboard
- `style.css` — responsive styling
- `script.js` — mobile menu and demo admission form
- `admin.js` — demo login and local dashboard

## Run locally
Open `index.html` in a browser. For a local server, use VS Code Live Server.

## Demo admin access
- Email: `admin@igniteacademy.com`
- Password: `Ignite@2027`

## Publish with GitHub Pages
1. Create a new GitHub repository, e.g. `ignite-academy-website`.
2. Upload all files in this folder to the repository root (not the ZIP itself).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, then Save.
6. Wait for deployment. Your website URL will appear in the Pages section.
7. Admin page: append `/admin.html` to the website URL.

## Important security and data notes
This is a **frontend design/demo**, not a production management system.
- The demo credentials are visible in `admin.js`; anyone can inspect the source and bypass this login.
- Admission form entries and dashboard data use browser `localStorage` only. They are not sent to you and are not shared across devices.
- Do not use this demo login for real student or financial data.
- Before public real-world use, connect Firebase Authentication (admin-only access), Firestore/Cloud Functions, server-side security rules, and a real form submission workflow. Never store real admin passwords in frontend JavaScript.

## Customize
- Update academy copy and contact details in `index.html`.
- Update colors in `style.css` (`#101a35` navy, `#f5a623` gold).
- Replace placeholder teacher information and notices with verified academy details.
