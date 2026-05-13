# Result Driving School Website

A professional, responsive website for Result Driving School with black/red/yellow color scheme.

Inspired by professional driving school websites with modern design and user-friendly navigation.

## Pages Included

- **Home** (index.html) - Hero section, features, services preview
- **About** (about.html) - Company story, mission, why choose us
- **Services** (services.html) - Detailed service offerings including ADI instructor training and pricing packages
- **Testimonials** (testimonials.html) - Student reviews and statistics
- **Contact** (contact.html) - Contact form and business information
- **Booking** (booking.html) - Lesson booking form (placeholder for future integration)

## Customization

### 1. Update Business Information

Replace placeholders in all HTML files:
- `<phone number>` - Your phone number
- `<email>` - Your email address
- `<address>` - Your business address

### 2. Customize Content

The site is already branded as "Result Driving School" but you can:
- Update service descriptions
- Modify pricing
- Add your own testimonials

### 3. Update Pricing

Edit `services.html` to update:
- Individual lesson prices
- Package prices
- Service descriptions

### 4. Add Real Testimonials

Edit `testimonials.html` to add your actual student reviews.

### 5. Customize Colors (Optional)

Edit `styles.css` at the top to change colors:
```css
:root {
    --primary-black: #1a1a1a;
    --secondary-red: #dc143c;
    --accent-yellow: #ffd700;
}
```

## Deploying to GitHub Pages (Free Hosting)

### Step 1: Create GitHub Account
1. Go to https://github.com
2. Sign up for a free account

### Step 2: Create Repository
1. Click "New repository"
2. Name it: `your-driving-school` (or any name)
3. Make it Public
4. Don't initialize with README

### Step 3: Upload Files
1. Click "uploading an existing file"
2. Drag all files from this folder:
   - index.html
   - about.html
   - services.html
   - testimonials.html
   - contact.html
   - booking.html
   - styles.css
   - script.js
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Under "Source", select "main" branch
4. Click Save
5. Your site will be live at: `https://yourusername.github.io/your-driving-school`

### Step 5: Custom Domain (Optional)
1. Buy a domain (e.g., yourdrivingschool.com)
2. In GitHub Pages settings, add your custom domain
3. Update DNS settings at your domain registrar

## Adding Booking Functionality Later

The booking form currently shows an alert. To make it functional:

### Option 1: Google Forms
1. Create a Google Form
2. Get the embed code
3. Replace the form in `booking.html`

### Option 2: Formspree (Free tier: 50 submissions/month)
1. Sign up at https://formspree.io
2. Update form action: `<form action="https://formspree.io/f/YOUR_ID" method="POST">`

### Option 3: EmailJS (Free tier: 200 emails/month)
1. Sign up at https://www.emailjs.com
2. Follow their JavaScript integration guide
3. Update `script.js` with EmailJS code

### Option 4: Calendly
1. Sign up at https://calendly.com
2. Get embed code
3. Replace booking form with Calendly widget

## Adding to Google My Business

1. Go to https://business.google.com
2. Create/claim your business profile
3. Verify your business
4. Add your website URL: `https://yourusername.github.io/your-driving-school`
5. Complete your profile with photos, hours, services

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Need Help?

- GitHub Pages Documentation: https://pages.github.com
- Formspree Documentation: https://help.formspree.io
- Google Business Profile Help: https://support.google.com/business

## License

Free to use and modify for your driving school business.
