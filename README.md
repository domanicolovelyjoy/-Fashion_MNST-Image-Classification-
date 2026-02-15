# Domanico-Lovely-Joy_LW1-Image-Classification
1. What is the Fashion MNIST dataset?
Fashion MNIST is a dataset of 70,000 grayscale images featuring 10 categories of clothing and accessories. It serves as a standard benchmark for evaluating image classification models.

2. Why do we normalize image pixel values?
Normalizing scales pixel values to a range between 0 and 1, which prevents mathematical instability. This helps the optimization algorithm converge faster and more efficiently during training.

3. List the layers used and their functions.
The Flatten layer converts 2D images into 1D arrays, while the Dense (ReLU) layer extracts complex patterns from that data. Finally, an output Dense layer calculates probability scores for each of the 10 clothing classes.

4. What does an epoch mean?
An epoch is one complete pass of the entire training dataset through the neural network. During each epoch, the model adjusts its internal weights to reduce error and improve its predictions.

5. Compare the predicted and actual labels.
The model’s predicted label matches the actual ground-truth label for the first test image. This confirms that the network successfully recognized and classified that specific item.

6. How can accuracy be improved?
Accuracy can be improved by adding more layers or neurons to make the model deeper, or by increasing the number of training epochs. Switching to a Convolutional Neural Network (CNN) architecture is also a highly effective way to better capture visual patterns.
