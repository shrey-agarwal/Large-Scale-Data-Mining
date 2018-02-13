The project has been developed and tested in python2 as well as python3 for compatibility.

The structure is as follows:
There are three files, 2 python notebook (ipynb) and one python file (py)
project2.ipynb and project2-all20.ipynb can be run as it is without making any changes.

To run the files:
If you already have pre-trained models for TF-IDF, LSI, and NMF
1. Set the "load_from_previous" to true
2. Put the models in "models" folder in the same location as the programs.

Otherwise you will have to set the "load_from_previous" to false.
By default, we have set the "load_from_previous" to false so that all the models are trained and then used.
No other changes are required to run the files project2.ipynb and project2-all20.ipynb.

utils.py has some utility functions to save and load models and plot contingency matrix.
