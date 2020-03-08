# AutoEncoder
The repository contains the AutoEncoder implementations using FashionMNIST data. 

By definition **Autoencoders** are a type of neural network that can be used to learn efficient codings of input data. Given some inputs, the network first applies a series of transformations that map the input data into a lower dimensional space. This part of the network is called the encoder.
Then, the network uses the encoded data to try and recreate the inputs. This part of the network is the decoder.

However, there are much more interesting applications for autoencoders.
One such application is called the **variational autoencoder(VAE)**. Using variational autoencoders, it’s not only possible to compress data — it’s also possible to generate new objects of the type the autoencoder has seen before.
