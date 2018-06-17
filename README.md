# HR-analytics
This data project is to analyze why employee leave company and predict if they will leave. 14,999 observations and 10 variables. It is binary classification problem, implemented in R. 
* Variables: 
response: Employess left or not, 0 and 1 (left)
predictors (numerical variables): 
Satisfaction level
Last evaluation
Number project
Average monthly hour
Time spend in company
predictors (categorical variables): 
Work accident- 0 and 1(yes)
Promotion in last 5 years- 0 and 1 (yes)
Department- IT, Counting, HR, Management, Product management, Support, Sales, Marketing, RandD, Technical
Salary- low, medium, high
* Data exploratory analysis
Using histogram and barplot to explore each variable, response with each variable, correlation between two variables. 
* Data treatment
Some variables is changed to the right format, and split data randomely into train and test set by 7:3. 
* Build classification model
Logistic regression, Tree, Random forest, boosting tree, SVM, neural netwok
* Results
1. Satisfaction level is the most important indicator for whether employees leave
2. Number of projects and average monthly hour are secondly important variables
3. Test set prediction error, Random forest<SVM<Boosting tree<Tree<Neural network
