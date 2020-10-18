# Mushroom-Classification
Classifying whether a mushroom is edible or poisonous based on the data provided by the UCI Machine Learning Repository.

# Content

This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy. (Description by UCI Machine Learning Repository)

# Task

Predict whether a mushroom is `edible` or `poisonous`.

# Approach

* Data Exploratory Analysis
* Data Formatting
* Experimentation

# Conclusion

Model                     Accuracy      F1-Score
Logistic Regression        94.9%          0.94
Support Vector Machine     98.6%          0.99
Keras Classifier           100%           1.0

In conclusion, the Neural Network model performed the best on the test data, followed by the Support Vector Classifier.


