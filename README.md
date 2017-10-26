Welcome to the ml-datapreprocessing-template wiki!

Added templates for :
1. Data preprocessing
2. Classification problems

Sample Classifications and regressions:

# DecisionTreeRegressor
`from sklearn.tree import DecisionTreeRegressor`
`regressor = DecisionTreeRegressor(random_state = 0)`

# DecisionTreeClassifier
`from sklearn.tree import DecisionTreeClassifier`
`classifier = DecisionTreeClassifier(criterion = 'entropy', random_state = 0)`

# KNeighborsClassifier
`from sklearn.neighbors import KNeighborsClassifier`
`classifier = KNeighborsClassifier(n_neighbors = 10)`

# GaussianNB
`from sklearn.naive_bayes import GaussianNB`
`classifier = GaussianNB()`

# SVC
`from sklearn.svm import SVC`
`clf_rbf = SVC(kernel = 'rbf', random_state=0)`
`clf_lin = SVC(kernel = 'linear', random_state=0)`
`clf_pol = SVC(kernel = 'poly', random_state=0, degree=2)`
