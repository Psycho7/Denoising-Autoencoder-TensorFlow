# Denoising Autoencoder
This repo contains the implementation of Denoising Autoencoder (DAE) using TensorFlow and a series of experiments. It starts with [blackecho's gist](https://gist.github.com/blackecho/3a6e4d512d3aa8aa6cf9).

## TODO
- [ ] Add Gaussian noise to the corruption module.
- [ ] Add ReLU as one activation function, in addition to sigmoid and tanh.
- [ ] Compare the performance between different activation functions.
- [ ] Compare the performance between cross entropy and squared loss.
- [ ] Compare different learning approaches.
  - [ ] With or without momentum.
  - [ ] Others.
- [ ] Feed the output from the hidden layer into SVM. Feed the feture map from LeNet-5 into SVM. Then compare their classification performance.
- [ ]  *Unspecified* Use the weight trained from DAE to initialize LeNet-5.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details