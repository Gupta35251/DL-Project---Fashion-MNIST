# DL-Project---Fashion-MNIST

This project is a classic deep learning task for image classification. The goal is to train a neural network that can accurately identify the type of fashion item (e.g., T-shirt, trouser, dress) from a grayscale image.

Core Libraries Used

    scikit-learn (fetch_openml): To load the Fashion MNIST dataset.

    NumPy & Pandas: For data manipulation and handling.

    Matplotlib: For visualizing the images and plotting the model's training history.

    TensorFlow & Keras: The primary deep learning framework used to build, compile, and train the neural network.

    MLxtend: For plotting a confusion matrix to evaluate the model's performance.

Key Project Steps

    Data Loading and Preprocessing: The project begins by fetching the Fashion MNIST dataset, which consists of 70,000 grayscale images of 10 different types of clothing. The pixel values of the images are normalized (scaled to a range of 0 to 1) to help the model train more effectively.

    Model Architecture: A Deep Neural Network (DNN) is constructed using a sequential model in Keras. The network consists of an input layer, multiple hidden dense layers with relu activation, and a final output layer with softmax activation to classify the images into one of the 10 categories.

    Model Training: The dataset is split into training and testing sets. The model is then compiled with an optimizer and loss function and trained on the training data. The training history, including accuracy and loss, is recorded.

    Model Evaluation: The model's performance is evaluated by plotting its training and validation accuracy and loss over the epochs. A confusion matrix is also generated to provide a detailed breakdown of how well the model performed on each class in the test set.

    Predictive System: The trained model is used to make predictions on new, unseen images from the test set, demonstrating its ability to classify fashion items it has never seen before.
