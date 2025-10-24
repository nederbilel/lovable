# Louati neder - Personal Landing Page

A clean, modern, single-section landing page built with pure HTML and CSS. This minimalist portfolio landing page showcases a centered hero layout with soft pastel colors and smooth animations.

## 🎯 Project Overview

This project contains a standalone HTML file (`landing.html`) that serves as a personal landing page for Louati neder, an aspiring frontend developer. The page features a modern, responsive design with no dependencies - just pure HTML and CSS.

## ✨ Features

- **Single Page Design**: All content in one focused section
- **Fully Responsive**: Adapts beautifully to all screen sizes (mobile, tablet, desktop)
- **Modern Typography**: Uses Inter font family from Google Fonts
- **Smooth Animations**: Fade-in animation on page load
- **Interactive Button**: Hover effects with smooth transitions and shadows
- **Soft Pastel Colors**: Gradient background (purple to blue)
- **Zero Dependencies**: No frameworks or libraries required

## 🎨 Design Elements

### Color Palette
- Background: Linear gradient from `#fef5ff` (light purple) to `#f0f9ff` (light blue)
- Primary Text: `#1a1a2e` (dark navy)
- Secondary Text: `#64748b` (slate gray)
- Button Gradient: `#a855f7` (purple) to `#ec4899` (pink)

### Typography
- Font Family: Inter (with fallbacks to system fonts)
- Heading: 3rem to 6rem (responsive)
- Subtitle: 1.25rem to 1.75rem (responsive)
- Button: 1.125rem

### Spacing & Layout
- Centered content (both horizontally and vertically)
- Max-width container: 800px
- Responsive padding and margins
- Button shadow: `0 10px 30px -10px rgba(168, 85, 247, 0.4)`

## 📋 Content Structure

```
┌─────────────────────────────┐
│                             │
│      Louati neder          │  ← Name (H1)
│                             │
│ Aspiring Frontend Developer │  ← Subtitle (P)
│                             │
│   [View My Projects]        │  ← CTA Button
│                             │
└─────────────────────────────┘
```

## 🚀 How to Use

### Option 1: Direct File Opening
1. Download the `landing.html` file
2. Double-click to open in your default browser
3. That's it! No server or setup required

### Option 2: Local Development Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Then open http://localhost:8000/landing.html
```

### Option 3: Deploy to Production
Upload `landing.html` to any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any traditional web host

## 🛠️ Customization Guide

### Change Name and Subtitle
Edit the HTML content within the `<div class="container">`:
```html
<h1>Your Name</h1>
<p>Your Professional Title</p>
```

### Modify Colors
Update the CSS variables in the `<style>` section:
```css
/* Background gradient */
background: linear-gradient(135deg, #yourColor1 0%, #yourColor2 100%);

/* Button gradient */
background: linear-gradient(135deg, #yourColor3 0%, #yourColor4 100%);
```

### Adjust Button Link
Change the `href` attribute:
```html
<a href="#your-section" class="button">Your Button Text</a>
```

### Change Font
Replace the Google Fonts import:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;500;600;700&display=swap" rel="stylesheet">
```

## 📱 Responsive Breakpoints

- **Desktop**: Full size (6rem heading)
- **Tablet**: Medium size (responsive via clamp)
- **Mobile** (< 640px): Optimized spacing and font sizes

## 🌐 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Information

- **File**: `landing.html`
- **Size**: ~2.3 KB
- **Type**: Single HTML file with embedded CSS
- **Dependencies**: Google Fonts (Inter) - loaded from CDN

## 🎓 Technologies Used

- HTML5
- CSS3 (Flexbox, Animations, Gradients)
- Google Fonts API

## 📝 SEO Optimization

The page includes:
- Semantic HTML structure
- Meta description
- Proper heading hierarchy (H1)
- Viewport meta tag for mobile
- UTF-8 character encoding

## 💡 Future Enhancements Ideas

- Add projects section when clicking the button
- Include social media links
- Add contact form
- Implement dark mode toggle
- Add more animations (scroll effects)

## 📞 Contact

**Louati neder**  
Aspiring Frontend Developer

---

Made with ❤️ using pure HTML & CSS
