# Python Project for Data Science – ENSAE – 2A

**_Authors: ABE Kevin, DEMGNE Lisa, ZAIDAN Oscar_**

## Topic: **Analysis of Factors Influencing the Severity of Road Traffic Accidents in France**

Road traffic accidents have been one of the major concerns of French authorities for many years. From the post-war period to the present day, around 700,000 people have been killed on French roads (OSNIR). A wide range of policies have been implemented to combat this issue. For example, the points-based driving license system was introduced in 1992 to penalize dangerous driving behavior. In 2001, the National Road Safety Council (CNSR) was created. It brings together the main road safety stakeholders, with diverse expertise and perspectives, in order to debate, exchange ideas, and develop concrete proposals for the government to reverse the trend in road mortality.

The set of measures implemented by the CNSR led to a 51% decrease in road deaths between 2002 and 2012, and a further 11% decrease between 2012 and 2019. It should be noted that national road safety statistics are collected, processed, analyzed, and disseminated by the National Interministerial Road Safety Observatory (ONISR), ensuring continuous monitoring of trends in road traffic fatalities.

France signed the European declarations of Valletta in 2017 and Stockholm in 2020. Through these commitments, it has adopted the long-term “Vision Zero” strategy (zero deaths and zero serious injuries by 2050) and has aligned itself with the United Nations road safety objective of halving road deaths and serious injuries during the current decade of action (by 2030, using 2019 as the reference year, before the pandemic).

The objective of this project is to analyze data on injury-causing road traffic accidents produced by the ONISR and to identify the factors that may influence accident severity.

## Motivation

A snapshot of accident statistics for a given year provides law enforcement agencies with insights into the effectiveness of measures implemented to reduce road accidents. In addition, identifying risk factors can help optimize police patrol deployment and better target awareness and prevention efforts.

## Installation

The packages used in this project are:
- requests  
- matplotlib  
- os  
- geopandas  
- pandas  
- plotly  
- folium  
- seaborn  
- io  
- tabulate  
- scipy  
- numpy  
- sklearn  

The following packages must be installed beforehand: requests, io, os, tabulate, scipy.

## Descriptive Statistics

For data description, we mainly rely on univariate and bivariate descriptive analysis methods.

## Modeling

We used a multivariate logistic regression model (since the target variable, accident severity level, has more than two categories). This model allows us to identify the key determinants of accident severity and to estimate the probability of severe outcomes based on explanatory variables.

## Data Sources

- [Annual database of injury road traffic accidents](https://www.data.gouv.fr/fr/datasets/bases-de-donnees-annuelles-des-accidents-corporels-de-la-circulation-routiere-annees-de-2005-a-2023/?reuses_page=1#/resources)  
- [Official Geographic Code](https://www.insee.fr/fr/metadonnees/source/operation/s2085/bases-donnees-ligne): used to obtain INSEE department codes and names  
- [Population data by department in France](https://www.insee.fr/fr/statistiques/fichier/7752095/estim-pop-dep-sexe-gca-1975-2024.xls)

Download links for the 2023 injury road traffic accident datasets:
- [User database](https://www.data.gouv.fr/fr/datasets/r/68848e2a-28dd-4efc-9d5f-d512f7dbe66f)  
- [Vehicle database](https://www.data.gouv.fr/fr/datasets/r/146a42f5-19f0-4b3e-a887-5cd8fbef057b)  
- [Location database](https://www.data.gouv.fr/fr/datasets/r/8bef19bf-a5e4-46b3-b5f9-a145da4686bc)  
- [Accident characteristics database](https://www.data.gouv.fr/fr/datasets/r/104dbb32-704f-4e99-a71e-43563cb604f2)

## References

- [Lasso regression](https://www.ibm.com/fr-fr/topics/lasso-regression)  
- [Logistic regression with scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)  
- Description of the annual injury road traffic accident databases (2005–2023), ONISR (available in the repository)

## Project Workflow

- The project is explored by running the notebook cells sequentially.
- Depending on the execution environment, the modeling section may take a long time or run indefinitely. In such cases, it may be necessary to increase computational resources or download and run the notebook locally.

## Project Limitations

The results of this project could be improved and refined. Possible extensions include:
- Using tools such as black boxes or onboard cameras to better understand driver behavior before, during, and after accidents.
- Conducting more in-depth studies on accidents involving public transport vehicles, heavy vehicles, and wrong-way driving, in order to better understand their causes and implement appropriate preventive measures.

## Contacts

- lisabrice.demgnewafeu@ensae.fr  
- oscar.zaidan@ensae.fr  
- kevin.abe@ensae.fr  
