# MNIST_DigitsClassification_KNN

Given a labeled dataset D = {(x1,y1),(x2,y2)...(xn,yn)} , a KNN algorithm predicts the class y(test) of an unseen test data x(test)

Finding the k closest examples to x(test) from the dataset, i.e. kNN(x(test)) = {(x1',y1'),(x2',y2'),...(xn',yn')} such that x1',x2',..xn' are the best k points among all x(i) in the training dataset at minimizing d(x(i)',x(test)), where d(x(i), x(j)) is a distance measure between x(i) and x(j)

The predicted class label y(test) is the result of a majority vote


Jupyter Notebook : MNIST_CLassification_KNN.ipynb

The dataset is named as : MNIST_Classification_dataset.npy
