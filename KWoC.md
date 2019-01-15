---
layout: post
title: KWoC 2018 End Report  
subtitle: My Experience with 5-week program
tags: [IIT KWoC, Analysis Of Variance, Machine Learning, Data Analysis]
---




## About KWoc (Kharagpur Winter Of Code)
Kharagpur Winter of Code is a 5-week long online programme for students who are new to open source software development or want to be
more confident about contributing to open source projects.KWoC provides a great opportunity to get acquainted with Github along with 
Git commands and contribute to open source efficiently.If you love coding and want to learn about software development then KWoC helps
you to get a glimpse of it and gives you a head start.

![img](68747470733a2f2f696d6775722e636f6d2f7978614f644b6b2e6a7067.png)



## Projects
There were many projects to choose from that belonged to various fields of computer science like Android Development, Data Analysis,
Deep Learning, Web Development etc. I contributed to two projects that were based on data analysis and deep learning that are described
below beiefly.

1. [ANONS: Analysis of Variance for Neural Networks](https://github.com/nishnik/ANONS)
    The task was to perform ANOVA (Analysis of Variance) on neural networks to measure the effect of different hyperparameters
    on performance and the interactions among the hyperparameters. A basic MNIST digit classification dataset and CIFAR10 image 
    dataset were used to make neural network model on which the above mentioned statistical test was performed. The basic workflow
    is as follow:
    1. Creating a baseline model on dataset given.
    2. Training the model with different hyperparameters for fixed no. of epochs and logging the accuracy for each epoch in a 
       markdown file. 
    3. Collecting plots of validation error vs epochs in a folder.
    4. Performing Analysis of variance using python.


2. [Automatic Leaf Infection Identifier](https://github.com/johri002/Automatic-leaf-infection-identifier)
    Automatic detection of plant diseases is an important research topic as it may prove benefits in monitoring large fields 
    of crops, and at very early stage itself it detects the symptoms of diseases means when they appear on plant leaves. This 
    enables machine vision that is to provide image based automatic inspection, process control. Comparatively, visual 
    identification is labor intensive less accurate and can be done only in small areas. The project involves the use of 
    self-designed image processing algorithms and techniques designed using python to segment the disease from the leaf, while
    using the concepts of machine learning to categories the plant leaves as healthy or infected.The basic workflow has been    
    well described in the README file of the repository.
    
    
 ## Commits and Description 

|              Repository             | Link to commits                                                                                                         | Commit description                         |
|:-----------------------------------:|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/98b0ecfb96382aeb34b8b8a562c122b9429a0a7d#diff-74d892d318663b2d5d763fd730d8b050)                                | log_cifar.md         |
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/98b0ecfb96382aeb34b8b8a562c122b9429a0a7d#diff-d026b63005772ffcd9a88702b57d3ace)                                | CIFAR10 using colab                        |
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/98b0ecfb96382aeb34b8b8a562c122b9429a0a7d#diff-d026b63005772ffcd9a88702b57d3ace)                                | Added Loss errorVsepochs                 |
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/7c8eb90a1ad0385527ff57143f5f38fd7cb6e556)                                | Anova on fashion MNIST                 |
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/787f8422bb53deab88ccbab5c60e1668c538fe3c)                                | Fasion_log.md                 |
| ANONS                               | [Link](https://github.com/skyrb/ANONS/commit/69076026a96cc14644f4405329d28fa652838d00)                                | Modified code for fashion mnist                |
| Automatic Leaf Infection Identifier | [Link](https://github.com/skyrb/Automatic-leaf-infection-identifier/commit/514b431d7890bbf333293717a9b6871a75b69e09) | Requirement.txt       |
| Automatic Leaf Infection Identifier   | [Link](https://github.com/skyrb/Automatic-leaf-infection-identifier/commit/70be4e68c91a351852441cf98c340854fb13beb4) | Modified classifier.py                |  

## Conclusion
This 5-week long program gave me confidence about my git skills. I got to explore the architecture of neural networks and how the various hyperparameteres effect the performance of the deep learning models. This thought of looking deep into the neural networks and log the performance would not have come to my mind if this program had not been there. The second project  that I followed taught me how a Machine learning project can be modelled with less amount of data and without using the modern frameworks. I am very thankful for the oppurtunity I got to participate in this program. It was really a learning experience.
