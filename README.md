# NOIR Fashion Store - Deployed on Azure App Service

![Azure](https://img.shields.io/badge/Azure-App%20Service-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Project Overview

**NOIR** is a modern, fully responsive fashion e-commerce website deployed live on **Microsoft Azure App Service** using an automated **CI/CD pipeline with GitHub Actions**.

The project demonstrates how to host a static web application on Azure and automate deployments — every push to the `main` branch automatically triggers a build and deploys the latest version to the cloud. No manual steps required.

---

## 🌐 Live Demo

> Deployed on Microsoft Azure App Service
> *(Add your Azure App Service URL here)*

---

## 🖼️ Screenshots

> *(Add screenshots of the live website, GitHub Actions workflow, and Azure dashboard here)*

---

## ✨ Website Features

| Feature | Description |
|---|---|
| 🎠 Hero Carousel | Auto-rotating image slider with 3 fashion model images |
| 👗 Collections Grid | Filterable product cards — Women, Men, Accessories, Limited Edition |
| ⭐ Testimonials | Customer reviews section with star ratings |
| 📬 Contact Form | Full contact form with name, email, subject, and message fields |
| 🗺️ Google Maps | Embedded store location map |
| 📱 Responsive Design | Fully mobile-friendly with hamburger navigation |
| 🌙 Dark Aesthetic | Noir-themed dark UI with pink accent colors |

---

## 🏗️ Project Structure

```
Azure-App-Service-/
│
├── .github/
│   └── workflows/
│       └── main_priya-fashion-store.yml   # GitHub Actions CI/CD pipeline
│
├── images/                                # All website images (.avif format)
│   ├── noir-fashion-hero-01.avif
│   ├── noir-fashion-hero-02.avif
│   ├── noir-fashion-hero-03.avif
│   ├── urban-edge.avif
│   ├── midnight-luxe.avif
│   └── ...
│
├── index.html                             # Main HTML file
├── templatemo-noir-fashion.css            # Stylesheet
└── templatemo-noir-scripts.js             # JavaScript logic
```

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Cloud Platform:** Microsoft Azure App Service
- **CI/CD:** GitHub Actions
- **Version Control:** Git & GitHub

---

## ⚙️ CI/CD Pipeline — How It Works

The deployment pipeline is configured using **GitHub Actions** (`.github/workflows/`).

```
Developer pushes code to GitHub (main branch)
        ↓
GitHub Actions workflow is triggered automatically
        ↓
Azure App Service pulls the latest code
        ↓
Website goes live — zero manual deployment needed ✅
```

**Workflow steps:**
1. Triggered on every push to the `main` branch
2. Checks out the latest code
3. Deploys directly to Azure App Service
4. Live site updates within seconds

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/PRIIII17/Azure-App-Service-.git
   cd Azure-App-Service-
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```
   > No build tools or dependencies required — it's pure HTML, CSS, and JS!

---

## ☁️ How to Deploy on Azure App Service

1. **Create an Azure App Service** in the [Azure Portal](https://portal.azure.com)
   - Choose: **Web App** → Runtime: **Static HTML**

2. **Set up GitHub Actions deployment**
   - In Azure Portal → Your App → Deployment Center
   - Connect your GitHub repo and branch (`main`)
   - Azure auto-generates the workflow YAML file

3. **Push your code**
   ```bash
   git add .
   git commit -m "Deploy to Azure"
   git push origin main
   ```
   The pipeline runs automatically and your site goes live! 🎉

---

## 📚 What I Learned

- ✅ Hosting a web application on **Microsoft Azure App Service**
- ✅ Setting up **automated CI/CD pipelines** with GitHub Actions
- ✅ Understanding the **push → build → deploy** DevOps workflow
- ✅ Working with **Azure Portal** and deployment configurations
- ✅ Real-world cloud deployment experience

---

## 🙋‍♀️ Author

**Pahulpreet** — [@PRIIII17](https://github.com/PRIIII17)

---

## 📄 License

This project uses the [TemplateMo Noir Fashion](https://templatemo.com/tm-599-noir-fashion) template.
Images sourced from [Unsplash](https://unsplash.com).
