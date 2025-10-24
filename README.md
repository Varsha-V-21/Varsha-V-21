# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio features a clean design, smooth animations, and is fully responsive across all devices.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Performance Optimized**: Fast loading with optimized code
- **Accessibility**: Semantic HTML and keyboard navigation support

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font family for typography

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone or download** this repository to your local machine

2. **Open the project** in your preferred code editor

3. **Customize the content**:
   - Replace "Your Name" with your actual name
   - Update social media links with your profiles
   - Modify the about section with your information
   - Add your actual projects and skills
   - Update contact information

4. **Run the website**:
   - **Option 1**: Open `index.html` directly in your browser
   - **Option 2**: Use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

5. **Access the website**:
   - Direct file: Open `index.html` in your browser
   - Local server: Visit `http://localhost:8000`

## 🎨 Customization Guide

### Personal Information

1. **Update the hero section** in `index.html`:
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <p class="hero-subtitle">Your Job Title</p>
   ```

2. **Update social links**:
   ```html
   <a href="https://github.com/yourusername" target="_blank" class="social-link">
   <a href="https://linkedin.com/in/yourusername" target="_blank" class="social-link">
   ```

3. **Modify the about section** with your personal information

### Skills and Technologies

Update the skills section in `index.html`:
```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <span class="skill-item">React</span>
        <span class="skill-item">Vue.js</span>
        <!-- Add your skills here -->
    </div>
</div>
```

### Projects

Replace the sample projects with your actual projects:
```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-live-demo" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### Styling

Customize colors and fonts in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #1f2937;
    --background-color: #ffffff;
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Email format validation
- Success/error notifications
- Form reset after submission

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to integrate with a backend service or email service provider.

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings
3. Scroll down to "Pages" section
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push
3. Custom domain support available

### Vercel

1. Import your GitHub repository to Vercel
2. Automatic deployments on every push
3. Global CDN for fast loading

## 🔧 Development

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update navigation menu if needed

### Performance Tips

- Optimize images before adding them
- Minify CSS and JavaScript for production
- Use a CDN for external libraries
- Enable gzip compression on your server

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📞 Support

If you have any questions or need help customizing this portfolio, feel free to reach out!

---

**Happy coding! 🎉**