# Handwritten-Digit-Recognition
The MNIST digits dataset contains images of handwritten digits from 0-9.\
As the dataset contains 784 features (pixels) for every image, PCA is applied to reduce the dimesionality from 784 to 90.\
An SVM classifier with gamma=0.01 and rbf kernel is trained on the transformed dataset.\
An accuracy of 94.92% is achieved.
