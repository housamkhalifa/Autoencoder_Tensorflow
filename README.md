# TensorflowExamples
Examples based on Google's Tensorflow to help you understand some of the concepts in machince learning.


Some of the codes are taken from (pkmital) : https://github.com/pkmital/tensorflow_tutorials

1. basic_autoencoder_example.ipynb:
- This code implements a basic autoencoder algorithm using tensorflow
- You can add your own dataset as follow:
   -   data = skimage.io.imread_collection('path/your/training/file/*.png')
   -   test_sample = skimage.io.imread('path/to/your/test/image')
- Then you need to define the the dimension for each layer 
    - e.g dimensions = [2500, 2300, 2000, 1700, 1400, 1100, 800, 500, 300]
- Finally before you call the main function you need to define:
   -   batch size
   -   number of iterations
  
