# Carbon-Predictions
Predicting Carbon Concentrations at different P, T and Melt Compositions

Dataset_M is the file for our training data set containing different values of pressure,temperature and melt compositions (Iron, Nickel and Sulfur, Carbon). We train the different machine learning models on this data and predict Carbon values (C) based on the predictors - P, T, Fe, Ni, S. 

Dataset_O is our new test data whereby we predict the Cabon concentratrions based on the measured values of P, T, Fe, Ni, S from the best model (Extra Trees) obtained from training on Dataset_M  

Dataset_N is the preedictions from the ML model we used to draw the phase boundaries. 

Dataset_P is the dataset incorporating the uncertainties in the measured values of predictors and the Carbon concentration. We use this as our test dataset to generate samples randomly within the uncertainty range for 1000 Monte Carlo simulations and generate the mean Carbon predicions and standard deviation (2σ variation) and to correlate how the concentrations vary compared to the measured Carbon values.  
