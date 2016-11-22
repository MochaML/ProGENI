# *ProGENI* - Prioritization of Genes Enhanced with Network Information
#### Amin Emad
#### KnowEnG BD2K Center of Excellence
#### University of Illinois Urbana-Champaign

# Motivation
Identification of genes whose basal mRNA expression can predict a phenotype (e.g. sensitivity of tumor cells to different treatments) in an important task in bioinformatics. For example, in the context of genes predictors of drug sensitivity, screening the expression of these genes in the tumor tissue may suggest the best course of chemotherapy or suggest a combination of drugs to overcome chemoresistance. We present ProGENI (Prioritization of Genes Enhanced with Network Information) a novel computational method to identify such genes by leveraging their basal expressions and prior knowledge in the form of an interaction network. ProGENI is based on identifying a small set of genes where a combination of their expression and the activity level of the network module surrounding them shows a high correlation with drug response, followed by the ranking of the genes based on their relevance to this set using random walk techniques.

The figure below depcits the method overview in the context of drug response. 

![Method Overview](/images/Pipeline_ProGENI.png)

# Requirements

In order to run the code, you need to have Python 3.5 installed. In addition, the code uses the following python modules/libraries which need to be installed:
- [Numpy](http://www.numpy.org/)
- [Scipy](https://www.scipy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Sklearn (scikit-learn)](http://scikit-learn.org/stable/)
Instead of installing all these libraries independently, you can use prebulit Python distributions such as [Anaconda](https://www.continuum.io/downloads), which provides a free academic subscription.

# Input files

ProGENI requires three files as input.
1- 
