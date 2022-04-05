# Intro

Consistency training has been used for self-supervised learning tasks when large amounts of unlabeled data is available. But what if insufficient sized noisy data is available. Does it constrain model predictions to be invariant to input noise. In the reference work, RandAugment and back-translation have been used to add noise to mimic natural distributional shifts in vision data. Does encouraging a model to make consistent predictions against such shifts make it smarter to counter it and make better predictions? 
Lets use a vision dataset to find out if feeding a noisier version of similar images allows the model to learn about such imperfections in data when [trainied with consistency regularization](/consistency_training.ipynb).

# References

https://arxiv.org/abs/1904.12848

https://keras.io/examples/vision/consistency_training/

https://www.happywhale.com
