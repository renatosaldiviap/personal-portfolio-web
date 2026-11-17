# 🌐 Data Analytics & BI Portfolio Web | Astro

![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)

## 📌 Project Overview

Personal portfolio website built with **Astro** to showcase end-to-end **Data Analytics, Business Intelligence (SQL, Power BI, GCP)**, and **Machine Learning** projects with ultra-fast static performance and clean responsive design.

🔗 **Live Portfolio:** [renatosaldiviap.github.io/personal-portfolio-web](https://renatosaldiviap.github.io/personal-portfolio-web/)

## 🛠️ Tech Stack & Architecture

- **Framework:** [Astro](https://astro.build/) (Static Site Generation with zero-JS overhead by default).
- **Languages:** Astro components, TypeScript / JavaScript (ES6+), and modular CSS3.
- **Deployment & CI/CD:** Automated build and hosting via **GitHub Pages**.

```text
[ Astro Components & Pages ] ──► [ Static Build (dist/) ] ──► [ GitHub Pages Hosting ]
```

## 🚀 Featured Projects Showcased
- Apex Logistics (GCP + Power BI): End-to-end cloud pipeline (GCS, BigQuery, Kimball Star Schema) analyzing delivery delays, customer churn, and MRR exposure.
- Digital Health & Workplace Productivity (Power BI): Interactive dashboard evaluating screen exposure, stress levels, and burnout thresholds across 3,500 records using DAX.
- Gaming Habits & Mental Health (Python EDA): Large-scale statistical auditing and behavioral correlation analysis across a 10M-record dataset.
- Rainfall Prediction in Australia (ML / CRISP-DM): End-to-end classification pipeline with Scikit-Learn and LightGBM under class imbalance.

## 📁 Project Structure
```text
├── public/          # Static assets (images, icons, downloadable ATS CV)
├── src/
│   ├── components/  # Reusable UI components (Project cards, Hero, Skills)
│   ├── layouts/     # Base page layout structure
│   └── pages/       # Routing and main views (index.astro)
├── astro.config.mjs # Astro configuration & GitHub Pages base path
└── package.json     # Project scripts and dependencies
```

## 💻 Getting Started Locally
1. Clone the repository:
```bash
git clone https://github.com/renatosaldiviap/personal-portfolio-web.git
```
2. Install dependencies:
```bash
git clone https://github.com/renatosaldiviap/personal-portfolio-web.git
```
3. Start the local development server:
```bash
npm run dev
```
4. Build for production:
```bash
npm run build
```
