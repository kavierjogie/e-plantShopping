# Paradise Nursery – e-plantShopping

**Paradise Nursery** is an online plant shop built with React, Vite and Redux Toolkit. Users can browse house plants, add them to a shopping cart, and manage quantities with live totals.

## Features

- **Landing page** with a background image, the company name, an About Us section and a **Get Started** button.
- **Product listing page** with 18 house plants grouped into three categories (Air Purifying, Aromatic Fragrant, Insect Repellent) — six per category, each with a thumbnail, name, description and price.
- **Add to Cart** buttons that add the plant to the cart, disable once added, and update the cart icon count.
- **Navbar** on the product and cart pages with links to Home, Plants and Cart, plus a cart icon showing the total number of items.
- **Shopping cart page** showing each plant's thumbnail, name, unit price, subtotal, increase/decrease buttons and a Delete button, the total cart amount, a **Continue Shopping** button and a **Checkout** button ("Coming Soon").

## Tech stack

- React 18 + Vite
- Redux Toolkit / React Redux (`CartSlice.jsx`)

## Project structure

```
src/
  App.jsx          Landing page + page switching
  App.css          Landing page styles (background image)
  AboutUs.jsx      Company details
  ProductList.jsx  Navbar, plant categories and Add to Cart
  CartItem.jsx     Shopping cart page
  CartSlice.jsx    Redux slice: addItem, removeItem, updateQuantity
  store.js         Redux store
```

## Getting started

```bash
npm install
npm run dev
```

## Deploying to GitHub Pages

1. Replace `<your-github-username>` in `package.json` → `homepage`.
2. Run `npm run deploy`.
3. In the repo's **Settings → Pages**, set the source to the `gh-pages` branch.
