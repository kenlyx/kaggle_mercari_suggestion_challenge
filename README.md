# kaggle_mercari_suggestion_challenge

 1. Split category_name into sub-categories
 2. Parallelize LGBM to 4 cores
 3. Increase the number of rounds in 1st LGBM
 4. Another LGBM with different seed for model and training split, slightly different hyper-parametes.
 5. Weights on ensemble
 6. SGDRegressor doesn't improve the result, going with only 1 Ridge and 2 LGBM
