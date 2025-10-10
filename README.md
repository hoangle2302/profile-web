# 🚀 Portfolio Website - Lê Huy Hoàng

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Responsive-Mobile--First-blue?style=for-the-badge" alt="Responsive">
</div>

<div align="center">
  <h3>🎯 Developer & AI Researcher Portfolio</h3>
  <p>A modern, responsive portfolio website showcasing skills, projects, and professional journey in technology and AI development.</p>
</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [📱 Pages Overview](#-pages-overview)
- [🎨 Design Features](#-design-features)
- [📊 Responsive Design](#-responsive-design)
- [🔧 Customization](#-customization)
- [📞 Contact Information](#-contact-information)
- [📄 License](#-license)

---

## ✨ Features

### 🌟 Core Features
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Multi-page Navigation** - Organized content across multiple pages
- **Interactive Elements** - Hover effects, smooth scrolling, and dynamic content
- **Contact Form** - Functional contact form with validation
- **Social Media Integration** - Links to GitHub, Facebook, Email, and YouTube

### 🎯 Professional Sections
- **Personal Introduction** - Hero section with professional overview
- **Skills Showcase** - Interactive skill bars and technology categories
- **Project Portfolio** - Detailed project cards with live demos and source code
- **Career Timeline** - Professional journey and milestones
- **Personal Interests** - Hobbies and personal life insights
- **Contact Information** - Multiple ways to get in touch

---

## 🛠️ Technologies Used

### Frontend Technologies
- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Advanced styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)** - Interactive functionality and dynamic content
- **Font Awesome** - Professional icon library
- **Google Fonts** - Custom typography (Poppins, Playfair Display)

### Design Framework
- **CSS Grid & Flexbox** - Modern layout systems
- **CSS Variables** - Consistent theming and easy customization
- **Media Queries** - Responsive breakpoints for all devices
- **Smooth Animations** - CSS transitions and keyframe animations

---

## 📁 Project Structure

```
profile-web/
├── frontend/
│   ├── index.html          # 🏠 Homepage
│   ├── info.html           # ℹ️ Detailed personal information
│   ├── skills.html         # 💪 Skills and technologies
│   ├── projects.html       # 🔨 Project portfolio
│   ├── contact.html        # 📞 Contact information
│   ├── style.css          # 🎨 Main stylesheet
│   ├── avt.jpg            # 👤 Profile image
│   ├── đầu đỏ.jpg         # 👤 Additional profile image
│   └── assets/            # 📂 Additional assets
│       ├── images/        # 🖼️ Project images
│       └── icons/         # 🎯 Custom icons
├── README.md              # 📖 Project documentation
└── .gitignore            # 🚫 Git ignore rules
```

---

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML/CSS/JavaScript

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/hoangle2302/profile-web.git
   cd profile-web
   ```

2. **Navigate to frontend directory**
   ```bash
   cd frontend
   ```

3. **Open in browser**
   - Double-click `index.html` or
   - Right-click and "Open with" your preferred browser or
   - Use Live Server extension in VS Code

### Local Development
```bash
# If using VS Code with Live Server extension
code .
# Then right-click on index.html and select "Open with Live Server"
```

---

## 📱 Pages Overview

### 🏠 Homepage (`index.html`)
- **Hero Section** - Personal introduction and call-to-action
- **About Section** - Professional overview and statistics
- **Skills Preview** - Technology stack and expertise levels
- **Featured Projects** - Highlighted work samples
- **Contact Section** - Contact form and information

### ℹ️ Info Page (`info.html`)
- **Personal Introduction** - Detailed background story
- **Personal Information** - Education, experience, and skills
- **Hobbies & Interests** - Personal life and interests
- **Career Timeline** - Professional development journey

### 💪 Skills Page (`skills.html`)
- **Technical Skills** - Programming languages and frameworks
- **Tools & Technologies** - Development tools and platforms
- **Skill Levels** - Visual representation of proficiency
- **Certifications** - Professional certifications and achievements

### 🔨 Projects Page (`projects.html`)
- **Project Showcase** - Detailed project presentations
- **Technology Stack** - Technologies used in each project
- **Live Demos** - Links to working applications
- **Source Code** - GitHub repository links

### 📞 Contact Page (`contact.html`)
- **Contact Form** - Direct messaging capability
- **Contact Information** - Phone, email, and location
- **Social Media** - Professional social network links
- **FAQ Section** - Frequently asked questions

---

## 🎨 Design Features

### Color Scheme
```css
:root {
  --primary-color: #0d9488;      /* Teal Green */
  --secondary-color: #14b8a6;    /* Light Teal */
  --accent-color: #06b6d4;       /* Sky Blue */
  --bg-primary: #ffffff;         /* White */
  --bg-secondary: #f0fdfa;       /* Light Mint */
  --text-primary: #134e4a;       /* Dark Teal */
  --text-secondary: #0f766e;     /* Medium Teal */
}
```

### Typography
- **Primary Font**: Poppins (Modern, clean sans-serif)
- **Heading Font**: Playfair Display (Elegant serif for titles)
- **Font Weights**: 300, 400, 500, 600, 700

### UI Components
- **Gradient Buttons** - Eye-catching call-to-action elements
- **Card Layouts** - Clean, organized content presentation
- **Progress Bars** - Visual skill level indicators
- **Hover Effects** - Interactive feedback on all clickable elements
- **Smooth Transitions** - Professional animations throughout

---

## 📊 Responsive Design

### Breakpoints
- **Desktop**: 1200px+ (Full layout with sidebar)
- **Laptop**: 992px - 1199px (Adjusted spacing)
- **Tablet**: 768px - 991px (Stacked navigation)
- **Mobile**: < 768px (Mobile-first approach)

### Mobile Features
- **Hamburger Menu** - Collapsible navigation
- **Touch-Optimized** - Larger tap targets
- **Optimized Images** - Faster loading on mobile
- **Readable Typography** - Scaled fonts for mobile screens

---

## 🔧 Customization

### Updating Personal Information

1. **Profile Images**
   - Replace `avt.jpg` and `đầu đỏ.jpg` with your photos
   - Recommended size: 400x400px for profile images

2. **Personal Content**
   ```html
   <!-- Update in index.html -->
   <h1 class="hero-title">
     Xin chào, tôi là <br>
     <span class="text-gradient">Your Name Here</span>
   </h1>
   ```

3. **Contact Information**
   ```html
   <!-- Update social media links -->
   <a href="https://github.com/yourusername" class="social-link">
   <a href="mailto:youremail@domain.com" class="social-link">
   ```

4. **Skills and Projects**
   - Update skill percentages in the progress bars
   - Replace project images and descriptions
   - Update GitHub repository links

### Color Customization
```css
/* Update CSS variables in style.css */
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  /* Add more custom colors */
}
```

---

## 🎯 Key Projects Showcased

### 🔍 Mắt Thần - AI Traffic Monitor
- **Technology**: Python, YOLO, OpenCV
- **Description**: AI system for real-time traffic violation detection
- **Features**: Deep learning, Computer Vision, Real-time processing

### 🐎 Horse Racing Game  
- **Technology**: Python, Pygame, PyQt6
- **Description**: Multiplayer online horse racing game
- **Features**: Beautiful graphics, Multiplayer support, Game logic

### 🔒 Cybersecurity Toolkit
- **Technology**: Python, Security Libraries
- **Description**: Comprehensive security tool suite
- **Features**: Network scanning, Vulnerability assessment

---

## 📈 Performance Features

### Optimization
- **Lazy Loading** - Images load as needed
- **Minified CSS** - Compressed stylesheets
- **Optimized Images** - WebP format support
- **Caching Strategy** - Browser caching headers

### SEO Friendly
- **Semantic HTML** - Proper heading structure
- **Meta Tags** - Optimized for search engines
- **Alt Text** - Accessible image descriptions
- **Structured Data** - Rich snippets support

---

## 🔒 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 70+     | ✅ Full |
| Firefox | 65+     | ✅ Full |
| Safari  | 12+     | ✅ Full |
| Edge    | 79+     | ✅ Full |
| Opera   | 57+     | ✅ Full |

---

## 📞 Contact Information

### 👨‍💻 Developer
**Lê Huy Hoàng**
- 🎯 **Role**: Developer & AI Researcher
- 📧 **Email**: lehuyhoang840@gmail.com
- 🌐 **GitHub**: [@hoangle2302](https://github.com/hoangle2302)
- 📘 **Facebook**: [@hng.le2](https://www.facebook.com/hng.le2/)
- 📺 **YouTube**: [@lehuyhoang2302](https://www.youtube.com/@lehuyhoang2302)

### 💼 Professional Focus
- **AI & Machine Learning** - Computer Vision, Deep Learning
- **Web Development** - Full-stack development with modern frameworks
- **Cybersecurity** - Security tools and vulnerability assessment
- **Software Engineering** - Clean code, best practices, and scalable solutions

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Font Awesome** - For the beautiful icons
- **Google Fonts** - For the typography
- **Unsplash** - For placeholder images
- **Inspiration** - Modern portfolio design trends

---

<div align="center">
  <h3>⭐ Star this repository if you found it helpful!</h3>
  <p>Made with ❤️ by <a href="https://github.com/hoangle2302">Lê Huy Hoàng</a></p>
  <p><strong>2025 © All rights reserved</strong></p>
</div>