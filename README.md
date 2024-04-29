# adv_prog_final


Image Classification using TensorFlow and Gradio
This repository contains code for building an image classification model using TensorFlow and creating an interactive interface using Gradio. The model is trained on the Flower Photos dataset to classify images of flowers into different categories.

Getting Started
Prerequisites
Ensure you have the required libraries installed by running:

bash
Copy code
pip install gradio tensorflow
Dataset
The Flower Photos dataset is used for training the image classification model. You can download the dataset from this link or use the provided script in the notebook to fetch it.

Model Architecture
The deep learning model employed for image classification is a sequential Convolutional Neural Network (CNN). The architecture includes convolutional layers with max-pooling, followed by fully connected layers. The model is trained using the Adam optimizer and sparse categorical crossentropy loss.

Training
The model is trained for a specified number of epochs on the Flower Photos dataset, with validation conducted on a separate subset. Training and validation accuracy, as well as loss, are tracked over epochs.

Usage
An interactive Gradio interface is provided for image prediction. Launch the interface by running the provided code in the notebook. Upload an image, and the model will predict its class.

Files and Folders
image_classification.ipynb: Jupyter notebook containing the code for model training, evaluation, and the Gradio interface.
README.md: Documentation providing an overview of the project.
Acknowledgments
TensorFlow Documentation: https://www.tensorflow.org/
Gradio Documentation: https://www.gradio.app/docs/
Flower Photos Dataset: https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz
Feel free to explore and extend the project based on your requirements. If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request. Happy coding!
