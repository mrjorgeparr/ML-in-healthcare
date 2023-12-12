# ML-in-healtchare
Repository containing code corresponding to the lab assignments and final project of the Machine learning in healthcare course. Fall 2023.

## Lab 1

Implementation of an MVAE (multi-view variational autoencoder), capable of learning meaningful, disentangled latent representations from multiple image views. The approach implemented supports image processing however it can be easily extended to multi-modal data through contextual embeddings.

## Lab 2

Complete survival analysis project using Kaplan-Meier and Cox-Hazard models on latent representations of data obtained through UMAP based on subgroups found through mixture models maximizing BIC.


Main code is located inside the notebook

## Final project

 + Title: **Unsupervised analysis of the relationship between various genetic polymorphisms and their relationship to impulse-aggresiveness personality traits**



1. **Dimensionality Reduction and Clustering:**
   - Utilize statistical criteria for dimensionality reduction and clustering to create patient profiles.
   - Enhance our understanding of the patient population by identifying patterns in the data.

2. **Frequent Itemsets of Polymorphisms for Personality Types:**
   - Analyze frequent itemsets of genetic polymorphisms associated with various personality types.
   - Considering the limitations of imputed data in clinical value, focus on polymorphisms of different lengths.
   - Contribute to the comprehension of DNA mutation distribution and its impact on patient personality.

3. **Feature Importance Analysis:**
   - Employ a supervised learning approach using a random forest to determine feature importances.
   - Identify the key features that play a significant role in determining personality types.
   - Enhance interpretability and insights for clinical decision-making.

4. **Survival Analysis based on Polymorphisms:**
   - Implement survival analysis methods after dimensionality reduction and clustering.
   - Explore the impact of genetic polymorphisms on the likelihood of suicidal ideation.
   - Improve our understanding of the long-term effects of these polymorphisms and their potential clinical implications.

