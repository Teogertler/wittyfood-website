# WittyFood Landing Page

Official landing page for [wittyfood.com](https://www.wittyfood.com)

## 🚀 Quick Start

This site is hosted on **Netlify** and auto-deploys when you push changes to GitHub.

### To make changes:
1. Edit `index.html`
2. Commit and push to GitHub
3. Netlify automatically deploys (usually within 1 minute)

## 📁 Project Structure

```
wittyfood-site/
├── index.html          # Main landing page
├── README.md           # This file
└── assets/             # Images and other assets (future)
```

## ✏️ Common Edits

### Update Statistics (Progress Bar)
Find this section in `index.html` around line 850:

```javascript
// Calculate progress: 5 restaurants out of goal of 100 for Phase 1
const currentRestaurants = 5;
const goalRestaurants = 100;
```

Change `currentRestaurants` to your current count.

### Update Stat Cards
Search for these IDs in the HTML:
- `id="restaurantCount"` — Number of restaurants
- `id="dishCount"` — Number of dishes  
- `id="cityCount"` — Number of cities

### Update Founder Information
Search for `founder-card` class to find the founder sections. Update:
- Names
- Roles
- Bios
- Social links

### Update Contact Information
Search for `contact-method` to find:
- Email address
- Social media links
- Location

## 🎨 Styling

All styles are in `<style>` tags within `index.html`. Key CSS variables at the top:

```css
:root {
    --color-cream: #FDF6E9;
    --color-butter: #F5E6C8;
    --color-tangerine: #FF6B35;
    --color-tomato: #E63946;
    --color-espresso: #2D1810;
    --color-sage: #606C38;
}
```

## 🔗 Useful Links

- **Netlify Dashboard**: [app.netlify.com](https://app.netlify.com)
- **Squarespace Domains**: [account.squarespace.com/domains](https://account.squarespace.com/domains)
- **Google Workspace Admin**: [admin.google.com](https://admin.google.com)

## 📧 Forms

Currently, forms show JavaScript alerts. To make them functional:
1. Use Netlify Forms (add `netlify` attribute to form)
2. Or connect to your backend API

---

*Last updated: January 2026*
