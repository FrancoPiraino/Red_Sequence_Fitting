# Red_Sequence_Fitting

##################### Using_sklearn_to_fit_gaussians code ####################
 
To fit a gaussian distribution, we use sklearn.mixture.GaussianMixture  class
(https://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html) 
from the python scikit-learn library that I think you should install it (https://scikit-learn.org/stable/install.html). 
In this code you can test this library.


##################### Fitting RMS in CMD with sklearn code #####################

Code to fit a red sequence in a CMD 

To fit the red-squence line the code separate the magnitude axis in four bins 
and then, across the color axis, a double gaussian is fitted (or 1 gaussian depending 
on the amount of data in the bin) for each b

The code needs to read a table that contains magnitudes for r and g band. 

In the code, the limits of the bins are defined and then the double gaussian is fitted
for each bin in four different cells, where also the number of components that we want are 
defiend, and a random number that usually is 0.

For the outputs results, the code should give you the magnitude
and color for the reddest peak gaussian for each bin and the slope
and intercept for the rs equation and the same results for the 
intersection point between the two gaussians, 
in the case that you have fitted a gaussian with two components.



