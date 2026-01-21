# Testimonials Section

A powerful section to showcase customer reviews and build social proof. Display authentic testimonials with star ratings, customer photos, and detailed reviews to increase trust and conversions.

## 📋 Overview

The Testimonials section helps you build credibility by showcasing real customer experiences. It features a responsive grid of testimonial cards, each with a customer photo, name, star rating, and review text.

## ✨ Features

### Content Features
- **Up to 12 Testimonials**: Add multiple customer reviews
- **Star Ratings**: 1-5 star rating system with visual stars
- **Customer Photos**: Upload customer images or use placeholder
- **Role/Company Display**: Show customer title or company name
- **Quote Icon**: Optional decorative quote marks
- **Flexible Text**: Support for short or long-form reviews

### Design Features
- **Responsive Grid**: 1 column on mobile, up to 3 on desktop
- **Card Customization**: Border, radius, padding, background
- **Hover Effects**: Smooth lift animation on hover
- **Typography Control**: Customizable sizes and colors
- **Image Options**: Square or circular customer photos
- **Visual Hierarchy**: Clear separation between rating, text, and customer info

### Performance Features
- **Lazy Loading**: Images load as needed
- **Optimized Markup**: Clean, semantic HTML
- **Flexible Layout**: Auto-adjusts to content length

## 🎨 Customization Options

### Content Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading | Text | "What Our Customers Say" | Main section title |
| Subheading | Textarea | "Real reviews from real customers" | Section subtitle |

### Layout Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Container Width | Range (1000-1600px) | 1200px | Maximum section width |
| Columns (Mobile) | Select | 1 column | Grid columns on mobile (1 or 2) |
| Columns (Desktop) | Range (1-3) | 3 | Grid columns on desktop |
| Gap Between Cards | Range (8-48px) | 24px | Space between testimonial cards |

### Heading Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading Alignment | Select | Center | Left, Center, or Right |
| Heading Size (Mobile) | Range (20-48px) | 28px | Mobile heading font size |
| Heading Size (Desktop) | Range (24-64px) | 36px | Desktop heading font size |
| Space Below Heading | Range (16-64px) | 40px | Margin below heading |
| Heading Color | Color | #000000 | Heading text color |
| Subheading Color | Color | #666666 | Subheading text color |

### Card Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Card Background | Color | #ffffff | Card background color |
| Card Border Width | Range (0-4px) | 1px | Border thickness |
| Card Border Color | Color | #e5e5e5 | Border color |
| Card Border Radius | Range (0-24px) | 12px | Corner roundness |
| Card Padding | Range (16-48px) | 24px | Internal padding |

### Rating

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Star Rating | Checkbox | On | Display star ratings |
| Star Size | Range (14-32px) | 20px | Star icon size |
| Star Color (Filled) | Color | #ffc107 | Color for filled stars |
| Star Color (Empty) | Color | #e0e0e0 | Color for empty stars |

### Review Text

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Show Quote Icon | Checkbox | On | Display quote marks |
| Text Size | Range (14-20px) | 16px | Review text font size |
| Text Color | Color | #333333 | Review text color |

### Customer Info

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Image Size | Range (40-80px) | 56px | Customer photo size |
| Image Border Radius | Range (0-50%) | 50% | Image roundness (50% = circle) |
| Placeholder Background | Color | #f0f0f0 | Background for missing photos |
| Placeholder Icon Color | Color | #cccccc | Icon color for placeholders |
| Name Size | Range (14-20px) | 16px | Customer name font size |
| Name Color | Color | #000000 | Customer name color |
| Show Customer Role/Company | Checkbox | On | Display role or company |
| Role Size | Range (12-16px) | 14px | Role text font size |
| Role Color | Color | #666666 | Role text color |

### Spacing

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Top Padding (Mobile) | Range (20-100px) | 40px | Top spacing on mobile |
| Bottom Padding (Mobile) | Range (20-100px) | 40px | Bottom spacing on mobile |
| Top Padding (Desktop) | Range (40-160px) | 80px | Top spacing on desktop |
| Bottom Padding (Desktop) | Range (40-160px) | 80px | Bottom spacing on desktop |

### Colors

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Background Color | Color | #f9f9f9 | Section background |

## 🧩 Block Settings

Each testimonial is added as a **Testimonial Block** with the following settings:

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Star Rating | Range (1-5) | 5 | Number of stars (1-5) |
| Review Text | Textarea | (sample text) | Customer review content |
| Customer Photo | Image Picker | - | Customer profile image |
| Customer Name | Text | "Sarah Johnson" | Customer's name |
| Role or Company | Text | "Verified Buyer" | Optional title/company |

**Block Limit**: Up to 12 testimonials

## 📱 Responsive Behavior

### Mobile (< 768px)
- 1 column layout (default)
- Smaller heading sizes
- Reduced padding
- Full-width cards
- Touch-friendly spacing

### Desktop (≥ 768px)
- 1-3 columns (configurable)
- Larger typography
- Hover effects active
- Optimal card proportions

## 🎯 Use Cases

### Homepage
Perfect for building immediate trust with new visitors. Place after hero section or featured products.

### Product Pages
Show product-specific testimonials to reduce purchase hesitation. Place near Add to Cart button.

### About Page
Showcase customer satisfaction and brand reputation with diverse testimonials.

### Landing Pages
Build credibility for specific campaigns or promotions with targeted reviews.

## 💡 Best Practices

### Content
- **Keep it Real**: Use authentic customer reviews, not generic testimonials
- **Vary Length**: Mix short and detailed reviews for visual interest
- **Show Diversity**: Include different customer types and use cases
- **Update Regularly**: Refresh with new testimonials to show ongoing satisfaction
- **Use Photos**: Real customer photos build more trust than placeholders

### Design
- **3 Columns Max**: More than 3 columns makes cards too narrow
- **Consistent Ratings**: Most testimonials should be 4-5 stars for credibility
- **Readable Text**: Keep review text size at 15-16px minimum
- **Visual Balance**: Maintain consistent card heights with similar text lengths

### Placement
- **Above the Fold**: Place high on homepage for immediate impact
- **Near CTAs**: Position close to purchase decisions
- **After Features**: Use to validate product claims
- **Before Footer**: End pages with social proof

## 🔧 Technical Details

### Performance
- Images use lazy loading for faster page loads
- Minimal CSS for quick rendering
- No external dependencies
- Optimized for Core Web Vitals

### Accessibility
- Semantic HTML structure
- Alt text for customer images
- Color contrast compliant
- Screen reader friendly

### Browser Support
- All modern browsers
- IE11+ (with graceful degradation)
- Mobile browsers (iOS Safari, Chrome)

## 📝 Installation

### Step 1: Add to Theme
1. Copy `testimonials.liquid` to your theme's `sections/` folder
2. Or create a symlink if using a development workflow

### Step 2: Add to Page
1. Go to **Online Store** > **Themes** > **Customize**
2. Navigate to the page where you want testimonials
3. Click **Add section**
4. Select **Testimonials**

### Step 3: Add Testimonials
1. In the section settings, click **Add block**
2. Select **Testimonial**
3. Fill in:
   - Star rating (1-5)
   - Review text
   - Customer photo (optional)
   - Customer name
   - Role or company (optional)
4. Repeat to add more testimonials (up to 12)

### Step 4: Customize Design
1. Adjust layout (columns, spacing)
2. Customize colors and typography
3. Configure card styling
4. Set section spacing
5. Preview and save

## 🎨 Design Examples

### Classic Layout
- 3 columns on desktop
- White cards with subtle border
- Circular customer photos
- Gold stars (#ffc107)
- Light gray background

### Modern Minimal
- 2 columns on desktop
- Borderless cards
- Square customer photos
- Black stars
- White background

### Bold & Colorful
- 3 columns on desktop
- Colored card backgrounds
- Circular photos with border
- Custom brand color stars
- Contrasting background

## 🚀 Pro Tips

1. **Social Proof Hierarchy**: Place your best testimonials first (left to right, top to bottom)
2. **Specific Details**: Encourage testimonials that mention specific features or benefits
3. **Verified Badges**: Use the role field to add "Verified Buyer" or "Verified Purchase"
4. **Video Alternative**: Link customer names to video testimonials on YouTube
5. **A/B Testing**: Test different numbers of testimonials (3 vs 6 vs 9)
6. **Mobile First**: Always check how testimonials look on mobile devices
7. **Loading Speed**: Optimize customer photos to under 50KB each
8. **Trust Signals**: Include company logos in the role field for B2B testimonials

## 🔄 Updates & Maintenance

### Regular Updates
- Add new testimonials monthly
- Rotate featured reviews seasonally
- Update customer photos if needed
- Refresh copy to stay relevant

### Quality Control
- Verify all testimonials are authentic
- Check for typos and grammar
- Ensure photos are high quality
- Test on multiple devices

## 🆘 Troubleshooting

### Cards Have Different Heights
**Solution**: Keep review text lengths similar, or use CSS to set min-height

### Stars Not Showing
**Solution**: Check that "Show Star Rating" is enabled in section settings

### Images Not Loading
**Solution**: Ensure images are uploaded and under 2MB in size

### Layout Breaks on Mobile
**Solution**: Use 1 column on mobile for best results

### Text Too Small
**Solution**: Increase text size in settings (minimum 15px recommended)

## 📊 Conversion Impact

Testimonials can significantly impact conversion rates:
- **Trust Building**: 72% of customers trust reviews as much as personal recommendations
- **Purchase Confidence**: 88% of consumers trust online reviews
- **Social Proof**: Testimonials can increase conversions by 34%
- **Credibility**: Real photos increase trust by 95%

## 🔗 Related Sections

- **Featured Products**: Pair with testimonials to show product quality
- **Trust Badges**: Combine for maximum credibility
- **FAQ**: Answer objections that testimonials don't cover
- **Hero Banner**: Use testimonial quotes in hero text

## 📚 Additional Resources

- [Shopify Section Documentation](https://shopify.dev/docs/themes/architecture/sections)
- [Social Proof Psychology](https://www.nngroup.com/articles/social-proof-ux/)
- [Review Collection Best Practices](https://www.shopify.com/blog/customer-reviews)

---

**Need Help?** This section is fully customizable through the Shopify theme editor. No coding required!
