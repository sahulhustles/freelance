# Freelancer Sahul — Personal Portfolio & Services Website 🚀

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-ISC-green.svg)
![Status](https://img.shields.io/badge/status-production--ready-brightgreen.svg)

A high-performance, modern, accessible, and fully responsive freelancer portfolio and multi-service landing application built for **Sahul Hameed** ([sahulhustler.com](https://sahulhustler.com/)). 

Designed to showcase services, handle client order inquiries, provide dedicated detail pages for each service, and deliver top-tier SEO performance.

---

## ✨ Features

- 🌗 **Light / Dark Mode Engine**: Instant visual theme toggle with persistent user preference via `localStorage`.
- ⚡ **Zero-Dependency Frontend**: High-performance layout built with Vanilla HTML5, CSS3 Variables, and ES6+ JavaScript.
- 🎯 **Dedicated Service Landing Pages**:
  - **SEO Portfolio Website Development** ([portfolio-website/](portfolio-website/))
  - **Professional ATS Resume Writing** ([resume-writing/](resume-writing/))
  - **Web Development & Project Assistance** ([web-development/](web-development/))
- 📱 **100% Mobile Responsive**: Customized drawer navigation and adaptive CSS Grid & Flexbox layouts across mobile, tablet, and desktop viewports.
- 📈 **SEO & Structured Data (JSON-LD)**: Rich Schema markup (`Service`, `OfferCatalog`, `LocalBusiness`, `FAQPage`), Google Search Console optimized, with `sitemap.xml` and `robots.txt`.
- 🔒 **Security & Performance**: Custom Netlify header policies (`CSP`, `X-Frame-Options`, `Cache-Control`) for instant caching.
- 📩 **Form Handling**: Integrated Formspree serverless endpoint with asynchronous user feedback and interactive order selection.

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3 (CSS Custom Properties & Grid/Flexbox), JavaScript (ES6+, `IntersectionObserver`, `requestAnimationFrame`)
- **Backend / Web Server (Optional)**: Node.js, Express.js (`server.js`)
- **Typography & Icons**: Inter, Plus Jakarta Sans, SVG Favicons
- **Forms & Integration**: Formspree API, Google Forms
- **Deployment Rules**: Netlify `_headers` & `_redirects`

---

## 📁 Repository Directory Structure

```
freelancer_portfolio/
├── portfolio-website/
│   └── index.html          # SEO Portfolio Website detail & pricing page
├── resume-writing/
│   └── index.html          # ATS Resume Writing detail & pricing page
├── web-development/
│   └── index.html          # Web App & Project Help detail & pricing page
├── index.html              # Main homepage & services portal
├── style.css               # Centralized Design System & CSS theme variables
├── script.js              # Theme engine, mobile menu, counters, scroll animations
├── 404.html                # Custom styled 404 error page
├── server.js               # Express.js server for Node environments
├── manifest.json           # PWA configuration manifest
├── sitemap.xml             # Search engine XML sitemap
├── robots.txt              # Search engine crawler directives
├── _headers                # Security & cache HTTP response headers (Netlify)
├── _redirects              # Clean URL & custom 404 routing rules (Netlify)
├── favicon.svg             # Primary SVG site icon
├── profile.jpeg            # Profile image asset
└── package.json            # Node.js manifest & dependencies
```

---

## 🚀 Quick Start & Local Setup

### Option 1: Static Web Server (VS Code Live Server, etc.)
Simply open `index.html` in any modern web browser or serve via Live Server.

### Option 2: Node.js / Express Server
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/freelancer-portfolio.git
   cd freelancer-portfolio
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm start
   ```
4. Open your browser and navigate to `http://localhost:3000`.

---

## 🌐 Deployment Instructions

### Deploy to Netlify / Vercel / Cloudflare Pages (Recommended)
1. Push your code to GitHub.
2. Connect your GitHub repository to Netlify/Vercel.
3. Leave build settings empty (Static Site) and set Publish Directory to `./`.
4. Deploy! Netlify will automatically detect `_headers` and `_redirects`.

### Deploy to Render / Railway / Heroku
1. Connect your repository.
2. Build command: `npm install`
3. Start command: `npm start` (Runs `node server.js`).

---

## 💼 Services Offered

| Service Track | Basic Plan | Professional / Main Plan | Premium / Executive Plan |
| :--- | :--- | :--- | :--- |
| **SEO Portfolio Website** | ₹999 (1 Page, Free Hosting) | ₹2,999 (Custom Domain, Full SEO) | ₹4,999 (Admin Panel, Blog, Support) |
| **ATS Resume Writing** | ₹299 (ATS Layout, PDF) | ₹599 (Custom Design, PDF + DOCX) | ₹999 (Executive, Cover Letter, LinkedIn) |
| **Web Dev / Project Help** | ₹1,000–3,000 (Mini Projects) | ₹3,000–8,000 (College Projects) | ₹300/hr (Bug Fixing) / ₹500+ (Deployment) |
| **SEO Content Writing** | ₹499 (1 Article / 1k words) | ₹1,499 (3 Articles / Landing Page) | ₹2,999 (5 Articles / Full Content Strategy) |

---

## 👨‍💻 Author

**Sahul Hameed**
- Website: [https://sahulhustler.com](https://sahulhustler.com/)
- Email: [sahulhustler@gmail.com](mailto:sahulhustler@gmail.com)
- Location: Coimbatore, Tamilnadu, India

---

## 📄 License

This project is licensed under the [ISC License](LICENSE).
