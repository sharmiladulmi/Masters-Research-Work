# Masters-Research-Work
# Customer behaviour analysis and quotation success prediction using machine learning for sales optimization

![image](https://github.com/user-attachments/assets/e1529f07-2b29-4823-81b4-d0589191699a)

This research focuses on Customer Behavior Analysis and Quotation Success Prediction using machine learning to optimize sales strategies in the electrical industry. Data was collected from a private electrical company, encompassing a wide range of sales, customer, and item-related attributes. The dataset underwent meticulous preprocessing involving data cleaning and feature engineering, with features categorized into six primary groups: database attributes, customer behavior features, financial ratios, item characteristics, managerial and departmental information, and stock availability metrics.

To enhance model performance and reduce dimensionality, feature extraction techniques such as Chi-Square and Mutual Information were applied within a threshold-based selection framework. Following the identification of the most pertinent features, classification models were developed to forecast the success of sales quotations based on historical customer behavior and sales data patterns.

The findings demonstrate that machine learning can significantly improve the accuracy of quotation outcome predictions, enabling more informed decision-making and resource allocation in the sales process. This study offers a scalable method for incorporating customer analytics into sales operations, thereby improving sales performance and customer targeting strategies.
Using engineered customer, item, and financial information, four machine learning models Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM) were used in this study to forecast quotation success. Accuracy and Root Mean Squared Error (RMSE) were the primary measures used to assess each model's performance.

The table below provides a summary of the comparison results, emphasizing each algorithm's advantages. Based on the input features, the Random Forest Classifier demonstrated superior prediction performance by achieving the best accuracy and the lowest RMSE among the four models.

![image](https://github.com/user-attachments/assets/c1124a07-e6ff-4547-944f-2607c6a32788)


To gain a better understanding of the elements influencing quote failure, the dataset attributes were clustered in this study according to the lost reasons, especially Out of Stock, Other Brand, Technical Issue, Price, and Lead Time. We determined the relative weights of important characteristics affecting quotation success by examining these groupings. In addition to streamlining the quotation success prediction process, this method offered practical insights into how various aspects influence client choices in a range of loss circumstances.

## Quotation Lost Reason Optimisation

![image](https://github.com/user-attachments/assets/4954a904-98a5-4319-90d1-315de8bb5020)

## Optimize Lost Reason is Out of Stock Items
![image](https://github.com/user-attachments/assets/eb85a123-879b-4efa-9af8-8ae5266b1aeb)

## Objectives of The Study

The Primary objectives of this research are as follows
•	To analyze customer behavior patterns employing past sales and quote information from an electrical company, with an emphasis on determining important behavioral markers that affect the results of quotations.
•	To perform data preprocessing and feature engineering by categorizing data into meaningful groups such as customer behavior features, financial ratios, item features, manager and department-based features, and stock availability features.
•	To apply feature selection techniques such as Chi-Square and Mutual Information to extract the most significant variables affecting quotation success.
•	To develop predictive models using machine learning algorithms to forecast the likelihood of quotation acceptance or rejection.
•	To evaluate the performance of the models and assess how well they work to enhance decision-making and sales forecasting.
•	To provide actionable insights that can improve quotation success rates and optimize sales strategies for management and sales teams at organizations. 

## Limitations of The Study

Although the study offers insightful information, there are certain restrictions:
•	Data Specificity: Because the study is based on data from a single business, the findings may not be as applicable to other sectors or geographical areas.
•	Feature Availability: The completeness and quality of the features that are accessible determine how accurate the forecasts are. The performance of the model may be impacted by missing or inconsistent data.
•	Model Interpretability: Non-technical users may find it difficult to make decisions when using machine learning algorithms that have high accuracy but poor interpretability.
•	Time Restrictions: Due to the study's time constraints, a comprehensive comparison analysis and model optimization with a variety of algorithms may not be possible.
•	External Factors: The model might not take into consideration outside factors that could have an impact on consumer choices, such as market trends, competitive activity, or shifts in the economy.




