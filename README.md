# TechPick — Amazon Affiliate Tech & Gadgets Website

> A clean, fast, and fully responsive Amazon Affiliate website focused on the best Tech & Gadgets deals for Indian shoppers.

---

## Live Website

🌐 **[https://YOUR-USERNAME.github.io/techpick](https://YOUR-USERNAME.github.io/techpick)**

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## What is TechPick?

TechPick is a curated Amazon affiliate deals website for tech enthusiasts in India. It features hand-picked products across categories like Smartphones, Laptops, Air Conditioners, Tablets, Storage, and Home Tech — all linked directly to Amazon India via the Amazon Associates Program.

Every product listed is carefully selected and linked with an affiliate tag. When a visitor clicks a product link and makes a purchase on Amazon, the site owner earns a small commission at no extra cost to the buyer.

---

## Features

- Responsive design — works on mobile, tablet, and desktop
- Filter products by category (Mobiles, Laptops, AC, Tablets, Home, Storage)
- Top 10 Picks section updated monthly
- Newsletter signup section
- Affiliate disclosure (required by Amazon Associates)
- Fast loading — pure HTML/CSS/JS, no frameworks

---

## Products Currently Listed

| # | Product | Category |
|---|---------|----------|
| 1 | OnePlus 15 — 16GB+512GB Sand Storm | Smartphone |
| 2 | OnePlus 13 — 12GB+256GB Midnight Ocean | Smartphone |
| 3 | OnePlus 15R — 12GB+512GB Charcoal Black | Smartphone |
| 4 | HP Victus Gaming Laptop — Ryzen 7 + RTX 3050 | Gaming Laptop |
| 5 | Panasonic 1.5 Ton 5★ WiFi Inverter AC | Air Conditioner |
| 6 | Godrej 1.5 Ton 3★ AI Inverter AC | Air Conditioner |
| 7 | Xiaomi Pad 8 — 12GB+256GB Graphite Grey | Tablet |
| 8 | Seagate One Touch 5TB External HDD | Storage |
| 9 | Cadlec CookEase 2000W Induction Cooktop | Kitchen Tech |
| 10 | ECOVACS DEEBOT N30 Plus Robot Vacuum & Mop | Robot Vacuum |

---

## How to Deploy (GitHub Pages)

### Step 1 — Create a Repository
1. Go to [github.com](https://github.com) and log in
2. Click **"+"** → **"New repository"**
3. Name it `techpick`, set it to **Public**, check **"Add a README file"**
4. Click **"Create repository"**

### Step 2 — Upload the Website File
1. Rename `techdeals-affiliate.html` to **`index.html`**
2. In your repo, click **"Add file"** → **"Upload files"**
3. Drag and drop `index.html`
4. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to **Settings** → **Pages** (left sidebar)
2. Under **Branch**, select `main` → folder `/ (root)`
3. Click **Save**
4. Wait 1–2 minutes — your live URL will appear as:
   `https://YOUR-USERNAME.github.io/techpick`

---

## How to Add Your Affiliate Links

All product links use Amazon short URLs in the format `https://amzn.to/XXXXXXX`.

To update a link:
1. Open `index.html` in any text editor (Notepad, VS Code, etc.)
2. Find the product by its name using **Ctrl+F**
3. Replace the `href="https://amzn.to/..."` value with your new affiliate link
4. Save and re-upload to GitHub

---

## How to Add New Products

To add a new product card, copy this template and paste it inside the `<div class="products-grid">` section in `index.html`:

```html
<div class="product-card" data-cat="CATEGORY">
  <div class="product-img">EMOJI</div>
  <div class="product-badge badge-best">Best Seller</div>
  <div class="product-body">
    <div class="product-category">CATEGORY LABEL</div>
    <div class="product-name">PRODUCT NAME</div>
    <div class="product-desc">Key features here · Short and punchy</div>
    <div class="product-rating">
      <span class="stars">★★★★★</span>
      <span class="rating-num">4.8</span>
    </div>
    <div class="product-footer">
      <div class="price-new">View Price</div>
      <a href="YOUR-AFFILIATE-LINK" target="_blank" rel="noopener" class="buy-btn">Buy on Amazon →</a>
    </div>
  </div>
</div>
```

**Category values for `data-cat`:** `mobile`, `laptop`, `ac`, `tablet`, `home`, `storage`

**Badge classes:** `badge-best` (yellow), `badge-blue` (blue), `badge-purple` (purple), `badge-sky` (sky blue), `badge-amber` (amber)

---

## Registering with Amazon Associates

1. Sign in to your [Amazon Associates account](https://affiliate-program.amazon.in/)
2. Go to **Account Settings** → **Manage Your Websites and Mobile Apps**
3. Click **Add a Website or Mobile App**
4. Enter your GitHub Pages URL: `https://YOUR-USERNAME.github.io/techpick`
5. Describe your site as: *"A curated tech deals and product review website linking to Amazon India products across categories including smartphones, laptops, ACs, tablets, and home appliances."*
6. Click **Save**

---

## Affiliate Disclosure

TechPick is a participant in the **Amazon Associates Program**, an affiliate advertising program designed to provide a means for sites to earn advertising fees by advertising and linking to [amazon.in](https://www.amazon.in).

When visitors click product links on this site and make a purchase on Amazon, TechPick may earn a small commission at **no additional cost** to the buyer.

---

## Tech Stack

- Pure HTML5, CSS3, JavaScript (no frameworks)
- Google Fonts — Syne + DM Sans
- Hosted on GitHub Pages (free)

---

## License

This project is for personal affiliate use. All product names, logos, and trademarks belong to their respective owners. Amazon, Amazon Associates, and the Amazon logo are trademarks of Amazon.com, Inc.

---

*Built with ❤️ for Indian tech shoppers.*
