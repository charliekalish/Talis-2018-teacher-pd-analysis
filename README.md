# Teacher Professional Development Analysis
**AI-Assisted Data Analysis for Career Transition & Learning**

## Project Purpose

This project serves two purposes:

(1) Showcase ability to analyze survey data and generate actionable insights using AI-powered tools

(2) Create for myself a learning foundation for developing an individualized, AI-scaffolded Python curriculum

## Background

After 10+ years collecting and analyzing data using traditional tools (spreadsheets, pivot tables, formula-driven dashboards), I took a career break during which I made it one my goals to learn Python. Progress was incremental but slow—-until I discovered AI assistants.

I initially started this project to showcase Python skills learned independently. However, I quickly realized AI assistants could dramatically accelerate both coding and learning. This project now serves as a work sample I can use to structure exercises around specific Python skills.

**Learning Roadmap:**

This TALIS 2018 analysis serves as the foundation for a three-phase learning journey:

1. **Deconstruct the methodology** - Work with AI to break down the analysis workflow into discrete learning modules covering data manipulation, transformation, and statistical testing

2. **Build proficiency** - Complete AI-generated lessons, exercises and self-assessments for each module

3. **Demonstrate mastery** - Apply learned skills to independently analyze TALIS 2024 data, including longitudinal comparisons with 2018 baseline

**Goals:** 
Create a sample of work which:
- Demonstrates a proficiency in Python
- Showcases my ability to combine domain expertise in education with new AI tools
- Applies these skills to examining real-world problems

---

## TALIS 2018 Analysis: Teacher Professional Development Gaps

This analysis examines U.S. middle school teacher PD with a specific focus on science teachers:

1. **Overall landscape** - What are the most common PD needs and barriers among all teachers?
2. **Science teacher comparisons** - Do science teachers face different needs and barriers than other subjects? How do these differ by career stage (early-career, mid-career, veteran)?
3. **Critical gaps for science teachers** - Where do high needs meet high barriers for science teachers specifically?

**Sample:** 1,799 middle school teachers (grades 7-9) with complete data

**Key Finding:** Career stage drives different critical gaps for science teachers. Veterans need technology training but lack incentives (28% gap). Early-career teachers need classroom fundamentals but lack time (28% gap).

---

## Project Structure
```
├── notebooks/                          # 3 Jupyter notebooks
│   ├── 01_barriers_analysis.ipynb      # What prevents PD access
│   ├── 02_needs_analysis.ipynb         # What PD teachers need
│   └── 03_integration_analysis.ipynb   # Critical gaps analysis
├── outputs/figures/                    # 10 visualizations
├── executive_summary.md                # One-page summary
└── requirements.txt                    # Python dependencies
```

---

## Visualizations

![Critical Gaps Heatmap](outputs/figures/08_critical_gaps_heatmap.png)
*Need-barrier combinations affecting most teachers*

![Career Stage Comparison](outputs/figures/10_science_teachers_gap_comparison.png)
*Different gaps for veterans (red) vs. early-career (blue)*

---

## Technical Setup
```bash
# Install
pip install -r requirements.txt

# Dependencies
pandas, numpy, plotly, scipy, pyreadstat
```

**Data:** Download [TALIS 2018](https://www.oecd.org/education/talis/) and place in `data/raw/`

**Methodology:** Descriptive statistics, chi-square tests (α=0.05), needs-barriers matrix

---

## About

**Charlie Kalish** | charliekalish@gmail.com | [LinkedIn](https://www.linkedin.com/in/charlie-kalish/)

**Career Transition:** Education, Regulatory compliance → Data analytics  
**Target Roles:** Program Manager, Data Analyst, Operations analyst 

---

**License:** MIT | **Data:** OECD TALIS 2018