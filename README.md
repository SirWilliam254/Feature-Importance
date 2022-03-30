![GitHub](https://img.shields.io/github/license/SirWilliam254/Feature-Importance?color=success&style=plastic)
# Feature-Importance

- permutation importance
[EXAMPLE! ](https://sirwilliam254.github.io/Feature-Importance/feat.html)

As the name permutation suggests, this method shuffles the values in a certain column i.e feature and a prediction is made while holding other features as they are. By shuffling the data in such a manner we expect the prediction accuracy to drop as the values are different all together, this procedure is repeated and an average is calculated from the same. The method is applied to all other features and their importance is rated. We have an output which shows the confidence i.e + or - some value of how the feature affects the prediction accuracy.

Output from the coding example above:
![image](https://github.com/SirWilliam254/Feature-Importance/blob/main/permutationimporatance.png)

As from the screenshot above we can see the most usefull feature to the least useful in that sequence

### DEPENDENCIES
- pandas
- eli5
- sklearn

- # PDP

Partial dependence plots demonstrate how a property influences the prediction. Partial dependency charts, like permutation importance, are computed after a model has been fitted. The model is fitted to real-world data that has not been modified in any manner.

[Coding EXAMPLE!](https://sirwilliam254.github.io/Feature-Importance/pdp.html)

Output example of a pdp plot, more information about it in the link above.

![image](https://github.com/SirWilliam254/Feature-Importance/blob/main/pdp1.PNG)

### DEPENDENCIES
- pandas
- sklearn
- matplotlib
- pdpbox

- # SHAP
SHAP Values (an acronym from SHapley Additive exPlanations) break down a prediction to show the impact of each feature.

[Coding EXAMPLE!](https://sirwilliam254.github.io/Feature-Importance/shap.html)

![image](https://github.com/SirWilliam254/Feature-Importance/blob/main/one.PNG)
### DEPENDENCIES
- shap
- pandas
- numpy
