# Data-Driven Customer Segmentation

This project is designed for customer segmentation analysis using machine learning techniques. The goal is to segment customers based on demographic features (such as age, income, spending score) and identify meaningful patterns for targeted marketing and business insights.

The project includes a Streamlit web app that allows users to interactively upload customer data, visualize data distributions, perform K-Means clustering, and analyze the results using PCA.

## Features
- **Upload Data**: Allows users to upload their own dataset in CSV or Excel format.
- **Data Overview**: Displays a preview of the dataset, summary statistics, and basic information.
- **Visualizations**: Generate correlation heatmaps, and custom plots (bar, line, scatter).
- **Interactive Analysis**: Provides tools to filter and display specific columns and rows of the dataset.
- **K-Means Clustering**: Perform customer segmentation using K-Means and visualize clusters.
- **PCA Visualization**: Visualize the dataset in reduced dimensions (2D) using PCA and analyze the clustering results.

## File Breakdown
- app.py: The main Streamlit application that powers the interactive dashboard.
- model.ipyb: (Optional) If you have a pre-trained model, include it here.
- requirements.txt: A list of Python packages required for the project.
- Mall_Customers.csv: File consisting of the dataset that will be used.
- README.md: This file, providing documentation for your project.


## Installation

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

pip install -r requirements.txt
streamlit run app.py
```
This will start a local server and open the web app in your default browser.
