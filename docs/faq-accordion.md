# FAQ Accordion Section

A clean and interactive section to display frequently asked questions with smooth collapsible answers. Perfect for reducing customer support inquiries and improving user experience.

## 📋 Overview

The FAQ Accordion section helps customers find answers quickly with an elegant expand/collapse interface. Features smooth animations, customizable styling, and SEO-friendly structured data.

## ✨ Features

### Content Features
- **Up to 20 FAQ Items**: Add unlimited questions and answers
- **Rich Text Answers**: Support for formatted text, lists, and links
- **Auto-Open First**: Optionally open first item by default
- **Single/Multiple Open**: Choose if multiple items can be open simultaneously
- **SEO Structured Data**: Schema.org markup for better search visibility
- **Semantic HTML**: Proper heading hierarchy and accessibility

### Design Features
- **Smooth Animations**: Elegant expand/collapse transitions
- **3 Icon Styles**: Plus/Minus, Chevron, or Arrow
- **Icon Rotation**: Icons rotate when items expand
- **Hover Effects**: Subtle border and shadow on hover
- **Fully Customizable**: Colors, spacing, typography, borders
- **Responsive Design**: Works perfectly on all devices

### Interaction Features
- **Click to Expand**: Intuitive accordion behavior
- **Keyboard Accessible**: Full keyboard navigation support
- **ARIA Labels**: Screen reader friendly
- **Close Others Option**: Accordion or independent mode

## 🎨 Customization Options

### Content Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading | Text | "Frequently Asked Questions" | Main section title |
| Subheading | Textarea | (sample text) | Section subtitle |

### Behavior Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Open First Item by Default | Checkbox | On | First FAQ opens automatically |
| Close Other Items When Opening One | Checkbox | On | Only one item open at a time |
| Enable FAQ Schema (SEO) | Checkbox | On | Adds structured data for search engines |

### Layout Settings

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Container Width | Range (600-1200px) | 900px | Maximum section width |
| Space Between Items | Range (8-32px) | 12px | Gap between FAQ items |

### Heading Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Heading Alignment | Select | Center | Left, Center, or Right |
| Heading Size (Mobile) | Range (20-48px) | 28px | Mobile heading font size |
| Heading Size (Desktop) | Range (24-64px) | 36px | Desktop heading font size |
| Space Below Heading | Range (16-64px) | 40px | Margin below heading |
| Heading Color | Color | #000000 | Heading text color |
| Subheading Color | Color | #666666 | Subheading text color |

### Item Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Item Background | Color | #ffffff | FAQ item background |
| Item Border Width | Range (0-4px) | 1px | Border thickness |
| Item Border Color | Color | #e5e5e5 | Border color |
| Enable Hover Effect | Checkbox | On | Show hover state |
| Item Border Color (Hover) | Color | #999999 | Border color on hover |
| Item Border Radius | Range (0-24px) | 8px | Corner roundness |

### Question Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Question Padding | Range (12-32px) | 20px | Internal padding |
| Question Hover Background | Color | #f9f9f9 | Background on hover |
| Question Size (Mobile) | Range (14-24px) | 16px | Mobile font size |
| Question Size (Desktop) | Range (16-28px) | 18px | Desktop font size |
| Question Color | Color | #000000 | Question text color |
| Question Font Weight | Select | Semi Bold | Normal, Medium, Semi Bold, Bold |

### Icon Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Icon Style | Select | Plus/Minus | Plus, Chevron, or Arrow |
| Icon Size | Range (16-32px) | 24px | Icon dimensions |
| Icon Color | Color | #000000 | Icon color |

**Icon Options:**
- **Plus/Minus**: Classic + that becomes - when open
- **Chevron**: Downward pointing chevron that rotates
- **Arrow**: Downward arrow that rotates

### Answer Style

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Answer Bottom Padding | Range (12-32px) | 20px | Padding below answer |
| Answer Size | Range (14-20px) | 16px | Answer text size |
| Answer Color | Color | #666666 | Answer text color |

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

Each FAQ is added as an **FAQ Item Block** with the following settings:

| Setting | Type | Default | Description |
|---------|------|---------|-------------|
| Question | Text | "What is your return policy?" | The question text |
| Answer | Rich Text | (sample answer) | The answer with formatting support |

**Block Limit**: Up to 20 FAQ items

**Rich Text Support:**
- Paragraphs
- Bold and italic text
- Bullet and numbered lists
- Links
- Line breaks

## 📱 Responsive Behavior

### Mobile (< 768px)
- Smaller text sizes
- Reduced padding
- Touch-friendly tap targets
- Full-width container
- Optimized spacing

### Desktop (≥ 768px)
- Larger typography
- Hover effects active
- Optimal reading width
- Enhanced spacing

## 🎯 Use Cases

### Product Pages
Answer product-specific questions to reduce purchase hesitation. Place near Add to Cart button.

### Homepage
Address common questions about shipping, returns, and policies to build trust.

### Support/Help Pages
Create a comprehensive self-service knowledge base to reduce support tickets.

### Landing Pages
Address objections and concerns specific to your campaign or offer.

### Footer
Provide quick access to essential information on every page.

## 💡 Best Practices

### Content
- **Clear Questions**: Use natural language that customers actually search for
- **Concise Answers**: Keep answers brief but complete (2-4 sentences ideal)
- **Prioritize Order**: Put most common questions first
- **Update Regularly**: Add new questions based on customer inquiries
- **Use Keywords**: Include relevant search terms for SEO
- **Link to Details**: Use links in answers for more comprehensive information

### Design
- **Readable Typography**: Minimum 15px for answers, 16px for questions
- **Sufficient Contrast**: Ensure text is easily readable
- **Clear Hierarchy**: Make questions stand out from answers
- **Consistent Spacing**: Maintain uniform padding and gaps
- **Mobile First**: Test on small screens first

### Organization
- **Group by Topic**: If you have many FAQs, create multiple sections
- **Limit Items**: 5-10 FAQs per section is ideal (max 20)
- **Logical Order**: Most important/common questions first
- **Clear Categories**: Use section headings to organize topics

### SEO
- **Enable Schema**: Always enable FAQ structured data
- **Use Keywords**: Include relevant search terms in questions
- **Natural Language**: Write questions as customers would ask them
- **Complete Answers**: Provide thorough answers for better ranking

## 🔧 Technical Details

### Performance
- Vanilla JavaScript (no dependencies)
- Minimal CSS for fast rendering
- Smooth CSS transitions
- No layout shifts
- Optimized for Core Web Vitals

### Accessibility
- Semantic HTML with proper headings
- ARIA attributes (aria-expanded)
- Keyboard navigation support
- Screen reader friendly
- Focus states for keyboard users
- Button elements for clickable areas

### SEO
- Schema.org FAQPage markup
- Proper heading hierarchy (h2, h3)
- Semantic HTML structure
- No hidden content from search engines
- Rich snippets eligible

### Browser Support
- All modern browsers
- IE11+ (with graceful degradation)
- Mobile browsers (iOS Safari, Chrome)
- Progressive enhancement approach

## 📝 Installation

### Step 1: Add to Theme
1. Copy `faq-accordion.liquid` to your theme's `sections/` folder
2. Or create a symlink if using a development workflow

### Step 2: Add to Page
1. Go to **Online Store** > **Themes** > **Customize**
2. Navigate to the page where you want FAQs
3. Click **Add section**
4. Select **FAQ Accordion**

### Step 3: Add FAQ Items
1. In the section settings, click **Add block**
2. Select **FAQ Item**
3. Fill in:
   - Question text
   - Answer (with formatting if needed)
4. Repeat to add more FAQs (up to 20)
5. Drag to reorder items

### Step 4: Customize Design
1. Adjust behavior (open first, close others)
2. Customize colors and typography
3. Choose icon style
4. Set spacing and layout
5. Preview and save

## 🎨 Design Examples

### Classic Style
- Plus/Minus icons
- White background items
- Subtle gray borders
- Light hover effect
- Center-aligned heading

### Modern Minimal
- Chevron icons
- Borderless items
- Subtle dividers
- Strong hover effect
- Left-aligned heading

### Bold & Colorful
- Arrow icons
- Colored backgrounds
- Thick borders
- Brand color accents
- Custom typography

## 🚀 Pro Tips

1. **Question Format**: Start questions with "How", "What", "When", "Where", or "Why"
2. **Answer Length**: Keep answers under 100 words for scannability
3. **Link Strategy**: Link to detailed pages for complex topics
4. **Voice Search**: Write questions as people speak them
5. **Analytics**: Track which FAQs get clicked most to prioritize content
6. **A/B Testing**: Test different question orders to optimize engagement
7. **Cross-Linking**: Link between related FAQs in answers
8. **Video Answers**: Embed video links for complex explanations
9. **Update Frequency**: Review and update FAQs quarterly
10. **Customer Feedback**: Add FAQs based on actual support questions

## 🔄 Updates & Maintenance

### Regular Updates
- Add new FAQs based on customer questions
- Update answers when policies change
- Remove outdated information
- Optimize question wording for clarity
- Test all links in answers

### Quality Control
- Check for typos and grammar
- Ensure answers are accurate
- Verify links work correctly
- Test on multiple devices
- Monitor search console for FAQ rich results

## 🆘 Troubleshooting

### Items Won't Expand
**Solution**: Check that JavaScript is enabled and no console errors exist

### Animation is Jerky
**Solution**: Reduce max-height in CSS or simplify answer content

### Icons Not Showing
**Solution**: Verify icon style is selected in settings

### Schema Errors in Search Console
**Solution**: Ensure answers have proper text content (not just images)

### Mobile Layout Issues
**Solution**: Reduce padding and font sizes for mobile

### Items Stay Open
**Solution**: Enable "Close Other Items When Opening One" setting

## 📊 Conversion Impact

FAQs can significantly improve user experience and conversions:
- **Reduce Support**: Can decrease support tickets by 30-50%
- **Increase Conversions**: Answering objections can boost sales by 20%
- **Improve SEO**: FAQ schema can increase organic traffic by 15-30%
- **Build Trust**: Transparency increases customer confidence
- **Reduce Bounce**: Keeping users engaged longer improves metrics

## 🔗 Related Sections

- **Testimonials**: Combine with social proof for maximum trust
- **Trust Badges**: Pair with FAQs to address credibility concerns
- **Featured Products**: Link to products in FAQ answers
- **Hero Banner**: Use FAQ insights to improve hero messaging

## 📚 Additional Resources

- [Shopify Section Documentation](https://shopify.dev/docs/themes/architecture/sections)
- [Schema.org FAQ Documentation](https://schema.org/FAQPage)
- [Google Rich Results FAQ](https://developers.google.com/search/docs/appearance/structured-data/faqpage)
- [Accessibility Best Practices](https://www.w3.org/WAI/ARIA/apg/patterns/accordion/)

## 🎓 FAQ Writing Tips

### Good Question Examples
✅ "How long does shipping take?"
✅ "What is your return policy?"
✅ "Do you ship internationally?"
✅ "What payment methods do you accept?"

### Bad Question Examples
❌ "Shipping" (too vague)
❌ "Tell me about returns" (not a question)
❌ "Why is your product the best?" (leading)
❌ "How do I do everything?" (too broad)

### Good Answer Examples
✅ Clear, concise, and complete
✅ Includes specific details (timeframes, costs)
✅ Links to more information if needed
✅ Addresses the question directly

### Bad Answer Examples
❌ Too long (over 200 words)
❌ Vague or incomplete
❌ Doesn't answer the question
❌ Too many links (distracting)

---

**Need Help?** This section is fully customizable through the Shopify theme editor. No coding required!
