# Denoising Autoencoder
This repo contains the implementation of Denoising Autoencoder (DAE) using TensorFlow and a series of experiments. It starts with [blackecho's gist](https://gist.github.com/blackecho/3a6e4d512d3aa8aa6cf9).

## Prerequisites
- Python 3
- TensorFlow 1.0
- NumPy
- Pickle

## TODO
- [x] Improve original code.
  - [x] Update to Python 3 and TensorFlow 1.0.
  - [x] Modify the default values of hyper-parameters.
  - [x] Export Origin / Corrupted / Decoded image.
  - [x] Miscellaneous (see [commits](https://github.com/Psycho7/Denoising-Autoencoder-TensorFlow/commits)).
- [x] Add Gaussian noise to the corruption module.
- [x] Add ReLU as one activation function, in addition to sigmoid and tanh.
- [x] Compare the performance between different activation functions.
- [x] Compare the performance between cross entropy and squared loss.
- [x] Compare different learning approaches.
- [x] Feed the output from the hidden layer into SVM. Feed the feture map from LeNet-5 into SVM. Then compare their classification performance. (This [gist](https://gist.github.com/Psycho7/82591b258920cd2ec75c11e0efe431e8) helps to extract features from LeNet-5)
- [ ] Use the weight trained from DAE to initialize LeNet-5.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details