# 📊 Collecting Job Data Using APIs

This project is part of **Module 1** of the **IBM Data Analyst Capstone**, which also is part of the main course [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst). 
It demonstrates how to collect, analyze, and visualize job market data using an open-access **Jobs API**, focusing on **technology-specific demand** across various cities.

---

## 🎯 Project Objectives

- Use HTTP APIs to fetch real-world job listings
- Extract structured data from JSON format
- Build reusable functions for data collection
- Analyze demand by **technology** and **city**
- Visualize job trends using Python charts
- Interpret results to identify **in-demand skills**

---

## 🧪 Tools & Technologies

- Python (Jupyter Notebook)
- `requests` (API consumption)
- `pandas` (data processing)
- `matplotlib` (visualizations)
- JSON handling
- Git + GitHub for publishing

---

## 📂 Project Structure

```plaintext
ibm-capstone-data-analyst/
└── module-1-real-world-projects/
    └── job-data-api-project/
        ├── data/
        ├── notebooks/
        │   └── job_data_api_project_enhanced.ipynb
        ├── visuals/
        │   ├── python_job_listings_by_city.png
        │   ├── total_job_listings_by_city.png
        │   └── top_15_job_titles_chart.png
        ├── dashboard/               # optional exports
        └── README.md


---
## 📈 Key Functional Highlights

- `get_number_of_jobs_T(technology)`
- `get_number_of_jobs_T_L(technology, locations)`
- `get_number_of_jobs_L(location)`
- `get_number_of_jobs_multiple_locations(locations)`

Each function includes printed results and visual outputs for clarity and interpretation.

---

## 📊 Sample Insights

- Python job demand is highest in **Washington DC (258 jobs)**, followed by **Detroit (170)** and **New York (143)**.
- Overall job volume is largest in **Washington DC (5316 total jobs)** and **Detroit (3945 jobs)**.
- Most frequent job titles include **Sales Executive**, **PHP Developer**, and **Business Development Executive**.

---

## 🧩 Dataset Source

This project uses a publicly hosted dataset provided by IBM via the Coursera Labs environment.

**Source URL:**  
[https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%201/Accessing%20Data%20Using%20APIs/jobs.json](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/labs/module%201/Accessing%20Data%20Using%20APIs/jobs.json)

📌 The dataset contains synthetic job posting data intended for educational and analytical purposes.

---

## 🖥️ Dashboard Notebook

Explore the full project with visuals and insights via the hosted dashboard:

[![View Dashboard](https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge&logo=plotly)](https://kelechiede.github.io/Project_1_Data-Collection-using-APIs/dashboard/Collecting_job_data_using_APIs-Lab.html)
- 📄 [Download as PDF](dashboard/Collecting_job_data_using_APIs-Lab.pdf)

> 💡 This notebook includes bar charts, job demand visualizations, and clean API data analysis — best viewed on a desktop browser.

---

- 📁 **Original Jupyter Notebook**: `notebooks/Collecting_job_data_using_APIs-Lab.ipynb`
- 📄 **Static HTML Version**: [`Collecting_job_data_using_APIs-Lab.html`](https://kelechiede.github.io/Project_1_Data-Collection-using-APIs/dashboard/Collecting_job_data_using_APIs-Lab.html)


---

## 📜 Certification

[![IBM Certificate Thumbnail](certification/ibm-data-visualization-thumbnail.png)](https://www.coursera.org/account/accomplishments/verify/ARTLBRAPJ68Q)

> [Verify Capstone Certificate on Credly](https://www.credly.com/badges/259d69a8-bd52-47fb-b02e-19947b158dc6/public_url)

---

## 🧑‍💼 Author

**Kelechukwu Innocent Ede**  
IBM Certified Data Analyst  
🔗 GitHub: [@Kelechiede](https://github.com/Kelechiede)  
🔗 LinkedIn: [Kelechukwu Innocent Ede](https://www.linkedin.com/in/kelechukwu-innocent-ede-b448aa134/)  
📧 Email: kelechukwuede@gmail.com
