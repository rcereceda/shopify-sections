# Hero Banner Section - Usage Guide

🇺🇸 English | [🇪🇸 Leer en español](../es/hero-banner.md)

## 📋 Overview

The Hero Banner section is a full-width, high-impact section perfect for homepages, landing pages, and campaign pages. It supports both image and video backgrounds with customizable overlays and flexible content positioning.

## ✨ Features

- **Flexible Media**:
  - Image background (recommended: 1920x800px or larger)
  - Video background (MP4 format, optional)
  - Automatic fallback to image if video not provided
  - Placeholder if no media selected
- **Image Effects**:

  - **Parallax on scroll**: Creates depth effect as you scroll
  - **Ambient movement**: Subtle circular motion when idle
  - Both effects can be enabled/disabled independently
  - Respects user's motion preferences (accessibility)

- **Professional Design** (Heroicons):
  - Clean, modern Heroicons for mini badges
  - Consistent with Trust Badges section
- **Content Elements**:
  - Eyebrow text (small text above heading)
  - Main heading (H1)
  - Subheading/description (richtext)
  - Up to 2 CTA buttons (primary + secondary)
  - Dynamic mini trust badges (unlimited via blocks)
- **Full Customization**:
  - Overlay color and opacity control
  - Text color customization
  - Vertical positioning (top/center/bottom)
  - Horizontal positioning (left/center/right)
  - Text alignment (left/center/right)
  - Content max-width control
  - Height control (mobile + desktop)
- **Responsive Design**:
  - Optimized for all screen sizes
  - Separate height controls for mobile and desktop
  - Text sizes adapt automatically
  - Touch-friendly buttons

## 🎨 Customization Options

### Media Settings

| Setting              | Type  | Description                                    |
| -------------------- | ----- | ---------------------------------------------- |
| **Background Image** | Image | Main background image (1920x800px recommended) |
| **Video URL**        | URL   | Optional MP4 video URL (see note below)        |

**Video URL Note:**

- Upload your video to **Shopify Files** (Settings → Files), then copy the generated URL
- Or use a CDN URL (your own hosting, Vimeo direct link, etc.)
- Shopify doesn't support uploading videos directly to theme assets (they're too large)
- MP4 format with H.264 codec recommended, keep under 10MB for performance

### Image Effects

| Setting                       | Type     | Default | Description                                                 |
| ----------------------------- | -------- | ------- | ----------------------------------------------------------- |
| **Enable Parallax on Scroll** | Checkbox | Off     | Creates depth effect as you scroll (works best with images) |
| **Enable Ambient Movement**   | Checkbox | Off     | Adds subtle circular motion to the image when idle          |

**Effect Notes:**

- **Parallax**: The image stays fixed while you scroll, creating a depth illusion. Best for hero sections at the top of the page.
- **Ambient Movement**: A gentle 30-second circular animation that adds life to static images. Subtle and professional. **Only applies to images, not videos** (videos already have motion).
- Both effects work together or independently
- Effects are automatically disabled for users who prefer reduced motion (accessibility)

### Overlay Settings

| Setting             | Type  | Default | Description                |
| ------------------- | ----- | ------- | -------------------------- |
| **Overlay Color**   | Color | #000000 | Color of the overlay       |
| **Overlay Opacity** | Range | 40%     | Opacity of overlay (0-80%) |

### Content Settings

| Setting        | Type     | Default                  | Description                |
| -------------- | -------- | ------------------------ | -------------------------- |
| **Eyebrow**    | Text     | "New Collection"         | Small text above heading   |
| **Heading**    | Text     | "Welcome to Our Store"   | Main heading (H1)          |
| **Subheading** | Richtext | "Discover our latest..." | Description text           |
| **Text Color** | Color    | #ffffff                  | Color of all text elements |

### Button Settings

| Setting            | Type | Default      | Description           |
| ------------------ | ---- | ------------ | --------------------- |
| **Button 1 Label** | Text | "Shop Now"   | Primary button text   |
| **Button 1 Link**  | URL  | -            | Primary button URL    |
| **Button 2 Label** | Text | "Learn More" | Secondary button text |
| **Button 2 Link**  | URL  | -            | Secondary button URL  |

### Social Proof Blocks

The Hero Banner supports **two types of blocks** for social proof:

#### 1. Trust Badges (Unlimited)

Mini trust indicators displayed horizontally.

**To add a badge:**

1. In the theme customizer, click "Add block"
2. Select "Trust Badge"
3. Configure icon and text
4. Drag to reorder

**Block Settings:**

| Setting  | Type   | Default         | Description |
| -------- | ------ | --------------- | ----------- |
| **Icon** | Select | Shipping        | Badge icon  |
| **Text** | Text   | "Free Shipping" | Badge text  |

**Available Icons**: None, Free Shipping, Money-Back Guarantee, 24/7 Support, Premium Quality, Easy Returns

#### 2. Featured Testimonial (Limit: 1)

A highlighted customer review with stars, quote, photo, and name.

**To add a testimonial:**

1. In the theme customizer, click "Add block"
2. Select "Featured Testimonial"
3. Configure rating, quote, photo, and customer info

**Block Settings:**

| Setting               | Type         | Default          | Description                 |
| --------------------- | ------------ | ---------------- | --------------------------- |
| **Star Rating**       | Range (0-5)  | 5                | Number of stars (0 to hide) |
| **Testimonial Quote** | Textarea     | (sample text)    | Customer review text        |
| **Customer Photo**    | Image Picker | -                | Customer profile image      |
| **Customer Name**     | Text         | "Sarah Johnson"  | Customer's name             |
| **Customer Title**    | Text         | "Verified Buyer" | Title or company            |

**Benefits of blocks:**

- ✅ Choose between badges, testimonial, or both
- ✅ Add unlimited badges + 1 featured testimonial
- ✅ Reorder with drag & drop
- ✅ Remove blocks easily
- ✅ No code changes needed

### Layout Settings

| Setting                 | Type   | Default | Description                           |
| ----------------------- | ------ | ------- | ------------------------------------- |
| **Vertical Position**   | Select | Center  | Top, Center, or Bottom                |
| **Horizontal Position** | Select | Center  | Left, Center, or Right                |
| **Text Alignment**      | Select | Center  | Left, Center, or Right                |
| **Content Max Width**   | Range  | 700px   | Maximum width of content (400-1000px) |
| **Height (Mobile)**     | Range  | 500px   | Section height on mobile (400-700px)  |
| **Height (Desktop)**    | Range  | 650px   | Section height on desktop (400-900px) |

## 📖 Installation

### Create the Section File

1. Copy the code from `hero-banner.liquid`
2. Go to **Shopify Admin** → **Online Store** → **Themes**
3. Click **Actions** → **Edit code**
4. In the **Sections** folder, click the **"+"** icon
5. Name it `hero-banner.liquid`
6. Paste the code and click **Save**

### Add to Your Page

1. Go to **Online Store** → **Themes** → **Customize**
2. Navigate to your desired page (usually Homepage)
3. Click **Add section**
4. Search for **"Hero Banner"**
5. Click to add it
6. Customize the settings
7. Upload your image/video
8. **Add trust badge blocks** (optional):
   - Click "Add block" inside the Hero Banner section
   - Select "Trust Badge"
   - Choose an icon and enter text
   - Repeat to add more badges
   - Drag blocks to reorder them
9. Click **Save**

## 💡 Usage Examples

### Example 1: E-commerce Store

```
Media:
- Background Image: Product lifestyle shot
- Video: (Optional) Product in use
- Overlay: #000000, 50% opacity

Effects:
- Parallax on Scroll: ✓ Enabled
- Ambient Movement: ✗ Disabled

Content:
- Eyebrow: "NEW ARRIVAL"
- Heading: "Premium Quality Products"
- Subheading: "Discover our curated collection of exceptional items"
- Text Color: #ffffff

Buttons:
- Button 1: "Shop Now" → /collections/all
- Button 2: "Learn More" → /pages/about

Badges (add as blocks):
1. ✓ Free Shipping (icon: shipping)
2. ✓ Easy Returns (icon: returns)
3. ✓ 24/7 Support (icon: support)

Layout:
- Vertical: Center
- Horizontal: Center
- Text Alignment: Center
- Height Desktop: 700px
```

### Example 2: Fashion Store

```
Media:
- Background Image: Model wearing new collection
- Overlay: #1a1a1a, 30% opacity

Effects:
- Parallax on Scroll: ✓ Enabled
- Ambient Movement: ✓ Enabled (adds subtle life to the image)

Content:
- Eyebrow: "SPRING 2026"
- Heading: "New Collection Drops"
- Subheading: "Sustainable fashion for the modern wardrobe"
- Text Color: #ffffff

Buttons:
- Button 1: "Shop Women" → /collections/women
- Button 2: "Shop Men" → /collections/men

Badges (add as blocks):
1. ✓ Free Shipping (icon: shipping)
2. ✓ Easy Returns (icon: returns)
3. ✓ Premium Quality (icon: quality)

Layout:
- Vertical: Center
- Horizontal: Left
- Text Alignment: Left
- Height Desktop: 650px
```

### Example 3: Tech Product Launch

```
Media:
- Background Image: Product hero shot
- Overlay: #0066cc, 60% opacity

Effects:
- Parallax on Scroll: ✗ Disabled
- Ambient Movement: ✓ Enabled (subtle product showcase)

Content:
- Eyebrow: "INTRODUCING"
- Heading: "The Future is Here"
- Subheading: "Experience innovation like never before"
- Text Color: #ffffff

Buttons:
- Button 1: "Pre-Order Now" → /products/new-product
- Button 2: "Watch Video" → #video-section

Badges (add as blocks):
1. ✓ Free Shipping (icon: shipping)
2. ✓ 2-Year Warranty (icon: guarantee)
3. ✓ 24/7 Support (icon: support)

Layout:
- Vertical: Center
- Horizontal: Center
- Text Alignment: Center
- Height Desktop: 800px
```

## 🎯 Best Practices

### Media Guidelines

1. **Image Dimensions**: Use 1920x800px or larger for best quality
2. **Image Format**: JPG for photos, PNG for graphics with transparency
3. **Video Upload**:
   - Go to Shopify Admin → Settings → Files
   - Upload your video (MP4, H.264 codec)
   - Copy the generated CDN URL
   - Paste it in the "Video URL" field
4. **Video Format**: MP4, H.264 codec, max 10MB for fast loading
5. **Video Length**: 10-30 seconds loop works best
6. **Compression**: Optimize images/videos before uploading

### Effect Guidelines

1. **Parallax on Scroll**:

   - ✅ Best for: Hero sections at the top of the page
   - ✅ Works great with: High-quality lifestyle images
   - ⚠️ Avoid with: Videos (can cause performance issues)
   - 💡 Tip: Combine with a darker overlay for better text contrast

2. **Ambient Movement**:

   - ✅ Best for: Static images that need subtle life
   - ✅ Works great with: Product shots, lifestyle photos
   - ⚠️ **Not applied to videos**: Videos already have motion, so ambient movement is automatically disabled when using video backgrounds
   - 💡 Tip: The effect is very subtle - that's intentional for professionalism

3. **Combining Both Effects**:
   - Creates a premium, modern feel
   - Best for fashion, lifestyle, and luxury brands
   - Test on mobile to ensure smooth performance

### Content Tips

1. **Eyebrow Text**: Keep it short (1-3 words), use for categories or announcements
2. **Heading**: Clear, bold, benefit-driven (3-6 words ideal)
3. **Subheading**: Expand on the heading, add context (10-15 words)
4. **Buttons**: Use action verbs ("Shop Now", "Get Started", "Learn More")
5. **Badges**: Highlight key benefits (free shipping, guarantees, etc.)

### Design Tips

1. **Overlay Opacity**:
   - Light images: 20-40% opacity
   - Dark images: 40-60% opacity
   - Busy images: 50-70% opacity
2. **Text Color**:

   - Dark overlay → White text (#ffffff)
   - Light overlay → Dark text (#000000)
   - Ensure contrast for readability

3. **Content Positioning**:

   - **Center/Center**: Most versatile, works for any content
   - **Left/Center**: Great for storytelling, more dynamic
   - **Bottom/Left**: Modern, editorial style

4. **Height**:
   - Homepage hero: 650-800px desktop
   - Landing page: 500-650px desktop
   - Campaign page: 400-550px desktop

### Conversion Tips

1. **Above the Fold**: Make sure heading and CTA are visible without scrolling
2. **Clear CTAs**: Primary button should stand out, secondary is optional
3. **Trust Signals**: Use badges to reduce friction (free shipping, returns, etc.)
4. **Mobile First**: Test on mobile - most traffic comes from phones
5. **Fast Loading**: Optimize media files for quick load times

## 🔧 Customization Examples

### Minimal Style (Clean & Modern)

```
Overlay: #ffffff, 20% opacity
Text Color: #000000
Vertical: Center
Horizontal: Left
Text Alignment: Left
Height: 550px
```

### Bold Style (High Contrast)

```
Overlay: #000000, 70% opacity
Text Color: #ffffff
Vertical: Center
Horizontal: Center
Text Alignment: Center
Height: 750px
```

### Editorial Style (Magazine-like)

```
Overlay: #1a1a1a, 40% opacity
Text Color: #ffffff
Vertical: Bottom
Horizontal: Left
Text Alignment: Left
Height: 650px
```

### Product Focus (E-commerce)

```
Overlay: #ffffff, 30% opacity
Text Color: #000000
Vertical: Center
Horizontal: Right
Text Alignment: Right
Height: 600px
```

## 🐛 Troubleshooting

**Issue**: Video not playing

- **Solution**: Make sure video is MP4 format and URL is correct. Check browser console for errors.

**Issue**: Text is hard to read

- **Solution**: Increase overlay opacity or change text color for better contrast.

**Issue**: Content is cut off on mobile

- **Solution**: Reduce mobile height or adjust vertical positioning.

**Issue**: Buttons are too close together

- **Solution**: This is handled automatically, but you can hide Button 2 if needed.

**Issue**: Badges not showing

- **Solution**: Make sure you've added at least one "Trust Badge" block using the "Add block" button.

**Issue**: Image looks stretched or cropped

- **Solution**: Use recommended dimensions (1920x800px) and ensure image is high quality.

**Issue**: Parallax effect not working

- **Solution**:
  - Make sure "Enable parallax on scroll" is checked
  - Parallax works best with images, not videos
  - Try scrolling the page to see the effect
  - Check that the hero section is at the top of the page

**Issue**: Ambient movement is too subtle / not visible

- **Solution**:
  - The effect is intentionally subtle (30-second loop)
  - Wait a few seconds to see the gentle circular motion
  - The effect scales the image to 1.2x, so ensure your image has enough space
  - Effect is disabled for users with motion sensitivity preferences

**Issue**: Effects causing performance issues

- **Solution**:
  - Disable ambient movement on mobile if needed
  - Optimize image file size (compress before uploading)
  - Avoid using parallax with video backgrounds
  - Test on different devices and browsers

## 📱 Responsive Behavior

### Mobile (< 768px)

- Height: Uses `height_mobile` setting
- Font sizes: Reduced for readability
- Buttons: Stack if needed
- Badges: Wrap to multiple lines
- Padding: 40px vertical, 20px horizontal

### Desktop (≥ 768px)

- Height: Uses `height_desktop` setting
- Font sizes: Full size
- Buttons: Side by side
- Badges: Single line
- Padding: 60px vertical, 40px horizontal

## ⚡ Performance

- **No External Dependencies**: All icons are inline SVG (Heroicons)
- **Optimized Media**: Uses Shopify's image CDN with responsive srcset
- **Minimal CSS**: ~4KB of styles (including parallax effects)
- **No JavaScript**: Pure CSS animations for all effects
- **Fast Loading**: Lazy loading for images, optimized video delivery
- **Accessibility**: Respects `prefers-reduced-motion` for users with motion sensitivity
- **GPU Accelerated**: Parallax and ambient effects use CSS transforms for smooth performance

## 🎨 Color Schemes

### Dark Overlay (Most Common)

```
Overlay: #000000, 40-60%
Text: #ffffff
Buttons: White text on dark background
```

### Light Overlay (Modern)

```
Overlay: #ffffff, 30-50%
Text: #000000
Buttons: Dark text on light background
```

### Brand Color Overlay

```
Overlay: #0066cc (your brand color), 50-70%
Text: #ffffff
Buttons: White text on brand color
```

## 📊 Use Cases

### Perfect For:

- ✅ Homepage hero sections
- ✅ Landing pages
- ✅ Campaign pages
- ✅ Product launches
- ✅ Seasonal promotions
- ✅ Brand storytelling

### Not Ideal For:

- ❌ Product detail pages (use product-specific sections)
- ❌ Blog posts (use article templates)
- ❌ Cart/Checkout (keep these simple)

## 🚀 Pro Tips

### General Recommendations:

**For Product-Focused Stores:**

- Use high-quality product images or lifestyle shots
- Keep heading short and benefit-driven (3-6 words)
- Highlight key differentiators in badges
- Primary button should lead to products/collections

**For Brand Storytelling:**

- Use authentic behind-the-scenes imagery
- Eyebrow text for credibility (year founded, awards, etc.)
- Subheading should convey your unique value
- Secondary button can link to "About" or "Story" page

**For Subscription/Service Businesses:**

- Emphasize convenience and value
- Use action-oriented language
- Badges should address common objections
- Clear CTA for sign-up or trial

---

**Need help?** Check the main [README](../README.md) or open an issue on GitHub.
