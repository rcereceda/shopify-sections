# Shopify Sections

A collection of free, high-quality, and reusable Shopify sections designed to boost conversions and enhance your store's design.

## 🚀 Features

- **100% Free & Open Source** - No hidden costs, no subscriptions
- **Copy & Paste Ready** - Just copy the code and paste it into your theme editor
- **No Dependencies** - Pure Liquid and CSS, no external libraries required
- **Fully Customizable** - All settings editable through the Shopify theme editor
- **Responsive Design** - Works perfectly on all devices
- **Performance Optimized** - Lightweight and fast-loading

## 📚 Sections vs Blocks

### 📦 Sections (Full-Width Components)

Sections are standalone, full-width components that you add to complete pages.

**Examples**: Hero banners, trust badges grid, testimonials, FAQ
**Where**: Homepage, collection pages, landing pages
**How to add**: Customize theme → Add section

### 🧩 Blocks (Small Components)

Blocks are smaller components that you add INSIDE existing sections.

**Examples**: Product trust badges, countdown timers, size guides
**Where**: Product pages (inside Product Details), cart drawer
**How to add**: Customize theme → Open a section → Add block

**Think of it this way**:

- **Sections** = Full pages or major page areas
- **Blocks** = Small pieces within those areas

## 📦 Available Sections

### 1. Trust Badges ✅

Display trust indicators to build customer confidence and increase conversions.

**Features:**

- Multiple badge support via blocks
- 8 built-in SVG icons (shipping, secure payment, guarantee, support, quality, returns, payment, eco-friendly)
- Responsive grid layout (1-4 columns)
- Customizable colors, spacing, and border radius
- Hover effects

**Use Cases:**

- Homepage
- Product pages
- Checkout pages
- Landing pages

**Links:**

- [📄 View Code](./sections/trust-badges.liquid)
- [📖 Full Documentation](./docs/trust-badges.md)

---

---

## 🧩 Available Blocks

### 1. Product Trust Badges ✅

Compact trust indicators for product pages, designed to reduce purchase friction.

**Features:**

- Vertical layout (stacked badges)
- 4 configurable badges with enable/disable
- 6 built-in icons (shipping, secure, guarantee, returns, quality, support)
- Optimized for placement below "Add to Cart" button
- Customizable colors and spacing

**Use Cases:**

- Product pages (below buy buttons)
- Quick view modals
- Cart drawer

**Links:**

- [📄 View Code](./blocks/product-trust-badges.liquid)
- [📖 Full Documentation](./docs/product-trust-badges.md)

---

## 🎯 Coming Soon

**Sections:**

- **Hero Banner** - Full-width hero section with image/video background
- **Testimonials** - Customer reviews and social proof
- **FAQ Accordion** - Collapsible frequently asked questions
- **Feature Grid** - Showcase product features and benefits

**Blocks:**

- **Countdown Timer** - Create urgency with time-limited offers
- **Size Guide** - Help customers choose the right size
- **Stock Indicator** - Show remaining inventory
- **Shipping Calculator** - Estimate delivery costs

---

## 📖 Installation

### Step 1: Copy the Section Code

1. Navigate to the section you want to use (e.g., `sections/trust-badges.liquid`)
2. Copy the entire file content

### Step 2: Create the Section File

1. Go to your Shopify Admin
2. Navigate to **Online Store** → **Themes**
3. Click **Actions** → **Edit code** on your active theme
4. In the left sidebar, find the **Sections** folder
5. Click the **"+"** icon (or right-click → **New file**)
6. Name it `trust-badges.liquid`
7. Paste the copied code
8. Click **Save**

> **Note**: If you see an error, make sure you copied the complete file including the `{% schema %}` section.

### Step 3: Add Section to Your Pages

1. Go back to **Online Store** → **Themes**
2. Click **Customize** (not "Edit code")
3. Navigate to the page where you want the section (e.g., Home page)
4. Click **Add section** (you'll see this button under Header, Template sections, or Footer)
5. Search for **"Trust Badges"** in the section list
6. Click to add it
7. Customize the settings in the right sidebar
8. Click **Save**

---

## 🎨 Customization

All sections are fully customizable through the Shopify theme editor. No coding required!

Each section includes settings for:

- Layout options (columns, spacing, alignment)
- Colors (background, text, icons)
- Typography (sizes, weights)
- Spacing (padding, margins, gaps)

---

## 🌐 Demo

See these sections in action: [sections-lab-2.myshopify.com](https://sections-lab-2.myshopify.com)

_(Demo store uses the Horizon theme)_

---

## 💡 Tips for Best Results

1. **Trust Badges**: Place them on your homepage, product pages, and near checkout buttons
2. **Keep it Simple**: Don't overload pages with too many sections
3. **Test on Mobile**: Always preview on mobile devices
4. **Match Your Brand**: Customize colors to match your store's design
5. **Use High-Quality Content**: Good copy and images make a huge difference

---

## 🤝 Contributing

Found a bug? Have a suggestion? Want to contribute a new section?

Feel free to open an issue or submit a pull request!

---

## 📄 License

MIT License - Free to use for personal and commercial projects.

---

## 🙋 Support

Need help? Have questions?

- Check the [installation guide](#-installation) above
- Review the code comments in each section
- Open an issue on GitHub

---

## 🎯 Roadmap

- [ ] Hero Banner section
- [ ] Testimonials section
- [ ] FAQ Accordion section
- [ ] Feature Grid section
- [ ] Announcement Bar section
- [ ] Newsletter Signup section
- [ ] Image Gallery section
- [ ] Product Showcase section

---

**Made with ❤️ for the Shopify community**
