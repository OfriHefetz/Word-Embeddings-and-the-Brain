# Word-Embeddings-and-the-Brain

Authors: Ofri Hefetz, Shai Shani Bar

## General
This repository contains our final project in the course "Language, computation and Cognition" taught at Technion University.

## Our project 
This project contains 3 parts: a structured task, a semi-structured task, and an open-ended task in the field of sentence decoding and semantic hierarchies within the brain. 


**In the structured task**, we compared the results of Homework Assignment 3 question 3 using different static word
embeddings, specifically Word2Vec and GloVe. To gain further insights, we reviewed Pereira et al.'s (2018) research
and highlighted the similarities and differences between their analyses.

**In the semi-structured tasks**, we trained a decoder model on datasets from analyses 2 and 3 using the non-contextualized
original sentence representations and representations from a contextualized word embedding model. Finally, we compared
the results of both methods to assess their performance in sentence decoding. Furthermore, we built a brain-encoder
model to predict human neural signals from sentence embedding vector representations. We used linear regression
models for each voxel in the dataset related to analyses 2, calculated R^2 scores, and examined the significance of
associations between word vectors and neural activity. This analysis was conducted using both non-contextualized and
contextualized vector representations.

T**he open-ended task** aimed to investigate and compare the uncovering of semantic hierarchies and explore the hierarchical
structure of semantic representations between BERT representations and fMRI data. We aim to understand how
these two distinct modalities capture and represent semantic information within the brain.
