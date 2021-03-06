# Breast-Cancer-Classification-model-2.0
Same model as in https://github.com/PavanNettam/Breast-Cancer-Classification-Model is applied on a different dataset<br>
<h2>Data Set Information:</h2>

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. A few of the images can be found at [Web Link] 

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes. 

The actual linear program used to obtain the separating plane in the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34]. 

This database is also available through the UW CS ftp server: 
ftp ftp.cs.wisc.edu 
cd math-prog/cpo-dataset/machine-learn/WDBC/
<br>
<h2>Attribute Information:</h2>

1) ID number 
2) Diagnosis (M = malignant, B = benign) 
3-32) 

Ten real-valued features are computed for each cell nucleus: 

a) radius (mean of distances from center to points on the perimeter) 
b) texture (standard deviation of gray-scale values) 
c) perimeter 
d) area 
e) smoothness (local variation in radius lengths) 
f) compactness (perimeter^2 / area - 1.0) 
g) concavity (severity of concave portions of the contour) 
h) concave points (number of concave portions of the contour) 
i) symmetry 
j) fractal dimension ("coastline approximation" - 1)
<br>
<h2>Classfication results:</h2>

The dataset is divided into two parts, Trainings set(80% of the dataset) Testing set(20% of the dataset)

Logistic regression model is applied on the training dataset and when tested on the testing dataset the following results were obtained:

<h2>Confusion matrix:</h2>
<img width="585" alt="confusion_matrix" src="https://user-images.githubusercontent.com/79460453/152561898-f44bf5aa-9c39-417d-8317-6d9b8b43f820.png">

Accuracy Score = 0.956140350877193<br>
K-Fold cross validation shows the following accuracy for the model:

Accuracy = 98.18% Standard Deviation = 3.64%

Dataset is taken from the following webpage:
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

