# TFLite On Device Machine Learning

This is a project to train a model using TFLite Model Maker to recognize different species of flowers.

## Description

This project utilizes the TFLite Model Maker library to train a machine learning model for flower species recognition. The training is done in the Google Colab environment, which may provide a powerful and convenient platform for running machine learning experiments. **In this case, learning was stunted because the colab environment does not support tensorflow model maker and required a conda environment to be made.** This, however, causes an unsuppoerted version of tensorflow to be used which makes it difficult to utilize the GPU for training.

## Features

- Train a flower species recognition model using TFLite Model Maker
- Utilize transfer learning to leverage pre-trained models
- Evaluate the model's performance and accuracy
- Export the trained model in TFLite format for deployment on various platforms


## Usage

To use the trained model for flower species recognition, follow these steps:

1. Load the TFLite model into your application
2. Preprocess the input image according to the model's requirements
3. Run inference on the preprocessed image using the TFLite model
4. Obtain the predicted flower species label from the model's output

**Recommended: Use a different training environment with tensorflow model maker instead of google colab**

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgements

- [TFLite Model Maker](https://www.tensorflow.org/lite/guide/model_maker)
- [Google Colab](https://colab.research.google.com/)

## Flower Dataset

Training used this dataset from the official tensorflow examples API.


image_path = tf.keras.utils.get_file(
      'flower_photos',
      'https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz',
      untar=True)

