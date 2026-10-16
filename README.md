# Luna Petal Shop

A mobile-friendly, static storefront for Luna Petal (@lunapetal_ng). Built with plain HTML, CSS and JavaScript so it can be tested on GitHub Pages without Lovable credits or a backend.

## Current features
- Responsive storefront and product category filters
- Product search
- Shopping bag with quantity controls and removal
- WhatsApp-order message draft with customer/delivery details
- Instagram link
- Prices intentionally marked as “Price on request” until the shop owner confirms them

## Before launch
1. Add the actual product photos to `assets/` using the filenames referenced in `index.html`.
2. Set the correct WhatsApp business number in the checkout script. Use country code digits only, without `+`, spaces or punctuation. The checkout currently stays disabled until this is configured.
3. Confirm product names, sizes, prices, stock and delivery terms.
4. Test on desktop and mobile before enabling GitHub Pages.

## Product photo filenames
- `assets/vivon-body-care.jpg`
- `assets/body-care-mix.jpg`
- `assets/medix-vitamin-c.jpg`
- `assets/eos-body-lotion.jpg`
- `assets/dove-body-care.jpg`
- `assets/skin-by-zaron.jpg`

## Test locally
Open `index.html` in a browser. No build step or package installation is required.

## Publish after approval
In GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. Do this only after product images, WhatsApp number, prices and checkout have been verified.
