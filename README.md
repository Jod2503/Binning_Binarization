# Binning: 
used to convert numeric data to categorical data.

It is of 3 types

1. Uniform binning: bin/interval length are uniform

2. Quantile binning: bin length are based on perentiles

3. K-means binning: random centroids are chosen, bisected, and then posn is changed to mean of the data. Process is repeated until no change in posn of centroids.

4. Imported using the 'KBinsDiscretizer class in sklearn.preporcessing

# Binarization:
Used to convert numerical data into binary categorical data (0,1)
imported  by Binarizer class in sklearn.preprocessing
