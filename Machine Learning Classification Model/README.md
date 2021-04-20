### Using the following machine learning models to predict whether a customer will purchase or not.
### It's an imbalanced classification problem (85% not purchase vs. 15% purchase)
<br>

#### **XGBoost**
Before tuning, the testing accuracy is 90%, recall score of not purchase and purchase = 96% & 59% respectively. <br>
After tuning, the testing accuracy is 87%, recall score of not purchase and purchase = 88% & ***80%*** respectively. <br>
**recall: fraction of truly relevant results returned**

#### **CatBoost**
Before tuning, the testing accuracy is 90%, recall score of not purchase and purchase = 96% & 58% respectively. <br>
After tuning , the testing accuracy is 85%, recall score of not purchase and purchase = 84% & ***86%*** respectively.

#### **Logistic Regression**
Before tuning, the testing accuracy is 88%, recall score of not purchase and purchase = 97% & 36% respectively. <br>
After tuning, the testing accuracy is 86%, recall score of not purchase and purchase = 91% & ***60%*** respectively.
