# Data exploration and cleaning

In this project, I am going to walk you through the end-to-end data analysis process with Python and the OpenFoodFacts Dataset. 
The different goals are :

1. Process the dataset, by identifying relevant variables for future processing
2. Clean data by highlighting any missing values and identifying and quantifying possible outliers for each variable
3. Automate these treatments to avoid repeating these operations
4. Throughout the analysis, produce visualizations to better understand the data
5. Perform a univariate analysis for each variable of interest, in order to synthesize its behavior
6. Confirm or refute hypotheses using multivariate analysis
7. Perform the appropriate statistical tests to verify the significance of the results

# Cleaning steps description

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_desc.png" width="1200">

# Results overview

## Univariate analysis

### Nutriscore

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_ns.png" width="200">
<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_ns_res.png" width="600">

1. The nutriscore_score variable is a quantitative variable whose empirical distribution is between -15 and 40
2. The lower its value, the healthier the product
3. The distribution is bimodal with an overrepresentation of nutriscores B and D
4. On average, the nutriscore is 8 (C)
5. With a median of 7, half of the products have a nutriscore between A and C
6. Finally, with Q3 equal to 14, we can say that 75% of the products have a nutriscore less than or equal to D

### The place of organic products

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_organic.png" width="600">

## Bivariate analysis

### Nutriscore vs saturated fat

Assumption: The lower the saturated fat, the healthier the product

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_ns_ft.png" width="600">

### Correlation circle

<img src="https://raw.githubusercontent.com/jamesbarthelemy/images/main/p2_cc.png" width="600">
