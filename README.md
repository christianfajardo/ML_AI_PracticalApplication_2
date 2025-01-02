# UC Berkeley | Professional Certificate in Machine Learning and Artificial Intelligence
## Practical Application 2 (Module 11)


This project focuses on analyzing used car prices in the US, leveraging Ridge and Lasso regression models. The study confirms widely known factors such as mileage, year, and manufacturer as key determinants of used car prices. The repository includes preprocessing steps, feature engineering, model implementation, and insightful visualizations to support the conclusions.

---

## Project Overview
### This project implements the CRISP-DM methodology.

- **Objective**: To identify and confirm the key factors driving used car prices in the US using Ridge and Lasso regression models.
- **Scope**: The analysis focuses on common variables such as mileage, year, and manufacturer, while exploring their relationships with used car pricing.
- **Outcome**: The models validate the importance of these features and provide a structured, data-driven approach to analyze pricing trends.

---

## Key Features and Methodology

- **Data Preprocessing**:
  - Cleaned up nulls values and irrelevant features, renamed features, and converted feature data types
  - Outliers were removed using the IQR method to improve model stability.
  - Numerical and categorical features were scaled and encoded using pipelines for consistent preprocessing.

- **Feature Engineering**:
  - Polynomial interactions between `year` and `mileage` were created to capture non-linear relationships.
  - One-hot encoding and ordinal encoding were used for categorical variables such as manufacturer and title status.

- **Model Implementation**:
  - Ridge and Lasso regression models were applied, with hyperparameter tuning to identify optimal `alpha` values.
  - Recursive Feature Elimination (RFE) was used to rank features based on their importance.

---

## Visualizations
- **Histogram Plot**:
  - Used in initial data analysis and understanding

- **Scatter Plot**:
  - Mileage and price were plotted to show their negative correlation.

- **Box Plot**:
  - Used to explore the distribution of prices for different manufacturers.

---

## Key Results

- **Model Performance**:
  - Both Ridge and Lasso models showed low R² scores but consistently highlighted mileage, year, and manufacturer as top predictors.

- **Feature Rankings**:
  - Mileage had the highest positive impact, followed by polynomial terms such as `year^2 mileage`.
  - Specific manufacturers like Mercedes-Benz and Toyota emerged as significant categorical variables.

- **Validation of Common Knowledge**:
  - The models reinforced the widely accepted understanding of used car pricing drivers in the US.

---

## Conclusions

- Mileage, year, and manufacturer remain the most critical factors influencing used car prices.
- Polynomial interactions between year and mileage highlight complex relationships that align with market trends.
- While the models exhibited modest predictive performance, they effectively validated common knowledge through a data-driven approach.
- Iterative improvements, such as additional features or more advanced algorithms, could further enhance the models.

---

## Next Steps

- **Continuous Data Updates**:
  - Integrate new data on used car sales to retrain and fine-tune the models regularly.

- **Advanced Feature Engineering**:
  - Explore additional features like fuel type, transmission, and location to improve model accuracy.

- **Model Refinement**:
  - Experiment with advanced regression techniques or ensemble models to capture more complex patterns.
  - Explore Permutation Importance and analyze results


---

## Repository Structure

- `data/`: Contains the cleaned dataset used for analysis.
- `images/`: Contains images
- `README.md`: Project documentation.


