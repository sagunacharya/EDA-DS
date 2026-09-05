# AI JOB MARKET INTELLIGENCE

### An Exploratory Analysis of AI Jobs, Skills, Salaries and Career Trends

A portfolio-quality Python EDA project using a documented real-world AI job-posting dataset to study job roles, experience requirements, salaries, remote work, technical skills, and career signals.

> **Trusted Data → Clean EDA → Strong Questions → Meaningful Visualizations → Career Insight**

## Dataset

**AI Job Market Global 2026**

- **Kaggle:** https://www.kaggle.com/datasets/atharvasoundankar/ai-job-market-global-2026
- **Original collection sources:** Adzuna API and USAJobs API
- **Reported size:** 5,773 job postings
- **Tracked technical skills:** 24
- **License:** CC BY 4.0

The dataset is automatically retrieved at notebook runtime with `kagglehub`. The downloaded CSV is intentionally not included in this repository.

## What the analysis covers

- Dataset structure, data types, missing values and duplicates
- Data cleaning and feature engineering
- Most common AI job roles
- Experience-level composition
- Role vs. experience structure
- Salary distribution and outliers
- Salary vs. experience
- Highest-paying roles
- Salary by location
- On-site vs. hybrid vs. remote work
- Technical skill demand ranking
- Skill co-occurrence
- Entry vs. senior skill demand
- Skill–salary association
- Role demand vs. salary
- Job-description length by experience
- Numeric correlation analysis
- Transparent AI Career Opportunity Score

No deep learning, web application, API service, or unnecessary ML model is included.


## Important Interpretation Notes

Salary analysis uses only postings with disclosed salary information.

Skill counts measure whether a skill is mentioned in a posting; they do not measure proficiency.

Skill–salary relationships are descriptive associations, not causal salary effects.

The Career Opportunity Score is an exploratory index combining demand, observed salary, and entry accessibility. It is not a hiring prediction model or salary prediction model.

## Repository Structure

```text
AI-Job-Market-EDA/
├── notebooks/
│   └── AI_Job_Market_EDA.ipynb
├── visuals/
│   └── important_charts/
├── README.md
├── requirements.txt
└── LICENSE
```

## Technologies

Python · Pandas · NumPy · Matplotlib · Seaborn · KaggleHub · Jupyter/Google Colab

## Attribution

Soundankar, A. (2026). *AI Job Market Global 2026* [Dataset]. Kaggle.  
https://www.kaggle.com/datasets/atharvasoundankar/ai-job-market-global-2026

Dataset license: CC BY 4.0

## Author

**Sagun Acharya**
