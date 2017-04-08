# A simple neural network
- _an implementation of a simple neural network_     
- _done in Python and Numpy, with no external machine learning framework used_    



The purpose of this project was to understand the full architecture of a neural network and to visually break down what's going on while training to recognize handwritten digits. 

#### DONE:

###### Setting up:    
- [x] execute ipython notebook from commandline in the same folder as `NeuralNetwork_Handwritten_Recognition`
- [x] when the broswer is open launch `NeuralNetwork_Handwritten_Recognition.ipynb`
 

###### Training:    
- execute the code using the `jupyter notebook interface`

#### TO IMPROVE:
Even though you can get some insights into the learning during training, the network is extremely slow!
This is mainly because it was never designed and optimized to process large volume of images.
It would be great to rewrite this in:
- CNN from scratch
- Theano or Tensorflow


#### FURTHER IDEAS:
- once optimized -> build an interactive visualization in the browser of the filters being trained
- building a generative model that reproduces the image based on a label
- maximizing a given classification (final activation) by backpropagating all the way to your image (input layer) and updating pixel values -> could provide some better intuition on what the network thinks of a class's features.



