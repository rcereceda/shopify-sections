# Featured Products Section

A flexible and highly customizable section to showcase your best products. Perfect for highlighting bestsellers, new arrivals, seasonal items, or any curated collection of products.

## 📋 Overview

The Featured Products section displays products from any Shopify collection in a beautiful, responsive grid. It includes product images, titles, prices, sale badges, and customizable call-to-action buttons.

## ✨ Features

### Content Features
- **Collection Integration**: Pull products from any Shopify collection
- **Flexible Product Limit**: Show 2-12 products
- **Heading & Subheading**: Customizable section titles
- **Product Information**: Image, title, vendor, description, price
- **Sale Badges**: Automatic discount percentage display
- **Compare Prices**: Show original price when on sale
- **View All Button**: Link to the full collection
- **Image Hover Effect**: Show second product image on hover (if available)

### Design Features
- **Responsive Grid**: 1 column on mobile (default), 2-4 on desktop
- **Card Customization**: Border, radius, padding, background
- **Image Control**: Aspect ratio (square, portrait, landscape) and fit options
- **Typography Control**: Sizes and colors for all text elements
- **Button Styling**: Fully customizable CTA buttons
- **Hover Effects**: Smooth shadow animation + button reveal

### Performance Features
- **Lazy Loading**: Images load as needed
- **Responsive Images**: Srcset for optimal image sizes
- **Optimized Markup**: Clean, semantic HTML

## 🎨 Customization Options

### Content Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading | Text | "Featured Products" | Main section title |
| Subheading | Text | "Discover our most popular items" | Section subtitle |
| Collection | Collection Picker | - | Source collection for products |
| Maximum Products | Range (2-12) | 4 | Number of products to display |

### Layout Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Columns (mobile) | Select | 1 column | Grid columns on mobile (1 or 2) |
| Columns (desktop) | Range (2-4) | 4 | Grid columns on desktop |
| Gap Between Products | Range (8-48px) | 24px | Space between product cards |
| Container Width | Range (1000-1600px) | 1200px | Maximum section width |

### Heading Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading Alignment | Select | Center | Left, Center, or Right |
| Heading Size (mobile) | Range (20-48px) | 28px | Mobile heading font size |
| Heading Size (desktop) | Range (24-64px) | 36px | Desktop heading font size |
| Space Below Heading | Range (16-64px) | 32px | Margin below heading |
| Heading Color | Color | #000000 | Heading text color |
| Subheading Color | Color | #666666 | Subheading text color |

### Product Card Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Card Background | Color | #ffffff | Card background color |
| Card Border Width | Range (0-4px) | 1px | Border thickness |
| Card Border Color | Color | #e5e5e5 | Border color |
| Card Border Radius | Range (0-24px) | 8px | Corner roundness |
| Card Padding | Range (8-32px) | 16px | Internal padding |

### Product Image

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Second Image on Hover | Checkbox | On | Display second product image on hover |
| Image Aspect Ratio | Select | Square (1:1) | Image proportions |
| Image Fit | Select | Cover | How image fills container |
| Image Background Color | Color | #f5f5f5 | Background for transparent images |

**Image Ratio Options:**
- Square (1:1) - 100%
- Portrait (4:5) - 125%
- Portrait (3:4) - 133%
- Landscape (4:3) - 75%

### Product Info

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Vendor | Checkbox | Off | Display product vendor/brand |
| Vendor Color | Color | #999999 | Vendor text color |
| Title Color | Color | #000000 | Product title color |
| Title Size | Range (14-24px) | 16px | Title font size |
| Show Description | Checkbox | Off | Display product description |
| Description Color | Color | #666666 | Description text color |
| Price Color | Color | #000000 | Price text color |
| Price Size | Range (14-24px) | 18px | Price font size |
| Compare Price Color | Color | #999999 | Original price color |

### Sale Badge

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Sale Badge | Checkbox | On | Display discount percentage |
| Badge Background | Color | #ff0000 | Badge background color |
| Badge Text Color | Color | #ffffff | Badge text color |

### Button

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Button | Checkbox | On | Display CTA button below card (appears on hover) |
| Button Text | Text | "Buy Now" | Button label |
| Button Background | Color | #000000 | Button background color |
| Button Text Color | Color | #ffffff | Button text color |
| Button Border Radius | Range (0-24px) | 4px | Button corner roundness |

### View All Button

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show 'View All' Button | Checkbox | On | Display collection link |
| Button Text | Text | "Shop Now" | Button label |
| Space Above Button | Range (24-80px) | 48px | Top margin |
| Background | Color | #ffffff | Button background |
| Text Color | Color | #000000 | Button text color |
| Border Color | Color | #000000 | Button border color |

### Section Spacing

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Padding Top | Range (0-120px) | 60px | Top spacing |
| Padding Bottom | Range (0-120px) | 60px | Bottom spacing |
| Background Color | Color | #f5f5f5 | Section background |

## 📦 Installation

### Step 1: Copy the Section Code

1. Navigate to [`sections/featured-products.liquid`](../sections/featured-products.liquid)
2. Copy the entire file content

### Step 2: Create the Section File

1. Go to your Shopify Admin
2. Navigate to **Online Store** → **Themes**
3. Click **Actions** → **Edit code**
4. In the **Sections** folder, click **Add a new section**
5. Name it `featured-products`
6. Paste the copied code
7. Click **Save**

### Step 3: Add to Your Theme

1. Go to **Online Store** → **Themes** → **Customize**
2. Navigate to the page where you want to add the section
3. Click **Add section**
4. Select **Featured Products**
5. Configure the settings as desired
6. Click **Save**

## 🎯 Usage Examples

### Example 1: Homepage Bestsellers

**Use Case**: Showcase your top-selling products on the homepage

**Settings**:
- **Heading**: "Our Bestsellers"
- **Subheading**: "Customer favorites that keep selling out"
- **Collection**: Select your "Bestsellers" collection
- **Products Limit**: 4
- **Columns (desktop)**: 4
- **Show Sale Badge**: On
- **Show Button**: On, "Shop Now"

### Example 2: New Arrivals

**Use Case**: Highlight recently added products

**Settings**:
- **Heading**: "Just Arrived"
- **Subheading**: "Fresh products added this week"
- **Collection**: Select your "New Arrivals" collection
- **Products Limit**: 6
- **Columns (desktop)**: 3
- **Show Vendor**: On (if multiple brands)
- **Show Description**: On

### Example 3: Seasonal Collection

**Use Case**: Feature seasonal or limited-time products

**Settings**:
- **Heading**: "Summer Collection"
- **Subheading**: "Limited time only"
- **Collection**: Select your seasonal collection
- **Products Limit**: 8
- **Columns (desktop)**: 4
- **Sale Badge Color**: Custom brand color
- **Button Text**: "Shop Summer"

### Example 4: Category Landing Page

**Use Case**: Show featured products for a specific category

**Settings**:
- **Heading**: "Featured Coffee Blends"
- **Subheading**: "Hand-selected by our roasters"
- **Collection**: "Featured Coffee"
- **Products Limit**: 4
- **Show Description**: On
- **Image Ratio**: Portrait (4:5)
- **View All**: "Explore All Coffees"

## 💡 Best Practices

### Collection Setup

1. **Create Dedicated Collections**
   - Create specific collections for featured products
   - Use automated collections with conditions (e.g., "tag equals featured")
   - Keep collections updated with your best products

2. **Product Curation**
   - Feature 4-8 products for optimal impact
   - Choose products with high-quality images
   - Include a mix of bestsellers and new items
   - Ensure all products are in stock

3. **Strategic Placement**
   - Homepage: Show bestsellers or new arrivals
   - Category pages: Feature products from that category
   - Landing pages: Highlight products relevant to the campaign

### Design Tips

1. **Image Consistency**
   - Use consistent image styles across products
   - Ensure all images have similar lighting and backgrounds
   - Use the same aspect ratio for all product images
   - Recommended: Square (1:1) or Portrait (4:5)

2. **Grid Layout**
   - **2 columns**: Best for detailed product cards with descriptions
   - **3 columns**: Balanced layout for most use cases
   - **4 columns**: Compact grid for showcasing many products

3. **Color Scheme**
   - Match section colors to your brand
   - Ensure sufficient contrast for readability
   - Use sale badge color strategically (red for urgency)
   - Keep button colors consistent with site-wide CTAs

4. **Typography**
   - Keep product titles concise (2-3 words ideal)
   - Use descriptions sparingly (toggle off if not needed)
   - Ensure price is prominent and easy to read

### Conversion Optimization

1. **Sale Badges**
   - Always show sale badges when products are discounted
   - Percentage-off creates urgency
   - Use contrasting colors for visibility

2. **Call-to-Action**
   - Use action-oriented button text ("Shop Now", "Add to Cart")
   - Keep button text short (1-3 words)
   - Ensure buttons stand out with contrasting colors

3. **Social Proof**
   - Show vendor names for multi-brand stores
   - Consider adding review stars (requires app integration)
   - Use "View All" button to drive collection page traffic

4. **Mobile Optimization**
   - Use 2 columns on mobile for better visibility
   - Ensure images are clear at smaller sizes
   - Test touch targets are large enough (min 44px)

## 🔧 Troubleshooting

### No Products Showing

**Problem**: Section displays "No products found in this collection"

**Solutions**:
1. Verify a collection is selected in section settings
2. Check that the collection has published products
3. Ensure products in the collection are active and in stock
4. Verify collection isn't empty or hidden

### Images Not Loading

**Problem**: Product images appear broken or don't load

**Solutions**:
1. Check that products have featured images assigned
2. Verify image files aren't corrupted
3. Ensure images are published (not in draft mode)
4. Try re-uploading product images

### Layout Issues on Mobile

**Problem**: Products don't display correctly on mobile devices

**Solutions**:
1. Check "Columns (mobile)" setting (should be 1-2)
2. Reduce card padding if cards feel cramped
3. Adjust grid gap for better spacing
4. Test on actual mobile device, not just browser resize

### Sale Badge Not Showing

**Problem**: Discount badge doesn't appear on sale products

**Solutions**:
1. Verify "Show Sale Badge" is enabled
2. Check that product has both price and compare_at_price set
3. Ensure compare_at_price is higher than price
4. Verify badge colors aren't same as background

### Slow Loading

**Problem**: Section takes long to load

**Solutions**:
1. Reduce number of products shown
2. Optimize product images (compress before uploading)
3. Use lazy loading (already built-in)
4. Consider using smaller image ratio

## 📱 Responsive Behavior

### Mobile (< 768px)
- Grid switches to mobile column count (1-2)
- Heading size reduces to mobile size
- Touch-optimized hover states
- Stacked layout for better readability

### Tablet (768px - 1024px)
- Desktop column count applies
- Desktop heading size applies
- Full hover effects enabled

### Desktop (> 1024px)
- Full desktop layout
- Maximum container width applies
- Optimal spacing and typography

## 🚀 Performance

### Optimization Features
- **Lazy Loading**: Images load only when visible
- **Responsive Images**: Srcset provides optimal sizes
- **Efficient Markup**: Minimal DOM elements
- **CSS-only Animations**: No JavaScript overhead

### Best Practices
- Limit products to 8-12 maximum
- Optimize product images before upload (recommended: 1200x1200px)
- Use WebP format when possible
- Avoid showing descriptions unless necessary

## 🎨 Color Scheme Examples

### Minimal & Clean
```
Background: #ffffff
Card Background: #ffffff
Card Border: #e5e5e5
Heading: #000000
Price: #000000
Button: #000000 / #ffffff
```

### Bold & Modern
```
Background: #f8f8f8
Card Background: #ffffff
Card Border: #000000
Heading: #000000
Price: #ff0000
Button: #ff0000 / #ffffff
```

### Elegant & Sophisticated
```
Background: #fafafa
Card Background: #ffffff
Card Border: #d4d4d4
Heading: #2c2c2c
Price: #8b7355
Button: #2c2c2c / #ffffff
```

### Warm & Inviting
```
Background: #fff9f5
Card Background: #ffffff
Card Border: #f0e5dc
Heading: #5c4033
Price: #d4a574
Button: #5c4033 / #ffffff
```

## 🔗 Integration with Other Sections

### Works Great With:
- **Hero Banner**: Feature products after hero
- **Trust Badges**: Build credibility before products
- **Testimonials**: Add social proof after products
- **FAQ**: Answer questions after showcasing products

### Recommended Page Flow:
1. Hero Banner (with CTA)
2. Trust Badges (build trust)
3. **Featured Products** (showcase products)
4. Testimonials (social proof)
5. FAQ (answer objections)

## 📊 Conversion Tips

1. **Feature 4-6 Products**: Sweet spot for conversion
2. **Show Sale Badges**: Creates urgency and value perception
3. **Use Action Buttons**: "Shop Now" converts better than "View"
4. **Add View All**: Drives traffic to collection pages
5. **Update Regularly**: Keep products fresh and seasonal
6. **Test Layouts**: A/B test 3 vs 4 columns
7. **Mobile First**: 60%+ traffic is mobile, optimize for it

## 🆘 Need Help?

If you encounter issues or need customization help:
1. Check the troubleshooting section above
2. Review Shopify's [Theme Development Documentation](https://shopify.dev/docs/themes)
3. Test in Shopify's Theme Customizer preview mode
4. Verify all products and collections are properly set up

---

**Version**: 1.0.0  
**Last Updated**: January 2026  
**Compatibility**: Shopify 2.0 themes
