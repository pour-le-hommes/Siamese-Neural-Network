# Siamese-Neural-Network
Initiated and led an in-depth exploration of Siamese Neural Networks for face recognition of my face with the help of research paper and YouTube. Leveraging the Siamese architecture, this project aimed to facilitate accurate face recognition by learning the similarity between my face and other sample faces.

### Explanation

The full preprocessing phase just consist of 3 steps :

1. Resizing the image into 100x100 pixel size.
2. Normalizing the value inside the image into 0 to 1 values.
3. Add the images into two array, positives and negatives, inside each array consist of the positive/negative image, anchor image, and label (if it’s true or false denoted by 1 and 0 respectively)

While most of the model is just a normal neural network model, there is a unique feature called L1dist, which is short for L1-Distance, to calculate the value difference between the positive/negative value against the anchor value.
