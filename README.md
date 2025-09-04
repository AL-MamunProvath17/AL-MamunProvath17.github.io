# Academic Portfolio Website

This is the personal academic portfolio of **Md. Al-Mamun Provath**, showcasing research publications, academic background, and professional links.

The website is based on a lightweight HTML/CSS template adapted from [Jon Barron's academic website](https://github.com/jonbarron/jonbarron_website) and further customized for a modern, professional look.

---

## 🚀 Features

- **Academic Profile**: Includes bio, affiliations, and contact information
- **Research Publications**: Structured list of published papers with links to IEEE, Springer, and Google Scholar
- **Responsive Layout**: Optimized for desktop and mobile viewing
- **Lightweight**: Pure HTML and CSS without unnecessary frameworks
- **Professional Design**: Clean, modern interface focused on academic content

---

## 📂 Project Structure

```
.
├── index.html             # Main HTML file (your portfolio page)
├── stylesheet.css         # Custom styles
├── images/                # Profile photo and publication figures
│   └── Provath.jpeg      # Profile photo
├── data/                  # CV and bio files
│   ├── Provath-CV.pdf    # Academic CV
│   └── Provath-bio.txt   # Short biography
├── favicon/               # Favicon files
│   ├── favicon.ico
│   └── favicon-16x16.png
└── README.md              # Documentation (this file)
```

---

## 🛠️ How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

### 2. View Locally
Open `index.html` in any modern web browser to preview the website.

### 3. Customize Your Content

#### **Profile Information**
- **Photo**: Replace `images/Provath.jpeg` with your profile photo
- **Bio**: Edit the biography section directly in `index.html`
- **Contact**: Update email, institutional affiliation, and other details

#### **Publications**
Add or modify publications by editing the `<tr>` blocks in `index.html`:
```html
<tr>
  <td style="padding:20px;width:25%;vertical-align:middle">
    <div class="one">
      <img src='images/your-paper-image.png' width="160">
    </div>
  </td>
  <td style="padding:20px;width:75%;vertical-align:middle">
    <a href="link-to-paper">
      <papertitle>Your Paper Title</papertitle>
    </a>
    <br>
    <strong>Your Name</strong>, Co-author Name
    <br>
    <em>Conference/Journal Name</em>, Year
    <br>
    <a href="paper-link">paper</a> /
    <a href="project-link">project</a>
    <p>Brief description of your research contribution.</p>
  </td>
</tr>
```

#### **Professional Links**
Update the header section with your:
- Email address
- Google Scholar profile
- LinkedIn profile  
- GitHub profile
- ORCID (optional)

#### **CV and Bio Files**
- Replace `data/Provath-CV.pdf` with your academic CV
- Update `data/Provath-bio.txt` with your biography

---

## 🌐 Deployment

### GitHub Pages (Free Hosting)
1. Push your repository to GitHub
2. Go to **Settings → Pages** in your repository
3. Select the `main` branch and `/root` folder as source
4. Your site will be live at: `https://your-username.github.io/portfolio/`

### Other Hosting Options
- **Netlify**: Drag and drop your folder for instant deployment
- **Vercel**: Connect your GitHub repository for automatic deployments
- **Traditional Web Hosting**: Upload files via FTP to your hosting provider

---

## 🎨 Customization

### Colors and Styling
Modify `stylesheet.css` to change:
- Color scheme
- Typography
- Layout spacing
- Responsive breakpoints

### Adding New Sections
You can easily add new sections like:
- Teaching experience
- Awards and honors
- Service activities
- Software/tools developed

Follow the existing HTML structure and styling patterns.

---

## 📱 Browser Compatibility

This website is compatible with all modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

---

## 🤝 Contributing

If you find bugs or have suggestions for improvements:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- Website design inspired by [Maxine Perroni-Scharf](https://maxineaps.github.io/)
- Original code adapted from [Jon Barron's academic website](https://github.com/jonbarron/jonbarron_website)
- Template structure follows academic portfolio best practices

---

## 👤 Author

**Md. Al-Mamun Provath**  
Lecturer, Department of Computer Science and Engineering  
[Chittagong University of Engineering & Technology (CUET)](https://cuet.ac.bd/)

📧 [am.provath@cuet.ac.bd](mailto:am.provath@cuet.ac.bd)  
🎓 [Google Scholar](https://scholar.google.com/citations?user=your-id)  
💼 [LinkedIn](https://linkedin.com/in/your-profile)  
💻 [GitHub](https://github.com/your-username)

---

## 📈 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Implement blog section
- [ ] Add publication search/filter functionality
- [ ] Include interactive research timeline
- [ ] Add contact form
- [ ] Implement analytics tracking

---

*Last updated: September 2025*
