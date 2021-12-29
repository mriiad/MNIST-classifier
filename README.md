# MNIST-classifier

This is the solution of an MNIST classifier that trains to 99% accuracy or above, and does it without a fixed number of epochs -- i.e. the training stops once that level of accuracy is reached.

Some notes: 
1. It should succeed in less than 10 epochs, so it is okay to change epochs= to 10, but nothing larger
2. When it reaches 99% or greater it should print out the string "Reached 99% accuracy so cancelling training!"
