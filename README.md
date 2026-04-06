# 🌐 Binit Kumar Karn — Personal Portfolio Website


> A dark-themed, responsive personal portfolio website built with pure **HTML, CSS & JavaScript** — no frameworks, no dependencies.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-f5c542?style=for-the-badge&logo=google-chrome&logoColor=black)]([(https://www.binitkumarkarn.com.np/)])
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/binitkumarkarn-ds/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/binit-kumar-karn-ds))

---

## 👤 About

This is the source code of my personal portfolio website — designed to showcase my skills, experience, and projects as a Data Analyst.

Built entirely from scratch without any CSS framework or JS library (except EmailJS for the contact form), it reflects my attention to detail and passion for clean, functional design.

---

## ✨ Features

- 🎨 **Dark aesthetic** with gold accent theme and grain overlay
- 🖱️ **Custom animated cursor** with smooth ring follow effect
- 📱 **Fully responsive** — mobile hamburger menu included
- 🔢 **Scroll-triggered animations** using IntersectionObserver
- 📊 **Skills, Experience & Projects** sections with smooth reveal
- 📜 **Clickable certification cards** linking to real certificates
- 📬 **Working contact form** powered by EmailJS (no backend needed)
- ♻️ **Auto page refresh** after form submission
- 🔗 **Logo click** reloads the page

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Scripting | Vanilla JavaScript (ES6+) |
| Email | [EmailJS](https://www.emailjs.com/) |
| Icons | [Font Awesome 6](https://fontawesome.com/) |
| Fonts | [Bebas Neue + Outfit](https://fonts.google.com/) — via Google Fonts |

---

## 📁 Project Structure

```
portfolio/
│
├── index.html                        # Main HTML file (entire site)
├── photto.png                        # Profile photo
├── Binit_Kumar_Karn_CV.pdf           # Downloadable CV
│
├── sales-analysis-dashboard.jpg      # Project 1 thumbnail
├── customer-churn-prediction.png     # Project 2 thumbnail
└── chatbot-web-app-development.png   # Project 3 thumbnail
```

> All CSS and JavaScript are embedded directly in `index.html` — no separate files needed.

---

## 🚀 Getting Started

### View locally

```bash
# Clone the repository
git clone: https://github.com/binit-kumar-karn-ds.git

# Navigate into the folder
cd portfolio

# Open in browser (no build step needed)
open index.html
```

Or simply drag and drop `index.html` into any browser.

### Deploy to GitHub Pages

```bash
# Push to main branch
git add .
git commit -m "Deploy portfolio"
git push origin main

# Then enable GitHub Pages in repo Settings → Pages → Source: main / root
```

---

## 📬 Contact Form Setup (EmailJS)

The contact form uses [EmailJS](https://www.emailjs.com/) to send emails without a backend.

To use your own EmailJS account:

1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create a **Service** and note your `Service ID`
3. Create an **Email Template** and note your `Template ID`
4. Copy your **Public Key** from Account settings
5. Update these values in `index.html`:

```js
const CFG = {
  publicKey:  'YOUR_PUBLIC_KEY',
  serviceId:  'YOUR_SERVICE_ID',
  templateId: 'YOUR_TEMPLATE_ID'
};
```

---

## 📌 Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, title, CTA buttons, profile card |
| **About** | Bio, background, and certifications with links |
| **Skills** | 6 skill categories with tech pills |
| **Experience** | Timeline of work history |
| **Projects** | 3 featured projects with GitHub links |
| **Numbers** | Key stats — experience, dashboards, accuracy, NEC |
| **Contact** | Contact links + working EmailJS form |

---

**Binit Kumar Karn**
📧 [Binitkumarkarn1@gmail.com](mailto:Binitkumarkarn1@gmail.com)
📞 +977 9843940897
🔗 [linkedin.com/in/binitkumarkarn-ds](https://www.linkedin.com/in/binitkumarkarn-ds/)
📍 Kathmandu, Nepal

---
