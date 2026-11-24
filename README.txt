# BAKE N FRY PWA

Files: index.html, manifest.json, service-worker.js, icons/.

## Publish on GitHub Pages
1. Upload all files and the icons folder to the root of your repository.
2. In GitHub: Settings → Pages → deploy from your main branch and /(root).
3. Open the HTTPS Pages URL on your phone.
4. iPhone: Safari → Share → Add to Home Screen. Android: Chrome → menu → Install app / Add to Home screen.

## Important limitation
This first version is a local-device PWA prototype. Orders are saved in the browser's localStorage on the device where they are placed. GitHub Pages is static hosting and these three technologies alone do not provide a shared order database or remote push delivery to the owner's phone. The notification code demonstrates a local notification on the same device after an order is placed; it does not notify a separate admin device about a customer's order. Do not use this version as a live multi-customer ordering service until a shared backend/push sender is added.

Edit product names and prices in the `products` array near the top of the script in index.html.
