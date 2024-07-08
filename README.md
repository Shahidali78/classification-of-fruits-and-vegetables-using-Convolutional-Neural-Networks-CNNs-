# classification-of-fruits-and-vegetables-using-Convolutional-Neural-Networks-CNNs-
Fruit and Vegetable Classification Using Convolutional Neural Networks
This project aims to develop an automated system for classifying images of fruits and vegetables into 36 different categories using Convolutional Neural Networks (CNNs). The dataset, sourced from Kaggle, includes a diverse collection of images for training, validation, and testing.

Features
Data Collection: Images of various fruits and vegetables collected and labeled from the Kaggle dataset.
Data Preprocessing: Images are resized to 180x180 pixels and normalized for efficient processing.
Model Architecture: The CNN model consists of:
Rescaling layer to normalize pixel values
Three convolutional layers with increasing filter sizes (16, 32, 64) and ReLU activation
Max pooling layers to reduce spatial dimensions
Flatten layer to convert 3D feature maps into 1D feature vectors
Dropout layer to prevent overfitting
Dense layers for final classification
Model Training: The model is trained for 25 epochs using the Adam optimizer and sparse categorical cross-entropy loss function.
Model Evaluation: Performance is measured using accuracy, precision, recall, F1 score, and confusion matrix.
Deployment: The trained model is saved and can be used for real-time classification of new images.
Results
Achieved a test accuracy of 95.54%, indicating high performance in classifying fruit and vegetable images.
Detailed metrics and visualizations demonstrate the model's robustness and effectiveness.
Future Work
Implement data augmentation techniques.
Explore hyperparameter tuning and more complex architectures.
Develop a real-time classification application.
Expand the dataset to include more classes and perform cross-dataset evaluations.
