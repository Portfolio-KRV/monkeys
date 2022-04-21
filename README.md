# Monkeys
Developed in the Neural Networks course by: Diego Quezada and Kevin Reyes.
## Objectives
- Apply convolutional neural networks to the classification of monkey breeds using Transfer Learning.
- Visualize the internal state of the convolutional network in an interpretable way using CAM.
- Compare VGG16 and VGG19 network performance.
- Compare CNN network performance, CNN with skip connections trained exclusively to classify monkeys with networks with Transfer Learning.

## Description
Convolutional neural networks for the classification of monkey breeds, using skip connections, transfer learning and CAM method for the visualization of the internal state of the network.

## Conclusions
- Neural networks with Transfer Learning have superior performance to networks trained exclusively for monkey classification, since they store a large set of patterns in their parameters, which can be useful for object recognition in other classification problems.
- The CAM method is a very useful tool to visualize the internal state of the convolutional network and detect errors that the network makes when predicting in an interpretable way.
- The face of the monkeys is usually a point of great attention for the network when predicting the race of the monkey.

## Technology stack
- Numpy.
- Pandas.
- Matplotlib.
- Seaborn.
- Cv2.
- Keras.
- Tensorflow.
- VGG16.
- VGG19.