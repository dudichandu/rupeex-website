# RupeeX (RPX) — Official Website

India's Hybrid Crypto Payment Token — Static website built from Adobe XD design.

## 🚀 Live on GitHub Pages

Deploy this site to GitHub Pages in 3 steps:

1. **Create a new GitHub repository** (e.g. `rupeex-website`)
2. **Upload all files** keeping the folder structure:
   ```
   index.html
   images/
     logo.png
     team-photo.jpg
     chart.jpg
     market1.jpg
     market2.jpg
   README.md
   ```
3. **Enable GitHub Pages**: Go to repository Settings → Pages → Source → `main` branch → Save

Your site will be live at `https://yourusername.github.io/rupeex-website`

## 📁 Structure

```
rupeex-website/
├── index.html        ← Main website (single-page)
├── images/
│   ├── logo.png      ← RupeeX logo
│   ├── team-photo.jpg
│   ├── chart.jpg     ← Market chart
│   ├── market1.jpg
│   └── market2.jpg
└── README.md
```

## ✨ Features

- Responsive design (mobile + desktop)
- Sticky navigation
- Live price ticker
- UPI payment form with copy-to-clipboard
- Scroll animations
- Dark theme with green accent (#22C55E)

## 🎨 Design

Faithfully converted from Adobe XD (rupeex_upi_.xd):
- Background: `#0F172A`
- Accent: `#22C55E` (Green)
- Typography: Syne (headings) + Space Grotesk (body)

## 📝 Customisation

Update UPI ID in `index.html`:
```html
<span class="upi-id" id="upiId">rupeex06@ybl</span>
```

Update RPX price in the JavaScript section:
```js
const rpx = (amt / 0.042).toFixed(2); // change 0.042 to current price
```

---
© 2026 RupeeX | Hybrid Crypto + UPI Payment System
