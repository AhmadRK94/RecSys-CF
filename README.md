# RecSys-CF
Implementation of various collaborative filtering methods for recommender systems with implicit feedback.

The methods are:
 * SVD
 * Denoising AutoEncoder (DAE): https://arxiv.org/abs/1802.05814
 * Variational AutoEncoder (VAE): https://arxiv.org/abs/1802.05814
 * Bayesian Personalized Ranking (BPR): https://arxiv.org/abs/1205.2618
 * Light Graph Convolutional Network (LightGCN): https://arxiv.org/abs/2002.02126 and https://arxiv.org/abs/2108.08735 for reading about signBPR loss
 * Embarrassingly Shallow AutoEncoders (EASE): https://arxiv.org/abs/1905.03375
 * Neural Network version of EASE (NeuEASE)
 
Note: the models are not tuned and the accuracies are just for demonstration.<br>
Note: im not sure about my negative sampling procedure but the methods implementations are correct.
