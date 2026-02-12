# Portfolio Website - Sai Preetham

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-green)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

A modern, responsive personal portfolio website showcasing my professional profile, skills, and projects. Built with clean HTML5 and CSS3, this single-page application provides an elegant user experience across all devices.

## 🌐 Live Demo

Visit the live website: [Portfolio Website](https://saivishnupreetham.github.io/Portfolio-website-mark-1/)

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Sections](#sections)
- [Design Highlights](#design-highlights)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Responsive Design](#responsive-design)
- [Browser Compatibility](#browser-compatibility)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## ✨ Features

- **Fully Responsive Design**: Seamlessly adapts to desktop, tablet, and mobile devices
- **Single Page Application**: Smooth navigation with anchor links
- **Modern UI/UX**: Clean, professional design with custom color scheme
- **Fixed Navigation Bar**: Easy access to all sections from anywhere on the page
- **Interactive Elements**: Hover effects on buttons and links for better user engagement
- **Downloadable Resume**: Direct CV download functionality
- **Project Showcase**: Dedicated section highlighting technical projects
- **Contact Section**: Easy-to-use contact form (ready for backend integration)
- **Optimized Performance**: Lightweight codebase for fast loading times

## 🛠 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure (56.7%) |
| **CSS3** | Styling, layout, and responsive design (43.3%) |
| **Google Fonts** | DM Sans font family for modern typography |
| **CSS Variables** | Consistent theming and easy customization |
| **Flexbox** | Modern layout system for responsive design |

## 📁 Project Structure

```
Portfolio-website-mark-1/
│
├── index.html                          # Main HTML file
├── README.md                           # Project documentation
│
└── assets/
    ├── Resume-Sai_Preetham_Mark-3.pdf # Downloadable resume
    │
    ├── images/                         # Image assets
    │   ├── sai.crop.png               # Logo image
    │   ├── sai.profile.jpg            # Profile photo
    │   └── icons/
    │       └── arrow.png              # Navigation arrow icon
    │
    └── style/
        └── main.css                    # Main stylesheet
```

## 📄 Sections

### 1. **Navigation Bar**
- Fixed position for persistent access
- Logo branding
- Quick links to all sections: Home, About, Projects, Contact, Download CV
- Responsive mobile menu (collapsible on smaller screens)

### 2. **Hero Section**
- Eye-catching introduction
- Name and current academic status
- Visual arrow indicator for scrolling
- Full viewport height for impact

### 3. **About Me**
- Professional profile photo
- Detailed biography
- Educational background (B.Tech CSE - AIML, Dayananda Sagar University)
- Skills and interests in AI/ML
- Career objectives and internship availability

### 4. **Projects**
- Showcase of technical projects
- Detailed project descriptions
- Technology stack information
- Links to GitHub repositories

**Featured Project:**
- **Face Detection System**: Real-time face detection and counting using OpenCV and Python with Haar cascade classifiers

### 5. **Contact Section** (Expandable)
- Contact form structure ready for backend integration
- Clean input fields with labels
- Submit button with hover effects

### 6. **Download CV**
- Direct download link for resume
- Prominent button styling
- Easy access for recruiters and collaborators

## 🎨 Design Highlights

### Color Palette

The website uses a carefully selected color scheme defined through CSS custom properties:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary | `#6366F1` | Main brand color, buttons, links |
| Secondary | `#F2F2F2` | Background, contrast elements |
| Accent | `#EC4899` | Call-to-action buttons, highlights |
| Gray Text | `#606060` | Body text, subtle elements |

### Typography

- **Font Family**: DM Sans (Google Fonts)
- **Heading 1**: 3.75rem with 97% line height
- **Heading 2**: 2rem with 117% line height
- **Body Text**: 1rem with 166% line height for readability
- **Links**: 0.8rem with uppercase transformation

### Interactive Elements

- Smooth hover transitions on buttons and links
- Color inversion effects on button hover
- Border highlights for enhanced contrast
- Cursor pointer feedback on clickable elements

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SaiVishnuPreetham/Portfolio-website-mark-1.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Portfolio-website-mark-1
   ```

3. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server (recommended)
   ```

### Using a Local Server

**Option 1: Python**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option 2: Node.js (with http-server)**
```bash
npx http-server
```

**Option 3: VS Code Live Server**
- Install Live Server extension
- Right-click on `index.html`
- Select "Open with Live Server"

## 💻 Usage

1. Open `index.html` in a web browser
2. Navigate through sections using the fixed navigation bar
3. Click on project links to view GitHub repositories
4. Download the resume using the "Download CV" button
5. Use the contact form to get in touch (backend integration required)

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `assets/style/main.css`:

```css
:root {
    --primary-color: #6366F1;    /* Your primary color */
    --secondary-color: #F2F2F2;  /* Your secondary color */
    --accent-color: #EC4899;     /* Your accent color */
    --gray-text: #606060;        /* Your text color */
}
```

### Updating Content

1. **Personal Information**: Edit text in `index.html` within respective sections
2. **Profile Images**: Replace images in `assets/images/` with your own (maintain same filenames)
3. **Resume**: Replace `Resume-Sai_Preetham_Mark-3.pdf` in `assets/` folder
4. **Projects**: Add new project containers in the projects section

### Modifying Layout

Adjust layout variables in `:root`:

```css
:root {
    --container-width: 1000px;        /* Maximum content width */
    --section-margin-top: 205px;      /* Space between sections */
}
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:

- **Desktop**: Default styles (> 800px)
- **Tablet/Mobile**: Media query at 800px

### Mobile Optimizations

- Flexbox containers switch to column layout
- Reduced gaps between elements
- Added horizontal padding (3rem) for readability
- Navigation menu adapts for smaller screens
- Images scale proportionally

```css
@media(max-width:800px) {
    .hero, .flex-container, .project_container, .section-wrapper {
        flex-direction: column;
        gap: 2rem;
    }
    .container {
        padding: 0 3rem;
    }
}
```

## 🌐 Browser Compatibility

Tested and compatible with:

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

**Note**: Modern CSS features (CSS Variables, Flexbox) require relatively recent browser versions.

## 🚀 Future Enhancements

Planned improvements and features:

- [ ] Dark mode toggle
- [ ] Animated transitions using JavaScript
- [ ] Skills section with progress bars
- [ ] Testimonials/recommendations section
- [ ] Blog integration
- [ ] Contact form backend integration (Node.js/PHP)
- [ ] Social media links and icons
- [ ] Project filtering by technology
- [ ] Accessibility improvements (ARIA labels, keyboard navigation)
- [ ] SEO optimization with meta tags
- [ ] Performance optimization (lazy loading images)
- [ ] Analytics integration (Google Analytics)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Sai Vishnu Preetham**

- GitHub: [@SaiVishnuPreetham](https://github.com/SaiVishnuPreetham)
- Portfolio: [Live Website](https://saivishnupreetham.github.io/Portfolio-website-mark-1/)
- LinkedIn: [Connect with me](#) _(Add your LinkedIn URL)_
- Email: _(Add your email)_

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [Sai Vishnu Preetham](https://github.com/SaiVishnuPreetham)

</div>
