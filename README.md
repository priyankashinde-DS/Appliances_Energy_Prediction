# **Appliances Energy Prediction**

![image](https://user-images.githubusercontent.com/87980985/213869197-2877f179-b16e-4eaa-be59-966ad2aabdb5.png)

**In this project i shows that how much impact weather conditions have in our day-today energy consumption in home. Whenever the atomospheric pressure is low or high, there's a evident change in the way enegry is consumed.**

## **Problem Statement**
We should predict Appliance energy consumption for a house based on factors like temperature, humidity & pressure . In order to achieve this, we need to develop a supervised learning models using regression algorithms. Regression algorithms are used as data consist of continuous features and there are no identification of appliances in dataset


## **Dataset description**
The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru) and merged together with the experimental data sets using the date and time column.

The dataset contains features like:



* **date**= time year-month-day hour:minute:second


* **lights** = energy use of light fixtures in the house in Wh (Drop this column)

* **T1** = Temperature in kitchen area, in Celsius

* **RH1**= Humidity in kitchen area, in %

* **RH2** = Humidity in living room area, in %

* **T3** = Temperature in laundry room area

* **RH3** = Humidity in laundry room area, in %


* **RH4** = Humidity in office room, in %

* **T5** = Temperature in bathroom, in Celsius

* **RH5** = Humidity in bathroom, in %



* **RH6** = Humidity outside the building (north side), in %

* **T7** = Temperature in ironing room , in Celsius

* **RH7**= Humidity in ironing room, in %


* **RH8**=Humidity in teenager room 2, in %

* **T9**= Temperature in parents room, in Celsius

* **RH9** = Humidity in parents room, in %

* **Wind speed** (from Chievres weather station), in m/s

* **Visibility** (from Chievres weather station), in km

* **Tdewpoint** (from Chievres weather station), Â°C

* **rv1** = Random variable 1, nondimensional

* **rv2** = Random variable 2, nondimensional

* **T2** = Temperature in living room area, in Celsius

* **T4** = Temperature in office room, in Celsius

* **T6** = Temperature outside the building (north side), in Celsius

* **T8** = Temperature in teenager room 2, in Celsius

* **To** = Temperature outside (from Chievres weather station), in Celsius

* **Pressure** =(from Chievres weather station), in mm Hg

* **RH_out**=Humidity outside (from Chievres weather station), in %

**Target Variable :**

* **Appliances** = energy use in Wh (Dependent variable)

Where indicated, hourly data (then interpolated) from the nearest airport weather station(Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis,rp5.ru. Permission was obtained from Reliable Prognosis for the distribution of the 4.5 months of weather data.

---

## **Conclusion**

**The household appliance energy consumption prediction models based on Linear Regression, Lasso & Ridge, SVM, GBM and XGB are explored. First, we study the preprocessing of data, remove some features in the filtered data and normalize the data. Second, the grid search method is used to determine the optimal parameters in the model, and the models based on different machine learning methods are established. Finally, the prediction performance of each model was evaluated and compared. The results show that among the four prediction models established by the traditional machine learning method, SVM can achieve good results in the training set and the testing set, with the best prediction performance.GBM and XGB has the worst performance in the training set. The four models based on traditional machine learning are all relatively average in predicting performance. The prediction performance of the model based on SVM is much better than that of the model based on traditional machine learning, and the predicted value of SVM model is very close to the real value, it has advantages in terms of household appliance energy consumption prediction.**


## **References**

https://medium.com/analytics-vidhya/appliances-energy-prediction-2562af6ad3d9

https://www.academia.edu/48852012/Appliance_Energy_Prediction_Using_Time_Series_Forecasting_A_comparative_analysis_of_different_Machine_Learning_Algorithms

https://iopscience.iop.org/article/10.1088/1742-6596/1453/1/012064/pdf
