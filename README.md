# RecSysRoseltorg
Recommendation system for purchases and customers 
## Task
Build recommendation system for purchases and customers, which the will help to choose the customers for certain purchase.
## Solution
- Prepare data
- Create features
- Create embeddings with FastText
- Fitted Catboost (binary classification | ROC-AUC = 0.901, PR-AUC = 0.95)
- Find similar purchases with cosine similarity and define positive sales with catboost
- Calculate metric
## Metric
Metric #1 - For which part of the procedures, depending on n, at least one participant was guessed

Metric #2 - Total share of guessed unique engagements

