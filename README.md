# Cross-Sectional Asset Pricing Analysis

The Cross-Sectional Asset Pricing dataset includes 210 features. The target variable is 'excessret', a firm's excess return between the current and the previous quarter. In this project, I worked on a subset that includes the 'defined features' and the 'target variable' by performing preprocessing (in the subset, there will be 11 features in total including the target variable). I extracted the 'defined features' are as indicated below:

defined_columns = ['high52', 'mom12m', 'mom6m', 'maxret', 'mom12moffseason', 'realizedvol', 'idiovolaht', 'zerotrade', 'indretbig', 'returnskew']

I designed and implemented the solution to analyse the complex relationship between defined features and the firm's excess return between the current and the previous quarter. Highlight and visualise the attributes with the highest probabilistic relationship with the target variable. 

I decided to use the Bayesian Network in this analysis, as it is a good choice to spot the probabilistic relationships between 'defined features' and a firm's excess returns (target variable). Bayesian Networks are particularly good for this task due to their ability to capture complex dependencies.

In the created network, 'high52' and 'maxret' show as the attributes with the highest correlation to the target variable, indicating these factors are potentially strong predictors of excess returns. This insight is valuable for financial analysis and investment strategy formulation.

The model's performance, with an accuracy of 0.72 and perfect precision (1.0), indicates it is reliable in its predictions. However, the opportunity to improve the F1 score suggests that future iterations could enhance the model's ability to identify all relevant cases.

For visualization, a graph from the Bayesian Network can show the strength of the connections, with the edges between 'high52', 'maxret', and 'excessret' being highlighted to reflect their importance. This visual tool effectively communicates the probabilistic relationships and the model's findings in a concise and interpretable manner.
