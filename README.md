# Personal Portfolio Website

A modern, responsive portfolio website for showcasing data science and data engineering projects.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **CV Download**: Direct download functionality for your resume
- **Project Showcase**: Dedicated section to highlight your best work
- **Skills Display**: Visual representation of your technical skills
- **Contact Form**: Interactive contact form for potential employers/collaborators
- **Smooth Scrolling**: Enhanced user experience with smooth navigation

## 📁 File Structure

```
/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── assets/             # Assets folder
│   └── Giacomo_CV.pdf  # Your CV file (add this)
└── README.md           # This file
```

## 🛠️ Setup Instructions

### 1. Add Your CV
- Place your CV file in the `assets/` folder
- Name it `Giacomo_CV.pdf` or update the filename in `script.js` (line 65)

### 2. Customize Content
Update the following sections in `index.html`:

#### Personal Information
- Change "Giacomo" to your name throughout the file
- Update the hero description
- Modify the about section with your background

#### Contact Information
- Update email address: `your.email@example.com`
- Update LinkedIn profile: `linkedin.com/in/yourprofile`
- Update GitHub profile: `github.com/yourusername`

#### Projects Section
- Replace sample projects with your actual projects
- Update project descriptions, technologies, and links
- Add screenshots to the `assets/` folder and update image sources

#### Skills Section
- Modify the skills based on your expertise
- Add or remove skill categories as needed

### 3. Add Project Images (Optional)
- Create an `images/` folder inside `assets/`
- Add project screenshots/images
- Update the project cards to use real images instead of icons

### 4. Deploy to GitHub Pages

#### Option 1: Direct Upload
1. Create a new repository on GitHub named `yourusername.github.io`
2. Upload all files to the repository
3. Your site will be available at `https://yourusername.github.io`

#### Option 2: Using Git (Recommended)
```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit: Portfolio website"

# Add GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git push -u origin main
```

## 🎨 Customization Options

### Colors
The website uses CSS custom properties. You can easily change the color scheme by modifying the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #1f2937;
    --background-color: #ffffff;
}
```

### Fonts
The website uses Inter font from Google Fonts. You can change it by updating the font import in `index.html` and the font-family in `styles.css`.

### Layout
- The website is built with CSS Grid and Flexbox for easy customization
- All sections are modular and can be reordered or modified independently

## 📱 Mobile Responsiveness

The website is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: Below 768px

## 🔧 Technical Features

- **CSS Grid & Flexbox**: Modern layout techniques
- **Intersection Observer API**: Scroll-based animations
- **Throttled Scroll Events**: Optimized performance
- **Form Validation**: Client-side validation for contact form
- **Local Storage**: Saves user preferences
- **Accessibility**: Semantic HTML and keyboard navigation support

## 📊 Analytics (Optional)

To add Google Analytics:
1. Get your Google Analytics tracking ID
2. Add the following code to the `<head>` section of `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🚀 Performance Tips

1. **Optimize Images**: Compress images before adding them
2. **Minify CSS/JS**: Use tools like UglifyJS for production
3. **Enable Caching**: Configure proper cache headers
4. **Use CDN**: Consider using a CDN for faster loading

## 🐛 Troubleshooting

### CV Download Not Working
- Ensure your CV file is in the `assets/` folder
- Check the filename matches the one in `script.js`
- Verify the file path is correct

### Contact Form Not Sending
- The current form is frontend-only
- To make it functional, integrate with services like:
  - Formspree
  - Netlify Forms
  - EmailJS

### Mobile Menu Not Working
- Check if JavaScript is enabled
- Verify all JS files are loading correctly

## 🔄 Future Enhancements

Consider adding:
- Blog section for technical articles
- Dark mode toggle
- Multi-language support
- Advanced animations with libraries like GSAP
- Integration with CMS for easy content updates

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back with the community!

---

**Good luck with your portfolio website! 🚀**
