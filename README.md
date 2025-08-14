# Dai Quoc Tran - Academic Website

A professional academic website showcasing research in AI, Computer Vision, and Construction Safety.

## 🚀 Features

- **Professional Design**: Clean, modern academic website design
- **Responsive Layout**: Mobile-friendly responsive design
- **Research Showcase**: Highlighted publications, projects, and achievements
- **Professional Navigation**: Easy-to-use navigation with clear sections
- **SEO Optimized**: Meta tags and structured content for better search visibility
- **Fast Loading**: Optimized CSS and minimal external dependencies

## 🏗️ Site Structure

```
daitranskku/
├── _config.yml          # Site configuration and metadata
├── index.md             # Homepage with research overview
├── about.md             # Detailed about page with background
├── projects.md          # Research projects showcase
├── publications.md      # Academic publications and citations
├── assets/
│   └── css/
│       └── style.scss   # Custom styling and CSS variables
├── layouts/
│   └── default.html     # Main layout template
├── figures/             # Project images and figures
└── README.md            # This file
```

## 📱 Pages Overview

### Homepage (`index.md`)
- Professional introduction and current position
- Research focus and core areas
- Recent achievements and awards
- Featured projects preview
- Selected publications highlights
- Research experience summary

### About (`about.md`)
- Comprehensive academic background
- Research philosophy and approach
- Core competencies and skills
- Professional journey timeline
- Research impact and recognition
- Collaboration opportunities

### Projects (`projects.md`)
- Featured research projects with detailed descriptions
- Project status and outcomes
- Research methodology overview
- Collaboration opportunities
- Technology stack and achievements

### Publications (`publications.md`)
- Organized by publication type and year
- Conference and journal publications
- Patent information
- Publication statistics
- Research impact and citations

## 🎨 Design Features

- **Color Scheme**: Professional blue and green palette
- **Typography**: Modern, readable fonts (Inter, system fonts)
- **Layout**: Card-based design with hover effects
- **Icons**: Font Awesome integration for visual elements
- **Responsive**: Mobile-first responsive design
- **Animations**: Subtle hover effects and transitions

## 🛠️ Technical Details

### Built With
- **Jekyll**: Static site generator
- **GitHub Pages**: Hosting platform
- **CSS Grid/Flexbox**: Modern layout techniques
- **Vanilla JavaScript**: Lightweight interactions
- **SCSS**: CSS preprocessing with variables

### CSS Features
- CSS Custom Properties (variables)
- Modern layout systems (Grid, Flexbox)
- Smooth transitions and animations
- Responsive breakpoints
- Print-friendly styles

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers
- Progressive enhancement approach

## 🚀 Getting Started

### Prerequisites
- Ruby (for Jekyll)
- Jekyll gem
- Git

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/daitranskku/daitranskku.git
   cd daitranskku
   ```

2. Install Jekyll:
   ```bash
   gem install jekyll bundler
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Run locally:
   ```bash
   bundle exec jekyll serve
   ```

5. Open browser to `http://localhost:4000`

### Deployment
The site is configured for GitHub Pages deployment:
- Push changes to the main branch
- GitHub Pages will automatically build and deploy
- Site will be available at `https://daitranskku.github.io`

## 📝 Content Management

### Adding New Publications
1. Edit `publications.md`
2. Add new publication in appropriate section
3. Include all required metadata (authors, title, venue, year, links)

### Adding New Projects
1. Edit `projects.md`
2. Add project description, features, and status
3. Upload project images to `figures/` directory
4. Update project references

### Updating Personal Information
1. Edit `_config.yml` for site-wide changes
2. Update individual page files for specific content
3. Ensure consistency across all pages

## 🔧 Customization

### Colors
Modify CSS variables in `assets/css/style.scss`:
```scss
:root {
  --primary-color: #0366d6;
  --secondary-color: #28a745;
  --accent-color: #ffc107;
  // ... other variables
}
```

### Layout
- Edit `layouts/default.html` for structural changes
- Modify CSS classes for styling adjustments
- Update navigation in the header section

### Content
- All content is in Markdown format
- HTML can be embedded for complex layouts
- Images should be placed in `figures/` directory

## 📊 Performance

- **Minimal Dependencies**: Only essential external resources
- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Fast Loading**: Optimized images and minimal JavaScript
- **SEO Ready**: Proper meta tags and structured content

## 🤝 Contributing

This is a personal academic website, but suggestions for improvements are welcome:
1. Fork the repository
2. Create a feature branch
3. Make improvements
4. Submit a pull request

## 📄 License

This project is for personal academic use. All content and design are property of Dai Quoc Tran.

## 📞 Contact

- **Email**: daitran@skku.edu
- **LinkedIn**: [Dai Quoc Tran](https://www.linkedin.com/in/dai-quoc-tran-092579116/)
- **Google Scholar**: [Dai Quoc Tran](https://scholar.google.com/citations?user=nr1jqx4AAAAJ&hl=en)
- **GitHub**: [daitranskku](https://github.com/daitranskku)

---

*Last updated: January 2025*
