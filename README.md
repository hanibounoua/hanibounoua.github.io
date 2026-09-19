# Hani Bounoua — Personal Portfolio & Resume

Welcome to the repository for my personal website and interactive portfolio, hosted on GitHub Pages.

**Live Website:** [https://hnbn313.github.io](https://hnbn313.github.io)

---

## 👨‍💻 About Me

**Data Scientist / Data Mining Expert** based in Algiers, Algeria.
- **Top internal score (90.27%)** for Data Scientist Certified Expert designation.
- Awarded **Best Employee Q1 2026** at Djezzy (Veon Group).
- M.Sc. in Applied Statistics and Probability & B.Sc. in Algebra and Cryptography (USTHB).
- Experienced in large-scale telecom analytics, predictive modeling (churn, customer lifetime value), geospatial analytics, and clinical pharmacometrics.

---

## 🚀 Tech Stack & Skills

- **Languages & Databases:** Python, R, Teradata SQL, SQL Server, Java, C++
- **Data Engineering & Big Data:** PySpark, Polars, pandas, Teradata (FastExport, FastLoad, Macros)
- **Machine Learning & Modeling:** scikit-learn, tidymodels, mlr3, nlmixr2
- **Visualization & Web Apps:** R Shiny, Leaflet, Tableau, Power BI, NodeJS, ExpressJS
- **DevOps & Environments:** GitLab CI/CD, Git, Linux (Fedora, Garuda), Windows 11

---

## 📂 Repository Structure

```text
.
├── index.html        # Main landing page (Hero, About, Skills, Experience, Projects, Contact)
├── resume.tex        # LaTeX source code for the professional resume
├── resume.pdf        # Pre-compiled high-resolution PDF resume
├── css/
│   └── master.css    # Modern responsive styling (dark theme, glassmorphism)
├── javaScript/
│   └── index.js      # Navigation scrollspy & mobile menu drawer script
├── img/              # Profile photos and graphics
└── README.md         # Repository documentation
```

---

## 🛠️ Local Development & Preview

No build tools or complex node dependencies required. You can preview the website locally using any static web server:

```bash
# Clone the repository
git clone https://github.com/hnbn313/hanibounoua.github.io.git
cd hanibounoua.github.io

# Launch a local development server with Python 3
python3 -m http.server 8000
```

Then open your browser and navigate to: `http://localhost:8000`

---

## 📄 Compiling the Resume from Source

If you update [resume.tex](resume.tex), you can recompile [resume.pdf](resume.pdf) using `pdflatex`:

```bash
pdflatex -interaction=nonstopmode resume.tex
# Clean auxiliary files
rm -f resume.aux resume.log resume.out
```

---

## 📬 Contact & Links

- **Email:** [bounoua.hani@gmail.com](mailto:bounoua.hani@gmail.com)
- **Phone:** +213 663 47 99 28
- **GitHub:** [@hnbn313](https://github.com/hnbn313)
- **LinkedIn:** [hanibounoua](https://www.linkedin.com/in/hanibounoua/)

---

&copy; 2026 Hani Bounoua. All rights reserved.