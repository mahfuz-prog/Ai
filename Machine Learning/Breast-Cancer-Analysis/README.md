<p align="center">
<h1 align="center">Breast-Cancer-Analysis</h1>
</p>

<a href='https://colab.research.google.com/drive/1zOEo6c-Wury82nErLOod-EBIIegXnito?usp=sharing'>Google colaboratory notebook<a/>

### Breast Cancer Analysis using machine learning algorithm XGBoost (eXtreme Gradient Boosting) to classify Benign or Malignant.


- <h4> Step 1: I have used a <a href='https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data', target="_blank">dataset<a/> from kaggle and preprocessed.
- <h4> Step 2: After that I select top 25 features highly correlated with target attribute using sklearn library for avoid overfitting.
- <h4> Step 3: Then I used XGBoost-an optimized distributed gradient boosting library for my machine learning model.
- <h4> Step 4: Displyed test set results in a pandas dataframe where 1st column consist of test result exact values and 2nd column our model prediction.
- <h4> Step 5: Finally get,
``` 
  - Accuracy: 97.4%
  - K-Fold Cross-validation-score: 96.28% with Standard Deviation: 2.59%.
  - Confusion matrix : [[66  1]
                        [2 45]]
   
```
  
  
  
  
  
  
  
  
  
  
