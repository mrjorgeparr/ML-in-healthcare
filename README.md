# ML-in-healtchare
Repository containing code corresponding to the lab assignments and final project of the Machine learning in healthcare course. Fall 2023.

## Lab 1

Implementation of an MVAE (multi-view variational autoencoder), capable of learning meaningful, disentangled latent representations from multiple image views. The approach implemented supports image processing however it can be easily extended to multi-modal data through contextual embeddings.

## Lab 2

Complete survival analysis project using Kaplan-Meier and Cox-Hazard models on latent representations of data obtained through UMAP based on subgroups found through mixture models maximizing BIC.


Main code is located inside the notebook

## Final project

 + Title: **Unsupervised analysis of the relationship between various genetic polymorphisms and their relationship to impulse-aggresiveness personality traits**


 Using a highly sparse database containing various information regarding suicidal ideation, abuse and other information of the same nature, as well as genetic polymorphisms , we perform a series of tasks to maximize the clinical insight extracted. Those tasks were 
    1. Dimensionality reduction and clustering based on statistical criteria, helpful for patient profiling.
    2. Frequent itemsets of polymorphisms for personality types. To the extent of our data, since imputated data lacks clinical value, we analyzed the frequent of polymorphisms (of different lengths)itemsets associated to different personality types are. This help in furthering the understanding of the distribution of this DNA mutations and how they can affect the patient.
    3. Analysis of feature importances for detecting which of the features plays a larger role in determining the personality type considering a supervised learning task with the help of random forest.
    4. Survival analysis based on polymorphisms, after dimensionality reduction and clustering, survival analysis methods are programmed to improve the understanding and the impact of these polymorphisms in possible suicidal ideation. 
