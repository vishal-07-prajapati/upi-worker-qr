# Worker UPI QR

A small web app that makes one UPI QR code for each worker in a shop.
Every QR pays the shop's UPI ID, and the worker's name goes in the payment note,
so the owner can see who took each payment.

## Features
- Enter any UPI ID and shop name
- Add, rename and remove workers
- Optional separate UPI ID per worker
- Download or share each QR as a PNG (with shop name, worker name and UPI ID)
- Print all QRs for chair standees
- Works on phone, tablet and desktop, and can be added to the home screen
- Everything is saved in the browser only. No server, no tracking.

## Host on GitHub Pages
1. Create a new public repository on GitHub, e.g. `upi-worker-qr`.
2. Upload `index.html`, `icon.svg`, `manifest.webmanifest` and this README.
3. In the repository go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
5. After a minute the site is live at `https://<your-username>.github.io/upi-worker-qr/`.

## Note
The worker name is sent as the UPI payment note (`tn`). Some UPI apps let the customer
edit the note or don't show it in history, so test with a ₹1 payment first.
