# Baby Shower Website - Italian Alps Skiing Theme

A beautiful, custom baby shower invitation website featuring an Italian Alps skiing theme with the iconic Civetta owl mascot.

## Features

- **Italian Alps Theme**: Dramatic Dolomite mountain backdrop with realistic peaks
- **Civetta Owl Logo**: Classic vintage ski poster style owl on skis with poles
- **Script Typography**: Elegant Dancing Script font inspired by Val di Fassa branding
- **Accurate Olympic Rings**: Properly interlocking Olympic rings
- **RSVP Form**: Full-featured RSVP form with backend integration
- **Fully Responsive**: Works beautifully on desktop, tablet, and mobile devices

## Setting Up the RSVP Form

The RSVP form is ready to collect responses! You have several options:

### Option 1: Formspree (Recommended - Free & Easy)

1. Go to [https://formspree.io](https://formspree.io)
2. Sign up for a free account
3. Create a new form
4. Copy your form's endpoint URL (looks like `https://formspree.io/f/YOUR_FORM_ID`)
5. In `index.html`, replace `YOUR_FORM_ID` in line 208:
   ```html
   <form id="rsvp-form" class="rsvp-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
6. All RSVPs will be emailed to you automatically!
7. View all responses in your Formspree dashboard

### Option 2: Google Forms (Alternative)

1. Create a Google Form with the same fields
2. Get the form's embed code or action URL
3. Replace the form action URL in `index.html`

### Option 3: Custom Backend

If you want to store RSVPs in a database:
- Connect to Google Sheets using Google Apps Script
- Use a serverless function (Netlify Functions, Vercel, AWS Lambda)
- Set up your own backend API

## Viewing the Website

### Locally on Your Computer

1. Download both `index.html` and `style.css` to the same folder
2. Double-click `index.html` to open in your browser
3. Or drag `index.html` into any web browser

### On the Web (GitHub Pages)

1. Make sure files are pushed to your GitHub repository
2. Go to Settings > Pages
3. Select the branch: `claude/baby-shower-planning-g91HQ`
4. Select folder: `/ (root)`
5. Click Save
6. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Customization

### Colors
Edit the CSS variables at the top of `style.css`:
```css
:root {
    --alpine-cream: #F5F1E8;
    --warm-stone: #D4C4B0;
    --mountain-brown: #8B7355;
    /* ... etc */
}
```

### Event Details
Update the event information in `index.html` around lines 102-130

## Files

- `index.html` - Main website structure
- `style.css` - All styling and animations
- `README.md` - This file

## Design Credits

- Civetta Owl: Inspired by classic Italian Alps ski area logos
- Typography: Dancing Script (Google Fonts) for that Val di Fassa script vibe
- Mountains: Stylized Dolomite peaks (Tre Cime, Marmolada, Civetta)
- Olympic Rings: Official Olympic colors with proper interlocking design

## Browser Support

Works in all modern browsers:
- Chrome/Edge (recommended)
- Safari
- Firefox
- Mobile browsers (iOS Safari, Chrome Mobile)

---

Made with ❄️ for Sam & Gigi's Future Olympian
