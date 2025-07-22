# BUSA8000-LuminaTech_Analytics_Project

## Overview
This project aims to provide data-driven insights and recommendations for LuminaTech Lighting, focusing on sales performance, customer retention, and overall business efficiency. The project consists of data cleaning, exploratory analysis, statistical testing, predictive modeling, and customer churn analysis. The dataset contains variables such as accounting dates, customer district codes, product information, pricing, and order details.

## Directory Structure
```
LuminaTech_Project/
├── data/
│   ├── raw/                 # Original raw data files
│   └── processed/           # Cleaned or preprocessed data files
├── notebooks/
│   ├── data_cleaning.ipynb  # Data cleaning notebook
│   ├── exploratory_analysis.ipynb  # Exploratory analysis notebook
│   └── predictive_model.ipynb  # Predictive modeling notebook
├── scripts/
│   ├── data_cleaning.py     # Python script for data cleaning
│   ├── visualization.py     # Visualization functions
│   └── model.py             # Predictive modeling functions
├── reports/
│   ├── group_report.docx    # Final group report (excluding Python code)
│   ├── individual_reflection.docx # Individual reflections
│   └── visualizations/      # Exported visualizations for reports
├── results/
│   ├── figures/             # Visualizations for reports
│   ├── test_results.csv     # Outputs from statistical tests
│   └── predictions.csv      # Predictions from models
├── requirements.txt         # Python dependencies for the project
└── README.md                # Overview and project information
```

## Project Components

1. **Data Cleaning** (`data_cleaning.ipynb`)
   - Handle missing values, convert data types, and preprocess the raw data to prepare it for analysis.

2. **Exploratory Data Analysis (EDA)** (`exploratory_analysis.ipynb`)
   - Generate visualizations and descriptive statistics to uncover key trends, customer retention rates, and sales insights.

3. **Statistical Testing and Inference**
   - Perform two-sample tests to understand differences in customer behaviors.
   - Conduct multiple regression analyses to identify correlations.

4. **Predictive Modeling** (`predictive_model.ipynb`)
   - Develop a model to predict future sales prices and identify customer churn likelihood.

5. **Customer Churn Analysis**
   - Identify key features that impact customer churn and provide recommendations for customer retention.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Install dependencies by running:
  ```bash
  pip install -r requirements.txt
  ```

### Running the Project
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd LuminaTech_Project
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the notebooks in the following order:
   - `data_cleaning.ipynb`
   - `exploratory_analysis.ipynb`
   - `predictive_model.ipynb`

## Collaboration Workflow
- **Branches**: Each major component is worked on in separate branches (`data_cleaning`, `exploratory_analysis`, `predictive_model`).
- **Merging**: Once each part is finalized, branches are merged into `main` after thorough testing and code review.

## Contributors
- Warinthon
- Sawitree
- Tanyarat

## License
This project is intended for educational purposes.

## Acknowledgments
- Macquarie University Business School for providing the dataset and guidance.
- The Python community for libraries like Pandas, Matplotlib, and Scikit-Learn.
