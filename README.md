# k-Twisted-Strip
Can an autoencoder learn to encode a 2-twisted strip sitting in 3D using a 2D latent space? Mathematically, this is possible because the 2-twisted strip is homeomorphic (i.e., topologically the same) as a disc.

It turns out that naïve gradient descent, using state-of-the-art optimizers (e.g. Adam), does not find this global minimum.
This implies that at certain points in the training process, higher-order optimization methods to deal with singularities are necessary.
