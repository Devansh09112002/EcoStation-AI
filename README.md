# **The software utilizes machine learning to forecast the yearly carbon dioxide emissions of cellular base stations located worldwide.**
I created an original Machine Learning software that accurately predicts annual CO2 emissions from base stations across the globe. With this software, you can easily determine the predicted CO2 emissions of each country's base stations year by year. 

The values you enter should be (respectively):

**1) Estimated annual CO2 emissions (in kilotons) from diesel generators in mobile towers, predict for 2014**

**2) Estimated annual CO2 emissions (in kilotons) from diesel generators in mobile towers, predict for 2020**

**3) Enter population**

_Example:_ `model_run = model.predict([[int(predict_2014),int(predict_2020),int(predict_population)]])`

_Outpot :_ `Predicted country: ['Latin America']`

