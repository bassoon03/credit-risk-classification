# Credit Risk Analysis

The purpose of this report is to assess whether or not the results achieved from applying the Logistic Regression model to the accompanying data justify using the model to assess whether a loan is healthy or high-risk.

The precision, recall, and accuracy scores of the model are as follows:

-- Accuracy: 0.99
-- Precision:
    -- Healthy Loan: 1.00
    -- High-Risk Loan: 0.85
-- Recall:
    -- Healthy Loan: 0.99
    -- High-Risk Loan: 0.91

Overall, the model appears to be reasonably accurate. Based on the near perfect recall score for healthy loans, if a loan is healthy, the model is almost certainly going to identify it as such. This would mean that very few opportunities to make money are missed. Furthermore, only a small proportion of high-risk loans are going to be seen as healthy. However, that is not necessarily something to be seen as acceptable. The recall score for high-risk loans suggests that around 15% of high risk loans are predicted to be healthy. If there are a lot high-risk loans being applied for, then the number of high-risk loans that could be predicted as healthy could become unacceptably high. It may not be enough to offset the profits that could potentially be earned from the healthy loans, but it's not a risk I recommend taking. Admittedly the number of high-risk loans in the data is substantially smaller than the number of healthy loans. This may explain why the precision and recall scores for high-risk loans are lower than those for healthy loans. The model may be sufficiently accurate for predicting whether loans are healthy or high-risk, but I would prefer to reserve judgement until it is trained with more data with a greater proportion of high-risk loans. For this reason, I would not recommend this model, at least not at the present time.
