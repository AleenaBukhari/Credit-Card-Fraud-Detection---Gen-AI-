# Credit-Card-Fraud-Detection Gen-AI
SecureTrust Financial Services, a financial institution, has asked us to help them improve the accuracy of their fraud detection system. The model is a binary classifier, but it's not performing well due to data imbalance. Through frameworks such as TensorFlow and Keras in Python, I have created and trained a Generative Adversarial Network(GAN) to  to create synthetic fraudulent transactions that closely resemble real transactions.

The generator is designed to transform random noise into synthetic data, while the discriminator evaluates these outputs against real fraudulent transactions to determine their authenticity. Training emphasized two key parameters: the number of epochs and the batch size. The linear graph results indicate that as the number of epochs increased, the generator’s capacity to produce synthetic data closely resembling real fraudulent transactions improved significantly. 

