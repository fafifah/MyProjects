
**Objective:** The goal of this study is to develop a technique for determining vehicle speed using image
processing for traﬀic surveillance and management purposes.

• Pre-processing the video by converting it into frames and extracting parameters.

• Performing perspective transformation to align the frames with global coordinates.

• Generating grayscale images to improve processing speed and eliminate noise.

• Applying image blurring using a Gaussian filter to remove noise and edges.

• Utilizing image segmentation techniques, such as background subtraction, to extract moving
foreground objects.

• Performing thresholding to convert grayscale images into binary images.

• Applying morphological operations, such as opening, closing, and dilation, to refine segmentation
results.

• Extracting features and tracking vehicles by detecting contours and center points.

• Determining the speed of vehicles by calculating the distance traveled between frames and map-
ping it to real-world distances.

**Pipeline**

<img width="807" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/94cd0063-2e23-4813-8cc7-e321dd76251f">

**Perespective Transformation**

<img width="778" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/e8ed2c8e-e431-4ae3-b68f-6c3a14abcc17">

**Grayscale Image Generation**

<img width="501" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/eba2590f-8334-4122-a483-e7134fd815e3">

**Thresholding**

<img width="423" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/e68cde3d-6f29-4201-8ee4-5d6660a2120c">

**Morphological Operations**

<img width="378" alt="image" src="https://github.com/fafifah/MyProjects/assets/136669312/f394ff8d-58a5-4397-b750-bed2eaaaf431">




