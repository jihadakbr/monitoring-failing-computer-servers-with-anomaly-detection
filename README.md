
# Monitoring Failing Computer Servers with Anomaly Detection

This project was completed as a part of the Honors portion of the [Unsupervised Learning, Recommenders, Reinforcement Learning](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning) Course on [Coursera](https://www.coursera.org/).

Credit to DeepLearning.AI, Stanford, and the Coursera platform for providing the course materials and guidance.

## Objective

In this project, I will be implementing an anomaly detection algorithm to identify abnormal behavior in server computers. The dataset consists of two features: throughput (mb/s) and latency (ms) of each server's response. With 307 examples of server behavior, the dataset remains unlabeled ( {𝑥(1),…,𝑥(𝑚)} ).

The main objective is to distinguish between "normal" and "anomalous" examples within the dataset. To achieve this, I will employ a Gaussian model to detect anomalies effectively.

Initially, I will work with a 2D dataset to gain a visual understanding of the algorithm's functioning. By fitting a Gaussian distribution to this dataset, I will identify values with remarkably low probabilities, which can be considered anomalies.

Subsequently, I will apply the developed anomaly detection algorithm to a larger dataset containing multiple dimensions, simulating a real-world scenario with more complex data. Through this report, I aim to demonstrate the efficacy of the Gaussian-based anomaly detection approach and its potential application in various server monitoring contexts.
## Results

![Anomaly Detection Using Gaussian Contours](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh185xgmqITbnJfJRgItiKmRZWjbGQ7ItSYB3eBMZYU6iUksveU82z0ddkLRBElhMODFGYJoX61JpldtxzLix3Y02txXjUhmxdBhWLDImVE3xtKpazvRG-_Dqg5w4hSYgfm8jRl4XelGG7um78o2_8Vb8DRfjQ32CWr3Hwh0xKie04gXIBN58QSHY17qoM/s1600/anomaly-detection-using-gaussian-contours.png)