# Headgear Classification Project

This project demonstrates the steps involved in performing classification on a headgear dataset using the EfficientNetB0 model. It includes data loading, data preprocessing, model definition, training, evaluation, and testing.

## Dataset

The dataset used in this project consists of images of headgear belonging to 20 different classes. The dataset is divided into three sets: training, validation, and testing. The training set contains 3620 images, the validation set contains 100 images, and the testing set contains 100 images.

## Prerequisites

To run this project, you need the following libraries and frameworks:

- Numpy
- Pandas
- TensorFlow
- Keras
- Matplotlib

## Getting Started

1. Clone this repository to your local machine.
2. Set up the required libraries and frameworks as mentioned in the Prerequisites section.
3. Download the headgear dataset and place it in the appropriate directories: `train/`, `valid/`, and `test/`.
4. Open the notebook file `headgear_classification.ipynb` using Jupyter Notebook or any other compatible environment.
5. Run each cell in the notebook sequentially to perform data loading, preprocessing, model definition, training, evaluation, and testing.

## Results

The model achieved an accuracy of 94% on the validation set and a test accuracy of 94% on the testing set. The loss and accuracy curves are plotted for visualization.

## Authors

- Olamileye Clement Duduyemi

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Feel free to modify and use the code for your own purposes.

## Acknowledgments

- The headgear dataset used in this project is sourced from [source of the dataset].
- The EfficientNetB0 model is based on the work by [EfficientNetB0 paper citation].
