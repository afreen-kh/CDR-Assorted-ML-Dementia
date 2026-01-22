# Classifier Overview

This study presents a systematic evaluation of a diverse set of supervised machine learning classifiers to assess their effectiveness in dementia prediction using MRI-derived and clinical features. A total of twenty classifiers were selected to represent a broad spectrum of learning paradigms commonly employed in clinical machine learning research.

The evaluated models can be broadly categorized into the following groups:

## Generalized Linear Models
This group includes regularized logistic regression, ridge classifiers, perceptron-based models, and stochastic gradient descent–based classifiers. These models offer interpretability and computational efficiency, making them attractive for large-scale clinical datasets.

## Probabilistic Models
Naïve Bayes classifiers, including Bernoulli and Gaussian variants, were included to assess probabilistic decision-making under strong independence assumptions. These models serve as useful baselines despite their relatively simple structure.

## Support Vector Machines
Both linear and non-linear support vector classifiers were evaluated to capture margin-based decision boundaries in high-dimensional feature spaces. These models are known for their robustness to overfitting under appropriate regularization.

## Discriminant Analysis
Linear and quadratic discriminant analysis models were included to examine class separability under Gaussian assumptions, enabling comparison between linear and non-linear decision boundaries.

## Neighbor-Based Models
The k-nearest neighbors classifier was employed to evaluate instance-based learning behavior, particularly in settings with overlapping class distributions.

## Tree-Based and Ensemble Models
Decision trees and ensemble approaches—including bagging, random forests, extremely randomized trees, and boosting methods—were assessed to capture non-linear feature interactions and improve predictive stability through aggregation.

## Neural Network Model
A multi-layer perceptron was included to represent neural network–based learning, enabling comparison with both classical and ensemble-based approaches.

This comprehensive selection allows for a balanced comparison across interpretability, complexity, and predictive performance, providing insight into how different algorithmic families behave in dementia prediction tasks.
