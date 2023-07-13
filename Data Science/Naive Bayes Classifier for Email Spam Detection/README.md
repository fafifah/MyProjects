The task involved training a naive Bayes classifier for email spam detection using the ECML/PAKDD Discovery Challenge 2006 dataset. The achievements in this task were as follows:

**Data Processing**
Data Format: The dataset is provided in a sparse data format used by SVMlight. Each line represents an email, with the first token indicating the class label (+1 = spam, -1 = non-spam, 0 = unlabeled). The subsequent tokens represent word IDs and their corresponding term frequencies.

Separating Labels and Features: Initially, the labels and word frequencies are jumbled together, making it necessary to untangle them. The "load_svmlight_file" function from scikit-learn datasets is used to transform the dataset into separate X (features) and y (labels) formats.

Transforming Sparse Matrix: The X matrix is initially in a sparse CSR matrix format, which needs to be transformed into a regular numpy or other matrix format suitable for model building. This transformation allows for easier manipulation and analysis of the data.

Preparing Test Dataset: The performance testing dataset also needs to be processed similarly to the training dataset. One challenge encountered here is that the number of columns may differ from the training dataset. To address this, a zero element matrix is created and concatenated with the original performance testing dataset to ensure consistency.



**Model Test Result**

<img width="430" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/c7e32019-9bfd-4009-902f-ae83cfb68bfa">

