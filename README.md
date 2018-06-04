### MNIST-tensorflow : 
DNN 5 hiddens layers, 100 neurons, activation function ELU

#### Comparaison results with : 
DNN, DNN + batch normalisation, DNN + batch normalisation + dropout

#### Transfer learning :

Training DNP with label 0-4 and save model.

create a new DNN that reuses all the pretrained hidden layers of the previous model, freezes them, and replaces the softmax output layer with a new one.
Train new model on label 5-9 on small dataset (100 images by class)

Comparaison time with and without cache on freezen layers 