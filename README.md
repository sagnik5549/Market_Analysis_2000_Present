# Global Financial Market Analysis (2000–2026)

## Project Overview

This project presents a comprehensive exploratory analysis of global financial market data spanning from 2000 to May 2026. The dataset includes multiple asset classes such as stock indices, commodities, currencies, and cryptocurrencies across different regions of the world.

The objective of this project is to understand long-term market behavior, identify trading activity patterns, analyze the impact of major economic events, and extract meaningful insights from over two decades of financial data.

\---

## Business Objectives

The analysis aims to answer the following key questions:

* How are different asset classes represented in the dataset?
* Which assets contribute the most to trading activity?
* How has market behavior evolved over time?
* What impact did major economic events have on financial markets?
* Which asset classes exhibit the highest levels of trading activity?
* What long-term trends can be observed across global markets?

\---

## Dataset Information

The dataset contains historical market information from 2000 to May 2026.

### Features

|Feature|Description|
|-|-|
|date|Trading date|
|open|Opening price|
|high|Highest price|
|low|Lowest price|
|close|Closing price|
|volume|Trading volume|
|symbol|Asset symbol|
|asset\_name|Asset name|
|asset\_type|Asset category|
|region|Geographic region|

### Asset Classes Included

* Stock Indices
* Commodities
* Currencies
* Cryptocurrencies

\---

## Project Structure

```text
Market\\\_Analysis\\\_2000\\\_Present/
│
├── Data/
│   ├── raw/
│   │   └── global\\\_financial\\\_markets.csv
│   │
│   └── processed/
│       └── cleaned\\\_market\\\_data.csv
│
├── Notebooks/
│   ├── 01\\\_Data\\\_Understanding.ipynb
│   ├── 02\\\_Data\\\_Cleaning.ipynb
│   ├── 03\\\_Exploratory\\\_Data\\\_Analysis.ipynb
│   └── 04\\\_Insights\\\_and\\\_Findings.ipynb
│
├── Reports/
│
├── src/
│
├── requirements.txt
│
└── README.md
```

\---

## Analysis Workflow

### 1\. Data Understanding

* Dataset inspection
* Feature analysis
* Data type verification
* Initial statistical overview

### 2\. Data Cleaning

* Missing value assessment
* Duplicate detection
* Data type correction
* Date conversion
* Data quality validation

### 3\. Exploratory Data Analysis

* Dataset overview
* Asset composition analysis
* Market coverage analysis
* Trading volume analysis
* Time series analysis
* Rolling trend analysis
* Correlation analysis
* Major market events analysis

### 4\. Insights and Findings

* Summary of analytical findings
* Business insights
* Key observations
* Future recommendations

\---

## Key Findings

### Asset Composition

* Stock indices represent the largest asset category by record count.
* Cryptocurrencies account for the smallest share of observations.

### Trading Activity

* Bitcoin records the highest total trading volume in the dataset.
* Ethereum ranks second in overall trading activity.
* Trading volume is highly concentrated among a small number of assets.
* Cryptocurrencies exhibit the highest average trading volume despite having fewer records.

### Market Trends

* Financial markets exhibit a strong long-term growth trend.
* Short-term volatility is visible throughout the study period.
* The post-2020 period demonstrates the strongest market expansion.

### Correlation Analysis

* Open, High, Low, and Close prices are strongly positively correlated.
* Trading volume shows a weaker relationship with price-based variables.

### Major Economic Events

The analysis captures the impact of several significant market events:

* Dot-Com Crash (2000–2002)
* Global Financial Crisis (2008–2009)
* COVID-19 Market Shock (2020)
* Post-Pandemic Recovery (2021–2026)

\---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git
* GitHub

\---

## How to Run

### Clone Repository

```bash
git clone https://github.com/sagnik5549/Market\\\_Analysis\\\_2000\\\_Present.git
```

### Create Environment

```bash
conda create -n market\\\_analysis python=3.12
conda activate market\\\_analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

\---

## Future Improvements

Potential extensions of this project include:

* Interactive dashboards using Power BI or Tableau
* Market forecasting using Machine Learning
* Volatility and risk analysis
* Portfolio optimization techniques
* Asset clustering and similarity analysis
* Time-series forecasting models

\---

## Author

**Sagnik Kundu**

Data Analysis | Data Science | Machine Learning Enthusiast

This project was developed as part of a personal portfolio focused on financial market analysis, data analytics, and business insight generation.

