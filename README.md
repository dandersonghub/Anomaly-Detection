# [Anomaly-Detection](https://github.com/dandersonghub/Anomaly-Detection/blob/main/Anomaly-Detection.ipynb)
This analysis used an Isolation Forest machine learning algorithm to identify overpayments in a synthetic claims data set. The dataset was generated with 1000 normal claims and 20 overpayments added to it. The Isolation Forest model was trained with a contamination rate of 0.05, meaning that it was designed to identify claims that were different from normal claims by 5%. The predictions from the model were used to filter the dataframe and only overpayments were returned. The results of this analysis demonstrate the effectiveness of the Isolation Forest algorithm in accurately identifying potential overpayments in a claims dataset. The model identified 51 claims that could be considered overpayments and require further investigation to validate its results.

### 
![](https://github.com/dandersonghub/Anomaly-Detection/blob/main/overpayments.png)
