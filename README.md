# Predicting Political Crimes in Mexico

## Project Overview
This project analyzes political violence in Mexico, aiming to predict future incidents and uncover patterns linked to organized crime and socio-economic factors. By combining historical data on political violence with macroeconomic and demographic data, the project provides actionable insights to policymakers, law enforcement, and researchers for mitigating risks and improving political stability in Mexico.

---

## Features of the Project
- **Predictive Modeling**: Uses machine learning models like K-Nearest Neighbors (KNN), Random Forest Classifier, and LASSO regression (Applied SMOTE to handle class imbalance).
- **Data Integration**: Merges political violence, economic, and demographic datasets to provide a holistic view.
- **Feature Engineering**: Incorporates key variables such as political party, state, and demographic factors like the number of teenagers.
- **Visualization**: Presents insights using detailed charts and graphs to explore relationships between variables.
- **Actionable Insights**: Offers recommendations for stakeholders to address political violence effectively.

---

## Dataset Description
### Primary Data Sources:
1. **Political Violence Data**:
   - Source: "Voting Between Bullets" by Animal Político.
   - Contains news-reported incidents of violence against political figures.
2. **Economic and Demographic Data**:
   - Source: INEGI (Instituto Nacional de Estadística y Geografía).
   - Includes macroeconomic indicators and population characteristics.

### Key Variables:
- **Target Role**: Political position of the individual attacked (e.g., candidate, executive).
- **State-Level Factors**: Geographic location where the incident occurred.
- **Economic Indicators**: GDP, employment rates, and other economic measures.
- **Demographic Variables**: Population age groups, including "Niños del Narco" data.

---

## Methodology
1. **Data Preparation**:
   - Merged datasets from multiple sources.
   - Cleaned and standardized variables for consistency.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed patterns and correlations between variables.
   - Highlighted key predictors using visualization tools.
3. **Feature Engineering**:
   - Created new variables such as teenage population and internal migration rates.
   - Reduced dimensionality by grouping similar categories.
4. **Modeling**:
   - Implemented KNN for classification, achieving up to 72% accuracy.
   - Enhanced accuracy using feature selection methods like Random Forest and LASSO.
   - Addressed imbalanced classes with SMOTE.
5. **Evaluation**:
   - Validated models using cross-validation and performance metrics.

---

## Key Results
- **Feature Importance**: The political party, targeted role, and state were the most significant predictors of violence.
- **Model Performance**:
  - KNN achieved a final accuracy of 72%.
  - SMOTE increased accuracy by 6% and reduced misclassification.
- **Actionable Insights**:
   - Regions with higher youth unemployment showed increased vulnerability to political violence.

---

## Future Improvements
- **Enhanced Variables**: Incorporate additional socio-economic and political variables.
- **Dynamic Models**: Use time-series data to capture evolving trends.
- **Expanded Scope**: Analyze the impact of international crime networks.
- **NLP Integration**: Extract insights from political speeches and campaign materials.

---

## Getting Started
### Dependencies
- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/political-crimes-mexico.git
   ```
2. Load the merged dataset and execute the provided notebooks for data preprocessing, modeling, and visualization.
3. Adjust hyperparameters in the scripts to replicate or improve results.

---

## Contact
For questions or collaboration opportunities, please reach out to:

**Name**: Arturo Medina  
**LinkedIn**: [linkedin.com/in/arturo-medina](https://linkedin.com/in/arturo-medina)
