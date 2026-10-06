VELOURA — PREMIUM RESTAURANT TEMPLATE
=====================================

QUICK START
1. Extract the ZIP.
2. Double-click index.html OR open the folder in VS Code and use Live Server.
3. No npm / backend installation is required for the demo.

RESERVATION SYSTEM (IMPORTANT)
- This package includes a working STATIC DEMO reservation workflow.
- A guest fills the reservation form on index.html.
- JavaScript saves the booking in browser localStorage.
- Open admin.html IN THE SAME BROWSER to see all demo reservations.
- This makes the customer demo clear and interactive without hosting a backend.
- For a real restaurant, connect the form to your own PHP/Node.js/API/database/email service before production use.

MENU
- The full menu is defined near the top of script.js in the `menu` array.
- Edit category, dish name, description, price, badge and image key there.
- Current categories: Starters, Steaks, From the Sea, Pasta, Desserts.

IMAGES
- Demo photography uses remote Unsplash image URLs so the package stays lightweight.
- The assets folder contains the original placeholder SVG artwork only for reference; it is not used by the rebuilt design.
- For a commercial client deployment, download/replace photos with the restaurant's own licensed images and update the URLs in style.css/script.js.

EDIT RESTAURANT DETAILS
- Name, story, address, hours, phone and email: index.html
- Colors/layout/responsive design: style.css
- Menu, filtering, animations and booking demo: script.js

GITHUB PAGES DEMO
1. Create a repository.
2. Upload index.html, admin.html, style.css, script.js and assets folder.
3. Settings > Pages > Deploy from branch > main / root.
4. Use the generated Pages URL as your Canvasprout demo URL.

NOTE ABOUT ADMIN ON GITHUB PAGES
The localStorage demo works on GitHub Pages. Reservations are stored only in the visitor's browser, not in a shared online database. This is intentional for a safe static product demo. A production backend can be added separately.
