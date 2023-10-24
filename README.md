# Fraud_Transection_detection_end-to-end
The fraud transaction detection based system is a machine learning-based object detection model which will help us to detect the anomalies in the society and take the necessary action.

<b>Solution Architecture</b>
<ul>
  <li>In this we developed a novel method for fraud detection, where customers are grouped
based on their transactions and extract behavioral patterns to develop a profile for every
cardholder. Then different classifiers are applied on three different groups; later rating
scores are generated for every type of classifier.</li>
  <li>We observed that the Matthews Correlation Coefficient was the better parameter to deal
with the imbalance dataset. MCC was not the only solution.</li>
  <li>By applying the SMOTE, we tried balancing the dataset, where we found that the
classifiers were performing better than before.</li>
  <li>The other way of handling an imbalanced dataset is to use one-class classifiers like
one-class SVM. We finally observed that Logistic regression, decision tree and random
forest are the algorithms that gave better results.</li>
</ul>
