# Guilherme The Data Guy - Portfolio Website

A modern, responsive portfolio website showcasing data analysis and engineering expertise, built with HTML5, CSS3, and JavaScript.

## 🚀 Live Demo

Visit the live website: [https://guilhermethedataguy.com/](https://guilhermethedataguy.com/)

## 📋 About

This is a personal portfolio website for Guilherme, a passionate data analyst with 5+ years of experience in e-commerce, beverages, food delivery, and market research industries. The website showcases recent projects, skills, and provides contact information.

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: SASS/SCSS
- **Icons**: Font Awesome
- **Libraries**: 
  - jQuery
  - Poptrox (lightbox gallery)
  - Responsive Tools
- **Template**: Based on "Strata" by HTML5 UP

## 📁 Project Structure

```
portfolio_website/
├── assets/
│   ├── css/                    # Compiled CSS files
│   ├── js/                     # JavaScript files
│   ├── sass/                   # SASS source files
│   └── webfonts/               # Font Awesome fonts
├── images/
│   ├── projects/               # Project showcase images
│   ├── fulls/                  # Full-size gallery images
│   ├── thumbs/                 # Thumbnail images
│   ├── profile.jpeg            # Profile photo
│   └── MainTools.png           # Tools/skills image
├── index.html                  # Main HTML file
├── CNAME                       # GitHub Pages custom domain
└── README.md                   # Project documentation
```

## 🏗️ Setup & Installation

### Prerequisites

- A modern web browser
- (Optional) A local web server for development

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/GuilherLRO/portfolio_website.git
   cd portfolio_website
   ```

2. **Open locally**
   - Simply open `index.html` in your web browser, or
   - Use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Access the website**
   - Direct file: `file:///path/to/index.html`
   - Local server: `http://localhost:8000`

## 🎨 Customization

### Modifying Content

1. **Personal Information**: Edit the content in `index.html`
2. **Projects**: Update the "Recent Work" section with your projects
3. **Images**: Replace images in the `images/` folder
4. **Styling**: Modify SASS files in `assets/sass/` and recompile

### Compiling SASS

If you modify the SASS files:

```bash
# Install SASS (if not already installed)
npm install -g sass

# Compile SASS to CSS
sass assets/sass/main.scss assets/css/main.css
```

### Adding New Projects

1. Add project images to `images/projects/`
2. Update the projects section in `index.html`
3. Follow the existing format for consistency

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Custom Domain

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings

## 📝 Featured Projects

- **DuckDB Data Analysis**: Large dataset analysis using DuckDB
- **Weather Analytics**: Airflow + PostgreSQL + Metabase pipeline
- **AWS ML Model**: Starbucks offer acceptance prediction
- **Time Series Forecasting**: Highway occurrences prediction
- **Home Server Setup**: Docker-driven Ubuntu server with CasaOS

## 📧 Contact

- **Email**: guilhermelro2@gmail.com
- **Phone**: +55 85 98880-3266
- **Location**: Fortaleza, CE, Brasil
- **GitHub**: [GuilherLRO](https://github.com/GuilherLRO)
- **LinkedIn**: [https://www.linkedin.com/in/guilhermelro/](https://www.linkedin.com/in/guilhermelro/)

## 📄 License

This project is built upon the "Strata" template by HTML5 UP, which is free for personal and commercial use under the CCA 3.0 license.

## 🙏 Credits

- **Template**: [Strata by HTML5 UP](https://html5up.net)
- **Icons**: [Font Awesome](https://fontawesome.io)
- **JavaScript**: [jQuery](https://jquery.com)
- **Images**: Personal and project-specific images

## 🔧 Contributing

This is a personal portfolio website. However, if you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## 📊 Performance

The website is optimized for:
- ✅ Mobile responsiveness
- ✅ Fast loading times
- ✅ Cross-browser compatibility
- ✅ SEO-friendly structure
- ✅ Accessible design

---

*Last updated: January 2025*