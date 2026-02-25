
## Methods
- variant threshold
- K best features (filter)
- recursive feature elimination (RFE)
- boruta


Why?
- Faster to train
- Improve performance

When?
- Before hyperparameter tuning

## Basic Feature selection process
- Visualize data in features (to get the idea how data are placed)
- Feature that has the low variant -> *BAD Feature*
- Feature that has high variant -> *GOOD Feature*
	
## Some keywords
- *"Class distribution"* -> "this data set has ??? class, each class with ??? sample"
- *"Stratify=y/N"* for train/test split -> Maintain ratio of classes in train and test split
		-> if choose **NO** : *Bad Distribution*, create Bias

## Variant threshold (filter  method)
- variance is a measure of spread from the mean (if the data are close together -> low variant; data are scatter around over the place -> high variant)
	- -> if feature has *variant of 0* -> drop that feature
- Normalize data dict before doing feature selection (using scaller) -> to make feature that has value *very* close to 0 (like 0.9, 0.12) -> becomes 0.0
- 


## K-best feature
- meaning only get *top 'K' best feature* ; K is a number
- 



