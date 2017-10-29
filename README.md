# Bayes by Backprop

Clever application of ELBO maximization where we can model uncertainty in
our 'model' parameters by fitting a variational distribution to them. The ELBO form 
assumed is similiar to that of VAE formulation, where we minimize 
the KL divergence between the prior over our weights the VA and maximize the data 
log-likelihood marginalized over our VA. 
For Gaussian VA, we only double the number of trainable parameters.
