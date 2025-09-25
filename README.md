# Kaggle_Ariel_Data_Challenge_25

My final solution was a mixture of careful curve fitting, binning in both wavelength and time, then interpolation in wavelength and LGBM models to improve the fitted estimates, and estimate the uncertainty in the predictions.  I used the [batman model](https://lkreidberg.github.io/batman/docs/html/index.html) for curve fit only to generate an additional feature for the LGBM model.

[More about the Ariel space mission here](https://arielmission.space/)  
[Link to the competition page](https://www.kaggle.com/competitions/ariel-data-challenge-2025)
