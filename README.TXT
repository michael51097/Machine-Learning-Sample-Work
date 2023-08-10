The Final project for this Machine learning Course centered around an autoencoder section and a classification section, all done on scRNA-seq data in the form of counts.

The primary document with all part together --> Final_ML_project.pdf 

AUTOENCODER: Part 1:
- In the the autoencoder section we trained an autoencoder using the keras python package. The goal was to demonstate how using an autoencoder before dimensionalty reduction
could help better cluster the data. The two dimensionalty reduction techniques we used were PCA and T-SNE. And in each of these putting the data through an autoencoder
before dimensionality reduction helped with clustering

CLASSIFICAITON: Part 2:
- In the second section we wanted to test out different classification techniques to see which would work the best. The four classification methods
I used to try and classify the data back to cell types were a decision tree with cross-validation, random forest, random forest with bagging and finally
a feed- forward neural network (FFNN).The accuracy is in order from left to right is 66.7%, 70.7%, 73.6% and 84.3%. Overall making the FFNN the most effective at classifying
each sample into the right cell type.
