### WIDS Hackathon 2020

* **Last Sumission Model Summary**
  - **Kaggle score - .90150**
  - **Top Kaggle score - .9140**
  
  ### Pipeline Summary >
  - **Missing Values**
    - Random forest imputation was used to replace missing values
  - **Categorical Columns**
    - Dummy variables were created
  - **Correlated features**  
    - Correlated features above 0.90 were removed
  - **Feature Transformations**
   - PowerTransformer() was used
  - **Feature Reduction**
    - Random Forest, ANNOVA feature selection was used to rank variables
    - Most of the fields which had above 60% missing data were for the initial hour tests. Fields were removed based on suggestions from medical domain expertise.

  - **Modelling**
    - lightgbm
    - RandomForest 
    - XGBoost 
  - Best parameters obtained were:
  ![image](https://user-images.githubusercontent.com/47410643/85172344-dd601700-b23e-11ea-9974-dc0ad39ef5c7.png)
  
  - kaggle score:
  ![image](https://user-images.githubusercontent.com/47410643/85172408-fe286c80-b23e-11ea-9743-dfb975376110.png)

  - **Please check the presentation for further details. Youtube link: https://www.youtube.com/watch?v=dCoMEAPp2s0**
