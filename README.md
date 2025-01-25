# Wine Quality Analysis Project

## Project Background
This comprehensive data science project explores the intricate world of wine quality through advanced analytics and machine learning techniques. Focusing on Portuguese Vinho Verde wines, the research delves into understanding how physicochemical properties influence wine quality.

## Dataset Details
### Source
- **Origin**: UCI Machine Learning Repository
- **Created By**: Paulo Cortez, Antonio Cerdeira, Fernando Almeida, Telmo Matos, and Jose Reis (2009)
- **Wine Variants**: Red and White Portuguese Vinho Verde

### Dataset Characteristics
- **Total Instances**: 6,497
  - Red Wines: 1,599
  - White Wines: 4,898
- **Features**: 11 physicochemical properties
- **Target Variable**: Wine quality score (0-10)

### Physicochemical Properties Analyzed
1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulphates
11. Alcohol

## Project Objectives
- Perform comprehensive exploratory data analysis
- Conduct statistical comparisons between red and white wines
- Investigate correlations among wine properties
- Develop predictive models for wine quality
- Apply advanced clustering techniques to identify wine characteristics

## Methodology

### 1. Exploratory Data Analysis
- Descriptive statistics
- Data visualization
- Distribution analysis of wine properties

### 2. Statistical Analysis
- Comparative t-tests between red and white wine properties
- Pearson correlation coefficient calculations
- Identifying most significant wine characteristics

### 3. Predictive Modeling
#### Linear Regression
- Binary classification of wine quality (POOR vs. GOOD)
- Feature standardization
- Forward selection using Akaike Information Criterion (AIC)

#### Random Forest Regression
- Model training with varying tree counts (5, 10, 50, 100, 500, 1000, 5000)
- Performance evaluation
- Variable importance analysis

### 4. Clustering Techniques
#### K-means Clustering
- Determining optimal number of clusters
- Identifying discriminatory variables
- Visualization of cluster characteristics

#### Gaussian Mixture Model
- Alternative clustering approach
- Comparative analysis with K-means results

## Key Technological Components
- **Programming Language**: Python
- **Data Manipulation**: pandas, NumPy
- **Machine Learning**: scikit-learn
- **Visualization**: Matplotlib, Seaborn

## Installation and Setup
1. Clone the repository
2. Create a virtual environment
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run Jupyter Notebook

## Reproducibility
- Consistent random state (random_state=101)
- Multiple model runs for robust results
- Detailed documentation of methodology

## Key Findings and Insights
- Comprehensive analysis of wine quality determinants
- Predictive models for wine quality assessment
- Identification of most influential physicochemical properties
- Clustering insights into wine characteristics

## Limitations and Future Work
- Focus on physicochemical properties
- Potential for incorporating additional data sources
- Exploration of advanced machine learning techniques

## Citation
Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Modeling wine preferences by data mining from physicochemical properties. Decision Support Systems, 47(4), 547-553.

## Acknowledgments
- UCI Machine Learning Repository
- Original dataset creators
- Open-source libraries and tools used
