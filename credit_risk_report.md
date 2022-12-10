#  $Module$ *12* $Credit$ $Risk$ $Report$

## $Overview$ $of$ $the$ $Analysis$
---
The purpose of this analysis was to determine if the Machine learning algorithm could accurately predict if a loan was high risk or healthy.<br>
The financial data used to train the machine was supervised to enable better training in the prediction and accuracy.<br>
Using the financial data provided the model was going to attempt to identifiy `Healthy Loans '0'` and  `High Risk Loans '1'` so the institution would be better equiped to make risk assestments.<br>
The machine learning process I had to take the data model it, then fit that model into the algorithm and then make the predictions.<br>
This was done using methods such as `LogisticRegression` and `RandomOverSampler`.<br>

## $Results$
---
* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Accuracy Score: $99\%$
      * `Healthy Loans '0'`: $100\%$
      * `High Risk Loans '1'`: $88\%$
    * Precision Score: $99\%$
      * `Healthy Loans '0'`: $100\%$
      * `High Risk Loans '1'`: $85\%$
    * Recall Score: $99\%$
      * `Healthy Loans '0'`: $99\%$
      * `High Risk Loans '1'`: $91\%$

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    * Accuracy Score: $99\%$
      * `Healthy Loans '0'`: $100\%$
      * `High Risk Loans '1'`: $91\%$
    * Precision Score: $99\%$
      * `Healthy Loans '0'`: $100\%$
      * `High Risk Loans '1'`: $84\%$
    * Recall Score: $99\%$
      * `Healthy Loans '0'`: $99\%$
      * `High Risk Loans '1'`: $99\%$

## $Summary$
---
The Machine Learning Model 2 that used the `RandomOverSampler` function produced the most accurate results when identifying `High Risk Loans '1'`.<br>
Determining which loans are `High Risk Loans '1'` loans would be the more prudent<br>
value to ascertain as there is more financial risk associated with these loans.<br>

With more training data points with higher `High Risk Loans '1'` instances I would recommend model 2.<br> The reasoning behind this decision is it showed a higher accuracy with finding `High Risk Loans '1'` while maintaining nearly the same level of `Healthy Loans '0'` identification.
