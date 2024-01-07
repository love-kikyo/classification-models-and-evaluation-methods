# Introduction to Data Science Case Studies in Practice
In regression models, the assumption is that the response variable is quantitative. However, in many cases, the response variable is qualitative. For example, eye color is a qualitative variable with categories such as blue, brown, or green. These qualitative variables, also known as categorical variables, have a different statistical interpretation.

Predicting the qualitative response value involves classifying observations into categories. In other words, it requires assigning each observation to a specific category. Some classification methods start by predicting the probabilities of different categories for qualitative variables. The classification problem is then tackled by estimating these probabilities. Thus, there are similarities between classification and regression methods when considering this perspective.

Several classification methods have been learned in the course Introduction to Data Science, such as logistic regression, nearest neighbors, decision trees, support vector machines, random forests, and AdaBoost Among existing classifiers, support vector machine (SVM) is a popular method originating from the machine learning community. 

It is a typical example of using a single classification function to perform maximum interval classification on binary classification problems, and has good performance in practical applications In many problems, data typically contains two or more categories Although SVM has achieved success in binary classification, how to apply it to multi class classification problems remains a challenge The methods of using SVM for multi class classification in literature can be divided into two categories: the first category trains a series of binary support vector machines, and then combines the results for multi class classification Examples include one versus one and one versus many methods.

Although this method is simple in concept and implementation, it also has its own drawbacks The second type of method is to consider all classes simultaneously in an optimization problem The commonly used method is to use a classification function to represent the corresponding classes in the optimization, and give the final prediction result based on which classification function is the largest Currently, many synchronous multi class support vector machine classifiers have been proposed under the second type framework This project focuses on the comparison between support vector machines and other methods, as well as how to use SVM to handle multi classification problems.
