# Dai Quoc Tran - Academic Profile

A professional academic profile website built with Jekyll, showcasing research, publications, and projects in construction engineering and computer vision.

## Features

- **Professional Academic Design**: Clean, modern layout optimized for academic profiles
- **Responsive Layout**: Mobile-friendly design that works on all devices
- **Publication Management**: Organized display of research publications with status indicators
- **Project Showcase**: Detailed project descriptions with visual elements
- **Skills & Expertise**: Clear presentation of technical skills and research areas
- **SEO Optimized**: Built-in search engine optimization features

## Local Development

### Prerequisites

- **Ruby**: Version 2.6.0 or higher
- **RubyGems**: Usually comes with Ruby
- **Bundler**: Install with `gem install bundler`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/daitranskku/daitranskku.git
   cd daitranskku
   ```

2. **Install dependencies**:
   ```bash
   bundle install
   ```

3. **Run the site locally**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**: Open your browser and go to `http://localhost:4000`

### Development Commands

- **Build the site**: `bundle exec jekyll build`
- **Serve with live reload**: `bundle exec jekyll serve --livereload`
- **Build for production**: `bundle exec jekyll build --production`

## Site Structure

```
daitranskku/
├── _config.yml          # Site configuration
├── index.md             # Home page
├── about.md             # About page
├── publications.md      # Publications listing
├── projects.md          # Projects showcase
├── assets/
│   └── css/
│       └── style.scss   # Custom styles
├── figures/             # Images and figures
└── layouts/             # Jekyll layouts
```

## Customization

### Adding Publications

Edit `publications.md` to add new publications. Use the following format:

```markdown
<div class="publication-item">
  <div class="pub-authors"><strong>Your Name</strong>, Co-authors</div>
  <div class="pub-title">Publication Title</div>
  <div class="pub-venue">Journal/Conference Name</div>
  <div class="pub-year">Year | <a href="link">Published</a></div>
</div>
```

### Adding Projects

Edit `projects.md` to add new projects:

```markdown
<div class="project-card-large">
  <img src="{{ site.baseurl }}/figures/project-image.png" alt="Project Name">
  <div class="project-content">
    <p>Project description...</p>
    <div class="project-tech">
      <strong>Technologies:</strong> Tech stack used
    </div>
  </div>
</div>
```

### Styling

Customize the appearance by editing `assets/css/style.scss`. The site uses CSS custom properties for easy color scheme changes:

```scss
:root {
  --primary-color: #2c3e50;    // Main text color
  --secondary-color: #3498db;   // Accent color
  --accent-color: #e74c3c;     // Highlight color
  --success-color: #27ae60;     // Success indicators
  --warning-color: #f39c12;     // Warning indicators
}
```

## Deployment

### GitHub Pages

1. Push your changes to the `main` branch
2. GitHub Pages will automatically build and deploy your site
3. Your site will be available at `https://daitranskku.github.io`

### Other Hosting

- **Netlify**: Drag and drop the `_site` folder after building
- **Vercel**: Connect your GitHub repository for automatic deployments
- **Traditional hosting**: Upload the `_site` folder contents to your web server

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `bundle exec jekyll serve`
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: daitran@skku.edu
- **LinkedIn**: [Dai Quoc Tran](https://www.linkedin.com/in/dai-quoc-tran-092579116/)
- **Google Scholar**: [Dai Quoc Tran](https://scholar.google.com/citations?user=nr1jqx4AAAAJ&hl=en)
- **GitHub**: [daitranskku](https://github.com/daitranskku)
