# 🚀 RDNATH93 - Portfolio Website

A modern, dark-themed portfolio website built with vanilla HTML, CSS, and JavaScript. Showcasing projects, skills, and making a great first impression!

## ✨ Features

- **🌙 Modern Dark Theme** - Eye-catching dark design with vibrant cyan, pink, and purple accents
- **📱 Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **⚡ High Performance** - Lightweight vanilla JavaScript (no heavy frameworks)
- **🎨 Smooth Animations** - Elegant transitions and scroll animations
- **♿ Accessible** - Semantic HTML and keyboard-friendly navigation
- **🔍 SEO Friendly** - Proper meta tags and semantic structure

## 📁 File Structure

```
rdnath93.github.io/
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete dark theme styling
├── script.js           # Interactive JavaScript functionality
└── README.md           # This file
```

## 🎯 Sections

### 1. **Navigation Bar**
- Sticky navigation with smooth scrolling
- Animated underline effects on hover
- Responsive mobile menu support

### 2. **Hero Section**
- Eye-catching title with gradient text
- Call-to-action buttons
- Code block visual showcase

### 3. **About Section**
- Personal introduction
- Skills grid with 8 technology tags
- Organized layout with two-column design

### 4. **Projects Section**
- 4 featured project cards
- Each card includes:
  - Project title and description
  - GitHub and Live demo links
  - Technology tags
  - Hover animations and transitions

### 5. **Contact Section**
- Clear call-to-action
- Social media and email links
- Professional contact layout

### 6. **Footer**
- Copyright information
- Built-with message

## 🎨 Color Scheme

```css
Primary Background:    #0f0f1e (Deep Navy)
Secondary Background:  #1a1a2e
Text Primary:          #e0e0e0 (Light Gray)
Text Secondary:        #a0a0a0 (Medium Gray)
Accent Primary:        #00d4ff (Cyan)
Accent Secondary:      #ff006e (Pink)
Accent Tertiary:       #8338ec (Purple)
```

## 🚀 Getting Started

### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/RDNATH93/rdnath93.github.io.git
   cd rdnath93.github.io
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server: `python -m http.server 8000`

### Live Deployment
Your site is automatically published at: **https://rdnath93.github.io**

Changes are live within seconds of pushing to the main branch!

## 📝 Customization Guide

### 1. **Update Personal Information**
Open `index.html` and replace:
- Your name and title in the hero section
- Personal bio in the about section
- Social media links in the contact section
- Email address in the footer

### 2. **Add Your Projects**
In the projects section, update each project card:
```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <div class="project-links">
            <a href="GITHUB_LINK" class="project-link">GitHub</a>
            <a href="LIVE_LINK" class="project-link">Live</a>
        </div>
    </div>
    <p class="project-description">Your project description here...</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
</div>
```

### 3. **Customize Colors**
Edit the CSS variables in `styles.css`:
```css
:root {
    --accent-primary: #00d4ff;      /* Change cyan */
    --accent-secondary: #ff006e;    /* Change pink */
    --accent-tertiary: #8338ec;     /* Change purple */
    --bg-primary: #0f0f1e;          /* Change background */
    --text-primary: #e0e0e0;        /* Change text color */
}
```

### 4. **Update Skills**
Modify the skills grid in the about section:
```html
<div class="skills-grid">
    <div class="skill-tag">Your Skill</div>
    <!-- Add more skills as needed -->
</div>
```

### 5. **Add Social Links**
Update contact section with your actual URLs:
```html
<a href="https://github.com/YOUR_USERNAME" class="contact-btn">GitHub</a>
<a href="https://twitter.com/YOUR_HANDLE" class="contact-btn">Twitter</a>
<a href="https://linkedin.com/in/YOUR_PROFILE" class="contact-btn">LinkedIn</a>
<a href="mailto:YOUR_EMAIL@example.com" class="contact-btn">Email</a>
```

## ✅ Quick Checklist

- [ ] Update hero section with your name and title
- [ ] Add your personal bio in about section
- [ ] Add 4+ of your best projects
- [ ] Update skills/technologies you know
- [ ] Add your social media links
- [ ] Update email address for contact
- [ ] Test on mobile devices
- [ ] Push changes to GitHub

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (Vanilla)** - No dependencies, pure interactivity
- **Google Fonts** - Inter & JetBrains Mono typefaces

## 🎬 JavaScript Features

- ✅ Smooth scroll navigation
- ✅ Scroll-triggered fade-in animations
- ✅ Active link highlighting on scroll
- ✅ Navbar shadow on scroll
- ✅ Ripple effect on button clicks
- ✅ Intersection Observer for performance

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with all features
- **Tablet** (768px): Adjusted grid layout
- **Mobile** (640px): Single column layout, optimized spacing

## 🔗 Useful Resources

- [Google Fonts](https://fonts.google.com) - Add more fonts
- [CSS Gradients](https://cssgradients.io) - Create custom gradients
- [Normalize.css](https://necolas.github.io/normalize.css/) - For cross-browser consistency
- [GitHub Pages Docs](https://pages.github.com) - Deployment help

## 🤝 Contributing

Feel free to fork, customize, and improve this portfolio template!

## 📄 License

This project is open source and available for personal and commercial use.

## 💡 Tips

- **Add a Blog Section**: Create a `blog.html` page and link it in navigation
- **Add Projects Dynamically**: Use JSON to load projects and render them with JavaScript
- **Dark Mode Toggle**: Add a theme switcher for light/dark mode
- **Contact Form**: Integrate with Formspree or EmailJS for form submissions
- **Analytics**: Add Google Analytics to track visitors
- **Performance**: Minify CSS and JavaScript for production
- **SEO**: Add Open Graph meta tags for social sharing

## 🚀 Deployment Tips

1. **Custom Domain**: Add a CNAME file with your domain
2. **HTTPS**: GitHub Pages provides free HTTPS
3. **Fast Updates**: Push changes directly to main branch
4. **Caching**: Use `?v=1` parameters for cache busting

---

**Made with ❤️ by RDNATH93**

Happy coding! If you find this template useful, consider giving it a star ⭐

Visit: [https://rdnath93.github.io](https://rdnath93.github.io)
