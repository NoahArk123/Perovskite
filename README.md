# Prediction of perovskites' water-splitting ability

Our study aims at predicting whether a given perovskite has water-splitting ability. Since materials’ water-splitting ability is mainly determined by its band 
structure and heat of formation, our main task is to predict perovskite’s conduction/valence band energy and heat of formation based on atom’s easy accessible 
parameters like electronegativity, ionization energy, etc. Two methods are applied for predictions (i) kernel ridge regression (ii) neural network. We compare the 
predictions made by the two models and analyze the outliers. At last, a Graphical User Interface is setup which can read in a perovskite user input and return: (i) 
predicted values of the perovskite (ii) perovskite’s water splitting ability. 


GUI user guide:

1. Git clone or download our repo.
2. Type _python GUI.py_ in command line and enter(please wait for a while because it is a little slow...). Then the GUI interface will jump out.
3. Input A_ion, B_ion, anion, mass and volume(for example: Ca, Nb, O2N, 168 and 60.3), then click ok. 
4. Please wait for a while, the text box on bottom will show the result on whether it can do water-splitting.
5. If you cannot open the GUI.py, then just open the GUI4.0.ipynb, run the cell, it will show the same GUI.

Jupyter notebook:
the jupyter notebook files under PredictWaterSplit show step by step how we develop our KRR and NN model. 

Requirements:

Before using our package, you should install these modules:
numpy
pandas
matplotlib
keras
tkinter
sklearn
sqlalchemy
itertools
scipy
