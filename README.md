# Bites SMS Marketing Email Template

A responsive HTML email template based on the Mailchimp SMS Marketing campaign design.

## 📋 Features

- **Fully Responsive**: Adapts to mobile, tablet, and desktop screens
- **Email Client Compatible**: Works across major email clients (Gmail, Outlook, Apple Mail, etc.)
- **Inline CSS**: All styles are inlined for maximum compatibility
- **Table-based Layout**: Uses traditional table structure for email reliability
- **MSO Conditional Comments**: Special handling for Microsoft Outlook

## 🎨 Design Elements

- Hero section with image
- Clear call-to-action buttons (yellow/gold color)
- Feature sections with images and descriptions
- Footer with social media links and app badges
- Disclaimer section
- Mobile-optimized typography and spacing

## 📱 Responsive Breakpoints

- **Desktop**: 600px width (default)
- **Tablet**: 600px and below
- **Mobile**: 480px and below

## 🚀 Usage

### Testing the Template

1. Open `index.html` in a web browser to preview
2. For email testing, use services like:
   - [Litmus](https://litmus.com/)
   - [Email on Acid](https://www.emailonacid.com/)
   - [Mailchimp's Preview Tool](https://mailchimp.com/)

### Customization

#### Replace Placeholder Images

The template uses placeholder images. Replace these URLs with your actual images:

```html
<!-- Logo -->
<img src="YOUR_LOGO_URL" alt="Mailchimp" />

<!-- Hero Image -->
<img src="YOUR_HERO_IMAGE_URL" alt="SMS Marketing" />

<!-- Feature Images -->
<img src="YOUR_FEATURE_IMAGE_URL" alt="Feature description" />
```

#### Update Colors

Main colors used in the template:

- **Primary Background**: `#2C3E50` (Dark blue-gray)
- **CTA Button**: `#FFE01B` (Yellow/Gold)
- **Light Background**: `#F7F7F7` (Light gray)
- **Text**: `#000000` (Black) and `#333333` (Dark gray)

#### Modify Text Content

Update the text content in the HTML to match your campaign:

- Headlines
- Body copy
- CTA button text
- Feature descriptions
- Footer information

### Sending the Email

#### Option 1: Using Mailchimp

1. Log into your Mailchimp account
2. Create a new campaign
3. Choose "Code your own" template
4. Paste the HTML code
5. Test and send

#### Option 2: Using Other Email Service Providers

Most ESPs support custom HTML templates:

- **SendGrid**: Use their HTML editor
- **Campaign Monitor**: Import custom HTML
- **Constant Contact**: Use custom code option

## 🔧 Technical Notes

### Email Client Compatibility

✅ **Supported**:

- Gmail (Desktop & Mobile)
- Apple Mail (iOS & macOS)
- Outlook 2016+ (Windows & Mac)
- Yahoo Mail
- AOL Mail
- Samsung Mail
- Outlook.com

⚠️ **Limited Support**:

- Outlook 2007-2013 (uses Word rendering engine)
- Some older email clients may not support all styles

### Best Practices Implemented

1. **Inline CSS**: All styles are inlined for maximum compatibility
2. **Table-based Layout**: More reliable than div-based layouts in emails
3. **Alt Text**: All images have descriptive alt text
4. **Mobile-First**: Responsive design prioritizes mobile experience
5. **Safe Fonts**: Uses web-safe font stack (Arial, Georgia)
6. **Max Width**: 600px max width for optimal email display
7. **Background Colors**: Fallback colors for unsupported clients

### File Structure

```
06-Email-Template/
├── index.html          # Main email template
└── README.md          # This file
```

## 📝 Customization Checklist

Before sending your email, make sure to:

- [ ] Replace all placeholder images with actual images
- [ ] Update logo with your brand logo
- [ ] Customize headline and body text
- [ ] Update CTA button links (href="#")
- [ ] Add tracking parameters to links (UTM codes)
- [ ] Update footer information (address, links)
- [ ] Add real social media links
- [ ] Update app store badge links
- [ ] Test in multiple email clients
- [ ] Test on mobile devices
- [ ] Verify all links work correctly
- [ ] Check spelling and grammar
- [ ] Add unsubscribe link (required by law)

## 🎯 Image Specifications

For best results, use these image dimensions:

- **Logo**: 150x40px (PNG with transparent background)
- **Hero Image**: 560x280px (JPG or PNG)
- **Feature Images**: 200x200px (JPG or PNG)
- **Footer Logo**: 120x40px (PNG with transparent background)
- **Social Icons**: 24x24px (PNG)
- **App Badges**: 120x40px (PNG)

## 📧 Email Marketing Tips

1. **Subject Line**: Keep it under 50 characters
2. **Preview Text**: Write compelling preview text (first 100 characters)
3. **CTA**: Use clear, action-oriented button text
4. **Images**: Optimize images for fast loading (under 1MB total)
5. **Testing**: Always send test emails before the main campaign
6. **Segmentation**: Target specific audience segments
7. **Timing**: Send at optimal times for your audience
8. **A/B Testing**: Test different versions to improve performance

## 🔗 Resources

- [Mailchimp Email Design Guide](https://mailchimp.com/help/email-design-guide/)
- [Can I Email](https://www.caniemail.com/) - CSS support in email clients
- [Really Good Emails](https://reallygoodemails.com/) - Email design inspiration
- [HTML Email](https://htmlemail.io/) - Email development resources

## 📄 License

This template is provided as-is for educational and commercial use.

## 🤝 Support

For questions or issues with this template, please refer to:

- Email client documentation
- Your ESP's support resources
- HTML email development communities

---

**Note**: Remember to comply with email marketing laws (CAN-SPAM, GDPR, etc.) by including:

- Physical mailing address
- Unsubscribe link
- Clear sender identification
- Accurate subject lines
