
Objective: To analyze the performance of Support Vector Regression (SVR) models with different kernel functions in predicting bikesharing demand, providing insights for optimizing bikesharing systems.

Exploring the Dataset: Thoroughly examined the bikesharing dataset, gaining a comprehensive understanding of its attributes and structure.

Preprocessing the Data: Carefully selected the relevant input variables and the target variable (demand) for the SVR model. Applied data preprocessing techniques such as scaling using StandardScaler to ensure compatibility.

Splitting the Dataset: Divided the dataset into training and test datasets, considering the temporal aspect of the data. Allocated an appropriate proportion for each subset.

SVR Modeling with RBF Kernel: Trained an SVR model using the 'rbf' kernel on the training dataset. Fine-tuned the model's parameters (C and gamma) using advanced techniques like grid search or cross-validation. Evaluated the model's performance using various metrics such as accuracy, RMSE, MAE, MAPE, and r2.

SVR Modeling with Linear Kernel: Repeated the training process, this time employing a linear kernel. Analyzed and compared the performance of the linear kernel model with the previously trained RBF kernel model.

SVR Modeling with Polynomial Kernel: Developed an SVR model using a polynomial (poly) kernel. Determined the optimal values for the degree and coefficients of the model. Evaluated its performance and conduct a comparative analysis with the other kernel functions.

Performance Analysis: Created insightful visualizations to plot the accuracy levels of the SVR models over both the training and test datasets. Conducted a comprehensive analysis of the accuracy differences among the various kernel functions and identified the best-performing model.


<img width="758" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/764d5529-1ddd-4327-95eb-90e22fe858fd">

**Training Accuracy**

 <img width="690" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/aa0be77d-1041-41a7-8dbf-765045cb7d8f">
 <img width="680" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/26bbd2f6-ada0-450c-baf0-ec7760d6e856">

**Testing Accurancy**

<img width="707" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/aed42b59-6f8d-4b3b-8970-b4b8d253cf4b">
<img width="719" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/da5153a2-8f89-4f8f-869e-af31c7ec75b3">

