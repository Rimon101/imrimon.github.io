# 🌟 Customizable Portfolio Website

A modern, fully responsive, and highly customizable portfolio website built with HTML, CSS, and JavaScript.

## ✨ Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations** - Eye-catching transitions and scroll animations
- **Project Filtering** - Showcase your work with category filters
- **Typing Animation** - Dynamic hero section with typing effect
- **Contact Form** - Ready-to-use contact form
- **Easy Customization** - All customizable options are clearly documented
- **Modern UI** - Clean and professional design with gradient accents
- **Performance Optimized** - Fast loading and smooth scrolling

## 🎨 Customization Guide

### 1. Colors

Edit the CSS variables in `styles.css` (lines 8-22):

```css
:root {
    /* Primary Colors */
    --primary-color: #6366f1;      /* Main brand color */
    --primary-dark: #4f46e5;       /* Darker shade */
    --primary-light: #818cf8;      /* Lighter shade */
    
    /* Secondary Colors */
    --secondary-color: #ec4899;    /* Accent color */
    --secondary-dark: #db2777;     /* Darker shade */
    --secondary-light: #f472b6;    /* Lighter shade */
}
```

### 2. Personal Information

Update the following in `index.html`:

#### Hero Section (lines 26-48)
- Change "Your Name" to your actual name
- Update typing animation texts in `script.js` (lines 6-11)
- Add your social media links (lines 41-46)

#### About Section (lines 54-79)
- Replace placeholder image with your photo
- Update the about text and statistics
- Modify stats numbers (data-count attributes)

#### Contact Section (lines 240-287)
- Update email address
- Add phone number
- Add location

### 3. Skills

Edit the skills in `index.html` (lines 84-131):

- Add/remove skill cards
- Change skill icons (using Font Awesome)
- Update skill percentages (data-progress attribute)

### 4. Projects

Customize projects in `index.html` (lines 143-235):

- Replace placeholder images
- Update project titles and descriptions
- Add project links (demo and GitHub)
- Change project tags
- Add/remove projects as needed

### 5. Typing Animation

Edit the typing texts in `script.js` (lines 6-11):

```javascript
const typingTexts = [
    "Web Developer",
    "UI/UX Designer",
    "Problem Solver",
    "Creative Thinker"
];
```

### 6. Fonts

Change fonts in `styles.css` (lines 24-27):

```css
:root {
    --font-primary: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    --font-heading: 'Segoe UI', Arial, sans-serif;
    --font-mono: 'Courier New', monospace;
}
```

To use Google Fonts, add this to the `<head>` in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
```

Then update the CSS variable:

```css
--font-primary: 'Poppins', sans-serif;
```

### 7. Spacing and Sizing

Adjust spacing in `styles.css` (lines 29-33):

```css
:root {
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 4rem;
    --spacing-xl: 6rem;
}
```

### 8. Contact Form

The form currently shows an alert on submission. To connect it to a backend:

#### Option 1: FormSubmit (No coding required)
Replace the form action in `index.html`:

```html
<form class="contact-form" action="https://formsubmit.co/your-email@example.com" method="POST">
```

#### Option 2: Custom Backend
Uncomment and modify the fetch code in `script.js` (lines 179-193).

## 📁 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and CSS variables
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🚀 Getting Started

1. **Download/Clone** this repository
2. **Customize** the content (see guide above)
3. **Replace** placeholder images with your own
4. **Test** by opening `index.html` in a browser
5. **Deploy** to your hosting service

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `username.github.io/repository-name`

### Netlify (Free)
1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly

### Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project folder
3. Follow the prompts

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🛠️ Optional Features

The `script.js` file includes commented code for optional features:

1. **Particle Background** (lines 196-223)
2. **Custom Cursor** (lines 229-253)
3. **Dark Mode Toggle** (lines 259-283)

Uncomment these sections to enable them.

## 💡 Tips for Customization

1. **Keep backups** before making major changes
2. **Test on mobile devices** after customization
3. **Use high-quality images** for best results
4. **Optimize images** to improve loading speed (use tools like TinyPNG)
5. **Update meta tags** in `index.html` for SEO
6. **Add a favicon** for a professional touch

## 📸 Adding Your Own Images

Replace these placeholder images:

1. **Profile Picture**: `about-image` (400x400px recommended)
2. **Project Images**: `.project-image` images (800x600px recommended)

## 🎨 Color Scheme Ideas

Here are some popular color combinations you can use:

### Professional Blue
```css
--primary-color: #2563eb;
--secondary-color: #7c3aed;
```

### Modern Green
```css
--primary-color: #10b981;
--secondary-color: #06b6d4;
```

### Vibrant Orange
```css
--primary-color: #f97316;
--secondary-color: #ec4899;
```

### Classic Purple
```css
--primary-color: #8b5cf6;
--secondary-color: #6366f1;
```

## 📝 SEO Optimization

Add these meta tags to `index.html` `<head>`:

```html
<meta name="description" content="Your name - Web Developer Portfolio">
<meta name="keywords" content="web developer, portfolio, your skills">
<meta name="author" content="Your Name">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your portfolio description">
<meta property="og:image" content="link-to-your-image.jpg">
```

## 🐛 Troubleshooting

**Issue**: Animations not working
- **Solution**: Make sure JavaScript is enabled in your browser

**Issue**: Mobile menu not opening
- **Solution**: Check browser console for JavaScript errors

**Issue**: Images not displaying
- **Solution**: Check image paths are correct and files exist

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Support

If you have questions or need help customizing your portfolio:
- Check the comments in the code files
- Refer to this README
- Search online for specific CSS/JavaScript questions

## 🎉 You're All Set!

Your portfolio is ready to customize and deploy. Make it your own and showcase your amazing work!

---

**Happy Coding!** 🚀
