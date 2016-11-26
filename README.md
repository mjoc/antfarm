# Neural Network Scratch Code #

* Some scratch work to study Bayesian Neural Networks (ala MacKay) and Networks with *Energy* Based Units
* First implement a regular FeedForward, gradient-based Back Prop system
* Currently only softmax output and tanh hidden units work.
* Batch Back-prop is implemented
* Some preprocessing of input (normalisation) is implemented but want to add eignevector stuff (PCA at least)
* Weight randomisation currently is only implemented as Gaussian with standard deviation as parameter
* Using GSL but I will change to Eigen for matrix stuff
* Plan to create an R package for ease of use.
* Plan to use STAN for the Bayesian stuff, when I figure it all out
* Watch out, Tensorflow
