# Word-Embeddings-and-the-Brain

Authors: Ofri Hefetz, Shai Shani Bar

## General
This repository contains our final project in the course "Language, computation and Cognition" taught at Technion University.

## Our project 
This project contains 3 parts: a structured task, a semi-structured task, and an open-ended task in the field of sentence decoding and semantic hierarchies within the brain. 

**In the structured task**, we compared the results of Homework Assignment 3 question 3 using different static word embeddings, specifically Word2Vec and GloVe. To gain further insights, we reviewed Pereira et al.'s (2018) research and highlighted the similarities and differences between their analyses. 

**For the semi-structured tasks**, we trained a decoder model on datasets from analyses 2 and 3 using the non-contextualized original sentence representations and representations from a contextualized word embedding model. Finally, we compared the results of both methods to assess their performance in sentence decoding. Furthermore, we built a brain-encoder model to predict human neural signals from sentence-embedding vector representations. We used linear regression models for each voxel in the dataset related to analyses 2, calculated R^2 scores, and examined the significance of associations between word vectors and neural activity. This analysis was conducted using both non-contextualized and contextualized vector representations.

**The open-ended task** aimed to uncover semantic hierarchies within the brain by analyzing fMRI data collected during language processing tasks. The project involved various steps such as data collection and preprocessing, exploratory data analysis, dimensionality reduction, clustering analysis, statistical analysis, and subcluster analysis.


