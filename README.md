# CNN_A-five-layer-CNN-Model
This code is a TensorFlow/Keras script for training a Convolutional Neural Network (CNN) of five layers to classify images for pneumonia detection. Here's a short description:

Imports: Necessary libraries such as TensorFlow, NumPy, Pandas, and Google Colab's drive module are imported.

Mounting Google Drive: Google Drive is mounted to access the dataset stored there.

Constants Definition: Constants like image dimensions (IMG_HEIGHT and IMG_WIDTH) and batch size (BATCH_SIZE) are defined.

Data Directories and Generators: Paths for training and validation data directories are set. ImageDataGenerators are defined for augmenting the training data and validating the validation data.

Model Architecture: A CNN model is created using Sequential API. It consists of several convolutional layers followed by max-pooling layers for feature extraction.

Flattening and Dense Layers: The output from the last convolutional layer is flattened and passed through dense layers with dropout to perform classification.

Model Compilation: The model is compiled with Adam optimizer and binary cross-entropy loss.

Model Training: The model is trained using the fit method on the training data generator with a specified number of epochs. Validation data generator is also passed for validation during training.
