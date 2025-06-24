# Masters-Research-Work
Customer behaviour analysis and quotation success prediction using machine learning for sales optimization

![image](https://github.com/user-attachments/assets/e1529f07-2b29-4823-81b4-d0589191699a)

This research focuses on Customer Behavior Analysis and Quotation Success Prediction using machine learning to optimize sales strategies in the electrical industry. Data was collected from a private electrical company, encompassing a wide range of sales, customer, and item-related attributes. The dataset underwent meticulous preprocessing involving data cleaning and feature engineering, with features categorized into six primary groups: database attributes, customer behavior features, financial ratios, item characteristics, managerial and departmental information, and stock availability metrics.
To enhance model performance and reduce dimensionality, feature extraction techniques such as Chi-Square and Mutual Information were applied within a threshold-based selection framework. Following the identification of the most pertinent features, classification models were developed to forecast the success of sales quotations based on historical customer behavior and sales data patterns.
The findings demonstrate that machine learning can significantly improve the accuracy of quotation outcome predictions, enabling more informed decision-making and resource allocation in the sales process. This study offers a scalable method for incorporating customer analytics into sales operations, thereby improving sales performance and customer targeting strategies.
Using engineered customer, item, and financial information, four machine learning models Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine (SVM) were used in this study to forecast quotation success. Accuracy and Root Mean Squared Error (RMSE) were the primary measures used to assess each model's performance.
The table below provides a summary of the comparison results, emphasizing each algorithm's advantages. Based on the input features, the Random Forest Classifier demonstrated superior prediction performance by achieving the best accuracy and the lowest RMSE among the four models.

Machine Learning Model	RMSE Value	Accuracy
Logistic Regression	1.1671	0.6016
Decision Tree Classifier	0.7643	0.8741
Random Forest Classifier	0.7044	0.8938
Support Vector Machine	1.1634	0.6726

To gain a better understanding of the elements influencing quote failure, the dataset attributes were clustered in this study according to the lost reasons, especially Out of Stock, Other Brand, Technical Issue, Price, and Lead Time. We determined the relative weights of important characteristics affecting quotation success by examining these groupings. In addition to streamlining the quotation success prediction process, this method offered practical insights into how various aspects influence client choices in a range of loss circumstances.


