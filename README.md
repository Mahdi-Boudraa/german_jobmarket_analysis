# 🇩🇪 German Job Market Analysis – Power BI | SQL | Python

This project presents a full end-to-end analysis of the German IT job market. It combines data collection, 
cleaning, NLP-based skill extraction, and classification to build a rich, interactive Power BI dashboard. 
The project was developed using Python, SQL, and Power BI, and the final results were also published on Medium.

---

## 🔧 Tools & Technologies Used

- **Power BI** (Dashboards, DAX, data modeling)
- **Python** (pandas, regex, classification, scraping)
- **Jupyter Notebooks** (exploratory cleaning, transformation)
- **SQL** (Data filtering and transformation)
- **Regex & NLP** for job title and skill classification

---

## 📊 Dashboard Preview

![Overview](Dashboard)


👉 **Read full article on Medium:** [How I Built a Job Market Dashboard Using Power BI, SQL, and Python](https://your-medium-link)

---

## 🗂️ Project Structure
```bash
german_jobmarket_analysis/
│
├── Dashboard/
│ └── Power BI/
│ ├── job_analysis.pbix # Power BI report file
│ ├── Overview.png # Dashboard screenshots
│ ├── Job_details.png
│ └── Requirements.png
│
├── Data/
│ ├── clean/
│ │ └── data.csv # Final cleaned dataset
│ └── dirty/
│ └── data.csv # Raw merged dataset
│
├── Processing/
│ ├── Data Cleaning/
│ │ └── Dirty Data/
│ │ ├── stepstone_jobs[...] # Raw scraped StepStone files
│ │ ├── job_postings_classified.csv
│ │ └── temp/
│ └── Notebooks/
│ ├── cleaning.ipynb
│ ├── requirements_extraction.ipynb
│ ├── job_classification.ipynb
│ └── translation.ipynb
│
├── Data Collection/
│ ├── Data/
│ │ └── jobs_with_requirements.csv
│ └── Notebook/
│ └── job_scraping.ipynb # Job scraping script
│
├── Feature-Outliers-Engineering/ # Feature extraction & outlier removal
│
└── README.md
```
---

## 🔍 Key Features

- Collected and merged thousands of job listings from StepStone.de
- Cleaned and standardized messy data (languages, degree titles, remote/onsite tags)
- Extracted required skills and job titles using NLP and regular expressions
- Classified jobs into custom categories: Software Dev, Data, DevOps, etc.
- Created an interactive Power BI dashboard with filters by language, region, skills, and more
- Wrote a Medium article walking through the methodology and findings

If you'd like to collaborate, give feedback, or hire me — feel free to connect:

- 🐙 [GitHub Profile](https://github.com/Mahdi-Boudraa)





