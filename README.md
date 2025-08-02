# Samuel Were - Professional Portfolio

![Portfolio Screenshot](./screenshot.png)  
*Modern, responsive portfolio with red/black/gold theme*

## 🌟 Features
- **100% JavaScript-free** - Pure HTML/CSS implementation
- **Fully responsive** - Mobile-first design
- **Modern UI** - Red/black/gold color scheme with smooth animations
- **Performance optimized** - Fast loading with minimal dependencies

## 🎨 Design Specifications
```css
:root {
  --primary: #ff0000;    /* Vibrant red */
  --secondary: #000000;  /* Pure black */
  --accent: #ffcc00;     /* Gold accent */
  --text: #ffffff;       /* White text */
}
📂 File Structure
text
index.html          # Main HTML file (all CSS included internally)
images/             # Image assets
├── profile.jpg     # Profile picture
├── background.jpg  # Background image
README.md           # This documentation
🛠️ How to Customize
1. Update Personal Information
html
<!-- In header section -->
<header>
  <img src="images/your-photo.jpg" alt="Your Name">
  <h1><span class="title-highlight">Your</span> Name</h1>
  <p>Your Profession | Specialty</p>
</header>
2. Modify Projects Section
Edit the projects grid:

html
<div class="project-card">
  <div class="project-image">
    <i class="fas fa-icon-name"></i> <!-- Change icon -->
  </div>
  <div class="project-content">
    <h3>Project Title</h3>
    <p>Project description</p>
    <div class="project-links">
      <a href="#" class="btn"><i class="fas fa-eye"></i> Live Demo</a>
      <a href="#" class="btn-outline"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>
3. Change Color Scheme
Edit the CSS variables:

css
:root {
  --primary: #your-color; 
  --secondary: #your-color;
  --accent: #your-color;
}
🚀 Deployment
Hosted on GitHub Pages:
https://SamWere691.github.io

💡 Technical Highlights
Pure CSS animations: Hover effects, transitions, and keyframe animations

Responsive timeline: Education section with interactive elements

Modern layout: CSS Grid and Flexbox for perfect alignment

Performance: All styling in one file for fast loading

📬 Contact
📧 Email: rxmartin23@gmail.com

📞 Phone: +254 110 385 049

🌐 Live Portfolio: https://samwere691.github.io/portf/

✅ No JavaScript Required
✅ Perfect Lighthouse Scores
✅ Fully Accessible
