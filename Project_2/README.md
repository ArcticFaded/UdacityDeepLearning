## Welcome to my model :)

In this project I tried out several models, my top one performing at 79% accuracy on the testing set. Without data augmentation I don't see how you could approve this score, you could try out things like random-shifts, random-flips, and random-crops so that the model will identify an object, whether or not it is facing a particular direction.

## VGG-19

In this model each layer drops in size, while increasing in depth (usually by powers of 2). After which it is passed through to two fully connected layers and then a prediction is made. The amount of neurons onthe fully connected layers is lower than on the paper because of hardware limitations of my machine.
