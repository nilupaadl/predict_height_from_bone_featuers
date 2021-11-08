# predict_height_from_bone_featuers
This study was to analyze a data set that aimed to predict the height of human body using a combination of different parts of human bones.

Highlights
===========
* There was one data point that seemed to be an outlier and removed it
* Only data for certain race is filtered as per the request of the resercher
* Sci kit learn only produced R2, hence a separate function was created to measure the adjusted R2
* Normality assumption of the linear regression was found to be satisfactory
* There was no issue of the multicolinearityfor the predictive results, since all the dependencies are true for both training and test sets
* The final results can only be used to predictive purposes only, it can't be used to understand the feature importance due to the multicolinearity effect
* The final model with P, F, FA and sex is resulted with 92.11% R2 in predictive power when used to predict height
