GLAM SET STUDIO — V2 PROTOTYPE

Included:
- index.html: polished client sizing portal
- admin.html: studio dashboard with status changes, search/filter, and CSV export
- kit-generator.html: workflow for creating kit codes/QR destinations
- demo_qr_GSS-DEMO-4821.png: sample QR image
- styles.css: responsive brand styling

IMPORTANT:
This is still a front-end prototype. Browser localStorage is NOT a secure database and should not be used for real client records.

For the production version:
1. Host the client portal on a real domain with HTTPS.
2. Connect forms to a secure database.
3. Add authenticated admin access.
4. Generate a unique QR code for every kit that points to /portal?kit=UNIQUE-CODE.
5. Add order statuses and email/text notifications.
6. Keep payment-card data out of your database; use a PCI-compliant payment provider.
7. Add privacy policy/terms and appropriate data retention/security controls.

Recommended real workflow:
Kit created → QR printed → client scans → kit code prefilled → client enters 10 sizes + contact + billing/shipping → submission appears in dashboard → you change status → client receives confirmation/tracking.
