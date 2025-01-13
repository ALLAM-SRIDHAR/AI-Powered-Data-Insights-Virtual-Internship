# AI-Powered Data Insights Virtual Internship

Welcome to the **AI-Powered Data Insights Virtual Internship** repository! This project focuses on analyzing student engagement data using data science and machine learning techniques. The goal is to understand student behavior, identify patterns that lead to drop-offs, and provide actionable insights to improve engagement and retention. This internship spanned **four weeks**, each with specific objectives and deliverables.

---

## Table of Contents
1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Tasks by Week](#tasks-by-week)
    - [Week 1: Data Preprocessing and Feature Engineering](#week-1-data-preprocessing-and-feature-engineering)
    - [Week 2: Exploratory Data Analysis (EDA)](#week-2-exploratory-data-analysis-eda)
    - [Week 3: Predictive Analysis and Churn Analysis](#week-3-predictive-analysis-and-churn-analysis)
    - [Week 4: Recommendation System and Presentation](#week-4-recommendation-system-and-presentation)
4. [Technologies Used](#technologies-used)
5. [How to Run the Project](#how-to-run-the-project)
6. [Insights and Results](#insights-and-results)
7. [Contributors](#contributors)

---

## Overview
This internship aimed to analyze and improve student engagement using AI and data analytics. The dataset contains information on student interactions with various opportunities, including sign-ups, completions, and drop-offs. 

Key questions addressed during the project:
- Which opportunities attract the most sign-ups?
- What factors contribute to successful completions?
- What patterns lead to drop-offs?
- How can we recommend opportunities to students to increase engagement?

---

## Project Structure
├── datasets/ # Raw and processed data files 
├── Week1 Reports/ 
      |-- Preprocessing_week1.ipynb
      |-- Week1_Feature_Engineering_report.pdf
      |-- Cleaned_preprocessed_dataset.csv
├── Week2 Reports/ #EDA
      |-- EDA.ipynb
      |-- EDA_Report_Week2.pdf
├── Week3 Reports/ #Predictive Analysis and Churn Analysis
      |-- week3_predictive_model.ipynb
      |-- Week3_ChurnAnalysis_report.pdf
├── Week4 Reports/ 
      |-- Week4_final_ppt.pdf
      |-- Week4_final_report.pdf
      |-- Week4_final_recording_link.pdf
      |-- Week3_predictive_model(1).ipynb
├── README.md # Project overview and instructions 
└── requirements.txt # Python dependencies


---

## Tasks by Week

### Week 1: Data Preprocessing and Feature Engineering
- **Objective**: Clean and preprocess the data to ensure consistency and accuracy for analysis.
- **Tasks Completed**:
  - Handled missing values and duplicates.
  - Normalized and standardized numerical features.
  - Encoded categorical variables using appropriate techniques.
  - Engineered new features (e.g., time spent per opportunity, engagement scores).
- **Deliverables**:
  - Cleaned dataset.
  - Feature-engineering report.

---

### Week 2: Exploratory Data Analysis (EDA)
- **Objective**: Explore the dataset to uncover patterns, trends, and anomalies.
- **Tasks Completed**:
  - Visualized student sign-up, completion, and drop-off trends.
  - Analyzed engagement metrics across different demographic groups.
  - Identified key factors contributing to drop-offs.
- **Deliverables**:
  - EDA report with visualizations.
  - Insights on student engagement patterns.

---

### Week 3: Predictive Analysis and Churn Analysis
- **Objective**: Build predictive models to understand and predict student behavior.
- **Tasks Completed**:
  - Developed a classification model to predict student drop-offs.
  - Analyzed churn patterns using decision trees and logistic regression.
  - Evaluated model performance using accuracy, precision, recall, and F1 score.
- **Deliverables**:
  - Predictive models and evaluation metrics.
  - Churn analysis report.

---

### Week 4: Recommendation System and Presentation
- **Objective**: Create a recommendation system and present the project findings.
- **Tasks Completed**:
  - Built a content-based recommendation system to suggest relevant opportunities to students.
  - Compiled all insights into a presentation for stakeholders.
- **Deliverables**:
  - Recommendation system implementation.
  - Final presentation slides.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Analysis: `pandas`, `numpy`
  - Data Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `xgboost`
  - Recommendation System: `surprise`, `scipy`
- **Tools**: Jupyter Notebook, Google Slides

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-data-insights-internship.git
   cd ai-data-insights-internship
2. Install dependencies:
   pip install -r requirements.txt
3. Navigate to the notebooks/ directory and run the Jupyter notebooks in sequence.

