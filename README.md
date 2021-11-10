ML TECHNICS IN SALES AND MARKETING<br/>
<br/>
In this section I am focusing on data anlysis and machine learning technics, which can be used in sales <br/>
and marketing management.<br/>
<br/>
1.) GROCERY MARKET BASKET ANALYSIS<br/>
<br/>
In this project I am focusing on how market basket analysis improve 4P strategies. I determine ASSOCIATION<br/>
I determine ASSOCIATION rules, ANTICEDENT AND CONSEQUENT elements, and calculate SUPPORT, CONFIDENCE   <br/>
and LIFT indicators in two different ways, which provide useful information for the companies to plan   <br/>
their marketing strategy in fields like:
<br/>
- Product placement<br/>
- Promotional discount<br/>
- POS (point of sales) advertisement <br/>
- Product boundling<br/>
- ANTICEDENT AND CONSEQUENT products can be combined to a new product<br/>
 <br/>
<br/>
2.) E-COMMERCE RETAIL BUSINESS ANALYSIS<br/>
In this project I am working with a huge retail data trying out various technics to explore useful <br/>
connections and relations among the data including:<br/>
<br/>
- Choropleth to check the geographical distribution of the purchases <br/>
- Kmeans clustering to define customer clusters on the basis of how many invoices (say one invoice per <br/>
   customer means one shopping) one customer has and what are the total value of the invoices.<br/>
- Text mining technics to find product categories<br/>
- Market basket anylsis to get to know the buying patterns of the customers and promote cross selling of <br/>
  various products<br/>
   <br/>
 3.) CREDIT CARD FRAUD DETECTION
 The dataset from Kaggle contains transactions made by credit cards in September 2013 by European cardholders. <br/>
 The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. The <br/>
 reason why I was interested in this dataset is how to find a trade-off between recall and precision or in<br/>
   other words (in binary classification) between sensitivity and specificity. As As we have the task to predict <br/>
   the fraudulent transactions as precise as possible, we have to give up some precision percent to increase the <br/>
   recall result, and decrease the sum of the False Negative predictions. Please check the models and the<br/>
   results:<br/>
   
   |           Models           | Precision | Recall |False Negative Sum | 
|----------------------------|--------------------|-------------------|--------|      
| Logistic Regression (Sklearn) |        89.86%        |       67.39%        |  30 |    
| Logistic Regression (Sklearn) with 0.1 threshold value|        79.79%        |      81.52%       |  17 |        
| Random Forest Classifier |        95.00%       |       82.61%        |  16 |       
| Random Forest Classifier with 0.4 threshold value |        95.18%      |       85.87%        |  11 |   
| Feed-forward neural network|        0.60        |       0.52        |  0.009 |        
|         XGBoost with cross-validation and YJ transformation          |        0.60        |       0.50        |  0.055 |     
| Random Forest with Yeo-Johnson transformation and K-fold cross validation |0.59 | 0.50 | 0.065 |  
  
 
