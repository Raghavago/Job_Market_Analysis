# Job_Market_Analysis
Power BI project analyzing Data Science job-market trends, salaries, education requirements, locations, industries, companies, and in-demand technical skills.

## Project Overview

This project analyzes the Data Science job market to identify important trends related to job opportunities, salaries, industries, companies, job roles, education requirements, and technical skills.

The analysis is designed to help job seekers understand current market requirements and make data-driven career decisions.

## Dataset

The dataset contains 742 job records and 42 features.

Key attributes include:

- Job Title
- Salary Estimate
- Company Name
- Location
- Industry
- Rating
- Seniority
- Education Requirements
- Technical Skills
- Salary-related fields

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization

## Data Preparation

The dataset was prepared using Power Query.

The data preparation process included:

- Validating data types
- Cleaning text fields
- Handling missing or unavailable values
- Checking duplicate records
- Cleaning salary-related fields
- Transforming skill columns
- Creating a separate Job Skills table

The skill columns were unpivoted to make skill-level analysis easier.

## DAX Analysis

DAX measures were created to calculate important metrics such as:

- Total Jobs
- Average Salary
- Average Minimum Salary
- Average Maximum Salary
- Total Companies
- Skill Job Count

## Dashboard 1: Job Market Overview

This dashboard analyzes:

- Job opportunities by location
- Industry distribution
- Hiring companies
- Job titles
- Job demand

### Key Insights

- Job opportunities are concentrated in specific locations.
- Data Science and analytics roles are available across multiple industries.
- Certain companies show higher hiring activity.
- Some job titles have significantly higher demand than others.

## Dashboard 2: Salary & Education Analysis

This dashboard focuses on:

- Salary differences across states
- Salary by job title
- Minimum and maximum salary
- Education requirements
- Salary and education relationships

### Key Insights

- Salary levels vary across different states.
- High-demand job roles are not always the highest-paying roles.
- Salary patterns differ by job title and seniority.
- Education categories can show differences in average salary.

## Dashboard 3: Skills & Job Intelligence

This dashboard analyzes the technical skills required for different Data Science and analytics roles.

The skill columns were transformed into a separate Job Skills table using Power Query's Unpivot feature.

### Key Insights

- Technical skills play an important role in job-market demand.
- Employers often require a combination of skills.
- Different job roles require different skill combinations.
- Skill analysis can help identify gaps between candidate skills and market requirements.

## Key Findings

The analysis shows that the Data Science job market is influenced by:

- Location
- Industry
- Company hiring activity
- Job role
- Salary
- Education
- Seniority
- Technical skills

High job demand does not always mean higher salary.

Different job roles also require different combinations of technical and analytical skills.

## Recommendations

Job seekers should use a data-driven approach when planning their careers.

Instead of focusing on only one factor, candidates should consider:

**Location + Job Demand + Salary + Required Skills + Career Growth**

A focused career approach can be followed:

**Target Job Role → Required Skills → Skill Development → Projects → Job Applications**

## Project Outcome

This project demonstrates how Power BI, Power Query, and DAX can be used to transform job-market data into interactive dashboards and actionable insights.

The analysis can help candidates identify suitable job roles, understand salary expectations, and develop skills aligned with market requirements.
