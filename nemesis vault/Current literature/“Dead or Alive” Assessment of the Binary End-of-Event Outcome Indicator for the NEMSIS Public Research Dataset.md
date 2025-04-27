https://www.tandfonline.com/doi/abs/10.1080/10903127.2024.

### Objectives

The National Emergency Medical Services Information System (NEMSIS) provides a robust set of data to evaluate prehospital care. However, a major limitation is that the vast majority of the records lack a definitive outcome. This study aimed to evaluate the performance of a recently proposed method (“MLB” method) to impute missing end-of-EMS-event outcomes (“dead” or “alive”) for patient care reports in the NEMSIS public research dataset.

### Methods

This study reproduced the recently published method for patient outcome imputation in the NEMSIS database and replicated the results for years 2017 through 2022 (_n_ = 686,075). We performed statistical analyses leveraging an array of established performance metrics for binary classification from the machine learning literature. Evaluation metrics included overall accuracy, true positive rate, true negative rate, balanced accuracy, precision, F1 score, Cohen’s Kappa coefficient, Matthews’ coefficient, Hamming loss, the Jaccard similarity score, and the receiver operating characteristic/area under the curve.

### Results

Extended metrics show consistently good imputation performance from year-to-year but reveal weakness in accurately indicating the minority class: e.g., after adjustments for conflicting labels, “dead” prediction accuracy is 77.7% for 2018 and 61.8% over the six-year NEMSIS sub-sample, even though overall accuracy is 98.8%. Slight over-fitting is also present.

### Conclusions

This study found that the recently published MLB method produced reasonably good “dead” or “alive” indicators. We recommend reporting of True Positive Rate (“dead” prediction accuracy) and True Negative Rate (“alive” prediction accuracy) when applying the imputation method for analyses of NEMSIS data. More attention by EMS clinicians to complete documentation of target NEMSIS elements can further improve the method’s performance.