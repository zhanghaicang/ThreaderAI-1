# ThreaderAI
Template-based prediction of protein structure with deep-learning.

We propose a new template-based modelling method called ThreaderAI to improve protein tertiary structure prediction. ThreaderAI formulates the task of aligning query sequence with template as the classical pixel classification problem in computer vision and naturally applies deep residual neural network in prediction. ThreaderAI first employs deep learning to predict residue-residue aligning probability matrix by integrating sequence profile, predicted sequential structural features, and predicted residue-residue contacts, and then builds template-query alignment by applying a dynamic programming algorithm on the probability matrix.
