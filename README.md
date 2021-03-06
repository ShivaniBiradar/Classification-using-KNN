# Classification-using-KNN
Vertebral Column Dataset:

This Biomedical data set was built by Dr. Henrique da Mota during a medical residence period in Lyon, France. Each patient in the data set is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (in this order): pelvic incidence, pelvic tilt, lumbar lordosis angle, sacral slope, pelvic radius and grade of spondylolisthesis. The following convention is used for the class labels: DH (Disk Hernia), Spondylolisthesis (SL), Normal (NO) and Abnormal (AB)

Main Tasks:
- Pre-processing and exploratory data analysis using scatter plots and box plots
- Binary classification (NO = 0 and AB = 1) using sklearn's KNN classifier
- Plot train and test errors in terms of k to find the most suitable k*
- Evaluate performance by calculating the confusion matrix, true positive rate, true negative rate, precision and F-1 score when k=k*
- Plot learning curve to understand how the performance changes with change in size of training data
- Understand how the performance varies with different distance metrics:
  - Euclidean
  - Manhattan
  - Chebyshev
  - Minkowski
  - Mahalanobis
  
