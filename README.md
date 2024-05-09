# Student Performance Classification

This repository aims to implement various classification models to predict whether a student will fail or not. The project involves employing different traditional classification models with parameter tuning using GridSearchCV and utilizing a neural network for classification. The code encompasses preprocessing, exploratory data analysis (EDA), model training, and evaluation

## Methodology
 - Preprocessing: Data preprocessing techniques are applied to clean, transform, and prepare the dataset for modeling.
 - Exploratory Data Analysis (EDA): Exploring the dataset to gain insights into the distribution of features, correlations, and potential patterns.
 - Model Training: Various traditional classification models are trained on the dataset using GridSearchCV for hyperparameter tuning to optimize model performance.
 - Neural Network: A neural network architecture is employed for classification, leveraging TensorFlow/Keras.
 - Evaluation: Model performance is evaluated using appropriate metrics to assess their effectiveness in predicting student failure.

## Note
The predictive performance of the models may be influenced by the strong correlation between the target attribute G3 and the attributes G1 and G2. Considerations should be made when interpreting the results, and it's advisable to explore feature engineering techniques or alternative modeling approaches to enhance predictive accuracy.
