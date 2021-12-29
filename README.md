# MNIST-classifier

This is the solution of an MNIST classifier that trains to 99% accuracy or above, and does it without a fixed number of epochs -- i.e. the training stops once that level of accuracy is reached.

Some notes: 
1. It should succeed in less than 10 epochs, so it is okay to change epochs= to 10, but nothing larger
2. When it reaches 99% or greater it should print out the string "Reached 99% accuracy so cancelling training!"

Solution logs:
Epoch 1/10
60000/60000 [==============================] - 10s 175us/sample - loss: 0.2540 - acc: 0.9276
Epoch 2/10
60000/60000 [==============================] - 10s 167us/sample - loss: 0.1126 - acc: 0.9660
Epoch 3/10
60000/60000 [==============================] - 10s 167us/sample - loss: 0.0768 - acc: 0.9772
Epoch 4/10
60000/60000 [==============================] - 9s 157us/sample - loss: 0.0577 - acc: 0.9821
Epoch 5/10
60000/60000 [==============================] - 13s 208us/sample - loss: 0.0434 - acc: 0.9863
Epoch 6/10
60000/60000 [==============================] - 14s 226us/sample - loss: 0.0352 - acc: 0.9892
Epoch 7/10
59840/60000 [============================>.] - ETA: 0s - loss: 0.0265 - acc: 0.9918
Reached 99% accuracy so cancelling training!
60000/60000 [==============================] - 13s 217us/sample - loss: 0.0266 - acc: 0.9917

Output: ([0, 1, 2, 3, 4, 5, 6], 0.9917333)
