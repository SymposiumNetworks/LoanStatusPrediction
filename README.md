# LoanStatusPrediction
Predicting the defaulters from bank's existing customers
Classification problem, challenges with respect to NAN's and variables have missing values
Variable transformation is needed especially with some date based varaibles, sample used here is a small snippet of the actual data as size exceeds 25MB
Dropped a lot of variables becasue of their unutility, categorical variables like sub grade, address state, reason for loan have been dropped because of long list of classes
Tried out only logistic regression with balanced option in scikitlearn lr implementation
Tried out hyper parameter optimization using randomized search
