# K__Fold_Cross_Validation
# Frist i save my digits data "digits = load_digits()" and use method "train_test_split" to get "train" and "test" set
# My "X" will be "digits.data" and "y" "digits.target"
# Then i get "LogisticRegression", train it "lr.fit(X_train, y_train)" and get score lr.score(X_test, y_test)""
# I do it also with "SVC" and "RandomForestClassifier"
# Next from "sklearn.model_selection" I import "KFold" and set parameter "n_splits" to (3) it means that it create "(3) folds"
# Now I create "for" loop on my "train_index" and "test_index" and set "kf.split([1,2,3,4,5,6,7,8,9])", It is my data set just to check how it works
# I can create function that will "return" "model.score" and supplement it into parameters and "train function" "model.fit(X_train, y_train)"
# So I can use my function to get score of "SVC" """get_score(SVC(), X_train, X_test, y_train, y_test)"""
# Now I am gonna import "StratifiedKFold" and set number of "folds" at (3)
