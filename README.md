# Masters-Thesis
Image classification is mostly done at the pixel level and there is not many research done in 
the feature space. In this project we use the r separation property proposed by (Yang,et al., 
2020) which states that for real world image datasets any data points with different labels 
should be separated by atleast a distance of 2r. We have used type of Generative model for this 
project. First, we build a Variational Autoencoder and after we pass aur data through it and 
train the model, we will find the r separation distance in the latent space of the Variational 
Autoencoder, and the decoder will act as a generator network where we will generate our input 
data from sampling through this latent space of VAE.


Due to the recent progress in machine learning we know how incredibly powerful and 
successful it is, many different tasks that could not be solved with software before are now 
solvable, thanks to deep learning and convolutional networks and gradient descent all of these 
technologies are working really well. Until just a few years ago these technologies didn’t really 
work. In about 2013, we started to see that deep learning achieved human level performance at 
a lot of different tasks. we saw that convolutional nets could recognize objects and images and 
score about the same as people in those benchmarks. Part of the reason that algorithms score 
as well as people is that people can’t tell the difference between Alaskan huskies and Siberian
huskies very well, but modulo the strangeness of the benchmarks deep learning caught up to 
about human level performance for object recognition in 2013. That same year we also saw 
that for object recognition applied to human faces caught up to about human level that suddenly 
we had computers that could recognize faces about as well as you or I could recognize faces of 
strangers. We also saw that computers caught up to reading photos and fonts to us. It even got 
to the point that we could no longer use CAPTCHAs to tell whether a user of a webpage is 
human or not because the convolutional network is better at reading obfuscated text than a 
human is. So, with this context of deep learning working well especially for computer vision 
and its ever-increasing use in safety and security critical applications, there is an increasing 
concern over its trustworthiness, reliability, accuracy and dependency. Even with all its 
advancement in Adversarial examples, most of the research on Image Classification, Computer 
vision and Object detection is focused on the pixel level. In this project, we will explore how 
to test Deep learning techniques at feature level based on the Generative models. GANs are 
used to generating test cases, these test cases need to have a ground truth label based on the rseparation distance. For each one we can query a ML model and its testing to see if the 
predicted label is the same as the ground truth label therefore, we will have our accuracy.
