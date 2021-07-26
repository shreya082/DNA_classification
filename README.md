# DNA_classification
Problem Statement and Background
On a DNA sequence, there are some points at which
'superfluous' DNA is removed during the process of protein
creation.
These points are called Splice Junctions. The parts of the DNA
sequence retained after splicing are called as Exons.
The parts of the DNA sequence that are spliced out are called
as Introns.
The boundary between exons and intron is referred to as EI site
also referred to as 'Donors'.
The boundary between intron and exon is referred to as IE site
also referred to as 'acceptors'.
Given a DNA sequence, The problem posed by this dataset is
to recognise the corresponding site of the given DNA
sequence.

The Data Source You Intend to Use

https://archive.ics.uci.edu/ml/machine-learning-databases/molecular-
biology/splice-junction-gene-sequences/

Description of the Tools You Plan to Use

Matplotlib & seaborn - Python Library used for visualization

Pandas - For data manipulation and analysis

Numpy - used for working with arrays

scikit learn - classification, regression, clustering and dimensionality reduction.
NLTK - for processing DNA sequence

Evaluation Strategy:

Confusion matrix

Classification Accuracy : Number of correct predictions / Total number of predictions.

Precision :gives the fraction of correctly identified as positive out of all predicted as positives.

Recall : Recall gives the fraction you correctly identified as positive out of all positives.

ROC curve : For each possible threshold, the ROC curve plots the False positive rate versus the true positive rate
