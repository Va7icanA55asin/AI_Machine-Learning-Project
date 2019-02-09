Some notes about machine learning

# Terminology
Confusion Matrix- Predictions vs Actual
  * Table of values for each category
  
  
  
Confusion Matrix |                 |Predicted Classes |                 |
-------------------|----------|-------------------|----------
                               |                  | Negative              | Positive 
**Actual Classes**| Negative |       TN                   |         FP
                               |Positive    | FN                          |      TP

  * Accuracy = (TN+TP)/(TN+TP+FN+FP)
  * Precision = TP/(TP+FP)
  * Recall = TP/(TP+FN)
  
Supervised Learning- completely controlled, given input data and labelling

Unsupervised Learning- no labels so algorithm must determine how to use input data

Reinforcement Learning- Given feedback on performance

# K Nearest Neighbor
  * Finding "k" training samples closest to a new sample. Label for new sample based on other samples
  * Radius based algorithms
  * k-NN algorithm- shorthand
    * Works directly on learned samples
    * Set of categories
    * Learnset ***LS*** (labelled instances)
    * If instance *o* element of ***LS*** label of instance used
    *  *o* compared with all ***LS***; distance metric used for comparison
    * Determine *k* closest neighbors where *k* is defined constant and positive (small) integer
    * Most common class then assigned. If *k* = 1, object assigned to class of single nearest neighbor
     
