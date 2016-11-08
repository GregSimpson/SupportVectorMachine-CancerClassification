# IBM Watson Tool Exploration

After my experience with Galvanize, I will be joining Truven Health Analytics. 
http://truvenhealth.com/

Truven has recently been acquired by IBM and is in the process of being integrated into the 
IBM Watson Health group. https://www.ibm.com/watson/health/

Today, I am exploring the IBM SPSS Modeling tool.
This tool makes fast and easy work of Exploratory Data Analysis (EDA), Modeling and Presentation.

The software name originally stood for Statistical Package for the Social Sciences (SPSS),
reflecting the original market, although the software is now popular in other fields as 
well, including the health sciences and marketing.
(https://en.wikipedia.org/wiki/SPSS)


## Table of Contents
### SPSS Modeler
* Overview
* Dataset
* Analysing the Data
* Support Vector Machines
    * The theory
    * Hyperplanes  
    * Kernel Function
* SPSS Model and Results
* SPSS Modeler Summary and Review

---

# SPSS Modeler

## Overview
[IBM marketing description](http://www.ibm.com/support/knowledgecenter/SS3RA7_18.0.0/modeler_mainhelp_client_ddita/clementine/entities/clem_family_overview.html)
IBM SPSS Modeler is a set of data mining tools that enable you to quickly develop predictive models using business expertise and deploy them into business operations to improve decision making. Designed around the industry-standard CRISP-DM model, IBM SPSS Modeler supports the entire data mining process, from data to better business results.
IBM SPSS Modeler offers a variety of modeling methods taken from machine learning, artificial intelligence, and statistics. The methods available on the Modeling palette allow you to derive new information from your data and to develop predictive models. Each method has certain strengths and is best suited for particular types of problems.
                    


## Dataset


The SVM dataset

http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29


The SVM dataset

http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29

http://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/breast-cancer-wisconsin.data







(This is the preliminary SPSS dataset. I will not be positive on this until I have reviews the Cognos Use Cases)

The example is based on a dataset that is publicly available from the UCI Machine Learning Repository and was then modified for the SPSS example collection.
The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics. 
The fields in each record are:

|Field name|Description|
|:--------:|:---------:|
|ID	|Patient identifier|
|Clump|	Clump thickness|
|UnifSize|	Uniformity of cell size|
|UnifShape|	Uniformity of cell shape|
|MargAdh|	Marginal adhesion|
|SingEpiSize|	Single epithelial cell size|
|BareNuc|	Bare nuclei|
|BlandChrom|	Bland chromatin|
|NormNucl|	Normal nucleoli|
|Mit|	Mitoses|
|Class|	Benign or malignant|

For the purposes of this example, we're using a dataset that has a relatively small number of predictors in each record.


## Analysing the Data
screen shots and explanations

## Support Vector Machines

### Theory
[Wikipedia - Support Vector Machine](https://en.wikipedia.org/wiki/Support_vector_machine) 

An SVM model is a representation of the examples as points in space, mapped so that the examples of the separate categories are divided by a clear gap that is as wide as possible. New examples are then mapped into that same space and predicted to belong to a category based on which side of the gap they fall on.
In addition to performing linear classification, SVMs can efficiently perform a non-linear classification using what is called the kernel trick, implicitly mapping their inputs into high-dimensional feature spaces.

### Hyperplanes
[IBM SPSS - SVM Hyperplanes](https://www.ibm.com/support/knowledgecenter/SS3RA7_15.0.0/com.ibm.spss.modeler.help/svm_howwork.htm)
SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable. A separator between the categories is found, then the data are transformed in such a way that the separator could be drawn as a hyperplane. Following this, characteristics of new data can be used to predict the group to which a new record should belong.


### Kernel Function
[IBM SPSS - SVM Kernel Function](https://www.ibm.com/support/knowledgecenter/SS3RA7_15.0.0/com.ibm.spss.modeler.help/svm_howwork.htm)
The mathematical function used for the transformation is known as the kernel function. SVM in IBM® SPSS® Modeler supports the following kernel types:

https://www.quora.com/What-are-C-and-gamma-with-regards-to-a-support-vector-machine
http://scikit-learn.org/stable/auto_examples/svm/plot_rbf_parameters.html
http://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
http://stats.stackexchange.com/questions/168014/where-can-i-read-about-gamma-coefficient-in-svm-in-scikit-learn

• Linear

• Polynomial

• Radial basis function (RBF)

• Sigmoid

A linear kernel function is recommended when linear separation of the data is straightforward. In other cases, one of the other functions should be used. You will need to experiment with the different functions to obtain the best model in each case, as they each use different algorithms and parameters.



## SPSS Model and Results
screen shots and explanations


## SPSS Modeler Summary and Review
screen shots and explanations

something about time
ease of use
adjustability

---


---
## References

(https://www.ibm.com/support/knowledgecenter/en/SS3RA7_18.0.0/modeler_tutorial_ddita/clementine/entities/examples_intro.html) Demo list

(http://www.ibm.com/support/knowledgecenter/SS3RA7_17.0.0/modeler_tutorial_ddita-gentopic1.html)
(http://www.ibm.com/support/knowledgecenter/en/SS3RA7_17.0.0/clementine/example_adp.html)
(http://www.ibm.com/support/knowledgecenter/en/SS3RA7_17.0.0/clementine/example_svm_intro.html)
(https://en.wikipedia.org/wiki/Support_vector_machine)
https://www.ibm.com/support/knowledgecenter/SS3RA7_15.0.0/com.ibm.spss.modeler.help/svm_howwork.htm




