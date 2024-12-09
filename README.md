# Casa Legal Hub Website

A modern, responsive website for Casa Legal Hub, a law firm specializing in mediation and legal consultancy services in Rwanda.

## Features

- Responsive design that works on all devices
- Modern and professional layout
- Interactive navigation with smooth scrolling
- Contact form for client inquiries
- Sections for services, team members, and contact information
- Animated section transitions
- Mobile-friendly navigation menu

## Setup Instructions

1. Clone or download this repository to your local machine.

2. Required Images:
   - Place your logo image in the `images` folder as `logo.png`
   - Add a hero background image in the `images` folder as `hero-bg.jpg`
   - Add team member photos in the `images` folder (e.g., `joseph-bizimana.jpg`)

3. Customization:
   - Colors can be modified in the `styles.css` file under the `:root` section
   - Content can be updated in the `index.html` file
   - Contact form submission can be configured in the `script.js` file

## File Structure

```
casa-legal-hub/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── images/            # Image assets
│   ├── logo.png
│   ├── hero-bg.jpg
│   └── joseph-bizimana.jpg
└── README.md          # This file
```

## Customization Guide

### Colors
To change the website's color scheme, modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #3498db;
    --text-color: #333;
    --light-gray: #f5f5f5;
    --white: #ffffff;
}
```

### Images
1. Logo: Replace `images/logo.png` with your company logo
2. Hero Background: Replace `images/hero-bg.jpg` with your preferred hero image
3. Team Photos: Add team member photos to the `images` folder

### Contact Form
The contact form currently shows a success message and logs form data to the console. To make it functional:

1. Create a server endpoint to handle form submissions
2. Update the form submission code in `script.js`
3. Add proper error handling and validation

## Browser Support

The website is compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)
- Opera (latest)

## Future Enhancements

Potential improvements that could be added:
- Multi-language support
- Blog section
- Client testimonials
- Online consultation booking
- More detailed team profiles

## Contact

For any questions or support, please contact:
- Email: casalegalhub@gmail.com
- Phone: (+250) 788625631 / 728625631
