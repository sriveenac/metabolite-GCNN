# metabolite-GCNN
## ECE271B Final Project

# Leveraging metabolite connectivity for Cancer diagnosis using Graph Convolutional Neural Networks

## Abstract From Paper
Metabolic reprogramming is a hallmark of cancer, and
metabolomics offers insight into the pathophysiology of the
disease, allowing us to leverage metabolic data for classification of cancer patients. Through formulating the Cancer
diagnosis as a classification problem, the effectiveness of
various Machine Learning models can be compared on the
task of discriminating Cancer patients from healthy individuals. The commonly used models in metabolomics literature, namely Partial Least Squares Discriminant Analysis,
Support Vector Machines, Random Forest Classifiers, and
Artificial Neural Networks, have demonstrated success in
applications to metabolomic data. However, the choice of
their usage for classification tasks as opposed to other more
complicated ML models has not been examined rigorously.
Building off the systems biology approach of modelling
metabolite interactions and pathways as networks, we consider a novel approach for classification of cancer patients
using a Graph Convolutional Network (GCN) model on a
dataset of colorectal cancer patients and controls. Our
findings show that the GCN outperforms most of the commonly used methods significantly, with the exception of
the Random Forest Classifier whose performance, while
slightly worse, is comparable to that of our model. Our
findings suggest that there is promise in applying GCNs
to metabolomics research and it could aid cancer diagnosis efforts by utilizing non-invasive methods of extracting
metabolomic data.

Link to Paper: https://drive.google.com/file/d/14Ej4bw5rP2aD3xKIlGRZRMsQVJpfuMIO/view?usp=sharing

### Disclaimer: The code for the GCN was inspired by  Michael Defferrard, Xavier Bresson, and Pierre Van dergheynst's paper titled: "Convolutional neural networks on graphs with fast localized spectral filtering." published in Advances in Neural Information Processing Systems, 2016.
### The Datatset comes from Yachida et al. (paper title: Metagenomic and metabolomic analyses reveal distinct stage-specific phenotypes of the gut microbiota in colorectal cancer.
