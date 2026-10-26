# Manual Testing Checklist

Run the site in a modern browser. These are manual checks; they are not automated browser tests.

## Layout
- [ ] Page opens without missing local CSS/JS files.
- [ ] Header, hero, collection, story, newsletter, and footer appear.
- [ ] Resize to mobile width; content remains readable and does not overflow.
- [ ] Browser reduced-motion setting is respected.

## Products
- [ ] Eight sample products appear initially.
- [ ] Category chips filter the product grid.
- [ ] Search matches product name, category, or description.
- [ ] Sort options order by price or name.
- [ ] Reset filters restores all products and featured order.
- [ ] Add-to-bag increments the header count.

## Shopping bag
- [ ] Bag drawer opens and closes using the close button, overlay, and Escape.
- [ ] Quantity buttons update quantity and subtotal.
- [ ] Remove removes an item.
- [ ] Empty state appears when all items are removed.
- [ ] Refreshing the page preserves the bag in the same browser.
- [ ] Checkout shows a demo notice and does not request payment.

## Forms and browser storage
- [ ] Newsletter form accepts a valid email and shows demo confirmation.
- [ ] Newsletter form does not claim to send an email.
- [ ] If localStorage is unavailable, the page remains usable; persistence may not work.

## Limitations
No real backend, inventory, accounts, payment processing, or automated end-to-end tests are included.
