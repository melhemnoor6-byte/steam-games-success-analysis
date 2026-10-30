# Steam Games Success Analysis Using Business Intelligence

## Project Overview

This project was developed as part of the **Business Intelligence course** at Afeka Academic College of Engineering.

The objective is to analyze historical Steam game data and identify the key factors associated with commercial success in the gaming industry.

By combining Business Intelligence techniques, data warehousing, exploratory data analysis, and machine learning, the project aims to provide data-driven insights that can support game development, pricing, and marketing decisions.

## Technologies & Tools

- **Programming Language:** Python
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook
- **Business Intelligence:** ETL, Data Warehousing, Star Schema, OLAP
- **Machine Learning Algorithms:** Random Forest, K-Means Clustering

## Data Sources

The project uses two publicly available datasets from Kaggle:

1. Steam Games Dataset
2. Game Recommendations on Steam

The datasets contain information about game characteristics, pricing, user reviews, player engagement, and estimated ownership.

## Project Methodology

### 1. Data Extraction, Transformation & Loading (ETL)

- Imported datasets using Python and Pandas.
- Identified and corrected structural inconsistencies.
- Examined missing values and duplicate records.
- Validated data types and prepared data for integration.
- Merged datasets using Steam application identifiers (AppID).

### 2. Data Warehouse Design

Designed a Star Schema consisting of:

- **Fact Table:** Game performance metrics, including price, playtime, reviews, and concurrent players.
- **Dimension Tables:** Game information, content, platform, and time.

The data warehouse structure supports efficient multidimensional analysis.

### 3. OLAP & Business Intelligence Analysis

Performed multidimensional analysis to investigate:

- User satisfaction across game genres.
- Player engagement in single-player versus multiplayer games.
- Relationships between game pricing and customer satisfaction.
- Pricing strategies and estimated market reach.

### 4. Machine Learning — Classification

Developed a Random Forest classification model to identify successful games based on historical performance indicators.

Implemented feature engineering, one-hot encoding, train-test splitting, and model evaluation.

**Model Performance:**

- Random Forest Test Accuracy: **83.48%**
- Training/Testing Split: 70% / 30%

### 5. Machine Learning — Clustering

Applied K-Means clustering to group Steam games according to characteristics such as:

- Game pricing
- User satisfaction
- Player engagement
- Concurrent player activity

The clustering analysis identified **four game segments**, supporting further exploration of market patterns.

## Key Findings & Business Insights

- Multiplayer features were associated with higher average player engagement in the analyzed data.
- Game genres, pricing, and user satisfaction provide useful indicators for evaluating game performance.
- Machine learning can help identify patterns associated with successful games.
- Clustering techniques can support game segmentation and market analysis.
- Business Intelligence methods can help transform raw gaming data into information that supports strategic decision-making.

## Project Structure

The main Jupyter Notebook contains:

1. Introduction and Business Problem
2. ETL Process and Data Warehouse Design
3. OLAP Analysis and Visualizations
4. Random Forest Classification
5. K-Means Clustering
6. Big Data Considerations
7. Business Insights and Conclusions

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Download the source datasets from Kaggle.
4. Update the dataset file paths in the notebook if necessary.
5. Open the `.ipynb` file using Jupyter Notebook.
6. Execute the notebook cells in sequence.

## Academic Information

**Institution:** Afeka Academic College of Engineering  
**Course:** Business Intelligence  
**Project Type:** Academic Team Project  
**Date:** July 2026

## Conclusion

This project demonstrates the practical application of Business Intelligence and Machine Learning techniques to a real-world analytical problem.

It combines data preprocessing, ETL, data warehouse design, multidimensional analysis, classification, clustering, and data visualization to support data-driven decision-making in the gaming industry.
