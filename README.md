# Credit-card-fraud-detection


## Tools used 

numpy
pandas for importing dataset
matplotlib for data visualization 
seaborn for plotting heat map
sklearn for ml algorithm

## Visualising the data.

Dataset of around 284807 credit card transactions.
Highly imbalanced with around 0.001 class imbalance.

<img src="images/dataset.jpg">

Seperated the dataset to x & y.
x contains around 30 parameters which are a result of PCA dimensionality reduction.
y represent the classes of each of the datapoints.
0 means normal transaction 1 means fraudulent.

<img src="images/dataset histograms.jpg">

## Data preprocessing
Plotting the correlation matrix to find if there are any relation between the parameters

<img src="images/heatmap.jpg">

Performed a basic downsampling to improve class imbalance.

<img src="images/Downsampling.jpg">

## Algorithms used 

Isolation forest &
Local outlier factor.

## Results 
Second algorithm worked better than the first.
Support vector machine wasn't used because it would take longer to train.

Achieved precision of **0.78** and recall of **0.67** on the imbalanced class. 

<img src="images/Results.jpg">
