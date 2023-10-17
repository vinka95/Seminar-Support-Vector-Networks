# Seminar-Support-Vector-Networks

Traditionally pattern recognition is a field that stems out of engineering and has eventually
found its way into computer science especially through the appication of machine learning
algorithms. Typically pattern recognition problem can be solved as a classification problem. From a
single perceptron to today’s deep learning algorithm, there have been many state-of-the-art solutions
developed to tackle such classification problems. In this report, we describe the working of one such
learning machines called Support Vector Networks.
Support Vector Networks, or as otherwise called Support Vector Machines(SVM) solves a two-group
classification problem by constructing a hyperplane that optimally separates the two classes. SVM
maps all the input vectors into a high dimensional feature space. It then finds a hyperplane as a
decision surface in an N-dimensional feature space that distinctly classifies the data points into two
classes. Constructing an hyperplane separating the data that generalizes well over high-dimensional
feature spaces and to computationally be able to treat such feature spaces stand as two main challenges
for SVM. An Optimal Hyperplane is constructed which separates data linearly without any
errors. In the paper Support-Vector Networks [1] the idea of constructing optimal hyperplanes have
been extended to training data with error, with the concept of Hyperplanes with Soft Margin. In
this report we look at construction of convolution of dot-products in a higher dimensional space.
Experiments were performed on US Postal Services Database and NIST Database and the results
were then compared with classical machine learning algorithms.
