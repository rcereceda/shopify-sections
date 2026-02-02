# Trust Badges Section - Usage Guide

🇺🇸 English | [🇪🇸 Leer en español](../es/trust-badges.md)

## 📋 Overview

The Trust Badges section displays multiple trust indicators in a responsive grid to build customer confidence and increase conversions.

## ✨ Features

- **Multiple Badges**: Add unlimited trust badges using blocks
- **6 Built-in Icons** (Heroicons):
  - 🚚 Free Shipping (truck icon)
  - ✅ Money-Back Guarantee (shield-check icon)
  - 💬 24/7 Support (chat bubbles icon)
  - ⭐ Premium Quality (star icon)
  - 🔄 Easy Returns (arrow-path icon)
  - 🌱 Eco-Friendly (leaf icon)
- **Professional Design**: Modern Heroicons for a clean, consistent look
- **Responsive Grid**: 1-4 columns on desktop, 1-2 on mobile
- **Fully Customizable**: Colors, spacing, border radius
- **Hover Effects**: Smooth animations on hover
- **No Dependencies**: Pure Liquid and CSS

## 🎨 Customization Options

### Section Settings

| Setting               | Type    | Default            | Description                          |
| --------------------- | ------- | ------------------ | ------------------------------------ |
| **Heading**           | Text    | "Why Shop With Us" | Optional section heading             |
| **Columns (Mobile)**  | Select  | 1                  | Number of columns on mobile (1 or 2) |
| **Columns (Desktop)** | Range   | 4                  | Number of columns on desktop (1-4)   |
| **Gap**               | 8-48px  | 24px               | Space between badges                 |
| **Background Color**  | Color   | #f9f9f9            | Badge background color               |
| **Text Color**        | Color   | #000000            | Badge text color                     |
| **Icon Color**        | Color   | #000000            | Badge icon color                     |
| **Border Radius**     | 0-24px  | 8px                | Badge corner roundness               |
| **Padding Top**       | 0-100px | 40px               | Section top spacing                  |
| **Padding Bottom**    | 0-100px | 40px               | Section bottom spacing               |

### Block Settings (Per Badge)

| Setting         | Type   | Default              | Description                 |
| --------------- | ------ | -------------------- | --------------------------- |
| **Icon**        | Select | Shipping             | Choose from 6 icons or none |
| **Title**       | Text   | "Free Shipping"      | Badge title                 |
| **Description** | Text   | "On orders over $50" | Badge description           |

## 📖 Installation

### Create the Section File

1. Copy the code from `trust-badges.liquid`
2. Go to **Shopify Admin** → **Online Store** → **Themes**
3. Click **Actions** → **Edit code**
4. In the **Sections** folder, click the **"+"** icon (or right-click → **New file**)
5. Name it `trust-badges.liquid`
6. Paste the code and click **Save**

### Add to Your Page

1. Go back to **Online Store** → **Themes**
2. Click **Customize** (not "Edit code")
3. Navigate to your desired page
4. Click **Add section** (under Header, Template, or Footer)
5. Search for **"Trust Badges"**
6. Click to add it and customize settings
7. Click **Save**

## 💡 Usage Examples

### Example 1: E-commerce Homepage

```
Heading: "Why Shop With Us"
Columns (Desktop): 4
Columns (Mobile): 2

Badges:
1. Free Shipping | On orders over $50
2. Easy Returns | 30-day return policy
3. 24/7 Support | Dedicated customer service
4. Premium Quality | Top-rated products
```

### Example 2: Product Page

```
Heading: "" (no heading)
Columns (Desktop): 3
Columns (Mobile): 1

Badges:
1. Premium Quality | Handcrafted with care
2. Easy Returns | Hassle-free 60-day returns
3. Eco-Friendly | Sustainably sourced materials
```

### Example 3: Checkout Page

```
Heading: "Safe & Secure Shopping"
Columns (Desktop): 2
Columns (Mobile): 1

Badges:
1. Secure Payment | SSL encrypted checkout
2. Money-Back Guarantee | 100% satisfaction guaranteed
```

## 🎯 Best Practices

### Placement

- **Homepage**: Below hero section or above footer
- **Product Pages**: Below "Add to Cart" button
- **Collection Pages**: At the top or bottom
- **Cart/Checkout**: Near payment buttons

### Content Tips

1. **Be Specific**: "Free shipping on orders over $50" is better than just "Free shipping"
2. **Use Numbers**: "30-day return policy" is more concrete than "Easy returns"
3. **Build Trust**: Focus on what customers care about most
4. **Keep it Short**: Titles should be 2-4 words, descriptions 3-6 words

### Design Tips

1. **Match Your Brand**: Customize colors to match your store
2. **Don't Overdo It**: 3-4 badges is usually enough
3. **Use Contrast**: Make sure text is readable on the background
4. **Test Mobile**: Always check how it looks on mobile devices

## 🔧 Customization Examples

### Minimal Style

```
Background Color: #ffffff
Border Radius: 0px
Gap: 16px
```

### Card Style

```
Background Color: #f5f5f5
Border Radius: 12px
Gap: 24px
```

### Bold Style

```
Background Color: #000000
Text Color: #ffffff
Icon Color: #ffffff
Border Radius: 8px
```

## 🐛 Troubleshooting

**Issue**: Badges not showing up

- **Solution**: Make sure you've added at least one badge block

**Issue**: Layout looks broken on mobile

- **Solution**: Try reducing columns on mobile to 1

**Issue**: Icons not displaying

- **Solution**: Make sure you've selected an icon (not "none")

**Issue**: Colors not changing

- **Solution**: Clear your browser cache and refresh

## 📱 Responsive Behavior

- **Mobile (< 768px)**: Uses `columns_mobile` setting
- **Desktop (≥ 768px)**: Uses `columns_desktop` setting
- Icons scale from 48px to 56px
- Text sizes adjust automatically

## ⚡ Performance

- **No External Dependencies**: All icons are inline SVG (Heroicons)
- **Minimal CSS**: ~2KB of styles
- **Fast Loading**: No JavaScript required
- **SEO Friendly**: Semantic HTML structure
- **Modern Icons**: Professional Heroicons for a polished look

## 🎨 Color Schemes

### Light Mode (Default)

```
Background: #f9f9f9
Text: #000000
Icon: #000000
```

### Dark Mode

```
Background: #1a1a1a
Text: #ffffff
Icon: #ffffff
```

### Brand Colors (Example)

```
Background: #f0f7ff
Text: #003d82
Icon: #0066cc
```

## 📊 Conversion Tips

1. **Above the Fold**: Place trust badges where customers can see them immediately
2. **Near CTAs**: Position close to "Add to Cart" or "Buy Now" buttons
3. **Consistent Messaging**: Match badges with your actual policies
4. **Test Variations**: Try different combinations to see what converts best
5. **Update Regularly**: Keep information current (e.g., shipping thresholds)

---

**Need help?** Check the main [README](../README.md) or open an issue on GitHub.
