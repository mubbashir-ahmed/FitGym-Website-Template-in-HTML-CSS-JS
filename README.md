# FitGym Website Template

A modern, responsive one-page website template designed for fitness gyms and health clubs. Built with HTML, CSS, and JavaScript, this template features smooth animations, interactive elements, and a clean, professional design.

![FitGym](https://img.shields.io/badge/Version-1.0-brightgreen) ![HTML5](https://img.shields.io/badge/HTML-5-orange) ![CSS3](https://img.shields.io/badge/CSS-3-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow) ![Bootstrap](https://img.shields.io/badge/Bootstrap-4.x-purple)

## 🌟 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling Navigation** - Easy navigation between sections with smooth scroll effects
- **Animated Preloader** - Professional loading animation with slide transitions
- **Interactive Trainer Cards** - Hover effects revealing trainer information and social links
- **Contact Form** - Integrated contact form for user inquiries
- **Google Maps Integration** - Embedded map showing gym location
- **Newsletter Subscription** - Footer newsletter signup section
- **Social Media Links** - Connected social media icons (Facebook, Twitter, Instagram, RSS)
- **Scroll-to-Top Button** - Quick navigation back to the top of the page
- **AOS (Animate On Scroll)** - Beautiful scroll animations throughout the page
- **Font Awesome Icons** - Professional icon library integration
- **SEO Optimized** - Proper meta tags and semantic HTML structure

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with animations and transitions
- **JavaScript (ES6)** - Interactive functionality
- **Bootstrap 4.x** - Responsive grid system and components
- **Font Awesome 5.13.0** - Icon library
- **Google Fonts** - Open Sans font family
- **AOS Library** - Animate On Scroll effects
- **jQuery 3.5.1** - DOM manipulation and event handling

## 📋 Sections Overview

### 1. **Home Section**
- Eye-catching hero section with motivational tagline
- "Turn Fat into Fit" headline with animated text
- Call-to-action button for e-Brochure download
- Animated mouse scroll indicator

### 2. **About Us Section**
- Company introduction and mission statement
- Detailed description of gym facilities and philosophy
- Responsive layout with text content

### 3. **Services Section**
- 7 service cards showcasing different training programs:
  - General Training Programme
  - Personal Training Programme
  - Muscle & Weight Programme
  - Belly Fat Exercise Programme
  - Cardio Exercise Programme
  - Group Exercise Programme
  - Dieting Plans & Programme
- Each card features an image and description

### 4. **Trainers Section**
- 4 professional trainer profiles:
  - Nathan Harvey - Gym Instructor
  - Mason Wright - Weight Instructor
  - Ruby Cooper - Gym Instructor
  - Isabella Mills - Yoga and Aerobic Instructor
- Interactive hover effects revealing social media links
- Professional trainer photos

### 5. **Contact Us Section**
- Contact form with fields for:
  - Name
  - Email
  - Phone Number
  - Message
- Google Maps integration showing gym location
- Phone number display
- Submit button with icon

### 6. **Footer Section**
- Newsletter subscription form
- Contact information (address, email, phone)
- Social media links (Facebook, Twitter, Instagram, RSS)
- Copyright information
- Responsive multi-column layout

## 📁 File Structure

```
FitGym-Website-Template-in-HTML-CSS-JS/
│
├── index.html                 # Main HTML file
├── README.md                  # Project documentation
│
└── assets/
    ├── css/
    │   ├── bootstrap.css      # Bootstrap framework
    │   └── defaultcss.css     # Custom styles
    │
    ├── js/
    │   ├── jQuery3.5.1.js     # jQuery library
    │   ├── bootstrap.js       # Bootstrap JavaScript
    │   ├── aos.js             # Animate On Scroll library
    │   ├── defaultjs.js       # Custom JavaScript
    │   └── popperjs/
    │       └── popper.js      # Popper.js for Bootstrap
    │
    ├── fa-free5.13.0/         # Font Awesome 5.13.0
    │   ├── css/
    │   └── js/
    │
    ├── icons/                 # Favicon and app icons
    │   ├── favicon.svg
    │   └── apple-touch-icon-*.svg
    │
    ├── imgs/                  # Images for services and trainers
    │   ├── services1-7.jpg
    │   └── gymtrainer1-4.jpg
    │
    └── licenses/              # License files
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, Atom, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/mubbashir-ahmed/FitGym-Website-Template-in-HTML-CSS-JS.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd FitGym-Website-Template-in-HTML-CSS-JS
   ```

3. **Open in Browser**
   - Simply open `index.html` in your web browser
   - Or use a local development server (recommended):
     ```bash
     npx http-server
     ```

4. **View the Website**
   - Open your browser and navigate to `http://localhost:8000`

## 🎨 Customization Guide

### Changing Colors
Edit `assets/css/defaultcss.css` to modify the color scheme. Look for color values and replace them with your brand colors.

### Updating Content
- **Text Content**: Edit the HTML content directly in `index.html`
- **Images**: Replace images in `assets/imgs/` with your own (maintain same dimensions for best results)
- **Logo**: Modify the navbar brand section in `index.html` (line 44)

### Modifying Services
Add or remove service cards in the Services section (lines 116-170 in `index.html`). Follow the existing card structure.

### Adding/Removing Trainers
Edit the Trainers section (lines 185-243) to add or remove trainer profiles. Each trainer requires:
- Profile image
- Name and title
- Social media links

### Google Maps Location
Replace the Google Maps embed URL (line 262) with your gym's location:
1. Go to Google Maps
2. Search for your location
3. Click "Share" → "Embed a map"
4. Copy the iframe code and replace the existing one

### Contact Information
Update contact details in:
- Contact section phone number (line 257)
- Footer contact info (line 309)
- Newsletter email handler (add backend processing)

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)
- ⚠️ Internet Explorer 11 (limited support)

## 📄 License

This project is open source and available for personal and commercial use. Please check the `assets/licenses/` directory for third-party library licenses.

## 👨‍💻 Author

**Mubbashir Ahmed**
- GitHub: [@mubbashir-ahmed](https://github.com/mubbashir-ahmed)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

## 📝 Notes

- The contact form requires backend integration for actual email functionality
- Newsletter subscription needs backend API integration
- Social media links are placeholders and should be updated with actual URLs
- Replace placeholder text (Lorem ipsum) with actual content
- Update Google Maps location to your actual gym address

---

**Made with ❤️ for the fitness community**
