#  Exploratory Data Analysis (EDA) for Infant Mortality

## **Overview:**
This project focuses on conducting exploratory data analysis (EDA) on infant mortality data. The dataset provides insights into infant mortality rates and related statistics categorized by year and maternal race or ethnicity.

## **Objective:**
The primary objective of this project is to gain a deeper understanding of infant mortality trends and disparities across different maternal racial or ethnic groups. By analyzing the dataset, we aim to uncover patterns, trends, and relationships that can inform public health policies and interventions aimed at reducing infant mortality rates.

## **Approach:**
The project will involve analyzing various aspects of the dataset, including:
- Exploring trends in infant mortality rates over time.
- Investigating differences in mortality rates among different racial or ethnic groups.
- Identifying factors that may contribute to variations in infant mortality rates.
- Examining the relationship between the number of live births and infant mortality rates.

## **Tools and Techniques:**
We will utilize Python programming language along with libraries such as pandas, NumPy, and Matplotlib for data manipulation, analysis, and visualization. Exploratory data analysis techniques such as data visualization, statistical analysis, and data summarization will be employed to uncover insights from the dataset.




## Dataset Information
This dataset consists of a pandas DataFrame containing 48 entries and 9 columns. It offers insights into infant mortality rates and associated statistics categorized by year and maternal race or ethnicity.

### Data Columns
1. **Year**: Year of the data entry.
2. **Maternal Race or Ethnicity**: Race or ethnicity of the mother.
3. **Infant Mortality Rate**: Number of infant deaths per 1,000 live births.
4. **Neonatal Mortality Rate**: Number of neonatal deaths (within the first 28 days of life) per 1,000 live births.
5. **Postneonatal Mortality Rate**: Number of postneonatal deaths (from 28 days to 1 year of age) per 1,000 live births.
6. **Infant Deaths**: Total number of infant deaths.
7. **Neonatal Infant Deaths**: Total number of neonatal infant deaths.
8. **Postneonatal Infant Deaths**: Total number of postneonatal infant deaths.
9. **Number of Live Births**: Total number of live births.

    
[GitHub]( https://github.com/zulqarnainalipk) |
[LinkedIn]( https://www.linkedin.com/in/zulqarnainalipk/)
### Data Types
- **int64**: Integer data type.
- **float64**: Floating-point numeric data type.
- **object**: Categorical data type (specifically, text strings indicating race or ethnicity).

### Missing Values
- **Year**: 0
- **Maternal Race or Ethnicity**: 0
- **Infant Mortality Rate**: 8
- **Neonatal Mortality Rate**: 8
- **Postneonatal Mortality Rate**: 9
- **Infant Deaths**: 8
- **Neonatal Infant Deaths**: 8
- **Postneonatal Infant Deaths**: 8
- **Number of Live Births**: 0

### Filling of Missing Values
Missing values are filled using the average values of each respective column to maintain data consistency and accuracy without significant alterations.
👉 [check this project on Kaggle](https://www.kaggle.com/code/zulqarnainalipk/eda-for-infant-mortality) 👈

## Usage
To utilize this dataset:

```python
import numpy as np  # Numerical operations
import pandas as pd  # Data manipulation
import matplotlib.pyplot as plt  # Data visualization

# Ignore warnings
import warnings
warnings.filterwarnings('ignore')

# Read the dataset
df = pd.read_csv('/kaggle/input/infant-mortality/infant-mortality-1.csv')
```

## Exploratory Data Analysis (EDA)
You can perform exploratory data analysis using various techniques and visualizations.

1. **Bar Plots for Mortality Rates by Ethnicity**: Visualize mortality rates by ethnicity.
2. **Pie Chart for Ethnicity Distribution**: Understand the distribution of ethnicity in the dataset.
3. **Line Plot for Infant Mortality Rate Over Time**: Observe the trend of infant mortality rate over the years for different ethnicities.
4. **Bar Plot of Average Yearly Deaths by Ethnicity**: Analyze the average yearly deaths for each ethnicity.
5. **Bar Plot of Average Yearly Live Births by Ethnicity**: Explore the average yearly live births for each ethnicity.
6. **Scatter Plot for Infant Mortality Rate vs. Number of Live Births**: Investigate the relationship between infant mortality rate and the number of live births.

## Keep Exploring! 👀

Thank you for delving into this notebook! If you found it insightful or beneficial, I encourage you to explore more of my projects and contributions on my profile.

👉 [Visit my Profile](https://www.kaggle.com/zulqarnainalipk) 👈

[GitHub]( https://github.com/zulqarnainalipk) |
[LinkedIn]( https://www.linkedin.com/in/zulqarnainalipk/)

## Share Your Thoughts! 🙏

Your feedback is invaluable! Your insights and suggestions drive our ongoing improvement. If you have any comments, questions, or ideas to contribute, please feel free to reach out.

📬 Contact me via email: [zulqar445ali@gmail.com](mailto:zulqar445ali@gmail.com)

I extend my sincere gratitude for your time and engagement. Your support inspires me to create even more valuable content.
Happy coding and best of luck in your data science endeavors! 🚀

