NIyantri — Simple Coffee Website

Files included:
- index.html — Home page with hero, featured menu preview, and brief story.
- menu.html — Full menu listing with Add to Cart buttons.
- cart.html — Client-side cart using localStorage (mock checkout).
- contact.html — Contact form (mock send).
- about.html — About page.

Notes & defaults:
- Theme: modern coffee tones using Tailwind utility classes (amber/stony palette).
- Font: Inter (commented at top of each HTML file). Add a Google Fonts import if desired in production.
- Images: placeholders use the format src="https://images.unsplash.com/photo-1588192524634-1c3f8490f68b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw1fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU2NTM4MDk0fDA&ixlib=rb-4.1.0&q=80&w=1080". Replace with real image URLs.
- Cart: Stored locally in browser under the key "ny_cart" as JSON. No backend is included.
- Animations: subtle entrance animations and hover transforms are implemented with Tailwind utility classes and small inline scripts.

How to run:
1. Open any of the .html files in a browser (index.html is the entry).
2. The site uses the Tailwind CDN for convenience. For production, compile your own Tailwind build and include fonts correctly.

Customization tips:
- Replace placeholder image src values with real images.
- Hook up contact form and checkout to your backend or third-party services.
- Adjust Tailwind configuration to add brand colors or custom fonts.

If you want additional features (login, payments, or a backend for orders), tell me which pieces to add and I can extend the project.