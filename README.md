# 🚀 Yash Padme - Portfolio Website

A modern, responsive portfolio website showcasing professional experience, projects, certifications, achievements, and skills in Full Stack Development and Data Analytics.

**Live Demo:** [https://yash-padme.github.io/Portfolio/](https://yash-padme.github.io/Portfolio/)

---

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Sections](#project-sections)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contact](#contact)
- [License](#license)

---

## ✨ Features

- ✅ **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Smooth Scrolling Navigation** - Smooth anchor link navigation with header offset
- ✅ **Interactive Elements** - Animated cards, social media hover effects, and particle animations
- ✅ **Mobile Menu Toggle** - Hamburger menu for mobile navigation
- ✅ **Contact Form** - Integrated contact form with Formspree backend
- ✅ **Lazy Loading** - Optimized performance with intersection observer
- ✅ **Accessibility** - ARIA labels and semantic HTML for better accessibility
- ✅ **Social Media Integration** - Links to GitHub, LinkedIn, Instagram, LeetCode, and Email
- ✅ **Project Showcase** - Display of 9 projects across AI/ML, Analytics, and Development categories with filter buttons
- ✅ **Certifications Display** - Professional certifications with verification links
- ✅ **Experience Section** - Highlights of professional and leadership experience
- ✅ **Achievements Section** - Hackathons, competitions, and recognitions

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Icons:** Font Awesome 6.4.0
- **Form Backend:** Formspree
- **Animations:** CSS3 Animations, JavaScript Intersection Observer
- **Version Control:** Git & GitHub

---

## 📑 Project Sections

### 1. **Header Navigation**

- Logo and branding
- Responsive navigation menu with links to Home, About, Experiences, Achievements, Projects, Certificates, and Contact
- Mobile hamburger menu with toggle functionality

### 2. **Hero Section**

- Personalized greeting with animated title
- Professional summary
- Call-to-action buttons (View & Download Resume)
- Social media links (GitHub, LeetCode, LinkedIn, Instagram, Email)
- Profile image
- Animated particle background

### 3. **About Section**

- Personal bio and professional goals
- **Skills Showcase:**
  - Programming & Query Languages (Python, C++, SQL, HTML, JavaScript)
  - Machine Learning & Data Science (Pandas, NumPy, Scikit-learn, Seaborn, TensorFlow, PyTorch, Statistics, Regression, Forecasting, A/B Testing)
  - Web Technologies (React.js, Next.js, Node.js, Express.js, Tailwind CSS)
  - Databases & Backend (MySQL, PostgreSQL, MongoDB, Firebase, REST APIs, Database Normalization)
  - Cloud, Platforms & Concepts (AWS (EC2, S3), Google Cloud Platform, Docker, Git, ETL, Data Warehousing, Feature Engineering, Agile Methodology)

### 4. **Experience Section**

- **Technical Team Member** – Uthaan Club, ABV-IIITM Gwalior (2024)
  - Managed and maintained automation tools and event management platforms
  - Optimized internal workflows, achieving a 30% improvement in operational efficiency
- **Team Lead – Case Study Competition** – Infotsav 2024
  - Led a team of 6 members for a large-scale case study competition
  - Handled logistics and coordination for 500+ participants

### 5. **Achievements Section**

- **Adobe India Hackathon – Round 1** (2025) – Certificate of Participation (Online MCQ Assessment + Coding)
- **TVS Credit EPIC 7.0 – Strategy Challenge** (September 2025) – Certificate of Participation
- **CodeClash: The August Arena** (August 2025) – Certificate of Excellence, Ranked 528th in Foundations Round

### 6. **Projects Section**

Projects are filterable by category: All Projects, Development, Analytics, AI/ML, Case Studies.

- **Forest Fire Prediction** (AI/ML) – ML regression project using Algerian Forest Fire dataset with Linear, Lasso, Ridge, and Elastic Net models
- **Chartify** (Analytics) – Data visualization techniques with Matplotlib and Seaborn
- **NumPy-Essentials** (Development) – NumPy fundamentals, array operations, and performance comparisons
- **Pandas-Essentials** (Analytics) – Pandas data manipulation and analysis via Jupyter Notebooks
- **KrushiRaah** (AI/ML) – AI-powered agriculture web app for SIH 2025 with crop recommendations and disease detection
- **SmartSocialRecommender** (AI/ML) – Python-based social network recommendation system
- **E-Tailing Customer Segmentation** (Analytics) – ML-based customer segmentation for e-commerce data
- **CRS Credit Risk Scorecard** (Analytics) – Predictive credit risk models with feature engineering and validation ([Live App](https://crs-credit-risk-scorecard-project-yashpadme.streamlit.app/))
- **Vendor Performance & Profitability Analysis** (Analytics) – Vendor KPI tracking, comparative analysis, and business insights

### 7. **Certificates Section**

- **Software Engineering Job Simulation** – Forage (Issued: October 2025)
- **Data Visualisation: Empowering Business with Effective Insights** – Forage (Issued: March 2025)
- **0–1 MERN Full Stack Web Development** – 100xDevs (Completed: June 2024)
- **Alpha: DSA with C++** – Apna College (Issued: 2024)

### 8. **Contact Section**

- Contact information and location
- Functional contact form (Formspree)
- Social media links
- Call-to-action for internships, full-time roles, freelance projects, and collaborations

### 9. **Footer**

- Copyright information

---

## 🚀 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Yash-Padme/Portfolio.git
   cd Portfolio
   ```

2. **Open in Browser**
   - Double-click `index.html` or
   - Use a local server:
     ```bash
     python -m http.server 8000
     # or
     npx serve
     ```
   - Navigate to `http://localhost:8000`

---

## 📖 Usage

### Customization

1. **Update Personal Information**
   - Edit name, titles, and bio in `index.html`
   - Update social media links
   - Replace profile image in `images/` folder

2. **Modify Experience**
   - Edit experience cards in the Experience section
   - Update roles, companies, dates, and bullet points

3. **Modify Projects**
   - Edit project cards in the Projects section
   - Update demo links and GitHub repositories
   - Update the `data-category` attribute to control filter visibility
   - Add/remove project cards as needed

4. **Update Certifications**
   - Add new certification cards in the Certificates section
   - Update credential links and dates
   - Replace certificate images in `images/` folder

5. **Customize Styling**
   - Edit colors, fonts, and layouts in `styles.css`
   - Modify CSS custom properties (variables) at the root

6. **Add New Features**
   - Extend JavaScript in `script.js`
   - Add new sections with corresponding HTML markup
   - Update navigation links

---

## 📁 File Structure

```
Portfolio/
├── index.html              # Main HTML file
├── styles.css              # CSS styling
├── script.js               # JavaScript functionality
├── README.md               # Project documentation
├── .gitignore              # Git ignore rules
└── images/                 # Image assets
    ├── yash.jpg            # Profile picture
    ├── resume.pdf          # Resume PDF
    ├── ForestFirePrediction.jpg
    ├── NUMPY3.png
    ├── Pandas.png
    ├── KrushiRaah.png
    ├── social.jpg
    ├── project2.jpg
    ├── Forage_Software_Engineering.jpg
    ├── Forage_Data_Visualisation.jpg
    ├── 100xDevs_MERN_Certificate.png
    ├── ApnaCollege_Alpha_DSA.jpg
    ├── AdobeHackathon.png
    ├── TVSCreditEPIC7.png
    ├── CodeClash_Certificate.pdf
    ├── r1.png, g1.png, b1.png, y1.png  # Skill card backgrounds
    └── ... (other project and certificate images)
```

---

## 🎯 Key JavaScript Functions

- **Smooth Scrolling:** `DOMContentLoaded` event listener with smooth scroll behavior
- **Header Scroll Effect:** Dynamic header styling on scroll
- **Intersection Observer:** Section animations on scroll
- **Mobile Menu Toggle:** Responsive navigation with click handlers
- **Project Filtering:** Filter buttons to display projects by category (All, Development, Analytics, AI/ML, Case Studies)
- **Social Links Animation:** Hover effects on social media icons
- **Form Submission:** Formspree integration for contact form
- **Particle Animation:** Animated background particles in hero section

---

## 📱 Responsive Design

- **Desktop:** Full navigation, multi-column layouts
- **Tablet:** Optimized spacing, medium breakpoints
- **Mobile:** Hamburger menu, single-column layouts, touch-friendly buttons

---

## 🌐 Contact & Social Links

- **Email:** [yashpadme13@gmail.com](mailto:yashpadme13@gmail.com)
- **GitHub:** [Yash-Padme](https://github.com/Yash-Padme)
- **LinkedIn:** [yashpadme](https://linkedin.com/in/yashpadme)
- **LeetCode:** [yash_padme](https://leetcode.com/u/yash_padme/)
- **Instagram:** [@yash_padme11](https://www.instagram.com/yash_padme11)
- **Location:** Burhanpur (450331), Madhya Pradesh, India

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Yash Padme

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🎨 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## 🚀 Future Enhancements

- [ ] Dark/Light theme toggle
- [ ] Blog section for articles
- [ ] GitHub API integration for live projects
- [ ] SEO meta tags enhancement
- [ ] Analytics integration

---

## 📞 Support

For issues, questions, or suggestions, please reach out via:

- Email: yashpadme13@gmail.com
- GitHub Issues: [Create an issue](https://github.com/Yash-Padme/Portfolio/issues)

---

## ⭐ Show Your Support

If you found this portfolio helpful or inspiring, please consider giving it a star! ⭐

---

**Last Updated:** March 2026

**Status:** Active & Maintained ✅
