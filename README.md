# MetSummarizer
This repo contains the code that generates the results from "MetSummarizer: Repository Scale Classification and Decompositionof Tandem Mass Spectral Data".


## Correspondence between notebooks and sections in "MetSummarizer: Repository Scale Classification and Decompositionof Tandem Mass Spectral Data"
This repo contains 3 notebooks. 

* Notebook - Increasing Samples.ipynb corresponds to the section "Increasing accuracy of prediction by aggregation of datasets".
* Notebook - Disease Prediction.ipynb corresponds to the section "Classification of phenotypes".
* Notebook - Food Decomposition.ipynb corresponds to the section "Detecting raw ingredients of complex dishes"


## How to run this repo
Simply clone this repo on your local computer. First unzip the two zip files present, and then from within the cloned directory run the command "jupyter notebook". Running this command should lead you to an interface in your browser from which you can navigate to 3 notebooks. Upon navigating to a specific notebook, simply run each block of code starting from the top.

## Description of Files in Repository


* Anything file with Label in its name corresponds to a subset of the metadata for each sample
* FileCompoundFeatures contains features of each sample
* ColumnNames gives what each column in the label matrices corresponds too
* FoodCompositions corresponds to complex foods and the ingredients that compose them
* 
* UniqueFilesNamesForFoods corresponds to columns of in FoodMatrix
