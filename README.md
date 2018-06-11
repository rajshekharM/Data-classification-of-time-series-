# Classification and analysis of time series data classifiers based on deep nueral network models

Given a raw dataset of x,y,z accelerometer data in 10 second windows with various classes labelled against each instance of database,
one needed to extract relevant features from the raw dataset and convert it into useful information .

Then train a supervised classifier to classify the training dataset created correctly using cross validation and finally test the trained model over a blind test dataset.

Compared the time and space complexity graphs and trade-offs for various neural net layers and deep learning models 

Pipeline used :

Python for data wrangling, label extraction from filenames.

MATLAB for feature extraction (as it is least time consuming and good for signal procecssing).

Weka for classification, feature slection, mapping, model training, iterating with various ML algorithms.

Excel or Google Sheets for result visualization, data manipulation.

Facets for feature space visualization.
