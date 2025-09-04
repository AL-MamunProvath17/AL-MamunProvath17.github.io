# 🎓  Academic Portfolio - Md. Al-Mamun Provath

A cutting-edge, responsive academic portfolio designed specifically for PhD applications and research showcases. Built with modern web technologies and optimized for academic excellence presentation.

## ✨ Features

### 🚀 Modern Design Elements
- **Glassmorphism UI** - Semi-transparent elements with backdrop blur effects
- **Gradient Animations** - Dynamic color transitions and shimmer effects
- **Interactive Hover States** - Smooth transforms and shadow transitions
- **Responsive Grid Layouts** - CSS Grid with mobile-first approach
- **Typography Excellence** - Inter + Space Grotesk font combination

### 🎯 Academic-Focused Sections
- **Hero Section** - Impactful introduction with animated statistics
- **Research Interests** - Interactive cards highlighting research focus areas
- **Publications** - Filterable publication showcase with metrics
- **Contact Integration** - Professional networking links and CV download

### 📱 Technical Excellence
- **Performance Optimized** - Lightweight animations using transform/opacity only
- **Accessibility Compliant** - WCAG guidelines with semantic HTML
- **Mobile Responsive** - Fluid design across all device sizes
- **SEO Ready** - Proper meta tags and structured content

## 🛠️ Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Modern features (Grid, Flexbox, Custom Properties, Backdrop Filter)
- **Vanilla JavaScript** - Intersection Observer, smooth scrolling, interactive filters
- **Google Fonts** - Inter & Space Grotesk typography
- **No Dependencies** - Pure web technologies for maximum performance

## 📁 Project Structure

```
academic-portfolio/
│
├── index.html              # Main HTML file
├── README.md              # This file
├── images/                # Image assets
│   ├── Provath.jpeg       # Profile image
│   └── favicon/           # Favicon files
│       └── favicon.ico
└── data/                  # Documents
    └── Provath-CV.pdf     # CV file
```

## 🚀 Quick Start

### 1. Clone or Download
```bash
git clone https://github.com/AL-MamunProvath17/academic-portfolio.git
cd academic-portfolio
```

### 2. Add Your Content
Replace the placeholder content with your information:
- **Profile Image**: Replace `images/Provath.jpeg` with your photo
- **CV File**: Replace `data/Provath-CV.pdf` with your CV
- **Personal Info**: Update contact links, research interests, and publications

### 3. Deploy
Upload to any web hosting service:
- **GitHub Pages** (Recommended for academics)
- **Netlify** (Easy drag-and-drop deployment)
- **Vercel** (Great for performance)
- **Traditional hosting** (cPanel, etc.)

## 🎨 Customization Guide

### Color Scheme
The portfolio uses CSS custom properties for easy theming:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #1e1b4b 0%, #3730a3 100%);
  --secondary-gradient: linear-gradient(135deg, #0ea5e9 0%, #06b6d4 100%);
  --accent-color: #06b6d4;
  --highlight-color: #fbbf24;
}
```

### Typography
Two main fonts are used:
- **Inter** - Body text, clean and readable
- **Space Grotesk** - Headlines, modern tech aesthetic

### Layout Customization
- **Max Width**: 1400px container for large screens
- **Breakpoints**: 768px for mobile responsiveness
- **Grid Systems**: CSS Grid for complex layouts, Flexbox for components

## 📊 Content Management

### Adding Publications
```html
<div class="publication-item">
  <div class="publication-badge">YEAR</div>
  <div class="publication-title">
    <a href="DOI_LINK">Your Paper Title</a>
  </div>
  <div class="publication-authors">Authors List</div>
  <div class="publication-venue">Journal/Conference Name</div>
  <div class="publication-metrics">
    <span class="metric-badge">Accuracy: XX%</span>
    <span class="metric-badge">Category</span>
  </div>
</div>
```

### Updating Research Interests
```html
<div class="research-card">
  <div class="research-icon">🔬</div>
  <div class="research-title">Research Area</div>
  <div class="research-description">
    Detailed description of your research focus...
  </div>
</div>
```

### Statistics Update
```html
<div class="stat-item">
  <span class="stat-number">NUMBER</span>
  <div class="stat-label">Label</div>
</div>
```

## 🔧 Advanced Features

### Interactive Publication Filtering
The portfolio includes JavaScript-powered filtering:
- **All Publications** - Shows everything
- **By Year** - Filter by publication year
- **Journals vs Conferences** - Separate by type

### Smooth Animations
- **Intersection Observer** - Elements animate on scroll
- **Hover Effects** - Cards lift and glow on mouse over
- **Loading States** - Smooth transitions between states

### Performance Optimizations
- **Critical CSS** - Important styles loaded first
- **Image Optimization** - Proper alt tags and sizing
- **Minimal JavaScript** - Only essential interactions

## 📱 Mobile Optimization

### Responsive Features
- **Collapsible Navigation** - Mobile-friendly menu
- **Touch-Optimized** - Large tap targets
- **Readable Typography** - Fluid font scaling
- **Optimized Images** - Proper sizing for mobile

### Testing Across Devices
The design is tested and optimized for:
- **Mobile Phones** (320px - 768px)
- **Tablets** (768px - 1024px)
- **Desktops** (1024px+)
- **Large Screens** (1440px+)

## 🎯 SEO & Accessibility

### SEO Features
- **Semantic HTML** - Proper heading hierarchy
- **Meta Tags** - Title, description, author
- **Open Graph** - Social media sharing optimization
- **Structured Data** - Rich snippets for search engines

### Accessibility
- **ARIA Labels** - Screen reader support
- **Keyboard Navigation** - Full keyboard accessibility
- **Color Contrast** - WCAG AA compliance
- **Focus Indicators** - Visible focus states

## 📈 Analytics & Tracking

### Performance Monitoring
Track key metrics:
- **Page Load Speed** - Target: < 3 seconds
- **Core Web Vitals** - LCP, FID, CLS optimization
- **User Engagement** - Time on site, scroll depth

### Academic-Specific Metrics
- **CV Downloads** - Track CV engagement
- **Research Interest Clicks** - Popular research areas
- **Publication Link Clicks** - Most accessed papers

## 🚀 Deployment Options

### GitHub Pages (Free & Academic-Friendly)
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Choose source branch (usually `main`)
4. Access via `https://username.github.io/repository-name`

### Netlify (Drag & Drop)
1. Visit [netlify.com](https://netlify.com)
2. Drag project folder to deploy area
3. Get instant live URL
4. Optional: Connect to Git for auto-updates

### Custom Domain Setup
For professional presentation:
1. Purchase domain (yourname.com)
2. Configure DNS settings
3. Add SSL certificate
4. Update contact links accordingly

## 🔄 Maintenance & Updates

### Regular Updates
- **Publications** - Add new papers quarterly
- **Research Progress** - Update ongoing projects
- **Statistics** - Refresh citation counts monthly
- **CV** - Keep downloadable CV current

### Performance Monitoring
- **Google PageSpeed Insights** - Check loading performance
- **W3C Validator** - Ensure HTML/CSS compliance
- **Cross-browser Testing** - Test on Chrome, Firefox, Safari

## 🤝 Contributing

If you find bugs or have suggestions for improvements:

1. **Fork the repository**
2. **Create feature branch** (`git checkout -b feature/improvement`)
3. **Commit changes** (`git commit -am 'Add improvement'`)
4. **Push to branch** (`git push origin feature/improvement`)
5. **Create Pull Request**

## 📞 Support & Contact

For questions about implementation or customization:
- **Email**: am.provath@cuet.ac.bd
- **GitHub**: [@AL-MamunProvath17](https://github.com/AL-MamunProvath17)
- **LinkedIn**: [Al-Mamun Provath](https://www.linkedin.com/in/al-mamun-provath-3020a821b)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Design Inspiration**: Modern academic portfolios and tech company landing pages
- **Typography**: Google Fonts for Inter and Space Grotesk
- **Icons**: Emoji-based icons for universal compatibility
- **Color Palette**: Carefully selected for academic professionalism

---

**⭐ If this portfolio template helps with your academic journey, please consider giving it a star on GitHub!**

*Built with ❤️ for the academic community*
