# House-price-prediction


Result:
Numerically, the Linear Regression model provides the highest test R2 score (approximately 0.950) and is explicitly noted as avoiding both overfitting and underfitting, which makes it the most generalizable model according to the R2 metric. This suggests it is the most reliable model for predicting prices of unseen houses, given the dataset and its performance characteristics.
However, it is crucial to consider the qualitative observation that "linear regression cannot be considered as an effective method" because only 'Area' and 'Price' show a strong linear relationship. This implies that while it performs well on the R2 metric, it might be oversimplifying complex, non-linear interactions between other features and the price. If the goal is to fully capture all nuanced relationships within the data, a more complex model like XGBoost, despite its slightly lower test R2, might be considered if further fine-tuning could reduce its train-test R2 gap and leverage its ability to model non-linear patterns.
In summary, for direct predictive performance on new data based on the provided metrics and generalization assessment, the Linear Regression model is the best. However, its suitability for fully representing all underlying data relationships is questioned by the source itself.
