# Mathematics of Deep Learning
You can determine importance of each pixel by finding the gradient of the input image
You want each layer to have the same variance

# GAN
ex: we want to make the network classify something as an iguana
We find the y_hat for iguana
We look for an x that matches that y_iguanan
This means the loss of the SSD(network(X), y_iguana)

ex: we want to make the network classify a cat as an iguana
Loss is defined as SSD(network(x) - y_iguana) + λ*SSD(x, x_cat)
Generate your own adverserial examples, add them to the training set

Generator "G"
Disrimator "D"
BAN and real data are fed into D
y = 0 if from GAN
y = 1 if from real world

The -loss of the disriminator is the loss function for the GAN