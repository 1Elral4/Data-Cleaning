# 👥 Employee Exit Survey Analysis - DETE & TAFE Queensland

An in-depth analysis of employee resignation patterns using exit survey data from Queensland's Department of Education, Training and Employment (DETE) and Technical and Further Education (TAFE) institutes.

## 🎯 Project Overview

This project investigates whether employees who resign from DETE and TAFE institutes are leaving due to dissatisfaction, and how this varies across different career stages and demographics. The analysis reveals critical insights about employee retention patterns in Queensland's education sector.

## 🔍 Key Research Questions

- Are employees who only worked for the institutes for a short period resigning due to dissatisfaction?
- Are more experienced employees also resigning due to dissatisfaction?
- What patterns emerge across different career stages?

## 📊 Key Findings

- **51.6%** of established employees resign due to dissatisfaction
- **44.8%** of veteran employees resign due to dissatisfaction  
- **34.3%** of experienced employees resign due to dissatisfaction
- **30.2%** of new employees resign due to dissatisfaction

**Insight**: Contrary to expectations, more experienced employees show higher dissatisfaction rates, suggesting potential systemic workplace issues that compound over time.

## 📁 Dataset Information

### Data Sources
- **dete_survey.csv**: Exit survey responses from DETE (822 records, 56 columns)
- **tafe_survey.csv**: Exit survey responses from TAFE (702 records, 72 columns)

### Key Variables
- **Separation Type**: Reason for employment termination
- **Cease Date**: Year/month employment ended
- **Service Length**: Duration of employment
- **Demographics**: Age, gender, employment status
- **Dissatisfaction Factors**: Job satisfaction, work environment, recognition, etc.

## 🛠️ Technical Approach

### Data Cleaning & Preprocessing
- Standardized column names across datasets
- Handled missing values represented as "Not Stated"
- Filtered data to focus on resignations only
- Created consistent service length categories

### Feature Engineering
- **Career Stage Categorization**:
  - **New**: < 3 years of service
  - **Experienced**: 3-6 years of service  
  - **Established**: 7-10 years of service
  - **Veteran**: 11+ years of service
  - **Dissatisfaction Index**: Combined multiple dissatisfaction factors into a binary indicator

### Analysis Methods
- Exploratory data analysis with visualizations
- Cross-tabulation and pivot table analysis
- Comparative analysis across career stages and institutes

## 📈 Visualizations

The analysis includes:
- Box plots for tenure and cessation date distributions
- Bar charts showing dissatisfaction rates by career stage
- Comparative analysis between DETE and TAFE institutes

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **NumPy**: Numerical operations
- **Jupyter Notebook**: Interactive development environment


## 💡 Business Implications

### For HR Management:
- **Focus on mid-career retention**: Established and veteran employees show the highest dissatisfaction rates
- **Early intervention needed**: Address systemic issues before they compound over time
- **Career development**: Implement better progression opportunities for experienced staff

### For Policy Development:
- Review workplace policies affecting long-term employees
- Investigate specific dissatisfaction factors among established workers
- Develop targeted retention strategies for different career stages

## 🔍 Future Analysis Opportunities

- **Deeper demographic analysis**: Explore age and gender patterns
- **Seasonal trends**: Analyze resignation timing patterns
- **Department-specific analysis**: Compare different business units within DETE
- **Predictive modeling**: Build models to identify at-risk employees
- **Text analysis**: Analyze open-ended survey responses for deeper insights

