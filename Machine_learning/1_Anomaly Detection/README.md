What Does Anomaly Detection Mean?
Anomaly detection is the identification of data points, items, observations or events that do not conform to the expected pattern of a given group. These anomalies occur very infrequently but may signify a large and significant threat such as cyber intrusions or fraud.

Anomaly detection is heavily used in behavioral analysis and other forms of analysis in order to aid in learning about the detection, identification and prediction of the occurrence of these anomalies.

Anomaly detection is also known as outlier detection.



Example of Comparing All Implemented Outlier Detection Models
PyOD is a comprehensive Python toolkit to identify outlying objects in multivariate data with both unsupervised and supervised approaches. The model covered in this example includes:

Linear Models for Outlier Detection:

PCA: Principal Component Analysis use the sum of weighted projected distances to the eigenvector hyperplane as the outlier outlier scores)
MCD: Minimum Covariance Determinant (use the mahalanobis distances as the outlier scores)
OCSVM: One-Class Support Vector Machines
Proximity-Based Outlier Detection Models:

LOF: Local Outlier Factor
CBLOF: Clustering-Based Local Outlier Factor
kNN: k Nearest Neighbors (use the distance to the kth nearest neighbor as the outlier score)
Median kNN Outlier Detection (use the median distance to k nearest neighbors as the outlier score)
HBOS: Histogram-based Outlier Score
Probabilistic Models for Outlier Detection:

ABOD: Angle-Based Outlier Detection
Outlier Ensembles and Combination Frameworks

Isolation Forest
Feature Bagging
LSCP


Example of combining multiple base outlier scores.
PyOD is a comprehensive Python toolkit to identify outlying objects in multivariate data with both unsupervised and supervised approaches.

Four combination frameworks are demonstrated in this example:

Average: take the average of all base detectors
maximization : take the maximum score across all detectors as the score
Average of Maximum (AOM)
Maximum of Average (MOA)
