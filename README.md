# Customer Churn Prediction Using a Decision Tree Classifier
This project builds a Decision Tree classifier to predict whether telecom customers are likely to churn.
Understanding churn drivers helps telecom companies reduce customer loss and increase lifetime value.

#### Source: IBM Telco Customer Churn Dataset <br>
Dataset link: https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv
<br>
<br>
Target Variable: Churn/Stay 
Which I classified in 0s and 1s using simple mapping. 
<br>

#### Methodology: 
<ul>
 <li>I split the data into 80-20 for training and testing. </li>
 <li>Then applied a Decision tree classifier model with max_depth = 4.</li> 
 <li>Made use of Entropy values $(- \sum p_i \log_2(p_i))$ to judge the 'purity' of the dataset.</li>
 <li>Branched first on the Contract type (Features).</li>
 <li>Then Monthly Charges.</li>
 <li>Found key churn drivers, such as:</li>
<ul>
<li>Short tenure</li>

<li>Month-to-month contracts</li>

<li>Higher monthly charges</li>
</ul>
 
</ul>

#### Evaluation 
Performance assessed using: <br>
<ul>
<li>Accuracy Score</li>

<li>Confusion Matrix</li>

<li>Classification Report</li>
</ul>

