# 👨‍⚕️ Dr. Sai Kumar Koneti – Portfolio Website

Welcome to my personal portfolio site! This site showcases my projects, skills, and work in **health informatics**, **clinical research**, and **data science**. Built using **React**, **Tailwind CSS**, and **Framer Motion**, and deployed on **GitHub Pages** using Vite.

🌐 **Live Site**: [https://Saikoneti-25.github.io/sai-kumar-koneti-portfolio](https://Saikoneti-25.github.io/sai-kumar-koneti-portfolio)

---

## 📁 What's in This Repo

This repository includes:
- Full React + Vite codebase for the portfolio
- TailwindCSS setup
- framer-motion for animation
- A `/dist/` folder to support GitHub Pages deployment
- Deployment-ready configuration

---

## 🧠 About Me

I'm a physician-turned-health informatician completing my Master’s in Health Informatics at George Mason University. My work integrates clinical knowledge with analytics to improve patient outcomes and health systems.

---

## 🚀 Featured Projects

- **Heart Disease Readmission (MIMIC-IV)** – ML model predicting 30-day readmission risk.
- **Depression Treatment Prediction** – LASSO regression on All of Us dataset.
- **FACTORS** – Framework to evaluate AI tools like Synthesia & Sora.
- **Brain Tumor Detection** – CAD system using MATLAB & PyTorch.
- **Dementia Caregiver Education** – GenAI-powered caregiver video modules.
- **Hospital Dashboards** – Tableau dashboards for readmission metrics.

---

## 📂 Work Areas

- 🧪 Graduate Research Assistant (HAP)
- 💻 MSHI Projects
- 📊 Parexel Internship
- 🛠️ Independent Projects

---

## 💾 Tech Stack

- ⚛️ React + Vite
- 🎨 Tailwind CSS
- 🎞️ Framer Motion
- 📊 Tableau, SQL, Python, R
- 🔗 HL7 FHIR, SNOMED CT, ICD-10
- ☁️ GitHub Pages (for deployment)

---

## 🛠️ How to Use This Repo (Beginner Friendly)

### ✅ Step 1: Install Everything

```bash
npm install
```

### ✅ Step 2: Build the Portfolio Website

```bash
npm run build
```

This creates a `dist/` folder with your production-ready website.

### ✅ Step 3: Deploy to GitHub Pages

```bash
npm install gh-pages --save-dev
```

Update your `package.json`:

```json
"homepage": "https://Saikoneti-25.github.io/sai-kumar-koneti-portfolio",
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

Then deploy:

```bash
npm run deploy
```

---

## 🌍 Or Use Manual Upload Method

1. Build your site using `npm run build`
2. Go to GitHub → Your Repo
3. Click **Add file → Create new file**
4. Name the file: `dist/index.html`
5. Paste your HTML content or use the template
6. Commit directly to the `main` branch

Then go to:
**Settings → Pages → Source → `main` branch, `/dist` folder**

Your site will be live at:

```
https://Saikoneti-25.github.io/sai-kumar-koneti-portfolio
```

---

## 📫 Contact

- 📧 Email: [konetisaikumar27@gmail.com](mailto:konetisaikumar27@gmail.com)
- 🔗 LinkedIn: [dr-sai-kumar-5142a4226](https://www.linkedin.com/in/dr-sai-kumar-5142a4226/)

---

> 🧭 “Empowering clinical decisions and healthcare equity through data-driven solutions.”
