#  $Module$ *12* $Credit$ $Risk$ $Report$

## $Overview$ $of$ $the$ $Analysis$
---
The purpose of this analysis was to determine if the Machine learning algorithm could accurately predict if a loan would fall into the category of `High Risk Loans '1'` or `Healthy Loans '0'`.<br>
The financial data used to train the machine was supervised to enable better training in the prediction and accuracy.<br>
Using the financial data provided the model will attempt to identifiy `Healthy Loans '0'` and  `High Risk Loans '1'` so the institution would be better equipped to make risk assestments.<br>
The machine learning process that was used took the data to model it, then fit that model into the algorithm and to then make the predictions.<br>
This was done using the model `train_test_split` from `sklearn` library and used methods such as `train_test_split`, `LogisticRegression` and used the method `RandomOverSampler` from the `imblearn` library .<br>

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
Both models did have indicators that suggest the models were overfitted.<br>

With more training data points with higher `High Risk Loans '1'` instances and model adjusting to make it more correctly fitted I would recommend model 2.<br> The reasoning behind this decision is it showed a higher accuracy with finding `High Risk Loans '1'` while maintaining nearly the same level of `Healthy Loans '0'` identification.
