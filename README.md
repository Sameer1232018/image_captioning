# Image Captioning with CNN

## Overview
This project demonstrates an image captioning system that utilizes Convolutional Neural Networks (CNNs) for image processing and Natural Language Processing (NLP) techniques for text generation. The system generates descriptive captions for images, providing a richer context to visual content.

## Project Highlights
- Successfully developed an image captioning system using CNNs and NLP.
- Utilized Python as the primary programming language and popular libraries/frameworks such as TensorFlow or PyTorch for CNN model development, tokenization, and data generation.
- Employed tokenization to preprocess image descriptions into tokenized representations.
- Utilized a DataGenerator technique to efficiently handle large image datasets and dynamically generate training data, optimizing memory usage during the training process.

## Dataset
The project used the ([https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset](https://www.kaggle.com/datasets/aladdinpersson/flickr8kimagescaptions)) dataset from Kaggle. 
## Project Structure
- README.md               # Project documentation
- emotion-classification-cnn-using-keras.ipynb   # Jupyter Notebook with code and explanations
- haarcascade_frontalface_default.xml   # Haar Cascade XML file for face detection
- main.py                 # Main Python script for running the emotion classification
- model.h5                # Pre-trained CNN model for emotion classification
- tempCodeRunnerFile.py   # Temporary code runner file (can be removed)


## Getting Started
1. Clone the repository to your local machine:
2. Set up the required Python environment and dependencies:

3. Download the pre-trained model (`model.h5`) from [here](provide-download-link) and save it to a local directory of your choice.

4. Open the `main.py` file and update the `load_model` line with the local path to your downloaded `model.h5` file:
   classifier = load_model(r'path_to_your_model.h5')
5. Run the main.py script:
