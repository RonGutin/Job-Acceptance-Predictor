# Job Predictor  

This project uses ML techniques to predict job categories based on given features. It includes data preprocessing, exploratory data analysis, and the implementation of various classification algorithms.  

## Features  
- Data preprocessing with scaling and transformations.  
- Exploratory Data Analysis for feature insights.  
- ML models such as:  
  - Logistic Regression  
  - Random Forest 
  - K-Nearest Neighbors (KNN)  
  - AdaBoost  
- Model evaluation using metrics like ROC-AUC, confusion matrix, and learning curves.  

## Project Structure  
- `Final_Job_Predictor.ipynb`: Main notebook containing all steps from data loading to model evaluation.  
- `train.csv`: Training dataset.  
- `test.csv`: Testing dataset. 

## Results  
- The notebook includes visualization of key performance metrics and model comparisons to help identify the best-performing model.  
Key Finding: AdaBoost emerged as the best-performing model based on its superior ROC-AUC score and overall accuracy during testing. It effectively handled imbalanced data and demonstrated consistent performance across folds in cross-validation.

## Contributing  
Feel free to fork this project and submit pull requests. Suggestions and enhancements are welcome!  

## Authors
[Ron Gutin](https://github.com/RonGutin)
[Elad Krips](https://github.com/maxorelad)