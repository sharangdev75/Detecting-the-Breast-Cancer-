# Detecting-the-Breast-Cancer-
To Predict the Breast Cancer using all the relevant features

AIM: To Predict Breast Cancer using all the relevant features.

Dataset Description:	
1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)
radius (mean of distances from the center to points on the perimeter)
texture (standard deviation of gray-scale values)
perimeter
area
smoothness (local variation in radius lengths)
compactness (perimeter^2 / area - 1.0)
concavity (severity of concave portions of the contour)
concave points (number of concave portions of the contour)
symmetry 
fractal dimension ("coastline approximation" - 1).

Model Designing: 
In this project, I built the Artificial Neural Network. Where the activation function used was Relu and in the last layer, I used sigmoid. Uniformly weights were distributed across all the hidden layers. Batch size and the number of epochs were 100 and 150 respectively. The optimizer used while building this model was Adamax. As the dependent variable was binary classified(Benign = 0, Malignant = 1), the loss function used was binary_crossentropy and the metric used was Accuracy.

Dataset obtained from: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
