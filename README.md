# Obesity-Classification-Machine-Learning
- Prediction of levels of obesity by using machine learning classification models.

Data Source: https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+

The dataset contains data concerning obesity levels, physical condition, and eating habits of individuals in Mexico, Peru, and Colombia. The data was acquired from an online survey. The data contains 17 attributes and 2111 records, the records are labeled with the class variable NObesity (Obesity Level), that allows classification of the data using the values of Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III.

Domain Infromation: 
https://www.thelancet.com/campaigns/kidney/updates/obesity-and-overweight-populations-in-latin-america
https://pubmed.ncbi.nlm.nih.gov/9732306/

In 2014, more than 300 million adults in Latin America, were overweight. Of these more than 100 million were obese. Obesity has become a major health challenge in Latin America. Around 57% (302 million) of the region’s adult population (54% men and 70% of women) are overweight, and 19% (100.8 million) are obese (14.6% in men and 24% in women).Similar to other low-middle-income countries, overweight (61% in women and 54% in men) and obesity (24% in women and 14.6% in men) are more prevalent in women than in men. Fourteen countries in Latin America have a female prevalence greater than 20%. The highest prevalence of obesity in the adult population is found in El Salvador (33%) and Paraguay (30.1%) for women, and in Uruguay (23.3%) and Chile (22.0%) for men. The prevalence of overweight and obesity in Latin American children is also remarkably high (16%). It ranges from more than 12% for girls in Chile, Uruguay and Costa Rica to less than 5% in Bolivia, Ecuador, Peru, Honduras, and Guatemala. The highest prevalence of obesity in children is found in Chile (11.9%,) and Mexico (10.5%) in boys, and in Uruguay (18.1%,) and Costa Rica (12.4%) in girls.

## Data Preparation
![](pic/pic1.png)
![](pic/pic2.png)

## Exploratory Data Analysis
![](pic/pic3.png)
![](pic/pic4.png)
![](pic/pic5.png)
![](pic/pic6.png)
![](pic/pic7.png)
![](pic/pic8.png)
![](pic/pic9.png)
![](pic/pic10.png)
![](pic/pic11.png)
![](pic/pic12.png)
![](pic/pic13.png)
![](pic/pic14.png)

## Data Preprocessing
- Identify outliers/Remove outliers
- Categorical Variables Transformation: One Hot Encoding, Ordinal Encoding, Label Encoding
- Check correlation/multicollinearity

## Data Modeling
### KNN Classifier
![](pic/pic15.png)

### RandomForest
![](pic/pic16.png)
![](pic/pic17.png)

### DecisionTree
![](pic/pic18.png)
![](pic/pic19.png)

### Bagging
![](pic/pic20.png)

## Implementing Machine Learning Pipeline

![](pic/pic21.png)

![](pic/pic22.png)
![](pic/pic23.png)
![](pic/pic24.png)
