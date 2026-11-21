# Class 09: Feature Engineering & Encoding

**Machine Learning & AI Bootcamp**

## Overview

This class focuses on Feature Engineering and Encoding, an important part of the Machine Learning workflow. 
I explored different techniques for transforming raw data into meaningful features and preparing datasets for Machine Learning models.

## Topics Covered

### 1. Introduction to Feature Engineering
- Understanding the importance of feature engineering.
- Feature engineering workflow.
- Transforming raw data into model-ready features.

### 2. Numerical Feature Scaling
- StandardScaler
- MinMaxScaler
- RobustScaler
- Understanding scaling techniques and outlier sensitivity.

### 3. Normalization & Power Transformations
- L1 and L2 Vector Normalization.
- Log Transformation (`np.log1p`).
- Yeo-Johnson Transformation.
- Box-Cox Transformation.
- Handling skewed numerical data.

### 4. Encoding Categorical Variables
- Understanding Nominal and Ordinal variables.
- Ordinal Encoding.
- One-Hot Encoding.
- Label Encoding.
- Handling categorical features using Pandas and Scikit-learn.

### 5. Feature Creation & Domain Extraction
- Interaction terms.
- Polynomial features.
- Financial ratio creation.
- Text metadata extraction.
- Creating meaningful features from existing data.

### 6. Binning & Discretization
- Equal-width binning (`pd.cut`).
- Equal-frequency binning (`pd.qcut`).
- Scikit-learn `KBinsDiscretizer`.

### 7. Handling Date-Time Features
- Timestamp parsing.
- Extracting year, month, day, day of week, and hour.
- Weekend flag creation.
- Elapsed time and customer tenure.
- Cyclical encoding using Sine and Cosine transformations.

### 8. End-to-End Feature Engineering Workflow
- Transforming raw e-commerce customer data.
- Applying feature transformations and encoding.
- Preparing a model-ready feature matrix.

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Practical Dataset

Worked with an e-commerce customer dataset containing:
- Customer information
- Income and spending scores
- Membership tiers
- Preferred product categories
- Device types
- Purchase amounts
- Discount usage
- Customer feedback
- Signup timestamps

## Key Learnings

- Understood why feature engineering matters in Machine Learning.
- Learned how to scale and normalize numerical features.
- Practiced encoding categorical variables.
- Explored feature creation and extraction techniques.
- Learned how to handle skewed data and outliers through transformations.
- Practiced extracting useful information from date-time features.

## Learning Outcome

This class helped me understand how to transform raw datasets into meaningful numerical representations and prepare better features for Machine Learning algorithms.

