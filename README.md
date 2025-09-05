# Cisco U. | NetAcad Workshop Site

A clean, professional GitHub Pages site for distributing workshop materials and resources for Cisco networking education workshops.

## 🚀 Quick Start

1. **Fork this repository** to your GitHub account
2. **Update the site configuration** in `_config.yml`
3. **Replace placeholder content** with your workshop materials
4. **Enable GitHub Pages** in repository settings
5. **Customize and publish** your workshop site

## 📁 Site Structure

```
├── _config.yml              # Site configuration
├── _layouts/
│   └── default.html         # Main page layout
├── assets/
│   ├── css/
│   │   └── style.css        # Cisco-themed styling
│   ├── downloads/           # Workshop materials
│   └── images/              # Site images
├── index.html               # Homepage
├── agenda.html              # Workshop agenda
├── resources.html           # Instructor resources
├── feedback.html            # Feedback form
├── contact.html             # Contact & FAQs
└── README.md               # This file
```

## ⚙️ Configuration

### 1. Update Site Settings

Edit `_config.yml` to customize your workshop:

```yaml
# Site settings
title: "Your Workshop Title"
description: "Workshop description"
url: "https://yourusername.github.io/repository-name"

# Workshop details
workshop:
  name: "Your Workshop Name"
  description: "Workshop description"
  date: "Workshop Date"
  location: "Workshop Location"
```

### 2. Replace Workshop Materials

Upload your materials to the `assets/downloads/` directory:
- Presentation slides (PowerPoint/PDF)
- Lab guides and exercises
- Code samples and scripts
- Documentation and references
- Assessment materials

### 3. Update Interactive Links

- **Miro Board**: Replace the Miro board URL in `resources.html`
- **Google Form**: Replace the Google Form embed URL in `feedback.html`
- **Contact Information**: Update email addresses in `contact.html`

## 🎨 Customization

### Colors and Branding

The site uses Cisco brand colors defined in CSS variables:

```css
:root {
    --cisco-blue: #1BA0D7;
    --cisco-dark-blue: #0D274D;
    --cisco-light-blue: #58C4DC;
    --cisco-green: #6CC04A;
    --cisco-orange: #FF8C00;
}
```

### Adding New Pages

1. Create a new HTML file in the root directory
2. Add the Jekyll front matter:
   ```yaml
   ---
   layout: default
   title: "Page Title"
   description: "Page description"
   ---
   ```
3. Add the page to navigation in `_config.yml`

### Mobile Responsiveness

The site is fully responsive and mobile-friendly. Test on various devices and screen sizes.

## 📱 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Professional Styling**: Cisco-branded color scheme and typography
- **Interactive Elements**: Collapsible FAQs, star ratings, mobile menu
- **Downloadable Resources**: Organized file structure for easy access
- **Embedded Tools**: Google Forms, Miro boards, external links
- **SEO Optimized**: Proper meta tags and descriptions

## 🛠️ Local Development

### Prerequisites

- Ruby 2.7+ and Bundler
- Git

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
   cd repository-name
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open http://localhost:4000 in your browser

### Making Changes

1. Edit files locally
2. Test changes with `bundle exec jekyll serve`
3. Commit and push to GitHub
4. GitHub Pages will automatically rebuild and deploy

## 🚀 Deployment

### GitHub Pages Setup

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "GitHub Actions"
4. The site will automatically deploy when you push to the main branch

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update the `url` in `_config.yml`

## 📋 Checklist for New Workshops

- [ ] Fork/clone this repository
- [ ] Update `_config.yml` with workshop details
- [ ] Replace placeholder materials in `assets/downloads/`
- [ ] Update Miro board link in `resources.html`
- [ ] Update Google Form embed in `feedback.html`
- [ ] Update contact information in `contact.html`
- [ ] Test all download links
- [ ] Enable GitHub Pages
- [ ] Test the live site
- [ ] Share the site URL with participants

## 🤝 Contributing

This template is designed to be easily forkable and customizable. If you make improvements that would benefit other workshop organizers:

1. Fork the original repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Technical Issues**: Check the GitHub Issues page
- **Workshop Content**: Contact your Cisco U. or NetAcad coordinator
- **Site Customization**: Refer to Jekyll documentation

## 🔗 Related Resources

- [Cisco U. Portal](https://www.cisco.com/c/en/us/training-events/training-certifications/cisco-u.html)
- [NetAcad Learning](https://www.netacad.com)
- [Cisco DevNet](https://developer.cisco.com)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

**Built with ❤️ for the Cisco networking education community**
