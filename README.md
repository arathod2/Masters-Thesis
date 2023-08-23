# Masters-Thesis
Image classification is mostly done at the pixel level and there is not many research done in 
the feature space. In this project we use the r separation property proposed by (Yang,et al., 
2020) which states that for real world image datasets any data points with different labels 
should be separated by atleast a distance of 2r. We have used type of Generative model for this 
project. First, we build a Variational Autoencoder and after we pass aur data through it and 
train the model, we will find the r separation distance in the latent space of the Variational 
Autoencoder, and the decoder will act as a generator network where we will generate our input 
data from sampling through this latent space of VAE.
