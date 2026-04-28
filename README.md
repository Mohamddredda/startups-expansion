# Startup Expansion Analysis 🚀

This repository provides a data-driven analysis of startup expansion performance across various US regions. The project evaluates the efficiency of marketing spend and revenue generation for 150 store locations, categorized into established ("Old") sites and "New" expansions.

## 📌 Project Overview
The analysis utilizes Python to process complex business data, providing insights into regional performance and financial viability. By calculating key performance indicators such as **Profit** and **ROI**, this project helps identify which geographic areas yield the highest returns on marketing investments.

## 📊 Key Features & Data Processing
* **Data Cleaning**: Handled a dataset covering 35 unique states and 149 distinct cities.
* **Financial Feature Engineering**:
    * Calculated **Net Profit**: `Revenue - Marketing Spend`.
    * Calculated **ROI (Return on Investment)**: `(Profit / Marketing Spend) * 100`.
* **Regional Analysis**: Grouped performance by Sales Regions (Region 1 vs. Region 2) to identify broader market trends.
* **Visualizations**: Generated visual comparisons of expansion status and top-performing states using Matplotlib and Seaborn.

## 📈 Performance Summary
* **Revenue Statistics**: The average revenue per store is **$39,301.43**, with a maximum recorded revenue of **$68,828**.
* **Marketing Spend**: The average marketing investment per location is **$2,893.15**.
* **Store Distribution**: The analysis covers 140 established stores and 10 new expansion locations.

## 🛠 Tech Stack
* **Language**: Python
* **Libraries**: 
    * **Pandas**: Data manipulation and descriptive statistics
    * **Matplotlib & Seaborn**: Data visualization
    * **Numpy**: Numerical computing

## 📂 File Structure
* `startups-expansion.ipynb`: The Jupyter Notebook containing the end-to-end analysis.
* `startup-expansion.xlsx`: The raw business dataset.

## 🚀 How to Use
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
