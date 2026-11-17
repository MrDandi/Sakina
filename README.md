# Sakina

SAKINA PERFUMES - Starter website

HOW TO PREVIEW
1. Open index.html in a modern browser.
2. The store starts in Arabic (RTL). Click EN to switch to English (LTR).
3. Add products to the cart, enter customer details and submit to prepare a WhatsApp order.

IMPORTANT SETUP BEFORE USING
1. Open index.html in a text editor.
2. Find: const WHATSAPP_NUMBER = '2189XXXXXXXX';
3. Replace it with your WhatsApp number in international format, digits only. For Libya, start with 218 (do not include +).
4. Find: const ADMIN_PASSWORD = '1234'; and change the demo password.
5. Replace sample product data and image URLs with your real products and prices.

ADMIN PANEL
At the bottom of the page click "إدارة المتجر". Demo password: 1234.
You can add, edit and delete products, set prices and sale prices, choose a category and set an image URL.

LIMITATIONS OF THIS STARTER
- Product and cart data are stored in localStorage in the browser that is being used. They are not shared between devices or customers.
- Admin password is a front-end demo gate, NOT secure production authentication.
- No server-side order database, inventory synchronization, image upload service, hosting, domain, or delivery integration is configured.
- WhatsApp opens a pre-filled message; the customer must press Send.
- Use HTTPS hosting before public launch. For a real multi-user store, connect a backend/database (e.g. Supabase) and secure admin authentication.

This is a starter prototype, not a production-ready deployed store.