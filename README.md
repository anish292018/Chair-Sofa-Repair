# Chair & Sofa Repair Website

A professional, mobile-friendly multi-page website for a local Chair and Sofa Repair & Upholstery Service business.

## Features

- Responsive design that works on mobile, tablet, and desktop devices
- Clean and modern layout with warm, inviting colors
- Multiple pages: Home, Services, About Us, and Contact
- Contact form with validation
- Google Maps integration
- Testimonial slider
- WhatsApp integration for easy booking

## Pages

1. **Home (index.html)**
   - Hero section with headline, description, and call-to-action
   - Services preview with images and descriptions
   - Customer testimonials slider

2. **Services (services.html)**
   - Detailed service cards for Chair Repair, Sofa Repair, Upholstery Replacement, and Custom Cushion Making
   - Each card includes an image, description, features, and price range

3. **About Us (about.html)**
   - Company story and history
   - Years of experience highlights
   - "Why Choose Us" section with icons
   - Team member profiles
   - Our process section

4. **Contact (contact.html)**
   - Contact form with validation
   - Direct contact details (phone, email, WhatsApp)
   - Business hours
   - Google Map showing the shop location

## Customization

### Replacing Images

All image placeholders are located in the `assets/images/` directory. Replace them with your actual images while keeping the same filenames:

- `hero.jpg` - Hero section background (recommended size: 1200x600px)
- `chair-repair.jpg` - Chair repair service image (recommended size: 600x400px)
- `sofa-repair.jpg` - Sofa repair service image (recommended size: 600x400px)
- `upholstery.jpg` - Upholstery service image (recommended size: 600x400px)
- `cushions.jpg` - Custom cushion making service image (recommended size: 600x400px)

### Updating Content

Look for comments in the HTML files that indicate where to replace content:

```html
<!-- REPLACE WITH YOUR LOGO OR TEXT -->
<!-- REPLACE WITH YOUR HEADLINE -->
<!-- REPLACE WITH YOUR DESCRIPTION -->
<!-- REPLACE WITH YOUR WHATSAPP NUMBER -->
<!-- REPLACE WITH YOUR CONTACT INFORMATION -->
<!-- REPLACE WITH YOUR BUSINESS NAME AND YEAR -->
<!-- REPLACE WITH YOUR PRICE RANGE -->
<!-- REPLACE WITH YOUR SOCIAL MEDIA LINKS -->
<!-- REPLACE WITH YOUR GOOGLE MAPS EMBED CODE -->
```

### Changing Colors

The color scheme can be easily modified by changing the CSS variables in the `css/style.css` file:

```css
:root {
    /* Colors */
    --primary-color: #8B5A2B; /* Brown */
    --secondary-color: #D2B48C; /* Tan/Beige */
    --accent-color: #A0522D; /* Sienna */
    --light-color: #F5F5DC; /* Beige */
    --dark-color: #3C2415; /* Dark Brown */
    --grey-color: #E5E5E5; /* Light Grey */
    --text-color: #333333; /* Dark Grey for text */
    --white-color: #FFFFFF;
    --success-color: #4CAF50;
}
```

### Fonts

The website uses Google Fonts:
- Headings: Playfair Display
- Body text: Raleway

To change fonts, update the Google Fonts link in the `<head>` section of each HTML file and update the font variables in the CSS file.

## Technical Information

- Built with HTML5, CSS3, and vanilla JavaScript
- No backend frameworks or dependencies required
- Can be hosted on GitHub Pages without any changes
- Uses Font Awesome for icons
- Fully responsive design with mobile-first approach

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload all files and folders to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Click Save
6. Your website will be published at `https://yourusername.github.io/repository-name/`

## Local Development

To run the website locally, simply open the `index.html` file in your web browser.

## License

This website template is free to use for your business. Please replace all placeholder content with your actual business information before publishing.

---

© 2023 Chair & Sofa Repair. All Rights Reserved.