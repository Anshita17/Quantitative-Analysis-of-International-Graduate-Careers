# International-Graduate-Career-Analysis

This project provides a comprehensive analysis of **300,000+ international graduate records**, investigating the determinants of career success. By synthesizing data on education, visa status, and soft skills, the analysis identifies the "Multiplier Effect"—how language proficiency and internships amplify the value of academic degrees in the labor market.

## Dataset Overview

The dataset combines survey data with administrative records to track graduate outcomes. Key variables include:

- **Employment_Status**: Current status (Employed, Unemployed, Continuing Education).
- **Salary**: Annual income estimation (in USD/GBP).
- **Visa_Type**: Legal status (e.g., Student, Post-study Work, Work Visa, Permanent Residency).
- **Language_Proficiency**: Standardized classification (Basic, Intermediate, Advanced, Fluent).
- **Education_Level**: Highest degree obtained (Diploma, Bachelor's, Master's, PhD).
- **Internship_Experience**: Boolean indicator of work experience during study (Yes/No).
- **University_Ranking**: Tier of the institution (Low, Medium, High).
- **Field_of_Study**: Academic discipline (e.g., IT, Engineering, Business).
- **Country_of_Origin**: Nationality of the graduate.
- **Years_Since_Graduation**: Time elapsed since degree completion.
- **GPA**: Academic performance metric.

## Tools and Technologies

**Programming Language:**
- Python

**Data Collection and Cleaning:**
- **Pandas**: Used for handling large-scale datasets (300k+ rows), merging data frames, and imputing missing values.
- **NumPy**: Used for numerical operations and array handling.

**Visualization:**
- **Matplotlib** & **Seaborn**: Used to create boxplots, bar charts, and heatmaps to visualize salary distributions and employment trends.

**Statistical Analysis:**
- **SciPy**: Used for hypothesis testing (Chi-Square, ANOVA) to validate relationships between variables.

## Key Insights

### 1. The "Multiplier Effect" of Soft Skills
- **Language Matters:** Proficiency in the host country's language acts as a "multiplier." A Bachelor's degree holder with **Fluent** language skills often outperforms a Master's degree holder with only **Basic** proficiency in terms of employability.
- **Salary Impact:** There is a statistically significant correlation between language scores and salary, with fluent speakers earning a premium across all job sectors.

### 2. The Role of Internships
- **Bridging the Gap:** Graduates with internship experience had significantly higher employment rates (Employed status) compared to those without, regardless of their university ranking.
- **Visa Mitigation:** Internship experience proved to be a mitigating factor against restrictive visa categories, helping candidates secure sponsorship more effectively.

### 3. Structural Barriers vs. Human Capital
- **Visa Constraints:** Analysis highlights "Post-study" and "Student" visa holders face higher unemployment rates compared to "Permanent Residency" holders, quantifying the friction caused by legal status.
- **Degree Inflation:** Higher degrees (PhD/Master's) do not guarantee employment if not paired with local market experience (internships) or communication skills.

## Report

[Click Here to view the full Project Report (PDF)](The_Multiplier_Effect_on_International_Graduate_Career_Success.pdf)

## Key Skills and Responsibilities

- **Data Wrangling & Cleaning:** Processed a large-scale dataset of **300,000+ rows** using **Pandas**, addressing missing values in salary and employment columns and standardizing categorical variables (Visa Type, Education Level).
- **Statistical Modelling:** Conducted **Chi-Square tests** and **Two-Way ANOVA** to quantify the relationship between categorical variables (Language/Visa) and continuous outcomes (Salary), proving the statistical significance of the "Multiplier Effect."
- **Data Visualization:** Developed clear, publication-ready visualizations using **Seaborn** to illustrate the interaction between Education Level and Language Proficiency on salary outcomes.
- **Feature Engineering:** Analyzed the interaction between "Hard Skills" (GPA, Degree) and "Soft Skills" (Language, Internships) to derive actionable insights for university career services.
- **Actionable Insight Generation:** Synthesized findings into a strategic report, recommending that universities integrate language support and internship programs into the curriculum to maximize graduate ROI.

**Tools Used:** Google collab for reproducible analysis, Python for statistical testing, and Pandas for efficient data manipulation.
