# Classification-of-animals-using-transfer-learning-and-predicting-top-5-probabilities
The image recognition model called Inception-v3 consists of two parts:

Feature extraction part with a convolutional neural network.
Classification part with fully-connected and softmax layers.

In transfer learning, when you build a new model to classify your original dataset, 
you reuse the feature extraction part and re-train the classification part with your dataset. 
Since you don't have to train the feature extraction part (which is the most complex part of the model), 
you can train the model with less computational resources and training time.

Example

input
img_path = 'dataset/african-elephant-bull.jpg'

OUTPUT = Predicted: [('n02504458', 'African_elephant', 0.667814), 
                        ('n01871265', 'tusker', 0.24733664), 
                        ('n02504013', 'Indian_elephant', 0.02276934), 
                        ('n02391049', 'zebra', 0.00032032427), 
                        ('n06785654', 'crossword_puzzle', 0.00031294647)]
                        

