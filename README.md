This repository contains a dual-phase data science project. It starts with an automated data extraction system for real estate listings and concludes with a predictive machine learning model for health/lifestyle classification.

Project Structure
1. Real Estate Web Scraper (dplhmweek1.ipynb)
This module implements a custom-built scraper to collect live data from the Bina.az real estate portal.

Technology: Built with BeautifulSoup and Requests.

Data Points Extracted: * Property Location

Direct Announcement Link

Publication Timestamp

Listing Price

Automation: The script parses HTML structures to convert unstructured web content into a structured Pandas DataFrame.

2. Predictive Classification Model (pytoncasestudy5.ipynb)
This module focuses on analyzing customer/patient data to predict classifications using classical machine learning algorithms.

Exploratory Data Analysis (EDA): Uses Seaborn and Matplotlib to visualize feature correlations and distributions.

Modeling: Implements and compares different algorithms, including Decision Trees.

Metrics: Evaluates performance using:

Precision/Recall: To measure the accuracy of minority class prediction.

F1-Score: To find the balance between precision and sensitivity.

Confusion Matrix: To visualize true vs. false positives.

Technical Stack
Web Tools: BeautifulSoup4, Requests

Data Analysis: Pandas, NumPy

Visualization: Seaborn, Matplotlib

Machine Learning: Scikit-learn (DecisionTreeClassifier, train_test_split, classification_report)

Core Competencies Demonstrated
ETL (Extract, Transform, Load): Transforming raw HTML into clean CSV-ready data.

Statistical Modeling: Applying supervised learning to clinical or behavioral datasets.

Data Visualization: Creating heatmaps and distribution plots to drive data-informed decisions.

How to Run
Web Scraping: Run dplhmweek1.ipynb (requires active internet connection to reach Bina.az).

Machine Learning: Run pytoncasestudy5.ipynb to execute the data cleaning and model training pipeline.
