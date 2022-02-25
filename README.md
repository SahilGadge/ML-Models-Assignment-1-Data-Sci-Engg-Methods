# About Data
 Dataset Source: http://archive.ics.uci.edu/ml/datasets/Air+Quality#

This dataset contains following Attributes.

1. Date (DD/MM/YYYY)
2. Time (HH.MM.SS)
3. CO = Carbon Monoxide
4. PT08.S1 = Tin Oxide
5. NMHC = Non Metanic HydroCarbons
6. C6H6 = Benzene
7. PT08.S2 = Titania
8. NOx = Nitrogen oxide
9. PT08.S3 = Tungsten Oxide (nominally NOx targeted)
10. NO2 = Nitrogen Dioxide
11. PT08.S4 = Tungsten Oxide (nominally NO2 targeted)
12. PT08.S5 = Indium Oxide
13. T = Temperature in °C
14. RH = Relative Humidity
15. AH = Absolute Humidity

Conclusion- 

I successfully performed these ML operations like Data Cleaning and Feature Selection and understood dataset more. From such operation I found following



1.  'tinOxide', 'NMHC', 'C6H6', 'titania', 'NOx', 'NO2', 'tungstenOxideNO2', 'indiumOxide', 'T','RH', 'AH' are useful independent variables for predicting 'CO'(Carbon Monoxide) dependent variable.

2.   Dataset does contain missing values and variable 'NMHC' contain 90% missing values so it was not useful for prediction.

3. Training and testing dataset does have different data.

4. Independent variables like **'titania', 'tinOxide', 'indiumOxide'** were highly correlated with **'C6H6'** and therefore not contributing much towards prediction of 'CO' so we droped them.

5.   **'C6H6' , 'NOx' , 'NO2' , 'tungstenOxideNO2'** these predictor variables are most important in order to predict 'CO' our dependent variable

6.   Range of Independent variables does makes sense and there are no unrealistic entries.

7.   Independent variables have Gamma, Chi2 and Exponential power distribution.
