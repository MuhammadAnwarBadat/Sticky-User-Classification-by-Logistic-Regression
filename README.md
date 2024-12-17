---

# Sticky-User-Prediction

## Overview

This repository addresses a **Data Science Case Study**. The case study revolves around analyzing user behavior, purchase patterns, and spending abilities to identify **sticky vs non-sticky users**. The ultimate goal is to help the company efficiently target potential customers for its new business offerings without excessive marketing spend.

---

## Problem Statement

An XYZ company has a marketplace with **10k - 20k DAU (Daily Active Users)** and over a **million users**. The company aims to expand into high-end products and has two options:  
1. Spend on marketing to acquire new customers.  
2. Utilize existing user data to identify and target **high-potential sticky users**.

The key tasks include:

1. **Data Analysis**  
   - Identifying user segments based on purchase habits and spending ability.  
   - Performing region-based transaction and user analysis.  
   - Providing insights to guide business expansion.  

2. **Machine Learning**  
   - Building a predictive model to tag **newly acquired users** as **sticky** or **non-sticky** based on:  
     - Location  
     - Acquisition Time  
     - Purchase Amount  
     - Acquisition Channel  
   - Delivering an application that accepts a CSV file and outputs predictions.

---

## Deliverables

This repository includes the following:

1. **Source Code**:  
   - Data Analysis and Cleaning  
   - Machine Learning Model Development  
   - A User-Friendly Application Script to Predict Sticky Users  

2. **Resultant Dataset**:  
   - A dataset that highlights user stickiness and insights for decision-making.  

3. **PowerPoint Presentation**:  
   - A strategic overview and explanation of the problem-solving approach and results.  

---

## Dataset

The **sample dataset** can be viewed here:   
🔗 [Download Sample Dataset](https://docs.google.com/spreadsheets/d/1KY3GZ9I8DF8TYvxMrTRpPiVGU7hxEUohya71LLWi970)

The **input dataset** is available on Google Drive:  
🔗 [Download Full Dataset](https://drive.google.com/file/d/1lT5MY0UmKBaui26zYYAGOafTjAz-71XG/view?usp=sharing)

This dataset includes transaction-level details for users, such as:  
- `Location`  
- `Transaction Amount`  
- `Acquisition Time`  
- `Acquired By`  
- `Transaction Time`  

The **output dataset** is available on Google Drive which tags the sticky and non-sticky customers:  
🔗 [Download Output Dataset](https://drive.google.com/file/d/1lT5MY0UmKBaui26zYYAGOafTjAz-71XG/view?usp=sharing)

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/MuhammadAnwarBadat/Sticky-User-Classification-by-Logistic-Regression.git
   cd Sticky-User-Classification-by-Logistic-Regression
   ```

2. Run the '.ipynb' file on Jupyter Notebook or Google Colab

3. Output:  
   - A new CSV file with user stickiness predictions will be saved in the project folder as `predicted_sticky_users.csv`.

---

## Key Features

- **Data Analysis**: User insights based on habits, region, and transaction data.  
- **Machine Learning Model**: Predicts sticky vs non-sticky users using `Logistic Regression`.  
- **Automation**: A script that accepts input CSV files and outputs results seamlessly.  

---

## Results

The model successfully identifies **sticky users** who are more likely to engage with Bykea’s new offerings. This ensures targeted marketing and better resource allocation.

---

## Future Scope

- Adding more advanced ML models for improved accuracy.  
- Integration of real-time data pipelines for continuous predictions.  
- Enhanced analysis dashboards for business insights.  

---

## Contact

If you have any questions or suggestions, feel free to reach out:

- **By**: Muhammad Anwar  
- **LinkedIn**: http://www.linkedin.com/in/mmohamed-anwar  
- **Email**: anwarbadat1997.ab@gmail.com  

---

