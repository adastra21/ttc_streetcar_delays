# TTC Streetcar Delay Analysis Project

## Project Overview

This project focuses on analyzing and predicting delays in the Toronto Transit Commission (TTC) streetcar system using historical delay data. The dataset, sourced from [Toronto Open Data](https://open.toronto.ca/dataset/ttc-streetcar-delay-data/), contains detailed information about delays, including their causes, durations, and locations. Our goal was to derive actionable insights, build predictive models, and identify key factors contributing to delays.

## Team Members

This project was a collaborative effort by a team of four data enthusiasts:

- **Abdur Rehman [@adastra21](https://github.com/adastra21)**
- **Kamad Dastmalchi [@Kamanddst](https://github.com/Kamanddst)**
- **Mehul Patel [@mehulptech](https://github.com/mehulptech)**
- **Oluranti Ibileye [@Rantitope](https://github.com/Rantitope)**

## Video Submissions

- **[Abdur Rehman]()**
- **[Kamad Dastmalchi]()**
- **[Mehul Patel](https://drive.google.com/file/d/19X77LmoSs9dfkaNwa_4b8ldVDgMRkJa_/view)**
- **[Oluranti Ibileye]()**

## Objectives

1. **Data Preparation and Cleaning**:

   - Data Merging and preparing CSV file
   - Handling missing values
   - Data type conversion
   - Outlier detection and treatment

2. **Data Preprocessing and Exploration**:

   - Examine data distribution
   - Convert date and time features into appropriate formats
   - Engineer new features (e.g., day of week, hour of day, season)

3. **Descriptive Analysis**:

   - Understand the frequency and duration of delays by route, location, and time.
   - Identify the most common incident types and their impact on delays.
   - Examine correlations between variables (e.g., delay duration and gap time).

4. **Regression Analysis**:

   - Develop models to predict delay duration based on various factors.
   - Evaluate model performance and identify key predictors of delay length.

---

## Dataset

The dataset used for this project is publicly available at [Toronto Open Data](https://open.toronto.ca/dataset/ttc-streetcar-delay-data/).

---

## Data Science pipeline

We followed the following steps in the Data Science pipeline process, each with a separate notebook:

1. Data Preparation (`notebooks/01_data_prep.ipynb`)
2. Data Cleaning (`notebooks/02_data_preprocessing.ipynb`)
3. Exploratory Data Analysis (`notebooks/03_eda.ipynb`)
4. Descriptive and Regression Analysis (`notebooks/04_analysis.ipynb`)

---

## Key Findings

### Descriptive Analysis

- The **501 route** experienced the highest number of delays, with an average delay duration of 13.37 minutes.
- **Dundas West Station** was identified as a hotspot for delays with over 3,000 incidents recorded.
- Fridays had the highest number of incidents, but Sundays had the longest average delays.
- **Diversions** and **Overheads** caused the most incidents
- More than 30% of Incidents were caused by **Mechanical failures**

### Regression Analysis

- The strongest predictor of delay duration was **gap time**, with a positive correlation indicating that longer gaps lead to longer delays.
- The regression model achieved an R² score of 0.88, explaining 88% of the variability in delay durations.

---

## Future Work

If we had more time, we would:

1. Incorporate advanced machine learning techniques like gradient boosting or neural networks for better predictions.
2. Analyze seasonal trends or external factors (e.g., weather conditions) affecting delays.
3. Build an interactive dashboard for monitoring and visualization of streetcar delays.

---

## Strengths Brought to the Team

As a team, we brought diverse skills to this project:

- Strong collaboration and communication ensured smooth progress across all stages.
- A mix of technical expertise in data cleaning, machine learning, visualization, and storytelling helped us tackle challenges effectively.
- A shared passion for solving real-world problems made this project both impactful and enjoyable!

---

## How to Run This Project

1. Clone this repository to your local machine.
2. Install required dependencies
3. Run the Jupyter Notebook provided in the repository to explore the analysis and insights.

## References

[TTC Bus and Subway Delay Data Analysis](https://github.com/JasonYao3/TTC_transit_delay_proj?tab=readme-ov-file#Summary_of_Findings)
