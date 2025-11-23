# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript to showcase your projects, experience, education, skills, and certifications.

## Features

- ✅ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Dark/Light Mode** - Toggle between themes with persistent preference
- ✅ **Smooth Animations** - Scroll-triggered animations and transitions
- ✅ **Project Filtering** - Filter projects by category (Web, Mobile, Full Stack)
- ✅ **Interactive Timeline** - Visual timeline for work experience
- ✅ **Skills Visualization** - Animated progress bars for skills
- ✅ **Contact Form** - Functional contact form with email integration
- ✅ **Smooth Scrolling** - Navigation with smooth scroll behavior
- ✅ **Mobile Menu** - Hamburger menu for mobile devices
- ✅ **Back to Top Button** - Easy navigation back to top

## Sections

1. **Home/Introduction** - Personal introduction with call-to-action buttons
2. **About** - About me section with statistics
3. **Experience** - Work experience displayed in timeline format
4. **Education** - Educational background (High School, Graduation, etc.)
5. **Projects** - Portfolio projects with GitHub and demo links
6. **Skills** - Technical skills with progress bars and tags
7. **Certifications** - Professional certifications
8. **Contact** - Contact information and form

## Setup Instructions

### 1. Clone or Download

Download all files to your local machine:
- `index.html`
- `styles.css`
- `script.js`

### 2. Customize Content

#### Update Personal Information

**In `index.html`:**

1. **Meta Tags** (Line 7-10):
   ```html
   <meta name="description" content="Your description">
   <meta name="author" content="Your Name">
   <title>Your Name - Portfolio</title>
   ```

2. **Home Section** (Line 45-50):
   - Update name, title, and description
   - Replace profile image placeholder URL with your image

3. **About Section** (Line 80-95):
   - Update about me text
   - Modify statistics (projects, experience, technologies)

4. **Experience Section** (Line 100-160):
   - Update job titles, companies, dates, and descriptions
   - Add or remove timeline items as needed

5. **Education Section** (Line 165-200):
   - Update education details
   - Add or remove education cards

6. **Projects Section** (Line 205-320):
   - Update project titles, descriptions, and links
   - Replace placeholder images with project screenshots
   - Update GitHub and demo links
   - Modify project tags (technologies used)

7. **Skills Section** (Line 325-400):
   - Update skill names and percentages
   - Add or remove skills
   - Modify skill tags

8. **Certifications Section** (Line 405-460):
   - Update certification details
   - Add certificate links
   - Add or remove certification cards

9. **Contact Section** (Line 465-520):
   - Update email address
   - Update LinkedIn profile URL
   - Update GitHub username
   - Add other social media links if needed

#### Update Resume

1. Create a PDF version of your resume
2. Save it as `resume.pdf` in the same directory
3. The download button will automatically link to it

#### Update Images

1. **Profile Image**: Replace the placeholder URL in the home section with your professional photo
2. **Project Images**: Replace placeholder URLs with actual project screenshots
   - Recommended size: 400x250px
   - Format: JPG or PNG

### 3. Customize Colors (Optional)

**In `styles.css`:**

Modify CSS variables in the `:root` selector (Line 3-25) to match your brand colors:

```css
:root {
    --primary-color: #6366f1;    /* Your primary color */
    --secondary-color: #8b5cf6;  /* Your secondary color */
    --accent-color: #ec4899;     /* Your accent color */
    /* ... other colors */
}
```

### 4. Test Locally

1. Open `index.html` in your web browser
2. Test all sections and functionality
3. Test on different screen sizes (mobile, tablet, desktop)
4. Test dark/light mode toggle
5. Test contact form

### 5. Deploy

#### Option 1: GitHub Pages (Free)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Option 2: Netlify (Free)

1. Go to [Netlify](https://www.netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly

#### Option 3: Vercel (Free)

1. Go to [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

#### Option 4: Traditional Web Hosting

1. Upload all files via FTP to your web hosting
2. Ensure `index.html` is in the root directory

## Customization Tips

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add navigation link in the navbar
4. Update JavaScript if needed for animations

### Modifying Animations

- Animation timings are in `styles.css` (transition variables)
- Scroll animations are handled in `script.js` (Intersection Observer)

### Adding More Projects

1. Copy an existing `.project-card` element
2. Update the content
3. Set the `data-category` attribute (web, mobile, fullstack)
4. Add filter button if creating a new category

### Changing Fonts

1. Add Google Fonts link in `<head>` of `index.html`:
   ```html
   <link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;600;700&display=swap" rel="stylesheet">
   ```
2. Update `font-family` in `styles.css` body selector

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Compress images before uploading
   - Use tools like [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app)
   
2. **Minify Files**: Minify CSS and JavaScript for production
   - Use tools like [Minify](https://www.minifier.org)

3. **Lazy Loading**: Images are already set up for lazy loading

## Troubleshooting

### Images Not Loading
- Check image file paths
- Ensure images are in the correct directory
- Use relative paths or absolute URLs

### Dark Mode Not Working
- Clear browser cache
- Check browser console for JavaScript errors

### Contact Form Not Working
- Update email address in the form handler
- Consider using a form service like Formspree or Netlify Forms

### Mobile Menu Not Working
- Ensure JavaScript is enabled
- Check browser console for errors

## License

This project is open source and available for personal and commercial use.

## Credits

- Icons: [Font Awesome](https://fontawesome.com)
- Design: Custom design inspired by modern portfolio trends

## Support

If you encounter any issues or have questions, please:
1. Check the troubleshooting section
2. Review the code comments
3. Test in different browsers

---

**Good luck with your job applications! 🚀**



