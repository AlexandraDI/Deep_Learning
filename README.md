# [Deep Learning](https://github.com/AlexandraDI/Deep_Learning){:target="_blank"}

Implementation of 3 Assignments for the course Deep Learning.
Contributors: Diez Perez Maria, Gianluca Vico.

* [Task 1](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_1/DL_Assignment1.ipynb){:target="_blank"}:
The goal of this task is to produce a neural network model that is best suited for training a given dataset. This dataset consists of a 1000-by-1 vector of 8-bit unsigned integers. The values of the vector are shown below.

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure1.png" alt="zigzag" width="50%" height="50%" />  
</p>

Furthermore, we trained our model to predict a data point one step ahead for a fracture of the data. To solve this issue, we implemented two different architectures to train our data. In the [project report](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_1/DL_Assignment_1.pdf){:target="_blank"}, we explain why we chose these two architectures and present the results. Some of the results are shown below.

Prediction of the next 200 points:

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure2.png" alt="zigzag" width="50%" height="50%" />  
</p>

Evaluate the model on the test data:

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure3.png" alt="zigzag" width="50%" height="50%" />  
</p>

* [Task 2](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_2/DL_Assignment_2.ipynb){:target="_blank"}:
The goal of this task is to produce a neural network model in a recursive fashion to predict the temperature of a city given previous meteorological
measurements. In addition, to find a strategy to determine which features are the more relevant for the results, and to use visualisation techniques to show
them. This dataset consists of a 70128 by 4 by 5 vector that contains the information of the time, the location and the meteorological features respectively. The temperatures of the four locations are shown below.

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure4.png" alt="zigzag" width="100%" height="100%" />  
</p>

In the [project report](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_2/DL_Assignment_2.pdf){:target="_blank"}, we explain the implementation details and present the results. Some of the results are shown below.


Temperature prediction of the next week:

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure5.png" alt="zigzag" width="50%" height="50%" />  
</p>

Experiments between different features:

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure6.png" alt="zigzag" width="75%" height="75%" />  
</p>

* [Task 3](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_3/DL_Assignment_3.ipynb){:target="_blank"}: The data-set consists of several documents with magnetoencephalography data. The goal is to classify the task that the subject was performing during the recording: resting, math and story task, working memory, and motor task. To do so, we implemented a CNN model and trained it with the available training data. We also compared the accuracy of intra-subject and cross-subject
classification. Furthermore, we analyzed the influence of some hyper-parameters on the result and the difference between the training and testing accuracy.

Looking into the Intra case, shown in the image below on the left, we can see how the training loss decreased in the first epoch and then remains falling until
almost the end of the graph, epoch 8, when suddenly appears a significant increment, caused by over-fitting. The accuracy, precision, and recall obtained
in testing Intra classification are 99% and the confusion matrix shows a good performance in the classification.

<p align="center">
 <img src="https://alexandradi.github.io/Alex_Portfolio/figure7.png" alt="zigzag" width="100%" height="100%" />  
</p>

Analyzing the Cross loss plot, the right image above, we can see an unstable loss that is getting higher in the latest epochs. The accuracy with this classifier is worse than with Intra, having a 47% in the first and second set and a 25% in the third. The confusion matrix shows an unsatisfactory performance.

In the [project report](https://github.com/AlexandraDI/Deep_Learning/blob/main/Project_3/DL_Assignment_3.pdf){:target="_blank"}, we explain the implementation details and present the results.

