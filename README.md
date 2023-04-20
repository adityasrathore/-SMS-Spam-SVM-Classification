# SMS Spam SVM Classification

<p>Support Vector Machine (SVM) classifier is trained to classify SMS messages as either spam or ham. The dataset is preprocessed and the text data is converted to numerical data using TfidfVectorizer. The hyperparameters of the SVM model are tuned using GridSearchCV with a 10-fold stratified cross-validation. The best hyperparameters and the best accuracy score are printed. The code was modified to include the 'epsilon' and 'kernel' parameters as requested.</p>

Info:
1) kernel specifies the kernel type to be used in the algorithm, and 'rbf' and 'sigmoid' are two possible options.
2) C is a regularization parameter that controls the trade-off between achieving a low training error and a low testing error.
3) gamma is a parameter that defines the shape of the decision boundary, and a higher gamma leads to a more complex decision boundary.
4) Nu is a parameter that controls the trade-off between achieving a low training error and a low testing error. It is used only for the nu-SVC algorithm.
5) Epsilon is a tolerance parameter that specifies the acceptable margin of error for the solution. It is used only for the epsilon-SVR algorithm.
