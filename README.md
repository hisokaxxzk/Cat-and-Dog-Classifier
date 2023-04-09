# Cat-and-Dog-Classifier
This is a project that uses a Convolutional Neural Network (CNN) to classify images of cats and dogs. The model was trained on 8000 images of cats and 8000 images of dogs.

# Requirements
* Python 3.x
* TensorFlow 2.x
* Keras 2.x
* NumPy
* OpenCV
* Matplotlib

# Dataset
The dataset used in this project consists of 16000 images of cats and dogs, with 8000 images of each class. The images were downloaded from Kaggle and split into training and validation sets with a ratio of 80:20.

# Training
The model was trained for 200 epochs using a batch size of 32 and binary crossentropy loss function. The Adam optimizer was used with a learning rate of 0.0001.

# Result
The trained model achieved an accuracy of 80% on the validation set, which indicates that it is effective at classifying images of cats and dogs. Here are some sample predictions made by the model:

![image](https://user-images.githubusercontent.com/67821758/230778704-402ecd04-bf6f-4e5d-8bfe-3837c1b68549.png)

![image](https://user-images.githubusercontent.com/67821758/230778793-fcad6a88-31cd-4b3c-ae73-42ac3ef98b5f.png)

![image](https://user-images.githubusercontent.com/67821758/230778830-76683116-552f-452c-bf9a-8439198a4e3a.png)

