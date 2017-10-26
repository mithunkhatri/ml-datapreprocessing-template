Welcome to the ml-datapreprocessing-template !

Added templates for :
1. Data preprocessing
2. Classification problems

Sample Classifications and regressions:

# DecisionTreeRegressor
`from sklearn.tree import DecisionTreeRegressor`

`regressor = DecisionTreeRegressor(random_state = 0)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/DecisionTreeRegressor.png "DecisionTreeRegressor")

# DecisionTreeClassifier
`from sklearn.tree import DecisionTreeClassifier`

`classifier = DecisionTreeClassifier(criterion = 'entropy', random_state = 0)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/DecisionTreeClassifier.png "DecisionTreeClassifier")

# KNeighborsClassifier
`from sklearn.neighbors import KNeighborsClassifier`

`classifier = KNeighborsClassifier(n_neighbors = 10)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/KNN.png "KNeighborsClassifier")

# GaussianNB
`from sklearn.naive_bayes import GaussianNB`

`classifier = GaussianNB()`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/GaussianNB.png "GaussianNB")

# SVC
`from sklearn.svm import SVC`

`clf_rbf = SVC(kernel = 'rbf', random_state=0)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/SVC_rbf.png "SVC_rbf")

`clf_lin = SVC(kernel = 'linear', random_state=0)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/SVC_linear.png "SVC_linear")

`clf_pol = SVC(kernel = 'poly', random_state=0, degree=2)`

![alt tag](https://github.com/mithunkhatri/ml-datapreprocessing-template/blob/master/SVC_poly.png "SVC_poly")
