# 🏙️ Boston Crime Insights: Predictive Modeling of Crime Rates

## CHOOSE THE SECTION YOU WANT TO JUMP TO:

<p align="center">
  <a href="#-project-overview">
    <img src="https://img.shields.io/badge/-Project%20Overview-blue?style=for-the-badge" alt="Project Overview">
  </a>
  <a href="#-business-impact">
    <img src="https://img.shields.io/badge/-Business%20Impact-green?style=for-the-badge" alt="Business Impact">
  </a>
  <a href="#-key-findings">
    <img src="https://img.shields.io/badge/-Key%20Findings-red?style=for-the-badge" alt="Key Findings">
  </a>
  <a href="#-conclusion">
    <img src="https://img.shields.io/badge/-Conclusion-purple?style=for-the-badge" alt="Conclusion">
  </a>
</p>

## 📊 Project Overview

This project analyzes the Boston dataset to predict per capita crime rates using various urban and socioeconomic factors. By employing statistical learning techniques, we aim to uncover key predictors of crime rates and provide actionable insights for urban planning and policymaking.

## 💼 Business Impact

Understanding the factors that influence crime rates can have significant implications for:

- 🏗️ Urban development strategies
- 👮 Resource allocation for law enforcement
- 📜 Policy-making for crime prevention
- 🏘️ Real estate development and investment decisions

## 📂 Dataset

The Boston dataset is used for this analysis. It is under the library "MASS" in "R". It contains information about crime rates and various urban characteristics in the Boston area.

### Features

| Variable | Description |
|----------|-------------|
| CRIM | Per capita crime rate by town |
| ZN | Proportion of residential land zoned for lots over 25,000 sq.ft. |
| INDUS | Proportion of non-retail business acres per town |
| CHAS | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| NOX | Nitric oxides concentration (parts per 10 million) |
| RM | Average number of rooms per dwelling |
| AGE | Proportion of owner-occupied units built prior to 1940 |
| DIS | Weighted distances to five Boston employment centers |
| RAD | Index of accessibility to radial highways |
| TAX | Full-value property-tax rate per $10,000 |
| PTRATIO | Pupil-teacher ratio by town |
| BLACK | 1000(Bk - 0.63)^2 where Bk is the proportion of Black people by town |
| LSTAT | % lower status of the population |
| MEDV | Median value of owner-occupied homes in $1000's |

## 🔬 Methodology

1. **Exploratory Data Analysis**: Examined the relationships between variables and the target (crime rate).
2. **Simple Linear Regression**: Fitted individual models for each predictor.
3. **Multiple Linear Regression**: Developed a comprehensive model using all predictors.
4. **Non-linear Analysis**: Investigated potential non-linear relationships using polynomial terms.
5. **Other methods used**: Best subset selection, the lasso, ridge regression, and PCR.

## 🔑 Key Findings

1. **Significant predictors** of crime rates include:
    - Proportion of residential land zoned for large lots (ZN)
    - Weighted distances to employment centers (DIS)
    - Index of accessibility to radial highways (RAD)
    - Proportion of Black residents (BLACK)
    - Median value of homes (MEDV)

2. **Non-linear relationships** were observed with:
    - Nitric oxides concentration (NOX)
    - Proportion of old housing (AGE)
    - Distance to employment centers (DIS)
    - Pupil-teacher ratio (PTRATIO)

3. The Charles River dummy variable (CHAS) showed **no significant relationship** with crime rates.

## 💡 Insights and Recommendations

1. **Urban Planning**: Focus on creating mixed-use developments that reduce distances to employment centers.
2. **Education**: Investigate the impact of pupil-teacher ratios on community well-being and crime rates.
3. **Transportation**: Consider the complex relationship between highway accessibility and crime rates in infrastructure planning.
4. **Environmental Policy**: Address air pollution (NOX levels) as part of a holistic approach to improving urban living conditions.
5. **Housing Policy**: Develop strategies to address the link between older housing stock and crime rates.

## 🚀 Business Applications

For urban development companies, real estate firms, or city planners:

1. Use the model to assess potential crime risk in areas considered for development.
2. Identify key areas for community investment to potentially reduce crime rates.
3. Inform strategies for balanced urban growth that considers socioeconomic factors.

## 🛠️ Tools Used

![R](https://img.shields.io/badge/-R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/-RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## ⚙️ Installation and Usage

1. Clone the repository:
2. Install R and necessary packages:
```R
install.packages("MASS")
```
3. Run the script
```
Rscript boston_crime_analysis.R
```

## 🎓 Conclusion

This analysis demonstrates the complex interplay of factors influencing urban crime rates. While certain variables like zoning, accessibility, and housing values show clear correlations, the presence of non-linear relationships highlights the need for nuanced approaches to urban planning and policy-making. By understanding these dynamics, stakeholders can make more informed decisions to foster safer, more prosperous urban environments.

