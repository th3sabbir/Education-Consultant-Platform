# TopNotch Education Consultancy Website

[![Live Website](https://img.shields.io/badge/Live-Website-brightgreen)](https://topnotcheducationbd.com)
[![PHP](https://img.shields.io/badge/PHP-7.0+-blue)](https://www.php.net/)

A comprehensive, modern web platform for TopNotch Education, a leading study abroad consultancy. This project provides students with expert guidance, program information, and end-to-end support for international education opportunities.

> 🌍 **My First Paid Client Project** - Turning dreams into reality! This marks a significant milestone in my web development journey.

## 🌟 Features

### Core Functionality

- **Dynamic Homepage**: Interactive hero slider with animated elements, quick search form, and featured content
- **Smart Program Search**: Advanced filtering by country, field of study, and education level with real-time availability hints
- **Program Details**: Comprehensive individual program pages with detailed overviews, career prospects, and application guidance
- **Country-Specific Pages**: Dedicated pages for major study destinations (Australia, UK, USA, Malaysia, New Zealand, Italy, Cyprus)
- **Blog System**: Full-featured blog with detailed articles, categories, and social sharing capabilities
- **Contact Integration**: AJAX-powered contact form with real-time feedback and validation using PHPMailer for secure email delivery

### User Experience

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: AOS-powered scroll animations and interactive elements throughout
- **Modern UI**: Clean, professional design with gradient effects and hover animations
- **Accessibility**: Semantic HTML, proper alt texts, and keyboard navigation support

### Content Management

- **Modular Architecture**: PHP includes for header, footer, and reusable components
- **Dynamic Data**: Program listings, testimonials, and blog posts loaded from backend functions
- **SEO Optimized**: Proper meta tags, structured content, and clean URLs

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Backend** | PHP 7+ with modular includes |
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **Libraries** | Swiper.js, AOS, Font Awesome, jQuery |
| **Email** | PHPMailer for secure email delivery |
| **Styling** | Custom CSS with responsive breakpoints |
| **Fonts** | Google Fonts (Poppins, Inter, Montserrat) |

## 🚀 Getting Started

### Prerequisites

- PHP 7.0 or higher
- Apache/Nginx web server
- MySQL database (optional, for dynamic content)
- PHPMailer library (for email functionality)


## 📁 Project Structure

```
education_consultant/
├── index.php                   # Homepage
├── about.php                   # About Us page
├── apply-now.php               # Application form page
├── search.php                  # Program search page
├── program-detail.php          # Individual program details
├── programs.php                # All programs listing
├── blog.php                    # Blog listing
├── blog-detail.php             # Individual blog posts
├── career-counseling.php       # Career counseling service page
├── contact.php                 # Contact page
├── services.php                # Services overview page
├── career-counseling.php       # Career counseling service page
├── university-selection.php    # University selection service page
├── application-assistance.php  # Application assistance service page
├── visa-processing.php         # Visa guidance service page
├── ielts-preparation.php       # Test preparation service page
└── pre-departure-support.php   # Pre-departure support service page
├── sitemap.php                 # Site navigation sitemap
├── privacy-policy.php          # Privacy policy and data protection information
├── terms-of-service.php        # Terms and conditions for using the website
├── refund-policy.php           # Refund and cancellation policy
├── destinations.php            # All destinations overview page
├── australia.php               # Country-specific pages
├── uk.php
├── usa.php
├── malaysia.php
├── newzealand.php
├── italy.php
├── cyprus.php
├── subscribe.php               # Subscribe form handler (uses PHPMailer)
├── sendmail.php                # Mail form handler (uses PHPMailer)
├── sendmessage.php             # Contact form handler (uses PHPMailer)
├── sendappointment.php         # Appointment form handler (uses PHPMailer)
├── assets/
│   ├── css/
│   │   ├── style.css           # Main stylesheet
│   │   └── hero-mobile.css     # Mobile-specific hero styles
│   ├── images/                 # All website images and assets
│   └── js/
│       └── main.js             # Main JavaScript file
├── PHPMailer/
│   ├── PHPMailer.php           # Main PHPMailer class
│   ├── SMTP.php                # SMTP mailer class
│   ├── Exception.php           # Exception handler class
├── config/                     # Configuration files and settings
├── database/                   # Database connection and schema files
├── includes/
│   ├── footer.php              # Site footer component
│   ├── functions.php           # Utility functions and data handlers
│   ├── header.php              # Site header and navigation
│   └── init.php                # Initialization and configuration
└── site-data.php               # Site configuration and settings
```

## 🎯 Usage

### For Students

- Use the quick search form to find programs by country, field, and level
- Browse destination pages for country-specific information
- Read blog articles for study abroad tips and guidance
- Contact consultants through the integrated contact form (emails sent via PHPMailer)

### For Administrators

- Update content in `site-data.php` and related files
- Modify program data in `includes/functions.php`
- Customize styling in `assets/css/style.css`
- Configure PHPMailer settings for email delivery

## 👨‍💻 Author

**Your Name**

- GitHub: [@th3sabbir](https://github.com/th3sabbir)
- LinkedIn: [Sabbir Ahmed](https://linkedin.com/in/th3sabbir)
- Website: [Portfolio](https://sabbirahmed.online)

## 🎉 Acknowledgments

This project marks my first paid client work as a web developer, representing a significant milestone in my career. It showcases my ability to build comprehensive, user-friendly websites that solve real-world problems. I'm proud to have contributed to helping students achieve their study abroad goals through this platform.

---

<div align="center">
  <strong>Built with passion and dedication</strong>
  <br>
  Transforming ideas into digital experiences 🌟
</div>
