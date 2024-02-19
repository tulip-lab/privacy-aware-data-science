[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Privacy--aware--Data--Science-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-DP--SGD-orange)](README.md)

# Objective Perturbation and DP-SGD

Objective Perturbation and Differential Privacy Stochastic Gradient Descent (DP-SGD) are two essential techniques in the field of differential privacy, particularly within the context of machine learning optimization.

Objective Perturbation is a method for achieving differential privacy in the training of machine learning models. It involves adding noise directly to the objective function of an optimization problem, such as the loss function in a machine learning model. This perturbation ensures that the resulting model parameters do not reveal sensitive information about the individuals in the training data. The key challenge in objective perturbation is to balance the noise level to maintain the utility of the model while ensuring that the privacy guarantees are met. This technique is particularly effective for convex optimization problems and is widely used in scenarios where the model's accuracy and privacy are both critical.

Differential Privacy Stochastic Gradient Descent (DP-SGD) is a variation of the traditional stochastic gradient descent algorithm, which is fundamental in training deep learning models. DP-SGD modifies the SGD process by adding noise to the gradient computations and applying a clipping mechanism to limit the influence of any single data point. This approach allows the model to learn from the data while ensuring that the training process remains differentially private. DP-SGD is a cornerstone technique in private deep learning, enabling the training of complex models on sensitive datasets without compromising individual privacy.

Both Objective Perturbation and DP-SGD represent significant advancements in privacy-preserving machine learning. They provide robust frameworks for training a wide range of models, from linear classifiers to deep neural networks, ensuring that the privacy of the training data is protected without severely compromising the model's performance.

## :notebook_with_decorative_cover: Lecture Slides Handouts  

- [Lecture: Objective Perburtation](https://github.com/tulip-lab/handouts/blob/main/PaDS/FLIP33.pdf) 

