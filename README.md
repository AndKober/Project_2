# **SQL Analysis of Job Market Data – HeadHunter Case Study**  

📌 **GitHub Repository:** [Project Link](https://github.com/AndKober/Project_2/blob/master/Project_2.ipynb)  

## **Table of Contents**  
1. [Project Overview](#project-overview)  
2. [Business Context](#business-context)  
3. [Dataset](#dataset)  
4. [SQL Queries & Data Analysis](#sql-queries--data-analysis)  
5. [Key Findings](#key-findings)  
6. [Conclusions & Recommendations](#conclusions--recommendations)  

## **Project Overview**  
This **educational project** focuses on **analyzing job market trends** using SQL queries in **PostgreSQL**.  
The dataset is sourced from **HeadHunter**, a job search platform, and contains job postings, employer data, and salary details.  
The goal is to identify **key hiring trends, salary distributions, and demand for IT specialists**.  

## **Business Context**  
A data-driven approach to job market analysis helps:  
- **Job seekers** understand salary expectations and required skills.  
- **Recruiters** identify hiring trends and competition in specific regions.  
- **Data Scientists** develop **job recommendation models** based on structured data.  

## **Dataset**  
- **49,197 job listings** from **23,501 employers** across **1,362 regions**.  
- Only **1,771 vacancies (3.6%)** are related to **Data Science** roles.  
- **3,553 employers (15%)** specialize in **software development**, indicating strong demand for IT professionals.  
- Data is stored in a **relational PostgreSQL database** with multiple interconnected tables:  

![](scheme.png)  

## **SQL Queries & Data Analysis**  
Key SQL queries used in this project:  
- **Vacancy count analysis:** Total number of job postings.  
- **Salary distribution:** Identifying salary trends by region and experience level.  
- **Employer insights:** Most active companies hiring IT professionals.  
- **Remote work trends:** Evaluating salary differences between office-based and remote positions.  
- **Job market segmentation:** Demand for skills based on job titles.  

## **Key Findings**  
- **Mid-to-senior IT specialists are in highest demand.**  
- **Salary ranges vary significantly depending on employer size and location.**  
- **Only 2.8% of DS job postings** are open to **candidates without experience**, confirming a **high entry barrier**.  
- **Remote work with full-time employment** offers **higher salaries on average** than office-based positions.  
- **Certain regions (e.g., capital cities) have a much higher concentration of IT job openings.**  

## **Conclusions & Recommendations**  
- This dataset provides **valuable insights into the job market**, supporting better career decisions.  
- **Integrating multiple job board datasets** would improve job recommendation accuracy.  
- **Analyzing long-term trends** (e.g., the rise of remote work) can enhance predictive modeling.  
- Further research could explore **automated skill-matching algorithms** and **time-series tracking of salary trends**.  
