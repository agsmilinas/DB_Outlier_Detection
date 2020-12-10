# DB Outlier Detection

Simple python script to detect distance based outliers DB(pi,r) for two-dimensioned datasets, based on the definition in the paper LOF: Identifying Density-Based Local Outliers by Markus M. Breunig†, Hans-Peter Kriegel, Raymond T. Ng, Jörg Sander using two different distances: Euclidean and City Block (Comprehensive Survey on Distance/Similarity Measures between Probability Density Functions by Sung-Hyuk Cha in INTERNATIONAL JOURNAL OF MATHEMATICAL MODELS AND METHODS) using the Zahn dataset as en example. This script includes the comparison of an increasing minimum distance (vector R; this minimum distance is the radii within a hypersphere constantly growing to match the diameter of the data set.) and the percentage pi from 1 to 20% in the cardinality of the analyzed data set.

- DB Outliers with Euclidean Distance

![Image](https://raw.githubusercontent.com/agsmilinas/DB_Outlier_Detection/master/gif/out.gif)


- DB Outliers with City Block Distance

![Image](https://raw.githubusercontent.com/agsmilinas/DB_Outlier_Detection/master/gif/out2.gif)
