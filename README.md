# 🚀 Ayush Paudel - Personal Portfolio

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Computer Science student and aspiring software engineer.

![Portfolio Preview](preview.png)

## ✨ Features

- **Modern Dark Theme** - Sophisticated design with gold accents
- **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations** - Scroll reveals, typing effects, and micro-interactions
- **Interactive Elements** - Custom cursor, project card tilts, hover effects
- **Performance Optimized** - Vanilla JavaScript, no frameworks, fast loading
- **SEO Ready** - Semantic HTML5 with proper meta tags

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox
- **JavaScript** - Vanilla JS (no dependencies)
- **Fonts** - Google Fonts (Playfair Display + DM Sans)

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
├── script.js           # Interactive functionality
├── assets/             # Images and documents (create this)
│   ├── images/
│   └── documents/
│       └── CV.pdf      # Your CV (add this)
├── .gitignore         # Git ignore rules
├── README.md          # This file
└── LICENSE            # MIT License
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Git (for version control)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using VS Code Live Server extension
   # Right-click index.html → "Open with Live Server"
   ```

3. **View the site**
   - Navigate to `http://localhost:8000` (or the port shown)

## ⚙️ Customization

### 1. Update Personal Information

**In `index.html`:**
- Update name, contact details, and location
- Modify the about me section
- Add/remove projects
- Update experience and education details
- Replace placeholder links with actual URLs

### 2. Customize Colors

**In `style.css` (lines 13-23):**
```css
:root {
    --primary: #E8B86D;        /* Main accent color */
    --secondary: #4A90E2;      /* Secondary accent */
    --accent: #7C5CDB;         /* Tertiary accent */
    /* ... modify other colors as needed */
}
```

### 3. Add Your CV

1. Create an `assets/documents/` folder
2. Add your CV as `CV.pdf`
3. Update the download button in `script.js`:
   ```javascript
   const link = document.createElement('a');
   link.href = 'assets/documents/CV.pdf';
   link.download = 'Ayush_Paudel_CV.pdf';
   link.click();
   ```

### 4. Update Links

Replace all placeholder links (`#`) with actual URLs:
- GitHub profile and repositories
- LinkedIn profile
- Live project demos
- Email address (already set)

### 5. Add Images (Optional)

For project thumbnails or profile picture:
1. Add images to `assets/images/`
2. Update HTML with `<img>` tags
3. Images will lazy-load automatically

## 🌐 Deployment

### Option 1: GitHub Pages (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save and wait 2-3 minutes

3. **Access your site**
   - `https://yourusername.github.io/portfolio`

### Option 2: Netlify

1. **Deploy via Drag & Drop**
   - Visit [netlify.com](https://netlify.com)
   - Drag your project folder to the deploy zone
   - Get instant URL: `https://random-name.netlify.app`

2. **Deploy via Git**
   - Connect your GitHub repository
   - Netlify auto-deploys on every push

### Option 3: Vercel

1. **Install Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

### Option 4: Custom Domain

After deploying to any platform:
1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. Configure DNS settings in your hosting platform
3. Update DNS records to point to your deployment

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## 🎨 Design Philosophy

This portfolio avoids generic "AI slop" aesthetics by:
- Using distinctive typography (Playfair Display + DM Sans)
- Implementing a sophisticated dark theme with gold accents
- Creating unique animations and interactions
- Maintaining professional polish while being memorable

## 🔧 Maintenance

### Adding New Projects

1. Copy a project card in `index.html`
2. Update title, description, and tech stack
3. Add GitHub/demo links

### Updating Skills

1. Find the skills section in `index.html`
2. Add new `<span class="skill-tag">` elements
3. They'll automatically have hover effects

### Adding Experience

1. Copy a timeline item in the experience section
2. Update job title, company, dates, and responsibilities

## 📊 Performance

- **Load Time:** < 2 seconds on 3G
- **No Dependencies:** Pure vanilla JavaScript
- **Optimized:** Throttled scroll events, lazy loading ready
- **Lighthouse Score:** Aim for 95+ across all metrics

## 🐛 Troubleshooting

**Animations not working?**
- Check JavaScript console for errors
- Ensure all three files are in the same directory

**Fonts not loading?**
- Check internet connection (Google Fonts CDN)
- Verify font links in `<head>` tag

**Mobile menu not working?**
- Ensure JavaScript is enabled
- Check browser console for errors

**Form not submitting?**
- The form is frontend-only (demo)
- Integrate with Formspree, Netlify Forms, or custom backend

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📬 Contact

**Ayush Paudel**
- 📧 Email: paudelayush191@gmail.com
- 💼 LinkedIn: [ayush-paudel](https://linkedin.com/in/ayush-paudel-69913b22a)
- 📱 Phone: +44 7570471792
- 📍 Location: Plymouth, UK

## 🙏 Acknowledgments

- Google Fonts for typography
- Inspiration from modern portfolio designs
- Built with attention to recruiter preferences

---

⭐ If you found this helpful, please consider giving it a star on GitHub!

**Made with 💻 and ☕ by Ayush Paudel**
