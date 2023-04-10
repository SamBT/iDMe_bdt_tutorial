The code for the tutorial is in `bdt_intro.ipynb`. In order for the notebook to work, you need to have `XGBoost`, `uproot`, `numpy` and `matplotlib` installed (at a minimum). You will need to download the files [here](https://cornell.box.com/s/r6r1erz5vs8oysgxvgqul15u3vy9zna9) and put them into a folder called `samples` in order for the notebook to work (you can also just change the file paths coded into the notebook). Download at least the samples in the `signal` folder, and the `bkg_2018_QCD_TuneCP5_PSWeights_minimal_cuts` samples in the `bkg` folder to get started.

This tutorial notebook shows you how to interface with ROOT files using `uproot`, and how to organize data and feed them into an XGBoost classifier (most of the XGBoost code is borrowed from [this BDT tutorial](https://github.com/k-woodruff/bdt-tutorial/blob/master/bdt_tutorial.ipynb)).