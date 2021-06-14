# Text-Classification

This work represents a project for the clustering of text documents by keywords in Russian, in particular, patent abstracts. This is a clustering task. Algorithm testing is carried out in two stages. First, the results are analyzed on the trained sample, and then the clustering analysis is used for a new sample.

### Files : 

- google\_patents.csv - result from google patents service
- patents.csv - downloaded patent texts 
- clusters.csv -  is the data on which the model was trained with the clustering result
- validation.csv - new data sample with clustering results
- frequensy.csv - result of frequency analysis
- converter.py - code parse data from google\_patents.csv and the web links of files and extract text from the pdf file.
- cluster.ipynb - code with preprocessing of data and clustering

