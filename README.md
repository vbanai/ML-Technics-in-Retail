ML TECHNICS IN SALES AND MARKETING<br/>
<br/>
In this section I am focusing on data anlysis and machine learning technics, which can be used in sales <br/>
and marketing management.<br/>
<br/>
1.) A/B TESTING<br/>
<br/>
This project contains two A/B tests. In the first one I evaluate and compare 3 marketing campaigns. Dataset is <br/>
downloaded from Kaggle. The scenario is that a fast food chain plans to add a new item to its menu. One of the <br/>
common questions being what promotion has the greatest effect on sales. In order to determine this, the new item <br/>
is introduced at locations in several randomly selected markets using three different marketing campaigns. I carry out <br/>
A/B testing among the promotion campaigns to see which is the best option. Here the key value I am <br/>
performing the AB test is continous. <br/>
The second AB test is carried out on descrete value. Task is to check two different WEBDESIGN, where I test a banner <br/>
with green button or red button. The metric will be the click -through rate, showing how many people clicked on the <br/>
banner with red button and how many people clicked on the banner with green button. Both banners take to the same  <br/>
webpage. By means of the A/B test we can decide which button is more effective and produce more click through rate .<br/>
in the real life.<br/>
<br/>
2.) RECOMMENDATION SYSTEMS<br/>
<br/>
A) GROCERY MARKET BASKET ANALYSIS<br/>
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
3.) E-COMMERCE RETAIL BUSINESS ANALYSIS<br/>
<br/>
In this project I am working with a huge retail data trying out various analysis to explore useful <br/>
connections and relations among the data including:<br/>
<br/>

- Sales and revenue analysis:<br/>
 Describing the transactions by geographical distribution, by invoice amount and volume, by annual <br/>
 distribution and detecting loyal customers<br/>

- Segmentation: <br/>
 Creating consumer clusters, detecting loyal and satisfied customers, and detecting clusters that <br/>
 are lucrative for the shop regarding revenue <br/>

- Text mining: Find popular product categories based on the line item descriptions <br/>

- Market basket analyis: 
 Getting to know the buying patterns of the customers to promote cross selling of  <br/>
 products to boost the revenue and build loyalty and satisfaction.<br/>
<br/>
 4.) CREDIT CARD FRAUD DETECTION<br/>
 <br/>
 The dataset from Kaggle contains transactions made by credit cards in September 2013 by European cardholders. <br/>
 The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. The <br/>
 reason why I was interested in this dataset is that I want to know how I can find a trade-off between <br/>
  recall and precision or in other words (in binary classification) between sensitivity and specificity.  <br/>
  As we have the task to predict the fraudulent transactions as precise as possible, we have to give up  <br/>
  some precision percent to increase the recall result, and decrease the sum of the False Negative <br/>
  predictions. Please check the models and the results:<br/>
   
   |           Models           | Specificity | Sensitivity |
|----------------------------|--------------------|-------------------|
| Logistic Regression (Sklearn) |        89.86%        |       67.39%        |    
| Logistic Regression (Sklearn) with 0.1 threshold value|        79.79%        |      81.52%       |        
| Random Forest Classifier |        95.00%       |       82.61%        |      
| Random Forest Classifier with 0.4 threshold value |        95.18%      |       85.87%        |   
| XGBoost|        96.30%       |       84.78%        |  
| XGBoost with 0.4 threshold | 96.34%  | 85.87% |  
|       XGBoost with SMOTE Technique         |        99.80%       |       99.43%        |   
|        XGBoost with SMOTE Technique and 0.4 threshold          |        99,64%     |       99.79%       |   
|         XGBoost with SMOTEENN Technique          |        99.69%      |       99.45%        | 
|         Neural Network with class weight          |        90.43%      |       66.67%        | 
|         Neural Network with simple undersampling        |        91.84%     |       94.74%        | 
|         Neural Network with simple oversampling (recommended for small dataset)        |        99.72%      |       100.00%        | 

  
 
