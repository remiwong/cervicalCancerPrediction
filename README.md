# cervicalCancerPrediction
Use of Data mining tool to predict the risks of contracting cervical cancers.  Based on the UCI library cervical cancer dataset: https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29

# Cervical Cancer Prediction
Use of Data mining tool to predict the risks of contracting cervical cancers.

Based on the UCI library cervical cancer dataset: https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29

## Properties of Dataset
* 858 Tuples
* 21 Input Variables
* 8 Class Variables
* Presence of missing and dirty values

## Visualisation
The dataset was pre-processed and the different anomalities in the data were removed where necessary before the visualisation process.

A set of charts were generated on Tableau Visualisation tool to be able to learn the different patterns between the different patients who participated in the research and the confirmed cases of cervical cancer.

Important observations:
- THe majority of participants were aged between 15 and 45.
- Most cancer positive cases are registered for participants between 25 and 41.
- Sexually Transmitted Diseases were not seen to have a considerable impact on risks of cancer.
- Hormonal Contraceptives, Intrauterine Device (IUD), and number of Pregnancies were seen as high contributors in the risks of contracting cervical cancers.

## Model
- Multilayer perceptron neural network prediction model.
- 21 Input, 2 hidden layers (8 + 10 nodes), and 1 output
- Uses Cross-Validation performance method to improve the efficiency of the algorithm.


## Results
- Original Dataset split into Training set (838 tuples) and Test set (20 tuples).
- Test set predicted with a minimum accuracy score of 95 %.
- N-Fold Evaluation with 4 folds of 215 tuples each and generated a mean accuracy of 98.5 %.
- Precision and Recall evaluations were carried out. (precision: 0.60, recall: 0.75, true positive rate: 0.75, false positive rate: 0.0263, true negative rate: 0.97, and false negative rate: 0.03).

# Take Aways
* The training dataset being unbalanced with a majority of expected negative classes cause the model to perform better with inputs expecting negative outputs.
* The performance of the model could be improved by feeding more positive classed training tuples. Ideally the proportion of positives to negatives need to be equal.
* The model could be valuable in the detection and prediction of cervical cancers.

<b>Please refer to `cervical cancer prediction.pdf` documentation to read more on the machine learning research carried on the dataset</b>
