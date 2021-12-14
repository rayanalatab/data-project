This paper aimed to predict contraceptive use in women based on various demographic and socioeconomic characteristics. Additionally, the efficacy of logistic regression, decision trees, and random forest models on predicting contraceptive use was evaluated. The problem was initially framed as a three class problem. The initial three classes of contraceptive use were No Use, Short Term Use, and Long Term Use. The problem was later reduced to a two class case by combining No Use and Short Term Use into a single class. Various techniques such as feature engineering, hyperparameter tuning were performed in an attempt to optimize the models. The most successful model was a fine tuned random forest model on the two class case. The model used 110 learners with a max depth of 6. The final model had a resulting training and test accuracy of 77.50 % and 73.76 % respectively.

Data  

  Wife's age (numerical)

  Wife's education (categorical) 1=low, 2, 3, 4=high

  Husband's education (categorical) 1=low, 2, 3, 4=high

  Number of children ever born (numerical)

  Wife's religion (binary) 0=Non-Islam, 1=Islam

  Wife's now working? (binary) 0=Yes, 1=No

  Husband's occupation (categorical) 1=low, 2, 3, 4=high

  Standard-of-living index (categorical) 1=low, 2, 3, 4=high

  Media exposure (binary) 0=Good, 1=Not good

  Contraceptive method used (class attribute) 1=No-use, 2=Long-term, 3=Short-term
