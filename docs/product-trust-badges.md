# Product Trust Badges Block - Usage Guide

## 📋 Overview

The Product Trust Badges block displays trust indicators in a vertical list format, designed specifically to be placed within Product Details sections, typically below the "Add to Cart" button.

## ✨ Features

- **Vertical Layout**: Stacked badges (top to bottom) for easy scanning
- **Compact Design**: Optimized for product pages
- **4 Configurable Badges**: Enable/disable each badge individually
- **6 Built-in Icons**:
  - 🚚 Free Shipping
  - 🔒 Secure Payment
  - ✅ Money-Back Guarantee
  - ↩️ Easy Returns
  - ⭐ Premium Quality
  - 💬 24/7 Support
- **Fully Customizable**: Colors, spacing, and content
- **No Dependencies**: Pure Liquid and CSS

## 🎯 Why Use This Block?

### Conversion Impact

| Benefit                       | Impact                         |
| ----------------------------- | ------------------------------ |
| **Reduces Purchase Friction** | +10-42% conversion rate        |
| **Answers Objections**        | Before customers ask           |
| **Builds Trust**              | At critical decision moment    |
| **Mobile Optimized**          | Vertical layout = easy to read |

### Best Placement

```
Product Image
Product Title
Price
Variant Selector
[Add to Cart Button]
                           ← Place block HERE
🚚 Free Shipping
   On orders over $50
🔒 Secure Checkout
   SSL encrypted
↩️ Easy Returns
   30-day policy
```

## 🎨 Customization Options

### Block Settings

| Setting        | Type   | Default | Description          |
| -------------- | ------ | ------- | -------------------- |
| **Text Color** | Color  | #000000 | Color for all text   |
| **Icon Color** | Color  | #000000 | Color for all icons  |
| **Gap**        | 8-24px | 12px    | Space between badges |
| **Margin Top** | 0-40px | 16px    | Space above block    |

### Per Badge Settings (x4)

| Setting         | Type     | Default | Description                |
| --------------- | -------- | ------- | -------------------------- |
| **Enable**      | Checkbox | Varies  | Show/hide this badge       |
| **Icon**        | Select   | Varies  | Choose from 6 icons        |
| **Title**       | Text     | Varies  | Main badge text            |
| **Description** | Text     | Varies  | Supporting text (optional) |

## 📖 Installation

### Step 1: Create the Block File

1. Copy the code from `product-trust-badges.liquid`
2. Go to **Shopify Admin** → **Online Store** → **Themes**
3. Click **Actions** → **Edit code**
4. In the **Blocks** folder, click the **"+"** icon (or right-click → **New file**)
5. Name it `product-trust-badges.liquid`
6. Paste the code and click **Save**

> **Note**: If you don't see a "Blocks" folder, your theme might not support blocks yet. You'll need to upgrade to a Shopify 2.0 theme.

### Step 2: Add Block to Product Page

1. Go back to **Online Store** → **Themes**
2. Click **Customize**
3. Navigate to **Products** → **Default product**
4. Find the **Product information** section
5. Click **Add block** (inside the Product information section)
6. Search for **"Product Trust Badges"**
7. Drag it below the "Buy buttons" block
8. Customize the settings
9. Click **Save**

## 💡 Usage Examples

### Example 1: E-commerce Standard

**Recommended for most stores**

```
Badge 1: 🚚 Free Shipping | On orders over $50
Badge 2: 🔒 Secure Checkout | SSL encrypted
Badge 3: ↩️ Easy Returns | 30-day policy
Badge 4: Disabled
```

### Example 2: Premium Products

**For high-ticket items**

```
Badge 1: ✅ Money-Back Guarantee | 60-day full refund
Badge 2: ⭐ Premium Quality | Handcrafted materials
Badge 3: 💬 24/7 Support | Expert assistance
Badge 4: 🚚 Free Shipping | Worldwide
```

### Example 3: Fast Fashion

**For time-sensitive products**

```
Badge 1: 🚚 Free Shipping | Orders over $30
Badge 2: ↩️ Easy Returns | 14-day policy
Badge 3: 🔒 Secure Checkout | Safe payment
Badge 4: Disabled
```

## 🎯 Best Practices

### Content Tips

1. **Be Specific**: "Free shipping over $50" > "Free shipping"
2. **Use Numbers**: "30-day returns" > "Easy returns"
3. **Keep it Short**: Title 2-3 words, description 3-5 words
4. **Match Reality**: Only promise what you can deliver

### Design Tips

1. **3 Badges is Optimal**: Don't overwhelm with too many
2. **Match Brand Colors**: Customize icon/text colors
3. **Test on Mobile**: Vertical layout shines on mobile
4. **Place Below CTA**: After "Add to Cart" button

### Conversion Tips

1. **Address Top Objections**: Shipping cost, security, returns
2. **Use Social Proof**: "Trusted by 10,000+ customers"
3. **Create Urgency**: "Limited stock" or "Sale ends soon"
4. **A/B Test**: Try different badge combinations

## 🔧 Customization Examples

### Minimal Style

```
Text Color: #333333
Icon Color: #666666
Gap: 8px
Margin Top: 12px
```

### Bold Style

```
Text Color: #000000
Icon Color: #0066cc (brand blue)
Gap: 16px
Margin Top: 20px
```

### Subtle Style

```
Text Color: #666666
Icon Color: #999999
Gap: 12px
Margin Top: 16px
```

## 🐛 Troubleshooting

**Issue**: Block doesn't appear in the block list

- **Solution**: Make sure you created it in the **Blocks** folder (not Sections)
- **Solution**: Your theme must support Shopify 2.0 blocks

**Issue**: Can't add block to Product page

- **Solution**: You can only add blocks INSIDE sections (like Product information)
- **Solution**: Look for "Add block" button inside existing sections

**Issue**: Badges look too cramped

- **Solution**: Increase the "Gap between badges" setting (try 16px)

**Issue**: Text is hard to read

- **Solution**: Adjust text color to have better contrast with your theme

## 📱 Responsive Behavior

- **Mobile**: Vertical layout works perfectly (one badge per line)
- **Tablet**: Same vertical layout (consistent experience)
- **Desktop**: Same vertical layout (maintains readability)

**Why vertical?**

- ✅ Easier to scan on all devices
- ✅ More space for text
- ✅ Better for mobile (most traffic)
- ✅ Cleaner, more professional look

## ⚡ Performance

- **No External Dependencies**: All icons are inline SVG
- **Minimal CSS**: ~1KB of styles
- **No JavaScript**: Pure HTML/CSS
- **Fast Loading**: No additional HTTP requests

## 🎨 Icon Reference

| Icon             | Best For           | Common Text                             |
| ---------------- | ------------------ | --------------------------------------- |
| 🚚 **Shipping**  | Free/fast shipping | "Free shipping over $X"                 |
| 🔒 **Secure**    | Payment security   | "Secure checkout", "SSL encrypted"      |
| ✅ **Guarantee** | Money-back promise | "30-day guarantee", "100% satisfaction" |
| ↩️ **Returns**   | Return policy      | "Easy returns", "14-day policy"         |
| ⭐ **Quality**   | Product quality    | "Premium quality", "Handcrafted"        |
| 💬 **Support**   | Customer service   | "24/7 support", "Expert help"           |

## 📊 A/B Testing Ideas

Test these variations to find what converts best:

1. **3 badges vs 4 badges**: Less might be more
2. **With descriptions vs without**: Test if details help or distract
3. **Different icon colors**: Brand color vs neutral
4. **Badge order**: Try different sequences
5. **Above vs below CTA**: Test placement (though below is recommended)

## 🚀 Pro Tips

1. **Match Your Policies**: Only show badges for policies you actually have
2. **Update Seasonally**: Change shipping threshold during holidays
3. **Localize**: Different badges for different markets
4. **Track Impact**: Use analytics to measure conversion lift
5. **Keep Updated**: Review and update text quarterly

---

**Need help?** Check the main [README](../README.md) or open an issue on GitHub.
