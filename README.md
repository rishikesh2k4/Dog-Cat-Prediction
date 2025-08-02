# Cat vs Dog Image Classifier

A machine learning project that classifies images of cats and dogs using HOG (Histogram of Oriented Gradients) features and an SGD Classifier.

**📌 Project Summary**

This model:
	•	Loads grayscale cat and dog images.
	•	Extracts HOG features from each image.
	•	Trains a Stochastic Gradient Descent (SGD) classifier.
	•	Evaluates the model’s performance.
	•	Allows testing on new images to predict whether the input is a cat or a dog.

 **📁 Dataset**

 Dataset/
├── cats/
│   ├── cat1.jpg
│   ├── cat2.jpg
│   └── ...
└── dogs/
    ├── dog1.jpg
    ├── dog2.jpg
    └── ...


**🧠 Model Architecture**
	
  Feature Extraction:
      •	Images resized to 128x128
      •	Converted to grayscale
      •	HOG (Histogram of Oriented Gradients) features extracted for edge-based detection
      •	Model Used:
      •	SGDClassifier with hinge loss (linear SVM)


**📊 Performance**

	•	Dataset is split into 80% training and 20% testing
	•	Features are standardized using StandardScaler
	•	Evaluation includes:
	•	Accuracy Score
	•	Classification Report



**👨🏻‍💻Results**

