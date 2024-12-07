# Classify-Tumor
This project involves classifying whether a tumor is benign or malignant based on features like size and texture. This is a supervised learning classification problem, requiring us to take the following steps:

> Step 1: Collect data with features and labels (benign or malignant). 
> Step 2: For a new tumor, calculate the distance to each tumor in the training set. 
> Step 3: Select the K closest tumors and use the majority label (since this is a classification problem; would use the average value if it were a regression task) to predict the class.

## Dataset Description
The breast cancer dataset was used for this project.
It includes 30 numeric features (e.g., radius, texture, smoothness, symmetry, etc.).
The target variable is binary (1 = malignant, 0 = benign).
This dataset served well for a KNN project as it includes various characteristics of tumors, allowing for a practical illustration of classification with KNN.

Tools/Softwares/Packages Used
Python was used, along with libraries such as numpy, pandas, matplotlib, Seaborn and sklearn.

## Key Insights for Investigation/Analysis
To investigate the relationship between the size and texture of a tumor to its being diagnosed as malignant or benign.

## Summary of Findings
The trained KNN model was able to make predictions of maligancy or benigncy of a tumor when sets of predictor values were passed through it.

