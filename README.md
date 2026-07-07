# 🍽️ Royal Feast — Online Food Ordering Website

Royal Feast is a multi-page, responsive front-end website for a food delivery/restaurant business. It includes browsing a menu, viewing food details, managing a cart, checking out, and standard informational pages — all built with plain HTML, CSS, and vanilla JavaScript (no frameworks, no build tools required).

## 🔗 Live Pages / Site Map

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `royal-feast-home.html` | Hero banner, food categories, popular dishes, promo banner, testimonials |
| 🍔 Menu | `royal-feast-menu.html` | Full menu with category & price filters, search bar |
| 🍕 Food Detail | `royal-feast-food-detail.html` | Single dish page with toppings, quantity selector, live order summary |
| 🛒 Cart | `royal-feast-cart.html` | Cart items with quantity controls, coupon code, live totals |
| 💳 Checkout | `royal-feast-checkout.html` | Delivery address, payment method, order summary, success notification |
| 🧰 Services | `royal-feast-services.html` | Service highlights (delivery, tracking, payments, etc.) |
| 📖 About Us | `royal-feast-about.html` | Restaurant story, master chefs, mission & vision |
| ✉️ Contact | `royal-feast-contact.html` | Contact form, FAQ accordion, embedded map |
| 🔐 Login / Sign Up | `royal-feast-auth.html` | Combined authentication page (login + sign up toggle) |

All pages share a consistent dark theme with an orange (`#ff6a00`) accent color, and are fully cross-linked through the navigation bar, cart icon, and in-page buttons.

## ✨ Features

- Fully responsive layouts (mobile, tablet, desktop)
- Dynamic cart with quantity +/- controls and live subtotal/tax/delivery/total calculation
- Food detail page with toppings & add-ons that update the order summary in real time
- FAQ accordion on the Contact page
- Embedded Google Map on the Contact page
- Toast-style success notification on order placement
- Simple login/sign-up toggle with redirect to Home on login
- No dependencies — just open the HTML files in a browser

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom, no frameworks)
- Vanilla JavaScript (DOM manipulation, no libraries)

## 📁 Project Structure

```
royal-feast/
├── royal-feast-home.html
├── royal-feast-menu.html
├── royal-feast-food-detail.html
├── royal-feast-cart.html
├── royal-feast-checkout.html
├── royal-feast-services.html
├── royal-feast-about.html
├── royal-feast-contact.html
├── royal-feast-auth.html
└── README.md
```

## 🚀 Getting Started

No build step or dependencies needed.

1. Clone or download this repository
2. Open `royal-feast-home.html` in your browser
3. Navigate the site using the navbar — all pages link to each other automatically

```bash
git clone https://github.com/your-username/royal-feast.git
cd royal-feast
open royal-feast-home.html   # or double-click the file
```

> ⚠️ Keep all HTML files in the same folder — internal links reference each other by filename.

## 📌 Notes

- Images are pulled from Unsplash via direct URLs (requires an internet connection to load).
- Cart, checkout, and login flows are front-end demos only — there is no backend or database connected. Form submissions and cart data are handled entirely in-browser with JavaScript and are not persisted.

## 📄 License

This project is open for personal or educational use. Feel free to fork and customize it for your own restaurant or food delivery concept.
