# random_forest_classifier_magic_dataset
### Gamma–Hadron Classification using Random Forests and Q-Factor Optimization
This project focuses on the classification of gamma-ray and hadron-induced air showers using Hillas parameters derived from Imaging Atmospheric Cherenkov Telescope (IACT) simulations. By combining domain-specific feature analysis with machine learning, the goal is to distinguish signal (gamma) from background (hadron) events in a physically meaningful way.

The workflow includes exploratory data analysis, feature selection based on physical interpretability, and training a Random Forest classifier within a resampling pipeline to address class imbalance. Model performance is evaluated not only through standard metrics (accuracy, precision, recall, F1-score) but also through the Q-factor, a domain-specific metric widely used in gamma-ray astronomy to optimize signal significance.

A threshold optimization strategy is implemented using predicted probabilities ("gammaness") to balance gamma efficiency and hadron rejection, providing a practical decision boundary for event selection.
### Results
Accuracy: ~83%
Gamma Efficiency: ~90%
Hadron Leakage: ~29%
Optimal Q-factor: ~1.67 at threshold ≈ 0.5
