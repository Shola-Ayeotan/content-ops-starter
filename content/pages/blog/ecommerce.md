---
type: PostLayout
title: Loan Eligibility using H20.ai and Deep Learning
date: '2023-07-15'
excerpt: >-
  This project implemented a statistical model to ascertain loan eligibility for
  individuals applying for loans. Using a comprehensive dataset of over 100,000
  loan records, a model was developed to assess diverse factors and determine
  the likelihood of loan repayment.
featuredImage:
  type: ImageBlock
  url: /images/Loan.png
  altText: Case study 3
  styles:
    self:
      borderRadius: x-large
bottomSections:
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: FeaturedItemsSection
    items:
      - type: FeaturedItem
        title: Project Repository
        tagline: ''
        subtitle: ''
        text: >
          Explore the full implementation, including code, data, and detailed
          analysis, on GitHub.
        actions:
          - type: Button
            label: View Project on Github
            altText: ''
            url: 'https://github.com/Shola-Ayeotan/Loan-Eligbility'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mb-20
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
slug: ecommerce
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: left
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
---
This project uses H2O.ai to build a machine-learning model that helps financial institutions decide who gets a loan. By analyzing applicant information like income and credit score, the model predicts loan eligibility, streamlining the approval process.

#### Objective

The primary goal was to create an efficient and accurate model to predict whether an applicant is eligible for a loan based on their demographic and financial information. This approach reduces the manual effort involved in loan processing and enhances the consistency of approval decisions.

#### Tech Stack

*   Programming Language: Python

*   Libraries: Scikit-learn, H2O, pandas, numpy, Flask, Seaborn, Matplotlib

*   Containerization: Docker

#### Dataset Description

The dataset used for this project is an anonymized, synthetic dataset designed to mirror real-world loan data. It contains over 100,000 records, each with detailed information about the customer's financial history and loan application.

#### Approach:

1.  Exploratory Data Analysis (EDA):

*   Missing data analysis and imputation.

*   Removal of irrelevant features.

*   Visualization of feature distributions.

2\. Data Pre-processing:

*   Handling of outliers.

*   Categorical data encoding using One-Hot and Label Encoding.

3\. Feature Engineering:

*   Creation of non-linear combinations of features.

*   Addition of derived features based on existing data.

*   Applied Standard Scaler to normalize the data.

4\. Modeling:

*   Implemented various machine learning models including Random Forest, Gradient Boosting, XGBoost, and Neural Networks.

*   Models were evaluated using metrics like Precision, Recall, AUC, and F1 Score.

5\. Hyperparameter Tuning:

*   Used GridSearchCV to optimize model performance.

6\. Model Deployment:

*   Deployed the final model using Flask, encapsulated in a Docker container for easy scalability and deployment.

#### Project Takeaways

*   Mastered EDA techniques for complex datasets.

*   Gained expertise in data cleaning, feature engineering, and data standardization.

*   Developed multiple machine learning models and evaluated their performance.

*   Successfully deployed a predictive model using Flask and Docker.

*   Improved understanding of model metrics such as AUCPR, AUC, and F1 Score.

#### Impact

The final model achieved a high accuracy rate, enabling quicker and more consistent loan approval decisions. This solution effectively reduces the risk of loan defaults and helps financial institutions optimize their loan portfolios.

