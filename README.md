# Insurance-Claims-Analysis
Multivariate Analysis

**Objective/Goal:**

Analyze auto insurance claims using LDA and QDA models and explore the relationship between predictor variables and likelihood of making a claim. Also, perform a canonical correlation analysis to understand the relationship between policy/policy holder info and attributes of the car.


**Data:**

A2claims.csv dataset containing synthetic but realistic data about auto insurance claims. The dataset includes variables such as age_of_policyholder, ncap_rating, nconvenience, torque.rpm, and whether a claim was filed or not.

Models and Tools Used: RStudio, LDA model, QDA model, and canonical correlation analysis.


**Code:**

The code for the analysis is not provided.


**Results:**

The LDA model was used to compute the lda scores for each observation, and a boxplot of the scores vs. the true claim value (0 or 1) was created. The lda scores vs. the posterior probability of a claim were also plotted, and a table of the predicted classes was made. The analysis showed a relationship between the predictor variables as a whole and the likelihood of making a claim. Additionally, correlations between each of the original variables and the LDA score were computed, and factors strongly related to the score were identified.

The QDA model was also considered for this dataset, and exploratory plots were used to evaluate its suitability.

Furthermore, a canonical correlation analysis was performed to understand the relationship between policy/policy holder info and attributes of the car. The analysis showed a significant relationship between the two matrices, and a biplot of the variables was produced. Additionally, the correlations between the original variables and the first canonical axis were computed, and the relationship embodied by the first canonical axis pair was interpreted.
