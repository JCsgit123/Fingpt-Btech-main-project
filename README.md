# FinGPT - AI-Powered Financial Advisor

**FinGPT** is an innovative AI-driven financial tool designed to provide personalized tax optimization strategies and investment recommendations. Developed by students from Saintgits College of Engineering under the guidance of Dr. Nisha Joseph, this project harnesses machine learning to democratize financial advice, enhance financial literacy, and empower users to achieve better financial outcomes.

---

## Table of Contents
- [Features](#features)
- [Project Goals](#project-goals)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

---

## Features
- **Tax Optimization**: Uses Linear Regression to analyze income, deductions, and tax data, suggesting strategies to minimize liabilities.
- **Investment Clustering**: Employs K-means Clustering to group users by risk tolerance and goals, recommending tailored portfolios.
- **Real-Time Adaptation**: Updates recommendations based on tax laws, market trends, and economic indicators.
- **User Engagement**: Offers a conversational interface and educational resources for financial literacy.
- **Security & Compliance**: Prioritizes data security and transparency through potential collaborations with financial institutions.

---

## Project Goals
- Make high-quality financial advice accessible to diverse users.
- Empower individuals with data-driven tax and investment insights.
- Foster financial well-being through continuous learning and adaptation.
- Promote collaboration with industry stakeholders for innovation and trust.

---

## Tech Stack
- **Programming Language**: Python
- **Libraries**:
  - Pandas (data manipulation)
  - Scikit-learn (Linear Regression, K-means Clustering)
  - NumPy (numerical operations)
- **Data Sources**:
  - Anonymized tax return data (via chartered accountants)
  - Public datasets (e.g., Kaggle)
  - Economic indicators (GDP, inflation rates)
  - User surveys (risk tolerance, financial goals)

---

## Usage

### Tax Optimization
- **Input**: Provide financial details (e.g., income, deductions, investments) via the interface or a CSV file.
- **Output**: Receive predicted tax liabilities and optimization strategies.
- **Example:**
```bash
python tax_optimization.py --input data/user_tax_data.csv
```

### Investment Recommendations
- **Input**: Submit risk tolerance, financial goals, and current portfolio (via survey or file).
- **Output**: Get clustered investment suggestions (e.g., conservative, high-return, flexible plans).
- **Example:**
```bash
python investment_clustering.py --input data/user_investment_data.csv
```

Explore the interactive UI for real-time insights and educational content.

---

## Methodology

### Data Collection
- **Tax Data**: Historical anonymized tax returns and public datasets.
- **Economic Data**: Market trends, GDP, inflation rates from financial websites.
- **User Data**: Anonymized survey responses on demographics, risk tolerance, and goals.

### Data Pre-Processing
- **Cleaning**: Imputation for missing values, outlier removal, normalization.
- **Feature Engineering**: Created metrics like "tax deduction ratio" and "risk tolerance score."

### Model Training
- **Linear Regression (Tax Optimization)**: Trained on tax data to predict liabilities and suggest strategies.
- **K-means Clustering (Investments)**: Grouped investors into 3 clusters based on risk and goals.

---

## Results

### Tax Optimization (Linear Regression)
- **Training Accuracy**: 82.3%
- **Testing Accuracy**: 73.93%
- **Insight**: Effective at capturing patterns, but slight overfitting suggests refinement needs.

### Investment Strategies (K-means Clustering)
- **Training Accuracy**: 100%
- **Testing Accuracy**: 100%
- **Clusters:**
  - **Cluster 0**: Conservative plans (e.g., Tata AIA Fortune Pro, LIC SIIP).
  - **Cluster 1**: High-return plans (e.g., HDFC Sampoorna Nivesh, SBI eWealth).
  - **Cluster 2**: Flexible plans (e.g., Max Life Online Savings, Bajaj Smart Wealth).

---

## Contributors
- **Chirayil Adithya Vinod** - Student, Computer Science Engineering
- **Jewel Geea George** - Student, Computer Science Engineering
- **Jessel Cherian** - Student, Computer Science Engineering
- **Joel J Mullananickal** - Student, Computer Science Engineering
- **Dr. Nisha Joseph** - Associate Professor, Supervisor

---

## Acknowledgments
- **Saintgits College of Engineering** for academic support.
- **Collaborating chartered accountants** for tax data.
- **Open-source communities** (Pandas, Scikit-learn) for robust tools.
