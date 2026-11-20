# NLP-Based Detection of Product Quality Issues in Skincare Customer Reviews

## Project Overview

This project explores how Natural Language Processing (NLP) and Machine Learning can be used to identify recurring product quality complaints in skincare customer reviews.

Skincare companies receive large volumes of customer feedback across different products and brands. However, manually analysing thousands of reviews to identify recurring problems can be time-consuming.

This project aims to develop an NLP pipeline that analyses customer reviews, detects product-related complaints and categorises common quality issues.

The ultimate goal is to help businesses better understand customer dissatisfaction and identify products that may require further quality investigation.

## Business Problem

Customer dissatisfaction can affect brand reputation, customer loyalty and product sales.

Customers may report problems such as:

- Skin irritation.
- Poor product texture.
- Unpleasant smell.
- Poor product performance.
- Packaging defects.
- Poor absorption.

Identifying recurring complaints can help businesses understand potential product weaknesses and prioritise quality investigations.

## Project Objectives

The main objectives are:

1. Analyse customer reviews to understand product-related feedback.
2. Identify reviews containing product quality complaints.
3. Classify complaints into relevant categories.
4. Identify products associated with recurring customer-reported problems.
5. Evaluate the performance of machine-learning models.
6. Develop data-driven recommendations for product quality improvement.

## Dataset

**Dataset:** [Sephora Products and Skincare Reviews](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews)

**Source:** Kaggle

The dataset contains product information and customer reviews, including:

- Product names and brands.
- Customer review text.
- Product ratings.
- Product identifiers.
- Recommendation information.
- Review submission dates.
- Product categories.

The written customer reviews will be the primary data source for the NLP analysis.

## Proposed Complaint Categories

The project will investigate the following customer-reported product quality issues:

| Category | Description |
|---|---|
| Skin Irritation | Reports of redness, irritation or discomfort |
| Poor Texture | Complaints about sticky, greasy or unpleasant texture |
| Unpleasant Smell | Negative feedback about product fragrance or smell |
| Poor Performance | Products not meeting customer expectations |
| Packaging Problems | Complaints about leaking or defective packaging |
| Poor Absorption | Products that do not absorb properly |
| Other | Feedback that does not fit the defined categories |

These categories will be developed and validated as part of the data preparation process.

## Methodology

The proposed project follows an end-to-end NLP pipeline.

### 1. Data Collection
Obtain the Sephora dataset and select relevant skincare product reviews.

### 2. Exploratory Data Analysis
Examine review distributions, ratings, product information and text characteristics.

### 3. Data Preprocessing
Clean and prepare customer reviews for NLP analysis.

### 4. Text Annotation
Develop consistent complaint-category labels for a manually reviewed sample of customer feedback.

### 5. Feature Extraction
Apply TF-IDF to convert textual reviews into numerical representations.

### 6. Machine Learning
Explore and compare classification algorithms, including:

- Logistic Regression.
- Multinomial Naive Bayes.

### 7. Model Evaluation
Evaluate classification performance using appropriate metrics, including:

- Precision.
- Recall.
- F1-score.
- Confusion Matrix.

### 8. Business Analysis
Investigate recurring complaint categories and identify products that may deserve further quality investigation.

## Technologies

The planned technologies include:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

## Expected Outcomes

The project aims to produce:

- An NLP pipeline for analysing skincare customer reviews.
- A classification model for identifying product quality complaints.
- An analysis of recurring customer-reported problems.
- Visualisations of complaint patterns.
- Business recommendations to support product quality investigations.

## Limitations

This project has several important limitations:

- Customer reviews represent personal opinions and experiences.
- Customer-reported complaints do not necessarily establish actual product defects.
- Complaint categories require manual annotation.
- The dataset does not directly provide verified financial losses or refund costs.
- Review data may contain bias because not all customers submit reviews.

The system is intended to support business analysis and quality investigations, not replace professional product testing or safety assessments.

## Project Status

**Status: In Progress**

This repository will be updated as the data exploration, NLP implementation, model development and evaluation stages are completed.

## Author

Developed as a Big Data Analytics and Natural Language Processing project.
