# Carbon in the deep upper mantle and transition zone under reduced conditions : insights from high-pressure experiments and machine learning models
Jiali Lei, J ZhangZhou and Sayan Sen

Dataset_M is the file for our training data set containing different values of pressure (GPa),temperature (°C) and melt compositions (Iron, Nickel and Sulfur, Carbon in wt%). Our objective is to predict the Carbon Concentration based on the measured values of P, T, Fe, Ni, S. For this purpose we set P, T, Fe, Ni, S to be the predictors and Carbon to be our target variable and train different ML models to find the best model (based on MAE, MSE or RMSE) for our study that can predict the Carbon values with sufficiently good accuracy.

Dataset_O is our new test data whereby we predict the Cabon concentratrions based on the measured values of P, T, Fe, Ni, S from the best model (Extra Trees) obtained from training on Dataset_M  

Dataset_N is the preedictions from the ML model we used to draw the phase boundaries. 

Dataset_P is the dataset incorporating the uncertainties in the measured values of predictors and the Carbon concentration. We use this as our test dataset to generate samples randomly within the uncertainty range for 1000 Monte Carlo simulations and generate the mean Carbon predicions and standard deviation (2σ variation) and to correlate how the concentrations vary compared to the measured Carbon values.  
