# HDSC-Introduction-to-Python-for-Machine-Learning-EDA-Quiz-Code

Exploratory Data Analysis on a dataset provided by the Food and Agriculture Organization of the United Nations

## Author

- [@Renikeji19](https://www.github.com/Renikeji19)

## EDA QUESTIONS
## 1. What is the total sum of Animal Fat produced in 2014 and 2017 respectively?
Fao_data.groupby(['Item'])[['Y2014','Y2017']].sum().loc['Animal fats']
Y2014    209460.54
Y2017    269617.53
Name: Animal fats, dtype: float64


