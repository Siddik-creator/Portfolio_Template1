# Abubakkarsiddik Matwal - Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Showcase skills, projects, and professional experience.

## 🚀 Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Animated Elements**: 
  - Fade-in animations on scroll
  - Skill progress bar animations
  - Project card hover effects
  - Typing effect in hero section
  - Parallax scrolling effect
- **Mobile Navigation**: Hamburger menu with smooth transitions
- **Contact Form**: Functional form with validation
- **Social Media Integration**: Links to GitHub, LinkedIn, Twitter, and Instagram

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables, flexbox, and grid
- **JavaScript (ES6+)**: Interactive features and animations
- **Font Awesome 6.4.0**: Icons
- **Google Fonts (Poppins)**: Typography

## 📁 Project Structure

```
my-portfolio/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript functionality
├── README.md       # This file
└── TODO.md         # Project tasks
```

## 🏃‍♂️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)

### Installation

1. **Clone or Download**
   
```
bash
   git clone <repository-url>
   cd my-portfolio
   
```

2. **Open in Browser**
   - Simply double-click `index.html` to open in your default browser
   - Or use a live server:
     
```
bash
     # Using VS Code Live Server extension
     # Right-click index.html → Open with Live Server
     
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎨 Customization

### Changing Personal Information

Edit the following in `index.html`:

- **Name**: Update all occurrences of "Abubakkarsiddik Matwal"
- **Title/Role**: Modify the hero section text
- **About Section**: Update bio and education details
- **Projects**: Add/modify project cards in the projects section
- **Contact**: Update email, phone, and address
- **Social Links**: Modify href attributes for social media icons

### Color Scheme

Customize colors in `style.css` under `:root`:

```
css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --dark-color: #1e293b;
    --light-color: #f8fafc;
    --text-color: #334155;
    --text-light: #94a3b8;
    --white: #ffffff;
}
```

### Adding New Skills

In `index.html`, add a new skill card:

```
html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Skill Name</h3>
    <div class="skill-progress">
        <div class="progress-bar" style="width: XX%">
            <span class="progress-text">XX%</span>
        </div>
    </div>
</div>
```

### Adding New Projects

In `index.html`, add a new project card:

```
html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon"></i>
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tags">
            <span>Tag1</span>
            <span>Tag2</span>
        </div>
        <a href="#" class="project-link">
            <span>View on GitHub</span>
            <i class="fas fa-arrow-right"></i>
        </a>
    </div>
</div>
```

## 📄 License

This project is for personal use. All rights reserved © 2024 Abubakkarsiddik Matwal.

## 📬 Contact

- **Email**: siddikmatwal@gmail.com
- **Phone**: +91 9420048620
- **LinkedIn**: [abubakkarsiddik-matwal](https://www.linkedin.com/in/abubakkarsiddik-matwal-40511931b)
- **GitHub**: [Siddik-creator](https://github.com/Siddik-creator)

---

Built with ❤️ by Abubakkarsiddik Matwal
